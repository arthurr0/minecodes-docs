# 📝 Developers

### Maven configuration

#### Repository

```xml
<repository>
  <id>minecodes-repository-releases</id>
  <name>mineCodes Organization</name>
  <url>https://repository.minecodes.pl/releases</url>
</repository>
```

#### Dependency

```xml
<dependency>
    <groupId>pl.minecodes.mineplots</groupId>
    <artifactId>minePlots-api</artifactId>
    <version>1.1</version>
    <scope>provided</scope>
</dependency>
```

### Main class

```java
public final class PlotsApiExample extends JavaPlugin {

    private ApiPlotService apiPlotService;

    @Override
    public void onEnable() {
        this.setupPlotService();

        PluginManager pluginManager = Bukkit.getPluginManager();
        pluginManager.registerEvents(new BlockPlaceListener(apiPlotService), this);
    }

    public void setupPlotService() {
        if (!Bukkit.getServer().getPluginManager().isPluginEnabled("minePlots")) {
            Bukkit.getLogger().severe("Disabled due to no minePlots dependency found!");
            Bukkit.getPluginManager().disablePlugin(this);
            return;
        }

        RegisteredServiceProvider<ApiPlotService> serviceProvider = Bukkit.getServicesManager().getRegistration(ApiPlotService.class);
        Objects.requireNonNull(serviceProvider, "Service provider is null!");

        apiPlotService = serviceProvider.getProvider();
    }
}
```

### Example using

```java
public class BlockPlaceListener implements Listener {

    private final ApiPlotService apiPlotService;

    public BlockPlaceListener(ApiPlotService apiPlotService) {
        this.apiPlotService = apiPlotService;
    }

    @EventHandler
    public void onPlace(BlockPlaceEvent event) {
        Player player = event.getPlayer();
        Block blockPlaced = event.getBlockPlaced();
        ApiPlot plot = this.apiPlotService.getPlot(blockPlaced.getLocation());

        if (plot == null) {
            player.sendMessage("There is no plot at this location.");
        } else {
            OfflinePlayer offlinePlayer = Bukkit.getOfflinePlayer(plot.getOwner());
            player.sendMessage(String.format("There is a plot named %s owned by %s", plot.getName(), offlinePlayer.getName()));
        }
    }
}
```


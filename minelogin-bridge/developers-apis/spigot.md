# 📔 Spigot

### Maven configuration

> Repository

```xml
<repository>
  <id>minecodes-repository-releases</id>
  <name>mineCodes Organization</name>
  <url>https://repository.minecodes.pl/releases</url>
</repository>
```

> Dependency

```xml
<dependency>
    <groupId>pl.minecodes.minelogin</groupId>
    <artifactId>spigot-api</artifactId>
    <version>0.0.1</version>
</dependency>
```

#### Events

* CaptchaMapGiveEvent
* PlayerSuccessLoginEvent
* PlayerSuccessRegisterEvent
* SetHubSpawnEvent
* SetLoginLocationEvent
* TeleportToLastLocationEvent

#### Get UserManager instance

```java
public class mineLoginAddon extends JavaPlugin {

    private UserManager userManager;

    @Override
    public void onEnable() {
        this.setupManager();
    }

    public void setupManager() {
        if (!Bukkit.getServer().getPluginManager().isPluginEnabled("mineLogin-spigot")) {
            Bukkit.getLogger().severe("Disabled due to no mineLogin-spigot dependency found!");
            Bukkit.getPluginManager().disablePlugin(this);
            return;
        }

        RegisteredServiceProvider<UserManager> serviceProvider = Bukkit.getServicesManager().getRegistration(UserManager.class);
        userManager = serviceProvider.getProvider();
    }

    public UserManager getUserManager() {
        return userManager;
    }
}
```

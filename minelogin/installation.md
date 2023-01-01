---
description: Here you can find how to install mineLogin plugin on your server.
---

# 🛠 Installation

### <mark style="color:blue;">Requirements</mark>

Prepare a server with a _**Velocity**_ or _**Bungeecord**_ engine and minimum one lobby server with _**Spigot**_ or fork engine.

### <mark style="color:blue;">BungeeGuard</mark>

To increase security, we recommend installing the [**BungeeGuard** ](https://www.spigotmc.org/resources/bungeeguard.79601/)plugin on all of your sub-servers so that no one can bypass your proxy.

### <mark style="color:blue;">Uploading files</mark>

You must choose the appropriate files to upload to your servers. On the proxy server (_**Velocity**_ or _**Bungeecord**_), you should upload a file that has the name of your engine in the file name, e.g. _**mineLogin-1.5.1-velocity-public.jar**_. On the lobby servers, you should upload the file _**mineLogin-1.5.1-spigot-bridge.jar**_. To get the bridge on the lobby server to work, you should also upload the [**ProtocolLib**](https://www.spigotmc.org/resources/protocollib.1997/) **** plugin.

### <mark style="color:blue;">First start-up</mark>

During the first start-up of the proxy server, the plugin will automatically shut down the server after loading the files. You should then proceed to the first plugin configuration described below.

### <mark style="color:blue;">First configuration</mark>

In the initial configuration, you should only focus on the plugin that was uploaded to the proxy server (_**Velocity**_** ** or _**Bungeecord**_). In the plugins folder, find the folder named **mineLogin** and then open the file **configuration.yml** located in that folder.&#x20;

As the first point, you should provide your license that you received from mineCodes, find the field **license:** and fill it in with your key.&#x20;

Then you should decide which database you want to use, we have 4 different types of databases (_FLAT, H2, MYSQL, MONGODB_), the first three types of databases are saved in files on the server and do not require any login information.

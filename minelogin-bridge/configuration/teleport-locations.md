---
description: Here you can set the location of the hub
---

# 🎥 Teleport locations

{% hint style="info" %}
![🇺🇸](https://twemoji.maxcdn.com/2/svg/1f1fa-1f1f8.svg) It allows you to set the teleportation location when you enter your server, and you can also configure the location for logging in.
{% endhint %}

{% hint style="info" %}
![🇵🇱](https://twemoji.maxcdn.com/2/svg/1f1f5-1f1f1.svg) Umożliwia ustalenie lokalizacji teleportacji po wejściu na twój serwer oraz również możesz skonfigurować lokalizacje do logowania.
{% endhint %}

```yaml
#PL: Konfiguracja lokalizacji hub.
#EN: Configuration hub location.
hub-spawn:
  #PL: Czy gracz po wejściu na serwer ma być teleportowany na lokalizacje podaną poniżej.
  #EN: Does the player, upon entering the server, have to be teleported to the location given below.
  enabled: true
  #PL: Lokalizacja teleportacji po wejściu na serwer.
  #EN: Location of teleportation after entering the server.
  location: 'world:10.5:60.0:12.5:90.0:0.0:'
#PL: Konfiguracja lokalizacji do logowania się.
#EN: Configuration location for login in.
before-login-location:
  #PL: Graczy gracz przed zalogowaniem się ma być teleportowany na podaną po niżej lokalizacje a po zalogowaniu się wracać na poprzednią?
  #EN: The player is teleported to the location specified below before logging in and then returned to the previous location after logging in?
  enabled: true
  #PL: Lokalizacja teleportacji przed zalogowaniem się.
  #EN: Location of teleportation before logging in.
  location: 'world:10.5:60.0:12.5:90.0:0.0:'
```

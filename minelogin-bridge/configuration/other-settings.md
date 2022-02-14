---
description: Settings for assigning effects or hiding players
---

# ⚙ Other settings

{% hint style="info" %}
![🇺🇸](https://twemoji.maxcdn.com/2/svg/1f1fa-1f1f8.svg) In this section you will find options to configure if the plugin should hide player's items before login, if it should hide players or if it should get a blidness effect
{% endhint %}

{% hint style="info" %}
![🇵🇱](https://twemoji.maxcdn.com/2/svg/1f1f5-1f1f1.svg) W tym punkcie znajdziesz opcje do konfiguracji czy plugin ma ukrywać przedmioty gracza przed zalogowaniem, czy ma ukrywać graczy lub czy ma otrzymać efekt blidness
{% endhint %}

```yaml
#PL: Czy plugin ma ukrywać przedmioty gracza przed zalogowaniem.
#UWAGA: Gracz może utracić itemy przy crashu serwera, opcja niezalecana jeśli sieć nie posiada lobby
#EN: Should the plugin hide the player's items before logging in
#NOTE: Player may lose items when server crashes, option not recommended if network does not have a lobby
hide-items-before-login: false
#PL: Czy plugin ma ukrywać graczy przed zalogowaniem.
#EN: Is the plugin supposed to hide players from logging in.
hide-player-before-login: true
#PL: Czy gracz ma otrzymać efekt Blidness przed zalogowaniem.
#EN: Whether the player should receive the Blidness effect before logging in.
give-blindness-before-login: true
```

# 🖨 Notifications title

{% hint style="info" %}
![🇺🇸](https://twemoji.maxcdn.com/2/svg/1f1fa-1f1f8.svg) Do you want on-screen captions to appear when you try to log in, register or have a premium session? Configure this option!
{% endhint %}

{% hint style="info" %}
![🇵🇱](https://twemoji.maxcdn.com/2/svg/1f1f5-1f1f1.svg) Chcesz aby podczas próby zalogowania, rejestracji lub sesji premium pojawiały się napisy na ekranie? Skonfiguruj tą opcje!
{% endhint %}

```yaml
notifications-title:
  #PL: Czy powiadomienia title mają być włączone.
  #EN: Whether title notifications should be enabled.
  enabled: true
  #PL: Ile sekund ma pojawiać.
  #EN: How many seconds should appear.
  fade-in: 1
  #PL: Ile sekund ma znikać.
  #EN: How many seconds should disappear.
  fade-out: 1
  #PL: Ile sekund ma pozostać na ekranie.
  #EN: How many seconds should remain on the screen.
  stay: 3
  notification-title: '<color:#ffaf05><bold>m</color:#ffaf05><color:#ffb307> </color:#ffb307><color:#ffb709>i</color:#ffb709><color:#ffba0a>
    </color:#ffba0a><color:#ffbe0c>n</color:#ffbe0c><color:#ffc20e> </color:#ffc20e><color:#ffc610>e</color:#ffc610><color:#ffca11>
    </color:#ffca11><color:#ffce13>L</color:#ffce13><color:#ffd115> </color:#ffd115><color:#ffd517>o</color:#ffd517><color:#ffd918>
    </color:#ffd918><color:#ffdd1a>g</color:#ffdd1a><color:#ffe11c> </color:#ffe11c><color:#ffe51e>i</color:#ffe51e><color:#ffe81f>
    </color:#ffe81f><color:#ffec21>n</color:#ffec21></bold> '
  success-premium-login: <dark_gray>[</dark_gray><gold>#</gold><dark_gray>]</dark_gray>
    <green>Success premium logged in!
  success-session-login: <dark_gray>[</dark_gray><gold>#</gold><dark_gray>]</dark_gray>
    <green>Success session logged in!
  success-cracked-login: <dark_gray>[</dark_gray><gold>#</gold><dark_gray>]</dark_gray>
    <green>Success cracked logged in!
  success-register: <dark_gray>[</dark_gray><gold>#</gold><dark_gray>]</dark_gray>
    <green>Success account register.
  need-registered: <dark_gray>[</dark_gray><gold>#</gold><dark_gray>]</dark_gray>
    <green>You are need register.
  need-logged: <dark_gray>[</dark_gray><gold>#</gold><dark_gray>]</dark_gray> <green>You
    are need login in.
```

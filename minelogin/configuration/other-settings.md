# ⚙ Other settings

{% hint style="info" %}
<img src="https://twemoji.maxcdn.com/2/svg/1f1fa-1f1f8.svg" alt="🇺🇸" data-size="line"> Here you can configure other settings such as whether captcha should be enabled, where it should be displayed, whether the lobby command should work or the login time
{% endhint %}

{% hint style="info" %}
<img src="https://twemoji.maxcdn.com/2/svg/1f1f5-1f1f1.svg" alt="🇵🇱" data-size="line"> W tym miejscu możesz skonfigurować inne ustawienia: np. czy captcha ma być włączona, gdzie ma się wyświetlać, czy komenda lobby ma działać lub czas logowania
{% endhint %}

```yaml
other-settings:
  #PL: Czy podczas rejestracji ma być wymagany kod captcha?
  #EN: Should a captcha code be required during registration?
  captcha: true
  #PL: Czy captcha ma być pokazana na chacie czy na mapie.
  #EN: Whether the captcha should be shown on the chat or on the map.
  #Options: CHAT, MAP
  captcha-type: CHAT
  #PL: Czy korzystasz z mostu do serwera spigot?
  #EN: Are you using a bridge to the spigot server?
  use-spigot-bridge: false
  #PL: Czy komend /lobby ma być włączona?
  #EN: Should the /lobby command be enabled?
  enabled-lobby-command: true
  #PL: Włączenie tej opcji umożliwia graczom nie tracić przedmiotów podczas zmiany logowania z non-premium na premium.
  #EN: Enabling this option allows players not to lose items when switching from cracked to premium authentication.
  offline-unique-id-system: false
  #PL: Ta opcja chroni nazwy kont premium, dzięki czemu gracz non-premium nie może zająć nicku premium.
  #EN: This option protects premium account names so that a cracked player cannot take a premium nickname.
  premium-nicknames-protected: true
  #PL: Ile czasu gracz ma na rejestracje lub logowanie?
  #EN: How much time does a player have to register or log in?
  #Format: 1d, 1h, 1m or 1s
  login-timeout: 30s
  #PL: Czas trwania sesji logowania gracza non-premium.
  #EN: The duration of a cracked player's login session.
  #Format: 1d, 1h, 1m or 1s
  session-active-time: 3d
  #PL: Co ile sekund ma powtarzać się komenda logowania lub rejestrowania.
  #EN: Every how many seconds you want the login or logging command to repeat.
  commands-repeat: 5
  #PL: Regex dla dozwolonych nikców.
  #EN: The duration of a cracked player's login session.
  #Format: 1d, 1h, 1m or 1s
  nickname-allowed-regex: '[a-zA-Z0-9_]+'
  #PL: Komendy dostępne dla gracza przed zalogowaniem.
  #EN: Commands list available before player login in.
  available-commands-before-login:
  - login
  - register
  - l
  - reg
  - restore
  - recovery
  - recoveryaccount
```

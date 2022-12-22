# 🎈 Bossbar settings

{% hint style="info" %}
<img src="https://twemoji.maxcdn.com/2/svg/1f1fa-1f1f8.svg" alt="🇺🇸" data-size="line"> Sets the bossbar's functions when logging in or setting a password. You can set its color, options or messages
{% endhint %}

{% hint style="info" %}
<img src="https://twemoji.maxcdn.com/2/svg/1f1f5-1f1f1.svg" alt="🇵🇱" data-size="line"> Ustawia funkcje bossbara podczas logowania lub ustalania hasła. Możesz w nim ustawić jego kolor, opcje lub wiadomości
{% endhint %}

```yaml
boss-bar-commands:
  #PL: Czy pokazywanie komend na boss bar ma być włączone?
  #EN: Should the command display on the boss bar be turned on?
  enabled: true
  #PL: Kolor BossBara.
  #EN: BossBar color.
  color: YELLOW
  #PL: Styl BossBara.
  #EN: BossBar style.
  #Options: PROGRESS, NOTCHED_6, NOTCHED_10, NOTCHED_12, NOTCHED_20
  overlay: PROGRESS
  #PL: Wiadomość jeśli gracz potrzebuje się zalogować.
  #EN: Message for player if he is need login in.
  login-command: <gold>Use login command:</gold> <yellow>/login <password> {2fa}
  #PL: Wiadomość jeśli gracz potrzebuje się zarejestrować.
  #EN: Message for player if he is need register.
  register-command: <gold>Use login command:</gold> <yellow>/register <password> <password>
    {captcha}
```


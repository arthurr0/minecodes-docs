# 馃獌 Login servers

{% hint style="info" %}
![馃嚭馃嚫](https://twemoji.maxcdn.com/2/svg/1f1fa-1f1f8.svg) This function allows you to specify the server on which players will log in, whether the server should be automatically activated after restart or to which server it should move after the player logs in
{% endhint %}

{% hint style="info" %}
![馃嚨馃嚤](https://twemoji.maxcdn.com/2/svg/1f1f5-1f1f1.svg) Funkcja ta pozwala ustali膰 serwer na kt贸rym b臋d膮 logowa膰 si臋 gracze, czy serwer ma si臋 automatycznie w艂膮cza膰 po restarcie lub na jaki serwer ma przenosi膰 po zalogowaniu.
{% endhint %}

```yaml
servers:
  #PL: Serwery na kt贸rych gracze maj膮 si臋 logowa膰.
  #EN: Servers on which players are to log in.
  login-servers:
  - lobby
  #PL: Czy gracze po wyrzuceniu z jednego z serwer贸w na sieci maj膮 by膰 przenoszeni na serwer
  # awaryjny. (Zale偶nie czy jest w艂膮czona opcja poni偶ej s膮 przenoszeni na serwer logowania lub po zalogowaniu)
  #EN: Should players be moved to a fallback server after being kicked from one of the servers
  # on the network. (Depending on whether the option below is enabled they are moved to the login server or after login)
  fallback-server: true
  #PL: Czy gracze maj膮 by膰 przenoszeni na jeden z serwer贸w podanych poni偶ej po zalogowaniu.
  #EN: Have players be moved to one of the servers listed below upon login.
  change-server-after-login: false
  #PL: Serwery na kt贸re gracze maj膮 by膰 przeniesieni po zalogowaniu.
  #EN: Servers to which players are to be transferred upon login.
  after-login-servers:
  - survival
  - skyblock
```


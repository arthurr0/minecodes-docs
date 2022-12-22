# 🪃 Login servers

{% hint style="info" %}
<img src="https://twemoji.maxcdn.com/2/svg/1f1fa-1f1f8.svg" alt="🇺🇸" data-size="line"> This function allows you to specify the server on which players will log in, whether the server should be automatically activated after restart or to which server it should move after the player logs in
{% endhint %}

{% hint style="info" %}
<img src="https://twemoji.maxcdn.com/2/svg/1f1f5-1f1f1.svg" alt="🇵🇱" data-size="line"> Funkcja ta pozwala ustalić serwer na którym będą logować się gracze, czy serwer ma się automatycznie włączać po restarcie lub na jaki serwer ma przenosić po zalogowaniu.
{% endhint %}

```yaml
servers:
  #PL: Serwery na których gracze mają się logować.
  #EN: Servers on which players are to log in.
  login-servers:
  - lobby
  #PL: Czy gracze po wyrzuceniu z jednego z serwerów na sieci mają być przenoszeni na serwer
  # awaryjny. (Zależnie czy jest włączona opcja poniżej są przenoszeni na serwer logowania lub po zalogowaniu)
  #EN: Should players be moved to a fallback server after being kicked from one of the servers
  # on the network. (Depending on whether the option below is enabled they are moved to the login server or after login)
  fallback-server: true
  #PL: Czy gracze mają być przenoszeni na jeden z serwerów podanych poniżej po zalogowaniu.
  #EN: Have players be moved to one of the servers listed below upon login.
  change-server-after-login: false
  #PL: Serwery na które gracze mają być przeniesieni po zalogowaniu.
  #EN: Servers to which players are to be transferred upon login.
  after-login-servers:
  - survival
  - skyblock
```


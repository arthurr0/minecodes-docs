# 🔑 Limit management

{% hint style="info" %}
<img src="https://twemoji.maxcdn.com/2/svg/1f1fa-1f1f8.svg" alt="🇺🇸" data-size="line"> Here you can limit the maximum number of accounts for a given ip player or set the maximum number of login attempts.
{% endhint %}

{% hint style="info" %}
<img src="https://twemoji.maxcdn.com/2/svg/1f1f5-1f1f1.svg" alt="🇵🇱" data-size="line"> W tym miejscu możesz ograniczyć maksymalną ilość kont dla danego ip gracza albo ustalić maksymalną ilość prób logowania.
{% endhint %}

```yaml
limits:
  #PL: Maksymalna ilośc kont zarejestrowana na jeden adres ip.
  #EN: Maximum number of accounts registered to one ip address.
  accounts-per-address: 2
  #PL: Maksymalna ilość prób logowania.
  #EN: Maximum number of login attempts.
  login-attempts: 3
```

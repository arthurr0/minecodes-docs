# 📂 Cache systems

{% hint style="info" %}
![🇺🇸](https://twemoji.maxcdn.com/2/svg/1f1fa-1f1f8.svg) This section allows you to configure user caching. What is caching? Caching is a plugin cache. It saves for example player session time.
{% endhint %}

{% hint style="info" %}
![🇵🇱](https://twemoji.maxcdn.com/2/svg/1f1f5-1f1f1.svg) Ten punkt umożliwia konfiguracje cachowania użytkowników. Czym jest cachowanie? Cachowanie to inaczej pamięć podręczna pluginu. Zapisują on np. czas sesji gracza..
{% endhint %}

```yaml
cache:
  #PL: Po jakim czasie user ma być usunięty z cachu od momentu ostatniego użycia go. Czas podany w minutach.
  #EN: After how long the user should be removed from the cache since the last time he used it. Time in minutes.
  expire-after-access: 30
  #PL: Maksymalna ilość userów w cachu. Pod przekroczeniu ten liczby nadpisują się za starszych.
  #EN: Maximum number of users in cache. If this number is exceeded, the older users are overwritten.
  maximum-pool: 150
```

# 💽 Geo location

{% hint style="info" %}
<img src="https://twemoji.maxcdn.com/2/svg/1f1fa-1f1f8.svg" alt="🇺🇸" data-size="line"> Sets whether to enable ip address geo-localization. You can find a list of all available countries for configuration [here](https://en.wikipedia.org/wiki/ISO\_3166-1)
{% endhint %}

{% hint style="info" %}
<img src="https://twemoji.maxcdn.com/2/svg/1f1f5-1f1f1.svg" alt="🇵🇱" data-size="line"> Umożliwia ustalenie, czy geo lokazliacja adresów ip ma zostać włączona. Listę wszystkich dostępnych krajów do konfiguracji znajdziesz właśnie [tutaj](https://en.wikipedia.org/wiki/ISO\_3166-1)
{% endhint %}

```yaml
geo-location:
  #PL: Czy geo lokalizacja adresów ip ma być włączona?
  #EN: Should ip address geo localization be enabled?
  enabled: false
  #PL: Krajowe kody iso.
  #EN: Country iso codes.
  #List: https://en.wikipedia.org/wiki/ISO_3166-1
  available-countries:
  - PL
  - FR
  - EN
  - US
```

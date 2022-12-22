---
description: Here you will find QR map configurations
---

# 📜 Maps QR (2fa)

{% hint style="info" %}
<img src="https://twemoji.maxcdn.com/2/svg/1f1fa-1f1f8.svg" alt="🇺🇸" data-size="line"> Here you can configure the display maps to show the CAPTCHA code during registration and maps 2fa to scan the QR code in Google Authenticator or other app.
{% endhint %}

{% hint style="info" %}
<img src="https://twemoji.maxcdn.com/2/svg/1f1f5-1f1f1.svg" alt="🇵🇱" data-size="line"> W tym miejscu możesz skonfigurować funkcje wyświetlania mape ukazującą kod CAPTCHA podczas rejestracji oraz mape 2fa dzięki której można zeskanować kod QR w aplikacji Google Authenticator i innych.
{% endhint %}

```yaml
#PL: Konfiguracja slotów map.
#EN: Configuration for maps slots.
maps:
  #PL: Miejsce na pasku szybkiego dostepu do pojawiania się mapy z kodem QR.
  #EN: Slot on HotBar for map with QR code. (2FA)
  qr-code-map-slot: 1
  #PL: Miejsce na pasku szybkiego dostępu do pojawiania się mapy z kodem captcha.
  #EN: Slot on HotBar for map with captcha code.
  captcha-map-slot: 3
```

> <img src="https://twemoji.maxcdn.com/2/svg/1f1fa-1f1f8.svg" alt="🇺🇸" data-size="line"> What is Google Authenticator is a software-based two-step authentication token created by Google. The application generates six digits that you must enter when signing in along with your login and password to Google services.\
> \
> <img src="https://twemoji.maxcdn.com/2/svg/1f1f5-1f1f1.svg" alt="🇵🇱" data-size="line"> Czym jest Google Authenticator to programowy token uwierzytelniania dwuetapowego, stworzony przez Google. Aplikacja generuje sześć cyfr, które należy podać podczas logowania razem z loginem i hasłem do usług Google.

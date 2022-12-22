# ⏳ Passwords security

{% hint style="info" %}
<img src="https://twemoji.maxcdn.com/2/svg/1f1fa-1f1f8.svg" alt="🇺🇸" data-size="line"> In this section you can set how passwords should be encoded, which passwords are disabled or the minimum length of the password!
{% endhint %}

{% hint style="info" %}
<img src="https://twemoji.maxcdn.com/2/svg/1f1f5-1f1f1.svg" alt="🇵🇱" data-size="line"> W tym punkcie możesz ustawić w jaki sposób mają być kodowane hasła, jakie hasła są wyłączone lub jaką długość minimalnie powinno mieć hasło!
{% endhint %}

```yaml
passwords-security:
  #PL: Jakiego algorytmu hashowania ma używać plugin.
  #EN: What hashing algorithm should the plugin use.
  #Options: BCRYPT, SHA512, SHA256 and MD5
  hash-type: BCRYPT
  #PL: Czy hasła mają być dodatkowo zabezpieczone salt.
  #EN: Whether passwords should be additionally protected with salt.
  salt-for-passwords: false
  #PL: Minimalna długość hasła która gracz musi ustawić.
  #EN: The minimum password length that a player must set.
  minimum-password-length: 6
  #PL: Lista niedozwolonych haseł.
  #EN: List of disallowed passwords.
  disallowed-passwords:
  - password
  - password123
  - haslo123
  - haslo1
  - dick123
  - pussy1
  - pussy123
```

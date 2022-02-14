# 📧 E-Mail system

{% hint style="info" %}
![🇺🇸](https://twemoji.maxcdn.com/2/svg/1f1fa-1f1f8.svg) This feature allows you to send custom mails to other players on the server to recover your password
{% endhint %}

{% hint style="info" %}
![🇵🇱](https://twemoji.maxcdn.com/2/svg/1f1f5-1f1f1.svg) Ta funkcja umożliwia wysyłanie customowych maili do innych graczy serwera którzy w celu odzyskania hasła je otrzymują
{% endhint %}

```yaml
mailing:
  #PL: Czy system mailingowy ma być włączony?
  #EN: Is the mailing system to be enabled?
  enabled: false
  #PL: Ostrzeżenie wyświetlane, gdy do konta nie został przypisany żaden adres e-mail.
  #EN: Warning displayed when no email address has been assigned to the account.
  email-warning: true
  #PL: Nazwa twojego serwera w emailu.
  #EN: Server name in email.
  server-name: YourAddress.net
  #PL: Adres z którego będzie wysyłany email.
  #EN: Sender email address.
  sender-email: recovery@youraddress.net
  #PL: Adres serwera mailingowego.
  #EN: Mailing server address.
  server: smtp.sendgrid.net
  #PL: Port do serwera mailingowego.
  #EN: Mailing server port.
  port: 587
  #PL: Nazwa użytkownika do serwera mailongowego.
  #EN: Username for mailing server.
  username: apikey
  #PL: Hasło użytkownika do serwera mailongowego.
  #EN: Password for mailing server.
  password: securePassword
  #PL: Tytuł wysłanego emaila.
  #EN: Email title.
  email-title: Account recovery on YourAddress.net
```

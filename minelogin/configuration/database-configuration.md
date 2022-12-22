# 📑 Database configuration

{% hint style="info" %}
<img src="https://twemoji.maxcdn.com/2/svg/1f1fa-1f1f8.svg" alt="🇺🇸" data-size="line"> The **mineLogin** plugin contains two types of data storage. This is MySQL and Flat
{% endhint %}

{% hint style="info" %}
<img src="https://twemoji.maxcdn.com/2/svg/1f1f5-1f1f1.svg" alt="🇵🇱" data-size="line"> Plugin **mineLogin** zawiera dwa rodzaje zapisu danych. Jest to zapis MySQL oraz Flat&#x20;
{% endhint %}

> **Section in config MySQL Database:**

```yaml
database:
  #PL: Typ bazy danych.
  #EN: Dmtabase type.
  #Options: MYSQL, FLAT
  data-type: MYSQL
  #PL: Adres twojej bazy danych.
  #EN: Address for your database.
  hostname: localhost
  #PL: Port twojej bazy danych.
  #EN: Port for your database.
  port: 3306
  #PL: Użytkownik twojej bazy danych.
  #EN: Username for your database.
  username: root
  #PL: Hasło dostępu do twojej bazy danych.
  #EN: Password for your database.
  password: securepass
  #PL: Baza w której ma stworzyć się tabela mineLogin.
  #EN: Base where mineLogin create table.
  base: mineLogin
  #PL: Włącz w przypadku gdy twoja baza korzysta z SSL.
  #EN: Enable when your database use SSL.
  sll-use: false
  #PL: Parametr HikariCP dla maksymalnego czasu życia połączenia.
  #EN: HikariCP parameter for max life time connection.
  max-life-time: 1800000
  #PL: Parametr HikariCP dla maksymalnego rozmiaru puli.
  #EN: HikariCP parameter for max pool size.
  max-pool-size: 20
  #PL: Wyłącz gdy nie chcesz dostawać informacji o zerwanym połączeniu z bazą danych.
  #EN: Turn it off when you don't want to receive information about a broken connection to the database.
  show-mysql-errors: true
  #PL: Czas oczekiwania na połączenie.
  #EN: Connection timeout.
  connection-timeout: 3000
```

> **Section in config Flat (JSON):**

```yaml
database:
  #PL: Typ bazy danych.
  #EN: Dmtabase type.
  #Options: MYSQL, FLAT
  data-type: FLAT
```

{% hint style="warning" %}
<img src="https://twemoji.maxcdn.com/2/svg/1f1fa-1f1f8.svg" alt="🇺🇸" data-size="line"> This database type doesn't require any configuration, it's default from the first plugin launch. This type saves users in `plugins/mineLogin/usersData` folder, it is not recommended when creating larger server (+50 Players)
{% endhint %}

{% hint style="warning" %}
<img src="https://twemoji.maxcdn.com/2/svg/1f1f5-1f1f1.svg" alt="🇵🇱" data-size="line"> Ten typ bazy danych nie wymaga żadnej konfiguracji, jest on domyślny od pierwszego uruchomienia pluginu. Typ ten zapisuje użytkowników w folderze `/plugins/mineLogin/usersData`, nie jest on zalecany podczas tworzenia większych serwerów (+50 Graczy)
{% endhint %}


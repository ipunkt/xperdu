# Requirements

## Server

- PHP >= 5.6.0 (7.x would be better)
  - Extensions
    - required: reflection, pcre, spl, pdo, pdo_mysql, mcrypt, gd with FreeType Support or ImageMagick), OpenSSL, mb_string, json, curl, crypt() with BLOWFISH_CRYPT
    - optional: dom, iconv, imagemagick, simplexml
- MySQL >= 5.1.0 (or MariaDB)
- Apache or nginx
- min. 32 MB RAM
- min. 20 MB disk space (only for system)
- min. 1 MB database space

## Umgebung

- FTP-Zugang / SFTP-Zugang
  - Server
  - Benutzername
  - Password
  - Ordner für xperdu (optional)
- Datenbank
  - Server
  - Benutzername
  - Passwort
  - Datenbankname
  - Präfix für Tabellennamen (optional: falls nur einen Datenbank verfügbar ist sorgt der Präfix für eine Trennung zu anderen Tabellen in der gleichen Datenbank)
- Domain
  - Domain muss auf FTP-Ordner plus `/public` verweisen

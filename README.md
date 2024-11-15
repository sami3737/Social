# Social

## À propos

Social a été créé en 2020 et sert à lier son SteamID avec son DiscordID.

Une fois le lien fait, les joueurs ont la possibilité de récupérer leurs récompenses dans le jeu.

## Table des matières

- [À propos](#à-propos)
- [Prérequis](#prérequis)
- [Installation](#installation)
- [Outils](#outils)
- [Auteurs](#auteurs)
- [Licence](#Licence)

### Prérequis

  -[MySQL](https://www.mysql.com/)
  
  -[PHP7](https://www.php.net/releases/index.php)
  
  -[Apache](https://httpd.apache.org/)

  -[Discord](https://discord.com/)

### Installation

-Installer et configurer votre serveur Apache ou faite votre propre installation MySQL/PHP.

-Configurer les fichiers web suivants:

[Discord](./website/api/discord/setting.php)

[MySQL](./website/api/mysql/settings.ini.php)

[Steam](./website/api/steam/apikey.php)

[Website Identity](./website/api/login.php) ligne 5

-Configurer le plugin côté serveur

## Outils

  *Notepad++
  *PHPMyAdmin
  *Visual Studio

## Auteurs
* **Samuel Boutin** _alias_ [@sami3737](https://github.com/sami3737)

## Licence

Ce projet est sous licence ``MIT License`` - voir le fichier [LICENSE](LICENCE.md) pour plus d'informations

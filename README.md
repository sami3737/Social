# Social

## À propos

Social a été créé en 2020 et permet de lier un SteamID avec un DiscordID.

Une fois le lien effectué, les joueurs ont la possibilité de récupérer leurs récompenses dans le jeu.

## Table des matières

- [À propos](#à-propos)
- [Prérequis](#prérequis)
- [Installation](#installation)
- [Outils](#outils)
- [Auteurs](#auteurs)
- [Licence](#licence)

## Prérequis

Avant d’installer Social, assurez-vous d’avoir :

- [MySQL](https://www.mysql.com/)
- [PHP 7](https://www.php.net/releases/index.php)
- [Apache](https://httpd.apache.org/)
- [Discord](https://discord.com/) (pour l’intégration des identifiants Discord)

## Installation

1. Installer et configurer votre serveur Apache ou réaliser votre propre installation MySQL/PHP.
2. Configurer les fichiers web suivants :
   - [Discord](./website/api/discord/setting.php)
   - [MySQL](./website/api/mysql/settings.ini.php)
   - [Steam](./website/api/steam/apikey.php)
   - [Website Identity](./website/api/login.php) (ligne 5)
3. Configurer le plugin côté serveur.

## Outils

- [Notepad++](https://notepad-plus-plus.org/)
- [PHPMyAdmin](https://www.phpmyadmin.net/)
- [Visual Studio](https://visualstudio.microsoft.com/)

## Auteurs

- **Samuel Boutin** _alias_ [@sami3737](https://github.com/sami3737)

## Licence

Ce projet est sous licence **MIT License** - voir le fichier [LICENSE](LICENSE.md) pour plus d'informations.

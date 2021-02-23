# Kit Laravel 8 Docker

## Conteneur
- nginx
- php-fpm 8 (php 8)
- MariaDB
- PhpMyAdmin
- MailDev

# Installation
Pour démarrer docker et se connecter avec le conteneur:
`docker-compose up --build`<br/><br/>
Pour Créer le projet Laravel:<br/>
- Créer le répertoire app: `mkdir app`
- `docker-compose exec web bash`
- `composer create-project laravel/laravel .`
- `chmod -R 777 .`

# Prêt!
- `http://localhost`
- `http://localhost:8081/` (phpmyadmin)
- `http://localhost:1500/` (maildev)

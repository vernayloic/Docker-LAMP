Créer un dossier au nom du projet qui contient l'ensemble du pack soit :

    - Docker-compose.yml
    - .env
    - Répertoire "www"
    - Le dossier image de PHP "Myphp"

Dans le Dossier "Myphp"

    Le DockerFile permet de créer une image PHP
    -> Possiblité de choisir la version et d'ajouter des extentions 

Le fichier ".env" 

    Permet de choisir les variables du projet, ports, intentifiants etc... 

Avec un accès SSH (ou autre) accèder au repertoire du projet puis lancer :

    docker-compose up 

L'éxécution de la commande vas lancer la création de trois Dockers :

    X_php_1
    X_db_1
    X_phpmyadmin_1
    
X représente le nom du dossier parent du docker-compose.yml

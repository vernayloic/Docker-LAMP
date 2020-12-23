Créer un dossier au nom du projet qui contient l'enssemble du pack soit :

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


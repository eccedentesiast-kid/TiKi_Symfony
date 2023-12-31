# Welcome to TiKi website - PHP Symfony Project
## Comment lancer l'application

- Après avoir `pull` le projet de github, téléchargez immédiatement tous les compositeurs dans le fichier `composer.json`
- Vérifiez ensuite si la base de données n'existe pas, définissez sa source de données sur le fichier db.sqlite et téléchargez le pilote sqlite.
- Ouvrez ensuite le terminal et exécutez la commande pour installer Docker, lancez votre projet:

  `docker-compose up -d --build`

- Ouvrez `localhost:8989` pour accéder à la page d'accueil de site Web TiKi


## Comment lancer la BDD

Exécuter la commande suivante dans un terminal dans le répertoire de base du projet :

`php .\bin\doctrine o:s:update --force --dump-sql`

Ensuite vous pouvez exectuer le fichier `data.sql` sur la base de données afin que la base de données ne soit pas vide. Vous pouvez ajouter d'autre données en respectant la diagramme UML (cf rapport)


## Les spécificités de votre projet 

Sur le site vous pouvez parcourir les différentes pages en cliquant sur la barre de navigation en haut du site web, vous pouvez également vous inscrire et vous connecter

## Quelques images du site web
![image](https://github.com/eccedentesiast-kid/TiKi_Symfony/assets/91082621/a127a84a-c275-4825-bec5-f8647415902c)
![image](https://github.com/eccedentesiast-kid/TiKi_Symfony/assets/91082621/2004aa6c-d9ef-4d94-a662-cac14017253b)
![image](https://github.com/eccedentesiast-kid/TiKi_Symfony/assets/91082621/1e2d3c44-dfdf-4950-8c58-bf1a93f6165e)
![image](https://github.com/eccedentesiast-kid/TiKi_Symfony/assets/91082621/3a6a8119-c791-4b9f-b6ff-f65d39fefaf3)
![image](https://github.com/eccedentesiast-kid/TiKi_Symfony/assets/91082621/ea8b5aa9-9859-49b9-adbc-ad8bbbb986b0)
![image](https://github.com/eccedentesiast-kid/TiKi_Symfony/assets/91082621/3c55cb28-bdc4-472b-aca6-1af6119d13cb)


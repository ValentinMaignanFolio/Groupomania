Création d'un réseau social pour l'entreprise Groupomania
REACTJS / NODE.JS / SEQUELIZE / MYSQL

1/ Cloner le projet

2/ Créer un dossier config à la racine du dossier server contenant un fichier config.json contenant le code ci-dessous :

{
"development": {
"username": "votre identifiant",
"password": "votre mot de passe",
"database": "nom de votre BDD",
"host": "hebergement de votre BDD",
"dialect": "mysql"
},
"test": {
"username": "root",
"password": null,
"database": "database_test",
"host": "127.0.0.1",
"dialect": "mysql"
},
"production": {
"username": "root",
"password": null,
"database": "database_production",
"host": "127.0.0.1",
"dialect": "mysql"
}
}

3/ Créer un fichier .env à la racine du dossier server et préciser la valeur de la variable d'environnement TOKEN

--> SECRET_TOKEN ="votre valeur"

4/ Côté serveur

--> npm install express
--> npm start

5/ Côté client

--> npm install --save-dev nodemon
--> npm start

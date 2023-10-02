# Projet Bookeo MVC
## Installation
* Vous devez tout d'abord créer un domaine local dans votre fichier hosts, puis modifier votre vhost d'Apache et redémarrer votre serveur.
* Dans votre dossier, récupérez les sources avec Git ou en les téléchargeant.
* Vous devez ensuite créer une base de données mysql et importer le fichier bookeo.sql.
* La base de données contient déjà un jeu de données avec également deux utilisateurs (un administrateur et un utilisateur) :
    * user@test.com, mot de passe : test (à ne pas utiliser sur un site en production :) )
    * admin@test.com, mot de passe : test (à ne pas utiliser sur un site en production :) )
* Modifiez le fichier db_config.php en y ajoutant les données de votre base de données.
* Assurez-vous que le site fonctionne en local.

## Contexte
Un prestataire a commencé à mettre en place le site Bookeo en utilisant une structure MVC. Ce site a pour but de permettre aux visiteurs de consulter des fichiers sur des livres, des bandes dessinées et des mangas, ainsi que de pouvoir commenter et noter ces fichiers.

## L'existant
La navigation et la connexion sont déjà terminées. Pour les pages en cours, le code HTML a déjà été ajouté dans les différentes pages du dossier templates.

## Les tâches restantes
* Terminer l'affichage d'un livre
* Terminer l'ajout et la modification d'un livre.
* Terminer l'affichage de la liste des livres (et gérer la pagination).
* Terminer l'affichage des trois derniers livres sur la page d'accueil.
* Terminer la création d'un compte utilisateur.
* Terminer l'ajout de commentaires.
* Terminer la possibilité de pouvoir noter un livre.

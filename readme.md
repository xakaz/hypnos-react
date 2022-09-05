***  GROUPE HYPNOS CHAINE HOTELIERE ***

Le site est la vitrine d'un groupe hotelier Hypnos.
Il permet à n'importe quel utilisateur connecté de réserver une suite pour une ou plusieurs nuits.
Les différents hôtels poosèdent plusieurs suites.
Une fois la suite réservée, l'utilisateur peut gérer sa suite dans son espace.
Les réservations y sont affichées dans 2 sections distinctes:
- les réservations en cours 
-l'historique des réservations

A moins de 72h de la date réservée, l'utilisateur n'a plus la possiblité d'annuler la réservation.

*** Outils ***
Front : React, bootstrap
Back : PHP, MySQL

*** PHP ***
Architecture MVC :
 - Model      : Appel en bdd
 - View       : Affichage des données
 - Controller : Lien entre le modèle et la vue

 index.php : routing pour les différents pages.

 *** React ***
 - router : routing dans app.js avec react-router-dom
 - routes : liens vers les pages containers
 - containers : JSX, components, state, functions 
 - components : templates (cards, footer, navbar,...) 
 - assets : medias
 - context : gérer les autorisations globalement avec react-context

 *** Base de données locale ***
copier/coller les commandes présentes dans "--SQLite.sql"
lier sa base de données au projet.

*** Auth ***
2 types d'authentification :
- USER
++++ Firebase ++++
  --> créer un compte firebase 
  --> authentification
  --> cliquez sur commencer
  --> Choisissez adresse e-mail/mot de passe
  --> cliquez activer e-mail/mot de passe
  --> barre latérale : vue d'ensemble du projet
  --> cliquez sur le logo </>
  --> entrez le pseudo de l'application
  --> récupérez les données dans le champ texte
  --> remplir les variables d'environnement dans .env.template. 
  --> Supprimer "_TEMPLATE" à la fin de la constante.
  --> trnasformer .env.tmeplate en .env

- ADMIN & MANAGERS
++++ Database ++++



*** DEPLOIEMENT EN LIGNE ***

  *** ACCES ADMINISTRATEUR ***
  adresse : "http://hypnoshernandez.alwaysdata.net/"

  *** ACCES GERANTS ***
  adresse : "http://hypnoshernandez.alwaysdata.net/"

  *** SITE ***
  adresse : "https://hypnos-studi.herokuapp.com/"




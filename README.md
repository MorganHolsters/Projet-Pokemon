# Projet-Pokemon
## Équipe
Ce projet  a été créé par Holsters Morgan, Parfondry Mickaël, Grégoire Nathan et Florian Hourelle de la classe 1TL1
## Description du projet
### Besoin du client 
Nous désirons une page web simulant un combat pokémon avec possibilité de sauver vos résultats
### Fonctionnalités principales
```
.Une page présentant le jeu et ses règles
.Possibilité de choisir le nom du joueur 
.Une page de combat de Pokémon permettant de choisir son attaque
.Une page de fin de partie victoire ou défaite
```
### Fonctionnalités secondaires
```
.Possibilité d'arrêter le combat en appuyant sur fuite
.Possibilié de récupérer les statistiques du joueur en fin de partie 
```
## Implémentation détaillée
### Implémentation: approche technique
1.*backend*: Une base de donée permettant de mémoriser les Pokémon et les joueurs
   Une table uilisateurs
      reprenant les champs du formulaire (nom, prénom, sexe, language préféré, mdp, victoire, défaite)
   Une table Pokémon
      avec les champs id, nom, sexe, pv_totaux
   table attaques
      avec les champs id, nomattq, dégats 
2.*backend*: Un serveur web capable de proposer les pages html, js et css ainsi que de proposer des webservices 
3.*backend*: 
   -Un webservice capable d'envoyer et de recevoir des données utilisateurs 
       retour: varchar
       nom: get_user_info
       paramètres: in username, in password
   -Un webservice capable d'envoyer les nom et les pv totaux du Pokémon
       nom: get_Pokémon
       paramètres: in nomPokémon,in pvTotaux
   -Un webservice capable de mettre à jour un tableau de scores
       retour: int
       paramètre: tinyint
       nom: get_score
   -Un webservice




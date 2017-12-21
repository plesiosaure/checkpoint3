# Checkpoint Décembre Paris promo sep2017

*Checkpoint NodeJS/React* - **4h**

![yeah christmas](https://media.giphy.com/media/11EjiLDatd0syA/giphy.gif)

## Fais ta liste au Père Noël !

Noël approche, pour ça je ne t'apprends rien,
le problème ici c'est que le Père Noël n'a pas encore reçu ta liste de cadeaux !

Tu imagines bien ce que tu vas devoir faire du coup ...

![type](https://media.giphy.com/media/RRerwvHrb0nxm/giphy.gif)


## Instructions

**Sans le forker**, clone le projet sur ton ordinateur.

Crée ensuite une branche portant ton prénom suivi de la première lettre de ton nom de famille et travaille dans cette branche. 
A la fin de l’exercice, il faudra faire un **push de cette branche** sur le remote. 

Le dépôt contient les répertoires suivants:
* `front/` : Le projet en React (généré _via_ `create-react-app`)
* `back/` : Le projet NodeJS (généré _via_ `express --pug --git`)

Regarde et **analyse bien** tous les répertoires et fichiers fournis !

Pense à faire le nécessaire pour installer tous les modules dans les deux dossiers (_via_ le `npm install`).

## Étape 1 - le back

Pour la partie back tu auras trois routes principales sur le `/` : 

* `GET /` : Récupération des cadeaux
* `POST /` : Création du cadeau 
* `DELETE /` : Suppression du cadeau 

Pour les données, tu as un fichier `/models/Gift.js`, tu peux repartir de ce fichier ou le supprimer, libre à toi de l'utiliser. Pour stocker les données, plusieurs solutions s'offrent à toi : 
* Une base MongoDB avec `Mongoose`
* Une base SQLite avec `Sequelize`
* Une base MySQL avec le module `MySQL`
* Un fichier json qui tu iras éditer _via_ le module `fs`

Si jamais tu places des identifiants pour ta BDD, pense bien à les mettre dans un fichier de configuration à part et à rajouter ce fichier au `.gitignore`

## Étape 2 - le front

Pour le front tu devras : 
* Afficher l'ensemble des cadeaux 
* Ajouter la possibilité d'ajouter un cadeau _via_ le formulaire présent
* Au clic sur la croix du cadeau, pouvoir le supprimer 



### Sympa une belle liste, mais l'idée, c'est quand même que Santa la reçoive non ?
  
* En utilisant NodeMailer, envoie un mail à ton Santa préféré, voilà son adresse: florian.pdf@gmail.com (pourquoi ne pas le spammer pour Noël ? ;) )
* Si jamais tu places des identifiants, pense bien à les mettre dans un fichier de configuration à part et à rajouter ce fichier au `.gitignore`


_Pour ce travail tu as 4h devant toi. Ce checkpoint n'est pas un examen, il va nous permettre de valider tes compétences, essaye donc de le faire au maximum de ton côté. 
Ce checkpoint est très consistant, si tu n'arrives pas à tout faire ce n'est pas grave, fais de ton mieux ;)_


![joy](https://media.giphy.com/media/26n62j7cS0aZOYCu4/giphy.gif)

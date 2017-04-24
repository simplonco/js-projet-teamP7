# js-proj-p7team

5 groupes de fonctionnalité à mettre en place

## Partie privée (seulement pour membre P7)

### En tant qu'apprenant de la promo 7, je veux créer un compte sur le site de la team P7.

### En tant qu'apprenant de la promo 7, je veux pouvoir me logger le temps de ma session de navigation

### En tant qu'apprenant de la promo 7, je veux saisir mes competence en auto-completion

### En tant qu'apprenant de la promo 7, je veux créer des élément de porfolio. Pour chaque élément, je veux :
  * uploader une image
  * saisir une description
  * saisir un lien

### En tant qu'apprenant de la promo 7, je veux me connecter avec github

### En tant qu'apprenant de la promo 7, je veux pouvoir sélectionner des repos de mon compte github afin de les voir apparaitre dans ma page.

### En tant qu'apprenant de la promo 7, je veux pouvoir associer un schéma de couleur (un thème) à ma page de profil.

### En tant qu'apprenant de la promo 7, je veux créer une playlist musicale pour accompagner mon porfolio.

### En tant qu'apprenant de la promo 7, je veux me connecter avec linked

### En tant qu'apprenant de la promo 7, je veux afficher mes données linked sur ma page

### En tant qu'apprenant de la promo 7, je veux me connecter avec soundcloud

### En tant qu'apprenant de la promo 7, je veux créer une playlist musicale pour accompagner mon porfolio.

----------------------------

## Partie Admin

### En tant qu'admin, je veux vérifier à l'inscription que l'uttilisateur est bien un P7

---------------------------------------------------

## Partie publique

### En tant qu'utilisateur, je veux voir la liste des apprenants de la promo7

### En tant qu'utilisateur, je veux accéder à la page profile de chacun des apprenants

---------------------------------------------------

* Une equipe back
* Des equipes front pour chaque composants
* Des scrum master
* Une équipe UX / dev front qui gére le layout global

---------------------------------------------------

## Exemple de use case :

1. Le P7 arrive sur la home du site
2. Le P7 clique sur le bouton s'inscrire (seulement pour les membres de la P7)
3. un formulaire apparait présentant les éléments suivant :
  * un input text "Nom"
  * un input text "Prénom"
  * un input "Github account"
  * un input "Dribble account"
  * un input "Soundcloud account"
  * un input "Linkedin account"
  * un input text "E-mail"
  * un input text "Mot de passe"
  * un bouton "Valider"
4. Après avoir rempli les champs, l'utilisateur clique sur "Valider"
5. Le compte est crée
6. La page de gestion de compte s'affiche
7. Une notif apparait pour lui confirmer la création du compte.

#### Références :

*
* https://github.com/mweibel/connect-session-sequelize

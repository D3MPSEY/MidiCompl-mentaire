# Sécurité d'information individuelle
mini introduction tsé c'Est le premier

Les informations sont les choses les plus importantes, probablement plus que le pétrole. Donc c'est encore plus importants de la protéger.

On barre sont char mais on gait pas pareils avec nos appareils genre les barrers quand on quitte.
Bloquer les points d'entrée
 - Bluetooth
 - localisation
 - wifi
de manière à réduire les possibilité d'attaque.

## les mise à jour
failles de sécurité
c'est importants de le faire elles patche les failles connues donc exploiter

Routeur importants à mettre à jour aussi même si on n'y pense rarement
 - Passer par l'adresse du routeur

## mot de passe
C'est un truc importants à protéger.
mot de passe plus utilisé : 123456
### Mot de passe sécuritaire
 - éviter les mots du dictionnaire
 - Mettre des caractères spéciaux pour ajouter du temps de craquage
 - mettre un mot de passe long
 - GESTIONNAIRE DE MOT DE PASSE
 - 2FA
   - autentification avec 2 facteur (mot de passe + genre le téléphone avec un code par sms ou par courriel)
   - Regarder YubiKey

### hashcat
 - logiciel permettant de craquer des mot de passe 
 - peut utiliser la cartes graphique pour plus de vitesse
 - supporte plein d'algorithme

1 min pour trouver un mot de passe avec 309 000 000 de possibilité

### Question de sécurité
Mettre de la junk 
Limité l'information public

## Les données
### Les clées USB
VERACRYPT
 - crée un lecteur comme si c'était une clée USB, il faut un mot de passe pour le lire.

## Les connection 
### Connection wifi public
Man in the middle
 - Quelqu'un se fait passer pour le retour et voit toute l'information qui passe et d'envoyer ce que tu veux
 - Permet de pas mal tout capturer
   - nom, date de naissance, carte de crédit, mot de passe
 - Possible aussi sur les téléphones sans fils avec des antenne téléphone
   - faire une antenne avec un signal fort
   - tout le monde ce connecte 
   - Profit

 - Protection? -> VPN

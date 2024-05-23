# Déploiement de µKosmos

<details open>
  <summary> Sommaire </summary>
  
  1. [Démarage](deploiement_µkosmos.md#1--démarage)
  2. [Remise en route]()
      
</details>

## 1- Démarage

## 2- Remise en route
Cette partie explique les étapes de remise en route du système KOSMOS après un temps "d'unitilisation".

Dans un premier temps vérifier la version de l'OS sur la carte SD de la Raspeberry Pi.
- Taper dans un terminal
 ''' cat /ect/os-release '''

Vérifier ensuite que le software est à jour
- Taper dans un terminale la commande
  '''
  git checkout //Vérifier la branche sur laquelle on se trouve
  git pull //Récupérer la dernière version du code
  '''

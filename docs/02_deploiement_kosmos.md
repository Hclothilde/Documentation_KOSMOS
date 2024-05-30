# Déploiement de µKosmos

<details open>
  <summary> Sommaire </summary>
  
  1. [Démarage](deploiement_kosmos.md#1--démarage)
  2. [Remise en route](deploiement_kosmos.md#2--remise-en-route)
      
</details>

## 1- Démarage

## 2- Remise en route
Cette partie explique les étapes de remise en route du système KOSMOS après un temps "d'unitilisation".

### 2.1- Mise à jour du software
### Vérification de l'OS
Dans un premier temps vérifier la version de l'OS sur la carte SD de la Raspeberry Pi.
La dernière version de l'OS est Debian 12
- Taper dans un terminal
```
cat /ect/os-release
```

### Vérification du soft
- Vérifier ensuite que le software est à jour
Toujours dans le terminal, vérifier que vous êtes bien sur la branche `dev_stereo` et récupérer la dernière version du code
  ```
  git checkout dev_stereo //Vérifier la branche sur laquelle on se trouve
  git pull //Récupérer la dernière version du code
  ```
### 2.2- Vérification de la partie hardware
### Vérification des engrenages moteurs
- Ouvrer le caisson des engrenages du moteur
- Faire tourner les engrenage manuellement pour s'assurer que rien ne bloque

### Lubrification des joints

>[!Warning]
>Cette étape est indispensable et est à réaliser avec soin, elle assure l'étanchéité du système
>

- Déviser les connecteurs des caps
- Vérifier qu'il n'y ait pas de cheveux sur vos joints
- Graisser chaque joints (la couche de graisse doit être fine et homogène)
- Reviser les connecteurs sans oublier les joints

- Déviser les caps des extrémitées (hublot transparent, et caps noir)
- Répéter les opérations ci dessus

- Enlever les joints autour des entretoises
- Répéter les opérations ci dessus

  







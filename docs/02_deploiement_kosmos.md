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

### Mise au point de la caméra
- Démarrer la caméra
- Pl acer une mire à environ 5m
- Régler la focale .....
- Connecter vous à l'interface web (10.42.0.1)
- Vérifier avec le live de la caméra que la mire est net, modifier le focus si necessaire
- Serrer la vis pour fixer les réglages de la caméra
- Vérifier que l'image est toujours net et que les paramètres n'ont pas bougé en serrant la vis

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

- Enlever les joints autour des "entretoises"
- Répéter les opérations ci dessus

### Encapsulation
- Fermer le caisson étanche

### Vérification du fonctionnement géneral de Kosmos
- Démarrer la caméra
- Connecter vous à l'interface web (10.42.0.1)
- Vérifier les paramètres dans l'onglet config:
   - 00_system_mode :
   - 01_system_record_button_gpio :
   - 02_system_stop_button_gpio :
   - 03_system_led_b :
   - 04_system_led_r :
   - 05_system_shutdown :
   - 06_system_moteur :
<br>

   - 10_motor_esc_gpio :
   - 11_motor_power_gpio :
   - 12_motor_button_gpio :
   - 13_motor_vitesse_min : 
   - 14_motor_vitesse_favorite : 
   - 15_motor_pause_time : 
<br>

   - 20_csv_step_time : 
   - 21_csc_file_name : 
<br>

   - 30_picam_file_name : 
   - 31_picam_resolution_x : 
   - 32_picam_resolution_y : 
   - 33_picam_preview :
   - 34_picam_framérate : 
   - 35_picam_record_time :
   - 36_picam_conversion_mp4 :
   - 37_picam_awb :
     
- Vérifier avec le live que la caméra est positionner de façon à ce que l'image soit droite
- Démarer une vidéo
- Observer si le moteur tourne correctement
- Arreter la video et verifier que l'enregistrement c'est bien passé (création d'un fichier cvs et conversion du fichier video h264 en mp4)


  







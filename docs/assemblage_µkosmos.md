# Assemblage µKOSMOS
<details open>
  <summary> Sommaire </summary>
  
  1. [Assemblage du boitier électronique](assemblage_µkosmos.md#1-assemblage-du-boitier-électronique)
  2. [Assemblage du caison vidéo](assemblage_µkosmos.md#2-assemblage-du-caisson-video)
  3. [Assemblage du trépried](assemblage_µkosmos.md#3-assemblage-du-trépied)
  4. [Assemblage du casque](assemblage_µkosmos.md#4-assemblage-du-casque)
  5. [Assemblage du cable](assemblage_µkosmos.md#5-assemblage-du-cable)
  6. [Assemblage de la paravane](assemblage_µkosmos.md#6-assemblage-de-la-paravane)
      
</details>

## 1. Assemblage du boitier électronique
<details>
  <summary> Outils </summary>
  
  * gaine thermo {[Etape 1](assemblage_µkosmos.md#etape-1---réaliser-les-raccordements-entre-les-câbles-et-les-connecteurs)}
  * matériel soudure {[Etape 1](assemblage_µkosmos.md#etape-1---réaliser-les-raccordements-entre-les-câbles-et-les-connecteurs)}
  * couronne de forage (diamètre:...) {[Etape 3](assemblage_µkosmos.md#etape-3---percer-les-côtés-du-boitier)}
  * foret (diametre: ..) {[Etape 3](assemblage_µkosmos.md#etape-3---percer-les-côtés-du-boitier)}
  * perceuse {[Etape 3](assemblage_µkosmos.md#etape-3---percer-les-côtés-du-boitier)}
  * velcro {[Etape 4 et 5](assemblage_µkosmos.md#etape-4---fixer-le-receiver-gaming-la-carte-gps-et-le-ventilateur-dans-la-boite)}
  * tourne vis plat 
  * tourne vis cruciforme
  
</details>

<details>
  <summary> Materiel </summary>
  
  [Tableau matériel boitier électronique](materiel_boite.md)
    
</details>

## Etape 1 - Réaliser les raccordements entre les câbles et les connecteurs

### Relier un cable USB à un cable micro USB en passant par le commutateur 

> [!NOTE]
> Ce cable fera le lien entre la batterie et la Raspberry et permetta d'alimenter la carte. Le commutateur permet de couper le courant sans débrancher les câbles.

> [!TIP]
> Optionel : connecteur cosse  
> Ici des connecteurs cosses ont été utilisés mais ils ne sont pas obligatoires vous pouvez simplement réaliser des soudures entre les pins et les câbles
> 
> Il est également important de noté que le commutateur peut lui aussi est modifié, vous aurez seulement besoin d'un intérupteur avec auto maintient (qui reste dans sa position losrque l'ont appui dessus)

- couper le cable USB à une trentaine de centimètre du branchement USB  
- enfiler la gaine thermo sur le câble (elle sera chauffée à la fin)  
- utiliser les connecteurs cosses pour faire le lien entre les pins du commutateur et le cable USB, brancher le fil noir et le fil rouge  
- chauffer la gaine thermo pour recouvrir tous les fils  
- répéter les mêmes étapes que pour le côté avec le cable micro USB et le commutateur

<img src="https://github.com/Hclothilde/Documentation_KOSMOS/blob/ceec4b8716ca7170e905918eca46779770e4e37d/docs/pictures/assembly_guide/commutateur_cable.jpg" width="300"/> <img src="https://github.com/Hclothilde/Documentation_KOSMOS/blob/d7f3a26780ae5b1e7ddae37c8ff18bae6e9926e9/docs/pictures/assembly_guide/cosse.jpg" width="300"/>

### Relier un cable USB au ventillo

> [!NOTE]
> Ce cable fera le lien entre le ventilateur et la raspberry. Brancher le ventilateur sur la carte pemet de l'alimenter et de le faire fonctionner.

- couper le câble USB à une trentaine de centimètre du branchement USB  
- enfiler la gaine thermo sur le câble (elle sera chauffée à la fin)   
- souder les cables rouges ensemble et les cables noirs ensemble  

<img src="https://github.com/Hclothilde/Documentation_KOSMOS/blob/d7f3a26780ae5b1e7ddae37c8ff18bae6e9926e9/docs/pictures/assembly_guide/ventilateur_cable.jpg"  width="300"/>

### Relier des cables de prototypage au bouton poussoir  

> [!NOTE]
> Ces cables feront le lien entre le bouton poussoir et la raspberry.

- répéter les mêmes étapes que pour le cable USB et le ventillo  

<img src="https://github.com/Hclothilde/Documentation_KOSMOS/blob/d7f3a26780ae5b1e7ddae37c8ff18bae6e9926e9/docs/pictures/assembly_guide/bp_cable.jpg" width="300"/>

## Etape 2 - assembler la carte ethernet et la carte raspberry  

> [!NOTE]
> La carte Ethernet est nécessaire pour ""

- monter les supports sur la raspberry
- souder barette noire
- brancher carte ethernet sur raspberry
- connecter les "trames"

<img src="https://github.com/Hclothilde/Documentation_KOSMOS/blob/d7f3a26780ae5b1e7ddae37c8ff18bae6e9926e9/docs/pictures/assembly_guide/support_raspberry.jpg" width="300"/> <img src="https://github.com/Hclothilde/Documentation_KOSMOS/blob/d7f3a26780ae5b1e7ddae37c8ff18bae6e9926e9/docs/pictures/assembly_guide/ethernet_raspberry.jpg" width="300"/> <img src="https://github.com/Hclothilde/Documentation_KOSMOS/blob/d7f3a26780ae5b1e7ddae37c8ff18bae6e9926e9/docs/pictures/assembly_guide/trame_ethernet.jpg" width="300"/>

## Etape 3 - Percer les côtés du boitier 

> [!NOTE]
> Ces ouvertures permettront de placer les connecteurs.

> [!TIP]
> Réaliser une ouverture supplémentaire pour que l'air puisse circuler et refroidir le système

- percer des trou pour les connecteurs et pour les vis qui les fixeront
  
<img src="https://github.com/Hclothilde/Documentation_KOSMOS/blob/e7b992de14c27f3d806314fa78ff201460aad8f4/docs/pictures/assembly_guide/velcro_trou.jpg" width="300"/>

## Etape 4 - fixer le receiver gaming la carte gps et le ventilateur dans la boite

> [!TIP]
> brancher le cable micro USB sur la carte gps maintenant il sera difficile d'accès lorsque la carte raspberry sera fixée

- fixer le receiver gaming et la carte gp à l'aide de velcro
- visser le ventilateur
  
<img src="https://github.com/Hclothilde/Documentation_KOSMOS/blob/d7f3a26780ae5b1e7ddae37c8ff18bae6e9926e9/docs/pictures/assembly_guide/gps_receiver_ventilateur.jpg" width="300"/>

 ## Etape 5 - Fixer le clavier et la batterie dans le couvercle  
 - fixer le clavier et la baatterie à l'aide de velcro
<img src="https://github.com/Hclothilde/Documentation_KOSMOS/blob/d7f3a26780ae5b1e7ddae37c8ff18bae6e9926e9/docs/pictures/assembly_guide/fixer_batterie_clavier.jpg" width="300"/>

## Etape 6 - fixer la raspberry au boiter

<img src="https://github.com/Hclothilde/Documentation_KOSMOS/blob/d7f3a26780ae5b1e7ddae37c8ff18bae6e9926e9/docs/pictures/assembly_guide/branchement_gps_gaming.jpg" width="300"/>

## Etape 7 - fixer l'interrupteur, le bouton poussoir, les connecteurs et réaliser les branchements


## 2. Assemblage du caison vidéo
<details>
  <summary> Outils </summary>
  
  * ex1
  * ex2
  
</details>

<details>
  <summary> Materiel </summary>
  
  [Tableau matériel caisson vidéo](materiel_caisson_video.md)
    
</details>

## 3. Assemblage du trépried
<details>
  <summary> Outils </summary>
  
  * ex1
  * ex2
  
</details>

<details>
  <summary> Materiel </summary>
  
  [Tableau matériel trépied](materiel_trepied.md)
    
</details>

## 4. Assemblage du casque
<details>
  <summary> Outils </summary>
  
  * ex1
  * ex2
  
</details>

<details>
  <summary> Materiel </summary>
  
  [Tableau matériel casque](materiel_casque.md)
    
</details>

## 5. Assemblage du cable
<details>
  <summary> Outils </summary>
  
  * ex1
  * ex2
  
</details>

<details>
  <summary> Materiel </summary>
  
  [Tableau matériel cable](materiel_cable.md)
    
</details>

## 6. Assemblage de la paravane
<details>
  <summary> Outils </summary>
  
  * ex1
  * ex2
  
</details>

<details>
  <summary> Materiel </summary>
  
  [Tableau matériel paravane](materiel_paravane.md)
    
</details>



    

# Test de conversion d'une image généré par IA

Objectif : Convertir une image généré par IA en un objet découpable avec une machine de découpe laser

## [⌛Version 1](https://github.com/usini/creatures_ia_to_laser_cuter/tree/v1)
## [⌛Version 2](https://github.com/usini/creatures_ia_to_laser_cuter/tree/v2)
## [⌛Version 3](https://github.com/usini/creatures_ia_to_laser_cuter/tree/v3)

## Génération
* Générateur : https://nightcafe.studio
* Algorithme : SDXL 0.9
* Seed: 50379071
* Prompt : laser cut, svg, intrigate, one color, top view, fantasy creature, cute, schematics, magic, forest

![Image IA](references/generated.jpg)

## Travail sur l'image
* L'image a été prédécoupé avec paint.net
* Puis transformer en plusieurs couche correspondant à une zone à découper
![Image Vectoriel](creatures.svg)

## Vérification du résultat
Afin de vérifier si le résultat sera correcte, chaque couche est importé en SVG dans fusion 360

### [🖲️Visualiser en 3D](creatures.stl)

![Image Fusion360](creatures_fusion360.png)

## Préparation du fichier
* Chaque partie doit être préparer pour la découpe laser afin d'optimiser l'espace utilisé

## Découpe
* Les fichiers sont importés dans RdWorks 8

## Post Traitement
* Chaque partie est vernis afin de lui donner une teinte particulière
* Les parties sont collés à l'aide d'une colle à bois

## Yeux / Nez
Les yeux et les nez seront réalisés en 3D puis imprimés en résine.

1. Introduction
Ce projet consiste à concevoir un clavier mécanique Bluetooth de 60 touches.
L’objectif était de créer un clavier compact et personnalisé en réalisant deux éléments principaux :

- la conception électronique du PCB

- la modélisation 3D des touches et des éléments mécaniques

Le travail présenté ici correspond à la partie conception, qui a été entièrement réalisée.
La fabrication physique n’a pas été effectuée dans le temps imparti.

2. Présentation générale
Le clavier repose sur une matrice de 60 touches, un microcontrôleur compatible Bluetooth et une alimentation sur batterie.
Le projet se concentre sur la création d’un PCB fonctionnel et d’un ensemble de keycaps imprimables en 3D.

Les deux volets du projet sont :

- Le PCB, conçu sous KiCad

- La modélisation 3D, réalisée en CAO

3. Conception du PCB
La carte électronique a été conçue sous KiCad.
Elle intègre :

- un microcontrôleur ESP32‑WROOM‑32 pour la communication Bluetooth

- une matrice de 12 colonnes × 5 lignes (60 touches)

- une diode par touche pour éviter le ghosting

- un circuit d’alimentation sur batterie Li‑ion

- un interrupteur d’alimentation

- une LED d’indication

Le schéma et le routage du PCB sont terminés.
Les fichiers fournis incluent :

- le schéma KiCad

- le PCB routé

- les rendus 3D générés par KiCad

4. Modélisation 3D
Les touches du clavier ont été modélisées en CAO.
Elles respectent les caractéristiques suivantes :

- format standard 1U

- tige compatible MX

- géométrie simple, adaptée à l’impression 3D

- fichiers exportés en STL et STEP

La modélisation permet d’imprimer les keycaps en FDM ou en SLA.

5. Liste des composants (BOM)
Voici la liste complète des composants nécessaires à la fabrication du clavier.
Ils n’ont pas encore été commandés, mais la sélection est finalisée.

Microcontrôleur
- 1× ESP32‑WROOM‑32

Touches et matrice
- 60× switches mécaniques MX

- 60× diodes 1N4148

Alimentation
- 1× batterie Li‑ion 3,7 V (500–1200 mAh)

- 1× module de charge TP4056 (avec protection)

- 1× connecteur JST‑PH 2.0
  
- 1× interrupteur ON/OFF

Indication et contrôle
- 1× LED d’état

- 1× résistance pour LED (220–1000 Ω)

- 1× bouton reset (tact switch)

Passifs
- 4× condensateurs 100 nF

- 1× condensateur 10 µF

- 2× résistances 10 kΩ

Connectique
- 1× port micro‑USB ou USB‑C (selon le design choisi)

6. État d’avancement
À ce stade du projet :

- la conception du PCB est terminée

- la modélisation 3D des touches est terminée

- la fabrication n’a pas été réalisée

- les composants n’ont pas encore été commandés

Le projet correspond donc à un prototype numérique complet.

7. Améliorations possibles
Pour aller plus loin, plusieurs étapes pourraient être ajoutées :

- fabrication du PCB

- soudure et assemblage

- impression 3D des keycaps

- développement du firmware Bluetooth

- tests et ajustements éventuels

8. Conclusion
Ce projet m’a permis de concevoir un clavier mécanique Bluetooth de 60 touches en réalisant la partie électronique et la partie mécanique.
Même si la fabrication n’a pas été effectuée, la conception est complète et prête à être poursuivie

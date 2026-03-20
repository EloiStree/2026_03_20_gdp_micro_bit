
# Godot Package: Micro bit

> Workshop for Godot XR students: Try to recreate a MicroBit API in XR    

Dans le contexte d’apprendre à coder avec Godot et de créer des applications avec Godot XR Tools,     
je vous propose un exercice "simple" :    

Vous avez un GLB du micro:bit. Ajoutez, couche par couche, des fonctionnalités pour simuler le Micro:bit.     

C’est une demande typique dans le marché de la VR.     
Nous avons cet appareil à 10 000 $ dans un laboratoire, qui prend 3 jours à utiliser et coûte 400 $ à chaque test.    
Sans compter le temps d’un senior qui doit enseigner à la nouvelle recrue.    

Permettre à nos employés de s’entraîner sur la machine avant de l’utiliser réellement.   

Nous allons pratiquer sur un appareil très connu : le Micro:bit.     

Arrêtez-vous quand vous en avez marre,   
mais fixez-vous le challenge de publier l’application sur Itch.io   
dans une version portfolio finie avant la fin de l’atelier.   

Sachez travailler par couches de MVP.   
Votre jeu doit être jouable en APK à chaque fin d’atelier.   

---

## Liste des features (du plus facile au plus difficile)

* Créer une scène pour une LED
* Créer un script qui permet de gérer la couleur et la transparence basée sur un float
* Créer une scène avec 25 scènes de LED
* Créer un script qui permet de gérer les 25 LEDs avec du code :
  * Une LED à la fois
  * Avec un tableau de floats
  * Avec un string
  * Avec un énumérateur de strings par défaut
* Créer une animation pour une scène de boutons (il y en a 3 sur le Micro:bit)
* Faire un script pour changer d’état avec les boutons
* Ajouter les trois boutons à votre scène globale du Micro:bit
* Il y a 3 boutons qui, une fois touchés, produisent un vrai ou un faux par capacité :
  * Logo
  * Pin 1 et 3
* Avec Godot XR Tools, vous pouvez snapper des objets :
  * Créer un adaptateur 3D qui peut recevoir un snap du Micro:bit
  * Il reçoit une référence vers la façade que vous avez créée
  * Cet adaptateur permet de s’ajouter sur le Micro:bit :
    * Lecture
    * Écriture
    * Pins rouge, noir, jaune :
      * Noir : ground
      * Rouge : haut potentiel
      * Jaune : signal
        * Un signal peut être entrant ou sortant en électronique
  * En MicroPython, par défaut, il n’y a que 3 pins analogiques, les autres sont digitales

## To do

* Accéléromètre
* Gyroscope
* Température du jeu
* Son du jeu
* Batteries
* Pins
* ~Bluetooth~
* RT XT
  * UDP
  * WebSocket
* GDScript Sandbox pour coder avec votre Micro:bit
   
---
   
## 3D

Vous avez à disposition deux modèles.

Celui-ci est gratuit mais approximatif :   
Il est en CC, je l’ai donc mis dans le projet en gardant la licence.   

[<img width="597" height="526" alt="image" src="https://github.com/user-attachments/assets/f49143e3-78e3-48b6-bae4-88fb7fd0e39c" />](https://sketchfab.com/3d-models/microbit-assemby-f0c6ec58eefc47afaab08d8de07e1158#download)     
[Cult3D](https://cults3d.com/en/3d-model/gadget/micro-bit-pequicraftminecraft) - [SketchFab](https://sketchfab.com/3d-models/microbit-assemby-f0c6ec58eefc47afaab08d8de07e1158#download)    

Et il y a une version payante faite à la sueur de son front par [@sitetechnofr](https://cults3d.com/en/users/sitetechnofr/3d-models) :      

[<img width="1272" height="623" alt="image" src="https://github.com/user-attachments/assets/77b3d3b4-f592-4fdf-9c48-8c1edbd8615e" />](https://sketchfab.com/3d-models/microbit-v2-759eb0f3db0d44d5a7ea80d4ae00580e)   
[<img width="926" height="599" alt="image" src="https://github.com/user-attachments/assets/65bf2a22-e685-43e6-a0a4-6368b75d029f" />](https://sketchfab.com/3d-models/microbit-v2-759eb0f3db0d44d5a7ea80d4ae00580e)       [<img width="1090" height="697" alt="image" src="https://github.com/user-attachments/assets/79e08459-a4f7-41b8-a450-8f13bd78e6ed" />](https://sketchfab.com/3d-models/microbit-v2-759eb0f3db0d44d5a7ea80d4ae00580e)     
Buy: [Cult3D](https://cults3d.com/en/3d-model/various/micro-bit-v2)  

---

## SVG

Micro:bit fournit de beaux SVG et images du Micro:bit V2.   

[<img width="971" height="625" alt="image" src="https://github.com/user-attachments/assets/9048e1c5-c50d-4357-b94d-5d2dc7a624d3" />](https://microbit.org/design-your-microbit/v2/)   
[<img width="1125" height="510" alt="image" src="https://github.com/user-attachments/assets/e82f9ec1-d65c-480f-b7ff-bc56cfdebb8e" />](https://microbit.org/design-your-microbit/v2/)  
[Site Web officiel](https://microbit.org/design-your-microbit/v2/) - [GitHub](https://github.com/microbit-foundation/microbit-svg)  

---

## Un moteur et des roues ?

Si vous avez envie de faire un petit jeu de voiture avec votre prototype, ce moteur est l’un des plus achetés sur le web :   
  
[<img width="516" height="516" alt="image" src="https://github.com/user-attachments/assets/b0afd70e-f8aa-4999-b73f-7a944e3b7a9a" />](https://cults3d.com/en/3d-model/gadget/zdkderphb)     
[https://cults3d.com/en/3d-model/gadget/zdkderphb](https://cults3d.com/en/3d-model/gadget/zdkderphb)     


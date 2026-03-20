Add to existing project  
```
git submodule add https://github.com/EloiStree/2026_03_20_gdp_micro_bit.git addons/2026_03_20_gdp_micro_bit
```

Add to temporary project  
```
git clone https://github.com/EloiStree/2026_03_20_gdp_micro_bit.git addons/2026_03_20_gdp_micro_bit
```


-------------

# 2026_03_20_gdp_micro_bit

> Workshop for Godot XR students: Try to recreate a MicroBit API in XR


L exercie est simple.
Vous avez un GLB du micro bit, ajouter couche par couche des features pour simuler le Micro-Bit.

Arretez vous quand vous en avez mare.  
Mais fixez vous le challenge de publier l application sur Itch.io  
Dans une version portfolio finie.


- Creer une scene pour une led
- Creer un script qui permet de gere la couleur et la transparence baser sur un floatant
- Creer un scene avec 25 scne de led
- Creer un script qui permet de gere les 25 leds avec du code
  - Une led a la fois
  - avec un tableau de float
  - avec un string
  - avec un enumerateur des string par default
- creer une animation pour une scene de bouttons ( il y en a 3 sur le micro bit)
- fait un script pour changer d etat avec le bouttons
- ajouter les trois bouttons a votre scene global du micro bit.
- Il y a 3 bouttons qui une fois toucher produit un vrai ou un faut par capaciter
  - logo
  - pin 1 et 3
- avec Godot XR Tool, vous pouvez snaper des objets.
  - Creer un adaptateur 3D qui peut recevoir un snap du micro bit.
  - Il recoit une reference vers la facade que vous avez creez.
  - Cette adaptateur permet de s ajouter sur le micro bit.
    - Lecture
    - Ecriture
    - Pin Rouge Noir Jaune
      - Noir ground
      - Rouge haut potentiel
      - Jaune signal
        - Un signal peu etre entrant ou sortant en electronique.
  - En MicroPython par default, il n y a que 3 pin analogique les autres sont digital
  - 

To do:
- accelerometer
- gyroscope
- temperature du jeu
- son du jeu
- batteries
- pin
- ~Bluetooth~
- RT XT
  - UDP
  - Websocket
- GDScript Sandbox pour coder avec votre MicroBit
- 


## 3D

Vous avez a disposition deux models.

Celui-ci qui est gratuit mais approximatif:
Il est en CC je l'ai donc mis dans le projet en gardant la license.
[<img width="597" height="526" alt="image" src="https://github.com/user-attachments/assets/f49143e3-78e3-48b6-bae4-88fb7fd0e39c" />](https://sketchfab.com/3d-models/microbit-assemby-f0c6ec58eefc47afaab08d8de07e1158#download)     
[Cult3D](https://cults3d.com/en/3d-model/gadget/micro-bit-pequicraftminecraft) - [SketchFab](https://sketchfab.com/3d-models/microbit-assemby-f0c6ec58eefc47afaab08d8de07e1158#download)   

Et il y a une version fait la suieur de son frond par [@sitetechnofr](https://cults3d.com/en/users/sitetechnofr/3d-models):
[<img width="1272" height="623" alt="image" src="https://github.com/user-attachments/assets/77b3d3b4-f592-4fdf-9c48-8c1edbd8615e" />](https://sketchfab.com/3d-models/microbit-v2-759eb0f3db0d44d5a7ea80d4ae00580e)    
[<img width="926" height="599" alt="image" src="https://github.com/user-attachments/assets/65bf2a22-e685-43e6-a0a4-6368b75d029f" />](https://sketchfab.com/3d-models/microbit-v2-759eb0f3db0d44d5a7ea80d4ae00580e)    
<img width="1090" height="697" alt="image" src="https://github.com/user-attachments/assets/79e08459-a4f7-41b8-a450-8f13bd78e6ed" />

Buy: [Cult3D](https://cults3d.com/en/3d-model/various/micro-bit-v2)   

## SVG

MicroBit fournit des beaux SVG et image du MicroBit V2.
[<img width="971" height="625" alt="image" src="https://github.com/user-attachments/assets/9048e1c5-c50d-4357-b94d-5d2dc7a624d3" />](https://microbit.org/design-your-microbit/v2/)    
[<img width="1125" height="510" alt="image" src="https://github.com/user-attachments/assets/e82f9ec1-d65c-480f-b7ff-bc56cfdebb8e" />](https://microbit.org/design-your-microbit/v2/)  
[Site Web officiel](https://microbit.org/design-your-microbit/v2/) - [GitHub](https://github.com/microbit-foundation/microbit-svg)     


# Un moteur et des roues ?
Si vous avez envie de faire un petit jeux de voiture avec votre prototype, ce moteur et un des plus acheter sur le web:
[<img width="516" height="516" alt="image" src="https://github.com/user-attachments/assets/b0afd70e-f8aa-4999-b73f-7a944e3b7a9a" />](https://cults3d.com/en/3d-model/gadget/zdkderphb)   
https://cults3d.com/en/3d-model/gadget/zdkderphb  

-----------


[<img width="1423" height="1048" alt="image" src="https://github.com/user-attachments/assets/43c3c00f-80c4-4efb-a34c-9ae586131958" />](https://sketchfab.com/3d-models/microbit-v2-759eb0f3db0d44d5a7ea80d4ae00580e)   
https://sketchfab.com/3d-models/microbit-v2-759eb0f3db0d44d5a7ea80d4ae00580e  



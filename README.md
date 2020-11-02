The Neon GITS
===

An IC06 project developed with Unreal Engine 4





---
---
---
# Notes projet (FR)

## Ressources générales
[lien git projet](https://gitlab.utc.fr/tsantonj/the_neon_gits)

[alpha v0.2.62](https://drive.google.com/file/d/1k06yKDm4gRK0KNqYx69nvKnkiBf9G93u/view?usp=sharing
)

[lien google sheet planning](https://docs.google.com/spreadsheets/d/1Xr9n_vt9y2RlpWiuXXkXmDvKhSmyRA22sAipUdPXf8A/edit?usp=sharing)

[prèsentation vidéo contenu alpha v0.2.5](https://drive.google.com/file/d/1lI6rOlypVaHmL1ioif5b4uoKDrsdqKoh/view?usp=sharing)

### Inspiration CyberPunk
**Artstation Ghost in the Shell**
[Artstation Ghost in the Shell](https://www.artstation.com/search?q=ghost%20in%20the%20shell&sort_by=relevance)

- David Bocquillon Carrasco (Concept Artist)
![https://www.artstation.com/artwork/4ARqk](https://cdnb.artstation.com/p/assets/images/images/012/253/253/large/david-bocquillon-carrasco-ghost-in-the-shell.jpg?1533830732)


**Artstation Hong Kong**
[Artstation Hong Kong](https://www.artstation.com/search?q=Hong%20kong&sort_by=relevance)

- Sergey Zabelin (Concept Artist)
![https://www.artstation.com/artwork/G89oz](https://cdna.artstation.com/p/assets/images/images/000/544/340/large/sergey-zabelin-hong-kong-street-patrol-1920.jpg?1443928378)

- DOFRESH. (Concept Artist)
![https://www.artstation.com/artwork/O6qlJ](https://cdna.artstation.com/p/assets/images/images/009/559/158/large/dofresh-10-hk-landscape.jpg?1519669944)
![](https://cdnb.artstation.com/p/assets/images/images/009/559/171/large/dofresh-100-bridge-light-on.jpg?1519669897)


**ArtStation Cyberpunk**
[](https://www.artstation.com/search?q=cyberpunk&sort_by=relevance)

- Alexander Dudar (Concept Artist chez CD Projekt)
![https://www.artstation.com/artwork/NQN5J](https://cdnb.artstation.com/p/assets/images/images/009/089/349/large/alexander-dudar-city-view.jpg?1517073959)

- Tarmo Juhola (Concept Artist, Architect)
![https://www.artstation.com/artwork/XBEbml](https://cdnb.artstation.com/p/assets/images/images/020/057/175/large/tarmo-juhola-cyberpunkcity-kopio.jpg?1566192051)

- Donglu Yu (Concept Artist)
![https://www.artstation.com/artwork/nAZK4](https://cdna.artstation.com/p/assets/images/images/011/919/898/large/donglu-yu-cyberpunk-rooftop-view-small.jpg?1532089994)
![](https://cdna.artstation.com/p/assets/images/images/011/919/896/large/donglu-yu-cyberpunk-rooftop-view-crop01.jpg?1532089849)

- Rutger van de Steeg (Landscape Artist)
![https://www.artstation.com/artwork/4bBw64](https://cdnb.artstation.com/p/assets/images/images/020/275/221/large/rutger-van-de-steeg-saturation.jpg?1567107880)

- Petter Steen (VFX Artist)
![https://www.artstation.com/artwork/4bz39k](https://cdna.artstation.com/p/assets/images/images/018/819/052/large/petter-steen-render-08-1001.jpg?1560859004)

- James Daly (Concept Artist / Comic Book Artist)
![https://www.artstation.com/artwork/W2AoOQ](https://cdnb.artstation.com/p/assets/images/images/029/885/051/large/james-daly-untitled-1-1.jpg?1598934315)


### Inspiration Gameplay / Jeu
- [Binding of Isaac](https://fr.wikipedia.org/wiki/The_Binding_of_Isaac): principe de différentes salles (niveaux pour nous) et de différentes zones / profondeurs de cave, se finissant par un boss. Plein de stuff pour boost ses stats, différents perso (avec stats différentes)
- [Zone of the Enders](https://fr.wikipedia.org/wiki/Zone_of_the_Enders:_The_2nd_Runner): Grosse vagues à tuer, assez rapide, lock fire
- [Prototype de Pause Process](https://www.youtube.com/watch?v=I6XDJr_lczE): assez rapide, lock fire, ambiance Cyberpunk
- [HADES](https://fr.wikipedia.org/wiki/Hades_(jeu_vid%C3%A9o)): Die&Retry, RogueLike, choix de stuff / compromis, différentes salle se finissant par un Boss puis niveau différent, différentes armes
- [Cyberpunk 2077](https://fr.wikipedia.org/wiki/Cyberpunk_2077): pour l'inspiration graphique + thèmes abordés

### Inspiration Lore
- [Ghost in the Shell (1995)](https://fr.wikipedia.org/wiki/Ghost_in_the_Shell): base des thèmes cyberpunk, [lien de ma critique / présentation de Ghost in the Shell (1995) pour Cinem'UT](https://assos.utc.fr/lefil/article/?paper=234)
- [Cyberpunk 2077](https://fr.wikipedia.org/wiki/Cyberpunk_2077): pour l'inspiration graphique + thèmes abordés cyberpunk {%youtube B6dXb6rPy08 %}
- [Ex Machina](https://fr.wikipedia.org/wiki/Ex_machina_(film)) rapport à la robotique et à l'IA, frontière vivant / pas vivant, humain / pas humain, rapport à soi...
- [Lain](https://fr.wikipedia.org/wiki/Serial_Experiments_Lain) notion de réalité, rapport à soi, de conscience



## TECHNIQUE : Programmation, Description du code...
[Plugins UE4](https://www.pixstacks.com/best-free-unreal-engine-plugins)

### Bon tutos en vrac
- [Get Started with UE4](https://docs.unrealengine.com/en-US/GettingStarted/index.html?utm_source=launcher&utm_medium=ue&utm_campaign=uelearn) Doc de Unreal Engine
- [Introduction to Blueprints](https://docs.unrealengine.com/en-US/Engine/Blueprints/GettingStarted/index.html) Doc de Unreal Engine 
- [Blender, bases à un peu avancé, faire un MacBook en 4 vidéos](https://www.youtube.com/watch?v=d93bu-2rnOE) très très bon tuto bien complet et expliqué et relativement court ! Première vidéos : {%youtube d93bu-2rnOE %}
- [Modeling a character BaseMesh in Blender (Tutorial)](https://www.youtube.com/watch?v=WlaMfIgS2ns) {%youtube WlaMfIgS2ns %}
- 



### Explication code
---
**Bonus**
Dans le viewport : 
- **LOCKBOX**: Collision sphere ne doit pas détecter la lock box (sinon le joueur va prendre le bonus "en le regardant") -> dans collision: Collision preset sur custom, tout mettre en Overlap sauf la case Lock_Box
- **ROTATING MOVEMENT** set sur l'axe Z de 60.0°/s 
- **PointOfInterest** set de l'image "bonus" pour qu'il s'affiche sur la minimap
- **EFFET "VIRTUEL"** Les mesh ne doivent pas être "solides" -> set les Collision Perset des mesh sur "NoCollision"
- **UNSPAWN AUTO** Pour les bonus temporaire, au begin play, mettre un delay et le détruire
- **SPAWN LOCATION** le Spawn location en Z est set au begin play à 30.0 et reste fixe
- **OVERLAP ACTION** set son action et le faire unspawn à la fin
- **TAG** mettre un tag à "self" : "Bonus": ![](https://i.imgur.com/bLJnchI.png) + "Upgrade" dans le cas des upgrades

---
**Building**
- **TAG** mettre un tag à "self": "Building"
- **RANDOM CONSTRUCTION**: dans le construction script mettre de la randomization de taille et de forme : ![](https://i.imgur.com/oD145BQ.png), ![](https://i.imgur.com/yvv7aAz.png)
- **BUILDING COLOR THROUGH LEVEL**: evolve color building follow the level![](https://i.imgur.com/LaIpYUL.png)

---
**Portail**
- **Portail visibility & action** au begin play, désactiver la trigger box et set la visibilité du portail à faux, faire un petit delay (7 seconde pour la zone de bonus + Boss) puis appeler la fonction qui check le nombre d'ennemis avec un Set Timer by Function Name pour boucler sur ce check toutes les secondes (ou moins) : ![](https://i.imgur.com/eWS5zqy.png) Dans l'event tick, check si la visibilité du portail doit changer (est-il déjà actif (is_active) et doit-il etre généré (generate_portail)) : ![](https://i.imgur.com/o76DMUK.png)
- **Portail triggered & Save des stats entre les levels** quand le portail est triggered, avant de changer de level on save dans le game instance toutes les stats du joueur (stats qui peuvent évoluer d'un level à l'autre suivant les bonus gagnés ![](https://i.imgur.com/PFDXWeW.png)
- **Point of Interest** set le Point of interest Icon

---
**Projectiles**
- **Damage** à leurs création (begin_play) check les damages du joueur et les set au projectile
- **Prévenir la surcharge** mettre un timer à la fin du begin_play pour que le projectile s'autodétruise au bout de quelques secondes
- **Overlap** Check si c'est un ennemie et lui appliquer des dommages ou si c'est autre chose et donc simplement passer à l'étape suivante : faire un son et une animation avant de disparaitre : ![](https://i.imgur.com/mQIaKTu.png)
- **Laser Lock Damages** au begin play, le laser lock prend les damages du joueur * 2.5 afin d'être plus puissant
> **TODO** Commenter et faire l'emmission d'un son + animation à la destruction du projectile 

---
**PlayerCharacter**
> **TODO**, clean du blueprint
- **Begin_play & set stats** Au begin play, executer la fonction "init_stat" qui check le game_instance pour set les stats du joueur. Au lancement du jeu la vie du joueur est à -1 donc si on voit une vie négative, on init les stats avec les stats de base du joueur. Sinon on récupère celles du game instance : ![](https://i.imgur.com/zjF5AkJ.png)
- **check_health** cette fonction lancée au begin play va vérifier la vie du joueur et le tuer dans le cas ou il n'en a plus
- **Fonction sur le temps (time heal, lock_ammo_reload...)** Lancés au begin_play via un Set Timer by Function Name qui exécutera toutes les n secondes (cocher la case Looping) la fonction (qui ajoutera de la vie / des munitions / etc) : ![](https://i.imgur.com/usGQl7c.png)
- **Tir** le click bouton va set la variable "is_fireing" à vrai puis faux quand il est relaché. Dans l'event tick, si is_fireing est vrai on appel la function Fire qui fera spawn un projectile (au bon endroit et à la bonne direction): ![](https://i.imgur.com/vqRLIQE.png)
- **Lock fire**:
    - **Activation du trigger box** Check s'il peut etre activé (cooldown) si oui activation puis set du cooldown via un delay et limitation du temps d'activation : ![](https://i.imgur.com/Prn00uh.png)
    - **Tigger des ennemis** Quand il est actif, check des ennemis qui sont dedans pour savoir s'ils ont déjà été mis dans la liste des ennemis triggered ou pas. S'ils ne le sont pas, on les ajoute, sinon on passe. De plus on check la longueur de la liste pour ne pas tirer 10 fois si on n'a que 5 munitions : ![](https://i.imgur.com/ztngRqK.png)
    - **Lock Fire released** quand le lock fire est laché (ou quand le timer pour le temps max d'activation est à son terme), cette fonction est appelée. Pour chaque ennemi dans la liste des ennemis triggered, un tir de lock fire sera réalisé (**TODO** possibilité de mettre 1/10 de seconde entre chaque tir pour ne pas tout tirer en même temps...) à l'emplacement du joueur et en direction de l'ennemi locké : ![](https://i.imgur.com/2Iy9oim.png) 
    - **Viewport** mettre la lock box sur la camera du joueur pour qu'elle soit dans la direction du regard du joueur et set de la lock box pour qu'elle ne collisionne que les ennemis sinon le joueur aura des dégats en regardant les ennemis : ![](https://i.imgur.com/AUWliNr.png) 
- **Minimap camera** set en Orthographic au dessu du joueur![](https://i.imgur.com/y4kIeTD.png)
- **Point of Interest** set le player Icon

---
**Ennemis**
- **Spécificités** 
    - **Basic** ![](https://i.imgur.com/GIaaTOr.png) suit le joueur
    - **Boeing** ![](https://i.imgur.com/wJuVAWA.png) va en ligne droite et rebondi sur les murs
    - **Citern** ![](https://i.imgur.com/DnfLJ93.png) lache des mines
    - **Bus** ![](https://i.imgur.com/IiKCnYD.png) fait pop des Basic
    - **Turret** ![](https://i.imgur.com/OiyM5xu.png) c'est une tourrelle basique cherchant à tirer sur le joueur (fixe), j'ai tenté la prédiction de position mais... j'ai pas passé assez de temps ![](https://i.imgur.com/Oju57qZ.png)
    - **Generator** ![](https://i.imgur.com/TZijgWW.png) fait pop des Basic (fixe)
- **Tags** mettre le tag "Ennemy" sur les chaque "self" des ennemis : ![](https://i.imgur.com/0LeTky9.png)
- **Check Health** lancement au begin play, même fonctionnement que pour le joueur
- **Ennemy_Attack** appel au begin play s'il attaque dès le début avec une Timer by Function Name si besoin, ou au moment où un event se passe (joueur dans le champ de vu de l'ennemis)
- **Undermap spawn** prevenir cela en tuant l'ennemi... sale histoire... ![](https://i.imgur.com/dnIJWkS.png)
- **Touch player** via la collision box, quand elle triggered le joueur, elle lui applique des dégats ![](https://i.imgur.com/I3zfzjn.png) **!!! ATTENTION !!!** Il FAUT que la trigger box ne trigger pas le lockbox (sinon le joueur prend des dégats en regardant l'ennemi lol) set les collision de la trigger box ![](https://i.imgur.com/tGz8OkO.png)
- **Point of Interest** set l'ennemy Icon

---
**Game Mode**
- **Spawn ennemis** pour chaque ennemi, trouver un point sur la map où faire spawn l'ennemi mais prévenir le spawn sur un batiment (Z > 200) puis suivant la zone, faire spawn les ennemies correspondant (zone suivant le level) : ![](https://i.imgur.com/x9mWVce.png)
- **Spawn par zone** spawn spécifiques à la zone + appel de la zone d'en dessous de mani![](https://i.imgur.com/7Fsylqm.png)

---
**Game Instance**
liste des variables stockés au 31/10/2020 : ![](https://i.imgur.com/qaNPGCM.png)

---
**Map**
- **Menu_map** vide de base, on ne va que créer l'UI Menu dessus : ![](https://i.imgur.com/Y5WIHmW.png)
- **Level_map** map de base de chaque level:
    - **Construction du level** au begin play, construire les buildings puis créer l'UI du joueur (ingame UI), check le level pour savoir si on est dans un level de bonus / boss, ou un level intermédiaire (si intermédiaire, on call les fonctions de spawn des ennemis de Game Mode (oui on aurait pu laisser dans le level map...)). Si c'est une zone de bonus / boss, on va créer les bonus puis appeler le boss ![](https://i.imgur.com/ogEaaSe.png)
    - **Création des buildings**  trouver une position et faire spawn un acteur building de notre choix : ![](https://i.imgur.com/huunN6n.png)
    - **Viewport** ![](https://i.imgur.com/jhlHtkq.jpg)
        - **NavMeshBoundsVolume** pour dire que l'IA peut naviguer ici et créer une grille de navigation
        - **Player Start** pour dire ou le joueur commence
        - **Landscape**, les montagnes de base, la map de base
        - **BP_Sky_Sphere**, module de UE très cool pour faire une base pour un ciel 
        - **SkyLight** couplé au SkySphere, permet de mettre de la luminosité sur le level
        - **LightMassImportanceVolume** Zone où la lumière sera calculée
        - **Basic Portail** Seul élément fixe de la map en 0 0 0

---
**Matériaux**
- **les lumières** on set juste une couleur et de l'émmissivité... ![](https://i.imgur.com/UB8OujJ.png)
- **le matériaux chromé** on met le coté metallic à fond, la rugosité pas trop forte puis la couleur de base avec des micro variation pour que ça ne soit pas trop "clean" ![](https://i.imgur.com/HkTCFlW.png)
- **Plastique** un peu comme le matériaux chromé, j'ai fait joujou ![](https://i.imgur.com/4x9zsl8.png)
- **les textes** on a juste set le calque de base avec le texte et magie c'est beau ![](https://i.imgur.com/V5qFLJi.png)
- **particule laser** j'ai mis en required le matériaux laser ![](https://i.imgur.com/I58E8NH.png), un spawn rate de 320 ![](https://i.imgur.com/uZsWoOh.png), une lifetime de 1seconde ![](https://i.imgur.com/Dsf8VbX.png), une initial size fixe de 10 ![](https://i.imgur.com/gUwPYzy.png), une initial velocité de -100 sur X ![](https://i.imgur.com/rT7blon.png) et une initial location fixe à 0 0 0

---
**UI**
- **ingame ui** utilisation partout de grid pour éviter les taille fixe en pixels qui font n'imp ![](https://i.imgur.com/ftVKQim.png)
- pour les menus, comme **Options**, **Credits**..., essayer d'avoir toujours le total en row égal à 20, la première ligne à 2, la suivante à 3 et l'avant dernière à 2 et la dernière à 1 afin d'être sûr que le titre et le bouton close/exit soit toujours de la même taille : ![](https://i.imgur.com/Rfu3VOE.png)
- plein de widget qui vont check le nombre restant de vie ou d'ennmis ou de munition... pour évoluer en continue. Exemple avec l'health bar : design ![](https://i.imgur.com/CDZ3sqR.png) code ![](https://i.imgur.com/rskP93L.png)
- **Minimap** mettre un overlay et une image, l'image sera un matériau qui évolue (ATTENTION, ce minimap material et son render associé sont dans le dossier du character car issus de sa camera... c'est peut etre pas la meilleure des logique): ![](https://i.imgur.com/XUom6BZ.png), ajout de point d'intéret sur l'overlay : ![](https://i.imgur.com/ocARe5B.png) construction et maj de la map : ![](https://i.imgur.com/Fhv1CRW.png)
    - **PointofInterest** pour la minimap, à la construction on va chercher l'icon de point d'intéret de l'acteur (ex: l'icon d'ennemi pour les ennemis) : ![](https://i.imgur.com/YKBTuVd.png) ensuite à chaque event tick... on fait des math pour calculer la position de l'icon... ![](https://i.imgur.com/7QS4AkO.png) Fonctions matthématiques annexes : ![](https://i.imgur.com/vDOE9S2.png)
    - **minimap_render** set par la camera zenitale sur le character, récupère l'image vue par la camera à chaque instant, on peut dire que c'est l'écran de la camera
    - **minimap_material** globalement, on set la texture minimap_render, on crop le contour pour faire un rond et on ajoute une légère bordure pour qu'elle soit mieux visible (encore une fois, full math): ![](https://i.imgur.com/dkTLTBj.png)
    - **POI_component** (situé à la racine du projet... pas la meilleure des idées...) possède une variable pour set l'icon qui sera retransmis au widget de la minimap : ![](https://i.imgur.com/PXT0YVE.png)
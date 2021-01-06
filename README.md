The Neon GITS
===

An IC06 project developed with Unreal Engine 4 by Thibault Santonja

---
---
---
# Notes projet

## 1. Ressources et présentation du projet
[lien git projet](https://gitlab.utc.fr/tsantonj/the_neon_gits)

[version Actuelle](https://drive.google.com/file/d/1p9iDx2h6CapTku1eQL9YIeXAC4bc-97_/view?usp=sharing)

[lien google sheet planning](https://docs.google.com/spreadsheets/d/1Xr9n_vt9y2RlpWiuXXkXmDvKhSmyRA22sAipUdPXf8A/edit?usp=sharing)

[prèsentation vidéo contenu alpha v0.2.5](https://drive.google.com/file/d/1lI6rOlypVaHmL1ioif5b4uoKDrsdqKoh/view?usp=sharing)

[Vidéo de présentation finale du projet](https://youtu.be/NWYJ-hLyF7w) : {%youtube NWYJ-hLyF7w %}

### 1.1. Présentation générale
**Intro**: Shooter / Die&Retry / RogueLite dans un univers Cyberpunk avec des salles à "nettoyer" et différentes zones composées de plusieurs salles et se finissant par un boss.
**Références**: Zone of the enders 2 (grosses vagues d'ennemies (des centaines)), Binding of Isaac (scénario simple, zones à nettoyer, Die&Retry), Hades (RogueLite), Doom (retour visuels jouissifs)
**Contexte**: environnement Retro futuriste / cyberpunk avec des néons, une prédominence de couleurs cyan / magenta
**Éléments Principaux**: Vaisseau du joueur, ennemis sous forme de horde
**Mode de jeu**: un joueur (coop ?)
**Interface**: 3D, clavier sourie + portabilité console ?
**Maquette Graphique**: Map simple, plate, avec décors (buildings...) simples. Ambiance de nuit avec des néons pour l'éclairage (référence à l'imaginaire cyberpunk, exemple avec le jeu Cyberpunk 2077: [![](https://cdn.cdkeys.com/700x700/media/catalog/product/c/y/cyberpunk.jpg)]()https://cdn.cdkeys.com/700x700/media/catalog/product/c/y/cyberpunk.jpg), ou avec Ghost in the Shell (artwork de Alex Feliksovich) : [![](https://www.artstation.com/artwork/nqrYo)](https://www.artstation.com/artwork/nqrYo)

**Étude de l'existant** : [![](https://i.imgur.com/z2nVCuR.png)](https://i.imgur.com/z2nVCuR.png)
**Étude technique** : [![](https://i.imgur.com/V0XAasP.png)](https://i.imgur.com/V0XAasP.png)

### 1.2. Inspiration graphiques
#### 1.2.1. **Artstation Ghost in the Shell**
[Artstation Ghost in the Shell](https://www.artstation.com/search?q=ghost%20in%20the%20shell&sort_by=relevance)

- David Bocquillon Carrasco (Concept Artist)
[![](https://cdnb.artstation.com/p/assets/images/images/012/253/253/large/david-bocquillon-carrasco-ghost-in-the-shell.jpg?1533830732)](https://www.artstation.com/artwork/4ARqk)


#### 1.2.2. **Artstation Hong Kong**
[Artstation Hong Kong](https://www.artstation.com/search?q=Hong%20kong&sort_by=relevance)

- Sergey Zabelin (Concept Artist)
![https://www.artstation.com/artwork/G89oz](https://cdna.artstation.com/p/assets/images/images/000/544/340/large/sergey-zabelin-hong-kong-street-patrol-1920.jpg?1443928378)

- DOFRESH. (Concept Artist)
[![](https://cdna.artstation.com/p/assets/images/images/009/559/158/large/dofresh-10-hk-landscape.jpg?1519669944)
![](https://cdnb.artstation.com/p/assets/images/images/009/559/171/large/dofresh-100-bridge-light-on.jpg?1519669897)](https://www.artstation.com/artwork/O6qlJ)


#### 1.2.3. **ArtStation Cyberpunk**
[](https://www.artstation.com/search?q=cyberpunk&sort_by=relevance)

- Alexander Dudar (Concept Artist chez CD Projekt)
[![](https://cdnb.artstation.com/p/assets/images/images/009/089/349/large/alexander-dudar-city-view.jpg?1517073959)](https://www.artstation.com/artwork/NQN5J)

- Tarmo Juhola (Concept Artist, Architect)
[![](https://cdnb.artstation.com/p/assets/images/images/020/057/175/large/tarmo-juhola-cyberpunkcity-kopio.jpg?1566192051)](https://www.artstation.com/artwork/XBEbml)

- Donglu Yu (Concept Artist)
[![](https://cdna.artstation.com/p/assets/images/images/011/919/898/large/donglu-yu-cyberpunk-rooftop-view-small.jpg?1532089994)](https://www.artstation.com/artwork/nAZK4)
[![](https://cdna.artstation.com/p/assets/images/images/011/919/896/large/donglu-yu-cyberpunk-rooftop-view-crop01.jpg?1532089849)](https://www.artstation.com/artwork/nAZK4)

- Rutger van de Steeg (Landscape Artist)
[![](https://cdnb.artstation.com/p/assets/images/images/020/275/221/large/rutger-van-de-steeg-saturation.jpg?1567107880)](https://www.artstation.com/artwork/4bBw64)

- Petter Steen (VFX Artist)
[![](https://cdna.artstation.com/p/assets/images/images/018/819/052/large/petter-steen-render-08-1001.jpg?1560859004)](https://www.artstation.com/artwork/4bz39k)

- James Daly (Concept Artist / Comic Book Artist)
[![](https://cdnb.artstation.com/p/assets/images/images/029/885/051/large/james-daly-untitled-1-1.jpg?1598934315)](https://www.artstation.com/artwork/W2AoOQ)

- G liulian (Concept Artist) 
- [![](https://cdna.artstation.com/p/assets/images/images/024/207/936/large/g-liulian-.jpg?1581644573)](https://www.artstation.com/artwork/DxDKEE)


### 1.2. Inspiration Gameplay / Jeu
- [Binding of Isaac](https://fr.wikipedia.org/wiki/The_Binding_of_Isaac): principe de différentes salles (niveaux pour nous) et de différentes zones / profondeurs de cave, se finissant par un boss. Plein de stuff pour boost ses stats, différents perso (avec stats différentes)
- [Zone of the Enders](https://fr.wikipedia.org/wiki/Zone_of_the_Enders:_The_2nd_Runner): Grosse vagues à tuer, assez rapide, lock fire
- [Prototype de Pause Process](https://www.youtube.com/watch?v=I6XDJr_lczE): assez rapide, lock fire, ambiance Cyberpunk
- [HADES](https://fr.wikipedia.org/wiki/Hades_(jeu_vid%C3%A9o)): Die&Retry, RogueLike, choix de stuff / compromis, différentes salle se finissant par un Boss puis niveau différent, différentes armes
- [Cyberpunk 2077](https://fr.wikipedia.org/wiki/Cyberpunk_2077): pour l'inspiration graphique + thèmes abordés

### 1.3. Inspiration Lore
- [Ghost in the Shell (1995)](https://fr.wikipedia.org/wiki/Ghost_in_the_Shell): base des thèmes cyberpunk, [lien de ma critique / présentation de Ghost in the Shell (1995) pour Cinem'UT](https://assos.utc.fr/lefil/article/?paper=234)
- [Cyberpunk 2077](https://fr.wikipedia.org/wiki/Cyberpunk_2077): pour l'inspiration graphique + thèmes abordés cyberpunk {%youtube B6dXb6rPy08 %}
- [Ex Machina](https://fr.wikipedia.org/wiki/Ex_machina_(film)) rapport à la robotique et à l'IA, frontière vivant / pas vivant, humain / pas humain, rapport à soi...
- [Lain](https://fr.wikipedia.org/wiki/Serial_Experiments_Lain) notion de réalité, rapport à soi, de conscience


### 1.4. Inspiration musicale
- dark synthwave, retro electro, cyber electro
    - {%youtube _4SXjfVeGEQ %}
    - {%youtube m9H4kmrrDa0 %}
    - {%youtube eEteJhp-Ezs %}
    - {%youtube xB6zgo_dT9c %}
    - {%youtube ph_IhNseCBc %}
- Sarys (stremaer francais) {%youtube PLCay4HPF75fWwLL7zepT9UYFF3u7_AtM9}
	- {%youtube Qis-65_VsGg %}
	- {%youtube ITAQM5beb2M %}
	- {%youtube vl4aDkesNfA %}
	- {%youtube f3Qx7ZzYS0I %}

	
---
## 2. TECHNIQUE : Programmation, Description du code...
[Plugins UE4](https://www.pixstacks.com/best-free-unreal-engine-plugins)

### 2.1. Bon tutos en vrac
- [Level design Pause Process](https://www.youtube.com/watch?v=SjRo6k2XvCo){%youtube SjRo6k2XvCo %}
- [Get Started with UE4](https://docs.unrealengine.com/en-US/GettingStarted/index.html?utm_source=launcher&utm_medium=ue&utm_campaign=uelearn) Doc de Unreal Engine
- [Introduction to Blueprints](https://docs.unrealengine.com/en-US/Engine/Blueprints/GettingStarted/index.html) Doc de Unreal Engine 
- [Blender, bases à un peu avancé, faire un MacBook en 4 vidéos](https://www.youtube.com/watch?v=d93bu-2rnOE) très très bon tuto bien complet et expliqué et relativement court ! Première vidéos : {%youtube d93bu-2rnOE %}
- [Modeling a character BaseMesh in Blender (Tutorial)](https://www.youtube.com/watch?v=WlaMfIgS2ns) {%youtube WlaMfIgS2ns %}
- [Playliste pour la minimap (ici la vidéo 5, celles a retenir sont notamment la une à trois)](https://www.youtube.com/watch?v=VQxp5fh3AWs) {%youtube VQxp5fh3AWs %}
- [Procedural building](https://www.youtube.com/watch?v=_qVXrVV-ipc ) mais je ne l'ai pas utilisée
- [Blender Building Shop](https://www.youtube.com/watch?v=qv714UBCVg4) {%youtube qv714UBCVg4 %}
- [Bon tuto complet pour les particules](https://www.youtube.com/watch?v=Y4ZEka9j4CA) {%youtube Y4ZEka9j4CA %}
- [animation dans les widget](https://www.youtube.com/watch?v=iMt3oVzYwyA) {%youtube iMt3oVzYwyA %}
- [Bon tuto matériaux](https://www.youtube.com/watch?v=lngF4VVNER4&list=PLZlv_N0_O1gbQjgY0nDwZNYe_N8IcYWS-) : {%youtube lngF4VVNER4 %}


---
## 3. Lore
### 3.1. Synopsis
In the future, people will be living massively on an online network with the help of microchips that allow them to connect to it. The secret of this chip's code called "The Neon GitS", is kept in a server called "The Temple" where it is possible to materialize via the chip. This code is and must remain protected as its possibilities are immense. 

Regularly, hackers try to retrieve and crack this code in order to use its infinite possibilities, including its power of mental control over chipped humans or robots and AI's. The "Guardians" are thus there to protect this code from any intrusion attempts.

Since a few days, a rather powerful pirate manages to quickly break the firewalls of the temple to the safe protecting the code. As the Guardian of the Temple, it is your duty to quickly regain control and chase this pirate away...

### 3.2. Story through the game
- possibility to choose another Guardian (different weapons / abilities)
- retry again and again to get new parts of the story: each time we kill the final boss (the pirate), he tells us something new to understand who is he, why does he want the code, what does he want to do with it...
- possibility to add some philosophical reflexions on AI, natrure, what does it mean to be "alive", cyborg, robots... 
> reference to GitS, Blade Runner... (many SF)

### 3.3. Histoire complète

Histoire découpée en 10 parties correspondant aux 10 fins possibles. Vous pouvez retrouver [l'histoire complète ici](https://gitlab.utc.fr/tsantonj/the_neon_gits/-/blob/master/story.md)

---
## 4. Explication code

### 4.1. Bonus
Dans le viewport : 
- **LOCKBOX**: Collision sphere ne doit pas détecter la lock box (sinon le joueur va prendre le bonus "en le regardant") -> dans collision: Collision preset sur custom, tout mettre en Overlap sauf la case Lock_Box
- **ROTATING MOVEMENT** set sur l'axe Z de 60.0°/s 
- **PointOfInterest** set de l'image "bonus" pour qu'il s'affiche sur la minimap
- **EFFET "VIRTUEL"** Les mesh ne doivent pas être "solides" -> set les Collision Perset des mesh sur "NoCollision"
- **UNSPAWN AUTO** Pour les bonus temporaire, au begin play, mettre un delay et le détruire
- **SPAWN LOCATION** le Spawn location en Z est set au begin play à 30.0 et reste fixe
- **OVERLAP ACTION** set son action et le faire unspawn à la fin
- **TAG** mettre un tag à "self" : "Bonus": ![](https://i.imgur.com/bLJnchI.png) + "Upgrade" dans le cas des upgrades

### 4.2. Building
- **TAG** mettre un tag à "self": "Building"
- **RANDOM CONSTRUCTION**: dans le construction script mettre de la randomization de taille et de forme : ![](https://i.imgur.com/oD145BQ.png), ![](https://i.imgur.com/yvv7aAz.png)
- **BUILDING COLOR THROUGH LEVEL**: evolve color building follow the level![](https://i.imgur.com/LaIpYUL.png)


### 4.3. Portail
- **Portail visibility & action** au begin play, désactiver la trigger box et set la visibilité du portail à faux, faire un petit delay (7 seconde pour la zone de bonus + Boss) puis appeler la fonction qui check le nombre d'ennemis avec un Set Timer by Function Name pour boucler sur ce check toutes les secondes (ou moins) : ![](https://i.imgur.com/eWS5zqy.png) Dans l'event tick, check si la visibilité du portail doit changer (est-il déjà actif (is_active) et doit-il etre généré (generate_portail)) : ![](https://i.imgur.com/o76DMUK.png)
- **Portail triggered & Save des stats entre les levels** quand le portail est triggered, avant de changer de level on save dans le game instance toutes les stats du joueur (stats qui peuvent évoluer d'un level à l'autre suivant les bonus gagnés ![](https://i.imgur.com/PFDXWeW.png)
- **Point of Interest** set le Point of interest Icon


### 4.4. Projectiles
- **Damage** à leurs création (begin_play) check les damages du joueur et les set au projectile
- **Prévenir la surcharge** mettre un timer à la fin du begin_play pour que le projectile s'autodétruise au bout de quelques secondes
- **Overlap** Check si c'est un ennemie et lui appliquer des dommages ou si c'est autre chose et donc simplement passer à l'étape suivante : faire un son et une animation avant de disparaitre : ![](https://i.imgur.com/mQIaKTu.png)
- **Laser Lock Damages** au begin play, le laser lock prend les damages du joueur * 2.5 afin d'être plus puissant
> **TODO** Commenter et faire l'emmission d'un son + animation à la destruction du projectile 


### 4.5. PlayerCharacter
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


### 4.6. Ennemis
- **Tags** mettre le tag "Ennemy" sur les chaque "self" des ennemis : ![](https://i.imgur.com/0LeTky9.png)
- **Check Health** lancement au begin play, même fonctionnement que pour le joueur
- **Ennemy_Attack** appel au begin play s'il attaque dès le début avec une Timer by Function Name si besoin, ou au moment où un event se passe (joueur dans le champ de vu de l'ennemis)
- **Undermap spawn** prevenir cela en tuant l'ennemi... sale histoire... ![](https://i.imgur.com/dnIJWkS.png)
- **Touch player** via la collision box, quand elle triggered le joueur, elle lui applique des dégats ![](https://i.imgur.com/I3zfzjn.png) **!!! ATTENTION !!!** Il FAUT que la trigger box ne trigger pas le lockbox (sinon le joueur prend des dégats en regardant l'ennemi lol) set les collision de la trigger box ![](https://i.imgur.com/tGz8OkO.png)
- **Point of Interest** set l'ennemy Icon


#### 4.6.1. Basic
![](https://i.imgur.com/GIaaTOr.png)  
suit le joueur

#### 4.6.2. Boeing
![](https://i.imgur.com/wJuVAWA.png)  
va en ligne droite et rebondi sur les murs

#### 4.6.3. Citern
![](https://i.imgur.com/DnfLJ93.png)  
lache des mines

#### 4.6.4.Bus
![](https://i.imgur.com/IiKCnYD.png)  
fait pop des Basic

#### 4.6.5. Turret
![](https://i.imgur.com/OiyM5xu.png)  
c'est une tourrelle basique cherchant à tirer sur le joueur (fixe), j'ai tenté la prédiction de position mais... j'ai pas passé assez de temps  
![](https://i.imgur.com/Oju57qZ.png)

#### 4.6.6. Generator
![](https://i.imgur.com/TZijgWW.png)  
fait pop des Basic (fixe)

### 4.6.7. Boss
Deux boss ont pour le moment été créés pour les deux premiers niveaux. Leurs apparences sont pour le moment les mêmes mais leurs attaques différentes:
[![](https://i.imgur.com/FunXetX.png)](https://i.imgur.com/FunXetX.png)

Mouvements aléatoires:
[![](https://i.imgur.com/42e9L0y.png)](https://i.imgur.com/42e9L0y.png)

Health bar des boss:
On ajoute le widget correspondant à la health bar au viewport du boss, puis, sachant que la health bar n'a pas de Character spécifié, on set le character sur lequel est attaché la health bar avec "self" (donc avec le boss). Ca permet de réutiliser la même health bar pour chaque boss (ou même d'autres characters si besoin).
[![](https://i.imgur.com/ZOmMCp5.png)](https://i.imgur.com/ZOmMCp5.png)

Le widget en lui même est très basique, c'est une progress bar de 100 x 10 px, avec un background semi transparent et une couleur de remplissage bien voyante.
[![](https://i.imgur.com/VJEigL4.png)](https://i.imgur.com/VJEigL4.png)

Le taux de remplissage est ensuite saisi dans un bind / Blueprint:
[![](https://i.imgur.com/gMcEKmH.png)](https://i.imgur.com/gMcEKmH.png)
Il est intéressant de noter ici le cast pour adapter la barre au boss 1 et 2 ici.

#### 4.6.7.1. Spécificités boss zone 1
Ses attaques:
- Attaque de base qui tire des lasers tout autour de lui (changement de couleurs quelques secondes avant de tirer)
- Spawn d'ennemis basiques (pour détourner l'attention du joueur)

#### 4.6.7.2. Spécificités boss zone 2
Ses attaques:
- Attaque de base qui tire des lasers toutes les secondesen direction du joueur
- Spawn d'ennemis basiques (pour détourner l'attention du joueur)
- 3 colonne de feu venant du ciel aléatoirement autour du joueur
- 1 colonne de feu venant du ciel à l'endroit du joueur apparaissant toutes les 0.5secondes pendant 5 secondes (donc 10 sky fire au total)

Le "Sky fire" est un acteur composé des particules associés: 
[![](https://i.imgur.com/fMrd3Ha.png)](https://i.imgur.com/fMrd3Ha.png)
pendant 1.5 secondes, une simple trace sera au sol avec seulement quelques particules puis l'animation se jouera à fond. Pendant ce laps de temps le joueur pourra fuir la zone, ensuite il prendra des dégats (la trigger box sera activée (=is_damaging))
[![](https://i.imgur.com/mr36hEZ.png)](https://i.imgur.com/mr36hEZ.png)

Pour les particules, 500 particules sont émises de base par seconde, mais j'ai appliqué un rate dessus, ainsi de 0 à 1.35 secondes, on a une courbe linéaire allant de 10% à 20% de 500particules/s, puis entre 1.35 et 1.5, on fait un rapide drop à 0 avant de produire rapidement 100% des particules jusqu'à la fin de l'animation (5secondes (dans Required > Duration > Emitter Duration)):
[![](https://i.imgur.com/ItK07kW.png)](https://i.imgur.com/ItK07kW.png)


#### 4.6.7.3. Spécificités boss zone 3
**TODO** Boss final ?

#### 4.6.7.4. Spécificités boss zone 4
**TODO** Boss final ?



### 4.7. Game Mode
- **Spawn ennemis** pour chaque ennemi, trouver un point sur la map où faire spawn l'ennemi mais prévenir le spawn sur un batiment (Z > 200) puis suivant la zone, faire spawn les ennemies correspondant (zone suivant le level) : ![](https://i.imgur.com/x9mWVce.png)
- **Spawn par zone** spawn spécifiques à la zone + appel de la zone d'en dessous de mani![](https://i.imgur.com/7Fsylqm.png)


### 4.8. Game Instance
liste des variables stockés au 31/10/2020 : 
![](https://i.imgur.com/qaNPGCM.png)


### 4.9. Map
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
- **Home_map** Cette carte est la carte principale du jeu. Nous n'avons pas osé mais il serait intéressant de faire de cette map le point central du jeu. Le wiki du jeu y est déjà présent, différentes options aussi et cetera. 


### 4.10. Matériaux
- **les lumières** on set juste une couleur et de l'émmissivité... ![](https://i.imgur.com/UB8OujJ.png)
- **le matériaux chromé** on met le coté metallic à fond, la rugosité pas trop forte puis la couleur de base avec des micro variation pour que ça ne soit pas trop "clean" ![](https://i.imgur.com/HkTCFlW.png)
- **Plastique** un peu comme le matériaux chromé, j'ai fait joujou ![](https://i.imgur.com/4x9zsl8.png)
- **les textes** on a juste set le calque de base avec le texte et magie c'est beau ![](https://i.imgur.com/V5qFLJi.png)
- **particule laser** j'ai mis en required le matériaux laser ![](https://i.imgur.com/I58E8NH.png), un spawn rate de 320 ![](https://i.imgur.com/uZsWoOh.png), une lifetime de 1seconde ![](https://i.imgur.com/Dsf8VbX.png), une initial size fixe de 10 ![](https://i.imgur.com/gUwPYzy.png), une initial velocité de -100 sur X ![](https://i.imgur.com/rT7blon.png) et une initial location fixe à 0 0 0
- **Cube néon**, différentes intances d'un matériaux de type cube dont on peut changer les couleurs du cube + grâces à différentes fonctions, les arrêtes sont lumineuses (intensité peut être changée, couleur...) : ![](https://puu.sh/H4ifg/37fcb0854d.png) différentes créées (permet d'alléger et de ne pas refaire le matériaux à chaque fois) : [![](https://puu.sh/H4ifN/b4096bf7e3.png)](https://puu.sh/H4ifN/b4096bf7e3.png)
    > exemple d'une instance du matériaux : [![](https://puu.sh/H4iiH/c216b12173.png)](https://puu.sh/H4iiH/c216b12173.png)

### 4.11. UI
- **ingame ui** utilisation partout de grid pour éviter les taille fixe en pixels qui font n'imp ![](https://i.imgur.com/ftVKQim.png)
- pour les menus, comme **Options**, **Credits**..., essayer d'avoir toujours le total en row égal à 20, la première ligne à 2, la suivante à 3 et l'avant dernière à 2 et la dernière à 1 afin d'être sûr que le titre et le bouton close/exit soit toujours de la même taille : ![](https://i.imgur.com/Rfu3VOE.png)
- plein de widget qui vont check le nombre restant de vie ou d'ennmis ou de munition... pour évoluer en continue. Exemple avec l'health bar : design ![](https://i.imgur.com/CDZ3sqR.png) code ![](https://i.imgur.com/rskP93L.png)
- **Minimap** mettre un overlay et une image, l'image sera un matériau qui évolue (ATTENTION, ce minimap material et son render associé sont dans le dossier du character car issus de sa camera... c'est peut etre pas la meilleure des logique): ![](https://i.imgur.com/XUom6BZ.png), ajout de point d'intéret sur l'overlay : ![](https://i.imgur.com/ocARe5B.png) construction et maj de la map : ![](https://i.imgur.com/Fhv1CRW.png)
    - **PointofInterest** pour la minimap, à la construction on va chercher l'icon de point d'intéret de l'acteur (ex: l'icon d'ennemi pour les ennemis) : ![](https://i.imgur.com/YKBTuVd.png) ensuite à chaque event tick... on fait des math pour calculer la position de l'icon... ![](https://i.imgur.com/7QS4AkO.png) Fonctions matthématiques annexes : ![](https://i.imgur.com/vDOE9S2.png)
    - **minimap_render** set par la camera zenitale sur le character, récupère l'image vue par la camera à chaque instant, on peut dire que c'est l'écran de la camera
    - **minimap_material** globalement, on set la texture minimap_render, on crop le contour pour faire un rond et on ajoute une légère bordure pour qu'elle soit mieux visible (encore une fois, full math): ![](https://i.imgur.com/dkTLTBj.png)
    - **POI_component** (situé à la racine du projet... pas la meilleure des idées...) possède une variable pour set l'icon qui sera retransmis au widget de la minimap : ![](https://i.imgur.com/PXT0YVE.png)

## 5. Blender

Ce projet a été l'occasion pour moi de découvrir et de manipuler Blender. Ce logiciel de modélisation 3D a été utilisé pour créer la ville de la HomeMap et quelques éléments comme les PNJ, le portail et le trophé de cette même HomeMap.

### 5.1. city
pour la ville, demanière assez simple j'ai créer une surface avec des particules properties, où j'y ai associé différentes collection de buildings (HLM / Skycrapper / ...) : ![](https://puu.sh/H4iL0/5c3f6f00ed.png) ![](https://puu.sh/H4iMb/a7a869f6e9.png)

### 5.2. PNJ
Pour la majorité des modèles 3D, il n'y a rien de très compliqué, c'est de la modélisation basique de Blender. Voici un des exemple :
 ![](https://puu.sh/H4iNN/474bcf1d76.png)


---

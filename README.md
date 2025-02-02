![URLs](https://github.com/Afig-Asso/entreprises/actions/workflows/url.yml/badge.svg) 

# Listing d'entreprises en Informatique Graphique 
## Compléter/Modifier les informations 
  - Envoyez un email à contact[at]asso-afig.fr avec vos informations
  - Ou faites un push-request sur le dépot.
## Utilisation de la base en locale 
  - `data.yaml`: Base de données des entreprises 
  - `keywords.yaml`: Mots clés 

### Générer un site après modification: 
```
python scripts/generate.py 

```
Génère les fichiers suivants: 
- README.md: Vue des entreprises au format markdown pour github. 
- json/data.json: Base de donnée accessible pour générer des pages web dynamique. 
### Arguments 
```
generate.py [-c] [-C] 
  -c --checkValidity: Check coherence of keyword and accessibility of URLs.
        Do not exit if errors are detected (see -C for this). 
  -C --checkValiditywithFailure: Check coherence of keyword and accessibility of URLs.
        Quit if errors are detected.
```
### Site web: 
Le répertoire site/ contient un example de page web dynamique chargée dynamiquement depuis le fichier json présent sur github.
### Action push sur github: 
Après un push sur github, les éléments suivants sont mis à jours:
- La nouvelle base est vérifiée localement avec `python generate.py -C`
- Le contenu de site/ est déployé sur une page github.io: https://afig-asso.github.io/entreprises/


## Listing 

* **[2 minutes](http://2minutes.fr/)**  
  * _Studio production dessins animés._
  * **Localisation**: Paris, Angoulème, Canada, China
  * **Domaine scientifique/technique**: Modélisation, Animation
  * **Domaine d'application**: Cinéma/Films d'Animation/VFX


* **[2d3D Animations](https://www.2d3d-animations.com)**  
  * _Studio de production de films d'animations._
  * **Localisation**: Angoulème
  * **Domaine scientifique/technique**: Modélisation, Animation
  * **Domaine d'application**: Cinéma/Films d'Animation/VFX
  * [_Jobs_](https://www.2d3d-animations.com/emploi/)


* **[AMD](https://www.amd.com/)**  
  * _Développement de processeurs et cartes graphiques: développement matériel et logiciel._
  * **Localisation**: USA, International
  * **Nombres d'employés**: 16000
  * **Domaine scientifique/technique**: Hardware, Synthèse d'image, IA, Web/Cloud/Big Data, Visualisation, Autres
  * **Domaine d'application**: Générique
  * [_Jobs_](https://www.amd.com/en/corporate/careers)


* **[Adobe](https://www.adobe.com/fr/)**   :red_circle: _[Entreprise majeure en Graphique avec R&D avancée en France]_
  * _Dévelopement d'outils créatifs_
  * **Remarque**: _Centre de recherche à Paris_
  * **Produits**: Photoshop, Substance 3D, Premiere, Illustrator, etc.
  * **Localisation**: USA, Canada, France/Paris, UK, India, International
  * **Nombres d'employés**: 20000
  * **Domaine scientifique/technique**: Synthèse d'image, Modélisation, Animation, Design/Fabrication
  * **Domaine d'application**: Art/Evenementiel, Cinéma/Films d'Animation/VFX


* **[Alma](https://www.alma.fr/nos-activites/logiciels-cfao/)** (Alma Logiciels CFAO) 
  * _Edition de logiciels de Conception et Fabrication d'objets manufacturés._
  * **Localisation**: Grenoble,  Lyon,  Tarbes,  Paris,  Annecy
  * **Domaine scientifique/technique**: Modélisation, Design/Fabrication
  * **Domaine d'application**: Mécanique/Ingénierie civile, Automobile/Navigation/Aviation, Robotique/Systèmes autonomes
  * [_Jobs_](https://recrutement.alma.fr/cv/)


* **[Alteia](https://alteia.com/)**  
  * _Logiciels de Vision et IA._
  * **Domaine scientifique/technique**: Imagerie, Vision
  * **Domaine d'application**: Mécanique/Ingénierie civile
  * [_Jobs_](https://alteia.com/company/#careers)


* **[Anatoscope](https://www.anatoscope.com/)**  
  * _Logiciels pour l'anatomie 3D numérique personnalisé (orthopedie, dentaire, radiologique)._
  * **Localisation**: Grenoble,  Montpellier
  * **Domaine scientifique/technique**: Modélisation, Visualisation, Simulation, Géométrie, Imagerie, Reconstruction, Analyse de données
  * **Domaine d'application**: Médical/Biologique
  * [_Jobs_](https://www.anatoscope.com/offres-demploi-grenoble-montpellier/)


* **[Animal Logic](https://animallogic.com/)**  
  * _Studio de création d'animation et effets visuels._
  * **Localisation**: Australia/Sydney, Canada/Vancouver, USA/Los Angeles
  * **Nombres d'employés**: 1300
  * **Domaine scientifique/technique**: Synthèse d'image, Modélisation, Animation, Simulation
  * **Domaine d'application**: Cinéma/Films d'Animation/VFX


* **[Apple](https://www.apple.com/)**  
  * **Localisation**: USA/Cupertino, International
  * **Nombres d'employés**: 160000
  * **Domaine scientifique/technique**: Web/Cloud/Big Data, IA, Autres
  * **Domaine d'application**: Générique
  * [_Jobs_](https://jobs.apple.com)


* **[Artefacto](https://www.artefacto-ar.com/)**  
  * _Développement d'applications pour la Réalité augmentée pour la visualisation dans le domaine de l'immobilier, de l'industrie, ou de l'entrainement._
  * **Localisation**: Rennes (Betton)
  * **Domaine scientifique/technique**: VR/AR, Visualisation, Modélisation
  * **Domaine d'application**: Architecture/Immobilier, Entrainement/Formation/Serious Game
  * [_Jobs_](https://www.artefacto-ar.com/en/carrieres/)


* **[Autodesk](https://www.autodesk.com/)**  
  * _Logiciels 3D, CAO, Conception, Design_
  * **Produits**: Maya,  3DS Max,  AutoCAD
  * **Localisation**: USA, Canada, India, UK, Singapor, Norway, International
  * **Nombres d'employés**: 10000
  * **Domaine scientifique/technique**: Synthèse d'image, Modélisation, Animation, Visualisation, Simulation, Design/Fabrication
  * **Domaine d'application**: Cinéma/Films d'Animation/VFX, Automobile/Navigation/Aviation, Mécanique/Ingénierie civile
  * [_Jobs_](https://www.autodesk.com/careers/overview)


* **[BUF](https://buf.com/)**  
  * _Création d'effets visuels (VFX) pour le cinéma._
  * **Localisation**: Paris
  * **Nombres d'employés**: 60
  * **Domaine scientifique/technique**: Synthèse d'image, Modélisation, Animation, Vision
  * **Domaine d'application**: Cinéma/Films d'Animation/VFX
  * [_Jobs_](https://buf.com/jobs/)


* **[Beam Me Up Games](https://bmugames.com/)**  
  * _Analyse de comportement pour le jeu vidéo._
  * **Localisation**: Canada/Montréal
  * **Domaine scientifique/technique**: Analyse de données, IA
  * **Domaine d'application**: Jeu Vidéo


* **[Bentley](https://www.bentley.com/)**  
  * _Développement de logiciels pour l'ingénierie civile (simulation, visualisation, acquisition). Détient l'ancienne entreprise Francaise de reconstruction 3D "Acute 3D"._
  * **Localisation**: USA, UK, Netherlands, France/{Paris, Sophia}, Singapore, New Zealand, India
  * **Nombres d'employés**: 4000
  * **Domaine scientifique/technique**: Visualisation, Simulation, Vision, Modélisation, Reconstruction, Design/Fabrication
  * **Domaine d'application**: Mécanique/Ingénierie civile, Automobile/Navigation/Aviation
  * [_Jobs_](https://jobs.bentley.com/search)


* **[Blippar](https://www.blippar.com/)**  
  * _Développement d'outils pour la création de contenu en AR sur smartphone_
  * **Localisation**: UK/Londres
  * **Domaine scientifique/technique**: VR/AR, Modélisation, Web/Cloud/Big Data
  * **Domaine d'application**: Loisir Interactif/Immersion/Metavers
  * [_Jobs_](https://www.blippar.com/careers#Jobs)


* **[CLO Virtual Fashion](https://www.clo3d.com/en/)**  
  * _Logiciel de simulation de vêtements virtuels_
  * **Produits**: Marvelous Designer,  Clo3D
  * **Localisation**: Korea, USA, International
  * **Domaine scientifique/technique**: Modélisation, Animation, Simulation, Design/Fabrication
  * **Domaine d'application**: Cinéma/Films d'Animation/VFX, Mode/Vêtements/Accessoires
  * [_Jobs_](https://jobs.lever.co/clovirtualfashion)


* **[Christie](https://www.christiedigital.com/en-gb)**  
  * _Systèmes de projections vidéo et d'immersion (projecteur de cinéma, ecrans géants, projection immersive, etc)._
  * **Localisation**: USA/California, Canada/Ontario
  * **Nombres d'employés**: 2000
  * **Domaine scientifique/technique**: VR/AR, Visualisation
  * **Domaine d'application**: Art/Evenementiel, Loisir Interactif/Immersion/Metavers


* **[Dassault Systèmes](https://www.3ds.com/fr/)**   :red_circle: _[Entreprise majeure en Graphique avec R&D avancée en France]_
  * _Logiciels de CAO, Design et Simulation._
  * **Produits**: Catia,  SolidWorks
  * **Localisation**: France/{Paris, Aix en Provence}, USA, China, International
  * **Nombres d'employés**: 20000
  * **Domaine scientifique/technique**: Modélisation, Simulation, Visualisation, Géométrie, Design/Fabrication
  * **Domaine d'application**: Automobile/Navigation/Aviation, Mécanique/Ingénierie civile, Médical/Biologique
  * [_Jobs_](https://careers.3ds.com/)


* **[Disney](https://www.disneystudios.com/)**  
  * **Remarque**: _<a href="https://studios.disneyresearch.com/">Disney Research</a> implanté à Zurich est l'un des plus gros centre de R&amp;D en graphique._
  * **Localisation**: USA, International
  * **Nombres d'employés**: 220000
  * **Domaine scientifique/technique**: Synthèse d'image, Modélisation, Animation, Visualisation, Design/Fabrication, VR/AR, IA, Autres
  * **Domaine d'application**: Cinéma/Films d'Animation/VFX, Loisir Interactif/Immersion/Metavers, Robotique/Systèmes autonomes
  * [_Jobs_](https://jobs.disneycareers.com/)


* **[ESI](https://www.esi-group.com/)**  
  * _Entreprise Francaise de simulation, prototypage virtuel, et Double numérique pour l'industrie_
  * **Localisation**: France/{Paris, Lyon, Bordeaux}, International
  * **Nombres d'employés**: 1000
  * **Domaine scientifique/technique**: Modélisation, Simulation
  * **Domaine d'application**: Automobile/Navigation/Aviation, Sécurité/Défense, Mécanique/Ingénierie civile
  * [_Jobs_](https://www.esi-group.com/join-us)


* **[Effigy 3D](https://effigy-3d.com/)**  
  * _Studio de creation digitale 3D: Scan 3D, Mocap, Avatars._
  * **Localisation**: Paris
  * **Domaine scientifique/technique**: Animation, Acquisition, VR/AR
  * **Domaine d'application**: Cinéma/Films d'Animation/VFX


* **[Epic Games](https://www.epicgames.com/site/en-US/home)**  
  * _Développeur de jeu et du moteur 3D Unreal Engine_
  * **Localisation**: USA, International
  * **Nombres d'employés**: 2000
  * **Domaine scientifique/technique**: Synthèse d'image, Modélisation, Animation, Simulation
  * **Domaine d'application**: Jeu Vidéo, Cinéma/Films d'Animation/VFX
  * [_Jobs_](https://www.epicgames.com/site/en-US/careers/jobs)


* **[Gameloft](https://www.gameloft.com/)**  
  * _Développement de jeux vidéos orientés mobile._
  * **Localisation**: France/Paris, USA, Canada, Spain, India, International
  * **Nombres d'employés**: 3600
  * **Domaine scientifique/technique**: Synthèse d'image, Modélisation, Animation, Web/Cloud/Big Data
  * **Domaine d'application**: Jeu Vidéo
  * [_Jobs_](https://www.gameloft.com/corporate/fr/jobs/apply/)


* **[Google](https://about.google/)**  
  * **Remarque**: _<a href="https://ai.google/">Google AI</a> est une entité de recherche développant des projets en graphique_
  * **Localisation**: USA/Mountain View, International
  * **Nombres d'employés**: 140000
  * **Domaine scientifique/technique**: Web/Cloud/Big Data, IA, Vision, Autres
  * **Domaine d'application**: Générique
  * [_Jobs_](https://careers.google.com/)


* **[Harfang3D](https://www.harfang3d.com/)**
  * _Outils de visualisation 3D en temps réel, C++ et Python, pour l'industrie, la recherche et l'enseignement._
  * **Localisation**: Orléans, France
  * **Domaine scientifique/technique**: Outil 3D temps réel, simulation, VR.
  * **Domaine d'application**: Industrie, Recherche, Formation


* **[Illumination MacGuff](https://www.macguff.com/)**  
  * _Création de films d'animation et d'effets visels._
  * **Localisation**: Paris
  * **Nombres d'employés**: 60
  * **Domaine scientifique/technique**: Synthèse d'image, Modélisation, Animation, Vision
  * **Domaine d'application**: Cinéma/Films d'Animation/VFX
  * [_Jobs_](https://buf.com/jobs/)


* **[Kinetix](https://www.kinetix.tech/)**  
  * _Création d'animation 3D d'humain à partir de capture de video sur smartphone._
  * **Localisation**: Paris
  * **Domaine scientifique/technique**: Vision, Animation, IA, Acquisition
  * **Domaine d'application**: Loisir Interactif/Immersion/Metavers
  * [_Jobs_](https://kinetix-tech.welcomekit.co/)


* **[Kitware](https://www.kitware.com/)**  
  * _Développement de logiciels scientifique, de visualisation, et de compilation. Beaucoup de développement open-source._
  * **Localisation**: USA, France/Lyon
  * **Nombres d'employés**: 200
  * **Domaine scientifique/technique**: Visualisation, Reconstruction, Simulation, Géométrie, Imagerie, Vision, IA, Analyse de données
  * **Domaine d'application**: Médical/Biologique, Automobile/Navigation/Aviation, Mécanique/Ingénierie civile, Autres
  * [_Jobs_](https://www.kitware.com/careers/)


* **[Lectra](https://www.lectra.com/fr)**  
  * _Logiciels de conceptions professionels: Model, Automobile, Ameublement_
  * **Localisation**: France/Paris, International
  * **Nombres d'employés**: 1500
  * **Domaine scientifique/technique**: Modélisation, Simulation, Design/Fabrication
  * **Domaine d'application**: Mode/Vêtements/Accessoires


* **[Les Tontons Truqueurs](https://www.lestontonstruqueurs.com/)**  
  * _Prévisualisation et VFX en temps réels._
  * **Localisation**: Paris
  * **Domaine scientifique/technique**: Synthèse d'image, Vision, VR/AR
  * **Domaine d'application**: Cinéma/Films d'Animation/VFX


* **[Mercenaries Engineering](http://guerillarender.com/)**  
  * _Développement de logiciel de rendu (Guerilla Render) et d'animation (Rumba) pour la création de films d'animation._
  * **Produits**: [Guerilla Render](http://guerillarender.com/), [Rumba Animation](https://rumba-animation.com/)
  * **Localisation**: Paris
  * **Domaine scientifique/technique**: Synthèse d'image, Animation
  * **Domaine d'application**: Cinéma/Films d'Animation/VFX


* **[Microsoft](https://www.microsoft.com/)**  
  * **Remarque**: _<a href=\"https://www.microsoft.com/en-us/research/research-area/graphics-multimedia/?\">Microsoft research</a> est active en informatique graphique._
  * **Localisation**: USA/Redmond, International
  * **Nombres d'employés**: 180000
  * **Domaine scientifique/technique**: Web/Cloud/Big Data, IA, Synthèse d'image, Autres
  * **Domaine d'application**: Générique
  * [_Jobs_](https://www.amd.com/en/corporate/careers)


* **[MocapLab](https://www.mocaplab.com/)**  
  * _Studio et R&amp;D pour la capture de mouvement._
  * **Localisation**: Paris (Aubervilliers)
  * **Domaine scientifique/technique**: Acquisition, Analyse de données, Animation
  * **Domaine d'application**: Cinéma/Films d'Animation/VFX, Loisir Interactif/Immersion/Metavers, Jeu Vidéo


* **[ModaLive](https://www.modalive.fr/)**  
  * _Virtual try-on de vêtements de mode._
  * **Localisation**: Paris
  * **Domaine scientifique/technique**: Acquisition, Reconstruction, Géométrie, Vision, Modélisation
  * **Domaine d'application**: Mode/Vêtements/Accessoires


* **[NVidia](https://www.nvidia.com/)**  
  * _Développement de cartes graphiques materiel et logiciel_
  * **Remarque**: _NVidia Research est présent partout dans le monde, dont en France._
  * **Localisation**: USA, International
  * **Nombres d'employés**: 13000
  * **Domaine scientifique/technique**: Synthèse d'image, IA, Hardware, Simulation, Web/Cloud/Big Data, Visualisation
  * **Domaine d'application**: Générique


* **[Pixel Wizards](https://pixel-wizards.com/)**  
  * _Studio de jeu vidéos indie, jeux en tours par tours_
  * **Localisation**: Paris
  * **Domaine scientifique/technique**: Modélisation, Animation, IA
  * **Domaine d'application**: Jeu Vidéo
  * [_Jobs_](https://pixel-wizards.com/jobs/)


* **[Presagis](https://www.presagis.com/en/)**  
  * _Simulation d'environment dynamique pour la prédiction à large échelle (infrastructure, défense, désastre, etc)_
  * **Localisation**: Canada/Montréal, USA/Orlando, France/Paris, Italy, UK
  * **Domaine scientifique/technique**: Modélisation, Animation, Simulation, IA, Analyse de données
  * **Domaine d'application**: Sécurité/Défense, Automobile/Navigation/Aviation, Mécanique/Ingénierie civile
  * [_Jobs_](https://cae.wd3.myworkdayjobs.com/Presagis/jobs)


* **[Qarnot Computing](https://qarnot.com/)**  
  * _Calculs sur le Cloud._
  * **Localisation**: Paris (Montrouge)
  * **Domaine scientifique/technique**: Web/Cloud/Big Data
  * **Domaine d'application**: Générique
  * [_Jobs_](https://qarnot.com/en/recruiting)


* **[Shot Over](https://shotover.com/)**  
  * _Système d'imagerie gyro stabilisée pour des prises de vues sur véhicules (cinéma, sécurité, défense, etc)._
  * **Localisation**: USA/Colorado
  * **Domaine scientifique/technique**: Acquisition, Imagerie, Vision
  * **Domaine d'application**: Cinéma/Films d'Animation/VFX, Art/Evenementiel, Sécurité/Défense


* **[SideFX](https://www.sidefx.com/)**  
  * _Développement du logiciel de VFX Houdini - Modélisation et Animation procédurale, simulation._
  * **Produits**: Houdini
  * **Localisation**: Canada/Toronto
  * **Domaine scientifique/technique**: Modélisation, Animation, Simulation
  * **Domaine d'application**: Cinéma/Films d'Animation/VFX
  * [_Jobs_](https://www.sidefx.com/careers/)


* **[SpirOPS](https://www.spirops.com/)**  
  * _Approches d'IA pour l'industrie et le loisir: foule virtuelles, véhicules autonomes, assistants_
  * **Localisation**: Paris
  * **Domaine scientifique/technique**: IA, Animation, Simulation
  * **Domaine d'application**: Loisir Interactif/Immersion/Metavers, Automobile/Navigation/Aviation, Jeu Vidéo
  * [_Jobs_](https://www.spirops.com/jobs.php?lg=en)


* **[TVPaint](https://www.tvpaint.com/)**  
  * _Logiciel d'animation 2D._
  * **Localisation**: Metz
  * **Domaine scientifique/technique**: Animation
  * **Domaine d'application**: Cinéma/Films d'Animation/VFX


* **[Take-Two Interactive](https://www.take2games.com/)**  
  * _Développement de jeux vidéo, et détenant d'autres entreprises (Rockstar, 2K)._
  * **Localisation**: USA, France/Paris (Palaiseau), International
  * **Nombres d'employés**: 6000
  * **Domaine scientifique/technique**: Synthèse d'image, Modélisation, Animation, Simulation
  * **Domaine d'application**: Jeu Vidéo
  * [_Jobs_](https://careers.take2games.com/jobs)


* **[Technicolor Creative Studios](https://www.technicolorcreative.com/)**  
  * _Entreprise d'animation et de VFX international possédant les studios MPC, The Mill, Mikros Animation, et Technocolor Games._
  * **Localisation**: France/Paris, Canada/{Montréal, Toronto}, USA/{New York, Chicago, Los Angeles}, UK/London, International
  * **Nombres d'employés**: 12000
  * **Domaine scientifique/technique**: Synthèse d'image, Animation, Modélisation, VR/AR
  * **Domaine d'application**: Cinéma/Films d'Animation/VFX, Loisir Interactif/Immersion/Metavers
  * [_Jobs_](https://www.technicolorcreative.com/jobs/)


* **[Thales](https://www.thalesgroup.com/fr)**   :small_orange_diamond: _[Entreprise majeure avec R&D avancée en France]_
  * _Multi-nationale française à forte composante R&amp;D développant des produits pour l'aérospatiale, la défense, et la sécurité tel que la biométrie._
  * **Localisation**: France/Paris, International
  * **Nombres d'employés**: 80000
  * **Domaine scientifique/technique**: Reconstruction, Vision, Imagerie
  * **Domaine d'application**: Sécurité/Défense, Automobile/Navigation/Aviation
  * [_Jobs_](https://www.thalesgroup.com/fr/candidat)


* **[The Foundry](https://www.foundry.com/)**  
  * _Développement de logiciels pour la création 3D et VFX_
  * **Localisation**: UK, USA, Australia
  * **Domaine scientifique/technique**: Synthèse d'image, Modélisation
  * **Domaine d'application**: Cinéma/Films d'Animation/VFX
  * [_Jobs_](https://apply.workable.com/foundry/)


* **[UVR](https://www.united-vr.com/)** (United Visual Researchers) 
  * _Logiciel d'analyse optique et de rendu avancé (spectral, lumière polarisée)._
  * **Localisation**: Paris
  * **Domaine scientifique/technique**: Synthèse d'image, Simulation
  * **Domaine d'application**: Générique
  * [_Jobs_](https://uvr.welcomekit.co/)


* **[Ubisoft](https://www.ubisoft.com/)**   :red_circle: _[Entreprise majeure en Graphique avec R&D avancée en France]_
  * _Développeur de jeux vidéo Français, possédant de nombreux studios à l'international_
  * **Remarque**: _Ubisoft a créé une entité de recherche à Bordeaux appelée "La Forge" à l'image de celle existante à Montréal._
  * **Localisation**: France/{Paris, Bordeaux, Annecy}, Canada/{Montreal, Toronto}, USA/{San Francisco, New York, Atlanta}, Inde, Allemagne, Pologne, International
  * **Nombres d'employés**: 20000
  * **Domaine scientifique/technique**: Synthèse d'image, Modélisation, Animation, Simulation
  * **Domaine d'application**: Jeu Vidéo
  * [_Jobs_](https://www.ubisoft.com/en-us/company/careers)


* **[Unity Technologies](https://unity.com/)**   :red_circle: _[Entreprise majeure en Graphique avec R&D avancée en France]_
  * _Développement du moteur de jeu Unity_
  * **Remarque**: _<a href="https://unity-grenoble.github.io/website/">Equipe de recherche</a> en France dans le domaine du rendu à Grenoble_
  * **Localisation**: USA, France/{Paris, Grenoble}, International
  * **Nombres d'employés**: 5000
  * **Domaine scientifique/technique**: Synthèse d'image, Modélisation, Animation, Simulation
  * **Domaine d'application**: Jeu Vidéo, Cinéma/Films d'Animation/VFX
  * [_Jobs_](https://careers.unity.com/)


* **[YellowScan](https://www.yellowscan-lidar.com/)**  
  * _Scan LiDAR pour application industrielles_
  * **Localisation**: Montpellier (Saint-Clément-de-Rivière)
  * **Domaine scientifique/technique**: Acquisition, Reconstruction, Géométrie
  * **Domaine d'application**: Histoire/Archéologie/Muséographie, Mécanique/Ingénierie civile
  * [_Jobs_](https://www.yellowscan-lidar.com/about/career/)



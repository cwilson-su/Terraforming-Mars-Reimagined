# $${\color{red}Terraforming-Mars-Reimagined}$$
A simulation of terraforming Mars, blending procedural generation, simple AI dynamics, and environmental management systems.
[Screencast from 2024-04-23 22-48-50.webm](https://github.com/user-attachments/assets/00edf2ca-f6f3-4ed8-a545-816ba4493a46)

## $${\color{green}French \space Version.  \space Find  \space English  \space version  \space further  \space below}$$

### Important : Cet exécutable ne peut etre lancé qu’à partir d’une machine avec OS Windows. Si vous rencontrez l’erreur « There is no app installed for DOS/Windows Executable files », utilisez un émulateur Windows.

### Description du Projet
Inspiré du célèbre jeu de société Terraforming Mars lancé en 2016 par FryxGames (https://fryxgames.se/product/terraforming-mars/), ce projet est une simulation interactive basée sur une représentation de Mars, combinant génération procédurale, intelligence artificielle, et gestion de paramètres environnementaux. L'application explore des concepts tels que la terraformation, la gestion des ressources, les dynamiques proie-prédateur, et les systèmes environnementaux réactifs. Vous y découvrirez un écosystème où les humains travaillent pour rendre Mars habitable tandis que des martiens tentent de perturber leurs efforts.

Le fichier pdf « rapport_TerraformingMars.pdf » contient plus de détails et d’analyses sur cette simulation.

### Fonctionnalités Principales
- <b>Génération procédurale de la carte :</b> Utilisation de l'algorithme Perlin Noise pour générer dynamiquement une carte isométrique représentant Mars, divisée en régions distinctes (océans, forêts, villes).
- <b>Modèle SEIR pour épidémies :</b> Intégration d'un modèle épidémiologique SEIR (Susceptible, Exposed, Infected, Recovered) simulant la propagation des maladies dans les populations humaines.
- <b>Systèmes de terraformation réactifs :</b> Simulation des impacts environnementaux tels que l'augmentation de l'oxygène et la régulation de la température grâce à la plantation d'arbres et la création d'océans.
- <b>Gestion d'événements aléatoires :</b> Implémentation d'événements dynamiques tels que des tempêtes de sable, incendies de forêts, et destructions causées par les martiens.
- <b>Systèmes environnementaux interactifs :</b> Visualisation des niveaux d'oxygène et de température avec des compteurs dynamiques et des effets visuels.
- <b>IA des personnages :</b> Développement d'une intelligence artificielle pour les humains (travail, reproduction, fuite) et pour les martiens (destruction, attaque).
- <b>Mécanique jour/nuit :</b> Cycle temporel influençant le comportement des personnages et les interactions avec l'environnement.
- <b>Drones autonomes :</b> Déploiement de drones capables de détecter et d'éteindre les incendies déclenchés sur la carte.
- <b>Interface utilisateur (UI) :</b> Menu principal avec navigation intuitive, barres de progression pour les paramètres environnementaux et affichage des statistiques en temps réel.
- <b>Interactions proie-prédateur :</b> Simulation des dynamiques entre les martiens prédateurs et les humains proies, avec des comportements adaptés selon la proximité.

### Comment Utiliser l'Application
#### Lancer l’application
Attention : Un .exe n'est pas le projet Unity complet
    • Le fichier .exe est un build (version compilée) de votre projet, prêt à être exécuté sur un système Windows.
    • Il n'inclut pas les fichiers sources, les scripts, les assets ou les configurations nécessaires pour ouvrir le projet dans Unit

Étapes :
1. Téléchargez le fichier `.exe` depuis ce dépôt.
2. Double-cliquez sur le fichier `.exe` pour lancer la simulation.
3. Un window va s'ouvrir avec un menu. 
	- i) Aller dans 'OPTIONS' pour selectionner la taille de la grille souhaite
	- ii) Confirmer votre choix avec le bouton 'CONFIRM'
	- iii) Appuyer sur 'PLAY' pour lancer la simulation
A noter que sauter le choix de la taille de la grille lancera la simulation avec une valeur par default(26)

#### Quitter l’application
- Sortir de l'application grace au bouton 'QUIT' dans le menu principal
- Si la simulation est deja lancee, appuyer sur Alt+F4 (ou 'Q' sur Mac) pour quitter completement l'application.

#### Navigation de la caméra
1. Zoom/Dézoom : Utilisez la molette de la souris pour ajuster le niveau de zoom sur la carte.
2. Déplacement : Maintenez le clic droit de la souris et déplacez-la pour explorer différentes parties de la carte.
3. Rotation : Maintenez la touche Alt et déplacez la souris pour ajuster l'angle de vision.

### Observation des événements
- État de la carte : Survolez différentes régions pour observer les zones en cours de terraformation.
- Événements dynamiques : Observez l'apparition des tempêtes de sable et des incendies directement sur la carte.
- Statistiques en temps réel : Surveillez les indicateurs d'oxygène, de température et de population dans l'interface utilisateur.
  
### Interagir avec l'environnement
- Les actions des humains et des martiens sont automatisées via des scripts d'intelligence artificielle. Cependant, vous pouvez observer leurs comportements en temps réel :
  - Humains : Repérez ceux qui plantent des arbres ou creusent des océans.
  - Martiens : Suivez leurs actions destructrices et notez les impacts sur l'environnement.
  - Drones : Regardez-les éteindre les incendies.


## $${\color{green}English  \space Version}$$

### Important: This executable file can only be run on a machine with a Windows OS. If you encounter the error “There is no app installed for DOS/Windows Executable files”, use a Windows emulator.

### Project Description
Inspired by the famous board game Terraforming Mars, released in 2016 by FryxGames (https://fryxgames.se/product/terraforming-mars/), this project is an interactive simulation based on a representation of Mars. It combines procedural generation, artificial intelligence, and environmental parameter management. The application explores concepts such as terraforming, resource management, predator-prey dynamics, and reactive environmental systems.

You’ll discover an ecosystem where humans work to make Mars habitable while Martians attempt to disrupt their efforts.

The PDF file "rapport_TerraformingMars.pdf", in French, contains additional details and analysis about this simulation.

### Main Features
- <b>Procedural Map Generation:</b> Utilizes the Perlin Noise algorithm to dynamically generate an isometric map of Mars, divided into distinct regions (oceans, forests, cities).
- <b>SEIR Model for Epidemics:</b> Implements the SEIR epidemiological model (Susceptible, Exposed, Infected, Recovered) to simulate disease spread among human populations.
- <b>Reactive Terraforming Systems:</b> Simulates environmental impacts such as increased oxygen and regulated temperature through tree planting and ocean creation.
- <b>Random Event Management:</b> Integrates dynamic events such as sandstorms, forest fires, and Martian-caused destruction.
- <b>Interactive Environmental Systems:</b> Visualizes oxygen and temperature levels with dynamic counters and visual effects.
- <b>Character AI:</b> Develops artificial intelligence for humans (tasks, reproduction, fleeing) and Martians (destruction, attacks).
- <b>Day/Night Cycle:</b> A time-based mechanic influencing character behavior and interactions with the environment.
- <b>Autonomous Drones:</b> Deploys drones capable of detecting and extinguishing fires on the map.
- <b>User Interface (UI):</b> Includes a main menu with intuitive navigation, progress bars for environmental parameters, and real-time statistics display.
- <b>Predator-Prey Interactions:</b> Simulates dynamics between Martian predators and human prey with behavior adapted to proximity.

### How to Use the Application
#### Launching the Application
Important: An .exe file is not a complete Unity project.
- The .exe file is a build (compiled version) of your project, ready to be executed on a Windows system.
- It does not include the source files, scripts, assets, or configurations required to open the project in Unity.

Steps:
1. Download the .exe file from this repository.
2. Double-click the .exe file to launch the simulation.

Using the Executable:
1. Launch the executable TerraformingMars3.0.exe.
2. A window with a menu will appear.
    - i) Go to "OPTIONS" to select the desired grid size.
    - ii) Confirm your choice with the "CONFIRM" button.
    - iii) Click "PLAY" to start the simulation.
    Note: Skipping the grid size selection will start the simulation with the default value (26).
Quitting the Application
- Exit the application via the "QUIT" button in the main menu.
- If the simulation is already running, press Alt+F4 (or Q on Mac) to completely exit the application.

Camera Navigation
1. Zoom/Unzoom: Use the mouse scroll wheel to adjust the zoom level on the map.
2. Movement: Hold the right mouse button and move the mouse to explore different parts of the map.
3. Rotation: Hold the Alt key and move the mouse to adjust the viewing angle.

Observing Events
- Map State: Hover over different regions to observe areas undergoing terraforming.
- Dynamic Events: Watch sandstorms and fires appear directly on the map.
- Real-Time Statistics: Monitor oxygen, temperature, and population indicators in the user interface.

Interacting with the Environment
- Actions by humans and Martians are automated via AI scripts. However, you can observe their behaviors in real time:
  - Humans: Spot those planting trees or digging oceans.
  - Martians: Follow their destructive actions and note the environmental impacts.
  - Drones: Watch them extinguish fires.


$${\color{lightgreen} \space Screenshots}$$
$${\color{lightgreen}Captures \space d'écran}$$

Pre-terraformation:
![image](https://github.com/user-attachments/assets/dc78ad06-b127-482b-8883-3c09844089e9)
Post-terraformation:
![image](https://github.com/user-attachments/assets/e475ffdd-c147-4fdd-99eb-c1337fa133b1)

 

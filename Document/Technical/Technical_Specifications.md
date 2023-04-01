# Technical Specification Document for Catley's Revenge

## Introdution

The goal of this document is to provide a technical overview of the game Catley's Revenge. This document will be updated as the game progresses.

## Glossary

| Term          | Definition                                                                    |
| :------------ | :---------------------------------------------------------------------------- |
| Git           | A version control system.                                                     |
| GitHub        | A website that hosts Git repositories.                                        |
| UE4           | Unreal Engine 4.27                                                            |
| Blueprint     | A visual scripting language for UE4.                                          |
| Texture       | A file used to define the surface properties of a 3D object in UE4            |
| Material      | A file used to define the surface rendering of a 3D object in UE4             |
| Mesh          | A file used to define the geometry of a 3D object in UE4                      |
| Skeletal Mesh | A file used to define the geometry of a 3D object in UE4 that can be animated |
| Animation     | A file used to define the movement of a 3D object in UE4                      |
| NPC           | Non-Playable Character                                                        |
| AI            | Artificial Intelligence                                                       |
| UI            | User Interface                                                                |
| HUD           | Heads-Up Display                                                              |
| Open World    | A game world that is not restricted to a single level.                        |
| Level         | A single playable area in a game.                                             |
| Mixamo        | A website that provides free 3D models and animations, made by Adobe.         |

# Requirements

## Unreal Engine 4.27
We must use UE4.27 for this project. Because it's lightweight related to unreal engine 5.0 and it's easy to use.

## Git
We must use Git for version control and to work in team. and also we must use GitHub to host our project.

# Conventions

## Naming 
Folders, Files, Blueprints, Actors, Classes, Variables, Functions, and other assets should be named in a way that is easy to understand and consistent with the rest of the project. It's why we used PascalCase for folders, files, blueprints, actors, classes, and other assets. And we used camelCase for variables and functions.

## Folder Structure

We used this Folder structure for our project:

<details>
<summary>Folder Structure <b>Click to expand</b></summary>

```
Catley's Revenge
    ├── Content
    │   ├── Characters
    │   │   ├── Player
    |   |   |   ├── Meshes
    |   |   |   ├── Animations
    |   |   |   ├── Materials
    |   |   |   ├── Textures
    |   |   |   └── Controller
    │   │   └── NPC
    |   |       ├── Villagers
    |   |       |   ├── Meshes
    |   |       |   ├── Animations
    |   |       |   ├── Materials
    |   |       |   ├── Textures
    |   |       |   └── AI
    |   |       ├── Enemies
    |   |       |   ├── Meshes
    |   |       |   ├── Animations
    |   |       |   ├── Materials
    |   |       |   ├── Textures
    |   |       |   └── AI
    |   |       ├── Bosses
    |   |       |   ├── Meshes
    |   |       |   ├── Animations
    |   |       |   ├── Materials
    |   |       |   ├── Textures
    |   |       |   └── AI
    |   |       └── Animals
    |   |           ├── Meshes
    |   |           ├── Animations
    |   |           ├── Materials
    |   |           ├── Textures
    |   |           └── AI
    │   ├── Environment
    |   |   ├── Houses
    |   |   |   ├── Meshes
    |   |   |   ├── Materials
    |   |   |   └── Textures
    |   |   ├── Props
    |   |   |   ├── Meshes
    |   |   |   ├── Materials
    |   |   |   └── Textures
    |   |   ├── Vegetation
    |   |   |   ├── Meshes
    |   |   |   ├── Animations
    |   |   |   ├── Materials
    |   |   |   └── Textures
    |   |   ├── Maze
    |   |   |   ├── Meshes
    |   |   |   ├── Materials
    |   |   |   └── Textures
    |   |   └── Others
    |   |       ├── Water
    |   |       |   ├── Materials
    |   |       |   ├── Textures
    |   |       |   ├── Animations
    |   |       |   └── Sound
    |   |       ├── Sky
    |   |       |   ├── Materials
    |   |       |   ├── Textures
    |   |       |   └── Animations
    |   |       ├── Particles
    |   |       |   ├── Materials
    |   |       |   ├── Textures
    |   |       |   └── Animations
    |   |       └── Sound
    |   |       |   ├── Music
    |   |       |   ├── Ambiant Sound
    |   |       |   └── Sound Effects
    │   ├── UI
    |   |   ├── Fonts
    |   |   ├── Images
    |   |   ├── Main Menu
    |   |   |   ├── Play
    |   |   |   ├── Settings
    |   |   |   |   ├── Audio
    |   |   |   |   ├── Graphics
    |   |   |   |   └── Controls
    |   |   |   ├── Credits
    |   |   |   └── Quit
    |   |   ├── HUD
    |   |   |   ├── Pause
    |   |   |   ├── Save
    |   |   |   ├── Map
    |   |   |   ├── Quests
    |   |   |   ├── Audio Settings
    |   |   |   ├── Graphics Settings
    |   |   |   ├── Controls Settings
    |   |   |   └── Main Menu
    |   |   └── Others
    |   |       ├── Loading Screen
    |   |       └── Death Screen
```
</details>

## Git

### Branches

We used theses branches for our project:
- Main
- Documents
- Prototype
- Demo
- Level Design
- Mechanics Design

### Commits

The commit message should be written in english and should be clear and concise, It should not exceed 50 characters and it should be meaningful.

# Assets

We have used theses websites to get assets for our project:
- [Mixamo](https://www.mixamo.com/)
- [Sketchfab](https://sketchfab.com/)
- [Craftpix](https://craftpix.net/)
- [Unreal Engine Marketplace](https://www.unrealengine.com/marketplace/en-US/store)
- [Universal Soundbank](https://universal-soundbank.com/)
- [cgtrader](https://www.cgtrader.com/)

## Environment
For the environment we mainly use a free open source asset from the Unreal Engine Marketplace called "FANTASTIC - Village Pack" by Tidal Flask Studios. With this asset we created the world of Catley's Revenge.
We have enlarged the map and added several locations like:
- a Second Village
- a Forest
- an Ocean
- a Mountain range
- a Maze


<br><img src="img/VillagePack.png" width="450"><br>

[__Link to the Asset__](https://www.unrealengine.com/marketplace/en-US/product/fantastic-village-pack)

## Characters

### Player

For the player character we use a free open source asset from Sketchfab called "Puss in Boots" by CVRxEarth. This asset is cartoony and realistic, there is also a skeletal mesh provided with this asset so that it can be easily animated. We also added a controller to the character to make it playable.

<br><img src="img/PlayerCharacter.png" width="450"><br>

[__Link to the Asset__](https://sketchfab.com/3d-models/puss-in-boots-9b657d49d8a847bdb141e156caf55003)

### Ennemies

For the ennemies we use the characters from Mixamo and cgtrader following you will find the different characters.

1. The Knight<br>
    <br><img src="img/Knight.png" width="250"><br>
    [__Link to the Asset__](https://www.mixamo.com/#/?page=1&query=paladin&type=Character)

2. The Assassin<br>
   <br><img src="img/Assassin.png" width="250"><br>
    [__Link to the Asset__](https://www.mixamo.com/#/?page=1&query=erika&type=Character)

3. The Bandit<br>
   <br><img src="img/Bandit.png" width="250"><br>
    [__Link to the Asset__](https://www.cgtrader.com/free-3d-models/character/man/fantasy-bandit)

4. The Brute<br>
   <br><img src="img/Brute.png" width="250"><br>
    [__Link to the Asset__](https://www.mixamo.com/#/?page=1&query=brute&type=Character)

### Villagers

For the villagers we have used a pack with 14 differents villager, this pack is open-source and come from Craftpix:
<br><img src="img/NPCs1.png" width="200">
<img src="img/NPCs2.png" width="200">
<img src="img/NPCs3.png" width="200">

[__Link to the Asset__](https://craftpix.net/freebies/free-medieval-3d-people-low-poly-models/?num=1&count=4&sq=peasant&pos=0)

### Antic Dealer
<br><img src="img/AnticDealer.png" width="250"><br>
[__Link to the Asset__](https://www.mixamo.com/#/?page=1&query=peasan&type=Character)

### Bosses
1. Boss #1<br>
    <br><img src="img/Boss1.png" width="250"><br>
    [__Link to the Asset__](https://www.mixamo.com/#/?page=1&query=warrok&type=Character)

2. Boss #2<br>
    <br><img src="img/Boss2.png" width="250"><br>
    [__Link to the Asset__](https://www.mixamo.com/#/?page=1&query=maw+j+laygo&type=Character)

### Animals
For the animals we have also used a pack with 10 different animals, this pack is open-source and come from Craftpix:

<br><img src="img/Animals1.png" width="200">
<img src="img/Animals2.png" width="200">
<img src="img/Animals3.png" width="200">

[__Link to the Asset__](https://craftpix.net/freebies/free-wild-animal-3d-low-poly-models/?num=1&count=49&sq=farm%20animals&pos=11)

## Sounds

### Music

For the music we have used the Universal Soundbank, we have used theses musics:
TODO
## Ambiant Sounds

For the ambiant sounds we have used the Universal Soundbank, we have used theses sounds:
TODO
## Sound Effects

For the sound effects we have used the Universal Soundbank, we have used theses sounds:
TDODO

## Animations

### Player

For the player animations we have used the animations from Mixamo following you will find the different animations.

1. Idle
    <br><img src="img/PlayerIdle.gif" width="250"><br>
    [__Link to the Asset__](LINK TO THE ASSET)

2. Walk
    <br><img src="img/PlayerWalk.gif" width="250"><br>
    [__Link to the Asset__](LINK TO THE ASSET)

3. Jump
    <br><img src="img/PlayerJump.gif" width="250"><br>
    [__Link to the Asset__](LINK TO THE ASSET)

4. In the air
    <br><img src="img/PlayerInAir.gif" width="250"><br>
    [__Link to the Asset__](LINK TO THE ASSET)

5. Landing
   <br><img src="img/PlayerLanding.gif" width="250"><br>
    [__Link to the Asset__](LINK TO THE ASSET)

6. Punch #1
    <br><img src="img/PlayerPunch1.gif" width="250"><br>
    [__Link to the Asset__](LINK TO THE ASSET)

7. Punch #2
    <br><img src="img/PlayerPunch2.gif" width="250"><br>
    [__Link to the Asset__](LINK TO THE ASSET)

8. Punch #3
    <br><img src="img/PlayerPunch3.gif" width="250"><br>
    [__Link to the Asset__](LINK TO THE ASSET)

9. Kick #1
    <br><img src="img/PlayerKick1.gif" width="250"><br>
    [__Link to the Asset__](LINK TO THE ASSET)

10. Kick #2
    <br><img src="img/PlayerKick2.gif" width="250"><br>
    [__Link to the Asset__](LINK TO THE ASSET)

11. Sword Attack #1
    <br><img src="img/PlayerSwordAttack1.gif" width="250"><br>
    [__Link to the Asset__](LINK TO THE ASSET)

12. Sword Attack #2
    <br><img src="img/PlayerSwordAttack2.gif" width="250"><br>
    [__Link to the Asset__](LINK TO THE ASSET)

13. Fighting Idle
    <br><img src="img/PlayerFightingIdle.gif" width="250"><br>
    [__Link to the Asset__](LINK TO THE ASSET)

14. Take Damage #1
    <br><img src="img/PlayerTakeDamage1.gif" width="250"><br>
    [__Link to the Asset__](LINK TO THE ASSET)

15. Take Damage #2
    <br><img src="img/PlayerTakeDamage2.gif" width="250"><br>
    [__Link to the Asset__](LINK TO THE ASSET)

16. Take Damage #3
    <br><img src="img/PlayerTakeDamage3.gif" width="250"><br>
    [__Link to the Asset__](LINK TO THE ASSET)

17. Death
    <br><img src="img/PlayerDeath.gif" width="250"><br>
    [__Link to the Asset__](LINK TO THE ASSET)

### Ennemies

For the ennemies animations we have used the animations from Mixamo following you will find the different animations.

1. Idle
    <br><img src="img/EnnemieIdle.gif" width="250"><br>
    [__Link to the Asset__](LINK TO THE ASSET)

2. Walk
    <br><img src="img/EnnemieWalk.gif" width="250"><br>
    [__Link to the Asset__](LINK TO THE ASSET)

3. Attack
    <br><img src="img/EnnemieAttack.gif" width="250"><br>
    [__Link to the Asset__](LINK TO THE ASSET)

4. Take Damage
   <br><img src="img/EnnemieTakeDamage" width="250"><br>
    [__Link to the Asset__](LINK TO THE ASSET)

5. Death
    <br><img src="img/EnnemieDeath.gif" width="250"><br>
    [__Link to the Asset__](LINK TO THE ASSET)

### Bosses

For the bosses animations we have used the animations from Mixamo following you will find the different animations.

1. Idle
    <br><img src="img/BossIdle.gif" width="250"><br>
    [__Link to the Asset__](LINK TO THE ASSET)

2. Walk
    <br><img src="img/BossWalk.gif" width="250"><br>
    [__Link to the Asset__](LINK TO THE ASSET)

3. Attack
    <br><img src="img/BossAttack.gif" width="250"><br>
    [__Link to the Asset__](LINK TO THE ASSET)

4. Power-UP
    <br><img src="img/BossPowerUp.gif" width="250"><br>
    [__Link to the Asset__](LINK TO THE ASSET)

5. Take Damage
    <br><img src="img/BossTakeDamage" width="250"><br>
     [__Link to the Asset__](LINK TO THE ASSET)

6. Death
    <br><img src="img/BossDeath.gif" width="250"><br>
    [__Link to the Asset__](LINK TO THE ASSET)

### Villagers

For the Villagers animations we have used the animations from Mixamo following you will find the different animations.

1. Idle
    <br><img src="img/VillagersIdle.gif" width="250"><br>
    [__Link to the Asset__](LINK TO THE ASSET)

2. Walk
    <br><img src="img/VillagersWalk.gif" width="250"><br>
    [__Link to the Asset__](LINK TO THE ASSET)

3. Talk
        <br><img src="img/VillagersTalk.gif" width="250"><br>
    [__Link to the Asset__](LINK TO THE ASSET)


### Animals

For the animals animations we have made it ourselves following you will find the different animations.

1. Idle
    <br><img src="img/AnimalIdle.gif" width="250"><br>
    [__Link to the Asset__](LINK TO THE ASSET)

2. Walk
    <br><img src="img/AnimalWalk.gif" width="250"><br>
    [__Link to the Asset__](LINK TO THE ASSET)

# Gameplay
In this section we will explain the gameplay of the game.

## Controls
Here is the list of the controls of the game:

| Key                | Action           |
| ------------------ | ---------------- |
| Z                  | Move forward     |
| S                  | Move backward    |
| Q                  | Move left        |
| D                  | Move right       |
| Space              | Jump             |
| Left Shift         | Sprint           |
| Left Mouse Button  | Main Attack      |
| Right Mouse Button | Secondary Attack |
| Mouse Wheel        | Change Weapon    |
| E                  | Interact         |
| M                  | Open Map         |
| P                  | Show Quests      |
| Tab                | Target Ennemy    |
| Escape             | Pause            |
| 1                  | Weapon 1         |
| 2                  | Weapon 2         |
| 3                  | Weapon 3         |

<br><img src="img/ControlsList.png" width="500"><br>

## Combat

### Punch/Kick Combat

### Sword Combat

## Collectibles

## User Interface

# Level Design

## Map

### The Village

### The Forest
### The Mountains
### The Ocean
### The Maze

## Quests

### Tutorial

### Quest 1

### Quest 2

### Collect Collectibles

### The Maze
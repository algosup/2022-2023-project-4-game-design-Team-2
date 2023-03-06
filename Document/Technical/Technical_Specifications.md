# Technical Specifications

## Team

| Members | Rôle |
| :-: | :-: |
| [Grégory PAGNOUX]() | Project Manager |
| [Salaheddine NAMIR]() | Program Manager |
| [Pierre GORIN]() | Tech Leader |
| [Elise GAUTIER]() | Software Engineer |
| [Florent HUREAUX]() | Quality Assurance |




## Technical Specification Document for Single-Player Open-World Action Adventure RPG Game with Cat Protagonist

## Overview:

This technical specification document explains the technical details of a single-player open-world action adventure RPG game with a cat protagonist. The game will be developed using Unreal Engine 4.27 and will be available on Windows and macOS platforms. The document explains the game mechanics, hardware platform, control loop, game object data, data flow, game physics and statistics, and enemies.

## Overall Game Mechanics:

Hardware Platform or Operating System: The game will support Windows and macOS platforms. The minimum system requirements for Windows will be Windows 7/8/10/11 (64-bit), Quad-core Intel or AMD processor, 8 GB RAM, NVIDIA GeForce 660 GTX or AMD Radeon 7870 HD graphics card, and 5 GB free storage space. For macOS, the game will support macOS 10.15 or later, Quad-core Intel processor, 8 GB RAM, and 5 GB free storage space.

## External Code:

The game will use DirectX as a code library.

## Code Objects:

The game will use EXEs and DLLs for its code objects. The purpose and scope of the code objects being used, built, and compiled into the EXE and DLLs will be identified in the documentation.

## Control Loop:

The control loop of the game will involve the start-up code being transferred to the main game code. Functions involved will include movement, collision, and rendering. Drivers, multithreading, and memory management will also be important aspects.

## Game Object Data:

The game will use object-oriented programming with a class inheritance tree and class interface properties and functions. The game physics and statistics will be laid out and documented, including physics of the cat protagonist.

## Data Flow:

The overall data flow of the game will involve loading, storing, processing, transferring, restoring, and saving of data. References will be included and explained.

## Game Physics and Statistics:

The game physics and statistics will be implemented using codes that are flexible and modular so that it is easy to change while developing the game. The code will be optimized for versatility, speed, and neatness.

## Enemies:

The game will have several enemies to fight, including 2 Bosses. The enemies will have different levels of difficulty, with 4 types of difficulty:
- Easy
- Complicated
- Difficult
- Boss

The enemies will have different weapons or abilities, including swords, bows, fireballs, axes, and others. The bosses will be able to summon other enemies that are easier to beat.

## Main Character:

Our main character who is a cat will stand up and can do all the basic moves:
- Walk
- Run
- Jump
- Attack body to body
- Attack from a distance
- Dodge
- Escalating (if the feature does not take too long to implement)
- 
The Hero will suffer damage when in the water, as cats are often afraid of water and by default the cat sees well in the dark.

The hero can choose several ways to attack:
- Claws, melee attack: yes, ranged attack: no, availabilities: by default, speed: 9/10, degat: 5/10.
- The sword, melee attack: yes, ranged attack: no, availability: after a quest, speed: 6/10, thaw: 9/10. 
- The Hat: melee attack: no, ranged attack: yes, availability: after the tutorial, speed: 8/10, thaw: 7/10. 
The moving speed of the cat and the damage it can do will change as the game progresses.

## Conclusion:

This technical specification document has outlined the technical details of a single-player open-world action adventure RPG game with a cat protagonist. It includes information about the hardware platform, control loop, game object data, data flow, game physics and statistics, and enemies. The game will be developed using Unreal Engine 4.27 and will be available on Windows and macOS platforms. The game will have a variety of enemies with different levels of difficulty and weapons or abilities. The main character, a cat, will have several ways to attack, and its moving speed and damage will change as the game progresses.
# Functional Specifications

## Document Version

Last Update: 03/16/2023

## Team

| Members | Role |
| :-: | :-: |
| [Grégory PAGNOUX](https://github.com/Gregory-Pagnoux) | Project Manager |
| [Salaheddine NAMIR](https://github.com/T3rryc) | Program Manager |
| [Pierre GORIN](https://github.com/Pierre2103) | Tech Leader |
| [Elise GAUTIER](https://github.com/elisegtr) | Software Engineer |
| [Florent HUREAUX](https://github.com/florenthureaux) | Quality Assurance |


## Overview
The player incarnates an alley cat which lost some object it had previously and wants to bring it back and take revenge against the responsible of this.
The game is an open world, in which the player can do the main and side quests freely in a no linear way. The cat must bring back this hat and sword, learn new skills, face some enemies, bosses and complete a riddle to progress in the game.


## Target
This game is PEGI 7+, he's basically for everyone, he doesn't contain any  explicite content.
It's an mediaeval action adventure where the protagonist defeated some enemies with family friendly animation.


## Quality



#### Goal

During a period of 7 weeks, we must done:
- Create a One Sheet Document which gets an overview of the project.
- Create a prototype
- Create a demo
- Done the final game

#### Use case

| Use case| Actor(s) | Trigger | Pre/Post-condition | Main success scenario| Priority | Special Requirement | Note |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: |:-:| 
|Title screen|User |Open the game or select Return to Title screen in Quit option in the game|if the user is in the game -> Press escape/click on Quit -> Return to Title screen|User is in the title screen|Hight|None|None|
|Parameters(in Title menu)| User| Click on Parameters in the title screen|None|Display Commands and sound setting | Medium| None| Advance setting|
|Sounds (in Title screen)|User|Click on Sounds in Parametres|Click on Parameters/ Click on Sounds|User can change Sounds option|Hight|None|User can change sound (sound effect, background)|
|Commands (in Title screen)|User|Click on Commands in Parameters|Click on Parameters/ Click on Commands|User can change the Commands and also has a sheet cheat of the command|Hight|None|None|
|Minimap|User|On the HUD| None|Minimap display  |Medium| None | None|
|Quit(in Title screen)|User|Click on Quit|None|the user choose between quit or stay|Hight|None|None|
|Map|User|Press M|None|Display a bigger Map|Hight|None|None|
|Tags|User|Put a tags on the map and minimap|Press M / Right click to put the tags|User can put tags on the Map|Hight|None|User can put many tags at the same time and can remove the tags with right click again on the tags and an arrow is display on the minimap to guide the user to the location|
|Move Foward, Back, strafe Right and Left|User|Press Up, Down, Right and Left  or ZSDQ or WSDA on keyboard  |None|Charater move or strafe on expected way|Hight|None|User can keybind in setting menu|
|Jump|User| Press space | None|Charater Jump|Hight|None|User can keybind in setting menu |
|Sword attack|User| Left click on the mouse  |Press 2 or middle scroll wheel/ Left click|Character make sword attack|Hight|None|Wield sword with more powerful attack with better range but slightly slower speed attack, user can make combo attack depend of the timing it pressed  left click successively, medium recovery time |
|Claw attack|User|Left click on the mouse|Press 1 or up scroll whee/ Left click|Charater make claw attack |Hight|None| Attack by default weak but fast attack with short range, user can make combo attack depend of the timing it pressed left click successively, low recovery time |
|Slot|User|On the HUD|User select a weapon/ icon of selected weapon is bold |User see an icon in bold on which weapon is selected|Medium|None|Slot gain new icone depend of the progression|
|Run|User|Press Shift| None| Charater run| Medium|None|Run still active until run command is release |
|Interact| User|Press E| None|User can interact witn an element of the game|Hight|None|User point with the mouse whitch element it want to interact|
|Hat attack|User|Left click|Press 3 or down scroll wheel/Left click|Character throw an hat at long range|Medium|None|Throw an hat, hight recovery time |
|Second attack (kick)|User|Right click|None| Character perform a kick|Medium|None|Gap close move, knock back foes to a short range away of the character, hight recovery time|
|Pause menu|User| Press escape|None|User access to the Option menu|Medium|None|User can access to Save, Parameters and Quit option|
|Double jump|User|Press space twice|None|Character perform midair jump|Hight|None|Character can access a specific part of the level with it, perform only once until the character touch any solid surface|
|Dodge|User|Press Twice Right, D or Left Q, A|None|Character perform dodge movement on the right or on the left|Hight|None|Character can avoid some kind of attack of foes quickly, medium recovery time|
|Save|User|Click on Save in Pause menu|Press escape / click on Save|User can save this progress|Hight|None|Can save any time, restart at the nearest save point|
|Parameters(in Pause menu)|User|Click on Parameters in Pause menu|Press escape/ click on Parameters|User access to Parameters option|Hight|None|Access to sound and commands option|
|Sound(in Pause menu)|User|Click on Sound in Parameters(in Pause menu)|Press escape/click on Parameters -> Sound|User can change Sound option|Hight|None|User can change sound (sound effect, background)|
|Commands(in Pause menu)|User|Click on Commands in Parameters|Press escape/click on Parameters -> Commands|User access to Commands option|Hight|None|User can change this commands, can also access to the view of controls on a plan|
|Quit(in Pause menu)|User|Click on Quit in Pause menu|Press Escape/ Click on Quit|User has access to Quit,Stay and Return to title screen|Hight|None|User can Quit the game, return to title screen  or stay in the game|
|Money Overlay|User|On the HUD|None|Money Overlay is displayed on HUD|Hight|None|None|
|Semi-Circular Bars|User|On the HUD|None|Semi-Circular Bars display Heath Point and Stamina Point on separate bars|Hight|None|None|
















#### Dependices
Unreal Engine V.4.27

#### Risk

|Risk|impact | Probability |
|:-:|:-:|:-:|
|Technical Risks |Medium |Medium |
|Scope Creep | High | Medium/High |
|Resource Constraints | Low | Low |
|Team |Medium |Low |

#### Glossary

| Word | Definition |
| :-: | :-: |
|UI | User interface|
|UX|User experience|
|Recovery time|Period where the player can't use the same action during a certain amont of time|
|HUD|heads-up display|


## Cost

For the creation of our game, we only used free assets.

## Deadlines

| Project period | Content | Deliverary date | Done?|
| :-: | :-: | :-: | :-: |
|Week 1|[One Sheet Document](https://docs.google.com/document/d/1iRBUVD85ZWckOgvGBmtcu_85enL-P66Imu4cllDIVU4/edit)| 03/03/2023|Yes |
|Week 2| Working Prototype|10/03/2023|Yes |
|Week 3|Meeting report 1|17/03/2023||
|Week 4|Demo / Vertical Slice|24/03/2023||
|Week 5||||
|Weak 6|Final Game / Final Test |07/03/2023||

## Safety
 All sites used for our research were secure and no user data is required to play. The only data saved and used is the game data to save/load the player's game.
If the game bug, the computer of the user don’t crash.
## Environment
App : Unreal 4.27<br>
Languages : Blueprint / C++<br>
PC : Mac / Windows 7 → 11 / computer<br>
mouse and keyboard

## Resources

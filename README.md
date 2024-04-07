[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/YyUO0xtt)
# COMP2150  - Level Design Document
### Name: Takaaki Chi
### Student number: 47887729 

This document discusses and reflects on the design of your platformer level for the Level Design assessment. It should be 1500 words. Make sure you delete this and all other instructional text throughout the document before checking your word count prior to submission. Hint: You can check word count by copying this text into a Word or Google doc.

Your document must include images. To insert an image into your documentation, place it in the "DocImages" folder in this repo, then place the below text where you want the image to appear:

```
![Place any alt text here](DocImages/<IMAGE NAME AND FILE EXTENSION>)
```

Example:

![This is the alt text for an image!](DocImages/exampleimage.png)

## 1. Player Experience (~700 words)

### 1.1. Discovery
The Level begins with discovery, for the level waiting to be explored. The player learns about the main mechanics and hazards and how they can synergise with each other. An example is the first section. In the first section the player is introduced to basic platforming and a generous amount of health pickups to help familiarise the basic movements and combat systems. As the player progresses, they are introduced to new hazards individually to allow the player to understand their behaviour. The placement for checkpoints before and after hazardous areas allows the player to encounter the mechanics without punishing them too excessively. This allows the player to play around with the mechanics before moving on.

An example of this is the introduction to section 1 has a basic enemy that the player must manoeuvre around in order to not take damage. This introduces the movement and enemy to the player.

![Platforming to avoid enemies](DocImages/PlayerExpExample1.1.png)

### 1.2. Drama
The level maintains an intense dramatic curve with a variety of sections holding tension and relief throughout. This helps keep the player engaged as they go through each section. The player experiences a gradual increase in enemy placement and platforming, with calm areas such as hidden health caches sprinkled throughout with the option to retreat to a safer position. The addition of a different enemy variety such as the spitters and areas with high enemy density and traps create intense moments for the player and tests their reactions and strategies to minimise the risk of failure. Through moments that heighten tension this allows the player to find the need to retreat or find a safer area more satisfying. This helps the player maintain engagement and prevents gaming fatigue.


### 1.3. Challenge
The main challenges within the level revolves around precise platforming, combat and puzzle solving. To control the difficulty curve, the level takes into consideration the mechanics of enemies and enemy placement, this is combined with a gradual increase in difficulty for precise platforming and puzzles. For example the section 2 gives insight into the mechanisms that could be introduced such as trap doors and a new enemy type (the spitter) that is more easily countered using the gun awarded for completing the section, and in section 3 the player experience the combination of both the puzzle solving to engage the enemy to make the section easier. This tests the decision making and combat skills. By combining the mechanics to increase the complexity of challenges provides an opportunity for players to test their skills. The challenges gradually increase while maintaining a fair experience for the player encourages players to persist through challenging sections and rewards the player with a sense of accomplishment. 



### 1.4. Exploration
The level encourages the player to explore through its non linear and interconnected layout. By incorporating branching paths and interconnecting paths. This is the most prominent in section 2 with its branching puzzles that can be completed in any order. The player is insentivised to explore after a enemy dense area which could prove rewarding.
Section 2’s main focus is puzzle solving, building on the basic puzzle introduced to the player in section 1, with the addition of platforming and combat layered throughout. This Sections builds upon the puzzle solving aspect with the need to unlock multiple doors through activation of multiple buttons, these can be done in any order. This section is more open than the previous section and introduces a new enemy type making the need to explore for health caches more prominent. Once the puzzle is cleared the player is then rewarded with the gun however gets trapped. This allows the player to theorise how the previous owner of the gun came to be there. This introduces the mechanics of the gun and its potential for shooting far away enemies or elevated enemies more easily. This adds a sense of immersion to the player through its diverting paths and environmental storytelling.

![Diverting paths](DocImages/PlayerExpExample1.4.png)

## 2. Core Gameplay (~400 words)

### 2.1. Passthrough Platforms, Checkpoints, Chompers and Health Kit
Once the player enters the level, they are introduced with a passthrough platform to enter the main dungeon. This introduces them to the view of what they can pass through and what's solid.

Once dropped down they gather a checkpoint audio cue to alert that there is danger nearby, this is when they’re introduced to their first enemy chomper. The player cannot damage the enemy at this point which introduces the platforming element, allowing the player to manoeuvre themselves around the chomper to avoid damage.

Avoiding the chomper they are introduced to with a diverting path, if the player takes this path they are rewarded with a health cache which encourages the need for exploration. 

![Passable Platform, Checkpoints, Checkpoints, Chompers](DocImages/SB2.1.png)

### 2.2. Spikes and Moving Platforms
the player will notice a moving platform with a floor full of purple spikes, once on the moving platform. This introduces to the player that can platforms may move and the dangers of spikes

![Moving Platforms and Spikes](DocImages/SB2.2.png)


### 2.3. Keys and KeyDoor
The player’s eye catches the Key and when the key door visually changes, that hints at the player’s objective.

![Key and Door](DocImages/SB2.3.png)

### 2.4. Acid and Interactable Box
After crossing they are introduced to acid and a box blocking the main path, the player is introduced to both the pushing mechanics of the box and the box’s ability to act as a platform on acid along with a small platforming section

![Acid and Box](DocImages/SB2.4.png)

### 2.5. Weapon Pickup (Staff), Destructive object and Combat System
After this the player is introduced to the melee weapon pickup and its mechanic to break certain  pillars and walls. After this the player is reintroduced to the chompers which introduces the melee combat system

![Melee Pickup, Eestructive Object and Combat Systen](DocImages/SB2.5.png)

### 2.6. One Use Switch, PressurePad and TriggerDoor
A small easy puzzle that shows interactables such as the bridge and interactable objects after completing the puzzle the door opens, this is built upon in later section and prepares the Player.

![Switch, PressurePad and TriggerDoor](DocImages/SB2.6.png)

### 2.7.Spitters and Weapon Pickup (Gun)
the player is introduced to a new enemy type known as the spitter and can’t reach with its melee weapon so is forced to dodge past them

the player is introduced to the gun and a far away switch which frees the player and allows them to dispatch the spitters introduced earlier.
The majority of the core gameplay elements and mechanics are introduced in section 1 however the gun is withheld as in the 2D gamekit example, the player may rely on the gun more, during combat leaving little room for the player to know the mechanics of the melee weapon within combat. This is why the level introduces the gun as a reward later on and its mechanics that demonstrate its effectiveness in puzzles and combat. 

![Spitters and GunPickup](DocImages/SB2.7.png)



## 3. Spatiotemporal Design
A section on Spatiotemporal Design, which includes your molecule diagram and annotated level maps (one for each main section of your level). These diagrams may be made digitally or by hand, but must not be created from screenshots of your game. The annotated level maps should show the structure you intend to build, included game elements, and the path the player is expected to take through the level. Examples of these diagrams are included in the level design lectures.

No additional words are necessary for this section (any words should only be within your images/diagrams).
 
### 3.1. Molecule Diagram
![Molecule Diagram](DocImages/MoleculeDiagram.png)

### 3.2. Level Map – Section 1
![Section1](DocImages/Section1.png)
### 3.3.	Level Map – Section 2
![Section2](DocImages/Section2.png)
### 3.4.	Level Map – Section 3
![Section3](DocImages/Section3.png)


## 4. Iterative Design (~400 words)
During the development of each section, several changes are made to enhance the player’s experience based on continuous playtesting and observations. There were many changes made through playtesting such as platform placement to make a jump easier or harder, or enemy placement to force the player an intensive experience. Most of these themes would be less prominent in the first version of the level.

An example is the changes to section one, to make it not only introduce the main mechanics but a small combination of them too, such as the puzzle solving segment which introduces enemy clearing to make a puzzle easier to solve. This is built upon on a later section initially however didn’t show the mechanics of the single use switches and pressure pad. The section was initially linear so the placement of health kits in outcoves helps encourage the need for exploration to the player as health kits are rarer in later sections. The key door and key in section 1 was also changed placements to reduce the repetitive half of section 1 but backwards. 
Section one’s spike area was changed to also incorporate a moving platform as well as a wall to discourage the use of invisibility frames on the spike to bypass that area.

![Section 1 First Design](DocImages/IterativeComparison1.png)
![Section 1 Redesign](DocImages/IterativeComparison1.5.png)

Section 2’s layout was minorly changed to be more open with diverting pathways, this encourages the player to explore the sections of the map and helps emphasis on enemy clearing before puzzles.

![Section 2 First Design](DocImages/SectionTwoFD.png)
![Section 2 Redesign](DocImages/PlayerExpExample1.4.png)

There were changes to the pathways throughout section 3, initially the plan was after the player completes the puzzle in the first half, the player uses the crates throughout the puzzle to get to the door for the next second half of the section, a change was made for the player to move vertical above the door to bypass some of the precise platforming. This adds a non linear approach to an enemy dense section and allows a different approach.

![Section 3 First Design](DocImages/SectionThreeFD.png)
![Section 4 Redesign](DocImages/IterativeComparison2.png)

Overall, these iterative changes both improve on the flow and pacing of the level and enhance the gameplay aspects for the level, through continuous iterations to the level, it will create a more engaging and satisfying player experience.
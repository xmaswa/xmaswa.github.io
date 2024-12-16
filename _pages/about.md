---
permalink: /
title: "Diego's Portfolio"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


About me 
------
I'm a 23 year old developer, graduated in 2023 in CS. Currently working as a consultant I matured a strong interest towards algorithms and game development while I was approaching the very end of my academic career, I started with simple projects in Unity and then I switched to Unreal Engine in order to gain further knowledge and to face more difficult challenges. Right now on a journey to graphics programming and game engine development with the use of OpenGL, GLFW and C++.

Unity 
------
The very start consisted of relatively small tasks such as adding small features or fixing broken code in the provided projects by Unity itself. Thereafter I started my "major" project, a top down RPG, I spent quite a while (approximately 7/9 months) developing this game.

I explored many concepts regarding an RPG, I was greatly inspired by *Metin2* when developing this game.

These are some of the features that I was able to implement in the game:
1. **Character creation**: it wasn't bone oriented (such as deforming/manipulating bones) but rather choice oriented, i.e. selecting hair, eyebrows, type of face etc.. and also adjusting the color based on your likings. After the customization the player is prompted to choose the class of your character between warrior, mage and ninja.
1. **Skill system**: I implemented a simple skill tree, it consisted of single target, area of effect and buff skills. In order to get ahold of the powerful skills the player had to unlock the previous ones, hence why it's called a skill tree. The skills were further broken down in light sword & heavy sword for the warrior, daggers & bow for ninja, spellbook & magic spheres for mage.
1. **Crafting system**: the player could talk to the blacksmith and upgrade the weapons to a certain point, after which the weapon would evolve to a powerful one with better stats. Or you could craft it from scratch but at a higher prices and number of materials.
1. **Quest & Dialogue**: I actually used a wonderful plugin so I didn't make this from scratch, but it was helpful in order to read the documentation and explore every aspect of the plugin.
1. **Item stats**: every item was filled with stats for the solely purpose of powering the player, plus every item required a certain class in order to be worn. Every piece of equipment (armor and weapons) had their own effect based on the rarity. Moreover they provided a special status effect applied to the enemy only if the criteria met the requirements in order to be triggerable.
1. **Save system**: I made this from scratch, very basic save system, nothing complex.
1. **Classic RPG features**: looting, killing mobs, experience system (following Runescape's method), skill slot, chests' looting and so on.

Unreal Engine
------
After spending a while on Unity I eventually decided to switch to UE since I found out it was more industry oriented, I came to the conclusion that Unity was a good engine for indie/2D games and it does an honest job about it.

I started off with a basic souls-like in order to explore the engine, my 2 major projects in UE consisted of:
1. **Multiplayer 3rd person shooter**: spent quite a while with this one, the part I enjoyed the most about this was studying the concepts regarding the multiplayer performance issues due to the high ping, such as the Server Side Rewind (a technique of lag compensation, used for checking whether the hit was legit or not) and many others.
1. **LabyrAInth: an AI Powered Maze Runner**: I worked on a very interesting project with my co-workers, the game was an arcade revolved around beating AI generated labyrinths filled with traps, enemies. In the labyrinth you could also find powerups and weapons, which clearly were meant to be helpful for beating the challenges. With this project I didn't just learn how to execute efficiently the tasks provided by the leader, but I've also took the first step into developing a game with a team, so communication and coordination were a key to make this whole project work.
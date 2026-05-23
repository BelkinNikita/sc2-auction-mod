# 🎮 Auction — StarCraft II Custom Mode



## 📌 Overview



Auction is a large-scale custom StarCraft II game mode project developed since Autumn 2022.



The project is designed to work inside the "House Special Map" arcade map and adds multiple unique gameplay systems, randomization mechanics, strategic modes, and custom units.



The map was presented in a YouTube video:



https://www.youtube.com/watch?v=Hm7TsLJSxs0



---



## 🚀 Installation



The project is already configured for launching.



### 1. Download Includes folder



Place the folder:



```text

Includes

```



into:



```text

StarCraft II\\Mods

```



If the `Mods` folder does not exist, create it manually.



---



### 2. Download DATAModder.SC2Mod



Download:



https://drive.google.com/file/d/1vH6Al_cFgUZRX5W43yhkv-m8DYHECpR8/view



and place:



```text

DATAModder.SC2Mod

```



into:



```text

StarCraft II\\Mods\\Includes

```



---



### 3. Launch the game



Open:



```text

StarCraft II → Custom → Arcade

```



Find:



```text

House Special Map

```



The map will automatically detect the `Includes` folder and launch with the Auction mode enabled.



Original setup information:



https://docs.google.com/document/d/1NMkoAfWPTm6X4PJ5sUmw9KmPxT4ionzaNIx2uZm9UhQ/edit?usp=sharing



---



# 🎯 Main Game Modes



## 💰 Auction



Players buy randomly selected unit sets using a betting system.



---



## 🎲 Roulette



An addition to Auction where the winner of units is randomized.



---



## 🏰 KotH (King of the Hill)



Players must control and defend the central zone to win the game.



Inspired by the original KotH arcade map by KingCobra.



---



## 🤝 Coalitions



When the KotH timer is close to ending, all remaining players unite against the leading player.



---



## 🌍 Decreasing Map



The playable area gradually decreases over time.



---



## 🧱 Creates Supplies



The KotH owner receives defensive wall structures around the central point.



---



## 📍 Moving Center



The KotH control point periodically changes position around the map.



---



## 💎 Minerals in the Center



Minerals periodically appear in the central area.



---



## 🎯 Rivals



Each player receives a rival. Destroying rival units grants reinforcement rewards.



---



## 🎭 Name Anonimity



Player colors are randomized and nicknames are hidden.



---



## 📋 Objective



Players receive dynamic in-game tasks similar to campaign objectives.



---



## 🐾 YoungYakov



Neutral units appear across the map and can be captured.



---



## 🏢 Neutral Buildings



Neutral structures spawn across the map and can be used by any player, inspired by Warcraft III mechanics.



---



## ⚖️ Random Balance



Unit attributes are randomly modified during gameplay.



---



## 🌫 Fog



Periodic fog events reduce player vision.



---



## 🌙 Day\_Time



Dynamic day and night cycle system.



---



## 🔄 Unit Adaptation



Unit attributes evolve depending on their battlefield efficiency.



---



## 🛠 Custom Units



The project includes a large amount of custom-designed units.



---



# 🚧 Disabled / Experimental Modes



## 🏕 Nomad (currently disabled)



Random unit spawning across the map inspired by Age of Empires II Nomad mode.



# 📦 Project Structure



## IncludesModder.SC2Mod



Contains the main gameplay logic of the project, including game modes, triggers, systems, and core mechanics.



---



## IncludesMap.SC2Mod



Contains the playable map:



```text

Honorgrounds LE

```



Configured for 4 players.



---



## DATAModder.SC2Mod



Contains additional external resources, assets, and supporting content used by the project.



---



## additionalDataMod.SC2Mod



Contains unit data configuration and gameplay attributes for units, including custom balance and modifications.



---



# 📚 External Assets \& Resources



This project integrates third-party models, textures, and assets from the StarCraft II modding community (e.g. CurseForge contributors).



All external content is used under its original licensing terms and remains the property of its respective authors.



The original gameplay logic, systems, and custom code created for this project are licensed under Creative Commons Attribution 4.0 International (CC BY 4.0).



Used community assets:



* HammerTheTank107

&#x20; https://www.curseforge.com/sc2/assets/hammers-assets



* _ForgeUser6335207

&#x20; https://www.curseforge.com/sc2/assets/infested-zealot



* DaveTheSpectre

&#x20; https://www.curseforge.com/sc2/assets/davespectres-assets



* ghostnova91

&#x20; https://www.curseforge.com/sc2/assets/ghostnovas-mods



* thrikodias

&#x20; https://www.curseforge.com/sc2/assets/thrikodias-assets



* AlleyVsc

&#x20; https://www.curseforge.com/sc2/assets/starcraft-kitbash-universe



---



# 🛠 Future Plans



Planned improvements include:



* Optimization

* Refactoring

* Improved UI/UX

* Better gameplay balancing

* Re-adding mode enable/disable systems

* Additional custom mechanics

* Multiplayer stability improvements

* Developing a Twitch chatbot that interacts with the game via chat commands


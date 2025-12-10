
🧙‍♂️ Potions of Lumos

A magical first-person puzzle adventure built in Unreal Engine 4.27.

<br>


✨ Overview

Potions of Lumos is a 3-zone, puzzle-driven wizard trial designed for the SE3091 Games Technology module.
The player must explore a mystical academy, learn mechanics, unlock the ancient Lumos spell, and complete the final altar ritual to prove mastery.

This project demonstrates gameplay systems, interactivity, blueprints, VFX integration, widgets, and multi-zone level design.

<br>



⸻

🧩 Gameplay Summary

Zone 1 — The Courtyard (Tutorial Zone)

Learn the basics:
	•	Move with WASD
	•	Jump with Space
	•	Interact with objects using E
	•	Light ritual braziers using magical scrolls
Completing the four braziers unlocks the gate to Zone 2.

⸻

Zone 2 — The Potion Chamber

A brewing puzzle zone featuring:
	•	Ingredient pickup & placement
	•	Cauldron detection
	•	Correct vs incorrect potion order
	•	Wrong mix feedback widget
	•	Correct mix unlocks the Lumos spell

The Lumos bottle appears with reveal VFX, and the player gains the spell.

⸻

Zone 3 — The Altar Room

The final challenge:
	•	Pickup artifacts using R
	•	Place them onto pedestals (1 per pedestal)
	•	Use Lumos light to locate hidden magical relics
	•	Proximity VFX reacts to Lumos being active
	•	Once all artifacts are placed AND Lumos is cast, the altar completes the ritual
	•	The game fades to white and displays Game Completed

<br>



⸻

🎮 Controls

Action	Key
Move	W A S D
Jump	Space
Interact	E
Pickup Artifact	R
Toggle Lumos	F
Pause Menu	Esc

<br>



⸻

🛠️ Technical Features

Blueprint Systems
	•	Object pickup & attachment
	•	Cauldron ingredient logic + order validation
	•	Lumos spell toggle (light + SFX)
	•	Sphere overlap systems
	•	Altar activation + ritual completion
	•	Zone transitions through level streaming
	•	Pedestal & artifact placement
	•	HUD and widget-based hint systems
	•	Main Menu and Pause Menu
	•	VFX-driven interactions (Niagara)

Visual Effects

Integrated Niagara systems:
	•	Gate Glow
	•	Potion Fog
	•	Lumos Burst
	•	Reveal Spell
	•	Altar Activation
	•	Wand Glow (distance based)

UI / UX
	•	Zone tutorial widgets
	•	Wrong mix warnings
	•	Lumos unlocked notification
	•	Pause menu
	•	Main menu with cursor support

<br>

⸻

🔨 Building / Packaging

macOS Build

File → Package Project → Mac

Windows Build

Not available on macOS.
To package Windows, open the project on a Windows PC with Visual Studio + Windows SDK installed.

⸻

▶️ How to Play
	1.	Launch the packaged build (PotionsOfLumos.app or .exe)
	2.	Start from the Main Menu
	3.	Follow tutorial prompts in Zone 1
	4.	Solve each zone’s puzzle
	5.	Unlock Lumos and complete the final altar ritual
	6.	Reach the Game Completed screen

<br>



⸻

👥 Team

Project Name: Potions of Lumos
Role Distribution:
	•	Logic & Blueprints
	•	3D Assets / VFX / UI
	•	Level Design 

<br>



⸻

🧾 License

This project was developed for academic purposes.
You may view or clone the project, but redistribution or commercial use is not permitted.

⸻

# A Lizard's Tale (2019)
1st-year student group project simulating game pre-production and development.

This is my 1st-year major group project where multiple disciplines come together over 10 weeks to plan and develop a prototype that meets a client's brief. It was developed in **C#** in **Unity**. Our team consisted of three designers, four artists, and myself as the programmer.
I am very proud of what we were able to achieve in the short time we had to create the game.

The game is a 2D puzzle platformer that involves controlling a lizard wizard through a level
using various movement mechanics and magical spells. The player can move, jump, crawl
and climb up walls. They are also able to cast spells to clear paths, defeat enemy slimes, or
for use in puzzle solving.

All technical details and design choices are outlined in the **Technical Design Document**.

**Download the game on its Itch page: https://alizardstale.itch.io**

**A Lizard's Tale Trailer - [LINK](https://youtu.be/rnmI0GfieSc)**<br>
[![Alt text](https://img.youtube.com/vi/rnmI0GfieSc/0.jpg)](https://www.youtube.com/watch?v=rnmI0GfieSc)

**A Lizard's Tale Dev-Talk - [LINK](https://youtu.be/gu_07QpIxq4)**<br>
[![Alt text](https://img.youtube.com/vi/gu_07QpIxq4/0.jpg)](https://www.youtube.com/watch?v=gu_07QpIxq4)

## Project Brief
### Overview
- Create a single player side scroller platform prototype.
- The finished game must be an executable build and must meet the criteria/features below.
- It is up to the team to decide how they meet the criteria, as well as world/setting/narrative premise to the game, including suitable art style.
### Required Features
- 1x enemy with at least 3 observable A.I. behaviours
- Clear end goal/exit
- 1x power up
- Health mechanic
- Death/respawn system
- 1x weapon/tool
- Sound
### Required Level Details
- 1x level with a clear artistically cohesive biome
- Distinct foreground, midground and background layers
- Clearly defined playable and non-playable areas
- Use verticality/multi-levels
- Meaningful back-traversal

## Self-Reflection
I was the sole programmer in the group so I contributed all of the functionality for the game. I
wasn’t sure initially if I would be able to meet all the tasks that were expected of me. This
was emphasised by a severe over-scoping near the start of pre-production. I felt very
overwhelmed and under-prepared to implement all the features. Luckily we drastically
reduced our scope and removed many unnecessary mechanics.<br>
During development, I spent a lot of time designing systems that would make adding
features easier for me and also easier for designers to implement. For example, all sound
effects can be played through the GameController singleton, and can even be played without
an AudioSource reference. This makes it significantly easier for me to play sound effects
from anywhere in the code without needing AudioClip references. Furthermore, the designers
were able to add sound effects through the Inspector, without needing to touch the code.<br>
I made sure to expose appropriate variables in the Inspector to allow designers to tweak with
values. I organised groups of variables under headings to reduce clutter in the Inspector.
I am proud of the systems I programmed, especially the cutscene system - because they are
reusable and user-friendly. Although, I know it can be improved upon in future projects.
Some of the code is messy and hacked together. There are public member variables in
some classes that should be more hidden in a future implementation.<br>
I also made sure to communicate with each team member during development to make
transitioning assets into the project as smooth as possible. For example, understanding how
certain objects are being animated so I can run the appropriate animations through code.
Now that the project is over, I feel much more confident in my individual abilities. I now know
that I can meet the technical needs of building an entire game in a proper group project. I
credit this achievement to participating in game jams throughout the year which improved my
abilities and team skills and the documentations I completed in previous assessments.<br>
I have learned a lot programming-wise from this project that I can apply to my future
individual or group projects. 

## Credits & Acknowledgements
### Design
- Brendan Blue: Lead narrative design
- Idris Hunt: Lead systems design
- Christopher Selleck: Lead level design
### Art
- Martin Widdowson: Generalist
- Breanna Fox: Lead environment artist
- Charles Spall: Lead effects artist
- Elise Allan: Lead character artist
### Programming
- David Flintoft: Lead programmer
### Music
Soundtrack provided under Creative Commons.
- Song title: Loyalty.
- Artist: King Gizzard and the Lizard Wizard.

<br><br><br><br>
<img src="aie_logo_clr.jpg" alt="Academy of Interactive Entertainment" width=250px height=250px/><br>
Academy of Interactive Entertainment Canberra<br>
Bachelor of Games and Virtual Worlds

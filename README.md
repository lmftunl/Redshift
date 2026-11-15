ABOUT THE GAME

Junior Astronaut Mission Trainer is an offline browser game for ages 7–12. You manage a two-person outpost at Noctis Landing on Mars. Rotate modules to line up their docking ports, keep the crew supplied with power and breathable air, and plan Earth shipments before food and water run low.

The game teaches how engineering decisions affect one another. A dust storm can cut solar power and leave panels that the crew must clean. A greenhouse can supplement shipped food, but it needs water, electricity, and crew time. Players can replay the same mission to see how different choices change the outcome.

HOW TO PLAY

Download or clone this repository, then open index.html in a modern browser. The game runs offline and requires no installation.

Start by docking the Central Module, Habitation Module, and two Solar Tiles. Select a kit and press Q to rotate left or E to rotate right. Use the arrow keys to move the placement preview and Enter to place it. Mouse and touch players can use the on-screen rotation buttons.

Order a module before the first launch window on Sols 8–12. If you miss it, a backup window opens on Sols 22–26. Open Supply outlook from the Cargo panel to estimate how much food and water will last until the next delivery. Press Esc or select Menu to pause, change settings, or restart.

BUILT WITH

We designed the interface in Figma and built the game with HTML, CSS, and vanilla JavaScript. Node.js bundles the game into a single HTML file and runs the simulation tests. We verified offline play, responsive layouts, and mouse, keyboard, and touch input in Microsoft Edge.

Run these commands from the repository folder to rebuild and test:

node build.mjs
node --test tests/engine.test.mjs

SCIENCE AND PROJECT DOCUMENTATION

The terrain comes from NASA’s Mars Orbiter Laser Altimeter data. The mechanics draw on Opportunity dust storm observations, Curiosity radiation measurements, and ISS life-support and plant-growth research. In-game science notes distinguish the underlying research from gameplay assumptions such as the 70-sol cargo transit.

# 2D Tanks Game (C, GLFW/OpenGL)

A 2D tank game written in C using GLFW/OpenGL.

## Features
- Real-time game loop
- Tank movement and shooting
- Enemy AI with patrol routes
- Multiple maps loaded from text files
- Power-ups and particle effects
- Modular project structure: input, rendering, game logic, maps, tanks

## Tech stack
- C
- GLFW
- OpenGL

## Project structure
- `main.c` — application entry point
- `game.c` — core game logic
- `render.c` — rendering
- `input.c` — input handling
- `tank.c` — tank behavior
- `map.c` — map loading and processing
- `powerup.c` — bonuses
- `particles.c` — particle effects
- `lighting.c` — lighting-related logic

## Assets
Maps and patrol routes are stored in `.txt` files:
- `map_*.txt`
- `patrol_*.txt`

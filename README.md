# FunSniper

A lightweight first-person browser sniper mini-game prototype for **Jobmania-style Slime targets**.

## Prototype features

- First-person stationary shooting range
- Normal view + circular sniper scope
- Mouse and touch aiming
- Wind that changes by wave
- Bullet travel time
- Gravity / bullet drop
- Moving Slime targets
- Increasing target count, distance, and speed
- Score and hit counter
- Desktop + mobile controls
- No build step and no dependencies

## Controls

- **Mouse / touch:** aim
- **Left click / FIRE:** shoot
- **Right click / S / Space:** scope
- **R:** restart

## Ballistics

The prototype deliberately uses simplified game physics:

- bullet flight time = distance / bullet speed
- horizontal drift is based on wind × flight time
- vertical drop is based on ½ × gravity × flight time²

The values are scaled for gameplay so wind and drop are visible without turning the game into a simulation.

## Jobmania assets

The current Slimes are canvas-drawn placeholders so the game works immediately. Replace them with the approved Jobmania Slime series artwork when the source asset paths are available.

## Run

Open `index.html` directly, or enable GitHub Pages for the repository.

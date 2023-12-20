## Overview
Handles the core mechanics of Cannonfire, like firing projectiles, controlling velocity, and scoring based on impacts.

## Key Functions
- `fireProjectile(Velocity)`: Fires a projectile with specified velocity.
- `calculateScore(Impact)`: Calculates the score based on the impact of projectiles on targets.

## Game Mechanics
Detailed game mechanics are outlined in `gameMechanics.md`.

### Requirements and Expectations
- Develop a user-friendly mechanism for controlling projectile velocity.
- Implement a scoring system that rewards accuracy and impact force.
- Ensure game mechanics are intuitive and provide a challenging yet enjoyable experience.

## Example Usage
```cpp
Projectile projectile;
fireProjectile(projectile, 50); // Fires projectile with velocity 50


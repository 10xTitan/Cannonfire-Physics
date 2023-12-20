# Physics Module

## Overview
The Physics module in Cannonfire is responsible for handling all the physical interactions. This includes collision detection, gravity, and the physics of projectiles and targets.

## Key Functions
- `calculateCollision(Projectile, Target)`: Determines collision events between projectiles and targets.
- `applyGravity(Projectile)`: Applies gravity to projectiles in motion.
- `computeImpact(Projectile, Target)`: Calculates the impact of projectiles on targets, considering their mass and velocity.

## Physics Engine
We use NVIDIA PhysX for realistic physics simulation. It provides advanced features like rigid body dynamics, collision detection, and realistic environmental interaction.

### Requirements and Expectations
- Implement PhysX to simulate realistic projectile motion and target impact.
- Ensure that the physics simulation is optimized for performance to handle real-time interactions.
- Physics calculations should account for varying masses of targets and different velocities of projectiles.

## Example Usage
```cpp
Projectile projectile;
Target target;
if (calculateCollision(projectile, target)) {
    computeImpact(projectile, target);
}


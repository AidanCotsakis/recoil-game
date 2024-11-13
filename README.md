# Recoil - A Pygame Shooter

Recoil is a 2D shooter game built with Pygame, where players navigate an arena, battling endless waves of enemies. The game features fluid controls, adaptive difficulty, interactive menus, and background music, delivering an engaging and dynamic experience.

## **Features**

- **Intuitive Player Controls**: Real-time aiming and movement based on mouse input, with velocity and friction mechanics.
- **Procedural Enemy Waves**: Endless waves of enemies with scaling difficulty, spawned at randomized locations.
- **Dynamic Projectiles and Collisions**: Projectiles respond to player direction and speed, with accurate collision detection.
- **Interactive Menu and HUD**: Main menu options, in-game kill counter, and life tracking for continuous gameplay immersion.
- **Background Music**: Customizable playlist of songs that automatically loops during gameplay.

## **Setup**

1. Ensure **Python 3.x** is installed.
2. Install required packages using:
   ```bash
   pip install pygame numpy
   ```

3. Run the game with:
    ```bash
    python recoil.py
    ```

## **How to Play**
- Use the mouse to aim and click to shoot.
- Enemies spawn randomly and increase in speed based on player progress.
- Navigate to the main menu to control sound settings, play, or exit.
- Survive as long as possible while aiming for a high kill count!

## **Game Structure**
- **Player Class**: Manages player movement, rotation, firing delay, and shot mechanics.
- **Projectile Class**: Controls projectile movement and collision detection with enemies.
- **Enemy Class**: Handles enemy spawning, movement, and collision effects with both the player and projectiles.
- **Menu and Game Loops**: Separate loops manage game state transitions, ensuring smooth gameplay.

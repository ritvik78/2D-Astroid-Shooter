# 2D-Astroid-Shooter
A simple 2D Unity game to learn the basics of game development. Control a player spaceship, shoot enemies from all sides, and manage score/lives through UI. Includes scenes, prefabs, and scripts for spawning, game logic, and UI handling. Great for beginners.
Here’s an updated **short README** with **brief descriptions** added for clarity:

---

# 🚀 Space Shooter

A simple 2D Unity game created to understand the fundamentals of game development including object spawning, UI handling, and basic player-enemy interaction.

![preview](https://user-images.githubusercontent.com/73842931/212389368-593895fd-82d5-4206-8b61-08d5621c4993.gif)

---

## 🎮 Scenes

* **Main Menu** – Start screen with UI to begin the game.
* **Game Scene** – Core gameplay with player controls and enemy spawns.

---

## 🕹 Game Objects

* **Player** – The user-controlled spaceship that can shoot lasers.
* **SpawnManager** – Handles enemy spawning from four directions using containers.
* **GameManager** – Controls game flow (e.g., scene transitions, score logic).
* **Canvas** – Manages UI elements like score, lives, game over text, and menus.

---

## 📦 Prefabs

* **Enemies** – Enemy ships appearing from top, bottom, left, and right.
* **Laser** – Projectiles fired by the player to destroy enemies.

---

## 🧠 Scripts

* **Player.cs** – Controls movement, shooting, and collisions.
* **Enemy.cs** – Base enemy behavior (extended by directional enemies).
* **Top/Bottom/Left/RightEnemy.cs** – Define spawn direction logic.
* **Laser.cs** – Handles laser movement and collision.
* **SpawnManager.cs** – Spawns enemies at intervals from different sides.
* **UiManager.cs** – Updates UI text like score and game over.
* **GameManager.cs** – Loads scenes and holds game logic.

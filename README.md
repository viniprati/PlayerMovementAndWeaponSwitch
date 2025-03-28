---

# PlayerMovementAndWeaponSwitch - Unity Script

This script is responsible for controlling the player's movement and weapon switching in a Unity-based game. It provides basic movement features (walking, running, and dashing) as well as the ability to switch between weapons using the mouse scroll wheel.

## Features

- **Player Movement:**
  - Walk and run with adjustable speeds.
  - Accelerates movement when pressing the **Shift** key.
  
- **Dash (Quick Boost):**
  - Allows the player to perform a dash, providing fast movement for a short duration.
  - Dash has a cooldown to prevent excessive use.
  
- **Weapon Switching:**
  - Switch between available weapons using the mouse scroll wheel (up and down).

## How to Use

### 1. Setup

- Attach this script to a **GameObject** representing the player in your game (typically a GameObject with a Rigidbody).
- Ensure the GameObject has a **Rigidbody** component for physical movement.
- Drag and drop weapon prefabs into the `weapons` field in the Unity Inspector. These weapons will be activated/deactivated as the player switches between them.

### 2. Customization

- **Walk Speed** (`walkSpeed`): The speed of the player while walking.
- **Run Speed** (`runSpeed`): The speed of the player while running.
- **Dash Speed** (`dashSpeed`): The speed of the player during the dash.
- **Dash Duration** (`dashDuration`): The amount of time the dash lasts.
- **Dash Cooldown** (`dashCooldown`): The cooldown duration between two consecutive dashes.

### 3. How Weapon Switching Works

- Weapons can be toggled by using the mouse scroll wheel:
  - **Scroll Up**: Switch to the next weapon.
  - **Scroll Down**: Switch to the previous weapon.

## Requirements

- Unity 2020 or higher.
- A GameObject with a **Rigidbody** and **Collider** for movement and collisions.
- Weapon prefabs (GameObjects) for weapon switching.

## How to Use

1. Add this script to your player GameObject.
2. In the `weapons` field, add the weapon prefabs the player can use.
3. Run the game and use the following controls:

   - **W, A, S, D** or **Arrow Keys**: Move the player.
   - **Shift**: Run.
   - **Q**: Dash (available after cooldown).
   - **Mouse Scroll**: Switch between weapons.

## Contributing

If you wish to contribute to this project, feel free to open a **pull request** with improvements or bug fixes.

## Contact Information

- **Email:** [viniprati6503@gmail.com](mailto:viniprati6503@gmail.com)
- **Phone:** +55 27 99823-5428

---

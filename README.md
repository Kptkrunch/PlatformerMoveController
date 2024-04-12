# PlatformerMoveController
PlayerMoveController
This repository contains the script PlayerMoveController that is meant to provide a comprehensive solution for player movement in a Unity game project. This script uses the new Unity Input System for the players' controls and the Photon Unity Networking library for network callbacks.

# Game Object Requirements
This script should be attached to the player's GameObject. It assumes your GameObject has the following Components:

Rigidbody2D,
CapsuleCollider2D,
Animator,
BoxCollider2D,

It also requires objects for wall, ground and ledge check points.

# Controls
The current implemented controls include:
Basic movements: The player can move left and right with acceleration and deceleration for smoother controls.
Jump: The player can jump and the height can be controlled by how long the jump key is held.
Wall interaction: The player can slide down walls and do a wall jump. The player can also hang from ledges.
Crouch: The player can crouch which triggers an animation but does not alter movement for now.

# Customization
All relevant parameters, like movement speed, jumping force, slide speed, etc. are public and can be set from the Unity Editor. This provides high flexibility in terms of adjusting the player's controls to your specific needs.
Usage

This script is intended for 2D platformer games. It provides a good base for basic platformer controls and can be freely expanded to fit your needs. Import the script into your Unity project, create an instance of PlayerMoveController and attach it to your player character.

Feel free to utilize the script in any way that suits your project's needs.

Future Enhancements
This script is a basic framework and does not cover all possible situations a player character might encounter. Some possible enhancements could be ladder climbing, moving platforms interaction, etc.

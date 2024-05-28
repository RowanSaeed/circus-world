# Circus of Plates – Game

## Project Description
Circus of Plates is a single-player game where each clown carries two stacks of shapes, including plates and other dynamically loaded objects. Colored shapes fall, and the clown attempts to catch them. When the player collects three consecutive shapes of the same color, they vanish, and the player's score increases. The game ends based on certain rules defined during gameplay.

## Features
- **Dynamic Shape Loading**: Shapes are dynamically loaded from a specific folder before the game starts. The game supports at least two different shapes.
- **Variety of Falling Objects**: The game includes different kinds of falling objects, such as plates and bombs.
- **Scoring System**: Points are awarded when the player collects three consecutive shapes of the same color, even if the shapes are different.
- **Multiple Difficulty Levels**: The game supports at least three levels of difficulty, with variations such as different speeds, multiple clowns, more queues, and changing shape colors or sizes.
- **Game Engine Integration**: Utilizes a custom game engine with three types of objects: movable, constant, and user-controlled objects.
- **Design Patterns**: Implements at least five design patterns from a specified list.

## Design Patterns Used
1. **Singleton**: Ensures a single instance of key classes, such as the game controller or game engine.
2. **Factory**: Used for creating different types of shapes dynamically.
3. **Iterator**: Provides a way to iterate over collections of shapes and other game objects.
4. **Dynamic Linkage**: Dynamically loads shape classes from a specified directory.
5. **Observer**: Implements an event-driven mechanism to update the game state based on changes in the game objects.



 

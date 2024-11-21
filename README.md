# Magical_Arena_Game

# Magical Arena Project

# Overview
This Java project is a simple game simulation where two players engage in combat using dice rolls and mathematical calculations.
Every Player is defined by a “health” attribute, “strength” attribute and an “attack” attribute - all positive integers.
The player dies if his health attribute touches 0.

Any two player can fight a match in the arena. Players attack in turns. Attacking player rolls the attacking dice and the defending player rolls the defending dice.
The “attack”  value multiplied by the outcome of the  attacking dice roll is the damage created by the attacker.
The defender “strength” value, multiplied by the outcome of the defending dice is the damage defended by the defender.
Whatever damage created by attacker which is in excess of the damage defended by the defender will reduce the “health” of the defender.
Game ends when any players health reaches 0

Player with lower health attacks first at the start of a match.

Assume two players . Player A 50 health 5 strength 10 attack Player B 100 health 10 stregnth and 5 attack . Attacking die and Defending die are both 6 sided die with values ranging from 1- 6

Player A attacks and rolls die. Die roll : 5 . Player B defends and rolls die. Die roll 2

Attack damage is 5 * 10 = 50 ; Defending strength = 10 * 2 = 20 ; Player B health reduced by 30 to 70

Player B attacks and rolls die. Die roll : 4. Player A defends and rolls die. Die Roll 3

Attack damage is 4 * 5 = 20 ; Defending strength = 5 * 3 = 15 ; Player A health reduced by 5 to 45

And so on

## Project Structure

The project consists of the following classes:

- **Main.java:** This class contains the `main` method to execute the game.
- **GameModule.java:** This class contains the core logic of the game, including starting the game, simulating combat, and determining the winner.
- **Player.java:** This class represents a player in the game, with attributes such as name, health, strength, and attack points.
- **MathModule.java:** This class provides mathematical operations used in the game, such as rolling a dice.

## Usage

To run the game:

1. Open the folder into your local machine.
2. Open the project in your preferred Java IDE or text editor. Im my case I've used Intellij Idea.
3. Compile and run the `Main.java` file.

## Customization

- You can customize the attributes of the players (such as health, strength, and attack points) by modifying the constructor parameters when creating player objects in the `Main.java` file.

## Contributor

- Abhiram Valluri

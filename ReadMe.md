# Loopy Loop

## Description

This video game was created for our university assignment. It features an achievement system, a shop, an inventory, loot, a player HUD, scoring, map generation, and player progress tracking. The goal of the game is to connect all the pieces together to form a beautiful pattern. Each piece has coded exits with a value of one. The pieces, as well as the values, can be rotated by clicking the mouse. Once all exits are connected (with no disconnected values of one), the level is complete, and the beautiful pattern created by the player is showcased.

## Getting Started

To start playing the game, find the **LoopyLoop.exe** file in the **FinishedLoopyLoop** folder and double click it, no additional setup is required.

## Playability

There are two main ways to play LoopyLoop.

The first way is through **Classic Levels**. To play classic levels, simply press the **Play** button on the main menu screen, and you will be transferred to Level 1 of the game. You can progress through the classic levels endlessly.

The second way is through the **Time Trial** challenge. To play the time trial, simply press the **Time Trial** button on the main menu screen. This level is designed to test your speed. You need to complete a pre-made level as fast as possible and try to beat your own top score. 

## Game systems

#### Map Generation
After completing level 10 of the game, pre-made levels end, and computer-generated ones begin. These levels use a code that defines the width and length limitations of the level, specifies what pieces can be used, and is given a reference to the win condition code, so that it doesn't generate unwinnable levels. With this information, the code randomly places pieces in the specified length and width of the level and creates a new and never-before-seen level after you repeatedly complete it.

#### Shop, Inventory, and Loot
All of these systems are interlinked. These systems can be found under the **Skins** section of the main menu.

The loot in this game is the collection of skins that you can acquire for a certain price. You can get in-game currency by completing classic levels, which provide you with a random sum between 100 and 200 after each level completed.

The shop system lets you purchase these skins. The code for the shop reads the current money owned by the player from the PlayerHUD and sees if the skin can be purchased.

The inventory system is within the shop system. When you purchase a skin, a button for purchasing a skin will disappear, and a button for equipping it will immediately appear, letting you change between them whenever you want.

#### Scoring System
Your score is your personal best time for completing the **Time Trial** challenge. You can improve it by trying to beat your own time, thus improving your score.

#### PlayerHUD and Player Progress Tracking Systems
The player progress tracking system updates a text file filled with all the player statistics. The playerHUD system displays these statistics in the **Player Stats** tab in the main menu of the game. The playerHUD system scans the player statistics text file and displays the statistics that are being constantly updated by the tracking system.

#### Achievement System
This system tracks the milestones that the player has achieved while playing the game. When the achievement is completed, a notification will be seen briefly. The tracking system then updates the achievement list and player statistics file. The achievement list can be found in the **Achievements** tab in the main menu of the game.


## License

This project uses the **Unity Personal license**.

## Contact

If any questions arise, feel free to contact one of our team members:<br>


**Emails**: dovydas.jalianiauskas@viko.lt ; dainius.genzuras@viko.lt
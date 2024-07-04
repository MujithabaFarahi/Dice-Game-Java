# Dice Roller Game

#### Video Demo:  <https://youtu.be/PqJKnRhfo5k>

#### Description:

## Dice Roller Application Overview

The Dice Game Application is an engaging and strategic game developed for Android devices using Java in Android Studio. The game offers both single-player mode (human vs. computer) and multiplayer mode (human vs. human), where the objective is to reach a predefined target score before the opponent. The gameplay involves rolling five dice and making strategic decisions to maximize the score within three attempts per turn. Players can set a target score and choose the difficulty level when playing against the computer, ensuring a dynamic and challenging experience.

### Application Structure

The application is structured into four main activities, each serving a specific purpose in the game flow. This modular structure ensures a clear and intuitive user experience.

1. MainActivity (View Page)

   The `MainActivity` serves as the entry point of the application. It provides a simple interface with two buttons: "New Game" and "About".

   - New Game: This button leads to the `MainActivity2`, where players can configure the game settings.
   - About: This button displays information about the auther.

2. MainActivity2 (Game Settings)

   The `MainActivity2` allows players to set the parameters for the game before starting. The interface includes the following components:

   - Target Score: An input field for players to set the target score required to win the game. Deafault value is 101.
   - Difficulty Toggle: A toggle button to switch between easy and hard difficulty levels when playing against the computer.
   - Game Mode Selection: Two buttons to choose the game mode:
     - Vs Computer: Leads to the `MainActivity3`.
     - Multiplayer: Leads to the `MainActivity4`.

3. MainActivity3 (Single-Player Mode)

   The `MainActivity3` is where the single-player mode takes place. The interface is designed to display two sets of dice, one for the human player and one for the computer. It includes the following elements:

   - Dice Display: Two sets of five dice each, representing the current roll for both the human player and the computer.
   - Throw Button: Allows the player to roll the dice.
   - Score Button: Ends the player’s turn and updates the score based on the current dice values.

   In this activity, the computer player uses different strategies based on the selected difficulty level. In easy mode, the computer rolls all dice randomly, while in hard mode, it employs a strategy to maximize its score by selectively re-rolling dice with lower values.

4. MainActivity4 (Multiplayer Mode)

   The `MainActivity4` is similar in UI to the `MainActivity3`, designed for two human players. The interface includes:

   - Dice Display: Two sets of five dice each, representing the current roll for both players.
   - Throw Button: Allows the current player to roll the dice.
   - Score Button: Ends the current player’s turn and updates the score based on the current dice values.

   In multiplayer mode, both players can see each other's dice and make strategic decisions on which dice to re-roll. This ensures a fair and competitive gameplay experience.

### Design Choices

Several design choices were made to enhance the game’s playability and user experience:

#### User Interface

The user interface is designed to be simple and intuitive. Clear instructions and prompts guide players through the game setup and gameplay. The dice are displayed prominently, and the buttons for rolling and scoring are easily accessible.

#### Difficulty Settings

The inclusion of an adjustable difficulty setting for playing against the computer adds depth to the game. In easy mode, the computer rolls dice randomly, providing a less challenging experience. In hard mode, the computer employs a strategy to maximize its score, creating a more competitive environment.

#### Modular Structure

By dividing the game into distinct activities, the codebase remains organized and maintainable. Each activity is responsible for a specific part of the game, ensuring that the application is easy to navigate and extend.

### Conclusion

The Dice Game Application is a well-designed and engaging Android game that offers both single-player and multiplayer modes. The clear and intuitive interface, combined with strategic gameplay options, ensures an enjoyable experience for all players. By implementing a modular structure and thoughtful design choices, the application provides a dynamic and competitive gaming environment. The inclusion of difficulty settings for the computer player and the ability to set a target score before starting the game add to the replayability and depth of the game.

####   Project Title : Dice Roller
####   Name   : Mujithaba Farahi
####   Github : MujithabaFarahi
####   From   : Colombo, Sri Lanka
####   Date   : 04/07/2024"

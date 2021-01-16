# Monopoly-Command-Line-Game


# Project Structure

- Source code is stored in the /src/jwrc directory
- Test code is stored in the /src/test directory
- JavaDocs are stored in the /doc directory
- Diagrams are stored in the /diagrams directory
- A compiled jar file is stored in /monopoly_team9.jar

|── monopoly

    ├───diagrams
    ├───doc
    └───src
        ├───jwrc
        │   ├───board
        │   ├───game
        │   ├───main
        │   ├───menus
        │   └───player
        └───test

# Running the Application

No input parameters are required. However it is important to note the jar file was compiled using Java 1.8
instead of newer versions so as to support current typical JRE Version of 1.8.

To run the application:

- Download the jar file
- Set this download directory as the current working directory
- Run: java -jar monopoly.jar in cmd/terminal
- Follow the pre-game instructions to begin the game.

# General Instructions

The user prompts are fairly comprehensive and give a good guide as to what options you have at each stage. Should an invalid input be entered,
this will be warned.
The application is designed so that the user can take all actions relating to properties, jail etc at any point during
their turn, not just before the turn.

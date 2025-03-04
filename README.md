<h1>Number Guessing Game</h1>

<h3>Description</h3>

The Number Guessing Game 👽🛸 is an interactive game where the player tries to guess a randomly generated secret number. With each attempt, the game provides feedback indicating whether the guess is too high or too low until the player either guesses correctly or runs out of attempts.

<p align="center">
    <img src="https://github.com/luizcarmoo/numberGuessingGame/blob/master/Number_Guessing_Game.png?raw=true" align="center"  width="450">
</p>

**Features**

  Randomly generates a secret number within a defined range.<br>
  Interactive interface allowing the player to enter guesses.<br>
  Immediate feedback on whether the guessed number is too high or too low.<br>
  Keeps track of the number of attempts made and remaining.<br>

**Technologies Used**

  Java – Main programming language used to develop the game logic.<br>
  JavaFX 23.0.2 - Framework used to create the graphical user interface (GUI) of the game.<br>
  CSS – Used to style the game interface.<br>

**How to Play**

Clone this repository to your local environment:

    git clone https://github.com/luizcarmoo/numberGuessingGame.git

Navigate to the project directory that contains the jar file:

    cd numberGuessingGame/out/artifacts/Number_Guessing_Game_jar

With JavaFX configured in the environment variables, run the jar file:

    java --module-path "%JAVAFX_HOME%\lib" --add-modules javafx.controls,javafx.fxml -jar "Number Guessing Game.jar"

Follow the on-screen instructions to enter your guesses and try to guess the secret number 0 ~ 100.

Enjoy the game 😉

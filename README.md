# Hangman-Game-Using-Python
Hangman - A game to guess the words. </br>
Henceforth HANGMAN is a word guessing game where the player is to build the missing word by guessing one letter at a time.</br>
The word to guess is represented by a row of dashes.If the player guesses the letter the which is present in the word the letter will be placed in its right position.</br>
The player has 10 chances to guess the word.</br>
As soon as the player lost all their wrong guesses, they were hanged(not really, but on the desktop screen 😉 ) </br>

## Algorithm
1.develop the interface</br>
2.predefined list</br>
3.instructions and logic</br>
4.check the letters </br>
 * If right then enter in empty list</br>
 * Then draw figure</br>
 * reduce the turns</br>
 * generate the hangman figure.</br>
 
5.win or loss

## User interface
For the user interface we just need an input so that we can add the players name.</br>

### importing modules
import "random" module</br>
### define function
define the function say def hangman():

## Predefined list
Create a wordlist that will be used by the program to pick words randomly for the players to guess.</br>

## Instructions and logic
Give the valid letters , invalid letters , number of turns.</br>
Add the logic to allow the program to choose a random word from the wordlist</br>
Make use of while, if, else conditionals to choose the random word.

## check the letters
whenever the player enters a letter you need to checkin whether the letter is valid or not.</br>
If the letter exists then the letter is placed at its correct position else it will display invalid letter.</br>
modify the logic such that whenever the player enters a wrong letter the number of turns should be reduced.</br>

## Win or loss
If the player guesses all the letters of the random word correct in given number of turns then the player wins else dies(losses the game). 




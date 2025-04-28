# Word-Guesser
this is a hangman game using Python
First a corpus is taken and it is being tokenized and words are later being extracted. once the words are extracted in (1.3) I am taking a minimum of 5 frequencys between each word so they arent too difficult for the players.
secondly some tests are being done, such as if the user enters 2 letters at a time it will say this is not a single letter. Another test is done in (2.3) where if the letter is guessed in the word, that correct letter will replace an asterix. An example is 'u' in butter => *u****.
finaly in (2.5) all the code is combined and the guessing game has been made.
## Running the game
to run the game you will need:
1. jupiter notebook through anakonda, 2. the code of this game, 3. the link to the corpus (http://localhost:8888/files/anaconda3/assigment-programming%202024%20DEC/corpus.txt?_xsrf=2%7C07615c8c%7Cad92ec76c5498880d5322a3a2d092a03%7C1745855204)
once you have all three just run each piece of code in number 1 and the last chunk (2.5) which is the game.
## what I've learnt
i have learnt how to use the tokenized method on a corpus and how to use the guessing method, where if a letter is correct it puts it down and if its not it tells you "try again".
## future improvements
I would like to learn and add more code on how to not count the correct letters as wrong ones. (each time i guess a letter whether its right or wrong the failed guesses increase by 1.)

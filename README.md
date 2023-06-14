# test

Milestone 3

Created a class called Hangman(). Inside the class, an init method was created to initialise the attributes of the class to pass in word_list and num_lives as           parameters. num_lives defaults to 5.

attributes of the Hangman() class:

word: The word to be guessed, picked randomly from the word_list. Remember to import the random module into your script.

word_guessed: list - A list of the letters of the word, with for each letter not yet guessed. For example, if the word is 'apple', the word_guessed list would be ['', '', '', '', '']. If the player guesses 'a', the list would be ['a', '', '', '', ''].

num_letters: int - The number of UNIQUE letters in the word that have not been guessed yet.

num_lives: int - The number of lives the player has at the start of the game.

word_list: list - A list of words.

list_of_guesses: list - A list of the guesses that have already been tried. Set this to an empty list initially.

The hangman class has two functions

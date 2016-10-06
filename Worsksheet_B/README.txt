import random_word_library                                                              # maximum of 7 letters long in library

Game = False
number_of_guesses = 5
Answer = choose random from (random_word_libaray)
Word_Length = find length of string(Answer)

while Game = False and number_of_guesses < 6:
    print("Im thinking of a word with", Word_Length, "letters\, can you guess it?")
    print(" You have", number_of_guesses, "left.")
    number_of_guesses = number_of_guesses - 1
    Guess = input()
    correct_letters = likeness of Guess to Answer                                       #letters have to be in same position to be alike.
       if correct_letters = Word_Length:                                              
          print("Congrats, you did it in", number_of_guesses, "guesses!")
           Game = True
       
       elif:
           print("Your guess had", correct_letters, "in the right place")

print ("Game Over")
 
           
       
     

# HANGMAN
##a game of hang-man
 i choose the hangman game because it has a challenging logical problems to be solved.
the simple game of guessing words of places,people, things. if you fail with a limited number of lives your player on the screen is hanged.
 i was inpired by my love for football(soccer) and my appreciation of different cultures.
 ###issues
 i had a few issues with it from the start. my main issue was drawing the man on css and also how to end the program with lives intact. 

####here is the pseudocode
Start
 Prompt user to enter word and store it into a character array.
 Initiate another array of same length as word, but each character is an “_”.
 Prompt user to guess a letter a through z.
 For loop: number of iterations = length of word
 For each iteration, test whether the character entered by the player matches
 the letter of the number of the current iteration.
End the loop.
 If Condition 1: check whether any letters matched,
 Else if: If letters do match,
 replace the “_” with said letter.
 If condition 2: check whether new string is equal to original word
 If true, Print “CONGRATULATIONS YOU WIN!!” & end loop
 If condition 3: Check whether lives = 0
 If true, print “You lose” & end loop
 End while loop

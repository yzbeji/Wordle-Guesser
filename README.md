# Wordle Guesser Algorithm V2.0

<-- THERE WILL BE UPDATES -->
<--    NEW UPDATE (1)     --> 

Have you ever played Wordle? (NO!)

It is a game which gives you 5 chances to guess a random word from their list of words. Each time you enter a word, the game will tell you some useful information based on colors:

    1. If the letter is green, it means that you have got the position and letter correct
    2. If the letter is grey, it means that the letter does not exist in the correct word
    3. If the letter is yellow, it means that the letter is in the correct word, but the position is wrong

Let's name this algorithm as 'robot'. This robot will try its best to find the correct word in the 'best way' (best way = the number of guesses tries to be minimum) it can do. 

    Now, you are maybe asking: "How he does that?"

We all know that computers are fast, they can execute functions and resolve ecuations in a rapid way. You'll find also commentary in the code itself that explains what it is doing. I decided to use Python, because I wanted to improve myself at this programming language and I also consider that it is easy to use and understand. I also applied a very exciting theory learned at faculty, named 'Information Theory'. Based on this theory, everytime the robot tries a word, it, of course, obtains information that will lead him to the correct word sooner or later. Also, it calculates the score for every word and selects the one that suits the best. You'll find two algorithms: one that it generates a random word from the list and the other one which is for every possible word (you'll have available also the .txt file to see, so you don't have to run it). 

Approximately guesses: #6.511 (Total words: 14855)

UPDATES: 

(1) - Made the algorithm to get more information per word tried than last time, now the actual number is: #4.66
    - You can find it in the files with V2.0



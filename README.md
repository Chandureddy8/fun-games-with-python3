# fun-games-with-python3 

# Rock-Paper-Scissors Game Python Project👤🐱‍💻

![alt text](https://www.google.com/imgres?imgurl=https%3A%2F%2Fwww.resolve.edu.au%2Fsites%2Fdefault%2Ffiles%2FRock%2520Paper%2520Scissors.png&imgrefurl=https%3A%2F%2Fwww.resolve.edu.au%2Fclassroom-topics-focus-rock-paper-scissors&tbnid=eTb3AY2IfF5-4M&vet=12ahUKEwiOsbu2h77uAhWLgmMGHfeUCr8QMygDegUIARDdAQ..i&docid=meoEqpPLaYFmCM&w=769&h=556&q=rock%20paper%20scissors%20game&ved=2ahUKEwiOsbu2h77uAhWLgmMGHfeUCr8QMygDegUIARDdAQ)

Rock paper scissors game is also known as stone paper scissors. It is a hand game that is usually played between 2 people, each player can randomly form any one of three from their hand.

A player who chooses rock will win by another player who chooses scissors but loose by the player who chooses paper; a player with paper will loose by the player with the scissors.

If both players choose the same then the game is tied. Rock paper scissors game is mainly played among kids.

The object of the rock-paper-scissor python project is to build a game for a single player that plays with a computer, anywhere, and anytime. This project is base on the rules that:

rock blunts scissors so rock wins

scissors cut the paper so scissors win

paper cover rock so paper wins

This project is build using tkinter, random modules, and the basic concept of python.

In this python project, players have to choose any one from rock, paper, and scissors. Then click on the play button will show the result of the game.

**Project Prerequisites**

To implement this python rock paper scissors project we will use the basic concept of python with tkinter and random module.

Tkinter is a standard GUI library which is one of the easiest ways to build a GUI application.

random module use to generate random numbers

**Project File Structure and objects explanation used in project**

**Import required libraries**

**Initialize window**

Tk() use to initialized Tkinter to create window

geometry() sets the window width and height

resizable(0,0) by this command we can fix the size of the window

title() used to set the title of the window

bg = ‘’ use to set the color of the background

Label() widget used when we want to display text that users can’t modify.

root is the name of our window

text which displays on the label as the title of that label

font in which form the text is written

pack used to the organized widget in form of block

**Code for user choice**

user_take is a string type variable that stores the choice that the user enters.

Entry() widget used when we want to create an input text field

**Code for computer choice**

random.randint() function will randomly take any number from the given number.

Here we give the if-else() condition to play rock paper scissors

If the computer choose 1 then the rock will set to comp_pick variable

If the computer choose 2 then the paper will set to comp_pick variable

If the computer choose 3 then scissors will set to comp_pick variable


**Define functions**

user_take is a string type variable that stores the choice that the user enters.

We give if-else() condition to check who wins between user choice and computer choice.

In this rock paper scissors game,  a player who chooses rock will win by another player who chooses scissors but loose by the player who chooses paper; a player with paper will loose by the player with the scissors. If both choose the same then the game will tie.

root.destroy() will quit the rock paper scissors program by stopping the mainloop().


**Define buttons**

Button() widget used when we want to display a button.

command called the specific function when the button will be clicked.

root.mainloop() method executes when we run our program.

# cs1302-hw00 Implementing Tic-Tac-Toe

This class exercise is designed to review prerequisite material by having students implement
methods to complete a command-line Tic-Tac-Toe game given some of the code as a starting point.

## Prerequisite Knowledge

* An understanding of classes, objects, and 2-D arrays in the Java programming language.

## Exercise Steps

### Checkpoint 1 Steps - Implementing the Tic-Tac-Toe Methods

1. Read the following disclaimers:
      
   > In CSCI 1302, per the syllabus, all of your course-related programming will take place in a 
   > Unix-like environment on the department's Odin server. This includes editing source code
   > using a terminal-based text editor such as Emacs or Vi (i.e., no Eclipse, IntelliJ, BlueJ, etc.), 
   > compiling source code from the terminal, generating user-facing documentation, and 
   > even program execution.
      
   > **The only exception to the previous disclaimer is today's exercise!** You've already taken
   > at least one semester of programming, so use the tools you're currently familiar with to
   > complete this exercise.

1. Click the link for the [starter code](https://github.com/cs1302uga/cs1302-ce0.5/blob/main/src/TicTacToeGame.java)
1. Right-click on the button labeled "Raw" near the top of the page.
1. Select "Save Link as" or "Download Linked File As" and save the file somewhere on your local machine.
1. Create a new Java project within your favorite Java IDE (Eclipse, IntelliJ, etc.) and add `TicTacToeGame.java` to
   the project.
1. Read through the comments in the source code. As you are looking through the code, answer the following
   questions in your notes:
   * How many instance variables are found in the class? 
   * What are the names of each instance variable?
   * What do you think the purpose is of each instance variable?
   * How many methods are there in total?
   * How many methods still need to be implemented? What are the names of these methods?
1. Implement the `playMove` method. Things to consider as you work through it:
   * What do the comments tell us about how we might implement the method?
   * What are the inputs/outputs of the method?
   * What happens when the method receives input corresponding to an invalid move?
   * Are there any existing methods that we can use to help make the implementation easier?
1. Implement the `isFull` method. Things to consider as you work through it:
   * What does it mean for the board to be "full"?
   * How do we access the game board from within the method?
   * Should we use loop(s) in our implementation?
1. Implement the `isWinner` method. Things to consider as you work through it:
   * What does it mean for one player to win?
   * Should we use loop(s) in our implementation?
1. Implement the `isCat` method. Things to consider as you work through it:
   * What exactly does it mean for the game to be a tie? The more specific you are, the easier
     it will be to turn your idea into code.
   * What other methods can we call to simplify the implementation? 
   * Hint: you can implement this method in just one line of code!
<hr/>

![CP](https://img.shields.io/badge/Just%20Finished%20Checkpoint-1-success?style=for-the-badge)

<hr/>

### Checkpoint 2 Steps - Testing your Implementation

In software development, it is important to **thoroughly** test all of the methods you write by writing
test code to go along with the implementation. Luckily, a test program for our Tic-Tac-Toe implementation 
already exists. To test the code you wrote, download 
[`TicTacToeTester.java`](https://github.com/cs1302uga/cs1302-ce0.5/blob/main/src/TicTacToeTester.java) and
add it to your existing project. Then, run the code. If you encounter errors, work with your group to resolve
the issues in those methods.

Generally, when we test methods in a larger software system, we will test each method thoroughly as we write it.
As you can probably imagine, you don't want to write too much code before testing as bugs can be much harder
to find in large projects. We will discuss ways to effectively approach this later in the semester.

<hr/>

![CP](https://img.shields.io/badge/Just%20Finished%20Checkpoint-2-success?style=for-the-badge)

<hr/>

### Checkpoint 3 Steps - Play the Game!

Now that your code is implemented and tested, play the game against your neighbor! To do this, download
[`TicTacToeRunner.java`](https://github.com/cs1302uga/cs1302-ce0.5/blob/main/src/TicTacToeRunner.java) and add
it to your existing project. This class serves as a command-line interface for your game. Please note that other
interfaces (such as graphical user interfaces) would also work with your implementation!

<hr/>

![CP](https://img.shields.io/badge/Just%20Finished%20Checkpoint-3-success?style=for-the-badge)

<hr/>

### Submission Steps

You will not submit this assignment yet. Hang on to your code, you will need to use it soon.
Make sure you understand the concepts needed for this exercise as all of them will be necessary for the 
first project.

<hr/>

![CP](https://img.shields.io/badge/Just%20Finished-Submission-success?style=for-the-badge)

<hr/>

[![License: CC BY-NC-ND 4.0](https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey.svg)](http://creativecommons.org/licenses/by-nc-nd/4.0/)

<small>
Copyright &copy; Michael E. Cotterell, Brad Barnes, and the University of Georgia.
This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License</a> to students and the public.
The content and opinions expressed on this Web page do not necessarily reflect the views of nor are they endorsed by the University of Georgia or the University System of Georgia.
</small>

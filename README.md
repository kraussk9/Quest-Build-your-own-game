# Quest-Build-your-own-game
Week 1: Mini Project
# Quiz Game

My own text based terminal game using Python.

The objective is not only to create a working game, but also to demonstrate understanding of Python fundamentals, including:

Lists
Dictionaries
Functions
Flow Control
Loops
Modules
Error Handling
Documentation
The game should be playable directly from the terminal and provide a complete experience with a clear objective, a win condition, and a lose condition.

# Project Requirements
Your final project must include the following:

Data Structures
Use lists and dictionaries to represent game information.

Examples include:

Questions and answers
Cards and hands
Tournament rounds
Words and guesses
Scores and statistics
Game State
Store the game status in a dictionary that is updated throughout the game.

Example:

game_state = {
    "score": 0,
    "lives": 3,
    "game_over": False
}

Copy

Explain
Recommendation: Design Before Coding
Before you start writing code, spend some time planning your game.

Many programming problems become much easier when you first understand the logic and structure of the solution before jumping into implementation.

Create a simple design document, flow diagram, or pseudocode that answers the following questions:

What is the objective of the game?
What information needs to be stored?
What actions can the player perform?
What are the win and lose conditions?
What happens during a typical turn?
How does the game start?
How does the game end?
Try to describe the game flow step by step before writing code.

For example:

Start Game
↓
Initialize Game State
↓
Display Current Information
↓
Ask Player for Input
↓
Validate Input
↓
Update Game State
↓
Check Win Condition
↓
Check Lose Condition
↓
Continue or End Game

Copy

Explain
You do not need to create a complex diagram. A simple sketch, flowchart, or list of steps is enough.

A good plan will make the coding process much easier and help you break the project into smaller, more manageable tasks.

Functions
Break your code into reusable functions.

Examples:

start_game()
display_menu()
process_turn()
check_winner()

Copy

Explain
Flow Control
Use:

if
elif
else
while loops
for loops
to control the game logic.

Input Validation
Validate all user input.

Documentation
Use comments and docstrings to explain your code.

Win and Lose Conditions
The player must be able to either win or lose the game.

Final Deliverables
Submit:

main.ipynb
All supporting .py files (if needed)
GitHub repository containing the complete project
Your final game must be fully functional and playable from start to finish.

Presentation
On Friday, each student will present their project individually.

Maximum presentation time: 5 minutes

Recommended Structure
Slide 1: Introduction
Project title
Assigned game
Your name
Slide 2: Game Overview
What is the objective of the game?
What are the win and lose conditions?
Slide 3: Technical Design
Which data structures did you use?
How is the game state stored?
Which functions are most important?
Slide 4: Biggest Challenge
What was the most difficult part of the project?
How did you solve it?
Slide 5: Demo
Demonstrate your game running
Presentations should focus on explaining your code and demonstrating your understanding of the concepts covered during the week.

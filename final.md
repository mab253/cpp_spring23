# 💿 final project

For your final project in this class, you will code a C++ project from scratch (outside of zyBooks!). You have a few options for this assignment:

1. [🛡 Text-Based Adventure Game](#text-based-adventure-game)
2. [🧊 Spatial Data Analyzer](#spatial-data-analyzer)
3. [🎨 Your Own Design](#your-own-design)

There are specific requirements for each option, but all of your final projects will require:

- Work in pairs. Collaboration and [pair programming](https://www.newyorker.com/magazine/2018/12/10/the-friendship-that-made-google-huge) is an important skill to learn! Choose someone in your same Friday lab section (either CC1 or CC2) so that you can use that time and space to work together.

- Create code in the [Replit](https://replit.com/) environment, so that you can collaborate with your project partner and so that your code can be easily compiled and shared at the end of the semester.

- Each person will need to write a short (400 word) statement about the division of labor between you and your partner, and some brief reflections on how the project synthesizes what you have learned in this class.

- Your code will be evaluated on the specific requirements for each project, as well as _style_: is your code legible? Do you have some comments that help your fellow programmers understand your work? Do you use loops to avoid repetition, efficient `if/else` statements, vectors or linked lists when necessary, and multiple files when you are writing classes?

## Text-Based Adventure Game

Create a text-based game, in the style of [Colossal Cave Adventure](https://grack.com/demos/adventure/). You will need to create your own storyline, write text-based prompts for your user to navigate the game, and write an ending (or multiple endings) for your user's character.

This is a very open-ended project, but your code must include the following:
- at least 5 functions that you write, outside of `main`
- at least 1 class, and multiple instances of creating objects of that class
- at least 1 game-within-a-game, where your user must play a game or complete a task using `rand()`, the psuedo-random number generator
- at least 1 variable that changes with your user throughout the gameplay (for example: a score; an inventory of things they are holding; etc.)
- at least 1 instance of [ASCII art](https://www.asciiart.eu/)
- at least 10 "locations," or decision/branch points, for your users to navigate *

*The game does not have to be as long as Colossal Cave Adventure (there are 140 map "locations" in that game, when the user gets a chance to make a decision!), but this game should be an involved, significant experience to build and to play; it should take us more than 5 minutes to get through the action. Stretch yourself!

A few examples: your user is an astronaut exploring Mars, and she finds a locked safe in a crater and needs to crack the combination to open the safe as part of the mission; OR your user gets a new job counting rats in NYC subway tunnels, and needs to guess which train is coming first to avoid danger; OR your user is a student studying in the CCNY library, who finds a book with a note in it, which leads them to a party where they have to play [Blackjack](https://en.wikipedia.org/wiki/Blackjack), or at the door in order to get in; OR your user is starting a garden, and they have to respond to random acts of weather by choosing the right tools and actions; OR your user is shipwrecked and they have to find their way home, including picking up items on an island and guessing a password in order to stow away on a pirate ship; etc. etc ... this is a chance to be creative and explore a story that you enjoy.

## Spatial Data Analyzer

Create a program that analyzes spatial data. Being able to determine the frequency and distance between points has all kinds of applications, from computer graphics to machine learning. In this project, the spatial data will be given to you in the form of points, either 2D _(x, y)_ or 3D _(x, y, z)_ - and you will need to receive the data input by uploading a file.

You can download the file that you'll need to add to your program [here](https://cs103-proton.glitch.me/1m.txt).

How to do you begin and read this file in your project?
- Create your project on [Replit](https://replit.com/)
- Upload the .txt file to the file system (on the left) of your project
- You can look at zyBooks [Chapter 9.5](https://learn.zybooks.com/zybook/CUNYCSC10300BlountSpring2023/chapter/9/section/5) for further instructions on how to read data from an external txt file. Also, you can check out this example code: https://replit.com/@mab253/read-file-example#main.cpp

After the file upload, your program will need to analyze and output the following:

1. Count the number of 2D points in the uploaded file
2. Count the number of 3D points in the uploaded file
3. Count the frequency of 2D points - how  many points in the dataset have the same _(x, y)_?
4. Count the frequency of 3D points - how  many points in the dataset have the same _(x, y, z)_?
5. Calculate the farthest distance between two 2D points in the dataset
6. Calculate the farthest distance between two 3D points in the dataset
7. Write at least 6 functions outside of `main` to accomplish these tasks

## Your Own Design

Do you have a project idea that you and your partner really want to build? (Maybe something with [openFrameworks](https://openframeworks.cc/), maybe something with cryptography?) You can send me your idea via e-mail or Discord by **May 3rd,** and I will either approve it or suggest changes in scope/difficulty.

## Due Dates

1. First milestone: choose your project (1, 2, or your own idea) and your partner from your lab section **by May 5th.** You will need to fill out [this form](https://airtable.com/shraeiHt8vPUzNyQl) to share your project choice and your partner by 11:59pm on May 5th.

2. Final project delivery, including short reflection texts and code via the Replit platform, due **May 19th** @ 11:59pm.

## important notes

- **No late work accepted for final projects.** If you have an accomodation, you need to tell me this beforehand.
- [Academic honesty](https://github.com/mab253/cpp_spring23#academic-honesty-and-integrity), as always, applies to this assignment - even more so as this should represent your own work, as this is not a lab/practice problem. Violations of the academic honesty policy will have serious consequences, including but not limited to failing this course. Do not plagiarize writing or code!

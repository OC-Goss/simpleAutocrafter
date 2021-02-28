# simpleAutocrafter
A simple autocrafter program for OpenComputers

# Installation
Because it was intended for my personal use, i never added very user friendly interface and installation code, So to use the program in its current state:

1.Use wget to get the robotLibInstaller.lua to your OC Computer(it will install lib files to your "/usr/lib" directory)

2.Run that program, it will download all the required library from my repo and some excess files too :P(A dedicated library installer will be made later)

3.Use wget to download this program

# Resource Requirement/Setup

1. robot with crafting and inventory controller upgrade

2. a storage medium in front of the robot

3. robot need to face the ingredient chest

(Info available at the top of the code too :D)


# How to use
The program will show a ">" sign when it is ready for input

There are only 2 commands currently:

1.create --to add a recipe to the database(instructions on what to do next will be displayed)

2.craft --to craft an item stored in the database(instructions on what to do next will be displayed)

*Important:Recipe for intermediate products need to be present in the database(use create command)

*Note:If the program cannot search for the item from your query, try to make sure the first letter of the word is upper case(e.g. pickaxe -> Pickaxe)(planned to improve of course :P)

3.exit -- stop the program

No parameters needed, just directly type the word and press enter :D

# TODO/Bug

1.Missing "recipe created" prompt to show recipe successfully created

2.Program will crash if you attempt to craft an item without all its intermediate products's recipe present in the database
(e.g. No minecraft stick recipe while trying to craft a minecraft pickaxe when stick is not in the ingredient chest)

3.Database lookup with specified keyword from user in the crafting function cannot properly handle upper case or lower case difference

4.Precalculate the cost before actually crafting it?

5.Show total raw material cost of a recipe?

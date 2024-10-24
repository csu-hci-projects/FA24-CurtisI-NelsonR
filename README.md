# CS310H_HW1
Unreal Game Project

CS/IDEA 310H Homework Assignment 1 Handout. Spring 2024


For Homework Assignment 1, you will be creating an FPS game. This will build upon what we have covered in labs. You are welcome to refer to the textbook and lab content to create your game, however, some of the required features will necessitate that you go beyond what we have covered in class.


To receive full credit you must:


Create a new project (10 PTS)
Use the FPS template and load the starter assets.


## Create 3 unique levels
One level must be a “menu” scene with a start button that loads the first level and a quit button that exits the game. (10 PTS)


The level that is loaded from the menu must have hazards and targets (required functionality for these described below). Once all targets have been destroyed the third level must automatically load. (10 PTS)


The third (last) level must also have hazards and targets, but a different layout. Once all targets have been destroyed the menu scene must automatically load. (10 PTS)


Both of the non-menu levels must have static meshes with materials applied for the user to navigate. (10 PTS)

Each non-menu level must have at least 3 targets and at least 3 hazards.


Targets can be any mesh, but must have a “health” variable. Their starting health should be 100. (20 PTS)


The health variable is an integer that is reduced when shot (the exact amount of health lost is up to you). After a target’s health reaches 0 or less the target should be destroyed.
Once all targets in a level are destroyed the next level should automatically be loaded (see 2b and 2c for details).


Hazards need to damage the player. (20 PTS)

The player needs to have a health variable as well. The starting health should be 100.
When a player collides with a hazard (i.e. lava pit, spike trap, etc.) they will lose health (the exact amount they lose is up to you).
Once a player’s health reaches 0 or less the level should automatically restart (hint load the level currently being played!).

## Ammo
The player should have limited ammo. (10 PTS)


Whenever the player fires if they have ammo the ammo integer is reduced by 1.
If the player is currently at 0 or less ammo the gun does not fire.
The ammo count should be displayed at all times as: “AMMO: ##”


Pickups

Ammo pickups (10 PTS)
If the player runs over an ammo pickup their ammo count increases and the pickup is destroyed.
This pickup should have a unique mesh visual to identify the pickup.
Health pickups (10 PTS)
If the player runs over a health pickup their health increases. However, the player’s health cannot exceed 100. The pick up should then be destroyed.
This pickup should have a unique mesh visual to identify the pickup. (20 PTS) 


# To turn in:

Create a ReadMe file. This will be a text file. You will add there how your application works and anything needed to run it. On top, you will have the names of the members and what each member did or didn’t do. You will also have all the links required for this assignment at the top of the readme file.  You will also reference anything you may have used. 
Record a 5-10 minute video showcasing the features above. You must demonstrate how each feature works while running the game and show the event graph (blueprint “code”). This video needs to be uploaded to YouTube UNLISTED. That link must be turned in on the associated assignment Canvas page. It is your responsibility that it works. 
Record a longer video where you explain all your blueprints. This will also be YouTube unlisted. 
Please feel free to use LLMs (e.g., Chat GPT) to help or the web. Please write a document of what you used beyond the class. This part will not be graded but saved as you need it for your AI report. A PDF file of this will be required to be uploaded. 


After closing the submission, upload all files to your GITHUB repo provided to you by the TAs no later than 24 hours later. 


For advanced projects, you must provide a detailed report of your work and contributions to the project. It must be more advanced than a regular project. 


We reserve the right to request a one-on-one meeting to review code, implementation, and features for any reason.


10 pts. Meetings with your group (if a person of one, just write what you did). You will provide this at the bottom of your read-me file. The points include some class dates for meeting your group members in class (or at a different time for online students). 


# Riley
Second Level

Menu

Targets

Hazards

# Isaac
~~Create the Project~~

First Level

Menu

Ammo

Pickups

# Resources

Main Menu Creation: https://www.youtube.com/watch?v=zWI-36fIoDQ 
* helped us create the main menu in general however we will need another resource to keep it from going into first person when you click to the side of the buttons as that makes it less intuitive (gulf of execution?)
* soul cave asset pack from Epic Games
* Large File Storage for Git: https://medium.com/projectwt/setting-up-git-large-file-storage-for-unreal-engine-projects-1854d6337177
* collision event - https://www.youtube.com/watch?v=H2I7I8blgn8&ab_channel=GorkaGames

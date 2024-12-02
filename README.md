For Homework Assignment 2, you will be creating a VR game. This will build upon what we have covered in labs. You are welcome to refer to the textbook and lab content to create your game, however, some of the required features will necessitate that you go beyond what we have covered in class.

To receive full credit you must:

Create a new VR project. (20 PTS)
Use the VR Template and starter assets.
Configure and connect your assigned VR HMD.
Create a new level with static mesh objects to decorate your world. (10 PTS)
Configure this level to use the VR gamemode and use the VR player pawn.
Create a teleportation area (10 PTS)
Use a navigation volume and static mesh to enable teleportation in your VR level.
Add at least 3 unique VR grab interactables (you are welcome to add more and add multiple instances on a unique interactable). (10 PTS)
These should be static meshes with the grab component.
Ensure that “simulate physics” and “use gravity” are enabled.
Modify the Pistol Blueprint to keep track of ammo (10 PTS)
Add spatial UI to the pistol blueprint
Whenever the user shoots the ammo count should decrease
After shooting the UI should update to show the current ammo count
If the ammo count is 0 prevent the player from shooting
Add a delayed reload function (15 PTS)
Set up a button input as the reload button.
If the pistol is currently in the user’s hand and the button is pressed begin resetting the reload.
There must be a time delay before the ammo count is updated.
After the delay, update the spatial UI to display the new ammo count.
When reloaded play a notification sound to indicate that reloading has been completed.
Add at least 5 targets to the level (10 PTS)
These should keep track of how many times they’ve been hit by a projectile.
This should be an int variable that starts at 0.
After the first hit, change the color of the target material.
After the second hit, use an event to indicate that the target is being destroyed and then destroy it.
Modify the level blueprint to keep track of the number of targets destroyed. (10 PTS)
Add an event listener to the level blueprint that is connected to the target destroyed event delegate (see 5d).
Whenever a target is destroyed, increase an int variable that keeps track of the number of destroyed targets and print the number of destroyed targets to the screen.
Create an unlockable “no-teleport” area. (10 PTS)
Due to a technical issue this section has been updated 11/21/24. Once a single target has been destroyed unlock the "no-teleport" area.
After increasing the level blueprint variable to keep track of destroyed targets check to see if at least 3 have been destroyed.
If at least 3 have been destroyed, unlock the “no-teleport” area.
Add a “win” level (15 PTS)
Create a second level
Decorate this level with any static meshes, particle effects, etc. that you want.
Add in spatial text that reads “You Win!”
In your first level automatically load this second “win” level once all targets in the first level have been destroyed.
 

(20 PTS) 

To turn in:

Create a ReadMe file. This will be a text file. You will add there, how your application works and anything needed to run it. On top, you will have the names of the members and what each member did or didn’t do. You will also have all the links required for this assignment at the top of the readme file.  You will also reference anything you may have used. 
Record a 5-10 minute video showcasing the features above. You must demonstrate how each feature works while running the game and show the event graph (blueprint “code”). This video needs to be uploaded to YouTube UNLISTED. That link must be turned in on the associated assignment Canvas page. It is your responsibility that it works. 
Record a longer video where you explain all your blueprints. This will also be YouTube unlisted. 
Please feel free to use LLMs (e.g., Chat GPT) to help or the web. Please write a document of what you used beyond the class. This part will not be graded but saved as you need it for your AI report. A PDF file of this will be required to be uploaded. 
After closing the submission, upload all files to your GITHUB repo provided to you by the TAs no later than 24 hours later.
For the videos it is considered unprofessional to record your screen using a phone. We recommend using screen capture software such as OBS (https://obsproject.com/) to professionally capture demo videos of your work. Since this was not explicitly stated for HW1 there are no penalties for this assignment, however going forward it is expected that you use proper screen capture software for any other video recordings; otherwise there may be point reductions.

Challenges

If you are in a group of 4 you must complete at least two of the following. If you are in a group less than 4 (i.e. 1, 2, or 3) you can received extra credit for each of the following you complete:

Create a VR menu scene
This menu must have two buttons: “Play” and “Quit”
Players must be able to select the buttons using their motion controllers
When the “Play” button is clicked load the first level
When the “Quit” button is pressed quit the game
Modify targets to move
Targets must move back and forth between two points
Targets must have a “speed” variable that affects how fast a particular target moves between those two points
Add a “secret” room unlocked with a grab interactable
Create an inaccessible room (either using a no-teleport area or using static meshes that block teleportation)
Create a grabbable static mesh blueprint that acts as a “key”
Create a pedestal blueprint to act as the lock
When the “key” blueprint touches the pedestal remove the no-teleport or static meshes to allow access to the inaccessible room

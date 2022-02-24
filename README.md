# UnityGameScene
 Game scene

Background: Professor Price made you roll a character by hand, on paper. Then he made you do it as a scene in Unity. Now he wants you to create a menu system that will act as a scaffolding for the development of the rest of the semester. Show him that you can do this! Create a game with a menu system that includes your character generator UI that also satisfies the following requirements.

Requirements:

The assignment will be turned in on the class gitlab server at https://rijeka.sdsu.edu/ (Links to an external site.) . Your repo and unity project must be named F22_Proj_1B_Lastname_Firstname . Make sure to initialize your repository on Rijeka.sdsu.edu with a Readme. Create a Unity project with the exact same name as the Rijeka project. Then link the two projects together via git commands - use the git fetch command. This will result in a merge conflict. For maximum points, resolve the merge conflict.
You may copy the assets folder from your 1A project for this assignment.

Build a UI that should function as a ‘menu’ system to quit your game in editor mode and executable mode. You will need Five menu options (buttons): About, Settings, Roll Character, Play Game [2D and 3D], and Quit. Play Game button should be visible but not be available - until the player finishes Rolling a Character like Project 1A. When a user selects a menu option, your game will load a new unity scene using SceneManager.LoadScene.

The UI should implement a Game Controller that implements the Singleton software design pattern that is recommended for Unity games.
The Play Game menu item should load a scene with a back button that sends the player back to the Main menu screen. You do not need to implement a game for this project.
You must build and code this UI all by yourself. No additional assets (Free or paid for (Especially the Unity Tutorials)) may be used.

You may not use external APIs to generate your character.

Must be coded in C# using Unity3d 2020.3.# LTS or higher
Original art will score highest. Documented borrowed art will result in a higher score than unattributed works. In general you should include a list of attributions in the form of a bibliography.txt.

Push your code to your Rijeka repository. When you are ready for grading, push you code with a commit message of “Ready for Grading”

Requirements: please check the instructions   |   .doc file

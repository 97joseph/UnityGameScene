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

Background: Professor Price made you roll a character by hand, on paper. Show him that you can
do better by using Unity to make a character generator! Create a game with a user interface that
will be used to select a character for a player of your future games. Using Unity 2020.3.###LTS
and the Canvas system, make a game to satisfy the following requirements.

Requirements:
1. Use the Unity Canvas system to create a user interface.
a. The UI should be a scene named Scene_Roll_Character, When your game starts up this
scene will load.
b. The UI should implement a D&D 5th edition character generator which saves the
following game properties (in a data structure) to a JSON formatted string (must pass
validation) displayed in a selectable (input) text box. All the following elements should
be in the output (saved data structure):
i. Character Name - String
ii. Abilities - floats Ability_Strenght, Ability_Dexterity, Ability_Constitution,
Ability_Intelligence, Ability_Wisdon, Ability_Charisma
iii. Race - String See Below
iv. Class - String See Below
v. Alignment - String
vi. Experience Points ( Current and Max) - XP - Integer
vii. Hit Points ( Current and Max) - HP - Integer
viii. Armor Class - Integer
ix. Speeds ( Walking, Running, and Jump Height ) - Integer
x. Item List - List<String> (Leave list empty for this Assignment)
c. The Abilities portion of your UI should implement a dice simulator. Players must roll
3d8 and add the three highest rolls to compute each of the six Abilities (one at a time).
Note make all modifiers default to +2. See below for list of Abilities.
d. The Race and Class elements should be implemented as a Drop Down menu UI element.
e. The speeds should be implemented as a slider UI element.
f. The armor class element should only accept user input that is a positive integer between 1
and 100.
g. Once all abilities have been calculated, the json output shall be displayed in the output
section.
h. The project should implement an Exit Button that will exit the game in both Editor Mode
and Run Mode.
 
2. You must build and code this UI all by yourself. No additional assets (Free or paid for (Especially
the Unity Tutorials)) may be used.
 
3. You may not use external APIs to generate your character.
 
4. Must be coded in C# using Unity3d 2020.4.# (LTS)
 
5. Documented original art will result in a higher score than downloaded or unattributed works. In
general all your projects should include a list of attributions in the form of a bibliography.txt.
 


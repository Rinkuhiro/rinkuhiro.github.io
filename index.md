---
layout: default
---

Welcome to our blog showing the progression of our project in the class "HCI For Mixed Reality" of Telecom Paris.

# Step 0 : Installation

To begin everything, we installed unity, the software that we're going to use for the development of the project.

We opened Unity Hub, and went to Installs, then Install Editor, then download archive.

![Installation_0](images/Installation_0.jpg)

![Installation_1](images/Installation_1.jpg)

![Installation_2](images/Installation_2.jpg)

We chose to use the 6000.2.12f1 version, as one of us already had this version installed and it was compatible with the most recent tools for VR development.

![Installation_3](images/Installation_3.jpg)

We made sure to include Android Build support, to be able to run the project on most VR headsets.

![Installation_4](images/Installation_4.jpg)

![Installation_5](images/Installation_5.jpg)

![Installation_6](images/Installation_6.jpg)

And now the Unity Editor is installed ! 

# Step 1.0 : Creation of the Roll-a-Ball Project

Now we can create our project using the Universal 3d Render Pipeline.

![Create_Project_0](images/Roll_A_Ball_Tutorial/Create_Project_0.jpg)
![Create_Project_1](images/Roll_A_Ball_Tutorial/Create_Project_1.jpg)
![Create_Project_2](images/Roll_A_Ball_Tutorial/Create_Project_2.jpg)

# Step 1.1 : Creating a basic scene

Once our project was created, we created a basic scene.

![Create_Scene_0](images/Roll_A_Ball_Tutorial/Create_Scene_0.jpg)
*Creating the Ground*
![Create_Scene_1](images/Roll_A_Ball_Tutorial/Create_Scene_1.jpg)
*Creating the Player object*
![Create_Scene_2](images/Roll_A_Ball_Tutorial/Create_Scene_2.jpg)
*Modifying the Directional Light object*
![Create_Wall_0](images/Roll_A_Ball_Tutorial/Create_Walls.jpg)
*Adding some walls*


# Step 1.2 : Player Controller

Now that our Player object is created, we can give the player a way to control it.

![Create_PlayerController_0](images/Roll_A_Ball_Tutorial/Create_PlayerController_0.jpg)
*Creating the PlayerController script component*
![Create_PlayerController_1](images/Roll_A_Ball_Tutorial/Create_PlayerController_1.jpg)
*Writing the PlayerController script*
![Create_PlayerController_2](images/Roll_A_Ball_Tutorial/Create_PlayerController_2.jpg)
*Linking Unity's input manager with our script*

# Step 1.3 : Camera Controller

Now that our player can move, we have to make the camera follow the player.
![Create_CameraController_0](images/Roll_A_Ball_Tutorial/Create_CameraController_0.jpg)
*Writing the CameraController script*
![Create_CameraController_1](images/Roll_A_Ball_Tutorial/Create_CameraController_1.jpg)
*Attaching the script to the camera object*

# Step 1.4 : Gameplay

We can now add some gameplay to our project. Let's start with an item to pick up.

![Create_PickUp_0](images/Roll_A_Ball_Tutorial/Create_PickUp_0.jpg)
*Creating a Pick Up object*
![Create_PickUp_1](images/Roll_A_Ball_Tutorial/Create_PickUp_1.jpg)
*Writing the Pick Up script*
![Create_PickUp_2](images/Roll_A_Ball_Tutorial/Create_PickUp_2.jpg)
*Attaching the script to the object*
![Create_PickUp_3](images/Roll_A_Ball_Tutorial/Create_PickUp_3.jpg)
*Placing some Pick Up object in our scene*
![Create_PickUp_4](images/Roll_A_Ball_Tutorial/Create_PickUp_4.jpg)
*Adding a tag to the objects for the collision detection*
![Create_PickUp_5](images/Roll_A_Ball_Tutorial/Create_PickUp_5.jpg)
*Making the Player object detect the collision with Pick Up objects*
![Create_PickUp_6](images/Roll_A_Ball_Tutorial/Create_PickUp_6.jpg)
*Disabling the physical response of the Player - Pick Up collision*
![Create_PickUp_7](images/Roll_A_Ball_Tutorial/Create_PickUp_7.jpg)
*Counting the number of picked up object*

We add a HUD to display informations to the player.

![Create_HUD_0](images/Roll_A_Ball_Tutorial/Create_HUD_0.jpg)
*Adding a Canvas item and some text*
![Create_HUD_1](images/Roll_A_Ball_Tutorial/Create_HUD_1.jpg)
*Setting up the Canva*
![Create_HUD_2](images/Roll_A_Ball_Tutorial/Create_HUD_2.jpg)
*Adding a counter*
![Create_HUD_3](images/Roll_A_Ball_Tutorial/Create_HUD_3.jpg)
*Changing the counter from the Player script*

We add an Enemy.
![Create_Enemy_0](images/Roll_A_Ball_Tutorial/Create_Enemy_0.jpg)
*Creating the enemy body*
![Create_Enemy_1](images/Roll_A_Ball_Tutorial/Create_Enemy_1.jpg)
![Create_Enemy_2](images/Roll_A_Ball_Tutorial/Create_Enemy_2.jpg)
![Create_Enemy_3](images/Roll_A_Ball_Tutorial/Create_Enemy_3.jpg)
![Create_Enemy_4](images/Roll_A_Ball_Tutorial/Create_Enemy_4.jpg)
*Setting up the enemy's pathfinding*

We add some obstacles.
![Create_Obstacle_0](images/Roll_A_Ball_Tutorial/Create_Obstacle_0.jpg)
*Adding the objects*
![Create_Obstacle_1](images/Roll_A_Ball_Tutorial/Create_Obstacle_1.jpg)
![Create_Obstacle_2](images/Roll_A_Ball_Tutorial/Create_Obstacle_2.jpg)
*Updating the enemy's pathfinding*
![Create_Obstacle_3](images/Roll_A_Ball_Tutorial/Create_Obstacle_3.jpg)
![Create_Obstacle_4](images/Roll_A_Ball_Tutorial/Create_Obstacle_4.jpg)
*Adding some dynamic obstacles*

Let's add the win conditions.
![Create_Win_Lose_Conditions_0](images/Roll_A_Ball_Tutorial/Create_Win_Lose_Conditions_0.jpg)
![Create_Win_Lose_Conditions_1](images/Roll_A_Ball_Tutorial/Create_Win_Lose_Conditions_1.jpg)
![Create_Win_Lose_Conditions_2](images/Roll_A_Ball_Tutorial/Create_Win_Lose_Conditions_2.jpg)
*You lose !*
![Create_Win_Lose_Conditions_3](images/Roll_A_Ball_Tutorial/Create_Win_Lose_Conditions_3.jpg)
*You win !*

Finally let's build our game.
![Create_Build_0](images/Roll_A_Ball_Tutorial/Create_Build_0.jpg)
![Create_Build_1](images/Roll_A_Ball_Tutorial/Create_Build_1.jpg)
![Create_Build_2](images/Roll_A_Ball_Tutorial/Create_Build_2.jpg)


# Presentation - Locomotion Ideas
![LocomotionIdea0](images/LocomotionIdeas/LocomotionIdeas-0.jpg)
![LocomotionIdea1](images/LocomotionIdeas/LocomotionIdeas-1.jpg)
![LocomotionIdea2](images/LocomotionIdeas/LocomotionIdeas-2.jpg)
![LocomotionIdea3](images/LocomotionIdeas/LocomotionIdeas-3.jpg)
![LocomotionIdea4](images/LocomotionIdeas/LocomotionIdeas-4.jpg)
![LocomotionIdea5](images/LocomotionIdeas/LocomotionIdeas-5.jpg)
![LocomotionIdea6](images/LocomotionIdeas/LocomotionIdeas-6.jpg)

# Presentation - Project Locomotion Pitch
![LocomotionPitch0](images/LocomotionPitch/LocomotionPitch-0.jpg)
![LocomotionPitch1](images/LocomotionPitch/LocomotionPitch-1.jpg)
![LocomotionPitch2](images/LocomotionPitch/LocomotionPitch-2.jpg)
![LocomotionPitch3](images/LocomotionPitch/LocomotionPitch-3.jpg)
![LocomotionPitch4](images/LocomotionPitch/LocomotionPitch-4.jpg)

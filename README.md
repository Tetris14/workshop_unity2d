# WorkShop Platformer Unity 2D!

Welcome to the Unity 2D Platformer Workshop! Today, we will be diving into the exciting world of game development and creating our very own 2D platformer. You will learn the basics of Unity and how to bring your game ideas to life. With a focus on character control, physics-based interactions, and level design, you will leave this workshop with a playable platformer that you can share with your friends and family. Let's get started on this adventure in game creation!


## Step 0 : Installation

Please refer to the SETUP.md File

## Step 1 : Setting up the scene !

- Create 3 GameObjects
-- One that will hold all of our player's body parts
-- One that will be our player ( make it a rectangle or any form you like )
-- One that will be our ground ( Stretch the ground object in order to make a platform that isn't too small )

## Step 2 : Adding Components !

- Add a component to the player that will make it react to gravity and collide with the environnement
- Add a component to the platform that will make it solid to avoid the player to pass through it

## Step 3 : Make a move !
- Add a script to your player to make it move from left to right

## Step 4 : Jump into the action !

- update your previous script to make your player jump ( you might want to look at the tag )

## Step 5 : Make a good point !

- Now we want our player to be able to point at things.
- Download and drop the sprite in the repo in your unity scene
- Click on the project window, and click on your new asset
- in the inspector window click on pivot and select left, this will make our new asset rotate from the left side and not from the center
- Add this new GameObject to our player ( just left click and drag it into your player object to make it a child )
- click on this arm game object and then in the inspector window in sprite renderer click on additional settings and put the order in layer to 1
- Add a script to the arm object to make it rotate toward the mouse
- Create a game object to will be your projectile
- Make it able to collide, and add a rigidbody
- Drag and drop it into your asset folder in the project window to create a "PreFab"
- Create an empty game object that will be our shooting point
- Make this shooting point a child of your pointer
- Move your shooting point at the edge of your pointer so that it shoots at the end of the pointer
- Update your pointer script so that it ***instantiate*** the projectile prefab your created previously at the position of your shooting point
- Make your projectile prefab go in a straight line and when it collides with something ***destroy*** it
- Make your projectile able to hurt your slime
- when your slime is at 0 hp ***destroy*** it

## Step 6 : Make an enemy !
- Drag the enemy asset from our repo in your scene
- Add a hp to it
- Make it move from left to right
- Make it able to take hits and die

## Step 7 : Have fun !
- Now that you know how to create a player that is able to move and shoot and how to create basic enemies and platforms you make your own little platformer.

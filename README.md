#Love2D Game - Player and Tile Movement
This is a 2D platformer game built using Love2D framework. In this game, the player can move left and right and jump, and tiles move to the left as the player moves to the right.

#Table of Contents
    Love2D Game - Player and Tile Movement
    Table of Contents
    Getting Started
    Prerequisites
    Installing Love2D
    Gameplay
    Controls
    Gameplay Mechanics
    Assets
    Code Structure
    Variables
    love.load
    love.update
    love.draw
    Authors

#Getting Started:

#Prerequisites:
A computer with either Windows, macOS, or Linux operating system
Love2D framework
Installing Love2D
Follow the instructions on the Love2D website to install the framework on your computer.

#Gameplay:

#Controls:
Move left: Left arrow key
Move right: Right arrow key
Jump: Up arrow key
Gameplay Mechanics
The player can move left and right and jump. Tiles will continuously generate and move to the left as the player moves to the right. When the player reaches the right edge of the screen, they will reappear on the left side of the screen, and the tiles will also shift to the left. A box will occasionally generate at a random height on the right edge of the screen.

#Assets
The game uses the following assets:

sprites/box.png - image for the boxes that appear on the screen
sprites/tile.png - image for the tiles that make up the platform
sprites/background.png - image for the background
sprites/Soldier.png - image for the player character
Code Structure
The game is written in Lua, and the main code is in the main.lua file.

#Variables
The following variables are used in the code:

player: table that holds information about the player, including its position, size, velocity, and jump properties
ground: table that holds information about the ground, including its position
box_image, tile_image, and background_image: images for the boxes, tiles, and background, respectively
tiles: table that holds information about the tiles
tile_size: size of each tile

#love.load
The love.load function is called when the game starts and is used to initialize the game state. In this function, the player's spawn position is set, and initial tiles are generated.

#love.update
The love.update function is called once per frame and is used to update the game


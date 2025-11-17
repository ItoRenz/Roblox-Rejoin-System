# Roblox Rejoin System

A Roblox script that saves and restores player positions upon rejoining the game, ensuring seamless gameplay continuity.

## Features

- Automatically saves player position before rejoining
- Restores player to exact location after rejoining
- Includes a command to trigger rejoin functionality
- Designed for smooth character spawning and positioning

## Usage

1. Add the script to your Roblox game
2. Players can type `!rejoin` in chat to trigger the rejoin functionality
3. The system will automatically save their current position and teleport them back to the same location after rejoining

## How It Works

- Player positions are stored using `CFrame` values when the rejoin command is executed
- The system waits for the character to fully load before teleporting
- Position restoration occurs during the `CharacterAdded` event

## Requirements

- Roblox Studio
- Basic understanding of Roblox scripting

## Author

ItoRenz00

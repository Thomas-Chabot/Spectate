# Spectate

## Purpose
This module provides an easy way to allow spectating on Roblox. All the logic, input & camera changes are handled by the module; the only work that has to be done by other programs is to set it up with a list of active players & activate/deactivate the module as necessary.

## Notes
This module supports control from gamepad controllers, mobile devices and laptops/desktops. Gamepad controllers are handled through the use of the L2 & R2 buttons, while mobile/desktop/laptop will be given an arrow interface which can be clicked to cycle through players.

## Downloading
The easiest way to get the module is from the model on [Roblox](https://www.roblox.com/library/2014842090/Spectate-Module).

This can be inserted directly into Studio to use in games.

## Usage
### Requirements
The module must be run locally from a LocalScript.

### Constructor
The module must be required to work.
The constructor can be called through module.new() and takes no arguments.

### Methods
There are four available methods from the module:
1. setup (activePlayers : Array of Player)

      Purpose: This must be called before the Spectate module can be used.
      
      Arguments: activePlayers should be a list of players active in the game who may be spectated.
    
2. removePlayer (player : Player)

      Purpose: Removes a player from the active players list.
      
      Arguments: player - The player to be removed. If this is not an active player, will be ignored.

3. activate ()
      
      Purpose: Activates Spectate mode, which allows players to watch other players & cycle through the list.
      
4. deactivate ()

      Purpose: Deactivates spectate mode, returning the player to their own character & ignoring all input.


## Feedback
Feedback can be sent to me through [Roblox](https://www.roblox.com/messages/compose?recipientId=284140).



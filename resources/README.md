![Over_Gravity Logo](/resources/textures/logo.png)

## Game Resources

If you have made it into this folder than you are probably looking for ways to make changes
to Hyper_Gravity. I hope that you enjoy your game editing endevours and this readme will
hopfully help guide you through many of these changes.

### Folders/Files

- levels
  - This folder stores all information about the levels in the game. This does not include textures. If you are looking to make your own levels or edit prexisting ones, this is the place to go!
- sounds
  - By replacing the sounds in this folder with new sounds of the same name, you can edit the sounds in the game.
- textures
  - The same as the sounds folder, but for textures!
- augments.csv
  - This file stores the properties of the augments. This doesn't change how they effect the game, but it can change the name, icon, and description.

### Creating/Editing Levels

If you are interested in changing levels here is what you need to know. There are two
files associated with each level. The level map and the properties file. The map dictates what
the level looks like and the properties change how it plays. Both of these files are CSV
and can easily be edited.

#### Level Map
When changing the level map you can change one of the numbers to change how the level plays.
The numbers have the following meaning:

- 0 - Platforms
- 1 - Emtpy Space
- 2 - Enemy Spawn
- 3 - Player Spawn
- 4 - Teleporter

#### Level Properties
You can also change the level properties using the following numbers:

- 0 - Location of Elevator (x,y)
- 1 - Location of Movables (type,x,y,buttonx,buttony)
  - 0 - blue crate
  - 1 - yellow crate
  - 2 - red crate
  - 3 - green crate
- 2 - Enemy Spawn Rate (in seconds)
- 3 - Enemy Birth Rate (in seconds)
- 4 - Level Goal (type)
  - 0 - Power Meter Filled
  - 1 - Interaction Objects
- 5 - Enemy Distribution (robor, roborto, robro, xxx, roo)
- 6 - Wave Level (determines which augments can be unlocked during play)
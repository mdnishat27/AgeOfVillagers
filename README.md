# Age of Villagers

It is part of a game named _Age of Villagers (AoV)_. 
The game is about people from different parts of the world trying to build their villages. 
The game will have a lot of features, of which here we focus only on the village creation part.
 
A village can have several types of objects like _house_, _tree_ and _water source_. 
There are also several nations available. Based on the nation, the objects may look different. 
For example, the house of the Inuits can be an igloo, whereas the house of the Bedouin can be a tent.

## User Stories

All the user stories are assumed to be of a _village editor_ user role.

* As a village editor, I want to create a new village.
  * When creating a new village, I want a 600px x 400px drawing space to be available.
  * If there is anything already on the drawing space, it should be cleared.
  * I want to be able to give my village a name.
  
* As a village editor, I want to save the current state of a village so that I can open it later.
  * The village should be saved in a .aov file.
  
* As a village editor, I want to open a village that was previously saved.
  * The village can be edited after it is opened.
  * When a village is being opened, I would like to choose a nation for which the village will be drawn.

* As a village editor, I want to place the following items in a village:
  * House
  * Tree
  * Water source

* I want the following steps when placing an item:
  * Select a type of item from a radio button on the side panel
  * Click on a location on the village
  * Draw the selected item at that location
  * Repeatedly click on different locations to place items of the selected type

* I want the size of the items to be as below:
  * House: 16px by 16px
  * Tree: 16px by 24px
  * Water source: varies based on the nation
  
* I want the shape of the items to vary based on the nation.

* As a game editor, I want AoV to support different nations.
  * The village looks different for different nations like the objects will vary and the terrain (that means the background) will vary.
  * The nation information is not saved with the village in .aov file. The same village can be opened with different nations.
  
#### Nations:

* I want a nation named Bangladeshi Farmers.
  * The water source is a pond and it should be 24px by 16px.
  * the terrain should be a plain green color.

* I want a nation named Arab Bedouin.
  * Bedouin villages do not build their own water source; therefore, the water sources should disappear for Bedouin villages.
  * the terrain should be a yellowish color.

* I want a nation named Egyptian Kings.
  * The water source is a well and it should be 12px by 12px.
  * The terrain should be a plain yellow color.

* I want a nation named Inuit Hunters.
  * Relies on natural water sources so it is not possible to place water sources.
  * Also, cannot plant trees.
  * The terrain should be pure white.



# B.O.T. Command GuideBook
 A short discription and guide on all the building related PocketMine commands.
## COMMAND LIST

> **__[Tool Commands]__**

**_//commands <page: 1-4>    _** 

Displays list BuilderTools commands.

**_//wand_**	 

Places World-Edit wand into player inventory.

**_//blockinfo_** (or) **_//bi_** 

Places blockinfo stick in player invontory (use stick by right clicking on a block to display contents of blockinfo).

**_//id_** 

Displays the block ID of item in player hand.

**_//clearinventory_** (or) **_//ci_**	 

Clears player invontory.

> **__[Region Selecting/Altering]__**

**_//pos1_** (or) **_//1_** 

Selects first position of a region with BuilderTools (can also be selected by __left__ clicking with wand).

**_//pos2_** (or) **_//2_** 

Selects second position of a region with BuilderTools (can also be selected by __right__ clicking with wand).

**_//center_** 

Finds the center of selected region.

**_//biome <biome ID>_** 

Changes the biome of selected region ("//biome list" displays list of selectable biomes).

**_//copy_** 

Copies selected region from where player is standing onto the BuilderTools clipboard.

**_//cut_** 

Cuts out selected region and copies it to BuilderTools clipboard.

**_//paste_** 

Pastes copied region where player is standing.

**_//merge_** 

Pastes copied region where player is standing without removing any perviously placed blocks in the region.

**_//rotate <y> [x] {z}_** (or) **_//rotate <# of degree>_** 

Rotates copied area on the specified axis or specified amount of degrees.

**_//flip x_** (or) **_//flip y_** (or) **_//flip z_** 

Flips copied selection on specified axis.

**_//move <x> <y> <z>_** 

Moves blocks within selected region specified distance on the specified axis ("//move 20 0 0" would move blocks within 
selected region 20 blocks on the x axis).

**_//stack <count> [side|up|down]_** 

Copies selected region in specified direction the number of times listed and pastes based off of origin of selected region.

**_//fill <id1,dmg1,id2,...>_** (or) **_//set_** (or) **_//change_** 

Fills the selected region with specified blocks.

**_//replace <blocksToReplace: id1,id2> <blocks: id1:dmg1,id2,...>_** 

Replaces specified blocks inside selected region with blocks stated in the second statement.

**_//outline <id1,dmg1,id2,...>_** 

Fills selected region with specified blocks leaving a hollow interior.

**_//walls_** 

Creates a wall of stone around selected region.

**_//naturalize_** 

Replaces blocks inside of selected region with grass, dirt, and stone.

**_//undo_** 

Undo the previous completed world altering action.

**_//redo_** 

Redoes previously undone world altering action.

> **__[Shape Commands]__**

**_//sphere <id1:dmg1,id2,...> <radius>_** 

Creates a sphere of specified blocks and size on the position of the player.

**_//cube <id1:dmg1,id2,...> <radius>_** 

Creates a cube of specified blocks and size on the position of the player.

**_//cyl <id1:dmg1,id2,...> <radius>_** 

Creates a cylinder of specified blocks and size on the position of the player.

**_//pyramid <id1:dmg1,id2,...> <radius>_** 

Creates a pyramid of specified blocks and size on the position of the player.

**_//hsphere <id1:dmg1,id2,...> <radius>_** 

Creates a hollow sphere of specified blocks and size on the position of the player.

**_//hcube <id1:dmg1,id2,...> <radius>_** 

Creates a hollow cube of specified blocks and size on the position of the player.

**_//hcyl <id1:dmg1,id2,...> <radius>_** 

Creates a hollow cylinder of specified blocks and size on the position of the player.

**_//hpyramid <id1:dmg1,id2,...> <radius>_** 

Creates a hollow pyramid of specified blocks and size on the position of the player.

**_//island <id1:dmg1,id2,...> <radius> [step]_** 

Creates a island of specified blocks and size on the position of the player.


## //DRAW GUIDE
Command: //draw <shape> [brush size 1-10] {Gravity true/false}

> __*Avilable Shapes*__

• Sphere

• Cube

• Cylinder

(Note: there are also hollow variants of each shape far example "hsphere" for a hollow sphere)

> *__Command Usage:__* 

<shape> contains the shape you would like to place while drawing. [Brush Size 1-10] is the specified size of the shape which you have selected in previous statement. {Gravity True/False} specifies weather or not to have the blocks fall to ground level once placed. "//draw off" will turn off brush tool.

:warning: BE SURE TO __ALWAYS__ RUN "//draw off" WHENEVER YOU'RE FINISHED USING THE COMMAND TO AVOID ACCIDENTAL BLOCK PLACEMENT.

> *__Tool Usage:__* 

Once a brush is active it will will draw with whatever block the player is holding in their hand, to draw simply right click pointing your crosshair where you'd desire the shape to be drawn. If you wish to erase blocks hold the axe-wand in the player hand and right click pointing your crosshair in the direction of the area you would like to erase.

__EXAMPLE:__ 

• //draw sphere 5 false

This command will allow me to draw a sphere that is size 5 and has no gravity properties turned on (this excludes blocks that are affected by gravity by default such as sand).


## BLOCK-SNIPER GUIDE

> *__Brush Menu__*

• Bush Mode

Changes between brush mode to selection mode.

• Brush shape

Changes the shape of the brush.

• Brush Type

Changes the properties of how the brush interacts with the environment.

> *__[Brush Editor]__*

__Brush Sizing:__

• Brush size

Changes the size of the specified shape when using brush.

• Brush Width

changes the width of specified shape when using brush.

• Brush Height

changes the height of specified shape when using brush.

• Brush Length

changes the length of specified shape when using brush.


__Brush Effects:__

• Decrementing Brush

When using brush the brush size will gradually decrease.

• Hollow Brush

Will place specified shape with a hollow interior when using the brush.

• Brush Blocks

Specifies what blocks to place while using brush.

> *__Tool Usage__*

To acess the brush menu hold a __blaze rod__ in player hand. Once all menu settings have been selected hold the __blaze rod__ in player hand and point the crosshair in the direction of which you desire the blocks to be placed, and right click to start placing with the brush. If you wish to stop using the brush select a differnt hot-bar slot then the one with the __blaze rod__.

> *__[Brush-Type List]__*

**_-Biome_**

Alters the biome of a region.

**_-Clean_**

Removes MOBS and dropped items.

**_-Drain_**

Removes water.

**_-Expand_**

Enlarges a region of a previous brush placement.

**_-Fill_**

Simply places a fully filled shape of specified properties with the brush.

**_-Flatten_**

Places only on the top block layer of an area creating a flat surface.

**_-Layer_**

Places with brush by layering sections on top of eachother while placing.

**_-Melt_**

Slowly removes a portion of previously placed blocks.

**_-Overlay_**

Overlays on top of previously placed blocks blanketing over them.

**_-Replace_**

Replaces specified blocks when using brush.

**_-Snowcone_**

Overlays the top layer of a region with snow layers.

**_-Regenerate_**

Sets a region back to its original seed  default.

**_-Freeze_**

Freezes water and hardens ice.

**_-Warm_**

Melts snow layers and Ice.

**_-Heat_**

Affects blocks as fire would, for example burning leafs.

**_-Smooth_**

Smooths out a section of blocks.

## MULTI-WORLD GUIDE

> *__[Creating a New MW]__*

Command: /mw create <name> [seed] {generator}

> *__Avalible generators__*

• Nether

• End

• Skyblock

• Void

> *__Command Usage:__* 

<name> is what you would like to name the MW you are creating this can be anything. [Seed] is the world seed which you would like to have generated (this is typically 0). {Generator} is where you specify the world generator type of which you desire to make.

Note: MW's with spaces in the name will require you to type the name out using "" for it to be recognized properly.

__EXAMPLE:__

• /mw create test 0 skyblock

This command will generate a void world with a singal skyblock island at spawn and the world will be named "test".

## BUILDERTOOLS SCHEMATIC GUIDE

Command: //schem <load|create|list|paste> [file name]

> *__Creating a Schematic__*

To create a schematic file using BuilderTools you must first select the desired region using the BuilderTools wand. Once a region is selected run the command //schem <create> [name].

> *__Command Usage:__*

<Load> loads the specified schematic file. <Create> is the command to type when creating a new schematic. <List> Displays a list of all schematic files on the server. <Paste> places thje specifide schematic into the world. [Name] is where you place the name of the desired schematic file (unless you are creating a new schematic then [name] is where you place the name of which you would like to call your new schematic file).

__EXAMPLE:__

• //schem create test

This command will create a new schematic with the file name of "test".

• //schem paste test

This command will paste the schematic file with the name "test".

• //schem list

This command will load the list of all schematic files on the server.

• //schem load test

This command will load the file with the name of "test" so it is ready to paste.

# Saving and Loading
You are able to save and load your tilemap projects in JADE. When you save there are two files that are created:
- Project **[.lua]** File
    - This is a file that holds all the information about your project. Asset Id names, filepaths, and the filepath to the .map files for the colliders and the tiles
- Tile **[.map]** File
    - The [.map] file is a txt file that contains all of the information about that tile. Asset ID, collider, width, etc. 

- Collider **[.map]** File (optional)
    - There may be a case where you want to create colliders that are not associated with a specific tile. Therefore we have the colliders .map file. It has the same information as the tiles .map file, without the sprite information. 
    
    *The **_colliders.map** file is only created if there are box colliders in your tilemap.*
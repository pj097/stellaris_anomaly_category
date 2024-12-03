Mod generation process is detailed in create_mod.ipynb. 

definitions.csv can be modified with your own, but the notebook still needs to be run to re-generate the mods. 

Simply copy localisation/ and descriptor.mod into your mod directory.

The generation script first checks for an existing table (the CSV file which can be edited using, e.g. Excel), therefore you can modify the CSV file with your own definitions, colouring, etc. In the future I'll split the script into two as the current wiki put a new requirement on having more complex Python libraries such as Selenium. The future iteration will have a script that generates the mod files from the table file without requiring the user to install scraping libraries. 

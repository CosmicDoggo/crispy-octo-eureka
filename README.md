# Albion Item and Crafting Data
This repo is dead and only serves to archive data that others may find useful. Feel free to do whatever with this data, including reposting it in its entirety.

The data was last updated: Aug 5, 2024

Back when I used to play Albion I made some personal tools to help with trading and crafting. I no longer play the game, but found this file when I was cleaning my PC. I figured I should upload it so others can use it.

Data is structured as follows:
```
"ItemAPIName": {
        "Index": "Game generated item ID",
        "Real Name": "The item's in-game name",
        "Description": "The item's in-game description",
        "Craft Amount": "The base amount crafted from a single craft",
        "Ingredients": {
            "CraftingItemAPIName #1": amount required for 1 craft,
            "CraftingItemAPIName #2": amount required for 1 craft,
            "CraftingItemAPIName #3": amount required for 1 craft,
        }
},

ItemAPIName (same for the Crafting) is the name the game's API uses. 
T5_HEAD_LEATHER_FEY@2, one such name, means an "Outstanding Expert's Mistwalker Hood"
T5 is the tier (Expert's here),
HEAD_LEATHER_FEY is the api name for "Mistwalker Hood",
@2 is the item quality (its 0 indexed so no number is Normal, 1 is Good, up to 4 which is Masterpiece)
```

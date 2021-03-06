What is this?
------------------

This library of functions is a JS wrapper for the Guild Wars 2 public API. It wraps the current APIs available with functions and provides some utility functions.

Requirements
------------------
jQuery 1.8.0+ (2.0.0 with AJAX only included)

Installation
------------------
Include the following wherever you are loading your libraries, make sure it is loaded after jQuery
`<script src="gw2-api-wrapper.js"></script>`

Function Reference
------------------

###General
**checkValidLanguages(language)** - Checks if the given language is available with the API

###Dynamic Event API
**getEvents(worldID, mapID, eventID)** - Gets all events, filtered by the given arguments  
**getWorldNames([language])** - Gets all world names and caches them  
**getWorldName(worldID [,language])** - Gets a single world's name  
**getMapNames([language])** - Gets all map names and caches them  
**getMapName(mapID [,language])** - Gets a single map's name  
**getEvents([language])** - Gets all event names and caches them  
**getEvent(eventID [,language])** - Gets a single event's name  

###WvW API
**getWvwMatches()** - Gets all currently running WvW matches  
**getObjectiveNames([language])** - Gets all WvW objectives and caches them  
**getObjectiveName(objectiveID [,language])** - Gets a single objective's name  
**getMatchDetails(matchID)** - Get the details of a single match  

Added: 
getMatchDetailsBorder(matchID, border)


###Item and Recipe API
**getItems()** - Gets a list of all item IDs  
**getItemDetails(itemID [,language])** - Gets a single item's details  
**getRecipes()** - Gets a list of all recipe IDs  
**getRecipeDetails(recipeID)** - Gets a single recipe's details

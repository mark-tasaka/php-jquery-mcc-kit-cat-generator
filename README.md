# php-jquery-mcc-kit-cat-generator
The Mutant Crawl Classics Iconic Non-Player Character Generator is designed primarily with PHP and jQuery.  The Launch Page has a series of drop-down menus, where the user selects weapons, armour, artifacts, character level, etc. for the Iconic NPC.  When the user generates the iconic NPC, the information (variable) the user selects is collected through POST methods and added to the iconic character sheet.  

Several of the variables POSTED modify the values on the character sheet; therefore, jQuery or PHP functions have been created to make these adjustments possible. Several of the jQuery/JavaScript functions are stored in external files, as a means of creating greater design efficiency, with the goal of writing a program with high cohesion and low coupling.  In this way, this program simulates Object-Oriented design.  JSON is used to store multi-column variables, with jQuery functions used to retrieve these variables.    

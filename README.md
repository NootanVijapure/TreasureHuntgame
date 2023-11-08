# TreasureHuntgame
Step 1.Create the Location class
Create a new Java class named Location and provide it with two private fields: name and description.
Create a constructor for the Location class that initializes these fields.
Create getter methods for the name and description fields.

Step 2: Create the Treasure class
Create a new Java class named Treasure with three private fields: name, description, and value.
Implement a constructor for the Treasure class that initializes these fields.
Create getter methods for the name, description, and value fields.

Step 3: Create the TreasureHuntGame class
Create a new Java class named TreasureHuntGame.
Define the main method:

Step 4: Declare and initialize data structures
Inside the main method, declare and initialize the different data structures(Map,list,set)
- create map locations with <String, Location> as kep value pair 

- create list treasures which containes list of treasure

- create set inventory which contains list of treasure

setp 5: Populate locations and treasures
Populate the locations map and the treasures list with a few initial locations and treasures of your choice.

Step 6: Implement the game loop
Create a while (true) loop to keep the game running until the player decides to quit.

Step 7: Display the current location
Inside the game loop, retrieve the Location object for the current location.
Print the location's description.

Step 8: Prompt the player for actions
Display a menu for the player to choose from:
"Do you want to (1) Pick up a treasure, (2) Move to the next location, or (3) Quit? "

Step 9: Implement player choices
For choice 1, implement the logic for picking up a treasure.
For choice 2, implement the logic for moving to the next location (You can prompt the player to enter the name of the location).
For choice 3, display the player's inventory, calculate the total value of the treasures, and end the game.

Step 10: Implement the showTreasures, showInventory, and calculateTotalValue methods 

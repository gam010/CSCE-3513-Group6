# CSCE-3513 Laser Tag Project
## Project Members:
Gabriel Miranda: gam010

Eduardo Tenorio: eduardot26

Tommy Ngo: TommyN28

Cole Goodwin: cag029
### Instructions to Run:

The user must first start by downloading the required Python packages needed for the program's functionality. 
The user will need to update the Ubuntu platform, 
--sudo apt-get update. 

Also, due to some extra libraries being used, the user will need to have pip3 installed on their device, 
--sudo apt install python3-pip

To be able to use the Tkinker library the user will need to install Pillow,
--pip3 install pillow

Since a database library is also being used the user will need to install the library for Supabase,
--pip3 install supabase

The main file for this project is called main.py, and it needs to be run using python3. In case there are some errors due to missing imports with tkinker, additional commands need to be run to install the missing packages.

--sudo apt-get install python3-tk

--sudo apt-get install python3-pil python3-pil.imagetk

Then the user, using the command python3 main.py, should execute the code.

### Interacting with the Program:

The program simulates a 1980s-style laser tag game. Upon starting the program, the user is greeted by a short splash screen before the player entry screen is presented. On the player entry screen, the player will click a button to enter their ID and codename. 
That information will then be displayed on the list of players within the specified team, red or green. The information of the player is also stored in the game's database. This allows for a new game to be started and a player can retrieve their already existing player information to easily join the new game.

Upon running the program, the user is presented with a display of the empty list of players for both teams. The user can enter a new player into each team by providing a username, a player ID, and an equipment ID. The game requires there to be at least one player on each team otherwise it will not start. There also cannot be duplicate player IDs or equipment IDs. A maximum of 15 players per team is allowed. The list of players can also be reset if the user presses the F12 key. When the user is ready to begin the game, they can press F5 to begin the game's countdown timer. During this time, no action can be performed on the player entry screen. Once the countdown timer is complete, the player entry screen is replaced with the player action screen.

In future versions, the player action screen will display the list of players and their score, as well as a running log of player actions against one another.

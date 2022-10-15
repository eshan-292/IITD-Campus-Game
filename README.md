# INSTALLATION INSTRUCTIONS

MACHINE - 1 - Ubuntu Linux
- SDL2 - sudo apt-get install libsdl2-dev
- SDL2_image - sudo apt install libsdl2-image-dev
- SDL2_ttf - sudo apt-get install -y libsdl2-ttf-dev 
- SDL2_mixer - sudo apt-get install -y libsdl2-mixer-dev

MACHINE - 2 - M1 Mac OSX
- SDL2 - install the library from libsdl homepage (https://www.libsdl.org/download-2.0.php)
- SDL2_image - install the library from libsdl homepage (https://www.libsdl.org/projects/SDL_image/)
- SDL2_ttf - install the library from libsdl homepage (https://www.libsdl.org/projects/docs/SDL_ttf/SDL_ttf.html)
- SDL2_mixer - install the library from libsdl homepage (https://www.libsdl.org/projects/SDL_mixer/)

- After installing the libraries, copy the framework files into /Library/Frameworks/ 




This consists of the main map of the IIT Delhi Campus with interconnecting roads. The game tries to mimic the objectives of
a student till graduation from IIT
- Key arrow up, down, right, left would be used for commuting in between the places.
- To take a yulu cycle one must go near a yulu stand and press the key ‘y’
- Similarly to drop a yulu cycle one must go to another/same yulu stand and drop there
- If someone has taken yulu then his total money would be deducted by 1 for every 1 second



There are several grounds in the campus where a person can play sports
- In tennis court for every game energy would be decreased by 10 points, health and happiness would be
increased by 10 points
- Similar change of attributes happen in all outdoor sports like volleyball, football, hockey,cricket


Inside access is provided only for 2 hostels – One of the player can go inside Shivalik other inside
Satpura, since these are hostels of the creators of the game (us ;p). 
Inside the hostel:

- One can have food in mess leading to decrease in happiness by 5 and increase in energy by 10
- By playing table tennis energy would be decreased by 5 units and happiness would be increased
by 5 units
- A player can also go in the room of the corresponding hostel and sleep there.
- For every 1 second of sleep health and energy would be increased by 1 unit


We have also replicated all the food outlets inside the campus.
- For every meal taken outside mess money would be decreased by 20, health by 10
- Happiness and energy would be increased by 10


Now coming to the LHC (Lecture Hall Complex) three lecture halls are shown where the following lectures are going 
LH325 – MTL390
LH108-COL226
Lh114 - COL216

When a player enters a lecture hall then for every second of lecture -
- His health, happiness, energy decreases by 1
- His knowledge would be increased by 1

We also have the central library in our game:
When a person starts studying in the library then for every second of study -
- His health, happiness, energy decreases by 1
- His knowledge would be increased by 1

Also the CSC (Computer Services Centre):
For every second spend inside csc -
- His health, happiness, energy decreases by 1
- His knowledge would be increased by 1

Finally we have the SAC (Student Activity Centre):
- Inside SAC a person can either do weightlifting or play badminton both of which will lead to
change in attributes similar to other outdoor sports
- Listening to music causes a decrease in energy of 5 and an increase in happiness of 5
Inside OAT (Open Air Theatre) – we have a dance show going on
- For every second spent inside the OAT happiness would be increased by 1

Some General Comments:
- The icons for health, energy and happiness are dynamic in nature
- We have added quite a few interesting animations (look out for them while playing), for instance audio effects for dancing, peacocks etc and motion effects for rabbits, cats, sweepers, sleeping, playing different sports and many more.
- Also we have setup the win loss parameters after exhaustive testing by playing with each other, so that the gameplay is neither too easy nor too hard. 
- There is randomness in the game as well in the sense there can be angry professors, hungry dogs who appear at random places and can attach the player if he/she is in the radar.



Bonus Level Features:
- If a person has money >=60 then the person can buy a jetpack from this money
- The jetpack lasts for 15 seconds or the entering of the player to some location
- If the player does not enter into any location then the jetpack would be removed and the person
would be brought back to the point where he took the jetpack













# ONLINE RESOURCES

 - Geek for geeks website - for the code of using sockets
 - https://www.pixilart.com/draw - For making all pixelated objects
 - Stackoverflow - for resolving errors related to running of code and installation of libraries
 - https://lazyfoo.net/ - for learning SDL2
 - http://www.sdltutorials.com/sdl-net-part-1-user-tutorial



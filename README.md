# winterWonderland
Calm winter-based game in which you play as an elf who interacts with his environment!

This game is still in development! Early early earrrrly version being released just to keep track of what is being done between versions.
So, what has been done so far:

Player: moves around a world (WASD) and interacts with objects (clicking). You can switch between unlocked skins (left \ right arrow buttons) which you obtain by completing unknown achievements! Finally, there is a save feature (V) that saves your progress and statistics.

Objects \ entities: Collision is detected on the top and bottom sides of each object, and layering is complete so that when the player is above
an object it shows the object in front of the player. Each object, when hovered over with the mouse, shows an outline that confirms it's
selected. When an object is clicked on, a random phrase will pop up from that object (some are worse than others, you've been warned!).
Entities created so far: trees and penguins.

Weather: snow, just for asthetic reasons, doesn't change anything in-game except make it feel more like winter!

Hopes for the future:

- create a panel that shows controls
- create a panel that shows statistics (steps taken, number of interactions, etc.)
- create deer \ reindeer, polar bears, and other but much rarer entities!
- add more skins (only 8 as of now, 1 permeanently unlocked as the starting skin and 7 able to be unlocked)
- music (being worked on!)

NOTE: When \ if you download the .zip file versions, extract it in a folder, because the .jar file needs the images+and+data folder in order to put the images on screen and also to read in your skin and statistics data. Over all else just make sure they're in the same place, whether it be on your desktop or in a folder.

EXTRA SPECIAL NOTE: If the game does not open, you may need to download the Java Development Kit (JDK) that is distriuted for free by Oracle. These are the files that I use to make everything, so if the game doesn't have access to them then it will crash! Here's a link to Oracle's JDK download page (as of Jan. 2020):

https://www.oracle.com/technetwork/java/javase/downloads/index.html




VERSION UPDATE NOTES:




Beta Version 2:

+ Added goblins! Sit still until you get close enough, then they chase after you!
+ Made skin selecting easier, now you can use both the left and right arrow keys to switch between skins not just
the right arrow key
+ Added an autosave feature (15 min intervals)
+ Added 4 more skins to be unlocked!
+ Implemented random replacement! -
    This means that whenever an object has been interacted with, and you go far enough away from it, it will
    be replaced with another random object, making it so the environment is always changing.
+ Fixed a bug with interacting - before, you could endlessly click on an object and rack up your number of
interactions, now this has been fixed so that as long as an object's phrase is present, it can't be interacted with.
+ Made interacting easier. Before, if you were going to interact with something, you'd most likely have to sit still
and click on it, but now you can continue running and click on whatever you desire!


Beta Version 3:

+ changed the window size so that it fits easier on any given screen. Before there were some problems with phrases showing
up on the bottom of the screen but this is fixed now!
+ added another skin!
+ Made the map twice as large with twice as many objects within it!
+ Made it a little easier to get certain achievements \ skins


Beta Version 4:

+ source code is now included for all you programmers (or just curious peeps) in the "src" folder. The program is not
dependent in these files, so you can do with them what you will!
+ added a few new entities, with a new type that runs away if you click on them and you're close enough! There is
also a new feature - when a rare entity is spawned, a message will appear saying "Something magical happened!"
+ changed the random replacement algorithm to compensate for new creatures
+ added new skins once again!


Version 1.0:

+ Woo! Finally all packaed up in a .jar file. This is the first stable version of Winter Wonderland that doesn't have so
many annoying folders that come with it, its all within!
+ Changed the structure of the code, source code is no longer included

Version 1.2:

+ Had some trouble saving and loading information from the text file in the .jar, decided to have it be outside the .jar, so place it within a folder and a .txt file should pop up with all of your saved player data!
+ Also couldn't see trees or snowmen, all fixed!

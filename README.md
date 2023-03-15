# Sons-Of-The-Forest-Save-Game-Companion

  This program allows you to edit Sons of the Forest savefiles for different functions like regrowing trees or reviving companions.

## Prerequisites
  **Newest version contains automatic backup function, yay!**
  In order to use this program, you will need to have JDK 19 installed on your system. You can grab a copy of it from the following link: 
  https://www.oracle.com/java/technologies/javase/jdk19-archive-downloads.html (Without this you will get a the error message "A Java exception has occured" when running the .jar file)
  
## .jar VS .exe

  If you have issues with the .jar version, grab the .exe version instead, place it in the same directory
  
## Usage
  Download the SOTF-SGC.jar file from the repository.
  Place the .jar file in the same folder as your Singleplayer and Multiplayer folders are in the save folders directory. For example:

  C:\Users\USER\AppData\LocalLow\Endnight\SonsOfTheForest\Saves\76561198082060965\[Place .jar here]
    
  Run the .jar file inside the folder and edit your savegame to your preference:)

## Current work
  I appreciate any form of feedback on my work and I currently plan to add more functions to it, so keep the suggestions coming. Things i am/will be working on are:
  -Savable spawnpoints for you and your companions to teleport to
  -The ability to set the state of fallen trees/plants to that of a different save
  -Toggle the gps locator shown on the map
  -Sort the saves based on the time of save
  -Implement a filechooser so that you can place your .jar anywhere
  -More logical save to changes made
  -Backup files on save
  
## Known issues
  Currently the changes being made are saved directly to the save files, meaning changes to items located in saveData.json takes a second or two. This is because the saveData grows in size as you progress through the game. (Mainly affects changes to companions).
  
## Contributing
  If you would like to contribute to this project, please feel free to fork the repository and submit a pull request with your changes.
  
## Contact
  If you have any questions or concerns about this program, please contact the author at henkeharshagen@gmail.com.

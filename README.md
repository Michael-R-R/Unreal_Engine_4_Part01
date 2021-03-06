# Unreal_Engine_4_Part01
Localized place to showcase all new features learned and implemented in Unreal Engine 4 


ENEMIES AND HEALTH BARS:
  - Implemented first stage of enemy prototype, includes:
    - Enemy health bars above their heads
    - Rotating health bars wherever the player moves
    - Shows amount of damage done per hit, with different colors for regular hit or critical hit
    - Random scaling of the particle emitters per hit to provide some variety in particle size

![EnemyHit](https://user-images.githubusercontent.com/54217603/114228765-ee505500-9944-11eb-9080-4b2baa20ab8a.gif)


PORTALS AND GLASS WALLS:
  - Implemented two types of portals: Player portals && Projectile portals
  - Demostration of a projectile portal being used to solve simple puzzle and by-passing the glasss wall.
  - Things to note: 
    - Green progress bar's rotation follows player so that player is able to see it clearly. 
    - Upon reaching 100% on progress bar, it resets back to original position.


![DissolvingGlass](https://user-images.githubusercontent.com/54217603/114225759-b810d680-9940-11eb-860d-a55f6ea5f333.gif)

OPEN SEASAME:
  - Implemented interactable object with UI prompt
  - Demostration of a door that a player can interact to open && close
  - Functionality can be expanded to other interactable objects of differing variety
  - Things to note:
    - Object can only be interacted with if player is looking at it
    - UI prompt disappears after interacting with the door and redisplays after getting within distance again

![OpenDoor](https://user-images.githubusercontent.com/54217603/114724581-b3b23800-9d09-11eb-9676-e2ab5020f1f2.gif)


LETS GET TECHNICAL:
  - Updated the material of the vanishing glass wall with a energy wall material created inside the editor

![EnergyWall](https://user-images.githubusercontent.com/54217603/114725694-b5303000-9d0a-11eb-8a26-bb4c8e9c5aad.gif)


UNIVERSAL LANDSCAPER FOR HIRE:
  - Began working on some landscaping to better learn the sculpting tools, lightning, and texturing
  - Using Krita and https://tangrams.github.io/heightmapper/ I created a height map and imported it into UE4
  - After importing the height map I used the erosion and raise terrain to shape the terrain to my desire
  - Used the spline tool in order to create a path way up the mountain

![StartLandscape](https://user-images.githubusercontent.com/54217603/115094375-48c05700-9eeb-11eb-873b-472c5ac40b78.gif)



# awesome-mega-project
 **THE AWESOMEST MEGA PROJECT**

## FPS (CS:GO) Vision Based Cheating Tool

### BRAINSTORMING

### refs: 
- GameScripter - A Vision Based Tool for Playing Games
  - https://www.doc.ic.ac.uk/teaching/distinguished-projects/2011/p.lipka.pdf
- Extravagant Cheating via DirectX
  - https://blog.forrestthewoods.com/extravagant-cheating-via-directx-f3b61b654b73
- Starcraft 2 Automated Player (maybe not very related)
  - http://graphics.stanford.edu/~mdfisher/GameAIs.html

### language/libs
C++ : OpenCV for image treatment (also on Python)
...

### Needs:
Lib/API to retrieve screen images in real time
Lib/API to emulate a controller
real time process analysing and determining actions
IA Graph to determine actions to do when catching an event
MV-C model ? MV : image analysis, maybe no information displayed on screen, C : controller inputs
(TODO : find the script language enabling to sends inputs but not detected by VAC --> AUTOIT)

### Thoughts: 
#### (IA)
When catching "ennemy spotted" event, needs something to know when ennemy is dead
When seeing a dead body, needs something to not shoot the fuck out of his corpse
#### (IMG)
60fps nearly impossible to process, have to process less frames
Storing images will cost too much RAM, needs to store only the useful informations 
Possibility of doing pattern recognition knowing the map to target ROI to analyse instead of the whole img (maybe not really increasing perfs)

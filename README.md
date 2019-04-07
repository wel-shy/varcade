# varcade 🕹
Virtual reality arcade

## Description 📝
Group session for a care home, set in virtual field. People will solve tasks together, or experience things together, through interacting with arcade machines. User's will pull the handle on a slot machine, which will generate a task. Full description found [here](https://github.com/wel-shy/varcade/blob/master/docs/varcade-presentation.pdf)

### Tasks for users:
 - TV
 - Pictures
 - Music Videos
 - Trivia
 - Riddles
 - Jokes

### Use Case 👵
During a group activity in a care home, residents will enter the environment using Google Cardboard headsets, and be
able to see one another in the environment. Someone, likely the facilitator of the activity will pull a leaver on the
slot machine, showing a random task. Users will then collaborate to complete the task.

## Implementation 🔨
 - Using [A-Frame](https://aframe.io/) framework.
 - Built using [Glitch](https://glitch.com/~aframe).

### TODO ☑️
 - [X] Create a scene (Floor, Sky)
 - [X] Build an arcade machine (Rectangle Entity, Lever)
 - [X] Build tasks (find riddles, look at rendering videos?)
 - [X] Animate machine (detect gaze~~, and rotate lever)
 - [X] Show task
 - [X] Complete the task

 ## Use
 Pull repository into [Glitch](https://glitch.com/~aframe). Should automatically build from index.js. If assets are missing
 download the slot machine as an `obj` from the link below. Store
 the `slot.obj` and `slot.mtl` files in Glitch's `asset` folder. Make sure to update the CDN links in `index.html` for the slot machine files in the asset manager.

#### References 📚
 - Slot machine from [Anastasiia Ku](https://poly.google.com/user/aiHLOO4KRw6)

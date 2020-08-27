# ERA SENTRY




Code Submission for Robomaster AI challenge - Perception Task 3  

  - Code for Part 3 of Perception Group : Identify enemy robots by Outpost 
  - Algorithm Provides Map Coordinates and Pose of AI Robot in real time at ~24 fps
  - Algorithm provides optional armour plate detection & numeration that has not been used by our Team

# Multimedia

  - Video: Sentry_<number> : rendering of blender environment from diagonally opposite outpost rails with randomly distributed vision tags from the AI Challenge Library
  - Arena4.png : 1/10 scale image of battlefield 1px scaled to 10mm
  - Sample_<num> scaled image samples for GUI interface


# Program
  - Pt.py & GUI.py to be used in setup for extracting mapping between image and arena coordinates
  - Tracking_<1/2>.py OpenCV based procedure for detection and tracking of AI Robot and appending to Arena4.png uses id=12,10,15,29 and their respective coordinates on the map for inverse perspective transofrmation.
  - vision_marker.py Custom Aruco-dictionary for given tags, compatible with cv.aruco method
  - 
## Core functionality

Run tracking
```sh
$ python3 Tracking1.py
```

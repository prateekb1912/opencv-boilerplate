# OpenCV Image Processing Boilerplate

An OpenCV boilerplate for future image and video processing applications for Computer Vision developers.

An Object-oriented design which is easy to follow and use.

Allows you to screenshot and screencast the VideoCapture frame for further use.

## Capture Manager

Creates a video capture frame and handles many different Video Capture functions, like entering and exiting frames, creating VideoWriter,etc.

## Window Manager

Creates frame windows and handles various keyboard callback events to interact with the VideoCapture Frame.

In this repo, we have used the following keyboard shortcuts:
- SPACE key -> Take a screenshot
- TAB key   -> Start/Stop recording video
- ESC key   -> QUIT

You can add a bunch of other key shortcuts in the Cameo class.

## How to Use

Just clone the repo and run the <code>cameo.py</code> script which implements the Window Manager and Capture Manager objects. 
Then, create functions in the Cameo class for any computer vision task.

Some image processing tasks which I have performed with the Cameo class:

- [Filtering Images](https://www.github.com/prateek-ml/photo-film-filters "Emulating Photo Film Filters by Prateek Bhardwaj")
- [Tracking Faces](https://www.github.com/prateek-ml/face-tracker-and-swapper "Face Detector and Swapper by Prateek Bhardwaj")

Happy Image Processing! :)

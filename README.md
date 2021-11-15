# Drowsiness and Yawn det

https://user-images.githubusercontent.com/86318286/141834068-ccd71212-9dfe-4a68-92ca-4a3288998d8c.mp4

ection with voice alert using Dlib

Simple code in python to detect Drowsiness and Yawn and alert the user using Dlib.

## Dependencies

1. Python 3
2. opencv (tested with 3.4) 
3. dlib	(tested with 19.18.0)
4. imutils (tested with 0.5.3)
5. scipy
6. numpy
7. argparse

## Run 

```
Python3 drowsiness_yawn.py -- webcam 0		//For external webcam, use the webcam number accordingly
```

## Setups

Change the threshold values according to your need
```
EYE_AR_THRESH = 0.3
EYE_AR_CONSEC_FRAMES = 30
YAWN_THRESH = 10`	//change this according to the distance from the camera
```

## Authors

**Arijit Das** 


## Acknowledgments

* https://www.pyimagesearch.com/




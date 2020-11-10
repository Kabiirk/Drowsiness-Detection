# **DROWSINESS DETECTION**

## Contents
* Introduction
* Tools used
* Get Started !
* Working of the Project

### Introduction
---

### Tools Used
* OpenCV
* Numpy
* Time
* Keras (to load the model via ```load_model()``` function in keras.models)

#### NOTE: There is a mixer library imported from imported from pygame, but currently the sound isn't working (sound should alert the user upon detecting drowsiness, its still work in progress)

---

### Get started !
**STEP 1: Run the project**
To run the project, just open you command line and run *drowsiness_detection.py* from the command line by typing:
```
python drowsiness_detection.py
```
Upon which, a window will open showing the webcam's input

### **Working of the Project**
Whenever the model detects that you eyes are closed, the score starts increasing, and decrases when it is detected that your eyes are open.

## All Done :sparkles:

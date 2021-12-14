# AR KEYBOARD

This project aims to create a virtual keyboard which can be oeprated by pointing to a key on a virtual grid using the camera. 
First a grid is created and the respective characters are inserted into it. 
A random color is chosen and made into a physical pointer. The color of this is obtained by thresholding so that only the color shows a white pattern while the rest of the frame is black. 
When the video camera is switched on, the input frames are also thresholded so that the only input the program receives is the pointer. 
The location of the pointer is then tracked. Every time the pointer stays above a key for a given interval, the key is clicked and the input is saved. 

*First run range_det.py to for the pointer color*
## Progress
- A single finger input has been created. 

## To do
- Add more functionality and increase precision. 
- Also try to add tracking for multiple fingers. 

**range_det.py was obtained from 
https://github.com/EvilPort2/SimpleGestureRecognition/blob/master/range-detector.py

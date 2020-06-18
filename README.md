# real time object detection

This project is based on OpenCV and is used to identify any object which is static for certain amount of time.
After identiying any static object an alert is sent via mail to the desired person.
Input can be in a form of a video or a live stream such as CCTVs.



CODE 1 is used to create frames from a video

CODE 2 is used to create a mask over video so that object will be detected in that particular unmasked area.

CODE 3 is the mail code for the project

REMEMBER that few things are needed to be adjusted based on the inputs and objects to detect like either use dilate or morphological tranformation and etc...

INSTALL python , openCV , cv2 , and other related libraries.

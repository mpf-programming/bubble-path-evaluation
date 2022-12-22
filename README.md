# bubble-path-evaluation
Written during my bachelor´s thesis, the script uses computer vision to track the bubble path of an Shadowgraphy measurement. We analyzed amplitude and frequency of the bubble path to learn how different additives affect the climb up, e.g., in flotation processes. 
Shadowgraphy was applied to determine main bubble characteristics, such as equivalent diameter, morphology, and rising velocity. 
https://www.sciencedirect.com/science/article/pii/S0009250919301009#f0095

## General Information
The coordinates in the .csv-file can be used to draw the bubble path. 
It can be easily compared with other bubbles. 
The path could be fitted with a sinusoidal function to gain further insight, e.g., frequency or amplitude and to discover the effect of additives.

## Sample data
The sample data contains 54 .jpg images, obtained with a high speed camera via shadowgraphy method so that the script can be tested. The images show the rise of a single air bubble in an aqueous solution of hexadecylamine (HDA).

## Modules
Tested the last time on December, 2022. 
opencv(cv2) v4.5.5
numpy 1.16.6
sys
os 

## Copyright:
Micha P. Fertig, 2021

## Common errors
- Module cv2 is not installed -> pip3 install opencv-python 
- File path is not correct. -> the script uses two different file paths. The path has to end with two \\ to mark the end of the raw-string.
https://stackoverflow.com/questions/11168076/why-cant-i-end-a-raw-string-with-a-backslash




# Number Plate Detection Application
This is a GUI application which is used to identify the number plate of vehicles from images and convert them into a string so that it can be further processed.
It uses many Digital image processing algorithms to process the image and identify the number plate from it.

## Implementation
It is a very useful tool to process the number plate of vehicles on route with heavy traffic.

## Functionality
1. Resizing the image
2. Conversion of the image from RGB color to grayscale.
3. Noise removal with iterative bilateral filter (removes noise while preserving edges).
4. Find Edges of the grayscale image.
5. Find contours based on Edges.
6. sort contours based on their area keeping the minimum required area as '30' (anything smaller than this will not be considered).
7. loop over our contours to find the best possible approximate contour of number plate.
8. Crop those contours and store it as cropped image.

## Get Started
* Open the python file in a text editor.
* In terminal go the project folder and run the following commands.
   -$ pip install numpy
   -$ pip install opencv-python
   -$ pip install imutils
   -Go to https://github.com/UB-Mannheim/tesseract/wiki and download the latest version installer
   -$ pip install pytesseract

## Screenshots
![Orignal Image](Screenshot (195).png)
![Canny Image](Screenshot (196).png)
![Final Image](Screenshot (197).png)

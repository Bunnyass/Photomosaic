# PHOTO-MOSAIC USING PYTHON
## Tools used: 
Python 3.8.3, Pillow library, Tkinter, Visual Studio Code (1.46.0)
## Prerequisites: 
1. pip install Pillow
2. pip install multiprocess
## About: 
This project has been made to generate a photo-mosaic.  A photomosaic is an image split into a grid of rectangles, with each replaced by another image that matches the target (the image you ultimately want to appear in the photomosaic). The matching is done by comparing each pixel in the rectangle to the corresponding pixel from each library image. The rectangle in the target is then replaced with the library image that minimizes the total difference. This requires much more computation than the simple kind, but the results can be much better since the pixel-by-pixel matching can preserve the resolution of the target image. Concepts of OOP has been used in this project regressively with the usage of modular programming and using classes and functions. Tkinter has been used here to provide a GUI experience to fetch the source image and the directory containing the library of images and various other calculations and multiprocess functionality has been used to process the images to create the desired image object. 

## Screenshots
![alt text](https://github.com/jayantknaik/PhotoMosaic/blob/master/mosaic.jpeg?raw=true)
![alt text](https://github.com/jayantknaik/PhotoMosaic/blob/master/Media/source.jpg?raw=true)
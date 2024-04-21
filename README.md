
# PHOTO MOSAIC

A photomosaic is an image split into a grid of rectangles, with each replaced by another image that matches the target (the image you ultimately want to appear in the photomosaic). 
The matching is done by comparing each pixel in the rectangle to the corresponding pixel from each library image. The rectangle in the target is then replaced with the library image that minimizes the total difference.


## Features

- **Parallelization:** Used **"multiprocess"** library to utilize each core of the CPU to fit tile images to generate the final mosaic. 
- **Image Resizing:** Used **"pillow"** library to resize our tile images to the same size as the main image tiles, improving efficiency.
- **GUI:** Used **"tkinter"** library to provide a basic yet user-friendly UI for the user to complete the operation.


## Installation

Install photo-mosaic with pip

```bash
    pip install pillow multiprocess
```
    
## Sample Output

![alt text](https://github.com/jayantknaik/PhotoMosaic/blob/master/mosaic.jpeg?raw=true)

## Sample Input

![alt text](https://github.com/jayantknaik/PhotoMosaic/blob/master/Media/source.jpg?raw=true)
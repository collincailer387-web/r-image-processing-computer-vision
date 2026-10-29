# R Image Processing and Computer Vision

Image processing projects in R using the `magick` package: face detection, face measurement and grayscale conversion.

## What it does
- **Face detection:** finds faces in a photo and draws a box and a confidence percentage around each one.
- **Tallest and shortest face:** measures the height of each detected face and highlights the tallest (green) and shortest (blue).
- **Grayscale conversion:** converts a colour image of an apple to grayscale.
- **Image information:** reads each image's format, width, height and colour space.

## Tools
- R and R Markdown
- `magick` for reading, converting and inspecting images
- `image.libfacedetection` for face detection

## How to run
1. Download this repository.
2. Open `Image-processing.Rmd` in RStudio.
3. Install the packages: `install.packages(c("magick", "image.libfacedetection"))`
4. Click **Knit**.

## Results
Before and after images go here, for example:



![Grayscale apple](images/apple-grayscale.jpg)



## About
Built as part of my Data Science and Informatics studies at Midlands State University.

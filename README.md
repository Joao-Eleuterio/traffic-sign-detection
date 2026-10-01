# Traffic Sign Detection with OpenCV

Computer-vision project for detecting and classifying road signs in road images using classical image-processing techniques and OpenCV.

## Overview

The application processes road-scene images, identifies traffic signs, classifies them into relevant categories such as **danger** and **prohibition**, and highlights detected signs with bounding boxes.

The project also includes several image-processing utilities used to inspect and transform the input images.

## Features

- Traffic-sign detection in road images
- Classification of detected signs
- Bounding-box visualization
- Color-based image processing
- Grayscale conversion
- Red-channel emphasis
- Zoom and image inspection tools
- Batch evaluation of multiple images

## Tech

- C#
- OpenCV
- Computer Vision
- Image Processing

## Project structure

The repository includes:

- the OpenCV-based application
- test images
- the original project specification
- the technical report

## Running the project

The application uses a CSV file to locate the image dataset.

1. Open:
   `projetoComputacao/CG_OpenCV_Base/SS_OpenCV/bin/Debug/SS_files.csv`
2. Set the first column to the full path of the `images` directory.
3. Run the application.
4. Open **Eval → Process**.
5. Use **Run Selected** for a single image or **Run All** for the full set.

## Background

Originally developed as a Computer Graphics project, this repository demonstrates practical work with classical computer vision and image-processing pipelines.

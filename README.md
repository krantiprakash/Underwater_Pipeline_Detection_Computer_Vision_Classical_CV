**Underwater Pipeline Detection Computer Vision Classical CV**

**Overview**

This repository contains a robust and efficient classical computer vision pipeline for detecting underwater pipelines and similar infrastructure. The system is designed for robotic exploration and maintenance tasks, enabling autonomous underwater vehicles (AUVs) to identify and track submerged pipelines, cables, and power lines.
Unlike deep learning-based approaches, this system relies entirely on classical computer vision techniques. It eliminates the need for extensive labeled datasets and high computational resources while still achieving excellent detection accuracy.

**Pipeline Architecture**

The algorithm consists of several stages:

1. Pre-processing

   --Grayscale Conversion

-White Balancing

-Contrast-Limited Adaptive Histogram Equalization (CLAHE)


2. Edge Enhancement and Noise Reduction

-Gaussian Filtering

-Adaptive Thresholding for Edge Detection


3. Feature Extraction

-Contour Detection and Filtering

-Region of Interest (ROI) Processing


4. Line Detection

-Probabilistic Hough Transform

## **Performance Metrics**

Our system achieves the following performance metrics:

| Algorithm Version | Images Processed | Successful Detections | Success Rate |
|-------------------|------------------|------------------------|--------------|
| Original Pipeline | 16               | 9                      | 56.25%       |
| Improved Pipeline | 18               | 15                     | 83.33%       |

# Old Project Folder Structure

This project folder contains two main folders and an image set folder.

### Folders:

1. **New Pipeline Folder**
   - Contains the newly developed pipeline.
   - Code is in the `FINAL_PIPELINE.ipynb` Python Notebook file.

2. **Research**
   - Contains the implementation of the research paper pipeline.
   - Code is in the `Research_paper_implementation.ipynb` Python Notebook file.

3. **Images_set**
   - Contains all the images we have tested or tried during the execution.
  

### Running the Notebooks:

- **I used Google Colab to run the notebook files.**

  **To run on Google Colab:**
  1. Download the notebook file.
  2. Upload and run directly on Google Colab.

  **To run locally (VS Code or Jupyter Notebook):**
  1. Download the notebook file and the image set.
  2. Specify the path to the image set folder in the notebook.

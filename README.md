# Face and Anchor Points Dataset

## Description
This repository contains a dataset of 3,741 facial images and corresponding anchor points (keypoints), generated using [FaceTorch](https://github.com/facetorch). The dataset is a subset of the well-known [Faces in the Wild](http://vis-www.cs.umass.edu/lfw/) dataset, structured for use in tasks such as facial recognition, and machine learning applications involving facial feature detection. All faces are rotated such that they have the same pose. 


![Sample Image](Dataset/Bill_Gates/Bill_Gates15.jpg) <img src="https://i.imgur.com/C5iqogf.png" alt="Sample Image" width="250" height="250"/>

## Dataset Structure
- **Images**: 3,741 images from the Faces in the Wild dataset.
- **Anchor Points (Keypoints)**: Each image is annotated with 68 keypoints representing facial features.
- **CSV Format**: The anchor points are stored in a CSV file, with 204 columns representing the X, Y, Z coordinates for each of the 68 keypoints.

### CSV File Structure:
- Each row corresponds to an image.
- **Columns**:
  - 68 keypoints
  - For each keypoint: X, Y, Z coordinates (204 columns in total, all X values, then Y values, then Z values).

## Usage
This dataset can be used for:
- Training machine learning models for facial recognition.
- Detecting facial landmarks.
  
## Tools
The dataset was generated using the [FaceTorch](https://github.com/facetorch) library.


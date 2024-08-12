Mask R-CNN for Object Detection and Segmentation

This project demonstrates the use of Mask R-CNN for object detection and segmentation. It utilizes a pre-existing repository that has been adapted for TensorFlow 2.x.
Project Overview

Mask R-CNN is a state-of-the-art deep learning model that extends Faster R-CNN by adding a branch for predicting segmentation masks on each Region of Interest (RoI), in parallel with the existing branch for classification and bounding box regression.

This project sets up the Mask R-CNN model, installs necessary dependencies, and runs the model on sample data. The goal is to detect objects within an image and generate segmentation masks for each detected object.
Files and Directories

    cls_lab_4_cnn_mask_rcnn_(_day_4_).py: The main script that includes code for cloning the Mask R-CNN repository, installing dependencies, and running the model.

    Mask R-CNN repository: Cloned and used within the script for the model implementation.

Setup and Installation

    Clone the Repository: The script automatically clones the required repository. You can manually clone it if needed.
  git clone https://github.com/alsombra/Mask_RCNN-TF2
  cd Mask_RCNN-TF2

Install Dependencies: Install the required Python packages.
  pip install -r requirements.txt
  python setup.py install

Install Specific Numpy Version: The project requires a specific version of numpy (1.23.1) for compatibility.
    pip install numpy==1.23.1

Usage

To run the project, simply execute the provided Python script. Ensure that you have all dependencies installed and the repository cloned. The script handles the setup and runs the Mask R-CNN model on the sample data.
Notes

    Colab Specific Commands: The original notebook was intended for use in Google Colab, which is reflected in commands like !pip install and %cd. These should be adapted if running locally.

    Model Output: The script will generate segmented masks for objects detected in the input images. These masks are saved or displayed as per the script's instructions.

References

    Mask R-CNN Paper
    Mask R-CNN TensorFlow 2.x Implementation

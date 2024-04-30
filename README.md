# Image classification for xView-Recognition Challenge
## Folder Contents Description:

This repository contains a comprehensive exploration of various neural network architectures for a project focused on image classification. The main folder encompasses subfolders representing different architectures experimented with during the project's development. Additionally, there's a report file summarizing the findings and outcomes.

### 1. Architecture Subfolders:
- FFNN: This subfolder holds experiments conducted using Feedforward Neural Networks (FFNNs). These models are designed with fully connected layers and were one of the initial approaches explored.
- CNN: Here, Convolutional Neural Networks (CNNs) are investigated. CNNs are specialized for image-related tasks, leveraging convolutional layers to automatically learn features from input images.
- Transfer Learning: This subfolder contains experiments utilizing transfer learning, a technique where a pre-trained model is adapted to a new task. This approach often leads to faster convergence and better performance, especially with limited data.
### 2. Report File:
Report.pdf: This document serves as a comprehensive report detailing the methodologies, experiments, results, and conclusions drawn from the project. It encapsulates the insights gained from the exploration of various architectures and hyperparameters.

## Experimentation Approach:
Throughout the project, different architectures were applied to the dataset, and their performance was evaluated in light of advancements in class understanding. Each architecture's experimentation involved iteratively adjusting hyperparameters based on insights gleaned from previous experiments and new knowledge acquired from the professor's teachings.

## Hyperparameter Tuning:
Hyperparameters, crucial settings governing the behavior and performance of neural networks, were carefully selected after iterative experimentation. These parameters were fine-tuned to achieve optimal performance for each architecture, ensuring robustness and effectiveness in handling the dataset.

## Dataset
The dataset utilized in this study originates from the xView Recognition Challenge, a renowned competition in the field of computer vision aimed at advancing the state-of-the-art in satellite image analysis. The xView dataset is a large publicly available object detection dataset containing approximately 1 million manually annotated objects across 60 categories captured by the WorldView-3 satellite at 0.3m ground resolution. For this assignment, we used a subset of the dataset consisting of 846 annotated images, which were divided into 761 images for training and 85 images for testing. From these images, we extracted cropped objects based on the provided bounding box annotations, resulting in 21,377 images for training and 2,635 images for testing, with all images resized to 224x224 pixels. The task was to build models to classify these objects into 12 different categories.

### Data composition
The dataset consists of two main components: a training set and a test set, each comprising satellite images showcasing a wide array of transportation vehicles and buildings. The images are annotated with bounding boxes delineating the boundaries of objects belonging to twelve distinct categories. These categories encompass different types of transportation vehicles and buildings commonly encountered in satellite imagery, including but not limited to buildings, vehicles, and industrial structures.
The twelve categories present in the dataset are: Building, Small Car, Bus, Truck, Cargo Plane, Dump Truck, Excavator, Fishing Vessel, Helicopter, Motorboat, Shipping Container, Storage Tank.

**Usage:**

1. **Download the Repository:**
   - Download or clone the repository from [Cechup Dashboard](https://cechup.com/dashboard/Image-classification-for-xView-Recognition-Challenge).

2. **Install Required Libraries:**
   - Ensure you have Python installed on your system.
   - Install the necessary libraries by running:
     ```
     pip install -r requirements.txt
     ```

3. **Run the Python Files:**
   - Navigate to the downloaded repository folder.
   - Execute the Python files directly using Python interpreter.
     ```
     python file_name.py
     ```

4. **Explore the Results:**
   - The code will generate outputs based on the provided datasets and configurations.


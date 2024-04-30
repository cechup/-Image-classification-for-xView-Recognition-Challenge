# Image classification for xView-Recognition Challenge
## Folder Contents Description:
This repository contains a comprehensive exploration of various neural network architectures for a project focused on image classification. The main folder encompasses subfolders representing different architectures experimented with during the project's development. Additionally, there's a report file summarizing the findings and outcomes.

### 1. Architecture Subfolders:
- **FFNN**: This subfolder holds experiments conducted using Feedforward Neural Networks (FFNNs). These models are designed with fully connected layers and were one of the initial approaches explored.
- **CNN**: Here, Convolutional Neural Networks (CNNs) are investigated. CNNs are specialized for image-related tasks, leveraging convolutional layers to automatically learn features from input images.
- **Transfer Learning**: This subfolder contains experiments utilizing transfer learning, a technique where a pre-trained model is adapted to a new task. This approach often leads to faster convergence and better performance, especially with limited data.
### 2. Report File:
**Report.pdf**: This document serves as a comprehensive report detailing the methodologies, experiments, results, and conclusions drawn from the project. It encapsulates the insights gained from the exploration of various architectures and hyperparameters.
### 3. Requirements File:


## Experimentation Approach:
Throughout the project, different architectures were applied to the dataset, and their performance was evaluated in light of advancements in class understanding. Each architecture's experimentation involved iteratively adjusting hyperparameters based on insights gleaned from previous experiments and new knowledge acquired from the professor's teachings.

## Dataset
The dataset utilized in this study originates from the xView Recognition Challenge, a renowned competition in the field of computer vision aimed at advancing the state-of-the-art in satellite image analysis. Due to its size, the dataset is not contained within this repository. Instead, users are required to download it separately.
**Data usage**
1. Download the dataset zip file from [xView Recognition Challenge](http://xviewdataset.org/#dataset).
2. Upload the zip file to your Google Drive in the "MyDrive" directory.
3. Open each Python file in Google Colab.

## Requirements and usage
This project requires Python 3.10, as well as the following main packages:
- rasterio
- tensorflow
- sklearn
- Keras
- NumPy
- Matplotlib
All the libraries used in the project can be found in **requirements.txt**.

1. **Download the Repository:**
Download or clone the repository from [Cechup Dashboard](https://github.com/cechup/-Image-classification-for-xView-Recognition-Challenge). Explore the Jupyter notebooks contained within each architecture's folder. The notebooks are self-contained and include comments explaining each step of the process.

2. **Install Required Libraries:**
   - Ensure you have Python 3.10 installed on your system.
   - Install the necessary libraries by running:
     ```
     pip install -r requirements.txt
     ```

3. **Run the Python Files:**
   - Execute the Python files directly using the Python interpreter in Google Colab.

4. **Explore the Results:**
   - The code will generate outputs based on the provided datasets and configurations.
  
## Authors
Cecilia Peccolo

## License
This project is open-source and available under the terms of the [MIT License](https://opensource.org/licenses/MIT). You are free to use, modify, and distribute this software for any purpose with proper attribution to the original authors.

See the [LICENSE](LICENSE) file for the full text of the MIT License.

## Acknowledgments
The project was conducted with the collaboration of Federico Paschetta, a colleague, whose contributions were invaluable.


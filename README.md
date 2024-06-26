# PlantSpeciesNet-CNN-Based-Plant-Species-Classifier

This project aims to detect the species of a plant using a Convolutional Neural Network (CNN) in TensorFlow and Keras. The model is trained on a dataset consisting of images of four different plant species: black_nightsade, cotton, tomato, and velvet_leaf.

## Table of Contents
- [Installation](#installation)
- [Dataset](#dataset)
- [Training the Model](#training-the-model)
- [Evaluating the Model](#evaluating-the-model)
- [Prediction](#prediction)
- [Results](#results)
- [License](#license)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/plant-species-detection.git
    cd plant-species-detection
    ```

2. Mount Google Drive in Colab:
    ```python
    from google.colab import drive
    drive.mount('/content/drive')
    ```

3. Install the required libraries:
    ```bash
    pip install tensorflow
    pip install matplotlib
    ```

## Dataset

The dataset used in this project is stored in Google Drive. It contains images of four plant species categorized into the following folders:
- black_nightsade
- cotton
- tomato
- velvet_leaf

The dataset can be accessed at: `/content/drive/MyDrive/early-crop-weed-master/early-crop-weed-master`

## Training the Model

1. Load and preprocess the dataset:

2. Split the dataset into training and validation sets:
   
3. Define the CNN model:

4. Compile and train the model:
   
## Evaluating the Model

1. Plot the training and validation accuracy/loss:
   
## Prediction

1. Load a test image and make predictions:
   
## Results

- The model achieved an accuracy of `XX%` on the training set and `YY%` on the validation set after `ZZ` epochs.
- Predictions for test images are displayed along with their confidence scores.

## License

This project is licensed under the MIT License.

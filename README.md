# Multi-Class-Weather-Classification-Using-Different-CNN-Models


## Overview
This project built a Custom CNN Model using different Convolutional, Pooling, and Dense layers. Then, the Custom built CNN Model is compared to those of state-of-the-art pre-trained CNN models such as VGG16, ResNet50,  and MobileNetV2.

## Project Structure
- `Multi-Class-Weather-Classification-Using-Different-CNN-Models.ipynb`: Main project notebook containing all code and implementation
- `Research_Report.pdf`: Detailed Research Report including Introduction, Related Work, Methodology, Experimental Results, and Conclusion.
- `.gitignore`: Git ignore file
- `README.md`: Project documentation


## Main Project

### Prerequisites
Libraries used in this project:
- TensorFlow
- OpenCV (cv2)
- NumPy
- Matplotlib
- Scikit-learn
- Seaborn
- Keras (included with TensorFlow)

For exact versions, see `Requirements.txt`

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/pahul1712/Multi-Class-Weather-Classification-Using-Different-CNN-Models.git


## Dataset
The dataset is called "Multi-Class Weather Dataset" that provides a platform for outdoor weather analysis by extracting various features for recognizing different weather conditions.

This dataset contains 1125 images that are classified under 4 main classes: Cloudy, Rain, Shine, and Sunrise. The overall distribution of the images among these classes is as follows:

Sunrise - 357
Shine   - 253
Rain    - 215
Cloudy  - 300

The Dataset is collected from the website of Kaggle and you can get it from the url link given below:

https://www.kaggle.com/datasets/pratik2901/multiclass-weather-dataset


## Models used

- First, the Custom Convolutional Neural Network(CNN) Model is built from scratch using different convolutional layers, pooling layers and dense layers. 

- Then three Pre-Trained models: VGG16, ResNet50, and MobileNetV2 are trained on the same weather dataset, and are finally compared to that of the previously trained Custom CNN Model.

In total, there are 4 CNN  Models:

- Custom CNN Model
- VGG16 Model
- ResNet50 Model
- MobileNetV2 Model


## Results

All the models performed effectively on the Multi-Class Weather Dataset, and thus resulted in the validation accuracy of more than 90%. For more detailed information, you can refer to the `Research_Report.pdf`.


# Author
Pahuldeep Singh Dhingra  
[Reach out to me on my personal email: pahuldeepsingh531@gmail.com ]
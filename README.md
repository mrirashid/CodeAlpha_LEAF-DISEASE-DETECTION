![leaf_disease_detection](https://github.com/user-attachments/assets/18f79488-33aa-4541-8128-ed6e4eb842ab)

## Table of Contents
- Description
- Inspiration
- Source of Dataset
- Interesting Facts from EDA
- Technical Approach
- Original Development
- Get Started
  - Pre-installation
- Set-up
- Report
- Challenges
- Contributor




## Description
Leaf Disease Detection Using Deep Learning is a project aimed at identifying diseases in plant leaves using AI. It leverages state-of-the-art deep learning models to provide accurate, real-time predictions. The project focuses on assisting farmers, researchers, and agricultural consultants in diagnosing plant diseases efficiently.

## Inspiration
The agricultural sector suffers substantial losses each year due to undetected plant diseases. Early detection can save crops, reduce economic losses, and promote sustainable farming. This project is inspired by the potential of AI to revolutionize precision agriculture.

## Source of Dataset
The dataset used for training and testing this model consists of categorized plant leaf images collected from kaggle.
[Dataset Link](https://www.kaggle.com/datasets/emmarex/plantdisease)

## Interesting Facts from Exploratory Data Analysis
The dataset contains 15 categories of leaf diseases with a balanced distribution.
Common image augmentations (rotations, flips, zooms) were applied to increase dataset diversity.
Certain categories, such as [Category A], exhibited unique features that were highly differentiable from others.

## Technical Approach
- Data Preprocessing: Images resized to 224x224 pixels and normalized.
- EDA: Visualized class distributions and image samples.
- Deep Learning Models:
  - ResNet50: For robust feature extraction.
  - CNN: Custom-designed for simplicity and accuracy.
  - EfficientNetV2: For state-of-the-art performance.
- Training: Models were trained using 80% of the dataset, with 20% reserved for validation.
- Deployment: Deployed using Streamlit for a user-friendly interface.

## Original Development
This project was developed using Python, TensorFlow/Keras, Matplotlib, and Streamlit. The implementation includes:

Model training and evaluation on Kaggle.
Deployment and testing on a local environment.

# Get Started
## Pre-installation
Ensure the following tools and libraries are installed:
- Python 3.10+
- TensorFlow
- Streamlit
- Matplotlib
- NumPy
- Scikit-learn

Install dependencies using:
```
pip install -r requirements.txt
```
- Set-up
Clone this repository:
```
git clone https://github.com/mrirashid/leaf-disease-detection.git
cd leaf-disease-detection
```
Download the dataset and place it in the dataset directory.
Run the Streamlit app:
```
streamlit run leaf.py
```
## Report
[The Report about the Leaf Disease Detection Using Deep learning.pdf](https://github.com/user-attachments/files/17867181/The.Report.about.the.Leaf.Disease.Detection.Using.Deep.learning.pdf)

## Challenges
Dataset Preparation: Ensuring class balance and sufficient augmentation for minority categories.
Model Optimization: Fine-tuning hyperparameters to achieve the best performance.
Deployment: Streamlining the local environment for real-time predictions.
## Contributing
- Feel free to open issues or submit pull requests if you find any bugs or have suggestions for improvements.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Author
Developed by [MD Rashidul Islam](https://github.com/mrirashid/)

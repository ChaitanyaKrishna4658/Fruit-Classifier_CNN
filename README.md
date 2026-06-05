# Fruit Image Classification using CNN
 
A deep learning project that identifies fruit types from images using a Convolutional Neural Network (CNN).
 
---
 
## What this project does
- Takes a fruit image as input
- Predicts the fruit name as output
- Trained on 19 fruit categories with 90,000+ images
---
 
## Technologies Used
- Python
- TensorFlow & Keras
- Google Colab
- Matplotlib
- Kaggle Dataset
---
 
## Dataset
- Name: Fruits 360
- Source: https://www.kaggle.com/datasets/moltean/fruits
- Images: 90,000+
- Classes: 131 (we used 19)
---
 
## Model Architecture
- 3 Convolutional layers (32, 64, 128 filters)
- MaxPooling after each layer
- Flatten layer
- Dense layer (256 neurons)
- Dropout (0.5)
- Output layer (19 classes)
---
 
## Results
| Metric         | Value  |
|----------------|--------|
| Train Accuracy | ~98%   |
| Test Accuracy  | ~97%   |
| Total Classes  | 19     |
| Epochs         | 10     |
 
---
 
## How to Run
1. Open Google Colab
2. Upload this notebook
3. Run all cells one by one
---
 
## Author
- Name: G V Chaitanya Krishna

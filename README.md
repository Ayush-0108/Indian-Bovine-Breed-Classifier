# Indian-Bovine-Breed-Classifier
This project uses Deep Learning to identify various breeds of Indian cattle from images. It features a Convolutional Neural Network (CNN) built with TensorFlow/Keras and provides an interactive web interface using Gradio.

Project Overview
The model is trained on the 'Indian Bovine Breeds' dataset, which includes 41 distinct classes of cattle. The goal is to provide an accessible tool for farmers and researchers to identify breeds accurately.

Technical Stack
Framework: TensorFlow / Keras
Architecture: Convolutional Neural Network (CNN)
Optimization: Adam optimizer with Sparse Categorical Crossentropy loss
Regularization: Batch Normalization and Dropout to reduce overfitting
Interface: Gradio for real-time web-based predictions
How It Works
Data Preprocessing: Images are resized to 256x256 pixels and normalized to a [0, 1] range.
Model Training: The CNN extracts hierarchical features from the images to distinguish between breed characteristics.
Inference: Users upload an image through the Gradio interface, and the model outputs the most likely breed along with confidence scores.
Usage
To run the interactive demo locally, ensure you have the required dependencies installed and run the application script:

pip install tensorflow gradio pillow numpy
python app.py
Dataset
The dataset used for this project is sourced from Kaggle: Indian Bovine Breeds Dataset.

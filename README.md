# pneumonia_detection
X-Ray Pneumonia Detection with Severity Classification
This project uses a deep learning model to classify chest X-ray images into severity levels of pneumonia (Normal, Mild, Moderate, Severe) and provides medication recommendations based on the diagnosis. The project also includes a web-based interface for uploading X-ray images and viewing predictions.

Features
Severity Classification: Classifies X-ray images into four categories:
Normal
Mild Pneumonia
Moderate Pneumonia
Severe Pneumonia
Age-Based Medication Recommendations: Provides medications tailored for adults, children, and pregnant women based on the severity.
Web Integration: A user-friendly interface for uploading images and viewing results.
Deep Learning Model: Built using the VGG16 architecture pre-trained on ImageNet for transfer learning.
Technologies Used
Python: Core programming language for model development.
TensorFlow/Keras: Deep learning framework for building the classification model.
Flask: Lightweight web framework for hosting the application.
HTML/CSS: For creating the front-end interface.
Bootstrap: To ensure responsive design for the web page.
NumPy: For numerical computations.
Matplotlib: For visualizations (optional).
How It Works
Model Training:

Uses a pre-trained VGG16 model with additional layers for classification.
Trained on the Chest X-ray dataset.
The model predicts the probability of each severity level.
Web Interface:

Allows users to upload an X-ray image.
Processes the image using the trained model.
Displays the severity classification and medication recommendations.
Medication Suggestions:

Provides age-appropriate and severity-specific medication information.
Includes considerations for children and pregnant women.

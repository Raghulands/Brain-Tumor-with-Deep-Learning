Brain Tumor Prediction using Deep Learning

This project is a deep learning–based web application designed to classify brain tumors from MRI images. 
The system uses an EfficientNet-based Convolutional Neural Network (CNN) to identify four classes: glioma, meningioma, pituitary tumor, and no tumor. 
The trained model is deployed using a Flask web framework for real-time prediction.


Overview

Brain tumor detection is a critical task in medical imaging, where accuracy and speed are essential. 
Manual analysis of MRI scans can be time-consuming and subject to human error. 
This project aims to assist the diagnostic process by providing an automated, AI-powered solution that delivers fast and reliable predictions through a simple web interface.


Features

EfficientNetB0 with transfer learning
Real-time prediction using Flask
High accuracy (~95%) on test data


Tech Stack

Programming Language: Python
Deep Learning: TensorFlow, Keras
Model Architecture: EfficientNetB0
Web Framework: Flask
Frontend: HTML, CSS
Libraries: NumPy, OpenCV, Pillow, Matplotlib, scikit-learn


Dataset

The dataset is not included in this repository due to size and licensing constraints.
You can use publicly available MRI brain tumor datasets from academic sources or platforms like Kaggle.


Results

Achieved approximately 95% accuracy
Fast inference suitable for real-time applications
Strong performance across all four classes


Future Enhancements

Grad-CAM visualizations for explainable AI
Confidence scores for predictions
Cloud deployment for remote access
Mobile application integration

Disclaimer

This project is intended for educational and research purposes only and should not be used as a replacement for professional medical diagnosis.

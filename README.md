Brain Tumor Detection App

This project is a Deep Learning-based web application that detects brain tumors from MRI images using CNN and a Fusion Model. It also provides explainable AI results using GradCAM.

Features
Upload MRI brain images
Predict: Tumor / No Tumor
Fusion model (Image + Patient data like age, gender, symptoms)
CNN-based deep learning classification
GradCAM heatmap visualization for explainability
Streamlit interactive web interface
Tech Stack
Python
TensorFlow / Keras
Streamlit
OpenCV
NumPy
Pandas
GradCAM (Explainable AI)
Model Architecture
This project uses two models:
CNN model → processes MRI images
Fusion model → combines image features + tabular patient data
Flow:
MRI Image + Patient Data → CNN + Fusion Model → Prediction → GradCAM Visualization
How to Run
pip install -r requirements.txt
streamlit run brain_tumor_gradcam_dual_app_v2.py
Output
The system provides:
Classification result (Tumor / No Tumor)
Confidence score
Heatmap visualization (GradCAM) showing affected brain regions
Goal of the Project

To demonstrate how deep learning can be used in medical image analysis and how explainable AI (GradCAM) improves trust in predictions.

Author

Nowmya Pinni

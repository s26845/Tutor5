# Tutor5
# Machine Learning Breast Cancer Diagnostic System Architecture

This repository contains the system architecture diagram for a Machine Learning-based Breast Cancer Diagnostic System. The architecture covers all key components, data flows, and interactions in the solution. The goal of this system is to provide a tool for medical professionals to upload breast cancer scans, run AI-driven analysis, and get diagnostic results.

## System Overview

The system is composed of four major components:

1. **Frontend**: The user interface for medical professionals to interact with the system.
2. **Backend**: Handles authentication, data validation, and serves as the intermediary between the frontend and the machine learning pipeline.
3. **Machine Learning Pipeline**: Performs data preprocessing, model training, and inference.
4. **Database/Cloud Storage**: Stores scans, model parameters, and other relevant data.

## Architecture Overview

The architecture is broken down into the following modules:

### Frontend:
- **User Login**: Medical professionals log into the system to access its functionalities.
- **Upload Scans**: Upload scan data (e.g., MRI or mammogram scans).
- **Show Results**: Display the results of the AI-driven diagnosis after processing the scan.

### Backend:
- **Login/Password Verification**: Verifies user credentials for secure access.
- **Validation**: Ensures that the uploaded scans meet the required format and quality standards.

### Machine Learning Pipeline:
- **Preprocessing**: Cleans and prepares the uploaded scan data (e.g., resizing, scaling, and data augmentation).
- **Model Training**: Uses historical data to train the machine learning model to recognize signs of breast cancer.
- **Inference Model**: Applies the trained model to make predictions on new scan data.
- **Data Storage**: Stores the processed data and results in the database or cloud.

### Database/Cloud:
- **Store Data**: Stores uploaded scans and other data related to the diagnostic process.
- **Store Trained Parameters**: Stores the trained model parameters after training.
  
## Diagram

The diagram visually represents the architecture and data flow between components. It illustrates how the frontend, backend, ML pipeline, and database interact.

## Usage

To use the system:
1. **Login** with valid credentials.
2. **Upload scans** of the breast tissue for analysis.
3. The system will preprocess the data, run it through the trained model, and display the **diagnostic results**.

## Technologies Used

- **Frontend**: React or similar JavaScript framework.
- **Backend**: Python (Flask or Django), Node.js.
- **Machine Learning Pipeline**: Python (TensorFlow, Keras, PyTorch).
- **Database/Cloud**: PostgreSQL and cloud services like GCP.




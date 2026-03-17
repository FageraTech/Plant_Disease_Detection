#Plant Disease Detection App

Project Overview

This project is a web application that detects plant diseases from leaf images using a deep learning model.
The application allows users to upload a plant leaf image and receive a prediction of the disease affecting the plant.

The system is built using Python, a trained deep learning model, and an interactive web interface created with Streamlit.

Features

Upload plant leaf images

Automatic disease prediction

Simple and interactive web interface

Fast model inference

Supports multiple plant disease classes

Technologies Used

Python

TensorFlow / Keras

Streamlit

NumPy

Pillow (image processing)

Project Structure
Plant_Disease/
│
├── main.py              # Streamlit application
├── utils.py             # Helper functions
├── my_model.keras       # Trained deep learning model
├── requirements.txt     # Project dependencies
├── README.md            # Project documentation
└── dataset/             # Training dataset (optional)
Installation

Clone the repository:

cd Plant_Disease

Install dependencies:

pip install -r requirements.txt

Running the Application

Start the Streamlit app:

streamlit run main.py

The application will open in your browser at:


How It Works

The user uploads a plant leaf image.

The image is preprocessed.

The trained deep learning model predicts the disease class.

The predicted disease name is displayed on the interface.

.

Future Improvements

Add more plant species

Deploy the application online

Add disease treatment recommendations

Author

Developed by:
Jairus Rabala


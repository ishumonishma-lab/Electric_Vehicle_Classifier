Electric Vehicle Classifier
A deep learning based image classification system that identifies different types of Electric Vehicles and deploys the trained model through a Flask web application for real time predictions.
Project Overview
This project was developed as part of the Build – Train – Deploy hands on Machine Learning workshop conducted by the Department of Artificial Intelligence and Data Science at PSNA College of Engineering and Technology.
The system performs:
Image preprocessing
Deep learning model training
Model evaluation
Flask based web deployment
Real time EV prediction from uploaded images
Tech Stack
Python
TensorFlow / Keras
OpenCV
Flask
NumPy
HTML/CSS
Model Workflow
Load and preprocess EV image dataset
Train a CNN based classification model
Save the trained model (.h5 or .pkl)
Build a Flask web app for user input
Upload an image and get EV type prediction
Project Structure
EV_Vehicle_Classifier/
│── static/
│── templates/
│── model/
│── app.py
│── train.py
│── requirements.txt
│── README.md
How to Run the Project
Clone the repository
git clone https://github.com/your-username/ev-vehicle-classifier.git�
cd ev-vehicle-classifier
Install dependencies
pip install -r requirements.txt
Run the Flask app
python app.py
Open in browser
http://127.0.0.1:5000�
Upload an image to get the EV prediction.
Features
Deep learning based image classification
Real time prediction through web interface
End to end ML pipeline (Build → Train → Deploy)
User friendly interface
Learning Outcomes
Image data preprocessing
CNN model training and evaluation
Flask integration with ML model
Deployment workflow understanding
Acknowledgment
Thanks to Mr. Naveen Raj K S for the guidance and hands on training during the Build – Train – Deploy workshop.

##AI-Driven Crop Disease Prediction and Management System


##Problem Statement

Crop diseases can devastate yields, causing significant financial losses to farmers. Detecting these diseases early and intervening in time is essential for effective disease management. Current practices rely heavily on manual inspection, which is time-consuming, inefficient, and can miss early-stage diseases.

##Objective

To develop an AI-driven system that uses crop images and environmental data to predict potential disease outbreaks and provide actionable insights. This system will help farmers identify and treat diseases early, improving yield and reducing losses.

##Solution Description

The project focuses on building a mobile and web-based application that uses machine learning algorithms to identify crop diseases and offer treatment recommendations based on real-time data.

##Key Features:

AI Image Analysis: Uses computer vision models to analyze crop images uploaded by farmers and detect signs of diseases.

Environmental Data Integration: Considers environmental factors like temperature, humidity, and soil moisture to provide a more accurate disease prediction.

Real-Time Alerts: Sends notifications to farmers about potential disease outbreaks in their fields.

Actionable Insights: Provides detailed treatment plans and preventive measures tailored to specific crop diseases.

User-Friendly Interface: Both mobile and web applications designed for ease of use by farmers with varying tech skills.

##Technologies Used:

Frontend: React Native for mobile, ReactJS for web

Backend: Node.js, Express

Machine Learning: Python (TensorFlow/PyTorch) for training and deploying disease detection models

Database: MongoDB for storing crop data, images, and environmental data

Cloud Services: AWS for hosting the models and managing environmental data

Expected Outcome

Increased Crop Yield: By detecting diseases early, farmers can take preventive measures and increase productivity.
Cost Reduction: Early detection and timely intervention reduce the cost of disease treatment.
Scalability: The system is scalable for use across different regions and crops, making it widely applicable.

##Installation

##Prerequisites:

Node.js and npm installed

Python 3.x with necessary machine learning libraries

##Steps:

Clone the repository:

git clone https://github.com/63Vaishnavi2006/CROP-DISEASE-ANALYSIS

Install frontend dependencies:

cd frontend

npm install

Set up the Python environment in backend :

cd backend 

python -m venv venv

source venv/bin/activate    # For Windows: venv\Scripts\activate

pip install -r requirements.txt

Run the application:

##Backend:

cd backend

python run.py

##Frontend (Web):

cd frontend

npm run dev

##Usage

Sign up/Login to the application.

Upload Crop Images or input environmental data.

Get real-time predictions of possible diseases.

Receive Treatment Recommendations based on the detected disease.

##Contributing

Fork the repository.

Create a new branch (git checkout -b feature-branch).

Commit your changes (git commit -m "Add new feature").

Push to the branch (git push origin feature-branch).

Open a pull request.




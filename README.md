🌱 Smart Plant Watering Prediction System
Integrating Agricultural Knowledge with Automation
📖 Overview

This project leverages Machine Learning and Automation to predict whether plants require watering based on environmental and soil parameters. By analyzing sensor data and applying predictive models, the system helps optimize water usage, prevent overwatering or underwatering, and support sustainable farming practices.

The model is trained using real-world agricultural datasets to enhance decision-making for smart irrigation systems.

🚜 Objective

To automate the plant watering process using a predictive system that determines the need for irrigation based on environmental and soil features — bridging agricultural expertise with data-driven automation.

💡 Key Features

🌾 Predicts whether a plant needs watering using ML algorithms

📊 Performs data preprocessing (handling missing values, scaling, encoding)

🧠 Implements a K-Nearest Neighbors (KNN) classifier for prediction

📈 Includes detailed exploratory data analysis (EDA) and visualizations

🔍 Scalable model ready for IoT integration with smart sensors

🧩 Dataset

Dataset Source: Kaggle - Dataset for Predicting Watering the Plants

The dataset includes features such as:

Temperature

Humidity

Soil Moisture

Light Intensity

Rainfall

Wind Speed

and other environmental metrics

The target variable “Status” indicates whether watering is needed (1) or not (0).

⚙️ Technologies Used

Programming Language: Python

Libraries:

pandas, numpy – Data Handling

scikit-learn – Machine Learning Models & Preprocessing

matplotlib, seaborn – Data Visualization

statsmodels – Statistical Analysis

🧠 Model Development Workflow

Data Loading & Exploration:
Load the dataset, analyze feature relationships, and visualize correlations.

Preprocessing:

Handle missing data using IterativeImputer

Scale data using MinMaxScaler

Encode categorical variables using LabelBinarizer

Model Training:
Train a K-Nearest Neighbors (KNN) classifier with optimized parameters.

Evaluation:

Compute Accuracy, Confusion Matrix, and Classification Report

Visualize model performance

Prediction Example:
Test real-time data input (e.g., temperature, soil moisture, rainfall, etc.) to predict the watering requirement.

📊 Model Performance
Metric	Value
Accuracy	~XX.XX% (varies with dataset)
Algorithm Used	KNN (k = 3)
🧪 Example Prediction

Input sample:

input_data = (5,23,27,4,21.44,5.8,28.38,22.67,101.46,7.375482851,224.0581164,98,47,37)


Output:

Prediction: [1]  # Indicates watering is required

🚀 Future Enhancements

Integration with IoT sensors for real-time data collection

Deployment on microcontrollers (e.g., Raspberry Pi, Arduino) for automated watering

Use of deep learning for improved accuracy

Development of a mobile/web dashboard for farmers

🧑‍💻 Author

AjithKumar P
B.Sc. Botany
Pachaiyappa’s College

🏷️ Keywords

Agriculture • Automation • IoT • Machine Learning • KNN • Smart Irrigation • Data Science

# Medicine-Prediction-System

This is an AI-powered web application that predicts diseases based on user symptoms and provides comprehensive health recommendations. The system leverages machine learning algorithms to analyze symptom patterns and deliver accurate disease predictions along with personalized healthcare guidance.

### About the project
The System is designed to make preliminary medical diagnosis more accessible to everyone. Users can input their symptoms through a simple web interface, and the system uses a trained Support Vector Classifier (SVC) model to predict potential diseases. Once a disease is identified, the application provides detailed information including disease descriptions, precautionary measures, recommended medications, dietary suggestions, and appropriate workout routines.

### How it works
The application works through a multi-step process that begins when users enter their symptoms as comma-separated text values. These symptoms are then converted into a binary vector format, where each of the 132 recognized symptoms is represented numerically. The pre-trained machine learning model analyzes this symptom pattern and predicts the most likely disease from a database of 41 different conditions. After prediction, the system retrieves comprehensive health information from curated datasets and presents the results through an interactive, user-friendly interface with modal-based displays for each information category.

### Machine Learning & AI Technologies
This system is built on a Support Vector Classifier (SVC), a supervised machine learning algorithm that excels at classification tasks. The model was trained on medical datasets containing symptom-disease relationships and saved using Pickle for efficient loading during runtime. NumPy is used for creating and manipulating numerical arrays that represent symptom vectors, while Pandas handles data processing and loads information from CSV files containing disease details, precautions, medications, diets, and workout recommendations.

### Technical Stack
Flask, HTML, CSS, Bootstrap, JavaScript.

### Key Features
This system recognizes 132 different symptoms and can classify 41 distinct diseases with high accuracy. It provides comprehensive health guidance including disease descriptions, preventive precautions, medication recommendations, dietary advice, and exercise suggestions. The user interface is intuitive and responsive, featuring modal-based result displays that organize information clearly. This application provides important disclaimer reminding users that the system offers preliminary information only and should not replace professional medical consultation.

### Model Training
The machine learning model was trained using historical medical data that correlates symptoms with diagnosed diseases. The training process involved data preprocessing, feature engineering to convert symptoms into numerical representations, training the SVC classifier with optimized hyperparameters, model evaluation using accuracy metrics and cross-validation, and finally serializing the trained model using Pickle for deployment.

### Dataset
This is the dataset that I used in this project called [Medicine Recommendation System Dataset](https://www.kaggle.com/datasets/noorsaeed/medicine-recommendation-system-dataset) from Kaggle.

### Project
Video of the project

[Demo](https://drive.google.com/file/d/1depti-iLD5YykqCgQOGkLrLWLVeLUK5L/view?usp=sharing)

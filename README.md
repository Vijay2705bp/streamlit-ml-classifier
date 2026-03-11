# Machine Learning Classifier Explorer (Streamlit App)

## Project Overview

This project is an interactive **Machine Learning web application** built using **Streamlit**.  
It allows users to explore different classification algorithms and datasets while visualizing model performance.

The app enables users to:

- Select a dataset
- Choose a machine learning algorithm
- Adjust model hyperparameters
- Train the model
- Evaluate accuracy
- Visualize the dataset in 2D using PCA

This project demonstrates how machine learning models can be integrated into a **web-based interactive interface**.

---

## Algorithms Implemented

The application currently supports the following classifiers from `scikit-learn`:

- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Random Forest

Users can modify hyperparameters using sidebar sliders.

---

## Datasets Available

The following datasets from `sklearn.datasets` are used:

- Iris Dataset
- Breast Cancer Dataset
- Wine Dataset

These datasets are commonly used for classification demonstrations.

---

## Features

- Interactive UI built with **Streamlit**
- Dataset selection from sidebar
- Model selection (KNN, SVM, Random Forest)
- Hyperparameter tuning
- Accuracy evaluation
- PCA visualization of dataset
- Clean and simple user interface

---

## Technologies Used

- Python
- Streamlit
- Scikit-learn
- NumPy
- Matplotlib

---

## Project Structure

streamlit-ml-classifier
│
├── main.py
├── requirements.txt
└── README.md

---

## Installation

- Clone the repository:
https://github.com/Vijay2705bp/streamlit-ml-classifier.git

- Move into the project folder:
cd streamlit-ml-classifier

- Install dependencies:
pip install -r requirements.txt

## Run the Application
- Start the Streamlit app using:
streamlit run main.py

- The application will open in your browser at:
http://localhost:8501

## Example Workflow

- Select a dataset (Iris, Wine, or Breast Cancer)

- Choose a classifier (KNN, SVM, Random Forest)

- Adjust hyperparameters using sidebar sliders

- Train the model

- View the accuracy score

- Visualize the dataset using PCA projection

- Future Improvements

## Possible extensions for this project:

- Add more machine learning algorithms

- Upload custom datasets

- Add confusion matrix visualization

- Add precision / recall metrics

- Deploy with Docker

- Add model download option

- Deployment

## This application can be deployed easily using Streamlit Community Cloud.

## Steps:

- Push the project to GitHub

- Go to https://share.streamlit.io

- Connect your GitHub repository

- Select main.py

- Deploy the application

## 👨‍💻Author - Vijaya Kumar Kanipakam

This project is part of my portfolio, showcasing the Machine Learning(ML) skills essential for data scientist and Machine Learning roles . If you have any questions, feedback, or would like to collaborate, feel free to get in touch!

### Stay Updated and Join the Community

For more content on ML, data analysis, and other data-related topics, make sure to follow me on social media and join our community:

- **LinkedIn**: [Connect with me professionally](https://www.linkedin.com/in/vijay-kumar-2705m/)

Thank you for your support, and I look forward to connecting with you!

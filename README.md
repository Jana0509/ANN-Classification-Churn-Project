# ANN-Classification-Churn-Project

This project demonstrates the creation of an Artificial Neural Network (ANN) for solving a binary classification problem — predicting customer churn for a bank.

---

## Project Overview

The goal of this project is to build a deep learning model that can predict whether a customer will stay with the bank or exit, based on historical customer data. The model is trained on features such as geography, gender, age, balance, credit score, etc.

A Streamlit web app has been developed to interact with the trained ANN model. The app takes user inputs, applies necessary preprocessing such as scaling, and then predicts the likelihood of churn in real time.

---

## Project Workflow

1. **Feature Engineering**  
   - Converted categorical variables to numerical format  
   - Standardized numerical features for improved model performance

2. **ANN Model Creation**  
   - Built an ANN with an input layer, hidden layers, and an output layer for binary classification  

3. **Training**  
   - Calculated loss and optimized the network using backpropagation  
   - Used activation functions to introduce non-linearity  

4. **Model Export**  
   - Saved the trained model in `.h5` file format for deployment  

5. **Web Application**  
   - Developed a Streamlit app to provide an interactive user interface  
   - Integrated the app with the trained ANN model for real-time predictions

---

## Libraries Used

- **TensorFlow:** For creating and training deep learning models  
- **Keras:** High-level API for TensorFlow, simplifies ANN creation  
- **Pandas:** Data manipulation and preprocessing  
- **TensorBoard:** Visualization tool to monitor model training  
- **Streamlit:** To build an easy-to-use web application interface

---

## Learnings

- Gained an understanding of how artificial neural networks operate, including forward and backward propagation processes.  
- Learned how loss functions quantify model error and guide optimization during training.  
- Explored activation functions and their role in enabling the network to learn complex patterns.

---

## How to Run

1. Clone the repository  
   ```bash
   git clone https://github.com/yourusername/ANN-Classification-Churn-Project.git

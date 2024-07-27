# Data Science Projects Portfolio

Welcome to my data science portfolio repository! This collection features a range of data science projects, from beginner to advanced levels, demonstrating my skills and experience in machine learning (ML) and artificial intelligence (AI). Each project aims to explore different ML techniques and their applications before scaling them for larger, more complex problems. The implementations heavily leverage popular libraries such as [scikit-learn](https://www.scikit-learn.org), [TensorFlow](https://www.tensorflow.org), and [Keras](https://keras.io/).

![Project Visualization](https://github.com/Dan-Boat/Exp.AI.ML/blob/master/img/img1.jpg?raw=True)

## Project List

### 1. Stacked Ensemble Models
**Objective:** Demonstrate the use of stacking ensemble models for multi-class classification problems using Multi-Layer Perceptron (MLP) models.

**Details:**
- Utilizes sklearn datasets and models from TensorFlow.
- Implements logistic regression from `sklearn.linear_model`.
- Focuses on integrating and comparing separate stacking models.

### 2. Ensemble Regressors
**Objective:** Evaluate different ensemble methods to reduce bias and variance in regression tasks.

**Details:**
- Explores sequentially trained estimators.
- Uses `VotingRegressor` and `StackingRegressor` to combine models.
- Includes ExtraTreeRegressor, GradientBoosting, XGBoostRegressor, and others.
- Implements various regression models (Bayesian regression, GLM, SVR, MLP, LassoCV) from both sklearn and TensorFlow.

### 3. Hello World in ML
**Objective:** Train a deep learning model to recognize handwritten digits from the MNIST dataset.

**Details:**
- MNIST dataset contains 70,000 images (28x28 pixels) of handwritten digits.
- The goal is to classify digits (0-9), a 10-class classification problem.
- Demonstrates basic deep learning techniques and model training.

### 4. AudioBooks Targeted Ads
**Objective:** Predict customer repeat purchases at an audiobook shop to optimize targeted advertising.

**Details:**
- Uses client data for prediction.
- Model is saved for future use and retraining with new data.
- Helps in deploying targeted ads towards potential customers.

### 5. Absenteeism Data Analysis
**Objective:** Analyze employee absenteeism data to predict the likelihood of absence based on personal attributes.

**Details:**
- Classification problem using logistic regression.
- Targets are grouped into 0 (excessively absent) and 1 (moderately absent).
- Helps companies tailor hiring practices based on absenteeism predictions.

### 6. CNN for Cat or Dog Classification
**Objective:** Classify images of cats and dogs using Convolutional Neural Networks (CNN).

**Details:**
- Dataset includes 10,000 images for training.
- Simple CNN architecture with convolution layers, max pooling, flattening, and dense layers.
- Demonstrates basic image classification techniques.

### 7. RNN (LSTM) for Google Stock Price Prediction
**Objective:** Predict Google stock price trends using Long Short-Term Memory (LSTM) Recurrent Neural Networks (RNN).

**Details:**
- Optimized on 5 years of historical data, tested on January 2017.
- Uses 60 timesteps for each learning point.
- Focuses solely on stock price data for training.

---

## Getting Started
To get started with any of the projects, clone the repository and follow the instructions provided in each project directory. Ensure you have the necessary libraries installed, as specified in the respective README files or requirements.txt.

```bash
git clone https://github.com/Dan-Boat/Data_science_projects
cd Data_science_projects 
```

## Installation
Each project may require different dependencies. It's recommended to create a virtual environment and install the required packages using pip.

```bash
conda create --name "name of env"
pip install -r requirements.txt
```

## Contribution
Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## Contact
Feel free to reach out via email at [dannboateng@gmail.com] for any inquiries or further discussions.

---

Thank you for visiting my data science portfolio. I hope these projects demonstrate my capability and passion for data science and machine learning. Happy coding!
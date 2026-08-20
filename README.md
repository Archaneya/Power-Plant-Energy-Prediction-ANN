# ⚡ Power Plant Energy Prediction using ANN

A deep learning regression project that uses an **Artificial Neural Network (ANN)** built with **PyTorch** to predict the electrical energy output of a Combined Cycle Power Plant from environmental and operational conditions.

## 📌 Overview

Power generation in a Combined Cycle Power Plant is influenced by several environmental factors such as temperature, ambient pressure, relative humidity, and exhaust vacuum.

This project develops a neural-network-based regression model to learn the relationship between these input variables and the plant's **net electrical energy output**.

The project covers the complete machine learning workflow:

**Data Analysis → Preprocessing → Feature Scaling → ANN Development → Model Training → Evaluation → Visualization**

## 🎯 Objective

Build an Artificial Neural Network capable of predicting the **net hourly electrical energy output** of a combined-cycle power plant using measured environmental conditions.

## 📊 Dataset

The project uses the **Combined Cycle Power Plant dataset**, containing observations collected from a power plant operating under full-load conditions.

### Features

| Feature | Description         |
| ------- | ------------------- |
| `AT`    | Ambient Temperature |
| `V`     | Exhaust Vacuum      |
| `AP`    | Ambient Pressure    |
| `RH`    | Relative Humidity   |

### Target

| Variable | Description                         |
| -------- | ----------------------------------- |
| `PE`     | Net hourly electrical energy output |

## 🧠 Model

An **Artificial Neural Network (ANN)** was implemented using **PyTorch**.

The model learns a nonlinear mapping between the environmental input variables and the plant's electrical energy output.

### Workflow

1. Load and inspect the dataset
2. Perform exploratory data analysis
3. Analyze feature relationships and correlations
4. Separate features and target variable
5. Split the data into training and testing sets
6. Apply feature scaling
7. Build the ANN architecture using PyTorch
8. Train the model using an optimization algorithm
9. Evaluate predictions on unseen test data
10. Visualize model performance and prediction errors

## 🛠️ Tech Stack

* **Python**
* **PyTorch**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Scikit-learn**
* **Jupyter Notebook**

## 📈 Exploratory Data Analysis

The analysis includes:

* Feature distributions
* Correlation analysis
* Relationship between environmental variables and energy output
* Data visualization
* Identification of important patterns in the dataset

## 📏 Model Evaluation

The regression model is evaluated using appropriate regression metrics such as:

* **Mean Absolute Error (MAE)**
* **Mean Squared Error (MSE)**
* **Root Mean Squared Error (RMSE)**
* **R² Score**

These metrics are used to measure prediction accuracy and understand how well the neural network generalizes to unseen data.

## 🔍 Key Learning Outcomes

Through this project, I explored:

* Neural networks for regression problems
* PyTorch model development
* Forward propagation and loss optimization
* Feature scaling for neural networks
* Regression model evaluation
* Data visualization and exploratory analysis
* Applying deep learning to an energy-related prediction problem

## 📂 Project Structure

```text
Power-Plant-Energy-Prediction-ANN/
│
├── Power_Plant_Energy_Prediction_ANN.ipynb
├── README.md
└── dataset/
    └── ...
```

> File names may vary depending on the current repository structure.

## 🚀 Future Improvements

* Compare ANN performance with Random Forest, XGBoost, and other regression models
* Perform hyperparameter tuning
* Experiment with different ANN architectures
* Add model explainability using SHAP
* Build an interactive prediction interface
* Deploy the trained model as an API

## 👨‍💻 Author

**Aaryan Shelar**

AI/ML Engineering Student

[GitHub](https://github.com/Archaneya)

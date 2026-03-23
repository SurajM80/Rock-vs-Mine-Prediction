# Rock vs. Mine Prediction using Logistic Regression

## 📌 Project Overview
This project is a **Binary Classification** model designed to distinguish between **Rocks** and **Mines** based on sonar data. The model analyzes 60 different sonar frequencies bounced off an object to determine if it is a metal cylinder (mine) or a rock.

## 🚀 The Data
The dataset used is the **Sonar (Connectionist Bench) Dataset**. It contains:
* **60 Features:** Each feature represents the energy within a particular frequency band.
* **Target Label:** * `R` for Rock
  * `M` for Mine

## 🧠 Model Choice: Logistic Regression
For this project, **Logistic Regression** was chosen because it is an efficient and easy-to-interpret algorithm for binary classification. Since the relationship between the sonar frequencies and the object type can often be mapped linearly in a transformed feature space, Logistic Regression provides a solid baseline with high accuracy without the complexity of deep neural networks.

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** * `NumPy` (Linear algebra)
  * `Pandas` (Data manipulation)
  * `Scikit-learn` (Model training, splitting, and evaluation)

## 📋 Project Workflow
1. **Data Collection:** Loading the sonar data into a Pandas DataFrame.
2. **Data Pre-processing:** Checking for missing values and performing statistical analysis.
3. **Train-Test Split:** Dividing the data to ensure the model generalizes well to unseen data.
4. **Model Training:** Fitting the Logistic Regression model to the training data.
5. **Evaluation:** Measuring the accuracy score on both training and test data.
6. **Predictive System:** Building a function to take new input data and predict whether it's a Rock or a Mine.
1. Clone the repository:
   ```bash
   git clone [https://github.com/SurajM80/Rock-vs-Mine-Prediction.git](https://github.com/SurajM80/Rock-vs-Mine-Prediction.git)

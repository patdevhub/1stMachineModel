# 🤖 My First Machine Learning Model

### Predicting Molecular Solubility Using Supervised Machine Learning

Welcome to my first Machine Learning project! 🚀

This project documents my hands-on exploration of supervised machine learning using Python and Google Colab. The objective was to train and evaluate regression models capable of predicting molecular solubility (LogS) using numerical features from a dataset.

## 🎯 Project Objectives

- Understand the fundamentals of supervised machine learning.
- Prepare data for model training and testing.
- Build Linear Regression and Random Forest Regression models.
- Evaluate model performance using statistical metrics.
- Visualise actual versus predicted values.

## 🛠️ Technologies Used

- **Python** – Programming language
- **Google Colab** – Development environment
- **Pandas** – Data manipulation
- **NumPy** – Numerical calculations
- **Scikit-learn** – Machine learning algorithms
- **Matplotlib** – Data visualisation

## ⚙️ Machine Learning Workflow

**1. Data Preparation**

Separated the dataset into input features (X) and the target variable (LogS).

**2. Data Splitting**

Divided the dataset into 80% training data and 20% testing data.

**3. Model Development**

Implemented two supervised learning algorithms:
- Linear Regression
- Random Forest Regressor

**4. Model Evaluation**

Evaluated predictions using Mean Squared Error (MSE) and R² scores.

## 📊 Model Performance

The Linear Regression model produced the following results:

| Metric | Training | Testing |
|---|---|---|
| R² Score | 0.7645 | 0.7892 |
| Mean Squared Error | 1.0075 | 1.0207 |

The test R² score of approximately 0.789 indicates that the model explained around 78.9% of the variation in the test dataset's LogS values.

## 📈 Data Visualisation

Created a scatter plot comparing experimental and predicted solubility values, including a fitted trendline to help interpret model behaviour.

## 🧠 Key Learning Outcomes

Through this project, I gained practical experience in preparing datasets, training prediction models, evaluating performance, and understanding how supervised learning algorithms identify relationships in data.

## 🚀 Future Improvements

- Experiment with more machine learning algorithms.
- Perform hyperparameter tuning.
- Introduce cross-validation.
- Investigate feature importance.
- Explore more advanced predictive modelling techniques.

## 👨‍💻 About Me

ICT Application Development student at Sol Plaatje University, exploring Machine Learning, Cloud Computing, and High-Performance Computing.

*Learning, experimenting, and building one project at a time.*

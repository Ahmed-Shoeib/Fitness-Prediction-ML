# Fitness-Prediction-ML

## Project Overview
This project aims to predict a person's fitness status (`is_fit`) using a dataset containing health, lifestyle, and biometric data. It demonstrates a complete machine learning workflow including:

- Data loading and exploration
- Handling missing values
- Encoding categorical features
- Outlier detection and removal
- Data visualization
- Scaling numerical features
- Model training with multiple classifiers:
  - Logistic Regression
  - Random Forest
  - SVM
  - Naive Bayes
- Hyperparameter tuning using GridSearchCV
- Model evaluation using Accuracy, Confusion Matrix, Classification Report
- Cross-validation to ensure model stability
- Comparison of models and selection of the best performing one

---

## Dataset
The dataset used in this project (`fitness_dataset.csv`) includes the following features:

- `age` - Age of the person
- `gender` - Gender (M/F)
- `height_cm` - Height in cm
- `weight_kg` - Weight in kg
- `sleep_hours` - Average sleep per night
- `heart_rate` - Resting heart rate
- `blood_pressure` - Blood pressure
- `nutrition_quality` - Nutrition quality score
- `activity_index` - Activity index score
- `smokes` - Smoking status (yes/no)
- `is_fit` - Target variable (1 = Fit, 0 = Not Fit)

---

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/yourusername/Fitness-Prediction-ML.git
cd Fitness-Prediction-ML

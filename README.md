# Student Performance Prediction System


## Overview

The Student Performance Prediction System is a machine learning application that predicts student academic performance based on various factors including study habits, attendance rate, previous grades, sleep patterns, and extracurricular activities. The system uses regression models to predict a performance score (0-100) and provides personalized recommendations for improvement.

**Author:** Shivam Kashyap 
**Last Updated:** 2025-03-26 19:04:46

## Features

- **Data Generation:** Creates realistic synthetic student data with meaningful relationships between features
- **Feature Engineering:** Derives additional features to improve model performance
- **Multi-Model Training:** Compares Linear Regression, Random Forest, and Gradient Boosting models
- **Model Evaluation:** Evaluates performance using R², RMSE, and MAE metrics
- **Interactive Predictions:** Provides a user interface for real-time predictions with recommendations
- **Model Persistence:** Saves trained models for future use

## Repository Structure

```
Student-Performace-Prediction/
│
├── Data/                      # Data storage
│   ├── student_performance.csv        # Real-world data
│   └── synthetic_student_data.csv     # Synthetic training data
│
├── Models/                    # Saved models
│   ├── model_card.txt                 # Model information and metrics
│   └── student_performance_model.pkl  # Trained model with components
│
├── Plots/                     # Visualizations
│
├── LICENSE                    # License file
├── Performance_Prediction.ipynb       # Main Jupyter notebook
├── README.md                  # This file
└── requirements.txt           # Required dependencies
```



## Model Performance

The system was developed using synthetic data with the following performance metrics:

- **Best Model:** Linear Regression
- **R² Score:** 0.4246
- **Root Mean Squared Error:** 7.18
- **Mean Absolute Error:** 5.53


## Feature Importance

The most predictive factors for student performance are:
1. Previous Grades
2. Study Hours per Week
3. Attendance Rate
4. Sleep Hours per Night

## Future Improvements

Planned enhancements for future versions:
- Implement neural network models
- Add more features related to learning environment
- Create a web-based user interface
- Develop time-series analysis for performance trends
- Improve model's ability to identify at-risk students

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- This project was created as part of an educational data mining initiative
- Special thanks to contributors and testers who provided valuable feedback

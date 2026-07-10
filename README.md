# Manufacturing Quality Prediction: A Regression Analysis

This repository contains a comprehensive machine learning study focused on predicting manufacturing quality ratings.

The project explores the performance of various regression models, highlighting the importance of data preprocessing and feature engineering in achieving high predictive accuracy.

### 🚀 Key Highlights

*   **Comprehensive Comparison**: Benchmarked multiple regression algorithms including Linear, Polynomial, SVR, KNN, and Decision Tree.

*   **Feature Engineering**: Identified and removed redundant features (e.g., 'Temperature x Pressure') to mitigate multicollinearity and prevent overfitting.

*   **Optimization Strategies**: Utilized `Pipeline` and `PolynomialFeatures` to effectively capture non-linear relationships within the manufacturing dataset.

*   **Hyperparameter Tuning**: Employed `GridSearchCV` to optimize model performance, achieving R2 scores exceeding 0.99.

### 📊 Performance Summary

| Model | R2 Score |
| :--- | :--- |
| **Linear Regression** | 0.498 |
| **Polynomial Regression (Degree 5)** | **0.999** |
| **SVR (RBF Kernel)** | 0.996 |
| **K-Nearest Neighbors** | 0.985 |
| **Decision Tree Regressor** | 0.999 |

### 🛠 Tech Stack

*   **Language**: Python

*   **Libraries**: 
    *   `scikit-learn`: Model development, preprocessing, and grid search.
    *   `pandas` & `numpy`: Data manipulation and numerical analysis.

### 💡 Key Takeaways

This project illustrates that in real-world manufacturing scenarios, data is rarely strictly linear.

While simple linear models provide a baseline, advanced techniques like **Polynomial Regression** and **SVR with RBF kernels** are essential for capturing the complex dynamics of production processes.

Furthermore, implementing a robust `Pipeline` is critical for ensuring data integrity and preventing data leakage during the training process.

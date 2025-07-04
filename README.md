# Linear_Regression_Model_from_Scratch

This project demonstrates how to implement Linear Regression from scratch using NumPy and Gradient Descent, without relying on libraries like scikit-learn. The model is trained on real-world data, and its performance is compared against sklearn.LinearRegression.

By building this model manually, I've gained a solid understanding of:

        How gradient descent minimizes the loss function

        How weights and biases are updated

        How prediction accuracy evolves during training


Features Implemented: -

    Multivariate Linear Regression

    Batch Gradient Descent

    Custom implementation of fit() and predict()

    Custom evaluation metrics: MSE, MAE, R²

    Support for scaled inputs (StandardScaler)

    Performance benchmarking with sklearn


## Algorithms Used

1. Mean Squared Error (MSE) Loss:

    MSE = 1/m(Σ(y_pred - y_act)^2)


2. Gradient Descent Updates:

    w = w - α*dw

    b = b - α*db

    Where:

    α : learning rate

    w : weight vector

    b : bias (intercept)


## 🔧 How to Run

    Clone this repository
    
        $ git clone https://github.com/kailash-swami/Linear_Regression_Model_from_Scratch.git
        $ cd Linear_Regression_Model_from_Scratch

    Create a virtual environment (optional but recommended)
        $ python -m venv venv
        $ source venv/bin/activate  # or venv\Scripts\activate on Windows

    Install dependencies
        $ pip install -r requirements.txt

    Run the notebook
        $ jupyter notebook Linear_Regression_From_scratch.ipynb
 


## 🙌 Acknowledgements

    Inspired by Andrew Ng’s ML course
    

    Comparisons done using scikit-learn


## ✍️ Author

    Kailash Swami
  

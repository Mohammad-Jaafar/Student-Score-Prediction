# Student Score Prediction

This project aims to predict students' exam scores based on various academic and lifestyle factors such as study hours, sleep hours, and attendance percentage.  
It demonstrates how simple **Linear Regression** and **Polynomial Regression** models can be used to understand and forecast student performance.

---

## Overview
The goal of this project is to:
- Explore and visualize relationships between different performance factors.
- Build and evaluate regression models to predict exam scores.
- Compare the accuracy of **Linear Regression** vs **Polynomial Regression**.
- Allow users to input their own data (study hours, sleep hours, attendance) to get a predicted exam score.

---

## Features

-   Explore and visualize relationships between different performance factors.
-   Build and evaluate **Linear Regression** and **Polynomial Regression** models.
-   Compare model performance using **Mean Squared Error (MSE)** and **R² Score**.
-   Input custom values (study hours, sleep hours, attendance) to predict exam scores.
-   Visualize predicted vs actual scores and regression curves.


---

## Technologies Used

-   **Python 3.9+**
-   **NumPy**
-   **Pandas**
-   **Matplotlib / Seaborn**
-   **Scikit-learn**

---

## Project Structure
```
StudentScorePrediction/
│
├── Dataset/
│   └── StudentPerformanceFactors.csv
├── Student-Score-Prediction.ipynb
├── README.md          
└── requirements.txt              
```

---

## Installation & Usage

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/Mohammad-Jaafar/Student-Score-Prediction.git
    cd Student-Score-Prediction
    ```

2.  **Install dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

3.  **Run the notebook:**

    ```bash
    jupyter notebook Student-Score-Prediction.ipynb
    ```

    Or upload directly to [Google Colab](https://colab.research.google.com/).

4.  Input custom values for **study hours**, **sleep hours**, and **attendance percentage** to get predicted exam scores.

---


## Results

-   Scatter plots showing relationships between study hours and exam scores.
-   Polynomial regression curve fitting for better visualization.
-   Model evaluation metrics:

    | Model                  | Mean Squared Error (MSE) | R² Score |
    |------------------------|-------------------------|----------|
    | Linear Regression      | 12.34                   | 0.87     |
    | Polynomial Regression  | 8.56                    | 0.92     |

---
## Future Work

-   Use more advanced regression models such as **Random Forest** or **Gradient Boosting**.
-   Add **feature scaling** and more robust **data preprocessing**.
-   Build an interactive interface using **Gradio** or **Streamlit**.
-   Deploy the model on **HuggingFace Spaces**.

---

## Author
**Mohammad Jaafar**  
mhdjaafar24@gmail.com  
[LinkedIn](https://www.linkedin.com/in/mohammad-jaafar-)  
[HuggingFace](https://huggingface.co/Mhdjaafar)  
[GitHub](https://github.com/Mohammad-Jaafar)

---

*If you find this project useful, please give it a star on GitHub!*

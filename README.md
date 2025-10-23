# Student Score Prediction

This project aims to predict students' exam scores based on various academic and lifestyle factors such as study hours, sleep hours, and attendance percentage.  
It demonstrates how simple **Linear Regression** and **Polynomial Regression** models can be used to understand and forecast student performance.

---

## Project Overview
The goal of this project is to:
- Explore and visualize relationships between different performance factors.
- Build and evaluate regression models to predict exam scores.
- Compare the accuracy of **Linear Regression** vs **Polynomial Regression**.
- Allow users to input their own data (study hours, sleep hours, attendance) to get a predicted exam score.

---

## Machine Learning Techniques Used
- **Linear Regression** – to model the linear relationship between features and exam scores.
- **Polynomial Regression** – to capture potential non-linear relationships.
- **Model Evaluation Metrics:**
  - Mean Squared Error (MSE)
  - R² Score

---

## Dataset
- **Name:** Student Score Factors  
- **Format:** CSV (`StudentPerformanceFactors.csv`)  
- **Features:**
  - `Hours_Studied`: Number of study hours per day
  - `Sleep_Hours`: Average sleep hours per day
  - `Attendance`: Class attendance percentage
  - `Exam_Score`: Final exam score (target variable)

> The dataset should be placed inside a folder named `Dataset/` at the project root.

---

## Project Structure
```
StudentScorePrediction/
│
├── Dataset/
│   └── StudentPerformanceFactors.csv
│
├── Student-Score-Prediction.ipynb
├── README.md          
└── requirements.txt              
```

---

## Installation & Setup

### 1. Clone the repository
```bash
git clone https://github.com/Mohammad-Jaafar/Student-Score-Prediction.git
cd Student-Score-Prediction
```

### 2. Install dependencies
If you're using Google Colab, most libraries are already available.  
Otherwise, install manually:
```bash
pip install -r requirements.txt
```

### 3. Run the notebook
You can open the notebook in Jupyter or Google Colab:
```bash
jupyter notebook Student-Score-Prediction.ipynb
```

Or upload it directly to [Google Colab](https://colab.research.google.com/).

---

## Results & Visualizations
- Scatter plots showing relationships between study hours and exam scores.
- Comparison between actual and predicted exam scores.
- Polynomial regression curve fitting visualization.
- Model evaluation metrics for both Linear and Polynomial models.

---

## User Interaction
At the end of the notebook, you can **input your own values** for:
- Study hours
- Sleep hours
- Attendance percentage

The model will then output the **predicted exam score**.

---

## Future Improvements
- Use more advanced models (Random Forest, Gradient Boosting)
- Add data preprocessing and feature scaling
- Create a Gradio or Streamlit interface for interactive use
- Deploy on Hugging Face Spaces

---

## Author
**Your Name**  
mhdjaafar24@gmail.com  
[LinkedIn](https://www.linkedin.com/in/mohammad-jaafar-)  
[HuggingFace](https://github.com/mhdjaafar24)

---

*If you find this project useful, please give it a star on GitHub!*

# Capstone_Project
This project aims to analyze and predict student performance levels using various behavioral and academic factors. Through exploratory data analysis and machine learning models, we evaluate which factors influence performance and how accurately different classifiers can predict performance categories.

## 📊 Project Overview

- **Dataset**: A dataset including features such as exam scores, sleep hours, and social media usage.
- **Target**: Classify students into **Low**, **Average**, or **High** performance levels.
- **Methods**:
  - Data visualization (boxplots, confusion matrices)
  - Preprocessing and feature selection
  - Model training and evaluation using accuracy and F1-score

## 🧪 Machine Learning Models Used

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- K-Nearest Neighbors
- Gaussian Naive Bayes
- Support Vector Classifier (Linear and RBF)

## 📈 Key Results

- **Exam Scores** are strongly correlated with performance level.
- **Sleep Hours** show slight variation but no strong pattern across levels.
- **Social Media Usage** is inversely related to performance level.
- All models achieved **moderate accuracy (~35-39%)**, suggesting more complex features or data may be needed.
- F1-scores indicate classifiers are more accurate in predicting **Low** performers than **High** performers.

## 📁 Project Structure

├── CAPSTONE_PROJECT.ipynb # Jupyter notebook with full analysis
├── figures/ # Visualizations (boxplots, bar charts, confusion matrices)
├── README.md # Project overview

bash
Copy code

## 🔧 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/student-performance-capstone.git
   cd student-performance-capstone
Install required packages:

bash
Copy code
pip install -r requirements.txt
Open the notebook:

bash
Copy code
jupyter notebook CAPSTONE_PROJECT.ipynb

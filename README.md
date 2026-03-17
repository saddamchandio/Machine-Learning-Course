# Machine Learning Course 🚀

This repository contains all the coursework, assignments, algorithm implementations, and the final project completed during the **Machine Learning** module as part of the **Post Graduate Diploma (PGD) in Data Science & Artificial Intelligence (Batch 10)** at **NED University of Engineering and Technology**.

## 📖 Repository Purpose

The primary purpose of this repository is to showcase a comprehensive journey through the fundamental and advanced concepts of Machine Learning. It serves as a personal log of data science implementations, algorithm experiments, and predictive modeling projects built using Python, Scikit-Learn, Pandas, and other essential data science libraries.

It is intended both as an academic portfolio and an actionable reference for applying traditional Machine Learning algorithms effectively.

## 📂 Repository Structure

The repository is organized by algorithms, methodologies, and major academic milestones:

### 🧩 Core Algorithms & Methodologies
*   **`Linear Regression/`**: Implementations predicting continuous target variables.
*   **`Logistic Regression/`**: Implementations for binary and multiclass classification tasks.
*   **`Decision Tree/`**: Tree-based classification and regression modeling.
*   **`KNN/`**: K-Nearest Neighbors implementation and distance-based predictions.
*   **`SVM/`**: Support Vector Machines for high-dimensional classification boundaries.
*   **`Column Transformer/`**: Advanced unified feature engineering and categorical/numerical data transformation.
*   **`Pipeline Methodology in ML/`**: Building robust, sequential machine learning pipelines to streamline preprocessing and prevent data leakage.
*   **`LazyPredict/`**: Utilizing the LazyPredict library for rapid, broad-spectrum baseline model evaluation.

### 🎓 Academic Milestones
*   **`Assignment/`**: Various routine coursework and practice tasks.
*   **`Midterm/`**: Midterm examination practical coding and problem-solving solutions.
*   **`FinalExam/`**: Final examination implementations. *(Note: One extremely large dataset utilized here, `creditcard.csv`, is purposefully ignored from version control).*
*   **`FinalProject/`**: The capstone project of the course.

## 🌤️ Capstone Final Project: Karachi Weather Data Analysis and Forecasting

The absolute highlight of this repository is the Final Project, demonstrating practical, end-to-end data science capabilities through a robust time-series analysis.

*   **Objective:** To perform in-depth Exploratory Data Analysis (EDA) on key meteorological variables in Karachi, Pakistan, and accurately forecast future temperature trends.
*   **Data Engineering:** Extracted over 3 years of historical hourly weather conditions (January 2022 to September 2025) specifically tailored via the OpenMeteo API.
*   **Analysis & Findings:** Analyzed and plotted temperature, relative humidity, wind speeds, and rainfall. Discovered crucial regional climate dynamics such as statistically significant negative correlations between temperature and relative humidity.
*   **Advanced Forecasting:** Leveraged Meta's open-source **Prophet** library. The project successfully modeled complex daily, weekly, and yearly seasonality patterns, ultimately forecasting accurate temperature trends with bounds for a full 365 days into the future.

## 🛠️ Technologies & Tools Leveraged

*   **Language:** Python 3
*   **Environment:** Jupyter Notebooks (`.ipynb`)
*   **Core Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn, Plotly
*   **Specialized Libraries:** Meta Prophet, LazyPredict

## 🚀 How to Explore the Code

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/saddamchandio/Machine-Learning-Course.git
    ```
2.  **Navigate directly into the project directory:**
    ```bash
    cd Machine-Learning-Course
    ```
3.  Ensure your environment has standard data science libraries installed, or install missing ones via pip (`pip install pandas scikit-learn prophet seaborn lazy-predict`).
4.  Open the notebooks locally using Jupyter:
    ```bash
    jupyter notebook
    ```
    Navigate to the specific algorithm folder or the `FinalProject` to view the comprehensive `.ipynb` files!

## 👨‍💻 Author

**Saddam Hussain**  
*Post Graduate Diploma in Data Science & AI (Batch 10) | NED University*

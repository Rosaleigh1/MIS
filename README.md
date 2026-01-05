# 🌧️ Rainfall Prediction in Australia

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

> **Predict whether it will rain tomorrow in Australia based on daily weather observations.**

---

## 📖 Overview
This project leverages machine learning techniques to predict the binary target variable **`RainTomorrow`** (Yes/No). By analyzing historical weather data, we aim to build a robust model that can accurately forecast rainfall, aiding in agricultural and daily planning.

## 📂 Dataset
The dataset is sourced from the Australian Bureau of Meteorology.
* **Source:** [Rain in Australia - Kaggle](https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package?select=weatherAUS.csv)
* **Records:** Daily weather observations from numerous Australian weather stations.
* **Target:** `RainTomorrow`

---

## 🛠️ Methodology

The project workflow follows these key steps:

1.  **🧹 Data Preprocessing**
    * Handling missing values (Imputation).
    * Encoding categorical variables.
    * Feature selection.
    * **Time-Series Splitting:** Ensuring the model is validated on future data, not random splits.

2.  **🧠 Model Training**
    We experimented with several algorithms to find the best fit:
    * Decision Tree Classifier
    * Logistic Regression
    * Random Forest

3.  **🔍 Interpretability**
    * Feature Importance Analysis:** We analyzed the model's internal attributes (e.g., coefficients in Logistic Regression, split importance in Decision Trees) to determine which weather factors have the most significant impact on predicting rainfall.

---

## 🏆 Model Performance

Here is a summary of the model evaluations based on Accuracy:

<img width="1133" height="631" alt="image" src="https://github.com/user-attachments/assets/95b9bdb9-de12-4705-8d7d-2315ddb25c05" />

> *Note: Models were evaluated using TimeSeriesSplit to simulate real-world forecasting scenarios.*

---

## 📊 Visualizations

### Feature Importance
Analysis of which weather factors (e.g., Humidity, Pressure) contribute most to the rain prediction.

<img width="1129" height="638" alt="image" src="https://github.com/user-attachments/assets/f63dae31-5f34-4ab6-b208-d777b76a8044" />
<img width="1131" height="634" alt="image" src="https://github.com/user-attachments/assets/70c73071-d44b-459a-ba94-916294f03a86" />
<img width="1129" height="637" alt="image" src="https://github.com/user-attachments/assets/c4881c92-d935-4702-8efb-52adc56ad559" />


---

## 🚀 How to Run

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
    ```
2.  **Install dependencies**
    ```bash
    pip install pandas numpy scikit-learn matplotlib seaborn lime
    ```
3.  **Run the Notebook**
    Open `MIS_Project.ipynb` in Jupyter Notebook or Google Colab.

---

<p align="center">
  Made with ❤️ for the MIS Project
</p>

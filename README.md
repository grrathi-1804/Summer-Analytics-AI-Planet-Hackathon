# Summer-Analytics-AI-Planet-Hackathon

Submission for **Summer Analytics 2025** organized by **IIT Guwahati**.

---

## 📁 Files Included

- `Nutrition_Health_Survey_Age_Prediction_Summer_Analytics_2025.ipynb`  
  → Main Jupyter Notebook with exploratory data analysis, preprocessing, model training, and evaluation.

- `Submission.csv`  
  → Final predictions on the test set in the required submission format.

---

## 📌 Problem Statement

The task was to **predict the age** of individuals using the given nutrition and health survey data. The dataset includes features such as dietary habits, physical measurements, and other health indicators.

---

## 🔍 Approach

1. **Exploratory Data Analysis (EDA)**  
   - Handled missing values, identified outliers, and explored feature distributions.

2. **Preprocessing**  
   - Encoded categorical features
   - Standardized/normalized numerical columns where required

3. **Model Selection & Tuning**  
   - Trained various models (Linear Regression, Random Forest, etc.)
   - Chose the best-performing model based on MAE/RMSE

4. **Final Submission**  
   - Predictions were generated using the test dataset
   - Output saved in `Submission.csv` as per the format

---

## 🔧 Tools & Libraries Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 🏆 Evaluation Metric

The submission is evaluated using the **F1 Score**, which balances **precision** and **recall**—perfect for handling class imbalance.

**Formula:**
F1 = 2 * (Precision * Recall) / (Precision + Recall)
Where:
- **Precision** = TP / (TP + FP)  
- **Recall** = TP / (TP + FN)


---

## 🙋‍♂️ Author

- **Name**: Gaurav Rathi  
- **GitHub**: [grrathi-1804](https://github.com/grrathi-1804)

---

## 📬 Contact

For any queries related to this submission, feel free to reach out via GitHub or email.


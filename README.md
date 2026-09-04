# 🚚 Delivery Risk Classification using Logistic Regression

## 📌 Project Overview

This project applies **Logistic Regression** to predict whether a delivery is at risk (delayed) or not based on operational factors such as distance, warehouse load, and weather conditions.

The dataset used is **synthetic** and designed for educational purposes to practice classification techniques.

---

## 🎯 Objective

To build a machine learning model that classifies deliveries into:

* **0 → No Risk (On-time delivery)**
* **1 → Risk (Delayed delivery)**

---

## 📊 Dataset Description

The dataset contains ~1000 rows with the following features:

* `distance_km` – Delivery distance
* `warehouse_load` – Load on warehouse
* `order_hour` – Time of order
* `items_count` – Number of items
* `weather_risk` – Weather impact factor
* `carrier_delay_rate` – Delay probability
* `target` – Output (0 = No Risk, 1 = Risk)

---

## 🛠️ Tech Stack

* Python 🐍
* Pandas
* NumPy
* Matplotlib / Seaborn
* Scikit-learn

---

## ⚙️ Workflow

### 1. Data Preprocessing

* Removed duplicate records
* Checked and handled missing values
* Verified data consistency

### 2. Exploratory Data Analysis (EDA)

* Distribution plots
* Scatter plots
* Boxplots for outlier detection
* Correlation heatmap

### 3. Feature Engineering

* Created meaningful derived features (optional enhancements)
* Improved model input quality

### 4. Model Building

* Train-Test Split (80:20)
* Feature Scaling using StandardScaler
* Applied Logistic Regression

### 5. Model Evaluation

* Accuracy Score
* Confusion Matrix
* Precision, Recall, F1-score
* ROC Curve (AUC)

---

## 🤖 Model Used

**Logistic Regression**

* Suitable for binary classification
* Outputs probability of class membership
* Uses threshold (default = 0.5) to classify

---

## 📈 Results

* Model successfully classifies delivery risk
* Provides interpretable feature importance
* Achieves balanced performance across precision and recall

---

## 🔁 Comparison with Previous Work

| Aspect       | Previous Project  | Current Project     |
| ------------ | ----------------- | ------------------- |
| Problem Type | Regression        | Classification      |
| Model        | Linear Regression | Logistic Regression |
| Output       | Delivery Time     | Risk (0/1)          |

---

## 🚀 Applications

* Delivery delay prediction
* Logistics optimization
* Supply chain risk management
* Customer satisfaction improvement

---

## ⚠️ Limitations

* Dataset is synthetic
* Assumes linear relationship between features
* Real-world data may introduce noise

---

## 🔮 Future Improvements

* Use advanced models (Random Forest, XGBoost)
* Hyperparameter tuning
* Cross-validation
* Deploy as web app (Streamlit / Flask)

---

## 📂 How to Run

```bash
# Clone repo
git clone https://github.com/your-username/your-repo-name.git

# Install dependencies
pip install -r requirements.txt

# Run notebook
Open in Google Colab or Jupyter Notebook
```

---

## 👩‍💻 Author

**Kundeti Monasri**
AI & ML Student

---

## 📜 License

This project is for educational purposes only.

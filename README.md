# high_recipe_website_traffic
developing the machine learning model to predict which recipes will lead to **high website traffic**

Love it — let’s turn this into a **clean, recruiter-ready GitHub README** that actually *sells* your skills 🔥
Below is an **enhanced README.md** with the four sections you asked for, written in a professional, portfolio-friendly style.

You can **replace or append** this directly to your existing README.

---

```markdown
# 🍽️ Recipe Traffic Prediction Project

## 👤 Author
**Shamsuddeen Yusuf**  
Data Analyst | Machine Learning Enthusiast | Production Engineer  

---

## 📌 Project Overview
This project applies **data science and machine learning** to predict which recipes are likely to generate **high user traffic (≥80%)**, helping businesses minimize the risk of featuring low-performing content.

The solution combines **data cleaning**, **exploratory data analysis**, and **predictive modeling** to deliver **actionable insights** for editorial and operational decision-making.

---

## 🎯 Objectives
- Predict high-traffic recipes with high reliability
- Reduce the probability of featuring low-engagement recipes
- Support data-driven content placement decisions

---

## 🧠 Key Skills Demonstrated
- Data Cleaning & Validation
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Binary Classification Modeling
- Model Evaluation & Comparison
- Business Impact Translation

---

## 🗂️ Project Structure

```

recipe-traffic-prediction/
│
├── data/
│   ├── raw/                # Original dataset
│   └── processed/          # Cleaned and validated data
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_eda.ipynb
│   ├── 03_model_training.ipynb
│   └── 04_model_evaluation.ipynb
│
├── models/
│   ├── logistic_regression.pkl
│   └── random_forest.pkl
│
├── reports/
│   └── figures/            # Charts and visualizations
│
├── requirements.txt
├── README.md

````

---

## 🧹 Data Validation & Cleaning

- **Dataset size:** 947 recipes
- **Missing values:**  
  - 52 missing entries in calories, protein, sugar, and carbohydrates  
  - Imputed using **median values**
- **Category refinement:**  
  - `"Chicken Breast"` consolidated into `"Chicken"`
- **Servings:**  
  - Text noise removed (e.g., *"as a snack"*)
  - Converted to numeric format
- **Target variable:**  
  - `high_traffic` converted to binary:
    - `1` → High Traffic
    - `0` → Low or Missing Traffic

---

## 📊 Key Insights from Exploratory Data Analysis

### 🔑 Category Dominance
- Recipe category is the **strongest predictor** of traffic.
- Highest-performing categories:
  - **Vegetable**
  - **Potato**

### 🥗 Nutrition vs Preference
- High calorie content does **not** guarantee popularity.
- Users favor **meal type and category** over nutrient density.

### ☕ Underperforming Segment
- **Beverages** consistently generate low traffic regardless of nutrition.

---

## 🤖 Model Training

### Problem Type
- **Binary Classification**

### Features Used
- Category
- Servings
- Calories
- Carbohydrates
- Sugar
- Protein

### Models Implemented
| Model | Purpose |
|-----|--------|
| Logistic Regression | Baseline, interpretable, fast |
| Random Forest Classifier | Captures non-linear relationships |

---

## 🧪 Model Evaluation

### Evaluation Metrics
- **Accuracy**
- **Precision** (critical to avoid false positives)

### Key Findings
- Random Forest handled categorical variation more robustly.
- Confusion matrices were used to visualize prediction errors.
- Both models achieved **reliable performance**, with Random Forest slightly outperforming in robustness.

---

## 📦 Installation & Usage

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/recipe-traffic-prediction.git
cd recipe-traffic-prediction
````

### 2️⃣ Create Virtual Environment (Optional but Recommended)

```bash
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Run the Notebooks

Open Jupyter Notebook or Jupyter Lab:

```bash
jupyter notebook
```

Run notebooks in order:

1. `01_data_cleaning.ipynb`
2. `02_eda.ipynb`
3. `03_model_training.ipynb`
4. `04_model_evaluation.ipynb`

---

## 💼 Business Impact

### Metric of Interest

* Percentage of **High-Traffic Recipes** featured on the homepage

### Results

* **Current baseline:** 60.6%
* **With model-driven selection:**

  * Probability increases to **80%+**
  * Reduced risk of low-engagement days

---

## 🚀 Deployment & Integration

* Deploy the **Logistic Regression model** as a real-time scoring tool within the CMS.
* Use as a **Pre-Publishing Filter** for editorial teams.
* With larger datasets, migrate to **Random Forest** for improved predictive power.
* Implement monthly retraining using new traffic data.

---

## 🧠 Final Recommendations

* Prioritize:

  * Vegetable
  * Potato
  * Pork recipes
* Avoid featuring beverages in high-visibility sections.
* Establish continuous feedback and model retraining cycles.

---

## ⭐ Why This Project Matters

This project demonstrates the ability to:

* Translate raw data into business value
* Apply machine learning to real-world decision-making
* Communicate insights clearly to non-technical stakeholders

Perfect for **data analyst**, **machine learning**, or **analytics-driven business roles**.

---

## 📬 Contact

If you’d like to discuss this project or collaborate:

* **GitHub:** [https://github.com/your-username](https://github.com/your-username)
* **LinkedIn:** [https://linkedin.com/in/your-profile](https://linkedin.com/in/your-profile)

```

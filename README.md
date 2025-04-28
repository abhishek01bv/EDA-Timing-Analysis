# EDA-Timing-Analysis

Here’s a **brief and clear GitHub-ready project description** you can use in your README:

---

# ⚡ EDA ML Helper: Predicting Setup Timing Violations in VLSI

This project blends **VLSI design knowledge** with **machine learning** to predict whether a timing path in an integrated circuit will cause a **setup violation**.

### 🔍 Problem
In VLSI, setup violations can lead to faulty chips and failed tapeouts. Manually checking timing paths is tedious—so we use ML to automate it.

### 📊 Features Used
- `Delay_ns`: Total delay of the path  
- `Fanout`: Load on the gate (affects delay)  
- `Path_Length`: Number of gates in the path  
- `Slack_ns`: Time margin (negative = violation)

### 🛠️ Tools & Techniques
- Pandas, Seaborn, Matplotlib for EDA  
- RandomForestClassifier for prediction  
- SHAP for model explainability  
- Outlier detection & realistic noise simulation

### ✅ Outcome
Built a model to classify timing paths with 90%+ accuracy and visualized key circuit design insights. SHAP plots reveal how each feature affects the model’s prediction—helping engineers understand and trust ML outputs.

---

Let me know if you'd like a sample `README.md` file too!

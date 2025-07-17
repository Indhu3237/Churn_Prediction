# 📊 Hybrid Churn Prediction Model 

Welcome to the **Hybrid Churn Prediction** project!  
This notebook explores a unique approach to predicting customer churn by combining two powerful machine learning models: **Gradient Boosting** and **LSTM**.

The project uses the well-known **Telco Customer Churn dataset**, applying structured learning to static features (GBM) and sequential learning to temporal behavior (LSTM). The final predictions are passed through a **meta-learner** to make a more accurate and robust decision.

---

## 🔍 What You'll Find in This Notebook

✔️ Data Preprocessing and Cleaning  
✔️ Feature Engineering and Selection  
✔️ Training a GBM Model on Tabular Data  
✔️ Building and Training an LSTM on Sequential Features  
✔️ Combining Model Outputs Using a Meta-Learner  
✔️ Evaluation Metrics and Comparison  
✔️ Rich Visualizations like Heatmaps, ROC Curves, and more

---

## 🧠 Why a Hybrid Model?

Churn behavior can be influenced by both current state and past behavior. So instead of choosing either tree-based or sequence-based learning, we combined both:

- **GBM** helps in learning from billing, contract, and service features  
- **LSTM** captures usage patterns over time  
- The final layer is a **meta-model** that integrates the outputs and gives a final prediction score

---

## 📈 Plots and Profiling

The notebook provides clear and insightful visualizations that show:
- Feature correlations
- Prediction distributions
- Model performance comparisons
- Feature importances

---

## 💬 Final Thoughts

This project can be adapted for churn prediction in:
- Telecom
- SaaS products
- Streaming services
- Banking, Insurance, and more

By combining structured and sequential data pipelines, it brings better predictive power and opens up room for deep business insights.

---

🎯 Whether you're a student, researcher, or data science enthusiast, this notebook gives you a comprehensive look at hybrid modeling for churn!

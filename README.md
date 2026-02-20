# 🚀 Predicting Niche SaaS Subscription Churn
> **Algorithm:** Logistic Regression | **Niche:** B2B Project Management Tool

This project implements an interpretable machine learning pipeline to identify at-risk customer accounts for a B2B SaaS platform. By utilizing Logistic Regression, the model not only predicts *if* a user will churn but provides a mathematical breakdown of *why*.

---

## 📌 Project Overview
In the B2B SaaS industry, customer acquisition is expensive. Keeping existing users (retention) is the primary driver of growth. This project builds a **Churn Predictor** that helps Customer Success teams prioritize outreach to accounts showing signs of disengagement.

### The Unique Angle: B2B Metrics
Unlike generic datasets, this project focuses on metrics specific to project management tools:
* **Tasks Completed:** Measures the core value realized by the user.
* **Teammates Invited:** Measures the "stickiness" and network effect within an organization.
* **Support Tickets:** Measures technical friction and frustration.

---

## 🛠️ Tech Stack & Concepts
* **Python 3.x**: Core programming.
* **Scikit-Learn**: Model training, train-test splitting, and evaluation metrics.
* **Pandas & Numpy**: Data synthesis and feature engineering.
* **Logistic Regression**: Chosen for its high **interpretability** and ability to output **log-odds** for business logic.

---

## 📊 Evaluation Results
The model was tested on 200 unseen workspaces. The results demonstrate a high ability to identify healthy users, with a clear path identified for improving churn detection sensitivity.

### Confusion Matrix
```text
[[137   8]  -> 137 Correctly identified as "Staying"
 [ 39  16]] -> 16 Correctly identified as "Churning"
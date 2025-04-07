📊 Impact of Entropy and Mutual Information-Based Feature Selection on Classification Model Performance
This project investigates how two information-theoretic feature selection methods — Entropy and Mutual Information (MI) — affect the performance and training efficiency of machine learning classification models.

<br>
🧠 Overview
Feature selection helps reduce dataset complexity, improve model generalization, and lower training time. In this study, we evaluate two selection techniques:

Entropy: Unsupervised method that measures feature uncertainty.

Mutual Information (MI): Supervised method that quantifies dependency with the target variable.

We compare their effects across three classification models:

Logistic Regression

Decision Tree

Random Forest

Each model is evaluated under three conditions:

Using all features

Using entropy-selected features

Using MI-selected features

📁 Dataset
We used a publicly available airline passenger satisfaction dataset. It includes:

24 features: Numerical, categorical, and ordinal

Target: Binary label — satisfied vs neutral or dissatisfied

Balanced distribution: ~55% dissatisfied, ~45% satisfied

Preprocessing included:

Encoding: Label, One-Hot, and Ordinal encoding

Normalization: MinMaxScaler



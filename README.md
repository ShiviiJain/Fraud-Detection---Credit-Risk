This project focuses on building robust machine learning models to detect fraudulent credit card transactions within highly imbalanced datasets. The dataset consists of anonymized transaction records labeled as fraudulent or legitimate.

It has some key features: 
Data Imbalance Handling: Implemented Synthetic Minority Over-sampling Technique (SMOTE) to address severe class imbalance and improve model training.
Modeling Approaches: Developed and compared multiple classifiers, including Random Forest, Multi-Layer Perceptron (MLP), and Decision Tree models to identify fraud patterns.
Performance Metrics: Evaluated models using precision, recall, F1 score, and AUC-ROC to ensure balanced sensitivity and specificity.
Interpretability: Applied SHAP (SHapley Additive exPlanations) values for model interpretability, helping to explain the contribution of key features to fraud predictions.
Visualization: Created ROC curves and confusion matrices to visualize model performance and trade-offs.

Achieved significant improvements in F1 score (12% increase over baseline).
Reduced false positives while maintaining high detection rates, critical for minimizing unnecessary customer friction.

Python, scikit-learn, imbalanced-learn (SMOTE), SHAP, Matplotlib, Seaborn, Pandas

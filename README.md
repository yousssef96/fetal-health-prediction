# Description

The goal of this project is to predict fetal health status (Normal, Suspect, or Pathological) using supervised machine learning models. By analyzing cardiotocography (CTG) data, the models aim to classify the condition of the fetus and assist in early detection of potential complications. This project demonstrates preprocessing, dimensionality reduction with PCA, handling class imbalance, and model evaluation using ensemble methods such as a Majority Vote Classifier that combines Logistic Regression, k-Nearest Neighbors (kNN), and Gradient Boosting.

Context

Fetal health monitoring is critical for ensuring safe pregnancies and reducing risks during labor. Cardiotocography, a widely used non-invasive test, records fetal heart rate and uterine contractions. However, manual interpretation is often subjective and prone to variability among medical experts. Machine learning can provide objective, data-driven support for classifying CTG results and improving decision-making in obstetric care.

Healthcare datasets like this are often imbalanced, with relatively few pathological cases compared to normal ones. This project applies techniques to handle imbalance and uses evaluation metrics beyond accuracy to fairly assess model performance.

Potential Impact

A reliable fetal health prediction system could help doctors and midwives identify high-risk pregnancies earlier, leading to timely interventions, reduced complications, and better outcomes for both mothers and babies. On a broader scale, such predictive tools can support healthcare systems in resource allocation and reduce perinatal mortality rates.

Evaluation

Model performance is evaluated using:

ROC Curves and AUC (One-vs-Rest): assess the ability to distinguish between Normal, Suspect, and Pathological classes.

Classification Report: provides precision, recall, and F1-scores for each class.

Cross-Validation: ensures robust performance across multiple data folds.

Scree Plot (PCA): visualizes explained variance by principal components to aid dimensionality reduction.

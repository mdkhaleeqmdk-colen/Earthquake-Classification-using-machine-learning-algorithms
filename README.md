This project builds and compares ML models to classify earthquake alert levels (green, yellow, orange, red) from seismic features such as magnitude, depth, CDI, MMI, significance, and mag type. 

What’s inside

Final.ipynb — end-to-end notebook: EDA → preprocessing → model training/evaluation. 

Report (docx) — methodology, figures, results, and references.

Data

Kaggle earthquake records with attributes including magnitude, depth, CDI, MMI, alert, tsunami, significance, latitude/longitude, and magType. Missing values handled; categorical fields label-encoded. 

Methods

Models trained and compared:

Naive Bayes

Random Forest

Gradient Boosting
Evaluation uses accuracy, precision, recall, F1, confusion matrix; basic hyperparameter tuning performed. 

Results (headline)

Random Forest and Gradient Boosting: ~84% accuracy overall.

Naive Bayes: ~53% accuracy; struggles on minority classes.
Minority alert levels (yellow/red) are harder to predict; class imbalance is a factor.

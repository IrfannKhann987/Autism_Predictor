🧠 Autism Screening Predictor (Random Forest + Optuna)

Machine Learning Pipeline for Autism Spectrum Disorder (ASD) Prediction

This project implements a Random Forest Classifier optimized with Optuna hyperparameter tuning to predict the likelihood of Autism Spectrum Disorder based on screening questionnaire responses and demographic data. The entire workflow is in a Google Colab notebook, making it easy to run and reproduce results.

🚀 Features
Tried diffrent model and applied the one with best results(RandomForest)

Random Forest Classifier: Efficient tree-based model for classification.

Optuna Hyperparameter Tuning: Automatically finds the best model parameters.

SMOTE for Imbalanced Data: Balances the dataset to handle minority ASD cases.

Evaluation Metrics: Accuracy, F1-score, or other metrics can be calculated in the notebook.

Reproducible Workflow: Step-by-step data preprocessing, training, tuning, and evaluation.

📂 Project Structure
Autism_Screening_Predictor/
│
├── Autism_Prediction_Colab.ipynb   # Main Colab notebook
└── README.md

💻 How to Run

Click the Open in Colab badge above.

Upload your dataset or use the sample dataset provided in the notebook.

Run cells sequentially to:

Preprocess data and handle missing values

Apply SMOTE for balancing classes

Train and optimize a Random Forest model using Optuna

Evaluate performance on test data

No local installation is needed — everything runs in Colab.

📦 Requirements
pandas
numpy
scikit-learn
imbalanced-learn
optuna
matplotlib
seaborn


You can also install them directly in Colab via !pip install ...

👨‍💻 Author

Irfan Khan

Data Science & Machine Learning Enthusiast

GitHub: https://github.com/IrfannKhann987

⚠️ Notes

This notebook is for educational and research purposes only.

Predictions are not medical advice; consult professionals for diagnosis.

If categorical features (like gender or jaundice) are used, ensure consistent encoding when applying the model.

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

A Note :: Before building this project i didnt know what is Autism so i searched google and this was what i found

Autism Spectrum Disorder (ASD) is a lifelong neurodevelopmental condition that affects communication, social interaction, and behavior, presenting as a spectrum of challenges with varying severity. It stems from a complex interaction of genetic and environmental factors that impact the developing brain, though the exact cause of ASD is unknown. Risk factors include genetic predispositions, such as having a family member with autism, advanced parental age, and certain conditions during pregnancy, like maternal diabetes or infections.  
What is Autism?
Neurodevelopmental disorder: ASD is a condition present from birth that impacts brain development. 
Spectrum: It's called a "spectrum" because the signs and symptoms can vary widely from person to person. 
Key Characteristics: Common features include difficulties with social communication and interaction, restricted interests, and repetitive behaviors. 
Lifelong condition: ASD is a lifelong condition that affects daily functioning. 
What are the Causes of Autism?
The exact cause of autism is unknown, but scientists believe a combination of genetic and environmental factors is responsible. 
Genetic Factors:
Family history: There is strong evidence for a genetic link, as having a child with autism increases the risk for another biological child to have it. 
Gene mutations: Specific genetic mutations have been identified in some cases, though most cases lack a clear genetic cause. 
Environmental Factors:
Parental factors: Advanced parental age and certain maternal health conditions like diabetes or infections during pregnancy are associated with an increased risk. 
Birth complications: Very low birth weight or oxygen deprivation during birth are also considered risk factors. 
Early life exposures: Some research suggests that factors like exposure to air pollution or certain medications during pregnancy may contribute. 
It is important to note that while these factors are associated with an increased risk of autism, they do not guarantee that someone will develop the conditioAutism Spectrum Disorder (ASD) is a lifelong neurodevelopmental condition that affects communication, social interaction, and behavior, presenting as a spectrum of challenges with varying severity. It stems from a complex interaction of genetic and environmental factors that impact the developing brain, though the exact cause of ASD is unknown. Risk factors include genetic predispositions, such as having a family member with autism, advanced parental age, and certain conditions during pregnancy, like maternal diabetes or infections.  
What is Autism?
Neurodevelopmental disorder: ASD is a condition present from birth that impacts brain development. 
Spectrum: It's called a "spectrum" because the signs and symptoms can vary widely from person to person. 
Key Characteristics: Common features include difficulties with social communication and interaction, restricted interests, and repetitive behaviors. 
Lifelong condition: ASD is a lifelong condition that affects daily functioning. 
What are the Causes of Autism?
The exact cause of autism is unknown, but scientists believe a combination of genetic and environmental factors is responsible. 
Genetic Factors:
Family history: There is strong evidence for a genetic link, as having a child with autism increases the risk for another biological child to have it. 
Gene mutations: Specific genetic mutations have been identified in some cases, though most cases lack a clear genetic cause. 
Environmental Factors:
Parental factors: Advanced parental age and certain maternal health conditions like diabetes or infections during pregnancy are associated with an increased risk. 
Birth complications: Very low birth weight or oxygen deprivation during birth are also considered risk factors. 
Early life exposures: Some research suggests that factors like exposure to air pollution or certain medications during pregnancy may contribute. 
It is important to note that while these factors are associated with an increased risk of autism, they do not guarantee that someone will develop the conditio


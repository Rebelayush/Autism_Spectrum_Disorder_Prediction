🧠 Autism Spectrum Disorder (ASD) Prediction Using Machine Learning



📌 Project Overview
This project focuses on building a machine learning pipeline to predict whether an individual is likely to be on the Autism Spectrum based on behavioral data. With a goal of early detection, the model can assist in preliminary screening and support healthcare professionals.

Accuracy Achieved: 92%

Frameworks Used: TensorFlow, Scikit-learn

Techniques Applied: PCA, normalization, correlation analysis, regularization

🚀 Features
✅ Supervised learning model for binary classification (ASD vs. non-ASD)

✅ Automated data preprocessing pipeline

✅ Dimensionality reduction using PCA

✅ Model optimization and regularization to prevent overfitting

✅ End-to-end script automation for reproducibility

🧪 Tech Stack
Programming Language: Python

Libraries: TensorFlow, NumPy, Pandas, Scikit-learn, Matplotlib

Modeling Techniques: Logistic Regression, Random Forest, Neural Networks

Tools: Jupyter Notebook

📊 Dataset
The dataset includes behavioral attributes and screening results related to ASD traits. Public datasets like UCI ASD Screening Data were used, which include features like:

Age

Gender

A1–A10 behavioral questions

Result from AQ-10 screening

Family history of autism

All personally identifiable information (PII) was anonymized or removed.


📈 Model Performance
Metric	           Value
Accuracy	    92%
Precision	   High
Recall	           High
F1 Score	 Balanced

📁 Project Structure

Autism_Spectrum_Disorder_Prediction/
├── data/                      # Raw and cleaned datasets
├── notebooks/                # Jupyter Notebooks
├── src/                      # Python scripts for modeling and preprocessing
├── models/                   # Saved model files
├── requirements.txt
└── README.md


🛠 Setup Instructions

1. Clone the Repository

   git clone https://github.com/Rebelayush/Autism_Spectrum_Disorder_Prediction.git
   cd Autism_Spectrum_Disorder_Prediction


2. Create a Virtual Environment

   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate



3. Install Dependencies

   pip install -r requirements.txt

4. Run the Model

   python src/train_model.py



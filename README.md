# Cancer Cell Type Classification

[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)

## Project Overview

This repository implements a system to classify cancerous and non-cancerous cell images using both classical machine learning models (Logistic Regression, Random Forest) and deep learning (Convolutional Neural Networks). The goal is to provide accurate, automated cancer cell detection to assist early diagnosis.

---

## Directory Structure

CANCER-CELL-TYPE-CLASSIFICATION/
│
├── .git/ # Git version control directory
├── .gitignore # Specifies files and folders to ignore in Git
├── app.ipynb # Jupyter notebook for main application / analysis
├── dataset/ # Dataset folder
│ ├── images/ # Cell images for classification
│ └── data_labels_mainData.csv # CSV labels and metadata
├── logistic_regression_model.pkl # Pre-trained Logistic Regression model (pickle format)
├── README.md # Project overview and instructions
├── requirements.txt # Python dependencies list
└── train.ipynb # Notebook for training machine learning and deep learning models
 

---

## Installation Instructions

1. **Clone the repository**

```bash
git clone https://github.com/Waqas56jb/cancer-cell-type-classification.git
cd cancer-cell-type-classification
Create and activate a virtual environment (recommended)

 
python -m venv venv
# On Linux/macOS
source venv/bin/activate
# On Windows
venv\Scripts\activate
Install the required packages

 
pip install --upgrade pip
pip install -r requirements.txt
Usage
Training Models
Open the train.ipynb notebook.

This notebook walks through data preprocessing, training classical ML models (Logistic Regression, Random Forest), unsupervised clustering, CNN training, and model evaluation.

Run the notebook cells sequentially to reproduce the training process and results.

 
jupyter notebook train.ipynb
Running the Application / Analysis
Use app.ipynb for further analysis or to apply the trained models for predictions.

Load saved models such as logistic_regression_model.pkl as needed.

Requirements
Python 3.7+

Packages include:

numpy

pandas

scikit-learn

tensorflow

keras

matplotlib

seaborn

joblib

All dependencies are in requirements.txt.

Model Files
logistic_regression_model.pkl: Pre-trained Logistic Regression model saved for inference.

Additional models (Random Forest, CNN) can be saved or loaded via the notebooks.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Contact
For questions or collaboration, please contact:

Waqas
Email: your.email@example.com
GitHub: https://github.com/Waqas56jb

Thank you for exploring this project! Contributions and feedback are welcome.

 
 
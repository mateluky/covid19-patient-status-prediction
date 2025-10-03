# COVID-19 Patient Status Prediction

This project develops a **machine learning model** to help hospitals rapidly identify COVID-19 positive patients based on clinical and demographic data.  
By predicting infection status early, the system aims to **optimize bed occupancy**, **streamline testing workflows**, and **enable timely isolation and treatment**, supporting hospitals under pandemic pressure.


## 📌 Project Overview

Traditional COVID-19 diagnostics often rely on **manual testing** and **delayed laboratory results**, which can slow down hospital workflows.  
This project leverages **patient-level features** (symptoms, vital signs, demographics) and applies **supervised learning models** to predict COVID-19 infection status.  

Key steps:
- **Exploratory Data Analysis (EDA)** with visualizations
- **Feature preprocessing and scaling**
- **Model training & evaluation** using:
  - Decision Trees
  - Random Forest Classifier
- **Performance metrics**: accuracy, F1 score, ROC curves, confusion matrices
- **Feature importance analysis** to identify the most predictive patient variables

## 📂 Repository Structure
```
.
├── data_processing_covid.ipynb # Main Jupyter notebook (modeling + analysis)
├── README.md # Project documentation
├── requirements.txt # Python dependencies
└── LICENSE # 
```

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/mateluky/covid19-patient-status-prediction.git
cd covid19-patient-status-prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## 🚀 Usage

Open the Jupyter Notebook:
```bash
jupyter notebook data_processing_covid.ipynb
```

Run the cells step by step to:
- Load and preprocess hospital patient data.
- Train decision tree and random forest models.
- Evaluate performance using classification metrics.
- Visualize feature importance and predictive insights.

## 📊 Results

- Confusion Matrix: Shows correct vs misclassified cases.
- ROC Curve & AUC: Assesses discriminative power.
- Feature Importance Plot: Highlights most predictive variables.

## 📦 Requirements

Main Python libraries:

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

A full list is in requirements.txt.

## 📝 License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.



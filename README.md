# CrimeCast: Forecasting Crime Categories

This repository contains my submission for the **[CrimeCast: Forecasting Crime Categories](https://kaggle.com/competitions/crime-cast-forecasting-crime-categories)** competition on Kaggle.

The goal of this competition is to predict the category of a crime based on incident details such as location, victim information, and other contextual features.

---

## 📌 Competition Details
- **Objective**: Classify the type of crime from given historical incident data.
- **Evaluation Metric**: Accuracy score.
- **Dataset**: Provided by the competition (not included here — must be downloaded from Kaggle).
- **Private Score**: `0.74720`
- **Best Score**: `0.85600` (Version 5)

---

## 📂 Repository Structure
├── 22f1000675-notebook-t22024.ipynb # Kaggle notebook containing the full solution
├── requirements.txt # Python dependencies
└── README.md # Project documentation

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/Hades-69-420/Crime_Category_Prediction.git
cd Crime_Category_Prediction

###2. Create and activate a virtual environment (recommended)
python -m venv venv
# On Linux/Mac:
source venv/bin/activate
# On Windows:
venv\Scripts\activate

###3. Install dependencies
pip install -r requirements.txt

###4. Download the Dataset
Visit the Kaggle competition page
Accept the rules and download the dataset.
Place the dataset inside a data/ folder in this repository.

###5. Run the notebook
You can run the notebook using:
jupyter notebook 22f1000675-notebook-t22024.ipynb
or open it directly on Kaggle.

### Methodology

1.Data Preprocessing:
Handled missing values
Encoded categorical variables
Normalized numerical features

2.Modeling:
Tested multiple classification algorithms
Tuned hyperparameters for optimal performance

3.Evaluation
Compared models based on validation accuracy
Generated final predictions for Kaggle submission

### Citation
iitmbscs2008p. CrimeCast: Forecasting Crime Categories. 
https://kaggle.com/competitions/crime-cast-forecasting-crime-categories, 2024. Kaggle.

# QSAR Model: Predicting IC50 for EGFR Inhibitors

This project builds a QSAR (Quantitative Structure-Activity Relationship) model to predict IC50 values for molecules targeting EGFR (Epidermal Growth Factor Receptor), using molecular descriptors.

## 📊 Dataset
- Source: [ChEMBL - EGFR Target (CHEMBL203)](https://www.ebi.ac.uk/chembl/target_report_card/CHEMBL203/)
- Filtered for IC50 values with valid SMILES
- Cleaned and processed for regression modeling

## 🧪 Descriptors
- Molecular Weight (MolWt)
- LogP (lipophilicity)
- TPSA (Topological Polar Surface Area)

## 🧠 Model
- Algorithm: Random Forest Regressor
- Evaluation Results:
  - **R² Score**: 0.16
  - **Mean Squared Error (MSE)**: 83,756,896.63
  - Visual Output: Scatter plot of predicted vs actual IC50 values

## 🔧 Tools & Libraries
- Python, RDKit, pandas, scikit-learn, matplotlib

## 🛠 How to Run
1. Clone the repo
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open `QSAR_Predictor.ipynb` with Jupyter Notebook

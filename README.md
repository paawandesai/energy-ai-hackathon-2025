# Energy A.I. Hackathon 2025 – Team Data Comrades 🏆  
First Place Winners | **Predictive Energy Modeling for Hydraulic Fracturing**

## Overview  
This repository contains the complete workflow, solutions, and presentation for the Energy A.I. Hackathon 2025 hosted by The University of Texas at Austin. Our project aimed to predict energy consumption (**Grid, Diesel, and CNG**) for hydraulic fracturing operations, incorporating uncertainty modeling and domain-informed feature engineering.  

Our solution was awarded **1st Place** among 25 teams based on accuracy (MAPE), code quality, and presentation.

---

## Repository Contents  

### 1. **Workflow**  
- `workflow_demo.ipynb`: A complete Jupyter Notebook outlining our end-to-end workflow. It includes:  
  - **Data Cleaning & Imputation**: Addressing missing values and preparing the dataset for modeling.  
  - **Feature Engineering**: Using **CatBoost encoding**, feature ranking, and domain-informed transformations.  
  - **Model Building**: Implementing **XGBoost** and **Random Forest** models, with hyperparameter tuning using **UTuning**.  
  - **Uncertainty Modeling**: Generating 100 realizations per well for robust prediction.

### 2. **Solutions**  
- `solution.csv`: Our final submission file containing:  
  - Estimated energy consumption for **Grid**, **Diesel**, and **CNG**.  
  - 100 realizations per well for uncertainty quantification.

### 3. **Presentation**  
- `datacomrades_final.pptx`: The final presentation delivered to the judges, detailing our methodology, results, and recommendations.  

---

## Key Results  
- **R² Scores**:  
  - Grid: **0.9918**  
  - Diesel: **0.9766**  
  - CNG: **0.9692**  
- **Highlights**:  
  - Robust uncertainty modeling with 100 realizations per well.  
  - Feature engineering techniques such as **CatBoost encoding** and temporal modeling.  
  - Custom libraries: **ozbayrak_goodness** (goodness evaluation) and **UTuning** (hyperparameter optimization).  

---

## Tools and Technologies  
- **Programming Languages**: Python  
- **Libraries**: scikit-learn, XGBoost, Pandas, NumPy, CatBoost  
- **Custom Tools**: ozbayrak_goodness, UTuning  
- **Visualization**: Jupyter Notebook  
- **Presentation**: PowerPoint  

---

## How to Use  
1. Clone this repository:  
   ```bash
   git clone https://github.com/yourusername/energy-ai-hackathon-2025.git
   cd energy-ai-hackathon-2025

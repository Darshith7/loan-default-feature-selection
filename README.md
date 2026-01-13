# Loan Default Feature Selection Analysis

This project presents a comparative analysis of multiple filter-based feature selection techniques applied to a large-scale loan default prediction dataset. The goal is to identify the most relevant features influencing loan default risk and to compare the behavior of different statistical and information-theoretic filter methods.

## Project Overview
Loan default prediction is a critical task in the financial domain, as incorrect assessment of credit risk can lead to significant financial losses. Real-world financial datasets often contain a large number of features, not all of which contribute equally to predictive performance. Feature selection helps in identifying the most informative features while reducing redundancy and noise.

In this project, nine filter-based feature selection techniques are implemented and compared using a dataset containing over 255,000 loan records.

## Feature Selection Methods Used
- Pearson Correlation Coefficient  
- Chi-Square Test  
- Variance Threshold  
- Information Gain  
- Mutual Information  
- Fisher Score  
- Laplacian Score  
- Symmetrical Uncertainty  
- Markov Blanket Filtering  

## Dataset
The dataset used for this study consists of 255,348 loan records with demographic, financial, and loan-related attributes.

**Note:**  
Due to size and licensing constraints, the dataset is not included in this repository. The dataset was used only for academic and research purposes.

## Preprocessing Steps
- Handling missing values using median (numerical) and mode (categorical)
- Label encoding of categorical variables
- Feature scaling using:
  - Standardization (Z-score normalization)
  - Min–Max normalization
- Train–test split to ensure robustness of analysis

## Results
Each feature selection method produces a ranked list of features based on its evaluation criteria.  
The consolidated results are available in:
feature_selection_results.xlsx

This file contains separate sheets for each feature selection method.

## Tools & Technologies
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Git & GitHub

## Repository Structure
loan-default-feature-selection/
│
├── feature_selection.ipynb
├── feature_selection_results.xlsx
├── README.md
└── .gitignore

## Key Takeaways
- Financial attributes such as income, loan amount, interest rate, and employment duration play a significant role in loan default prediction.
- Categorical attributes related to financial responsibility (e.g., dependents, co-signer, mortgage) are strongly highlighted by information-theoretic methods.
- No single filter method is universally optimal; combining insights from multiple methods provides a more comprehensive understanding.

## Author
**Sai Darshith**  
B.Tech – Computer Science & Financial Technology  
Manipal Institute of Technology

---

## License
This project is intended for academic and educational use only.


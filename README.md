# Feature Selection Using MIQP and LASSO

## Table of Contents
1. [Introduction/Overview](#1-introductionoverview)
2. [Objective](#2-objective)
3. [Methodology/Approach](#3-methodologyapproach)
4. [Installation/Requirements](#4-installationrequirements)
5. [File Descriptions](#5-file-descriptions)
6. [Data Collection and Sources](#6-data-collection-and-sources)
7. [Results](#7-results)
8. [Conclusion](#8-conclusion)
9. [Contributors/Team](#9-contributorsteam)
10. [License](#10-license)

## 1. Introduction/Overview
This project explores feature selection in predictive analytics using Mixed Integer Quadratic Programming (MIQP) and LASSO (Least Absolute Shrinkage and Selection Operator). It aims to determine the effectiveness of these methods in selecting variables for regression models.

## 2. Objective
Comparing MIQP and LASSO to identify the most efficient method for feature selection in regression analysis.

## 3. Methodology/Approach
- **MIQP Implementation**: Utilizing Gurobi for direct variable selection.
- **LASSO Regression**: Employing L1 regularization for indirect variable selection.
- **Comparative Analysis**: Assessing both methods in terms of predictive performance and selected features.

## 4. Installation/Requirements
- [Python](https://www.python.org/downloads/)
- [Jupyter Notebook](https://jupyter.org/install)
- [Gurobi Optimizer](https://www.gurobi.com/downloads/) - Requires Gurobi license

## 5. File Descriptions
- **`Feature-Selection-Using-MIQP-And-LASSO.ipynb`**: This Jupyter Notebook contains Python code for feature selection using two methods MIQP and LASSO.
- **`DATA`**: A folder containing data files.

## 6. Data Collection and Sources
**Datasets Overview:**  
This project uses two CSV files located in the Data folder. These two datasets include `X` and `Y` data:

- `training_data.csv`
- `test_data.csv`

**File Structure:**  
- The first column is target `Y`.
- Columns 2-51 represents predictors, labeled `X1`, `X2`, `X3`, .... `X50`.

## 7. Results
- The project demonstrates that MIQP can be more effective in certain contexts, providing a more streamlined model with fewer variables.
- LASSO, while effective, tends to select more variables and may be preferred for its computational efficiency.

## 8. Conclusion
Both MIQP and LASSO are robust for fitting training data, but MIQP shows a marginal edge in test performance. The choice between MIQP and LASSO depends on the trade-off between accuracy and computational efficiency, as well as the specific requirements of the predictive model.

## 9. Contributors/Team
- Manideep Telukuntla
- Vaishnavi Ganesh
- Sanjana Nayak
- Bin Yang

## 10. License
Licensed under [MIT License](https://github.com/ManideepTelukuntla/InvestigateTMDBMovieData/blob/master/LICENSE)

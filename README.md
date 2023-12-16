# Feature Selection Using MIQP and LASSO

## Overview
This project explores feature selection in predictive analytics using Mixed Integer Quadratic Programming (MIQP) and LASSO (Least Absolute Shrinkage and Selection Operator). It aims to determine the effectiveness of these methods in selecting variables for regression models.

## Team
- Manideep Telukuntla
- Vaishnavi Ganesh
- Sanjana Nayak
- Bin Yang

## Objective
Comparing MIQP and LASSO to identify the most efficient method for feature selection in regression analysis.

## Methodology
- **MIQP Implementation**: Utilizing Gurobi for direct variable selection.
- **LASSO Regression**: Employing L1 regularization for indirect variable selection.
- **Comparative Analysis**: Assessing both methods in terms of predictive performance and selected features.

## Results
- The project demonstrates that MIQP can be more effective in certain contexts, providing a more streamlined model with fewer variables.
- LASSO, while effective, tends to select more variables and may be preferred for its computational efficiency.

## Conclusion
Both MIQP and LASSO are robust for fitting training data, but MIQP shows a marginal edge in test performance. The choice between MIQP and LASSO depends on the trade-off between accuracy and computational efficiency, as well as the specific requirements of the predictive model.

# Linear Regression Model – Forest Fire Weather Index (FWI)

This project implements a linear regression model to predict the **Fire Weather Index (FWI)**, a key indicator in forest fire risk assessment. The data used comes from a fire dataset in Algeria.

---

## Project Contents

- `Linear_regression_model.ipynb`: Notebook with the complete analysis, from data loading to model evaluation.
- Visualizations and error analysis included (scatter plots, residual distribution).
- Evaluation with metrics such as MSE, RMSE, and R².

---

## Technologies Used

- Python
- Pandas and NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Main Variables

- **FFMC, DMC, DC, ISI, BUI**: Indices related to soil and climate conditions that influence fires.
- **FWI** (*target*): Composite index representing total fire risk.
- **Temperature, RH, Wind Speed**: Standard meteorological variables.

---

## Results

The linear regression model achieved an R² of approximately 0.98, indicating that it explains approximately 98% of the variance in the FWI. The distribution of the residuals suggests a good fit, with no significant bias.

---

## Future Contributions

- Comparison with more complex models such as Random Forest, or classification models such as Logistic Regression.
- Implementation of an interactive dashboard for risk visualization.

---

## Author

Developed by Andres Felipe Santa as part of an academic project on linear regression in the context of the Neural Networks and Deep Learning class.

---

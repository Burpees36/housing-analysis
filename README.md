# Housing Price Regression Analysis (R)

This project analyzes housing prices using a structured regression workflow in **R** within a **Jupyter Notebook**. The goal is to understand which housing characteristics are most strongly associated with price and to compare multiple regression specifications to improve model fit and interpretability.

## Project Highlights
- Built and compared multiple regression models:
  - **Model 1:** Baseline multiple linear regression
  - **Model 2:** Interaction model to test whether effects change under different conditions
  - **Model 3:** Quadratic model to capture potential nonlinear relationships
- Evaluated models using:
  - **Adjusted R²**
  - **Residual Standard Error (RSE)**
  - **Nested F-tests** (ANOVA comparison for nested models)
- Reviewed diagnostic plots to assess key regression assumptions (residual patterns, normality, outliers/influence)

## Deliverables
- `index.html`: Rendered report view of the notebook (recommended for recruiters)

## Tools / Environment
- R in a Jupyter Notebook environment
- Base R modeling functions (e.g., `lm()`, `anova()`, `summary()`)


## Methods Overview
1. Data review and exploratory analysis (EDA)
2. Fit baseline linear regression (Model 1)
3. Add interaction terms to test conditional effects (Model 2)
4. Add quadratic terms to model nonlinearity (Model 3)
5. Compare models with adjusted R², RSE, and nested F-tests
6. Validate assumptions using diagnostic plots

## Key Takeaways (High Level)
- Housing price generally increases with living area, though the relationship may not be perfectly linear.
- Model extensions (interactions and quadratic terms) can improve fit, but must be justified by both metrics and interpretability.
- Nested F-tests provide evidence when a more complex model significantly improves upon a simpler baseline model.

## Notes
- If a dataset file is not included in this repo, it was omitted due to licensing or course constraints. The notebook/report documents the variables and workflow used.


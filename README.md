# DSCI 552 - Homework 5

Decision tree interpretation and pruning, followed by regression using least squares, ridge, LASSO, PCR, and XGBoost.

The required work is in [Oliver_Austin_HW5.ipynb](Oliver_Austin_HW5.ipynb). I tested the jupyter output with a PDF with saved outputs in [Oliver_Austin_HW5.pdf](output/pdf/Oliver_Austin_HW5.pdf), within the 20-page submission limit. I tried to be more concise with the outputs, since my initial jupyter notebook I created was around 26 pages with the all the cell outputs.

The notebook uses the Acute Inflammations and Communities and Crime datasets in `data/`. Assignment instructions are in [Homework5.pdf](Homework5.pdf).

For regression, the first 1,495 rows are used for training and the remaining 499 for testing. The random seed is 552.

Install the packages below, then open the notebook in Jupyter or VS Code and run all cells from the repo folder.

```bash
pip install numpy pandas matplotlib seaborn scikit-learn==1.7.2 xgboost==3.2.0 ipython ipykernel threadpoolctl
```

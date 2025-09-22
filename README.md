# CS4372_HW_Datasets_Shyam_Rudy
Dataset Link: [https://archive.ics.uci.edu/dataset/849/power+consumption+of+tetouan+city](https://archive.ics.uci.edu/dataset/849/power+consumption+of+tetouan+city)

Overview: 
  This project predicts electricity consumption in Zone 1 of Tétouan city using weather and time-based features.
Two regression models are used: SGDRegressor (from scikit-learn, with hyperparameter tuning) and OLS (from statsmodels).

How to Run:
  1. Open the .ipynb notebook in Jupyter Notebook, VS Code, or any IDE that supports notebooks.
  2. Run all cells in order:
  3. Load the dataset
  4. Preprocess and create time-based features
  5. Explore distributions and correlations
  6. Split into train and test sets
  7. Run the Hyperparameter Tuning section (shows the best parameter combinations)
  8. Run the final SGDRegressor cell (this trains with the best tuned parameters)
  9. Run the OLS model cell to compare results

Files Included:
  1. CS4372HW1_Shyam_Rudy.ipynb — complete code
  2. Tetuan City power consumption.csv — dataset
  3. Project 1 Report for CS 4372.501 - Rudy Rajput, Shyam Devani.pdf — written report

Note:
The final tuned model is trained in the last cell of the notebook.
No installation or cloning is required — just open the notebook and run all cells.

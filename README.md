# xAutoML_Project1

- Credit Card Fraud Detection: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud?resource=download
- Redwine Quality: https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009

Steps:

1. Baseline_no_tuning_*.ipynb - Choose a dataset. Build and train a baseline for comparison. To construct the baseline you do the following Try a set of possible machine learning algorithms using their default hyperparamters and choose the one with the highest performance for comparison. 

2. Hyperopt.ipynb - Based on the problem at hand, you study the potential pipeline structure, algorithms or feature transformers at each step, hyper-parameters ranges. Use hyperOpt with the potential search space to beat the baseline.

3. Hyperopt_*.ipynb - Monitor the the performance of you the constructed pipeline from the previous step across different time budgets (number of iterations) and report the least time budget that you are able to outperform the baseline. Determine whether the difference in performance between the constructed pipeline and the baseline is statistically significant.

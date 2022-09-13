# FinTech-Mod14-Challenge
FinTech-Mod14-Challenge

![Link](plt_act_vs_str_1mth.png)

![Link](plt_act_vs_str_3mth.png)

![Link](plt_act_vs_str_5mth.png)

![Link](plt_act_vs_str_SMA_2&500.png)

![Link](plt_act_vs_str_SMA_1&1000.png)

![Link](plt_act_vs_str_NewClassifier.png)

### Step 1: Tune the training algorithm by adjusting the size of the training dataset. 

To do so, slice your data into different periods. Rerun the notebook with the updated parameters, and record the results in your `README.md` file. 

Answer the following question: What impact resulted from increasing or decreasing the training window?

Answer: Increasing/Decreasing the training window did little to impact the result.

### Step 2: Tune the trading algorithm by adjusting the SMA input features. 

Adjust one or both of the windows for the algorithm. Rerun the notebook with the updated parameters, and record the results in your `README.md` file. 

Answer the following question: What impact resulted from increasing or decreasing either or both of the SMA windows?

Answer: Increasing /Decreasing the SMA windows reduced slightly the gap between the actual and strategy returns.

### Step 3: Choose the set of parameters that best improved the trading algorithm returns. 

Save a PNG image of the cumulative product of the actual returns vs. the strategy returns, and document your conclusion in your `README.md` file.

The conclusion is that increased SMA windows improves the results.

# Evaluate a New Machine Learning Classifier

### Step 3: Backtest the new model to evaluate its performance. 

Save a PNG image of the cumulative product of the actual returns vs. the strategy returns for this updated trading algorithm, and write your conclusions in your `README.md` file. 

Answer the following questions: 
Did this new model perform better or worse than the provided baseline model? 
Did this new model perform better or worse than your tuned trading algorithm?

Answer: This new model performed about the same as the provided baseline model.

Answer: This new model performed worse than the tuned trading algorithm.

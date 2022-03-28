Answer the following question: What impact resulted from increasing or decreasing the training window?

Increase in the training windows allow the model to predict more accurate result, as the stratedgy returns is more closer to the actual returns, reducing the training windows make reduce the model prediction accuracy, hence the strategy returns is farther from the actual returns.


Answer the following question: What impact resulted from increasing or decreasing either or both of the SMA windows?

Increasing the SMA short and long windows make the accuracy of the model increase. Using SMA short of 6 and SMA long of 150 make the stratedgy returns align more to the actual returns compared to the default model using 4-short and 100-long windows.


Save a PNG image of the cumulative product of the actual returns vs. the strategy returns, and document your conclusion in your README.md file.

The parameter that seems best for the algorithm is as thus:
training window : 6 months
SMA short: 6 days
SMA long: 150 days
Cummulative return plot image name: svm_plot_6_short_150_long.png



Evaluate a New Machine Learning Classifier


Answer the following questions: Did this new model perform better or worse than the provided baseline model? 

It did perform better than the traditional model provided up to 2020, but 2021 prediction seems way off the actual return.

Did this new model perform better or worse than your tuned trading algorithm?

It performs better, it seems like it predict the ideal result of the actual return up to 2020, but for 2021 it seems to be far off in accuracy compared to the tuned algorithm. So I would say the tuned algorithm is better as it predicts closely to the actual return through the whole years.
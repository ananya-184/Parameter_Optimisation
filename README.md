# Parameter Optimisation
## Problem Statement
Choose any multi-class dataset from UCI library. Dataset size must have rows between 5k and 30k. Divide the dataset into 70-30 for training and testing with 10 different samples. Optimize the SVM for every sample with 100 iterations and report the best parameters as shown in Table 1. Plot the convergence graph for the sample whose accuracy is maximum as shown in Figure 1. 

## Dataset Used
[Dry Bean](https://archive.ics.uci.edu/dataset/602/dry+bean+dataset)
Images of 13,611 grains of 7 different registered dry beans were taken with a high-resolution camera. A total of 16 features; 12 dimensions and 4 shape forms, were obtained from the grains.

## About Parameter Optimisation
Parameter optimization, also known as hyperparameter tuning, is a crucial step in machine learning model development. It involves finding the best set of hyperparameters for a given machine learning algorithm to optimize its performance on a specific dataset.

## Comparative performance of Optimised-SVM with different samples
| Sample | Best Accuracy | Best Kernel | Best Nu | Best Epsilon |
|--------|---------------|-------------|---------|--------------|
| S1     | 0.2738        | poly        | 0.0042  | 0.0584       |
| S2     | 0.2738        | rbf         | 0.5005  | 0.2004       |
| S3     | 0.2689        | rbf         | 0.8394  | 0.9629       |
| S4     | 0.2372        | rbf         | 0.2994  | 0.4927       |
| S5     | 0.2567        | rbf         | 0.1199  | 0.4537       |
| S6     | 0.1516        | poly        | 0.9484  | 0.9200       |
| S7     | 0.2249        | rbf         | 0.2923  | 0.4514       |
| S8     | 0.2200        | rbf         | 0.1372  | 0.4763       |
| S9     | 0.2836        | poly        | 0.9883  | 0.1702       |
| S10    | 0.0293        | sigmoid     | 0.1866  | 0.8548       |


## Convergence Graph
[![line-plot.png](https://i.postimg.cc/rmyxbh6j/line-plot.png)](https://postimg.cc/wtP1RQjR)

The last iteration seems to be an anomaly which we can ignore.

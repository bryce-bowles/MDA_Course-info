# SCMA 648 Business Data Analytics

Professor: Dr. Paul Brooks

hone: 828-1540

Email: jpbrooks@vcu.edu

Techniques and skills for leveraging real-world data to support decision-making using computational software. Topics include the analytics workflow, data preparation, visualization, cluster analysis, predictive modeling, and learning-enabled optimization.

Texts:
*	Camm, J.D., Cochran, J.J., Fry, M.J., Ohlmann, J.W., Anderson, D.R., Sweeney, D.J., Williams, T.A. Business Analytics, 3rd Edition. Cengage, 2019. Available via Cengage Unlimited. 4th Edition not available via Cengage Unlimited, but available as an eBook.
*	James, G., Witten, D., Hastie, T., Tibshirani, R. An Introduction to Statistical Learning with Applications in R. Springer, 2017. Available online: http://faculty.marshall.usc.edu/gareth-james/ISL/ISLR\%20Seventh\%20Printing.pdf
*	Tan, P.-N., Steinbach, M., Karpatne, A., Kumar, V. Introduction to Data Mining, 2nd Edition. Pearson, 2019. Chapters available online: https://www-users.cs.umn.edu/~kumar001/dmbook/index.php
*	Grolemund, G. and Wickham, H. R for Data Science. O'Reilly, 2017. Available online: https://r4ds.had.co.nz/.
*	Leemis, L.M. Learning Base R. Self-published, 2015.

Course Software: R

Skills Targeted for Improvement:
*	Problem formation: Ability to translate a decision problem into an analytics task.
*	Analytics implementation: Ability to choose appropriate methods to support an analytics task.
*	Computer software skills: Ability to manipulate software to derive information from data.
*	Technical communication: Ability to summarize and communicate results of an analytics investigation.

Course Topics: Introduction to Analytics, Descriptive Analytics (Data Preparation for Analytics, Data Exploration and Visualization, Cluster Analysis and Principal Component Analysis); Predictive Analytics (Introduction to Classification, Empirical Evaluation of Classification, Choosing the Best Classification, Beyond Linear Regression); and Prescriptive Analytics (Using Machine Learning Predictions as Inputs to Optimization Models) 


## Projects Completed: 
Business Data Analytics (Machine Learning, Classification Trees, Regression, Random Forests, Support Vector Machines, etc.)

* :star: [Alchemy Broker Analysis Project](https://github.com/bryce-bowles/alchemy-broker-modeling.git):  Performed segmentation analysis and predictive modeling on insurance broker performance to conclude a random forest model (highest AUC of 73%) predicted whether 2020 Gross Written Premium will increase or decrease from 2019 with a misclassification rate of 35%. Four classification models (classification trees, logistic regression, random forests, and support vector machines) were built, evaluated, and then tuned for prescriptive measures to analyze broker performance. Explored, visualized, and described five groups of brokers using principal component analysis.
* :star: :star: [Lending Club Data Analytics  in R](https://github.com/bryce-bowles/lending-club.git): Topics include the analytics work
flow, data preparation, visualization, cluster analysis, predictive modeling, and learning-enabled optimization. The Lending Club data is a mix of numeric, character, factor, and date data.
  1. [**Importing the data**](https://github.com/bryce-bowles/lending-club/tree/main/1_importing_data)  | To an acceptable format to use in r.
  2. [**Data Prep**](https://github.com/bryce-bowles/lending-club/tree/main/2_Data_Preparation) | Slicing, summarizing, missing values, aggregating, descriptive statistics, histograms, log transformation due to skewdness, normalizing and box plot of interest rate for each loan status
  3. [**Visualization**](https://github.com/bryce-bowles/lending-club/tree/main/3_visualization) | Histograms, log transformation due to skewdness, normalizing, box and whisker plot, Mosaic Plot, scatter plot, 3D Scatter, time series
  4. [**Cluster_pca**](https://github.com/bryce-bowles/lending-club/tree/main/4_cluster_pca) - Cluster Analysis and Principal Component Analysis in R (Cluster Dendrogram, silhouette plot, evaluating 3D clusters etc.) | ([:star:Assignment Report](4_cluster_pca/4_Assignment-3_cluster_pca.pdf) - Performed a Kmeans cluster analysis to identify 7 groups or clusters of the borrowers by income, loan amount, employment length, home ownership status, and debt-to-income ratio. Included Data Preprocessing and Removing Outliers.) 
  5. [**Classification**](https://github.com/bryce-bowles/lending-club/tree/main/5_classification) | Logistic Regression and Classification Trees
  6. [**Evaluating Classification Methods in R**](https://github.com/bryce-bowles/lending-club/tree/main/6_class_eval) - A/B testing or partitioning data, Logistic Regression, Classification Trees, ROC Curves, AUC, Categorical Variables with Many Levels | ([:star:Assignment Report](6_class_eval/6_Assignment4.pdf) - Built a logistic regression model and a classification tree model for predicting the final status of a loan based on various variables available. Confusion matrix and misclassification rate for each model for a test dataset. Variables that appear to be important for predicting outcome. Plotted and described the ROC curves and AUC for the four models.) 
  7. [**Other Classification Methods in R**](https://github.com/bryce-bowles/lending-club/tree/main/7_other_class) | Fitting Models, Random Forest, Support Vector Machine, Neural Networks and ROC Curves
  8. [**Choosing the Best Classifier**](https://github.com/bryce-bowles/lending-club/tree/main/8_Choosing_the_best_classifier)
  9. [**Regression Models**](https://github.com/bryce-bowles/lending-club/tree/main/9_regression) | Linear Regression, Regression Tree
  10. [**Optimization**](https://github.com/bryce-bowles/lending-club/tree/main/10_optimization) | Calculating Estimated Return, Build Predictive Models and Determining an Optimal Portfolio
* [Business Data Analytics Overview](https://github.com/bryce-bowles/business-data-analytics.git): Terms, classification models, test and training dataset splits, logistic regression models, classification tree models, ROC curves, AUC, confusion matrix, support vector machines, variance, bias, leakage, MAE and RMSE, R squared, LASSO approach (penalty on the coefficients) etc.
 

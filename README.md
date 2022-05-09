# Home-credit

This Home Credit Default Risk project is all about being able to predict which application is able to repay the loan. While there were many different data files to work with such as the Bureau ( client's previous loans from other institutions), Bureau_balance ( Monthly balance of credits in the credit Bureau), and POS_CASH_balance ( Monthly balance of client's previous loans in Home Credit). I ended up using only the application train and testing data for this project (The main tables with train and test samples with the Target feature) . 

# Model
When I was working on building the model, I used the random undersampler to correct the imbalance of data. 
I also used LGBMClassifier ( Light Gradient Boosted Machine) for the boosting algorithm.

- Fiona

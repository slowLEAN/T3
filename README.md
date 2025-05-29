This code demonstrates both simple and multiple linear regression using the housing price dataset.
Simple linear regression predicts house price based on a single feature: the area of the house.
Multiple linear regression uses several features together — area, bedrooms, bathrooms, stories, and parking — to predict price.
The dataset is split into training and testing parts for both cases. Models are trained on the training data, then used to predict prices on the test data.
The code prints the learned coefficients (how much each feature affects price) and the intercept (baseline price). It also calculates error metrics (Mean Absolute Error and Mean Squared Error) to evaluate how well the models predict prices.
Finally, it plots:
For simple regression: actual prices vs. area with the fitted regression line.
For multiple regression: actual prices vs. predicted prices to visualize prediction accuracy.
This helps understand how adding more features improves the prediction compared to using just one.

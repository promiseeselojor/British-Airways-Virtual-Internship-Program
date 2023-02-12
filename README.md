# British Airways Data Science Virtual Internship Program

This GitHub repository contains a project focused on scraping review data from the web and analyzing it to uncover insights about an airline. The data was collected from the website Skytrax and was cleaned and prepared for analysis.

The analysis includes topic modeling, sentiment analysis, and wordclouds. The results of the analysis were summarized in a single PowerPoint slide, including visualizations and metrics to provide key points.

Additionally, the dataset was prepared for predictive modeling, and a Linear Discriminant Analysis model was trained using pycaret to predict customer bookings.

The model's performance was evaluated using cross-validation and appropriate evaluation metrics.

The findings were summarized in a single PowerPoint slide and submitted in the repository. This project was completed using Python and the Jupyter Notebook provided in the resources section.

I have decided to choose the Linear Discriminant Analysis (LDA) model as the most suitable option for this problem. This is due to its good recall score, AUC, and accuracy of 72.85%, which are the key metrics that matter in this scenario. Despite the target variable imbalance, accuracy is not the only factor that I am considering in this decision.

The Extra Tree Classifier algorithm has the highest accuracy of 84.45%, but its recall score is low. This results in a high number of false negatives, where the model predicts that a customer will not book a holiday with the airline, but in fact, they do. In this case, minimizing false negatives is a priority as it is more costly for the business to miss out on potential bookings.

Therefore, it is more beneficial for the model to have a low number of false negatives and predict that a customer will book a holiday, even if this results in a lower accuracy. In this way, the business can maximize its potential revenue and minimize its losses.

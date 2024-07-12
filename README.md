# oibsip_5

# PROBLEM:

Sales prediction means predicting how much of a product people will buy based on factors such as the amount you spend to advertise your product, the segment of people you advertise for, or the platform you are advertising on about your product.

# OBJECTIVE:

To predict the future of sales with every step they take to manipulate the cost of advertising their product using ML concepts.

# KEY INSIGHTS:

# 01.Data Loading and Preparation:

Mount Google Drive: Mounted Google Drive to access the dataset.

Load Dataset: Loaded the dataset Advertising.csv from Google Drive.

Initial Exploration: Checked for null values (none found) and displayed the dataset's shape and summary statistics.

# 02.Exploratory Data Analysis (EDA):

Correlation Analysis: Plotted a heatmap to visualize correlations between numerical columns.

Distribution and Outliers: Visualized distributions and checked for outliers using histograms and boxplots.

Pairwise Relationships: Explored pairwise relationships between numerical columns using scatter plots and pair plots.

# 03.Data Preprocessing:

Drop Columns: Removed the Unnamed: 0 column as it was unnecessary for analysis.

Scaling Data: Applied MinMax scaling to normalize numerical features.

Feature and Target Split: Separated features (X) and target (y) columns for modeling.

# 04.Model Building and Evaluation:

Model Selection: Chose K-Nearest Neighbors (KNN) Regression for prediction.

Train-Test Split: Split data into training and testing sets.

Model Evaluation: Evaluated model performance using Mean Squared Error (MSE) and R-squared scores.

# CONCLUSION: 

The analysis of the advertising dataset reveals that TV and Radio advertising significantly impact sales, while Newspaper advertising has minimal influence. The K-Nearest Neighbors Regression model showed strong performance in predicting sales based on advertising expenditures, suggesting businesses should prioritize TV and Radio for higher returns.

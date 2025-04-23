# Click_Stream

🔹 Data Preprocessing & Cleaning

Dataset Used: Train.csv for model training and Test.csv for validation.

Handling Missing Values: Used mean/median for numerical features and mode for categorical.

Feature Encoding: Applied One-Hot Encoding and Label Encoding for categorical variables.

Feature Scaling: Standardized numerical data using MinMaxScaler or StandardScaler.

🔹 Exploratory Data Analysis (EDA)

Data Visualization: Used bar charts, histograms, and pair plots for insights.

Session Analysis: Examined session duration, page views, and bounce rates.

Correlation Analysis: Identified relationships between variables via heatmaps.

Time-based Analysis: Extracted hourly, daily, and seasonal trends in user behavior.

🔹 Feature Engineering

Session Metrics: Created session length, click counts, and time spent per category.

Clickstream Patterns: Tracked user browsing paths to uncover behavioral trends.

Behavioral Metrics: Included bounce rates, exit rates, and revisit patterns.

🔹 Balancing Techniques for Classification

Imbalance Check: Analyzed class distribution (Converted vs. Not Converted).

Oversampling: Used SMOTE to generate synthetic samples for minority class.

Undersampling: Randomly removed majority class samples for balance.

Class Weight Adjustment: Adjusted weights during model training.

🔹 Model Building

Classification Models: Implemented Logistic Regression, Decision Trees, Random Forest, XGBoost, and Neural Networks.

Regression Models: Used Linear Regression, Ridge, Lasso, Gradient Boosting Regressor for revenue prediction.

Clustering Models: Performed K-Means, DBSCAN, and Hierarchical Clustering for segmentation.

Pipeline Automation: Used Scikit-learn Pipelines for data preprocessing, scaling, model training, and evaluation.

🔹 Model Evaluation & Deployment

Streamlit App: Developed an interactive web app for real-time predictions, revenue estimation, and clustering visualizations with CSV upload and dynamic charts.


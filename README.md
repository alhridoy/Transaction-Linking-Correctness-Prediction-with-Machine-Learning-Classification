# Transaction-Linking-Correctness-Prediction-with-Machine-Learning-Classification

Undertook a machine learning classification task to predict the correctness of linking between payable and payment transactions, leveraging features such as payable and payment amounts, document types, account types, payment directions, and time differences.

Conducted exploratory data analysis (EDA) to analyze the dataset, including the distribution of the target variable and detailed examination of feature distributions and types. Applied preprocessing techniques, such as dropping irrelevant columns, handling missing values, and converting datetime features.

Utilized OneHotEncoder for categorical feature encoding, split the data into training and testing sets, and trained a Random Forest Classifier model using GridSearchCV for hyperparameter tuning. Evaluated the model's performance using accuracy, F1-score, and confusion matrix, visualizing the results with error bars for different maximum depths.

    Loading the Dataset: 
    The dataset is loaded using pandas.read_csv().
    
    Data Preprocessing: 
    In this case, the dataset does not have missing values, but the code is prepared to handle them if necessary.
    
    Feature Engineering:
    You can add any additional feature engineering steps if needed.
    
    Splitting the Data: 
    The data is split into training and testing sets. The stratify=y parameter ensures that the class distribution is maintained in both the training and testing sets.
    
    Standardizing the Features: 
    Standardizes the feature values using StandardScaler.
    
    Training and Evaluating Models: 
    Trains and evaluates three machine learning models (Logistic Regression, Decision Tree, and Neural Network).
    
    Visualization: 
    Plots confusion matrices for each model to visualize their performance


    Feature Engineering Steps:
    Time-based features:

    Hour: 
    Extracts the hour of the day from the Time column.
    
    Day: 
    Extracts the day of the week from the Time column.
    Amount-based features:

    LogAmount: 
    Applies a logarithmic transformation to the Amount column to reduce the skewness of the distribution.
    
    Dropping unnecessary columns: 
    The original Time and Amount columns are dropped after creating new features.
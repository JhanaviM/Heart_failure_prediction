# Heart_failure_prediction
The problem is to predict whether a patient has heart disease or not based on the given dataset. The dataset contains various features related to the patient's age, sex, chest pain type, resting blood pressure, cholesterol levels, fasting blood sugar, resting electrocardiogram results, maximum heart rate achieved, exercise-induced angina, oldpeak (ST depression), and the slope of the peak exercise ST segment. The target variable is the presence of heart disease, where 1 represents the presence of heart disease and 0 represents a normal condition.

👩‍💻 Dataset -
https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction

📌 Tasks -
1- Are there any missing values in the dataset? If so, how will you handle them? What is the distribution of heart disease and normal cases in the dataset? Is the dataset balanced or imbalanced?
2- How does the occurrence of heart disease vary with different input features (age, gender, hypertension, diabetes, etc.)? Create visualizations such as bar plots or boxplots to compare their distributions?
3- Can you identify any outliers in the dataset, particularly for numerical features like age, resting blood pressure, cholesterol levels, maximum heart rate achieved, and oldpeak? How are you planning to handle them?
4- Are there any correlations between the different features and the presence of heart disease? Visualize it using a heatmap or correlation matrix. Determine if any feature(s) can be dropped based on their relationship with the target variable.
5- Can you perform feature encoding or transformation on categorical variables like sex, chest pain type, resting ECG, and exercise-induced angina? Which encoding technique would be most suitable?

Working in file - 
- The first step was to perform Exploratory Data Analysis (EDA) on the dataset to clean and make the data suitable enough to perform all the subsequent tasks.
- Next we perform Classification/Regression on the transformed dataset. This involves data preprocessing (as per requirements), feature engineering, splitting the dataset(train - test split), fine tuning the model and making predictions based on the results.
- After applying the Logistic Regression model , the final calculated accuracy of the model is 83.67% 

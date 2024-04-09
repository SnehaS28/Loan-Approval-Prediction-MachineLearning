# Loan-Approval-Prediction

When it comes to deciding whether the applicant’s profile is relevant to be granted a loan or not, banks have to look after many aspects.
Predicting loan approval is a common application of machine learning in the financial industry. To create a machine learning model for loan approval prediction, I have  followed  the steps below:

1. Data Collection and Preprocessing:
- Gathered historical loan data, which includes credit history & both approved and denied loans.
- Clean and preprocess the data by handling missing values, encoding categorical variables, and scaling/normalizing numerical features.

2. Exploratory Data Analysis:
- Check the number of rows and columns, data types, and the presence of missing values.
- Examine the distribution of the target variable, which is typically whether a loan was approved or denied. Creating a bar plot or pie chart to visualize the distribution etc.
- Explore the distribution of individual features, both numerical and categorical. Use histograms, box plots, or bar charts to visualize the data. Identify outliers using box plots.
   
3. Data Splitting:
- Split your data into training and testing sets to evaluate your model's performance.

4. Model Selection:
- Choose an appropriate machine learning algorithm. I have used common algorithms for this classification problem like Logistic Regression, Decision Tree Classifier, Random Forest Classifier, and KNeighbors Classifier.
5. Model Training:
- Train your chosen model on the training data.

6. Model Evaluation :
- I have used appropriate metrics to evaluate the model's performance, such as accuracy, precision, recall, and F1-score. It's important to consider the specific requirements and constraints of the application.

7. Sampling :
- Checked the classification report whether there is an imbalance in the dataset or not. The difference was high, so I used the Oversampling Method, generated a random sample dataset, and then Train the Model on a new Dataset 

**Results**: The project achieves an accuracy of around 84% using a Random Forest Classifier model.
            





TASK 2 :PREDICTIVE ANALYSIS USING MACHINE

COMPANY NAME : CODTECH IT SOLUTIONS

NAME : SANJANA D

INTERN ID : CT08RDF

DOMAIN : DATA ANALYSIS

DURATION : 4 WEEKS

MENTOR : NEELA SANTHOSH KUMAR

EXPLANATION :
This code performs feature selection, model training, and evaluation for predicting ratings based on city and best time to visit. It begins by importing necessary libraries such as NumPy, Pandas, Matplotlib, Seaborn, and Scikit-learn. The dataset is loaded using Pandas and displayed to examine its structure. The selected features, "City" and "Best Time to visit," are extracted as independent variables (X), while "Rating" serves as the target variable (y). Since these features are categorical, they are converted into numerical format using one-hot encoding, ensuring that the model can process them effectively.
Next, the dataset is split into training and testing sets using an 80-20 ratio to ensure proper model evaluation. A Linear Regression model is then trained on the training data. Once the model is trained, predictions are made on the test data. The model's performance is assessed using the Mean Squared Error (MSE), a common metric for regression tasks, which is printed to evaluate the accuracy.
Finally, the actual and predicted ratings are visualized using a bar chart, making it easier to compare model performance. This helps in identifying potential discrepancies between predictions and real values.

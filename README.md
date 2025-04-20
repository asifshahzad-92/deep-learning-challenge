# Deep-Learning-challenge
## Module 21 Challenge

**Preprocess the Data:**
Create a dataframe containing the charity_data.csv data, and identify the target and feature variables in the dataset.

![image](https://github.com/user-attachments/assets/558aed06-fe9d-4872-bb25-ab1a0a0a50df)

  The Target variable is `IS_SUCCESSFUL`.
  The Feature Variables include : `APPLICATION_TYPE` , `AFFILIATION`, `CLASSIFICATION`, `USE_CASE`,
  `ORGANIZATION`, `STATUS`, `INCOME_AMT`, `SPECIAL_CONSIDERATIONS`, `ASK_AMT`.
  

Drop the EIN and NAME columns 

![image](https://github.com/user-attachments/assets/355519fc-b6d6-4187-a56b-b131bb968ed1)


Determine the number of unique values in each column

![image](https://github.com/user-attachments/assets/1d762b8b-12bc-40df-a68b-f34eb5699e28)


For columns with more than 10 unique values, determine the number of data points for each unique value

![image](https://github.com/user-attachments/assets/e5974a5b-986c-4bd8-8cb4-c7a5b4d1faf3)


Create a new value called Other that contains rare categorical variables

![image](https://github.com/user-attachments/assets/4c2202c5-2cf2-4bf5-9b2c-e56c00e7e709)


Create a feature array, X, and a target array, y by using the preprocessed data and Split the preprocessed data into training and testing datasets.

![image](https://github.com/user-attachments/assets/6245e792-f00e-465a-8ef9-7f9011f45469)


Scale the data by using a StandardScaler that has been fitted to the training data.

![image](https://github.com/user-attachments/assets/4219bb1a-ddc5-4d13-bf8e-03c09cf29c64)


**Compile, Train and Evaluate the Model.**

Create a neural network model with a defined number of input features and nodes for each layer. Create hidden layers and an output layer with appropriate activation functions

![image](https://github.com/user-attachments/assets/1d02ccaf-4715-4f2b-8b46-6b1f4ec38f09)


Check the structure of the model

![image](https://github.com/user-attachments/assets/ab8edbac-1ec9-4bfc-8e5a-041d94dae848)


Compile and train the model

![image](https://github.com/user-attachments/assets/b0efc91b-069f-4f10-a4b8-c23a3f3a62ec)

Evaluate the model using the test data to determine the loss and accuracy

![image](https://github.com/user-attachments/assets/20d762d6-70bc-4b3a-af08-8d4fd3965a1f)


Export your results to an HDF5 file named AlphabetSoupCharity.h5

![image](https://github.com/user-attachments/assets/09199022-6b08-4d5a-930f-f1ad04577434)


Optimize the Model

Repeat the preprocessing steps in a new Jupyter notebook

Create a new neural network model, implementing at least 3 model optimization methods

Save and export your results to an HDF5 file named AlphabetSoupCharity_Optimization.h5


Write an analysis that includes a title and multiple sections, labeled with headers and subheaders

Format images in the report so that they display correction

Explain the purpose of the analysis

Answer all 6 questions in the results section

Summarize the overall results of your model

Describe how you could use a different model to solve the same problem, and explain why you would use that model

# Past-Loans
In this we will evaluate various ML algorithms to check which one gives us the best results for the loan records.  

# List of Contents  
1. [Installation](#installation)  
2. [Data](#data)  
3. [Exploratory Data Analysis](#exploratorydataanalysis)  
4. [Classification](#classification)  
5. [Model Evaluation](#modelevaluation)    
6. [License](#license)  

## Installation  
The following libraries are installed in the notebook.  
-**`pandas`**  
-**`numpy`**  
-**`matplotlib`**  
-**`preprocessing`**  

## Data  
The dataset is about past loans. The loan data set includes details of 346 customers whose loans are paid off or defaulted.It includes the following fields.  
-Loan_status  
-Principle  
-Terms  
-Effective_date  
-Due_date  
-Age  
-Education  
-Gender    

## Exploratory Data Analysis
In this process we will explore the data to draw insights about the data.  
We will answer questions like....  
1) Which gender is likely to default?  
2) On which day of the week more customers apply for loan?  
Once we get the necessary insights we perform one hot encoding technique and normalize the data so that we can train the dataset on classification algorithms.  

## Classification
Using the various classification algorithms we train the dataset. The classsification algorithms are:  
1) K Nearest Neighbor(KNN)  
2) Decision Tree  
3) Support Vector Machine  
4) Logistic Regression 

## Model Evaluation
For model evaluation we will be using three models, they are:  
1) Jaccard Similarity Score  
2) Log loss  
3) F1 Score  

We will measure the values using the above mentods on all the classification algorithms mentioned above. 

## License
License under [MIT License](https://github.com/TarunGoli/Past-Loans/blob/master/LICENSE)

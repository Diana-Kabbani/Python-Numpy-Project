## Structure of the working process
1. *Introduce the project*
    1. The data scientist team wants to create a credit risk model, which estimates the probability  of default for every personal account. Our mission is to  take the raw dataset and prepare it for the model. The data scientist informed us what type of data is stored, and how to clean and preprocess it.
2. *Tasks and responsibilities*
    1. The data set: loan-data.csv is a sample of a larger dataset that belongs to an affiliate bank based in the US. All the values are in dollars and we need to provide their **euro equivalent**
    2. **Every categorical variable** must be quantified : we need to change every text columns into numbers based on the information it contains. For some colums, like the issue_date column, it's quite straightforward, while for others it is not. For these columns, we only care whether it provided positive or negative connotations (dummy variable that hold the value of 0 or 1). 
    3. **Missing information suggest the worst case scenario** : there are lower chances of getting a loan of the person did not provie all the information. If the information is not available, we will thus assume the worst. The team is providing us with **casting directions for each variable** in the dataset (min, max or some other value) when taking care of the missing data.
        1. Regressions that determine the probability of default only care if the candidate is in a stable financian condition. Therefere, the "Loan" column should contain a simply dummy indicator of whether the applicant is in a good (not defaulted) or bad  (defaulted) economic state
3. *Examine the dataset*
    1. Each row consists of information for the account of a loan candidate's application. Row= accounts, condidates, applications. 
    2. Each columns is a variable.
    3. Delimiter= ";"
4. *Cleaning and preprocessing of the data*
5. *Save the file as an external  .csv file*
6. *Pass it on to the data scientist*

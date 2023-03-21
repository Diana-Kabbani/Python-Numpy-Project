## Structure of the working process: 
1. *Introduce the project*
    1. Create a credit risk model, which estimates the probability  of default for every personal account
        1. Take the raw dataset and prepare it for the model. The data scientist informed us what data is stored, and how to clean and preprocess the value
2. *Tasks and responsibilities of each person in the data science team*
    1. dataset : loan data is a sample of a larger dataset that belongs to an affiliate bank based in the US --> All the values are in dollars and we need to provide their euro equivalent 
    2. Every categorical variable must be quantified : we need to change every text columns into numbers based on the info is contains. For some colums like the issue data it's quite straightforward (by month), for others we only care if it provided positive or negative connotatios( dummy variable that hold 0 or 1)
    3. Missing information suggest foul play -> lower chances of getting a loan: if the info is not available, we'll assume the worst. So the team is probiding us with casting directions for each variable (column) in the dataset (min, max or some other value) wheen taking care of the missing data
3. *Examine the dataset*
    1. Each row consists of information for the account of a loan candidate's applicatio. Row= accounts, condidates, applications. 
    2. Each columns is a variable.
    3. Delimiter= ";"
4. *Cleaning and preprocessing*
5. *Save the file as an external  .csv file*
6. *Pass it on to the data scientist*

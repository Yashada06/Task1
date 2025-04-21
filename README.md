21/04/2025

#Task 1
Project Dataset 1

Name : Diwali Sales Data
No. of Columns : 11251
Data Cleaning Tool : Python (Pandas)

Process did for data cleaning :

Used Python for Data Cleaning

1: Installed Python

2: Install Pandas Library

3: Import Pandas Library

4: Added my CSV file into Jupyter notebook
    using read_csv()

5: Display column by using
    df.info()

6: Null Values Checked ( sum () ) Counts the Null values 
   df.isnull().sum()

7: Drop null values
    df.dropna(inplace=True)

8: Print Duplicate Values
    print(df.duplicated())

9: Droped two Unwanted Columns (Status , Unnamed1)
    df.drop(['Status','unnamed1'] , axis=1, inplace=True)

 
 


#Task 1

Project Dataset 2

Name : Covid Worldwide Data
No. of Columns : 3000
Data Cleaning Tool : Python (Pandas)

Process did for data cleaning :

Used Python for Data Cleaning

1: Added my CSV file into Jupyter notebook
    using read_csv()

2: Display column by using
    df.info()

3: Null Values Checked ( sum () ) Counts the Null values 
   df.isnull().sum()

4: Drop null values
    df.dropna(inplace=True)

5: Print Duplicate Values
    print(df.duplicated())

6: Made Columns Upercase
    df.columns = df.columns.str.upper()

 

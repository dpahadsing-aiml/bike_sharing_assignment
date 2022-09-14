# Lending Club Case Study 

> Lending Club Case Study is an Explorative Data Analysis on the loan dataset of Lending Club (LC) with a view to find the strong influencing parameters to identify risky loan applicants, so that loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- It is required to understand the driving factors behind loan default, i.e. the variables which are strong indicators of default, so that a suitable decision can be made when a new application arrives at LC for loan.
- Dataset for loans issued between 2007 and 2011 in CSV format (loan.csv) along with a Data Dictionary in Excel file (data_dict.xlsx) is available in the repository. Meaning of variables as understood from LC's website et. al. has been incorporated in the data dictionary.
- The dataset after cleaning has also been stored in the repository in CSV format (loan_clean.csv) in case anyone wants to skip the data cleaning steps. **don't forget to import the libraries, which are at the beggining of the notebook**
- The analysis includes univariate, segmented univariate and bivariate analysis on the data
- A presentation (in PDF format) is also available in the repository to provide overview and key insights  


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Borrowering has an upward trend despite increase in interest rates  
- Loan Grade E, F & G are High Risk, High Return credits to High Income Borrowers 
- Very rich people also take loans and default
- Key drivers of loan default hav been identified as low income, high DTI, higher borrowing tendency etc. (details in the PDF and Notebook)
- LC can examine these key drivers for default during loan approval to reduce risks
- LC should use Credit Score benchmarking for loan approval decision


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used

#### Programming Language & Environment
- Python           - version 3.9.13
- Jupyter Notebook - version 6.4.12

#### Libraries
- numpy            - version 1.23.1  for array manipulation
- pandas           - version 1.4.3   for data manipulation
- matplotlib       - version 3.5.2   for plotting
- seaborn          - version 0.11.2  for plotting
- openpyxl         - version 3.0.10  for reading Excel file


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- To understand the meaning of the Variables and gain insight about the business, LC’s website (www.lendingclub.com) and other public websites (www.bankrate.com, www.investopedia.com etc.) were referred.


## Contact
Created by [@dpahadsing-aiml] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
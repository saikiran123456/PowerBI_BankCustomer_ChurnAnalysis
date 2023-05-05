# BANK Customer CHURN Analysis

Using PowerBI, Story has been created to solve the RBC Bank Customer CHURN Analysis case study

Real_Time Project Which was given by TechTip 24 , Complete Analysis using Excel, MySQL, PowerBI, Online PowerBI Dashboard Publishing, REFRESH Options, Gateway setup and Live PowerPoint Embed 

##* **Problem Statement :*
## Churn Analysis:

|Analyse the data and bring out few insights on the customer Churn.|

It is advantageous for banks to know what leads a client towards the decision to leave the company.
Churn prevention allows companies to develop loyalty programs and retention campaigns to keep as many customers as possible.


[POWERPNT_3o4LoSUi1x-output.webm](https://user-images.githubusercontent.com/37768258/236507997-43d99bfa-6b5b-46ce-a9f7-9f0be4a27134.webm)


|Visual|Insights|MicrosoftPowerBI-Service|

![chrome_aM4epRA2J9](https://user-images.githubusercontent.com/37768258/236509827-4a6e6bdd-0a45-4226-9e43-e7f41a139e7a.gif)



## 1)	Data Gathering:

Data assets to pull the data related to Bank customer and associated details.
ActiveCustomer.xlsx
Bank_Churn.csv
CreditCard.xlsx
CustomerInfo.csv
ExitCustomer.xlsx
Gender.xlsx
Geography.xlsx


## Data Dictionary (The complete understanding of Business)

1)	RowNumber—corresponds to the record (row) number and has no effect on the output.

2)	CustomerId—contains random values and has no effect on customer leaving the bank.

3)	Surname—the surname of a customer has no impact on their decision to leave the bank.

4)	CreditScore—can have an effect on customer churn, since a customer with a higher credit score is less likely to leave the bank.

5)	Credit score:
- Excellent: 800–850
- Very Good: 740–799
- Good: 670–739
- Fair: 580–669
- Poor: 300–579

6)	Geography(where the bank is and which location customers are)—a customer’s location can affect their decision to leave the bank.

7)	Gender—it’s interesting to explore whether gender plays a role in a customer leaving the bank.

8)	Age—this is certainly relevant, since older customers are less likely to leave their bank than younger ones.

9)	Tenure—refers to the number of years that the customer has been a client of the bank. Normally, older clients are more loyal and less likely to leave a bank.

10)	Balance—also a very good indicator of customer churn, as people with a higher balance in their accounts are less likely to leave the bank compared to those with lower balances.

11)	NumOfProducts(Bank offer diff products likes FD(fixedDepository), RD(RecurringDeposit), loans, —refers to the number of products that a customer has purchased through the bank. 
{ Which is better RD or FD?
The fixed and recurring deposits are very similar but can be differentiated by how money is invested. High-interest rates and a tax-saving facility are some of the best benefits of an FD. A recurring deposit is best for those who prefer to invest small amounts.}

12)	1HasCrCard—
Denotes whether or not a customer has a credit card. This column is also relevant, since people with a credit card are less likely to leave the bank(because they have to pay back their loans emi etc).
1 represents credit card holder
0 represents non credit card holder

13)	IsActiveMember—active customers are less likely to leave the bank.
1 represents Active Member
0 represents Inactive Member (If you are not doing transaction from debit/credit and doing transaction)

14)	 Estimated Salary—as with balance, people with lower salaries are more likely to leave the bank compared to those with higher salaries.

15)	Exited— whether or not the customer left the bank.
0 represents Retain   (Still they are with the bank)
1 represents Exit

16) Bank DOJ — date when the Customer associated/joined  with the bank




### End To End - TASKS Performed - Life Cycle of a Data Analyst

- Requirement Gathering (BRD / FRD)
- Data Collections (Database / CSV/ Excel)
- Data Modelling
- Data Cleaning / Data Pre-processing
- UI Report (Charts / Custom Charts)
- Additional Information (DAX Calculations)
- RLS


• Created a Workspace (Provided workspace access within team)

• Published
• Dashboard
• Gateway
• Schedule Refresh
• Added Roles, Subscribe, alerts
• Shared the Report
• Created App and Shared


- Part 1
• Requirement Gathering / Data Collection
- Part 2
• Data transformations / Data Computations
- Part 3
• Power BI Reports / UI
- Part 4
• Dashboard / Publishing

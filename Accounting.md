# Accounting

## Financial Reporting
* Balance Sheet
* Income Statement
* Statement of Cash Flows
* Statement of Stockholders' Equity
```
Balance sheet at 12/31/2019
Assets                 = Liabilities + Stockholders' Equity
Cash + Non-cash assets = Liabilities + Contributed Capital + Retained Earnings
 |                                                |                  |
 |                                                |                  |
 Statement of Cash Flows                          |           Income Statement
 for the year ended 12/31/2020                    |           for year eneded 12/31/2020
 |                                                |                  |
 |                                     Statement of SE(DELTA[CC+RE]) |
 |                                     for year ended 12/31/2020     |
 |                                                |                  |
 |                                                |                  |
Cash + Non-cash assets = Liabilities + Contributed Capital + Retained Earnings
Assets                 = Liabilities + Stockholders' Equity
Balance sheet at 12/31/2020
```
Balance Sheet records the financial status of a specific date, and the other three ones reflect changes in a period of time, e.g. a fiscal year.
## Balance Sheet Equation
Asset = Liability + Stockholders' Equity  
* Resource = Claims on Resources by Outsiders(Creditors) and Owners
* Must always be balanced
* Changes of Cash Flow, Income, and SE are summarized in IS, SCF, and SSE as below

Cash Asset + Non-Cash Asset = Liability + Contributed Capital + Retained Earnings  
* Statement of Cash Flows (IS) => Changes in Cash Asset
* Income Statement (SCF) => Changes in Retained Earnings
* Statement of Stockholders' Equity (SSE) => Changes in Stockholders' Equity  
```
Asset = Liability + Stockholders' Equity  
Asset = Liability + Contributed Capital + Prior Retained Earnings + Retained Earnings  
Asset = Liability + Contributed Capital + Prior Retained Earnings + Net Income - Dividends  
Asset = Liability + Contributed Capital + Prior Retained Earnings + Reveneue - Expense - Dividends
```
### Asset
* An asset is a resource that is expected to provide future economic benfits, i.e.
  * Generate future cash inflows
  * Reduce future cash outflows
* An asset is recognized when:  
  * It is acquired in a **past transaction or exchange** (e.g. sales amount would not be recognized as an asset if only a sales contract has been signed, as no transaction or exchange has occured yet, and account receivable would be recognized, because products have been delivered to customer)
  * The value of its future benefit can be measured with a reasonable degree of precision 

### Liability
* A liability is a claim on assets by "Creditors"(non-owners) that represents an obligation to make future payment of cash, goods, or services
* A liability is recognized when:
  * The obligation is based on **benefits or services recevied currently or in the past** (similar with asset, when employee signs a working contract with the company, the salary would not be recognized as a liability of the company, because the benefits or services provided by the employee has not occured yet, and account payable would be recognized as a liability, because supplier has already delivered inventory to the company, i.e. the company has already received the benefits from supplier)
  * The amount and timing of payment is reasonably certain
### Stockholders' Equity
* Stockholders' Equity is the residual claim on assets after settling claims of creditors (SE = Assets - Liability)
  * Also called "net worth", "net assets", "net book value"
* **Contributed Capital (arises from sales of shares)**
  * Common stock (par value)
  * Additional paid-in-capital (excess over par value)
  * Treasury stock (stock repurchased by company)
```
Company issues 10,000 shares of $5 par value stock for $15 cash per share

Dr. Cash (+A)                               150,000
    Cr. Common Stock-Par (+SE)               50,000
    Cr. Additional Paid in Capital (+SE)    100,000        
```
* **Retained Earnings (arises from operations)**
  * Accumulation of net income (revenue - expenses), less dividends, since start of business
  * Retained Earnings[END] = Retained Earnings[BEG] + Net Income - Dividends
### Dividends
* Not an expense
* Recorded as a reduction of retained earnings on the declaration date (creates a liability until payment date. The company keeps the cash corresponding to the dividends, which is the benefit received currently, till the payment date, therefore it is a liability to the owners during this period)  
```
Declaration date:
Dr. Retained earnings (-SE)        1,000
   Cr. Dividends payable (+L)      1,000
```
```
Payment date:
Dr. Dividends payable (-L)         1,000
   Cr. Cash (-A)                   1,000
```
## Debit and Credit Bookkeeping
### Debit Account and Credit Account
```
Assets = Liabilities + Stockholders' Equity  
Asset = Liability + Contributed Capital + Retained Earnings[BEG] + Revenue - Expense  
Asset + Expense = Liability + Contributed Capital + Retained Earnings[BEG] + Revenue  
```
* Every account on the **left side** of the balance sheet equation is called **Debit Account**.
* Every account on the **right side** is called **Credit Account**.
* In the last equation, **Expense** has been moved to the left side of the equation. This is to avoid the minus operation if we put it on the right side. **This makes Expense a Debit Account**. Expense needs to be deducted from Revenue when updating Retained Earnings and Income Statement.
* A similar account with Expense is **Accumulated Depreciation**, which accumulates the depreciation of tangible assets and needs to be deducted from assets when updating the balance sheet. **Accumulated Depreciation is a Credit Account.**
* **Typical Current Asset Account**: Cash, Marketable Securities, Account Receivable, Notes Receivable, Interest Receivable, Inventory, Prepaid Expenses(Deferred Expense)
* **Typical Long-Term Asset Account**: Land, Building, Accumulated Depreciation(Contra Asset, XA, Credit Account), Investments, Notes Receivable, Intangible Asset
* **Typical Liability**: Account Payable, Note Payable, Accrued Payable(Accrued Expenses), Unearned Revenue(Deferred Revenue)
* **Typical Stockholders' Equity**: Common Stock(at par), Additional Paid-in-Capital, Retained Earnings
### Debit(Dr.) and Credit(Cr.)
* Debit is an action which increases a Debit account and decreases a Credit account
* Credit is an action which decreases a Debit account and increases a Credit account
* **Every transaction must have at least one Debit and at least one Credit**
* In T-account bookkeeping, Debit is written on the left side of each account(no matter it is a Debit account or a Credit account) and Credit is written on the right side
```
Example: (First Journal entries, then T-account)
Transaction (1): Customer buys a product worth $1,000. Customer pays in cash directly.
Dr. Cash (+A)           1,000
    Cr. Revenue (+SE)   1,000

Transaction (2): Company buys raw material worth $2,000 from supplier. Company pays in cash directly.
Dr. Cash (-A)           2,000
    Cr. Inventory (-A)  2,000

Cash (Asset, Debit account)
-------------------------------
Beg. Bal.     0 |
      (1) 1,000 |               Transaction (1) increases Cash account by 1,000
                | 2,000 (2)     Transaction (2) decreases Cash account by 2,000
                |
-------------------------------
End Bal. (1,000)|               negative number is written in the format with parentheses

Revenue (Stockholders' Equity, Credit account)
-------------------------------
                | 0     Beg. Bal.
                | 1,000 (1)     Transaction (1) increases Revenue account by 1,000
                | 
                |
-------------------------------
                | 1,000   End Bal.

Inventory (Asset, Debit account)
-------------------------------
Beg. Bal.     0 |
      (2) 2,000 |               Transaction (2) increases Inventory account by 2,000
                | 
                |
-------------------------------
End Bal.  2,000 |          
```
To my understanding, the main reason to introduce Debit and Credit bookkeeping is to avoid negative numbers appearing on the ledger. This may avoid confusion like whether add or minus opeartion should be used when summarizing the transactions to get an account balance. Another benefit to use Debit and Credit (esp. with Journal entries) is that it is kind of a formalized language which presents the corresponding transaction in a standard way so that it could state clearly and efficiently how a transacton makes resources flow among two or more accounts.
### Three Fundamental Bookkeeping Equations
```
Assets = Liabilities + Stockholders' Equity  
Sum of Debit = Sum of Credit  
Account Balance[BEG] + Increase - Decrease = Account Balance[END]  
```
* These three equations must be balance at all times
* The balance sheet equation can be preserved through the use of Debits and Credits
* Account Balance is the difference between sum of Debits and sum of Credits for the account
```
Account Balance[Debit] = SUM[Debit] - SUM[Credit]
Account Balance[Credit] = SUM[Credit] - SUM[Debit]
```
### How to Analyze Transaction? How to record Journal Entries?
* Which specific asset, liability, stockholders' equity, revenue or expense account does the transaction affect? Normally starts from cash account if cash is involved in the transaction
* Does the transaction increase or decrease the affected accounts?
* Should the accounts be debited or credited?
* Always list Debit(Dr.) first and always indent Credit(Cr.)
## The Accouting Cycle
```
01/01/2020
    - Journalize and Post 
        + During the fiscal year, for every transaction, create Journal entries and post them to T-Account
12/31/2020

On 12/31/2020 (In reality, it can be 2 to 4 weeks after the end of the fiscal year)
    - Adjust Entries   
        + Adjust Accrued Revenue/Expense and Deferred Revenue/Expense
        + create Journal entries and post them to T-Account
    - Create Trial Balance Worksheet
        + Calculate account balance for all accounts based on T-Account
        + Copy all account balance on Trial Balance Worksheet
    - Create Income Statement for the year ended 12/31/2020
        + Copy all Revenue and Expense account balance on Income Statement, Expense in parenthesis
        + Calculate five major KPI: Revenue, Gross Profit, Operating Income, Pre-tax Income, Net Income
    - Create Balance Sheet 12/31/2020   
        + Calculate Retained Earnings account balance: RE[END] = RE[BEG] + Revenue - Expense (so-called closing entries for temporary account)
        + Copy all account balance on Balance Sheet
        + Calculate major KPI: Total Current Asset, Net PP&E, Intangible Asset, Total Asset, Total Current Liabiility, Total Liability, Total Shareholders' Equity, Total Liability and Shareholders' Equity
    - Create Statement of Cash Flow for the year ended 12/31/2020
        + Classify cash related transactions into three kind of cash flow bucket(Operation, Investing, Financial)
        + Use indirect method to create Cash Flow from Operations
        + Use direct method to create Cash Flow from Investing Activities and Cash Flow from Financing Activities
```
### Accrued Revenue/Expense and Deferred Revenue/Expense
```
Dr. Cash        --------------> Dr. Liability           Deferred Revenue
  Cr. Liability                   Cr. Revenue         
Dr. Asset       --------------> Dr. Expense             Deferred Expense
  Cr. Cash                        Cr. Asset         

-|----------------------------------|-----------------------------------|->
Cash                            Accounting                            Cash
Transaction                     Recogntion                            Transaction

Accrued Expense                 Dr. Expense     ------------> Dr. Liability
                                  Cr. Liability                 Cr. Cash
Accrued Revenue                 Dr. Asset       ------------> Dr. Cash
                                  Cr. Revenue                   Cr. Asset
```
Almost all tricks in accounting is resulting from the so-called **Accrual Accouting**. In Accrual Accounting, Revenue and Expense are recognized based on whether goods or services have been delivered (e.g. whether customer got benefit, whether emplyee made contribution, whether supplier delivered inventory), and they are not related with Cash Flow at all. One of the consequences of the Accural Accouting is that the Deferred/Accrued Revenue/Expense need to have adjustment entries at the end of a fiscal year (**Accouting Recognition**). 
### Statement of Cash Flows
```
Collections from customers -|                              |-  Payments to suppliers
                            |                              |-  Payments to employees
Receipts of interest and   -| --> Operating Activities --> |-  Payments of interest* and tax
dividends on investments*   |                              |-  Other operating disbursements

Divestiture of businesses  -|                              |-  Acquisition of businesses
Sale of PP&E & intangibles -| --> Investing Activities --> |-  Acquisition of PP&E & intangibles
Sale of investments        -|                              |-  Purchase of investments

Issue of new stock         -|                              |-  Payment of dividends*
Reissue treasury stock     -| --> Financial Activities --> |-  Purchase of treasury stock
Borrow money               -|                              |-  Payment of principal on debt
```
Under IFRS, interest and dividends received and paid (the activities marked with * in table above) may be classified as opearting, investing, or financing, as long as the booking habit of the company is consistent for years.
### Indirect Method for Cash Flow from Operations
```
- Start from Net Income
- Add Depreciation and Amortization
- Add(Minus) Loss(Gain) on sales of PP&E or investment
- Add(Minus) negative(positive) changes in non-cash current assets
- Add(Minus) positive(negative) changes in current liability
```
* Indirect Method is much more complicated than direct method. However, the benefit of using indirect method is that we can use Net Income and Cash Flow from Operations as benchmark to analyze the changes in various assets and liabilities, esp. the current assets and liabilities. This is a very critical approach in analyzing a company's operations.
* Loss(Gain) on sales of PP&E or investment is based on their book value. In case an asset is depreciated too fast, one may get gain when disposing it with the market value. Similarly, when it is depreciated too slowly, one may get loss.
* Direct Method is simply adding all revenues and deducting all cost in each of the cash flow bucket
### Free Cash Flow
```
Free Cash Flow = Cash Flow from Operation - CapEx(i.e. Investment in PP&E)
```
Investment in PP&E should at least cover the amount of Depreciation and Amortization, which represents the maintenance cost. The residual represents the expasion of the business.
## Ratio Analysis
### How to analyze a company's status based on its financial statements?
* **Time-Series Ratio Analysis**: Compare financial statements of last 3 to 5 years of this company
* **Cross-Sectional Ration Analysis**: Compare this company's status with other companies in the same industry
```
- Profitability
- Growth
    + Growth for basic financial metrics
    + Common size analysis on balance sheet
- DuPont Analysis
    + Profitability (Common size analysis on income statement)
    + Efficiency (Assets turnover)
    + Risk (Liquidity Ratios, Leverage Ratios)
```
### Profitability
```
ROE = Net income / Average Stockholder's Equity                                     // Average means (SE[BEG] + SE[END]) / 2
ROA = (Net income + (1 - tax rate) * Interest Expense) / Average Total Assets       // Net income adjustment for tax shield 
ROIC = Net operatin profit after taxes / Average invested capital
```
### Growth
* Basic financial metrics
  * Sales, Assets, Operating Income, EBITDA, Net Income, ...
* Growth Analysis (**Common Size Analysis on Balance Sheet**)
  * Use the percentage of Assets to exclude the fundamental growth factor of assets, so that the growth of each asset account can be revealed. Similar analysis method is applied for the liabilities.
### DuPont Analysis
```
ROE = Net Margin           * Assets Turnover  * Financial Leverage
ROE = (Net Income / Sales) * (Sales / Assets) * (Assets / Equity)
ROE = Profitability        * Efficiency       * Leverage
```
DuPont Analysis is a way to decode the ROE, and to find out the major cause for ROE growth, e.g. which one out of the three factors contributes most to ROE. Usually Profitability and Efficiency are considered to be a better way to achieve ROE growth. And then each of the three factors can be analyzed specificly by following ways documented below.
### Profit Margin Analysis (Profitability)
Use **Common Size Analysis on Income Statement** to find out the portion of each expense and income compared with sales, so that one can easily figure out the reason for a good net margin, e.g. sales price, COGS, SG&A, interest expense, tax expense.
### Turnover Analysis (Efficiency)
```
Asset Turnover = Sales / Average Total Assets
Fixed Asset Turnover = Sales / Average Net PP&E

A/R Turnover = Sales / Average Accounts Receivable
Inventory Turnover = COGS / Average Inventory
A/P Turnover = Purchases / Average Account Payable           // Purchases = Inventory[BEG] + COGS - Inventory[END]

Days Receivable = 365 / A/R Turnover
Days Inventory = 365 / Inventory Turnover
Days Payable = 365 / A/P Turnover
Net Trade Cycle = A/R Days + Invetory Days - A/P Days
```
* Days are used more often than Turover rate, because they are more intuitive
* Normally shorter A/R Days and Inventory Days are better, but when they are longer, it could also mean the company is expanding its business so that it purchased or produced more inventory based on optimistic expectation
* Similarly normally longer A/P Days is a better sign, but when it is shorter, it could also mean the company is expanding its business so that it purchased more inventory to get a discount from supplier
* Net trade cycle means the period which the company needs to borrow short-term debt to bridge its payment to supplier and money collection from customer. If the interest expense is higher than the discount from the supplier, then it does not make sense to have a long net trade cycle.
### Common Liquidity Ratios (Leverage, i.e. Risk)
Short-term (Ideally ratios would be over 1)
```
Current Ratio = Current Assets / Short-term Debt
Quick Ratio = (Cash + Receivables) / Short-term Debt
CFO Ratio = Cash from Operations / Average Current Liabilities
```
Interest coverage ratios (Ideally ratios would be over 1)
```
Interest Coverage = Operation Income before Depreciation / Interest Expense
Cash Interest Coverage = (Cash from Operations + Cash Interest Paid + Cash Taxes) / Cash Interest Paid
```
Long-term ((Ideally ratios would be less than 1, however it needs to compare with competitors)
```
Debt to Equity = Total Liabilities / Shareholders' Equity
Long-term Debt to Equity = Total Long-Term Debt / Total Stockholders' Equity
Long-term Debt to Tangible Assest = Total Long-Term Debt / (Total Assets - Intangible Assets)
```
## Account Receivable
### How to handle Bad Debt? (Allowance methods)
```
Transactions:
(1) (Credit Sales) BOC makes $10 in sales on account to each of three customers: Jordan, Dakota, and Peyton
(2) (Bad Debt Expense) At end of period, BOC estimates that $10 of sales will not be collected
(3) (Cash Collections) In the next period, BOC collects from Jordan and Peyton
(4) (Write-offs) After 90 days, BOC gives up on collecting from Dakota and writes-off the receivable
(5) (Recoveries + Cash Collections) After the write-off, Dakota wins the lottery and pays us $10

General Ledger:
                    Cash(A) + A/R(A) - Allowance for DA(XA) = Revenue(SE) - Expenses(E)
Time of sale                    30                                30
Adjusting entry                             10                                  10
Collection            20       (20)
Write-off                      (10)         (10)
Recovery                        10           10
Collection            10       (10)

A/R Ledger:
                    Account Receivable = A/R(Jordan) + A/R(Dakota) + A/R(Peyton)
Time of sale                30              10              10          10
Adjusting entry
Collections                (20)            (10)                        (10)
Write-off                  (10)                            (10)
Recovery                    10                              10
Collection                 (10)                            (10)

Journal entries:
(1) Dr. Account Receivable (+A)     30
      Cr. Sales (+R, +SE)           30
(2) Dr. Bad Debt (+E)                               10
      Cr. Allowance for Doubtful Accounts (+XA, -A) 10
(3) Dr. Cash (+A)                   20
      Cr. Account Receivable (-A)   20
(4) Dr. Allowance for Doubtful Accounts (-XA, +A)   10
      Cr. Account Receivable (-A)                   10
(5) Dr. Accounts Receivable (+A)                    10
      Cr. Allowance for Doubtful Accounts (+XA, -A) 10
    Dr. Cash (+A)                   10
      Cr. Account Receivable (-A)   10

T-accounts:
            Account Receivable (A)                   Allowance for Doubtful Accounts (XA)                        Cash (A)
---------------------------------------------       ---------------------------------------        -----------------------------------
Beg. Balance       |                                                 | Beg. Balance                 Beg. Balance           |
(1)Credit Sales 30 |                                                 |                                                     |
                   |                                                 | (2)Bad Debt Exp. 10                                 |
                   | (3)Cash Collections 20                          |                              (3)Cash Collections 20 |
                   | (4)Write-offs 10               (4)Write-offs 10 |                                                     |
(5)Recoveries 10   |                                                 | (5)Recoveries 10                                    |
                   | (5)Cash Collections 10                          |                              (5)Cash Collections 10 |

              Sales (R, SE)                                      Bad Debt (E)
---------------------------------------------       --------------------------------------- 
                   | (1)Credit Sales 30                                 |
                   |                                (2)Bad Debt Exp. 10 |
```
### How to estimate uncollectible accounts?
Percentage-of-sales method
* Step 1: use Credit sales to estimate Bad Debt Expense
* Step 2: use Bad Debt Expense to update End Balance of Allowance accounts
```
Accounts Receivable (A)                              Allowance for Doubtful Accounts (XA)
---------------------------------------------       ------------------------------------------
Beg. Balance 10,000 |                                               | 1,100 Beg. Balance
Credit sales 75,000 |                                               | ______ Bad Debt Expense
                    | 69,500 Cash collections                       |
                    | 500 Write-offs                 Write-offs 500 |
---------------------------------------------       ------------------------------------------
End Balance 15,000  |                                               | ______ End Balance

Bad Debt Expense = Credit sales * Estimated uncollectible percentage
                 = 75,000 * 2%
                 = 1,500
Allowance for Doubtful Accounts[END] = Allowance[BEG] + Bad Debt Expense - Write-offs
                                     = 1,100 + 1,500 - 500
                                     = 2,100
```
Aging-of-accounts-receivable method
* Step 1: use End balance of each A/R account to estimate End Balance of Allowance Accounts
* Step 2: use End balance of Allowance Accounts to update Bad Debt Expense
```
Accounts Receivable (A)                              Allowance for Doubtful Accounts (XA)
---------------------------------------------       ------------------------------------------
Beg. Balance 10,000 |                                               | 1,100 Beg. Balance
Credit sales 75,000 |                                               | ______ Bad Debt Expense
                    | 69,500 Cash collections                       |
                    | 500 Write-offs                 Write-offs 500 |
---------------------------------------------       ------------------------------------------
End Balance 15,000  |                                               | ______ End Balance

               A/R Balance      Estimated uncoll. perc.     Allowance Amount
-------------------------------------------------------------------------------
0-30 days        8,000              5%                            400
31-60 days       4,000              10%                           400
61-90 days       2,000              30%                           600
Over 90 days     1,000              50%                           500
-------------------------------------------------------------------------------
Totals          15,000                                          1,900

Allowance for Doubtful Accounts[END] = 1,900
Bad Debt Expense = Allowance for Doubtful Accounts[END] - Allowance for Doubtful Accounts[BEG] + Write-offs
                 = 1,900 - 1,100 + 500
                 = 1,300
```
### Bad Debt and the Indirect Method
```
Method(1)                               Method (2) (Net A/R = Gross A/R - Bad Debt Expense)    
-----------------------------------     -----------------------------------
Net Income                              Net Income
+   Bad Debt Expense                      
+/- Change in Gross A/R                 +/- Change in Net A/R
-----------------------------------     -----------------------------------
Cash Flow from Operating Activities     Cash Flow from Operating Activities
```
### Three Ways to Collect Cash from A/R more quickly
* Pledging
    * Use A/R as collateral to borrow money
* Factoring
    * Sell A/R at a discount that reflects an interest charge and risk of uncollectibility
* Securitization
    * Sell A/R to a seperate legal entity (Variable Interest Entity), which would then securitize the A/R
### A quick and dirty way to check Estimated Uncollectible Percentage
Since credit sales, write-offs, and bad debt expense may not be avaiable from financial reporting, a quick and dirty way to calculate the Estimate Uncollectible Percentage is like this:
```
Estimated Uncollectible Percentage = Allowance for DA / Gross A/R (i.e. Allowance for DA + Net A/R)
```
Use this way to compare the result for several years, and it would be helpful in finding out whether the company is manipulating this percentage so as to generate more net income.
## Inventory
### Inventory cost flows for a manufacturing firm
```
Transactions:
(1) Kirby purchased $865 of raw materials on account
(2) Kirby used $806 of raw materials inventory in manufacturing
(3) Kirby paid $524 cash for manufacturing labor
(4) Kirby paid $423 cash for power, heat, light, and other overhead
(5) Kirby recognized $81 of depreciation for plant equipment
(6) Kirby finished manufacturing goods that cost $1,960
(7) Kirby sold $2,862 of goods to customers on account
(8) The goods cost $1,938 to manufacture

Inventory cost flows:
Acquisition of                              Inventory Accounts                           Income Statement Accounts
materials and services
----------------------      ------------------------------------------------------      ---------------------------
Payables, Cash, or
Accumulated Depr.           Raw Materials               Finished Goods                  Cost of Goods Sold
------------------          -------------------------   --------------------------      ------------------
        |                   Beg. Bal. 110 |             Beg. Bal. 320 |                           |
        | 865 (1)               (1) 865   | 806(2)      (6) 1,960     | 1938 (8)        (8) 1,938 |
        |                   -------------------------   --------------------------
        |                   End Bal. 169  |             End Bal. 342
        |               
        |                   Work in Process
        |                   -------------------------
        |                   Beg. Bal. 265 |
        |                       (2) 806   |
        |                                 | 1,960 (6)
        | 524 (3)               (3) 524   |
        | 423 (4)               (4) 423   |
        |  81 (5)               (5)  81   |
        |                   --------------------------
        |                   End Bal. 139                                                SG&A Expense
        |                                                                               --------------------------
        | Selling costs     ----------------------------------------------------->      Selling costs |
        | Admin. costs      ----------------------------------------------------->      Admin. costs  |
```
Transaction (5) is considered as an asset in inventory account "Work in Process" instead of expense, because it is a necessary part of the manufaturing process.
### Invetory and COGS (LIFO vs. FIFO)
```
Cost of Goods Available for Sale = Cost of Goods Sold + Cost of Goods Held
--------------------------------   ---------------------------------------
Begin Inventory + New Inventory  =         COGS       + End Inventory
     (known)        (known)              (unknown)        (unknown)
```
```
LIFO vs. FIFO
                        Begin Inventory                 Purchases

2011:                   Sep 2010    Dec 2010        Feb 2011    Apr 2011    Oct 2011
Buy 3 units     FIFO    $25         $30             $35         $40         $45
                        Jan 2010    Mar 2010        Feb 2011    Apr 2011    Oct 2011
Buy 3 units     LIFO    $10         $15             $35         $40         $45

2011:
Sell 3 units    FIFO   |-------------------------------------| |--------------------|
                        COGS: $90                               End Inventory: $85
                LIFO   |----------------------|  |-----------------------------------|
                        End Inventory: $25        COGS: $120
```
* LIFO is only allowed in US. Even an international subsidiary which belongs to a US company could not use LIFO when computing COGS.
* Ending Balance of Invetory must be carried at the lower of historical cost (original cost) or fair market value (replacement cost).

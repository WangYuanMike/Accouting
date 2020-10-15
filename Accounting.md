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
* To my understanding, the main reason to introduce Debit and Credit bookkeeping is to avoid negative numbers appearing on the ledger. This may avoid confusion like whether add or minus opeartion should be used when summarizing the transactions to get an account balance. Another benefit to use Debit and Credit (esp. with Journal entries) is that it is kind of a formalized language which presents the corresponding transaction in a standard way so that it could state clearly and efficiently how a transacton makes resources flow among two or more accounts.
### Three Fundamental Bookkeeping Equations
Assets = Liabilities + Stockholders' Equity  
Sum of Debit = Sum of Credit  
Account Balance[BEG] + Increase - Decrease = Account Balance[END]  
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

On 12/31/2020
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
Nearly all tricks in accounting is resulting from the so-called **Accrual Accouting**. In Accrual Accounting, Revenue and Expense are recognized based on whether goods or services have been delivered (e.g. whether customer got benefit, whether emplyee made contribution, whether supplier delivered inventory), and they are not related with Cash Flow at all. One of the consequences of the Accural Accouting is that the Deferred/Accrued Revenue/Expense need to have adjustment entries at the end of a fiscal year (**Accouting Recognition**). 
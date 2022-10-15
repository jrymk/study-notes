# The Accounting Cycle: The Mechanics of Accounting

- Accounting cycle: The procedure for analyzing, recording, classifying, summarizing, and reporting the transactions of a business
- Business documents: Records of transactions used as the basis for recording accounting entries, include invoices, check stubs, receipts, and similar business papers and is often used (1) to confirm that a transaction has occured, (2) to establish the amounts to be recorded, and (3) to facilitate the analysis of business events.

## Sequence of the Accounting Cycle
1. Analyze transactions
2. Record the effects of transactions
3. Summarize the effects of transactions
	- posting journal entries
	- preparing a trial balance
4. Prepare reports
	- adjust entries
	- preparing financial statements
	- closing the books

- Events that cannot be reliably measured in monetary terms will not be reflected in the financial statements <span style="font-size:smaller;">[[Chapter 2#^monetary]]</span>
	- Information relating to the competitive environment, product development, and marketing and sales efforts is included in a company's annual report to stockholders, but not as part of the accounting information
- Determine if an arm's-length transaction has occurred <span style="font-size:smaller;">[[Chapter 2#^arms-length]]</span>
	- Company A signing a contrct with company B to purchase products in the future would not be reflected in the financial statements until the products are manufactured and delivered and company A has agreed to pay for them

## Step 1: Analyze transactions
- Account: An account is a specific accounting record that provides an efficient way to categorize similar transactions. You can think of an individual account as a summary of every transaction affecting a certain item (like cash). 
	- Examples of asset accounts: Cash, Supplies, and Office Equipment
	- Examples of liability accounts: Accounts Payable and Notes Payable
	- Examples of equity accounts: Capital Stock and Retained Earnings

### The Account Equation
Assets = Liabilities + Equity

The equation remains in balance
- Investment of $50,000 by owners
ASSET (Cash) +50,000, EQUITY (Capital Stock) +50,000
- Borrowed $25,000 from bank and signed a note to the bank:
ASSET (Cash) +25,000, LIABILITY (Notes Payable) +25,000
- Purchased $14,000 worth of supplies on credit
ASSET (Supplies) +14,000, LIABILITY (Accounts Payable) +14,000
- Purchased office equipment costing $15,000 for cash
ASSET (Office Equipment) +15,000, **ASSET (Cash) -15,000**

### T-account
- Abbreviated representation of an actual account
- Solve the problem of mixing + and - in one column by separating them for each account into separate columns, totaling each column, and then computing the difference between the columns

```
      The account title              ASSET     LIABILITY     EQUITY
--------------T----------------      --T--     ----T----     ---T---
  Debit (Dr.) |  Credit (Cr.)        + | -       - | +        - | +
```
- **Debit** ALWAYS means **left**, **Credit** ALWAYS means **right**
- Asset accounts
	- Debits refers to increases (+)
	- Credits refers to decreases (-)
	- Asset accounts usually have debit balances (+)
- Liability accounts
	- Debits refers to decreases (-)
	- Credits refers to increases (+)
	- Liability accounts usually have credit balances (+)
- Equity accounts
	- Debits refers to decreases (-)
	- Credits refers to increases (+)
	- Equity accounts usually have credit balances (+)
- **Debits always equal credits for every transaction**
	- Investment of $50,000 by owners
	ASSET (Dr.) +50,000, EQUITY (Cr.) +50,000
	- Borrowed $25,000 from bank and signed a note to the bank:
	ASSET (Dr.) +25,000, LIABILITY (Cr.) +25,000
	- Purchased $14,000 worth of supplies on credit
	ASSET (Dr.) +14,000, LIABILITY (Cr.) +14,000
	- Purchased office equipment costing $15,000 for cash
	ASSET (Dr.) +15,000, **ASSET (Cr.) +15,000**
	
	
### Expanded Accounting Equation
```
Assets = Liabilities + ( Equity                                                 )
       = Liabilities +   Capital Stock + ( Retained Earnings                    )
	   = Liabilities +   Capital Stock + (-Expenses) + (-Dividends) + (+Revenues)
```

- Revenues and expenses can be thought of as **temporary subdivisions of equity**
	- All revenue and expense accounts are **closed** into the retained earnings account at the end of the accounting cycle
- Revenues and expenses are just ways to **describe where the assets came from**, <span style="font-size:smaller;">see [[Chapter 2#Statement of Comprehensive Income]]</span>
- For example when we receive cash from providing G&S, we record an increase in ASSET (cash) and REVENUE to recognize that the source of the asset comes from providing G&S
- Increase in EXPENSE and DIVIDEND are **Debits**, as it means decrease in EQUITY, so when we purchase inventory, we 
	- debit (+) expense and credit (-) assets
	- debit (-) retained earnings and credit (-) assets
	- debit (-) equity and credit (-) assets
- When purchasing assets (inventory, supplies), it is not an expense
It is turned into expenses when it is sold (subtract cost of goods sold from assets)
When an expense happens, no assets are returned. When a revenue happens, no assets are gained

## Step 2: Record the Effects of Transactions
- Journal: An accounting record in which transactions are first entered, provides a chronological record of all business activities
	- Includes the dates of the transactions, the amounts involved, and the particular accounts affected by the transactions
	- Book of original entry
	- Provides a company with a complete record of its activities
	- Small companies might only have one journal called a "general journal"
	- Large companies might use special journals like "cash receipts journal" as well as a general journal

#### Format for Journalizing
- The debit entry is listed first
- The credit entry is listed second and is indented to the right
- The date and a brief explanation of the transaction are considered essential parts of the journal entry
- Dollar signs are usually omitted
- journalizing: Recording transactions in a journal
- journal entry: A recording of a transaction where debits equal credits, usually includes a date and an explanation of the transaction
- compound journal entry: A journal entry that involves more than one debit, more than one credit or both

---

General Journal Entry Format:
```
Date      Debit Entry                                                             xxx
            Credit Entry                                                                  xxx
			  Explanation
```

Making a journal entry involves
1. Identify which accounts are involved
2. For each account, determine if it is increased or decreased
3. For each account, determine by how much it has changed

#### Examples
- Borrowing money with interest (12 month note at 12% interest)
	- Cash (+ ASSET) Debit $2,000
		- Notes Payable (+ LIABILITY) Credit $2,000
- Paid first monthly payment on note with interest
	- Notes Payable (- LIABILITY) Debit $158
	- Interest Expense (- EQUITY-Retained Earnings-Expense) Debit $20
		- Cash (- ASSET) Credit $178

* Buying inventory
	* <span style="color: var(--green)">Inventory (+ ASSET) Debit $150</span>
		* <span style="color: var(--orange)">Cash (- ASSET) Credit $150</span>
* Selling half of the inventory for $90
	* <span style="color: var(--orange)">Cash (+ ASSET) Debit $90</span>
		* Sales Revenue (+ EQUITY-Retained Earnings-Revenue) Credit $90
	* <span style="color: var(--orange)">Cost of Goods Sold (- EQUITY-Retained Earnings-Expense) Debit $75</span>
		* <span style="color: var(--green)">Inventory (- ASSET) Credit $75</span>

<!---
Example:
```
 Date     Description                                              Post. Ref.   Debit  Credit
 
 2022
 July 1   Cash [+ ASSET]                                                        2,000
            Capital Stock [+ EQUITY]                                                    2,000
			  Issued 200 shares of capital stock at $10 per share
      
	  1   Cash [+ ASSET]                                                        2,000
	        Notes Payable [+ LIABILITY]                                                 2,000
			  Borrowed $2,000 from xxx bank, signing a 12-month
			  note at 12% interest
			  
	  5   Transportation Equipment [+ ASSET]                                      800
	        Cash [- ASSET]                                                                800
			  Purchased a used truck
	  
	  5   Machinery Equipment [+ ASSET]                                           250
	        Accounts Payable [+ LIABILITY]                                                250
		      Purchased a lawnmower on account
			  
	  5   Supplies [+ ASSET]                                                      180
	        Cash [- ASSET]                                                                180
			  Purchased supplies for cash
			  
	  7   Inventory [+ ASSET]                                                     150
	        Cash [- ASSET]                                                                150
			  Purchased inventory (shrubs) for cash
			  
	  9   Cash [+ ASSET]                                                          270
	      Accounts Receivable [+ ASSET]                                            80
			Lawn Care Revenue [+ EQUITY:Retained Earnings]                                350
			  To record revenue for lawn care services
		
	 14   Cash [+ ASSET]                                                           90
	        Sales Revenue [+ EQUITY:Retained Earnings]                                     90
		  Cost of Goods Sold [- EQUITY:Retained Earnings]                          75
		    Inventory [- ASSET]                                                            75
			  To record the cost of inventory (half of shrubs) sold (for $90)
			  and to reduce inventory for its cost
```
-->

## Step 3: Summarize the effects of transactions
### Posting journal entries
- Posting: The process of transferring amounts from the journal to the ledger
- Ledger: A book of accounts in which data from transactions recorded in journals are posted and thereby summarized

### Preparing a trial balance
- Trial balance: A listing of all account balances. Provides a means of **testing whether total debits equal total credits for all accounts**
It is very different from balance sheet. A trial balance is strictly an **internal document** used to summarize all of the account balances in a company's accounting system.


## Step 4: Prepare reports
[[Chapter 4]]
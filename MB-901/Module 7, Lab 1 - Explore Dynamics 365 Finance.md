MB-901: Dynamics 365 Fundamentals
Module 7, Lab 1 - Explore Dynamics 365 Finance
Prerequisites: Prior to performing the steps of this lab, perform the following tasks: 

Note: You need a deployed environment with demo data prior to perform this lab. Your Dynamics 365 Finance and Operations apps instance, can be lunched either from LCS or by directly going to the URL of the instance.

You will need to change the company to USMF. In order to login to the Dynamics 365 Finance and Operations apps instance you need to have a user name and password with either Chief Executive Officer or a System administrator security role.

In case your environment does not have demo data, follow the instructions below:

Navigate to Modules>Demo Data, and click Generate data then click OK.

Import exchange rates
Change the company to USMF.

Go to General ledger > Currencies > Exchange rate types.

Click New.

In the Exchange rate type field, type ‘GTL-EXCH’.

In the Name field, type ‘Seahorse Exchange Rate’.

Click Exchange rates.

Note there is not any exchange rates available.

Close Exchange rates form

Close exchange rate type form

Go to General ledger > Currencies > Configure exchange rate providers.

Click New.

Select Central Bank of the Russian Federation

Click OK.

Close the page.

Go to General ledger > Currencies > Import currency exchange rates.

In the Exchange rate type field, enter or select GTL-EXCH

Select Central Bank of the Russian Federation

In the Exchange rate provider field, enter or select Central Bank of the Russian Federation

Click OK.

Go to General ledger > Currencies > Exchange rate types.

Select GTL-EXCH

Click Exchange rates.

Note the imported values

Close all forms

Create a purchase order, post a product receipt
Go to Accounts Payables > Purchase orders > All purchase orders.

Click New.

In the Vendor account field, select 1001 Acme Office Supplies.

In the Warehouse field, select 11.

Click OK.

In the Item number field, Select item 1000 Surface Pro 128 GB.

On the Action Pane, click Purchase.

Click Confirm.

On the Action Pane, click Receive.

Click Product receipt.

In the Product receipt field, type GTL02020.

Click OK.

Close all forms.

Create a free text invoice
Go to Accounts receivable > Invoices > All free text invoices.

Select New.

In the Customer account field, select US-003.

In the Description field, enter Guide To Free Text Invoice. in the dialog box click Yes.

In the Main account field, select 110180 account number.

In the Quantity field, enter 17.

In the Unit price field, enter 817.00. The amount is calculated as the quantity times the unit price. However, you can override that calculation by entering an amount.

Select Charges to add a charge to the invoice.

In the Charges code field, enter FREIGHT.

In the Charges value field, enter 150.

Close the page.

Select Totals to view a summary of the invoice details and totals.

Select Close.

Select Post to post the invoice. You will still have an opportunity to cancel before you actually post.

You can change the timing of invoice printing. Select Current to print each invoice as it’s updated. Select After to print after all invoices have been updated.

To change how the customer’s credit limit is verified before the invoice is posted, change the value in the Credit limit type field.

To print the invoice, set the option to Yes.

To post the invoice, set the option to Yes. You can print the invoice without posting it.

Select OK.
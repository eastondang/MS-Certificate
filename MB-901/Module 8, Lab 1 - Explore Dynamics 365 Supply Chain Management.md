MB-901: Dynamics 365 Fundamentals
Module 8, Lab 1 - Explore Dynamics 365 Supply Chain Management
Create a product
In USMF, you need to create a new item for a new configuration of cabinet to be purchased from vendors.

Navigate to Product information management > Products>Released products.
Click New.
In the Product type field, select Item
In the Product subtype field, select Product
In the Product number field, type GTL007
In the Product name field, type Cabinet 2
In the Item model group field, select FIFO (First In-First Out)
In the Item group field, select TV&Video
In the Storage dimension group field, select SiteWH
In the Tracking dimension group field, select None
In the Inventory unit field, select ea (Each)
In the Purchase unit field, select ea (Each)
In the Sales unit field, select ea (Each)
In the BOM unit field, select ea (Each)
In the Purchase price field, type 30.00
In the Sales price field, type 30.00
In the Sales Taxation, Item sales tax group field, select ALL (All sales tax codes)
In the Purchase Taxation, Item sales tax group field, select ALL (All sales tax codes)
Click OK.
Click Validate to ensure the product is completely finalized. This button is located on the product action pane.
Close all pages.
Create product masters
In USMF, you need to create a new item (V neck T-shirt) to buy. This item will be available in size Small, Medium and Large and in colors: Black and Red.

Navigate to Product information management > Products > Released products.
Click New.
In the Product type field, select Item
In the Product subtype field, select Product master
In the Product number field, type GTLPM001
In the Product name field, type V Neck T-Shirt
In the Search name field, type VNeckTShirt
In the Retail category field, select Apparel and Footwear
In the Product dimension group field, select ColorSize
In the Configuration technology field, select Predefined variant
In the Item model group field, select FIFO (First In-First Out)
In the Item group field, select Audio
In the Storage dimension group field, select SiteWH
In the Tracking dimension group field, select None
In the Inventory unit field, select ea (Each)
In the Purchase unit field, select ea (Each)
In the Sales unit field, select ea (Each)
In the BOM unit field, select ea (Each)
In the Sales Taxation, Item sales tax group field, select ALL (All sales tax codes)
In the Purchase Taxation, Item sales tax group field, select **ALL **(All sales tax codes)
In the Purchase price field, type 19.95
In the Sales price field, type 29.95
In the Click OK. missing part of this
Close all pages.
Navigate to Product information management > Products > Released products.
Using quick filter search by item number for GTLS001.
Click item GTLS001 to open the product master record.
Click the Product dimensions button from Product action pane.
Select the Sizes tab.
Click New in the Define sizes for a product master section.
In the Size field, enter Small.
In the Name field, enter Small.
In the Description field, enter Small Size.
Click New.
In the Size field, enter Medium.
In the Name field, enter Medium.
In the Description field, enter Medium Size.
Click New.
In the Size field, enter Large.
In the Name field, enter Large.
In the Description field, enter Large Size.
Select the Colors tab.
Click New in the Define sizes for a product master section.
In the Color field, enter Black.
In the Name field, enter Black.
In the Description field, enter Black color.
Click New.
In the Name field, enter Red.
In the Description field, enter Red color.
Click Save.
Close the form.
Click Released Product variants button from Product action pane.
Click Variant suggestions from Product Variant action pane.
Click Select all.
Click Create.
Close all pages.
Create a Purchase Order
Create one purchase order for Acme Office Supplies, to be delivered today, with 5 of item number T0003 to be delivered to Site 1, and 5 of M1101 Foam Reacting Agent to be delivered to the Quality Testing Center123 W. Cherry Street, Zip Code 83642.

Go to the Procurement and sourcing > Purchase orders > All purchase orders.
Click New.
Vendor account: Select 1001 (Acme Office Supplies)
Delivery date: Verify the current date in the Delivery date field (this should be the default value).
Click OK
Add items to the purchase order
Item number: Select T0003.
Quantity: Enter 5.
Unit: Enter ea.
Click Add line
Item number: Select C0004.
Quantity: Enter 4.
Unit: Enter pcs.
Select delivery addresses for the items
Select the line for item T0003 in the Purchase order lines FastTab.
In the Lines Details fast tab, change to the Address tab.
Change the Delivery address to Contoso Entertainment System USA.
Select the line for item C0004 in the Purchase order lines FastTab.
Change to the Address FastTab.
Click the Add address button (+) to the right of the Delivery address field.
Name or description: Enter Quality Testing Center.
Zip/postal code: Enter 83642.
Street: Enter 123 W. Cherry Street.
Click OK.
Click Save.
On the Action Pane, click Purchase.
Click Confirm.
On the Action Pane, click Receive.
Click Product receipt.
In the Product receipt field, enter the product receipt number. For example, enter PR123.
Click OK to post the product receipt.
Close all pages.
Create sales orders
This procedure shows you how to create a sales order. You can use the procedure in demo data company USMF. Sales orders are typically created by a sales order processor.

Go to Sales and marketing > Sales orders > All sales orders.
Click New.
In the Customer account field, click the drop-down button to open the lookup.
In the list, find and select the customer US-004.
Click OK.
Click Sales order line.
Click Dimensions.
For this example, select the Color, Site and Warehouse dimensions. The dimensions you select here will appear in the sales order grid. If you want your selections to persist, set the Save setup option to Yes.
Click OK.
In the Item number field, click the drop-down button to open the lookup.
For this example, select item number T0004.
In the Color field, click the drop-down button to open the lookup.
In the list, find and select Black.
In the Quantity field, enter 1.
On the Action Pane, click Sales order.
Click Totals.
The Totals page displays details about the entire order. This includes the subtotal amount, which is a sum of all line net amounts adjusted for eventual line discounts, the total invoice amount, which is a subtotal amount adjusted for eventual order-level discount, charges, and sales tax, the customer credit limit situation, and more. The invoice amount is the amount that will appear on the customer’s invoice document.
Click OK.
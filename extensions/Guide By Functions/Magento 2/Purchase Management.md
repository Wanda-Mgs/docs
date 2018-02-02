# PURCHASE MANAGEMENT - USER GUIDE FOR MAGENTO 2
**Version 1.1.0**




## Introduction

**Purchase Management** is a Magento 2 module, which helps you manage purchasing and receiving stock from suppliers. All information about Purchase Order, Quotation and Suppliers are kept track and automatically updated in the system. 

[Purchase Management](https://www.magestore.com/purchase-order-management) is a module in our [Omnichannel Solution](https://www.magestore.com/omnichannel-retail).


## HOW TO CONFIGURE

## HOW TO USE

### Manage Supplier

- *Path:* **Purchase Management > Supplier** section **> Manage suppliers**

#### View Supplier Details

![manage supplier]()

On the **Manage Suppliers** page, you can view the table including information about **Supplier Code, Total SKU, Purchase Order Value, Last Purchase Order On,** and **Status**. 

Moreover, in the **Action** column, you can click on **View** for more detail about the supplier including which Products they have provided, along with **Supplier Information, Supplier Address** and **Purchase Sales List**

![manage supplier]()

#### Add a new Supplier

![manage supplier]()

Click on **Add New Supplier** and Fill **Supplier Information** and **Supplier Address**

![manage supplier]()

- **Supplier Information**

![manage supplier]()

(1)	**Supplier Code**: enter the code based on your own rules

(2)	**Supplier Name**: enter the supplier’s name

(3)	**Contact Person**: enter the name who you can contact when you need supply

(4)	**Email**: enter the **Contact Person**’s email

(5)	**Description**: enter the description if any

(6)	**Status**: select whether the supplier is **Enable** or **Disable** 

- **Supplier Address

![manage supplier]()

Fill **Supplier Address**, such as **Telephone, Fax, Street, City, Country, Region, Zip/Postal Code**, and **Website**

Finally, don’t forget to click on **Save** to complete this step.

Now you can assign products to this supplier. After you click on **Save** button, your screen will appear like following:

![manage supplier]()

There are two ways to assign products to the supplier: Add product manually and import products via a csv file. 

If you choose to upload products manually, remember to enter related information for each one: **Supplier SKU, Cost** and **Tax**. Otherwise, importing products in mass is recommended. A csv file sample is offered. In case you have a mistake on importing products, **Delete Product** button can help.

### Manage Pricelist

- *Path:* **Purchase Management > Supplier** section **> Manage pricelist**

*“**Pricelist** is a list of prices for the goods offered by a supplier. It usually consists of Minimal Qty and Cost”*

On the **Manage Pricelist** page, you can view **Product SKU, Supplier, Product Supplier SKU, Minimal Qty., Cost, Start Date** and **End Date**.

![manage pricelist]()

You can also delete the pricelist by ticking on the selected supplier on the 1st column, and select **Delete** in the **Actions** field

![manage pricelist]()

You can update the pricelist by click on **Add Pricelist** or **Import Pricelist**

- **Add Pricelist**

![manage pricelist]()

To add pricelist, you must complete three required steps:

-- **Step 1: Supplier**: Select the supplier that you want to add pricelist to
-- **Step 2**: Click on **Select Products** button

![manage pricelist]()

A pop-up will be shown

(1)	Tick on the selected product(s)

(2)	Click on **Select Product** to finish

-- **Step 3**: Finally, click on **Add Selected Product(s)** to finish

- **Import Pricelist**

![manage pricelist]()

(1)	Click on **Choose File** to upload a **CSV file**. A sample is available for download.

(2)	Click on **Import** to finish

### Quotation

*“**A quotation** (or a request for quotation) is the proposal of price and quantity of goods that store owners send to suppliers. The quotation will become purchase order when a seller sends confirmation of price and availability of products stated in the quotation.”*

#### Create a new Quotation

- *Path:* **Purchase Management > Quotation Management** section **> Create Quotation**

![Quotation]()

- **Step 1**: Fill in General Information

(1)	**Created Time**: click on **Calendar** to select Created Date (or you can use the system date)

(2)	**Supplier**: select the supplier that you want to send quotation

(3)	**Currency**: choose the currency  

(4)	**Currency Exchange Rate**: the amount of the currency in point 3 above that equals to 1 USD 

(5)	**Comments**: enter comments ifany

(6)	Click on **Prepare Product List** button to move to the next step

- **Step 2**: Select the products you need supplying.

![Quotation]()

(1)	After clicking on **Prepare Product List** button, You can view **Summary Information**, including time (**Created At**), **Purchase form, Payment Term** and **Shipping Method**, as below:

![Quotation]()

(2)	You add products that need supplying.

![Quotation]()

All products that you add will be shown on the table, where you should edit **Current Cost, Purchase Cost,** and **Qty. Offering**. Besides, you can edit **SKU, Product Name, Supplier SKU, Tax, Discount** and even **Delete** the products from the Quotation. 

There are 5 ways toprepare product list: **Import Products**, add **Supply Needs Products, Back Sales Products, Low Stock Products** and **All Supplier Products**: 

- **Import Products**:

![Quotation]()

Similar to step 3 in **Manage Pricelist** section

- **Supply Needs Products:**

![Quotation]()

(1)	**Warehouse(s)**: select warehouse(s) to see products that need supply

(2)	**Sales Period**: select the Sales Period

(3)	**Forecast Supply Need to**: click on Calendar to choose the date that you want to forecast

(4)	Click on **Show Supply Needs** button, then the name and Qty. of products will be shown in the table

(5)	Select/ deselect the products and Click on **Add Selected Products** to finish


- **Back Sales Products**: Back orders products are ordered by customers but not available in stock at that moment.

![Quotation]()

(1)	Tick on the **product SKU** that need supplying

(2)	Click on **Add Selected Products** button to finish

- **Low Stock Products:**

![Quotation]()

(1)	**Select Low Stock**: choose one of your low stock notification 

(2)	Tick on the **product SKU** that need supplying

(3)	Click on **Add Selected Products** button to finish


- **All Supplier Products:**

![Quotation]()

(1)	Tick on the products that need supplying

(2)	Click on **Add Selected Products** button to finish.

After you added all the products you need supplying, you need to:

![Quotation]()

(1)	Tick on the product(s) that you want to edit the **Qty. Ordering** and **Purchase Cost** (or **Tax, Discount**)

(2)	Edit the **Purchase Cost, Tax, Discount and Qty. Ordering.**  Remember **Purchase Cost** and **Qty. Ordering** are required fields

(3)	Click on **Save** to update the quotation 

- **Step 3**: Fill in Shipping and Payment method

![Quotation]()

(1)	**Shipping Address**: enter the shipping address

(2)	**Shipping Method**: choose one of your shipping method

(3)	**Shipping Cost**: enter the cost of shipment

(4)	**Start Shipping Date**: choose **Calendar** to pick the date
**Expected Delivery Date**: choose **Calendar** to pick the date when you want your products to arrive

(5)	**Payment terms**: choose one of your payment terms

(6)	**Sales Place Via**: you have 5 options – **Email, Fax, Phone, Vendor Website** or **N/A**

Remember to click **Save** to update what you have edited

- **Step 4**: Review the quotation.

Here, you can review/edit the quotation information including the Order Totals. 

![Quotation]()

- **Step 5:** Send Request to the suppliers or Print the quotation

![Quotation]()

-- **Back**: if you want to come back the **Quotation Management** page
-- **Cancel**: delete the quotation. A pop-up will be shown to make sure you want to cancel it. 
-- **Send Request**: the request will be sent to supplier via email
-- **Print**: to print out the Quotation
-- **Save**: click here to update and finish this quotation as the draft
-- **Confirm Quotation**: after the quotation is confirmed, the system will allow you to check again the information, then 

![Quotation]()

(1)	**Back**: get back the **Quotation Management** page

(2)	**Cancel**: delete the quotation. A pop-up will be shown to make sure you want to cancel it. Then if you really want to cancel this, you click on **Delete** button, if not, you click on **Back** then you will be linked the quotation management site.

(3)	**Send Email**: send the Quotation Confirmation email to supplier

(4)	**Print**: print out the Quotation Confirmation

(5)	**Save**: update what you have edited on Shipping and Payment field

(6)	**Convert Quotation to PO**: create **Purchase Order** from the quotation

(7)	**Revert Quotation**: get back to the **Quotation Creation** page, to edit product(s)

#### Manage Quotation

- *Path:* **Purchase Management > Quotation Management** section **> Quotation**

![manage quotation]()

Here, you can view **Quotation Number, Created At, Supplier, Required Qty., Grand Total (including Tax)**, and **Status**.

Besides, you can view more detail by clicking on **View** in the **Action** column

![manage quotation]()

You can view and edit **Summary Information, Shipping and Payment**, and **General Information**

### Purchase Order

*“**Purchase Order (PO)** is a document sent to a specific supplier to purchase more inventories for your warehouses. It contains descriptions, quantities, prices, discounts, payment terms, date of performance or shipment, other associated terms and conditions.”*

#### Create Purchase Order

- *Path:* **Purchase Management > Purchase Order Management** section **> Create Purchase Order**

When creating Purchase Order, you will see a tab showing steps at which Purchase Order is. They are **New, Pending, Processing**, and **Completed**.

- **Step 1**: input General Information

![purchase order]()

-- Enter required information. Similar to **Step 1 in Create a new Quotation**
-- Click on **Prepare Product List** button to move to the next step

- **Step 2**: Add products to the Purchase Order

![purchase order]()

Similar to **Step 2 in Creating a Quotation**, there are 5 ways to prepare product list:

-- Import products via a CSV file
-- Prepare product list based on supply need forecast
-- Prepare back order products (Back orders products are ordered by customers but not available in stock now)
-- Prepare low stock products
-- Prepare product list manually with **All Supplier Products** button

Then, click on **Confirm Purchase Order** at the top right to continue.

- **Step 3**: Setting Shipping and Payment

![purchase order]()

-- Enter the address you want the stock to be shipped to
-- Select a shipping method for the purchase order
-- Estimate and enter the shipping cost
-- Set start shipping and expected delivery date
-- Select the payment term
-- Choose the way to place order: N/A, Email, Phone, Fax, Vendor website

After this step, choose **Save** and the purchase order status will be changed to ***Pending***. At this time, you can choose to Send Request to the supplier (Request will be sent to suppliers’ email address), Print the purchase order, Cancel or Confirm Purchase Order. 

You should double-check all information before confirming purchase order. After being confirmed, the purchase order status will be changed to ***Processing***.

![purchase order]()

You can view **Summary Information, General Information and edit Invoices, Received Items, Returned Items, Transfered Items, Shippping** and **Payment**.

You can click on **Complete PO** to complete the purchase order (its status will be changed to Completed) even if you have not received all requested items. When the purchase order status is **Completed**, you cannot receive items anymore but you still transfer received items into warehouses after that.

You can also click on **Receive Items** button to note which and how many items are received.

- **Summary Information**

![purchase order]()

You can view the **time, supplier, shipping method, payment term, product list** and **sales totals report**

- **Receive Items**
When the purchase order’s status is processing, you can be navigated to the following view and receive or return items:

![purchase order]()

The table will shown received items with information including **Received Data, SKU, Product Name, Supplier SKU, Received Qty** and **Created By**

-- If you click on **Receive all items**, then all items that you need supplying are ordered. 
-- If you click on **Receive items** to note the received quantity of some items only. This method is most suitable when you use partial shipment. 

![purchase order]()

(1)	**Received Time**: click **Calendar** to pick the Date you received the items

(2)	**Product List:**
-- **Scan Barcode**: update product list by scanning product barcode 
-- **Select Products**: a pop-up will be shown as below

![purchase order]()

Tick on the product(s) you received. Then click on **Select** button to complete

![purchase order]()

After that, you need to enter the product quantity you received in the **Receive Qty** field. 

Finally, click **Save** to finish 

- **Returned Items**

![purchase order]()

In the Returned Items tab, you can return products to the Supplier by clicking on Return Products button. Please refer to **Create Return Request** for more details.

- **Invoices**

![purchase order]()

The invoice you created will be shown on the table, including information such as **Invoice ID, Billed Date, Invoice Total, Total Paid, Total Refund**, and **Billed Qty**.

Click on **Create an Invoice**. Note that multiple invoices can be created for one purchase order. 

![purchase order]()

(1)	**Billed From**: select the date it is billed

(2)	**Product List**: click on **Selected Products** button, then a pop-up will be shown

![purchase order]()

(3)	Tick on the product(s) you select. Then click on **Select** button to finish

- **Transferred Items**

After receiving products, you can transfer them to warehouses by clicking **Transfer Product to Warehouse.**

![purchase order]()

You will need to fill information like **Transferred Date, SKU, Product Name, Supplier SKU, Transferred Qty, Transferred to** and **Created By**. After that, you click on the **Save** button to save your work. After that, you can see the records of all transferred products in the **Transferred Items** tab.

-- **Shipping and Payment**: as above
-- **General Information**: as above

- **Step 4**: Completed

![purchase order]()

Here, you can view **Summary Information** (Short Information, Product List and Sales Totals), **Invoices, Received Items, Shortfall items, Returned Items, Transfered Items, Shipping and Payments**, and **General Information**

Then, you can click on **Send Email**, to send this purchase order to your supplier. Click on **Print** to print out the Purchase Order

#### Manage Purchase Order

- *Path:* **Purchase Management > Purchase Order Management** section **> Purchase Orders**

![manage purchase order]()

You can view the purchase date (**Purchase On – Expect Delivery On), supplier, Requested Qty, Received Qty, Total Paid, Grand Total (Including Tax)** and **Status**. Beside, you can view more details by clicking on View, or delete the purchase order by tick on the order then choose action **Delete**.

### Return Request

**Return Items** are records of items & Qty. returned against a purchase order. You can return partial or all items in the PO.

#### Create Return Request

- *Path:* **Purchase Management > Return Request Management** section **> Create Return Request**

- **Step 1**: status **New**: input General Information
 ![create return request]()
 
(1)	**Created Time**: select **Calendar** to choose date

(2)	**Warehouse**: select warehouse that holds the Returned Items

(3)	**Supplier**: select the one who supplies the items

(4)	**Reason**: enter the reason why you returned it

Then, click on **Prepare Product List** button to move to the next step

- **Step 2**: status **Pending**: Prepare products to create return request

 ![create return request]()

(1)	First, you need to select product(s) that you want to return: you can **Import Products, Scan Products (instruction below)** and select from **All Supplier Products**

 ![create return request]()

With **Scan Products**, you need to:

-- (1)	**Product List**: scan product barcode and it will appears here

-- (2)	Click on **Add Products** to finish

(2)	Click on **Confirm Request** to move to next step.
After this step, a return request is recorded with **Processing** status and awaits confirmation from the Supplier before you actually send items from warehouse. At this step, stock has not been subtracted from the warehouse yet.

You can also **Send request** to supplier via email or print the return request.

- **Step 3**: Status **Processing**: Send items and/or finish return request

 ![create return request]()
 
If the supplier confirms the return request, you can start sending products by clicking on **Delivery items**. 

A new window will open. You can select the date to send stock, choose to **Subtract stock on warehouse** once this step is completed, return products by scanning barcode or select from the product list and click **Save** to finish.

If you have selected **Subtract stock on warehouse** option, the returned stock is now subtracted from your warehouse.

Note that you can return partial items and come back later to return the rest.

 ![create return request]()
 
You can click on **Complete Request** to complete the return request even if you send back items in the previous step above or not. Once you have completed the return request, you will NOT be able to receive or edit further information of this request. 
The request status is marked **Completed**.

- **Step 4**: status **Completed**

 ![create return request]()
 
You can review the information you have created, send it via email to the supplier or print it out. 

#### Manage Return Request

![Manage Return Request]()

You can see **Return Number, Return On (date), Supplier, Warehouse, Returned Qty, Delivered Qty.,** and **Status**

(1)	Click on **Create Return Request** button if you want to create a new one.

(2)	Select the return request and click **View** to see all details of the request.

----------
## Release Note

### Version 1.1.0 (released on Oct 9, 2017)

### Version 1.0.1 (released on Jul 19, 2017)

Allow to assign product to suppliers when adding new product

------------------------------
**_Confidential Information Notice_**

Copyright2016

All Rights Reserved. Any unauthorized reproduction of this document is prohibited.

This document and the information it contains constitute a trade secret of Magestore and may not be reproduced or disclosed to non-authorized users without the prior written permission from Magestore. Permitted reproductions, in whole or in part, shall bear this notice.

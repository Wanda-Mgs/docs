# OMNICHANNEL SOLUTION STARTER PACKAGE - USER GUIDE FOR MAGENTO 2

## INTRODUCTION
Having a combined **POS** and **In-stock Management** solution is a must-have for retail businesses that want to be more efficient and keep accurate data. Web POS, a web based Point of Sale for Magento, is specially designed to integrate with this Instock Management module. Carrying out checkout procedure for customers has never been easier. Web POS helps your sales staff quickly create orders and apply promotion, conveniently collect in-store cash and credit sales transactions in a flash. And all steps are on just one single page! So, wouldn't it be great if this process could be hastened, saving time for more profitable actions!

Moreover, if your inventory is not enough to supply, you may lose customers. But if the inventory you keep is more than needed, it will cost you lots of money to manage. Thus, it is vital to equip your business with an effective inventory system to always keep your warehouses at an ideal stock level. Magestore team has been working hard to offer you a friendly & affordable stock management solution for Magento 2 with smart design, clean and simple workflow to handle every activity about stock management, stock taking and low stock notification... in your warehouses in the most efficient way. 

With the latest upgraded version and its convenience and the amount of time saved, we hope that you would enjoy and feel exhilarated when experiencing our solution. 

*Thanks and Best regards,*

**Magestore Team** 


## HOW TO CONFIGURE
### Inventory
#### Stock Control Configuration

Path: **Stock Management > Settings** section **> Configuration**

![Anh 1]()

1)	**Link stocks in Warehouse to Front Store View**: In managing a Warehouse, you can link Warehouse to a Front Store View (Path: **Stock Listing > Warehouses >** Click **View > Warehouse Information** section **> General Information** tab **> Magento Store View** field). Note that you can link a warehouse to one or multiple store views.
- If you enable **Link warehouse to Magento Front Store View** by choosing **Yes** here, stock in warehouse will be displayed on the linked store view. When customers buy on this store view, stock quantity will be deducted from this linked warehouse.
- If choose **No**, stocks in all warehouses will be shown on the store view. 

2)	**Adjust Stock by entering the change Qty**: 
- if you choose **Yes**, when you enter the difference quantity (either a positive or negative figure), the system will calculate the final balance in warehouse by adding/ subtracting the entered value.
- If you choose **No**, you need to enter the exact quantity of stock in warehouse and the system will recognize this figure as the latest available quantity of product.

3)	Click **Save Config** to finish

#### Inventory option

Path: **Stock Management > Settings** section **> Configuration > Catalog > Inventory**

***Note***: *If you want to configure based on your own features, then unmark box **Use System value.***

##### Stock Option

![Anh 2]()
 
1)	Select **Yes** in the dropdown list to adjust the quantity on hand when an order is placed.

2)	Select **Yes** in the dropdown list to return items to stock if an order is cancelled.

3)	Select **Yes** in the dropdown list to display products in the catalogue that are not in stock. 

4)	Enter the number in the blank to display the message: **Only x left** on website when the quantity in stock reaches the threshold.  

5)	Select **Yes** in dropdown list to display an **In Stock** or **Out of Stock** message on the product page.

6)	Tap **Save** to finish. 

##### Product Stock Options

Path: **Stock Management > Settings** section **> Configuration > Catalog > Inventory**
 
![Anh 3]()

(1)	Select Yes to activate inventory control for your catalog. 

(2)	Set Backorders to one of the following status: 
- **No Backorders Allow Qty. Below 0**: To reject backorders when product is out of stock.
- **Allow Qty. Below 0**: To accept backorders when the quantity falls below zero. 
- **Notify Customer**: To accept backorders when the quantity falls below zero, and notify the customer that the order can still be placed.

(3)	Enter the **Maximum Qty**. allowed in Shopping Cart.

(4)	Enter the quantity for Item's Status to become out of stock.

(5)	Enter the **Minimum** quantity allowed in Shopping Cart.

Next, 

![Anh 4]()
 
(6)	Enter the stock level that generates notification showing the item is out of stock.

(7)	Select **Yes** to activate quantity increments for the product. Then in the **Qty. Increments** field, enter the number of the items that must be purchased to meet the requirement mentioned above.

(8)	Select **Yes** to return the item to inventory by default when a credit memo is issued for the item.

Finally, click on **Save Config** to save changes.

#### Low Stock Notification Rules 
Please refer to section **Low Stock Rules**

### Web POS 
#### Default Guest  Checkout 

Path: **Sales > Web POS** section **> Settings > Default Guest Checkout**

Default customer is the customer whose information will be used for Guest Checkout or when customer information is not enough, default value will be filled automatically.

![Anh 5]()
 
Fill in all information as you want to use as default, including **First Name, Last Name, Street, Country, State/Province, City, Zip/Postal Code, Telephone** and **Email**. After finishing, click on **Save Config** button to save your work.

#### How to set up a Shipping Method for Web POS

Path: **Sales > Web POS** section **> Settings**

To set up Shipping Methods for Web POS, go to **Shipping for POS** section under **Settings**:

![Anh 6]()

(1)	**Applicable Shipping Methods**: 
•	If you want to apply all shipping methods, choose All Allowed Shipping.
•	If you want to apply some particular shipping methods only, choose Specific Shipping option.

(2)	**Specific Shipping Methods**: If you select **Specific Shipping** in point (1) above, then here you can select prefered shipping method. Hold **Shift + Click** to choose more than one.

(3)	**Default Shipping Method**: Choose the shipping method that you would want to set as default payment method during checkout WebPOS. This shipping method must be in **Specific Shipping Methods**.

(4)	You can enable **Mark as shipped** by default.

(5)	Click **Save Config** to save your settings.

#### How to enable a Payment Method for Web POS

Path: **Sales > Web POS** section **> Settings**

To set up Payment Methods for Web POS, go to **Payment for POS** section under **Settings**:

![Anh 7]()
 
(1)	**Applicable Payment Methods**: 
•	If you want to apply all shipping methods, choose **All Allowed Payments**.
•	If you want to apply some particular shipping methods only, choose **Specific Payments** option.

(2)	**Specific Payment Methods: If you select **Specific Payments** in point (1) above, then here you can select prefered payment method. Hold **Shift + Click** to choose more than one.

(3)	**Default Payment Method**: Choose the payment method that you would want to set as default payment method during checkout WebPOS. This payment method must be in **Specific Payment Methods**.

(4)	Click **Save Config** to save your settings.

#### How Web POS works with peripheral devices

Magestore WebPOS module can connect with **Barcode readers, Card swiper & Receipt printers**.
➢	**Barcode readers**: are any devices that can connect with iPad/Laptop/PC (including USB Port, Wifi or Bluetooth). The scanner can read barcodes & fill encoded information into Web POS search box.
➢	**Card swiper**: only devices connected through USB port (supports Authorize.Net & Stripe).
➢	**Receipt printers**: any devices that connect with iPad/laptop/PC.

## HOW TO MANAGE USER PERMISSION
**Note**: Only admin accessing Web POS can set up Staff permission

### How to manage User Roles and Users
**Note**: *Users are the one who get permission to access in the Backend*

#### Decentralize User Roles
Path: **System > Permission** section **> User Roles**

##### Manage user role

![Anh 8]()
 
(1)	Click **Add New Role** to create new user role.

(2)	Fill out the blank with a value to search, after click **Search**.

(3)	Search user role information with keyword.

View or edit a role’s detail by clicking on each line.

##### Create a new user role

![Anh 9]()
Click **Add New Role**

![Anh 10]()
In tab **Role Info**

Fill in all required fields

![Anh 11]()
 
In tab **Role Resources**:

(1)	**Resource Access**: You can choose **Custom** or **All**. Choose **All** if you want users having this role will have access to all resources, click on **Save** or **Save And Continue Edit** button to save your work.

(2)	If you choose **Custom**, you can tick to assign specific permissions for that role.

Click **Save** to complete the process.

#### Decentralize Users
##### Manage user

![Anh 12]()

(1)	Click **Add New User** to create new user.

(2)	Fill out the blank with a value to search

(3)	Click on **Search** button to search user information with keyword.

View or edit a user’s detail by clicking on each line.

##### Create a new user

![Anh 13]()

To create new user, click **Add New User**

![Anh 14]()

In tab **User Info**, fill in the blank:

(1)	**User Name** (required)

(2)	**First Name** (required)

(3)	**Last Name** (required)

(4)	**Email** (required)

(5)	**Password** (required)

(6)	**Password Confirmation** (required)

(7)	**Interface Locale**: you can select different location.

(8)	**This account is**: Active or Inactive.

(9)	**Your Password**: fill out your password. (required).
 
![Anh 15]()

In tab **User Role**, select a role for user.
![Anh 16]()
 
In tab Warehouse, click **Assign Warehouses** to assign warehouses to this user.
![Anh 17]()

Click **Save User** to complete the process.

### How to manage staff
#### Decentralize access permission of Web POS users
Path: **Sales > Web POS** section **> Manage Roles**

##### Manage role
![Anh 18]()
 
(1)	**Add Role**: Click to add a new role.

(2)	**Filters**: You can find role information by click it and fill out values.

(3)	**Action**: If you want to delete a role record, you need choose a role, then click Action and select Delete.

(4)	**Edit**: You can view role’s details (edit) by click Edit or click each line.

##### Add a new role

![Anh 19]()
Click **Add Role** to add a new role.

![Anh 20]()

In **General** tab, fill out the blank.

(1)	**Role Name**: Enter a name for the role. (required)

(2)	**Maximum discount percent (%)**: Limit the highest discount percent that each user role can offer customers.

(3)	**Description**: Enter text that describes the role.
 
![Anh 21]()

In **Permission** tab:

(1)	**Resource Access**: You can choose **Custom** or **All**. Choose **All** if you want users having this role will have access to all resources, click on **Save** or **Save And Continue Edit** button to save your work.

(2)	If you choose **Custom**, you can tick to assign specific permissions for that role.

#### Decentralize staff
##### Manage Staff
Path: **Sales > Web POS** section **> Manage Staff**

![Anh 22]()
 
(1)	Click **Add Staff** to create a new staff.

(2)	Click **Filters** to search staff information.

(3)	If you want to **Delete** or **Change status** a staff, first select a staff, then click **Actions**: choose **Delete** or **Change status**.

Click **Detail** to view a staff’s details or edit.

##### Create a new staff
Path: **Sales > Web POS** section **> Manage Staff**

![Anh 23]()
Click **Add Staff**.

![Anh 24]()
Fill out all the required fields or select:

(1)	**User Name.**

(2)	**Password.**

(3)	**Password Confirmation.**

(4)	**Display Name.**

(5)	**Email Address.**

(6)	**PIN Code (App only).**
 
 ![Anh 25]()

(7) **Customer Group**.

(8) **Location**: Hold **Ctrl + Click** to choose more than one
 
 ![Anh 26]()

(9) **Role**.

(10) **Status**: You can **Enabled** or **Disabled** this staff.

(11) **POS**: Assign POS for user. To choose more than one, hold **Ctrl + Click**.

Finally, click **Save** to complete the process.





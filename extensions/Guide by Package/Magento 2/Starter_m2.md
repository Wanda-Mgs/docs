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

1)	Select Yes to activate inventory control for your catalog. 

2)	Set Backorders to one of the following status: 
- **No Backorders Allow Qty. Below 0**: To reject backorders when product is out of stock.
- **Allow Qty. Below 0**: To accept backorders when the quantity falls below zero. 
- **Notify Customer**: To accept backorders when the quantity falls below zero, and notify the customer that the order can still be placed.

3)	Enter the **Maximum Qty**. allowed in Shopping Cart.

4)	Enter the quantity for Item's Status to become out of stock.

5)	Enter the **Minimum** quantity allowed in Shopping Cart.

Next, 

![Anh 4]()
 
6)	Enter the stock level that generates notification showing the item is out of stock.

7)	Select **Yes** to activate quantity increments for the product. Then in the **Qty. Increments** field, enter the number of the items that must be purchased to meet the requirement mentioned above.

8)	Select **Yes** to return the item to inventory by default when a credit memo is issued for the item.

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

1)	**Applicable Shipping Methods**: 
•	If you want to apply all shipping methods, choose All Allowed Shipping.
•	If you want to apply some particular shipping methods only, choose Specific Shipping option.

2)	**Specific Shipping Methods**: If you select **Specific Shipping** in point (1) above, then here you can select prefered shipping method. Hold **Shift + Click** to choose more than one.

3)	**Default Shipping Method**: Choose the shipping method that you would want to set as default payment method during checkout WebPOS. This shipping method must be in **Specific Shipping Methods**.

4)	You can enable **Mark as shipped** by default.

5)	Click **Save Config** to save your settings.

#### How to enable a Payment Method for Web POS

Path: **Sales > Web POS** section **> Settings**

To set up Payment Methods for Web POS, go to **Payment for POS** section under **Settings**:

![Anh 7]()
 
1)	**Applicable Payment Methods**: 
•	If you want to apply all shipping methods, choose **All Allowed Payments**.
•	If you want to apply some particular shipping methods only, choose **Specific Payments** option.

2)	**Specific Payment Methods**: If you select **Specific Payments** in point (1) above, then here you can select prefered payment method. Hold **Shift + Click** to choose more than one.

3)	**Default Payment Method**: Choose the payment method that you would want to set as default payment method during checkout WebPOS. This payment method must be in **Specific Payment Methods**.

4)	Click **Save Config** to save your settings.

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
 
1)	Click **Add New Role** to create new user role.
2)	Fill out the blank with a value to search, after click **Search**.
3)	Search user role information with keyword.

View or edit a role’s detail by clicking on each line.

##### Create a new user role

![Anh 9]()
Click **Add New Role**

![Anh 10]()
In tab **Role Info**

Fill in all required fields

![Anh 11]()
 
In tab **Role Resources**:

1)	**Resource Access**: You can choose **Custom** or **All**. Choose **All** if you want users having this role will have access to all resources, click on **Save** or **Save And Continue Edit** button to save your work.

2)	If you choose **Custom**, you can tick to assign specific permissions for that role.

Click **Save** to complete the process.

#### Decentralize Users
##### Manage user

![Anh 12]()

1)	Click **Add New User** to create new user.
2)	Fill out the blank with a value to search
3)	Click on **Search** button to search user information with keyword.

View or edit a user’s detail by clicking on each line.

##### Create a new user

![Anh 13]()

To create new user, click **Add New User**

![Anh 14]()

In tab **User Info**, fill in the blank:

1)	**User Name** (required)
2)	**First Name** (required)
3)	**Last Name** (required)
4)	**Email** (required)
5)	**Password** (required)
6)	**Password Confirmation** (required)
7)	**Interface Locale**: you can select different location.
8)	**This account is**: Active or Inactive.
9)	**Your Password**: fill out your password. (required).
 
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
 
1)	**Add Role**: Click to add a new role.
2)	**Filters**: You can find role information by click it and fill out values.
3)	**Action**: If you want to delete a role record, you need choose a role, then click Action and select Delete.
4)	**Edit**: You can view role’s details (edit) by click Edit or click each line.

##### Add a new role

![Anh 19]()
Click **Add Role** to add a new role.

![Anh 20]()

In **General** tab, fill out the blank.
1)	**Role Name**: Enter a name for the role. (required)
2)	**Maximum discount percent (%)**: Limit the highest discount percent that each user role can offer customers.
3)	**Description**: Enter text that describes the role.
 
![Anh 21]()

In **Permission** tab:
1)	**Resource Access**: You can choose **Custom** or **All**. Choose **All** if you want users having this role will have access to all resources, click on **Save** or **Save And Continue Edit** button to save your work.
2)	If you choose **Custom**, you can tick to assign specific permissions for that role.

#### Decentralize staff
##### Manage Staff
Path: **Sales > Web POS** section **> Manage Staff**

![Anh 22]()

1)	Click **Add Staff** to create a new staff.
2)	Click **Filters** to search staff information.
3)	If you want to **Delete** or **Change status** a staff, first select a staff, then click **Actions**: choose **Delete** or **Change status**.

Click **Detail** to view a staff’s details or edit.

##### Create a new staff
Path: **Sales > Web POS** section **> Manage Staff**

![Anh 23]()
Click **Add Staff**.

![Anh 24]()
Fill out all the required fields or select:

1)	**User Name.**
2)	**Password.**
3)	**Password Confirmation.**
4)	**Display Name.**
5)	**Email Address.**
6)	**PIN Code (App only).**
 
 ![Anh 25]()

7) **Customer Group**.
8) **Location**: Hold **Ctrl + Click** to choose more than one
 
 ![Anh 26]()

9) **Role**.
10) **Status**: You can **Enabled** or **Disabled** this staff.
11) **POS**: Assign POS for user. To choose more than one, hold **Ctrl + Click**.

Finally, click **Save** to complete the process.

## HOW TO MANAGE MASTER DATA 
### Product
#### Attribute
Path: **Stores > Attributes** section **> Product**

##### Manage Attribute 
 ![Anh 27]()

1)	Click **Add New Attribute** to create new user.
2)	Fill out the blank with a value to search, after click **Search**.
3)	Search attribute information with keyword.

You can view or edit attribute’s details by clicking on each line

##### Create A New Attribute 

Attributes can be created while working on a product, or from the Product **Attributes** pages. The following example show how to create attributes from the Stores menu. Any attribute that is used as a drop-down list of values for a configurable product must have the following properties:

| Property| Value|
|--|--|
|Catalog Input Type for Store Owner| Dropdown|
Scope|Global| 

![Anh 28]()
Click **Add New Attribute**

![Anh 29]()

**Basic Properties**
1)	Enter a **Default Label** to identify the attribute
2)	Set **Catalog Input Type** for Store Owner to the type in input control to be used for data entry
3)	Select **Yes** to require the customer choose an attribute value option

For Dropdown and Multiple Select input types, do the following:
- Under Manage Options, click **Add Option**.
- Enter the first value that you want to appear in the list.
 -	Enter one value for the Admin, and a translation of the value for each store view.
 -	Enter only the Admin value, if you have only one store view, you can enter only the Admin value.
- Click **Add Option** and repeat the previous step for each option that you want to include in the list.
- Select **Is Default** to use the option as the default value.
 
![Anh 30]()

**Advanced Properties** (if needed).
1)	Enter a unique **Attribute Code** in lowercase characters, and without space.
2)	Set **Scope** to indicate where in your store system the attribute can be used.
3)	Enter a **Default Value** of the attribute. 
4)	If you want to prevent duplicate values from being entered, set **Unique Value** to **Yes**
5)	To run a validity test of any data entered in the text field, set **Input Validation for Store Owner** to the type of data that the field should contain. This field is not available for input types with values that are selected. The test can validate any of the following:
- Decimal Number.
- Integer Number.
- Email.
- URL.
- Letters.
- Letters (a-z, A-Z) or Numbers (0-9).
6)	**Add to Column Options**: Include the attribute as a column in the Products grid.
7)	**Use in Filter Option**: Adds a filter a control to the column header in the Products grid.

![Anh 31]()

**Input Validation**.
![Anh 32]()

In tab **Manage Labels**: Enter a **Title** to be used as a label for the field. If your store is available in different languages, you can enter a translated title for each view.

 ![Anh 33]()

In tab **Storefront Properties**
1)	If the attribute is to be available for search, set Use in Search to **Yes** 
2)	To include the attribute in Product Compare, set Comparable on Storefront to **Yes**
For dropdown, multiple select and price fields, do the following: 
3)	To use the attribute as a filter in layered navigation, set **Use in Layered Navigation** to **Yes**
4)	To use the attribute in layered navigation on search results pages, set **Use in Search Results Layered Navigation** to **Yes**
5)	In the **Position** field, enter a number to indicate the relative position of the attribute in the layered navigation block.
6)	Set **Use for Promo Rule Conditions** to **Yes** to use the attribute in price rule.
7)	To allow the text to be formatted with HTML, set **Allow HTML Tags on Frontend** to **Yes**. This setting makes the WYSIWYG editor available for the field. 
8)	To include the attribute in catalog page listings, set **Visible on Catalog Pages on Storefront** to **Yes**
9)	Complete the following settings if supported by your theme:
- To include the attribute on the product detail page, set Visible on Catalog Pages on Storefront to **Yes**
- To include the attribute in product listings, set Used in Product Listing to **Yes**

To use attribute as a sort parameter for product listings, set Used for Sorting in Product Listing to **Yes**

 ![Anh 34]()

When complete, click **Save Attribute**.

#### Attribute Set 
Path: **Stores > Attributes** section **> Attribute set**

##### Manage Attribute Set

 ![Anh 35]()

1)	Click **Add Attribute Set** to create new attribute set.
2)	Fill out the blank with a value to search, after click **Search**.
3)	Search attribute set information with keyword.

You can view or edit details of attribute set by clicking on each line.

##### Create A New Attribute Set

 ![Anh 36]()
Click **Add Attribute Set** to create new attribute set.

 ![Anh 37]()

1)	In the **Name** field, enter a name for the attribute set (required)
2)	In the **Based On** field, select an existing attribute set to be used as a template:
- Bag
- Bottom
- Default
- Downloadable
- Gear
- Sprite Static Ball
- Sprite Yoga Strap
- Top
3)	Click **Save** button and continue

 ![Anh 38]()

To add a new attribute to the set, drag the attribute from the Unassigned Attribute list to the appropriate folder in the General group.

Click **Save** to complete the process.

#### Categories
Path: **Products > Inventory** section **> Categories**

##### Manage Categories  
When selecting a category on the left, all the information will be displayed on the left.

 ![Anh 39]()

##### Create A New Category

 ![Anh 40]()

**Create a Category**
 ![Anh 41]()

Path: **Products > Inventory** section **> Categories**

Set Store View to determine where the new category is to be available. In the category tree, tap the parent category of the new category. The parent is one level above the new category.

If you’re starting from the beginning without any data, there might be only two categories in the list: **Default Category**, which is the root, and an **Example Category**. 

Click **Add Sub-category** to add a new category.

 ![Anh 42]()

**Complete the Basic information**
1)	If you want the category to be immediately available in the store, set **Enable Category** to the **Yes** position.
2)	To include the category in the top navigation, set Include in Menu to the **Yes** position.
3)	Enter the **Category Name**.
4)	Click **Save**.

  ![Anh 43]()

Complete the Category Content

1)	To display a Category Image at the top of the page, tap **Upload**. Then, choose the image that you want to represent the category.
2)	In the **Description** box, enter the text that you want to appear on the category landing page. Then, format the text as needed.
3)	To include a content block on the category landing page, choose the CMS Block that you want to appear. 
4)	Click **Save**.
 
![Anh 44]()

Complete the **Display Settings**
Expand the **Display Settings** section.
1)	Set Display Mode to one of the following:
- Products Only.
- Static Block Only.
- Static Block and Products.
2)	If you want the category page to include the **Filter by Attribute** section of layered navigation, set Anchor to the **Yes** position.
3)	To change the Available Product Listing Sort By options, do the following: 
- Clear the **Use All checkbox**. 
- Select one or more of the available values to be available for customers to sort the list. By default, all available values are included. For example, the values might include:
 - Position.
 - Product Name.
 - Price 5.
4)	To set the default sort order for the category, choose the **Default Product Listing Sort By value.**
5)	To change the default layered navigation price step setting, do the following:
- Clear the **Use Config Settings** checkbox.
- Enter the value to be used as an incremental price step for layered navigation.

6)	Click **Save**.
 
![Anh 45]()

Complete the **Search Engine Optimization Settings**

Expand the Search Engine Optimization Settings section
1)	Enter a URL Key for the category, or let the system automatically create one that is based on the category name.

Complete the following meta data for the category:
2)	Meta Title.
3)	Meta Keywords.
4)	Meta Description.
5)	Click **Save**.

 ![Anh 46]()

Choose the **Products** in **Category**
Expand the Products in Category section. Then, use one of the following methods to add products to the category. 

To find the products:
1)	Fill out the blank with a value.
2)	Click Search to find the products.
To include a product in the category. 
3)	Mark the checkbox of each product, in the first column.
4)	Click **Save**.

#### Product Types
Path: **Products > Inventory** section **> Catalog**

##### Product Types 

| Product Types	|Description|
|--|--|
|Simple Product|	A simple product is a physical item with a single SKU. Simple products have a variety of pricing and of input controls which makes it possible to sell variations of the product. Simple products can be used in association with grouped, bundle, and configurable products.| 
Configurable Product| 	A configurable product appears to be a single product with lists of options for each variation. However, each option represents a separate, simple product with a distinct SKU, which makes it possible to track inventory for each variation.| 
Grouped Product| A grouped product presents multiple, standalone products as a group. You can offer variations of a single product, or group them for a promotion. The products can be purchased separately, or as a group.|
Virtual Product|	Virtual products are not tangible products, and are typically used for products such as services, memberships, warranties, and subscriptions. Virtual products can be used in association with grouped and bundle products.|
Bundle Product|	A bundle product let customers “build their own” from an as sort of options. The bundle could be a gift basket, computer, or any things else that can be customized. Each item in the bundle is a separate, standalone product.|
Downloadable Product	|A digitally downloadable product that consists of one or more files that are downloaded. The files can reside on your server or be provided as URLs to any other server.|

##### Manage Product 
Path: **Products > Inventory** section **> Catalog**
 ![Anh 47]()

**Workspace Controls**
| Control	|Description|
|--|--|
|Add Product|	Initiates the process to create a new simple product. To choose a specific product type, click the down arrow. Options: **Simple Product**/ **Configurable Product**. 
|| (1)	Grouped Product; (2) Virtual Product; (3)	Bundle Product; (4)	Downloadable Product|
| Action| Lists all actions that can be applied to selected products in the list. To apply an action to a product or group of products, mark the check box in the first column of each product. Options: (5)	Delete; (6)	Change Status; (7)	Update Attributes.| 
Filters| Initiates a catalog search based on the current filters.|
Edit|	Opens the product in edit mode or view product’s detail.  You can accomplish the same thing by clicking any where on the row.| 

##### Create A New Product 
**Simple product**

  ![Anh 48]()

In the upper-right corner on the Add Product ![Anh 49]() menu, choose Simple Product.

 ![Anh 50]()

Choose the attribute set that is used as a template for the product.
 ![Anh 51]()
 
**Complete the required setting**.
1)	Enter **Product Name**. *(required)*
2)	The default SKU that is based on the product name, or enter another.
3)	**Price**: enter the product price.

Then, Click **Save** to continue.
 
 ![Anh 52]()

**Complete the basic settings**

Set Tax Class to one of the following:
1)	Taxable Goods/None
2)	Enter the Quantity of the product that is currently in stock. 
3)	By default, Stock Status is set to **In Stock**
4)	Enter the Weight of the product.
5)	Assign Categories to the product. Tap the **Select** to select available category or you can create new category by click  ![Anh 53]() 
6)	Accept the default Visibility setting, **Catalog, Search**.
7)	Mark the Set Product as New checkbox to add the product in the list of new products.
8)	Choose the Country of Manufacture.
9)	Enable **On Web POS**

Then, click **Save** to continue

 ![Anh 54]()

Complete the product information
Scroll down and complete the information in the following sections as needed:
 o	Content
 o	Configurations
 o	Images and Videos
 o	Search Engine Optimization
 o	Related Products, Up-Sells, and Cross-Sells
 o	Customizable Options
 o	Products in Websites
 o	Design
 o	Schedule Design Update
 o	Gift Options
 o	Downloadable Information
 o	Barcode
 o	Suppliers

**Configurable product**
Create a new configurable product
 ![Anh 55]()

In the upper-right corner on the **Add Product**  ![Anh 56]() menu, choose **Configurable Product**.

 ![Anh 56]()

Choose the attribute set that is used as a template for the product.
 
  ![Anh 57]()

Complete the required setting
1)	Enter **Product Name**. (required)
2)	The default SKU that is based on the product name, or enter another.
3)	Enter the product Price.
4)	Click **Save** to continue.

 ![Anh 58]()

Complete the basic settings
1)	Set Tax Class to one of the following:
- None.
- Taxable Goods.
2)	Enter the Quantity of the product that is currently in stock. 
3)	By default, Stock Status is set to **In Stock**.
4)	Enter the Weight of the product.
5)	Assign Categories to the product. Tap the **Select** to select available category or you can create new category by click ![Anh 59]() 
6)	Accept the default Visibility setting, **Catalog, Search**.
7)	To feature Mark the Set Product as New checkbox to add the product in the list of new products.
8)	Choose the Country of Manufacture.
9)	Enable on Web POS

Then, click **Save** to continue.

 ![Anh 60]()
Complete the product information.

**Adding configurations**
 ![Anh 61]()

After creating a product, scroll down the **Configuration** section **>** Click **Create Configurations**.
 ![Anh 62]()

Choose the attributes
1)	Mark the checkbox of each attribute that you want to include as a configuration.
2)	Add a new attribute.
3)	Click to continue.
 ![Anh 63]()

For each attribute, mark the checkbox of the values that apply to the product.

Click **Next to continue**
 ![Anh 64]()
 
Configure the Images, Price, and Quantity.

Click **Next** to continue.

You will see list product.
 
 ![Anh 65]()
Click **Next** to finish the process.

**Grouped product**

In the upper-right corner on the **Add Product**  ![Anh 66]() menu, choose **Grouped Product**.
 ![Anh 66]()
Choose the attribute set that is used as a template for the product.
  ![Anh 67]()

Complete the required setting
1)	Enter **Product Name**. (required)
2)	The default SKU that is based on the product name, or enter another.
3)	Enter the Quantity of the product that is currently in stock 

Then, Click **Save to continue**.
 ![Anh 68]()

Complete the basic settings
1)	By default, Stock Status is set to **In Stock**
2)	Assign Categories to the product. Tap the **Select** to select available category or you can create new category by click ![Anh 69]()
3)	Accept the default Visibility setting, **Catalog, Search**.
4)	To feature Mark the Set Product as New checkbox to add the product in the list of new products.
5)	Choose the Country of Manufacture.
6)	Enable on Web POS

Then, click **Save to continue**.

**Add products to Group**
 
  ![Anh 69]()
  ![Anh 70]()

1)	Select product that you want to include in the group.
2)	Click to add them to group.
   
   ![Anh 71]()
1)	Enter a quantity.
2)	Remove a product from group.

Click **Save** to finish the process.
  
  ![Anh 72]()
Complete the product information

**Virtual product**

Aside from the absence of the Weight field, the process of creating a virtual product and a simple product is the same.

**Bundle product**
  
  ![Anh 73]()
In the upper-right corner on the Add Product ![Anh 74]() menu, choose Bundle Product.
  
  ![Anh 74]()
Choose the attribute set that is used as a template for the product

  ![Anh 75]()
Complete the required setting
1)	Enter Product Name. (required)
2)	The default SKU that is based on the product name, or enter another.
3)	Enter the product Price.

Then, Click **Save to continue**.

  ![Anh 76]()

Complete the basic settings
1)	Enable **Dynamic Price**
2)	Set Tax Class to one of the following:
- None
- Taxable Goods.
3)	Enter the Quantity of the product that is currently in stock. 
4)	By default, Stock Status is set to In Stock
(5)	Enter the Dynamic Weight of product.
(6)	Assign Categories to the product. Tap the Select to select available category or you can create new category by clicking on   
(7)	Accept the default Visibility setting, Catalog, Search
(8)	To feature Mark the Set Product as New checkbox to add the product in the list of new products.
(9)	Choose the Country of Manufacture.
(10)	Enable on Web POS
Finally, click Save to continue.
 
Add Bundle items
Scroll down to the Bundle Items section. Then, set Ship Bundle Items one of the following:
1.	Separately
2.	Together
Click Add Option

 
(1)	Option Title to be used field label.
(2)	Set Input Type to one of the following:
•	Drop-down.
•	Radio buttons.
•	Checkbox.
•	Multiple Select.
(3)	Mark to make the field a required entry.
(4)	Tap Add Products to Option, then mark the checkbox of each product that you want to include in this option.
 
Mark the checkbox of each product.
Click Add Selected Products, you will see.

 
(1)	Mark the checkbox of a product that you want it is default.
(2)	Enter Default Quantity.
Finally, click Save.
 
Complete products information

Downloadable product
 
In the upper-right corner on the Add Product    menu, choose Downloadable Product.

 
Choose Downloadable as the attribute set
 
Complete the required setting
(1)	Enter Product Name. (required)
(2)	The default SKU that is based on the product name, or enter another
(3)	Enter the product Price

Then, Click Save to continue.

 
Complete the basic settings
(1)	Set Tax Class to one of the following:
•	None.
•	Taxable Goods
(2)	Enter the Quantity of the product that is currently in stock. 
(3)	By default, Stock Status is set to Out of Stock.
(4)	The Weight is not used, because downloadable products are not shipped.
(5)	Assign Categories to the product. Tap the Select to select available category or you can create new category by clicking on   
(6)	Accept the default Visibility setting, Catalog, Search.
(7)	To feature Mark the Set Product as New checkbox to add the product in the list of new products.
(8)	Enable on Web POS
Then, click Save to continue.

 
Complete downloadable product.
1.	Mark the checkbox “Is this downloadable product”
2.	Enter the Title - to use as a heading for the download links.
3.	Click Add Link, then:
               Enter Title and Price. For both File and Sample files, choose:
•	Upload File: To upload the the distribution file to the server. Browse to the file, and select it for upload.
•	URL: To access the distribution file from a URL. Enter the full URL to the download file.

 
Complete the Sample.
(1) Enter the Title - to use as a heading for the samples.
(2) Enter the Title of the individual sample.
(3) Choose distribution methods.
(4) Click to add another sample.
When complete, click Save.

 
Complete the product information

4.1.4.4. Product Setting
a.	Content
 
(1)	Click on Products
(2)	Click on Catalog
(3)	Click on Edit
 
Scroll down to Content, and click on  , then write the description for the product, and the click Save on top right of the screen

b.	Images and Videos
 
(1)	Click on products
(2)	Click on catalog
(3)	Click on edit of product
 
Scroll down to Images And Videos, and click on  , then click on Browse to find or drag image here to upload new image

 
Click on Add Video to add new video
 
Fill in the box and the click on Choose File to upload new video

c.	Search Engine Optimization
 
(1)	Click on Products
(2)	Click on Catalog
(3)	Click on Edit of product
 
Scroll down to search Engine Optimization, and click on  , then fill in the box

d.	Related Products, Up-sells and Cross-sells 
 
(5)	Click on respectively
-	Add Related Products
-	Add Up-sell Products
-	Add Cross-sell Products
 
(2) Mark the checkbox to select products
(3) Click on Add Selected Product
 
(4)	Click on Save to finish

e.	Customizable Options
 
This function allows users to set and manage extra price for each product's variant separately.
Users can simply set the extra price to be applied on a product's variant, regardless of its attribute and attribute value.
(1)	Click on Add Option
(2)	Enter the option tittle
(3)	Select an option type 
(4)	Mark the checkbox to require 
(5)	Click on Add Value
(6)	Enter a title for the value
(7)	Enter an extra price
(8)	Select a price type
(9)	Enter an SKU for each product’s variant
To remove a value, click   on the right hand-side of the column 

f.	Gift Option
 
(1)	Click on Products
(2)	Click on Catalog
(3)	Click on Edit of a product
 
Scroll down to Gift Option, and click  on  , then set the allow gift massage to Yes

g.	Downloadable Information
 
(1)	Mark the checkbox
(2)	Enter a title for the download link
(3)	Mark the checkbox (if applicable)
(4)	Click “Add Link”, then do the following:
(5)	Enter a title for the download
(6)	Enter a number as a price for the download
(7)	Select an upload method for a file (Upload File/ Use URL)
(8)	Select an upload method for a file (Upload File/ Use URL)
(9)	Select a label in the dropdown list: 
•	No: to requires customers to log in to their accounts to access the download link. 
•	Yes: Sends the link by email, which customers can share with others. 
•	Uses Config: Uses the method that is specified in the Dowloadable Product Options configuration. 
(10)	Enter the number of “Max. downloads” to limit downloads per customer. 
Otherwise, to allow unlimited downloads, mark the “Unlimited” checkbox

h.	Barcode
 
(1)	Enter barcode 
(2)	Select a barcode template and see the preview as below 
(3)	Enter the quantity to print out
(4)	Click on Save to finish

i.	Suppliers
 
(1)	Click on Add Supplier
 
(2)	Mark the checkbox to select suppliers
(3)	Click on Add Selected Supplier
 
(4)	Enter the Supplier SKU, Cost, Tax
(5)	Click Save to finish

4.2.	Customer 
Path: Customers > All customers
4.2.1.	Manage Customer 
 
(1)	Click Add New Customer to create new customer.
(2)	Click Filters or fill out key word to search customer information.
(3)	Action: First, select a customer, then you can:
•	Delete
•	Subscribe to Newsletter.
•	Unsubscribe from Newsletter.
•	Assign a Customer Group.
•	Edit
(4)	Click Edit to view customer’s details and edit.
4.2.2.	Create New Customer 
 
Click Add New Customer.
 
Fill out all the required fields with information of a customer.
•	Associate to Website.
•	Group.
•	First Name.
•	Last Name.
•	Email.
 
Click Save Customer to complete the process.
4.3.	Warehouse
Path: Inventory Management > Stock Listing section > Warehouse
Please refer to Section 5.1.1.3. Warehouse for details.

4.4.	Location
Path: Sales > Web POS section > Manage Locations
 
(1) Click on Add Location to create new locations
(2) Additional Guidance: Click on Edit to amend existing locations’ information.
 
On the pop-up screen:
(1)	Fill in the Location Name (required)
(2)	Fill in the location Address field
(3)	Fill in the location Description field
(4)	Choose the Warehouse. 
•	If you already assign a location to your Primary Warehouse, you won’t be able to assign it again here. 
•	If you want to assign a new location to your Primary Warehouse, you need to Edit this field of the currently assigned warehouse to Don’t link to any Warehouses, then come back to the new location that you wish to assign and assign it to Primary Warehouse.
(5)	Click on Save

4.5.	Store (POS) 
Path: Sales > Web POS section > Manage POS
4.5.1.	Create A New Web POS 
   
Click Add POS
 Fill out or select all the re quired fields.
(1) POS Name: POS’s name. (re quired)
(2) Location: POS’s location. (required). Here, admin can choose the location created and mapped to Warehouse. So that, the admin can control both warehouse and location easily.
(3) Store View: (required)
(4) Current Staff: Staff is working on the POS.
(5) Status: you Enable or Disable this POS
(6) When checked: another staff can use the POS when it is available.

 
Click Save to complete the process.

Note: Even when you set the warehouse to a certain location, with online store, admin can see clearly warehouse information in any location. HOWEVER, with offline store, only Sales Manager can view the warehouse information only in the mapped location.
IT Admin can give other admin permission to view the Inventory information in any location by going to System > User Roles > Add new role or Edit role > Role Resource

4.5.2.	Manage Web POS 
Path: Sale > Web POS section > Manage POS
 
(1)	Click Add POS to create new POS.
(2)	Click Filters to search POS information.
(3)	If you want to delete a POS, first select a POS, then click Actions: choose Delete.
(4)	Click Detail to view a POS’s details or edit




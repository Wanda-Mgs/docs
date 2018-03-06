# OMNICHANNEL SOLUTION GROWTH PACKAGE - USER GUIDE FOR MAGENTO 1

----------------------

## INTRODUCTION 

Having seamless integration between **POS (Point of Sale)** and **Inventory Management** brings huge benefits to retailers. Magestore understand this issue deeply. Hence, in our continuous effort to give the best to e-commerce businesses, we offer you an **[Omnichannel Solution] (https://www.magestore.com/omnichannel-retail) - Growth package for Magento 1**. This product is tailor-made for online-to-offline retailers with one single warehouse which includes 2 essential functions i.e. POS and In-stock Management. 

In this detailed user guide, we’re glad to show you how to use and take advantage of this product. With the latest upgraded version, we hope that you will enjoy and greatly benefit from our solution.

-------------------

## HOW TO CONGIFURE 

### WEB POS 

#### Add New POS and Assign It to Cashier 

##### Create A New POS 

![Sample](./Image_Growth_m1/image002.png?raw=true)

Path: Sales > Web POS section > Manage POS

![Sample](./Image_Growth_m1/image003.png?raw=true)

Click on Add POS button. Then you will be linked to the New POS site

There are 4 sections will be displayed, including POS Information; Cash Denominations; Close Sessions; Current Sessions Detail

**POS information** 

![Sample](./Image_Growth_m1/image004.png?raw=true)

(1) **POS Name**: enter POS’s name.

(2) **Location**: POS’s location. Note that multiple POS can link to one location. Here, admin can choose the location created and mapped to Warehouse. So that, the admin can control both warehouse and location easily (see Section 4.5.2. Mapping Locations - Warehouses).

(3) **Current User**: Staff is working on the POS.

(4) **Status**: select to **Enable** or **Disable** this POS

**Closed Sessions**

![Sample](./Image_Growth_m1/image005.png?raw=true)

This section will display the statistics of Closed Sessions after staff working days. When you create a brand-new POS, this section is empty, and it will be updated automatically after being used in reality. 

**Current Session Detail** 

The same situation happens with Current Session Detail for the brand-new POS. No data is saved, and it will display like this: 

![Sample](./Image_Growth_m1/image006.png?raw=true)

And here is the performance of working POS: 

![Sample](./Image_Growth_m1/image007.png?raw=true)

##### Assign New POS to Cashiers 

Path: Sales > Web POS section > Web POS Permissions > POS Users

![Sample](./Image_Growth_m1/image008.png?raw=true)

(1) **Add User** button: to add POS to new cashier, click on this button and follow the guide in the Section 3.2. How to manage staff in Web POS

(2) **Action** field: to assign POS to recent cashiers, click on Edit, then:

![Sample](./Image_Growth_m1/image009.png?raw=true)

On the User Settings tab, edit these fields:

(1) **Locations** : select the locations your staff are working

(2) **POS**: select POS that you want to assign to your cashier (can choose more than one by holding Ctrl + Click)

(3) **Role**: edit role _(if needed)_

(4) **Status**: choose Enabled if you want to activate the staff work

#### Diffirentiate Access Permission 

Refer to the Section 3.2. How to manage staff

#### General Settings 

![Sample](./Image_Growth_m1/image010.png?raw=true)

(1) **Web POS logo**: Click on Choose File to upload your Website Logo.  Please notice that: Recommended image size: 260x120 px and supported file: jpeg, png

(2) **Web POS Color**: Enter the Hex Code of your Web color

(3) **Enable Cash Drawers**: Choose **Yes** to enable **Cash Drawers**

(4) **Enable Delivery Date**: Choose **Yes** to enable **Delivery Date**

(5) **Allow to sync orders out-of-stock items**: Choose Yes to sync orders of out-of-stock items

(6) **Session Timeout**: Enter the number of seconds

(7) **Integrate with Pole Display device**: Choose Yes to integrate with Pole Display Device. You should install Customer Pole Display’s Driver. After that, you need to install the desktop application to connect your PC/ Laptop with the pole. 

Notes: after purchasing Magento Omni-channel Module, you can download the Pole Display integration file which contains these following files & folders:

![Sample](./Image_Growth_m1/image011.png?raw=true)

Then follow these steps:

_**Step 1: Install the .NET Framework 4.5.2**_
Open the folder .NET Framework 4.5.2
Run NDP452-KB2901907-x86-x64-AllOS-ENU.exe file and install it to

_**Step 2: Install the USB to Serial COM setup**_
Open the folder USB to Serial COM
Run CDM21224_Setup.exe and install it to your computer

_**Step 3: Run the Pole Integration.exe file**_

![Sample](./Image_Growth_m1/image012.png?raw=true)

You need to open this program when using Web POS to use Customer Pole Display

(8) **Default Website**: Choose your Default Website

(9) **Need to confirm before deleting order (App only)**: If you use Web POS App on mobile or tablet, choose Yes to allow a Confirmation Pop-up that you want to delete order

(10) **Need to create session before working (App only)**: With Web POS App users, choose Yes to activate creating session before working

(11) **Active Key for using App**: Enter your activation code to use Web POS App

#### Set up Shipping Method

![Sample](./Image_Growth_m1/image013.png?raw=true)

(1) **Offline shipping Methods**: Choose Offline shipping methods that you offer for your customer, including: Fixed Flat Rate, Free Shipping, Store Pickup, Custom Method

(2) **Default Shipping Method**: Choose **Default Shipping Method**. There are various options for you to choose. If you don’t have any, choose **None**

#### Enable Payment Method

![Sample](./Image_Growth_m1/image014.png?raw=true)

(1) **Applicable Payments**: If you choose 
**Specific Payments**, a **Specific Payments** field will appear for you to choose your preferred payments. 

**All Allowed Payments**, then you allow all payments on the POS (the **Specific Payments** field will NOT appear)

(2) **Default Payment Method**: Choose **Default Payment Method**. If you don’t have any, choose **None** 
Notes: If you also use **Web POS App** on mobile and tablet, notice these following steps: 

(3) **Allow Customer pay via PayPal**:

If you choose **No**, then your customers cannot pay via PayPal service

If you choose **Yes**, then

![Sample](./Image_Growth_m1/image015.png?raw=true)

[1] Enter your application **Client ID** and your **Application Client Secret**

[2] Choose **Yes** to activate **Sandbox Mode** for better security

[3] Choose **Yes** to allow **PayPal Here** on Web POS

(4) **Redirect URL**: Redirect your byers back to your website after completing the payment. You need to sign in your PayPal account.  Then, select **Profile** > **Profile and Settings** > **My setting tools** > click **Update** next to Website Preferences > Select **On** next to **Auto Return** > In the Return URL field, enter the URL where you want to send your payer after payment is completed _(you can copy and paste the link we provide to test)_

(5) **Allow customer pay via authorize.net**: Choose **Yes** if you want to allow customer to pay via **authorize.net**

(6) **Allow customer pay via Stripe**: Choose **Yes** if you want to allow customer to pay via **Stripe**

#### Configure Product Search 

![Sample](./Image_Growth_m1/image016.png?raw=true)

(1) **Product Attribute(s) for Search**: Select your preferred **Product Attribute(s) for Search.**

Notes: Only select necessary attributes, or else the loading speed will be slow

(2) **Barcode Attributes**: Select **Barcode Attributes**. You can only change this configuration if you already have a barcode attribute

(3) Show inactive categories: Choose No to hide inactive categories for your Web POS Store View

#### Configure Default Guest Checkout 

![Sample](./Image_Growth_m1/image017.png?raw=true)

Fill in the **Default Customer ID.**

OR ELSE, you can set the field blank to create automatically a new customer with information fields below it. Then, you fill in **First Name, Last Name, Street, Country, State/Province, City, Zip/Postal Code, Telephone** and **Email**

#### Configure Default Email 

![Sample](./Image_Growth_m1/image018.png?raw=true)

(1) **Orders**

Choose **Yes** to activate automatic Order Confirmation Email

The Email Template is set as the **Store’s Default Template**

(2) **Invoices** 

Choose **Yes** to activate automatic Invoice Email
The Email Template is set as the **Store’s Default Template**

(3) **Shipments** 

Choose **Yes** to activate automatic Shipment Email

The Email Template is set as the **Store’s Default Template**

(4) **Credit Memos**

Choose **Yes** to automatically send your customers email about their **Store Credit Transaction**

The Email Template is set as the **Store’s Default Template**

#### Configure Receipt Printing 

![Sample](./Image_Growth_m1/image019.png?raw=true)

(1) Choose **Yes** to activate **Auto-print Receipt After Placing Order**. 

Notes: The function cannot work if your browser blocks automatic pop-up. 

(2) **Content**:

Choose **fonts**: Monospace or Sans-serif

With **Footer** and **Header** Text, you can fill in the content and choose simple **HTML** tags.

(3) **Optional Fields**:
Choose **Yes** to show **Web POS logo**, **Cashier name**, **Comment** and **Barcode** _(encode order increment ID)_

#### How WEB POS Works with Peripheral Devices 

Magestore’s Web POS module can connect with **Barcode readers**, **Card swiper & Receipt printers.**

**Barcode readers**: are any devices that can connect with iPad/Laptop/PC (including USB Port, Wifi or Bluetooth). The scanner can read barcodes & fill encoded information into Web POS search box.

**Card swiper**: only devices connected through USB port (supports Authorize.Net & Stripe).

**Receipt printers**: any devices that connect with iPad/laptop/PC

### Retailer POS 

Path: _**Sales**_ > _**Web POS**_ section > _**Settings**_

Note: Most settings for Retailer POS like shipping, payment, etc. are the same with Web POS. Please refer to the section 2.1.Web POS for more details.

_This section only mentions the settings that are specifically for Retailer POS_

#### Set Up General Information 

![Sample](./Image_Growth_m1/image020.png?raw=true)

**Need to confirm before deleting order (App only)**: requires cashier to confirm again before he/she can delete an order during checkout.

**Active key for using App**: enter the key required to activate the app.

#### Set Up Shipping Method for Retailer POS 

Our Retailer POS allows customers pay for their order via Authorize.net and Stripe. Enable this payment in Retailer POS frontend by selecting Yes in their setting. 

There is also detailed installation guide and Test the API connection function available for each method.

For other shipping settings, please refer to the section 2.1.4. Set up Shipping Method

#### Connect Retailer POS with Peripheral Devices 

Magestore’s Retailer POS module can connect with **Barcode readers, Card Swipe, Wireless Cash Drawer & Receipt printers**

- Card Swipe (via Audio jack)

- Receipt printer

- Barcode scanner (connected via Bluetooth device/iPad camera)

- Wireless Cash Drawer

### Muti-warehouse Management 

#### Stock Control Configuration 

_Path: **Inventory Management > Settings**_

![Sample](./Image_Growth_m1/image021.png?raw=true)

Then you will access to a page as below:

![Sample](./Image_Growth_m1/image022.png?raw=true)

(1) **Link warehouse  to Magento Front Store View**: In managing a Warehouse, you can link Warehouse to a Front Store View (path: **Stock Listing > Warehouses > Click View > Warehouse Information section > General Information > Magento Store View** with screenshot below). Note that you can link a warehouse to one or multiple store views.

![Sample](./Image_Growth_m1/image023.png?raw=true)

- If you enable **Link warehouse to Magento Front Store View** by choosing **Yes** here, stock in warehouse will be displayed on the linked store view. When customers buy on this store view, stock quantity will be deducted from this linked warehouse.

- If choose **No**, stocks in all warehouses will be shown on the store view.

(2) **Adjust Stock by entering the change Qty.: **

- If this feature is **enabled**, when adjusting stock, you can enter the difference quantity and the system will calculate the final balance in warehouse.

- If this feature is **disabled**, you need to enter the exact quantity of stock in warehouse and the system will receive this figure as the latest available quantity of product.

#### Stock Option 

_Path: **System** > **Configuration** section > **Catalog** > **Inventory** > **Stock Options**

![Sample](./Image_Growth_m1/image024.png?raw=true)

(1) **Decrease Stock When Order is Placed**: Select **Yes** in the dropdown list to adjust the quantity on hand when an order is placed.

(2) **Set Items’ Status to be In Stock When Order is Cancelled**: Select **Yes** in the dropdown list to return items to stock if an order is cancelled.

(3) **Display Out of Stock Products**: Select **Yes** in the dropdown list to continue to display products in the catalogue that are no longer in stock. 

(4) **Only X left Threshold**: Enter the number in the blank to display the message: **Only x left** on website when the quantity in stock reaches the threshold.  

(5) **Display products availability in stock in the frontend**: Select **Yes** in dropdown list to display an **In Stock** or **Out of Stock** message on the product page.

(6) Click on **Save Config** button to finish. 

#### Product Stock Options 

_Path: **System** > **Configuration** section > **Catalog** > **Inventory** > **Product Stock Options**_

![Sample](./Image_Growth_m1/image025.png?raw=true)

(1)**Manage Stock**: Select Yes to activate inventory control for your catalog. 

(2) **Backorders**: select

- **Backorders** to one of the following status: 

- **No Backorders** to reject backorders when product is out of stock.

- **Allow Qty. Below 0** to accept backorders when the quantity falls below zero. 

- **Allow Qty. Below 0 and Notify Customer** to accept backorders when the quantity falls below zero, and notify the customer that the order can still be placed.

(3) **Maximum Qty. Allowed in Shopping Cart**: Enter the **Maximum Qty**. allowed in Shopping Cart.

(4) **Qty. for Item’s Status to Become Out of Stock**: Enter the quantity for Item's Status to become out of stock.

(5) **Minimum Qty. Allowed in Shopping Cart**: Enter the **Minimum** quantity allowed in Shopping Cart.

Next, 

![Sample](./Image_Growth_m1/image026.png?raw=true)

(6) **Notify for Quantity Below**: Enter the stock level that generates notification showing the item is out of stock.

(7) **Enable Qty. Increments**: Select **Yes** to activate quantity increments for the product. Then in the **Qty. Increments field**, enter the number of the items that must be purchased to meet the requirement mentioned above.

(8) **Automatically Return Credit Memo Item to Stock**: Select **Yes** to return the item to inventory by default when a credit memo is issued for the item.

Finally, click on **Save Config** button to save changes. 

### Inventory Report 

![Sample](./Image_Growth_m1/image027.png?raw=true)

_Path: **Retailer Reports > Setting**

![Sample](./Image_Growth_m1/image028.png?raw=true)

The configuration setting of **Retailer Reports** has 2 tabs: **Historical Report Configuration** and **Sales Report Configuration**

**Historical Report Configuration**

![Sample](./Image_Growth_m1/image029.png?raw=true)

(1) **Duration**: The system only saves your historical reports within this period. You can choose from the drop-down list among _**Last 7 days, Last 30 days or Last 3 months.**_

(2) **Use Cron to auto update**: Choose **Yes**  to use Cron to auto update the reports

(3) **Auto Update Time**: Choose a time schedule when the reports will be automatically update

**Sales Report Configuration** 

![Sample](./Image_Growth_m1/image030.png?raw=true)

To automatically update Sales Report, choose **Yes**

After all, click on **Save Config** button to save your work.

### Barcode Management 

_Path: **Barcode Management > Settings**_ 

![Sample](./Image_Growth_m1/image031.png?raw=true)

(1) **One barcode per product SKU**: select **Yes** if you want to set ONE barcode/product SKU

(2) **Barcode patterns**: enter the barcode pattern used to generate barcodes.

For example,

[A.8]: 8 alpha characters

[N.4]: 4 numberic characters

[AN.6]: 6 alphanumeric characters

BAR[A.4][AN.6]: BARADFA12ND0O

(3) **Default barcode template for pricing**: select **Standard, A4** or **Jewelry**

### Purchase Management 

_Path: **Purchase Management > Setting**_

![Sample](./Image_Growth_m1/image032.png?raw=true)

In the Purchase Configuration, there are 5 tabs: **Product config, Shipping Method, Payment Method, Payment Term**, and **Tax and Shipping**

**Product Config** 

![Sample](./Image_Growth_m1/image033.png?raw=true)

In this tab, you can choose to get product from **Supplier** or **All store**

**Shipping Method** 

![Sample](./Image_Growth_m1/image034.png?raw=true)

Here you can add/edit/delete Shipping methods for purchase orders. Click **Add**, enter name of the shipping method and set its status **(Enable/Disable)**. Click **Delete** to delete a shipping method. 

**Payment Method** 

![Sample](./Image_Growth_m1/image035.png?raw=true)

This tab allows you to add/edit or delete Payment methods for purchase orders. Click on **Add**, enter name of the payment method and set status (Enable/Disable) for each one. Click **Delete** to delete a payment method.

**Payment Term**

![Sample](./Image_Growth_m1/image036.png?raw=true)

This tab allows you to add/edit or delete Payment terms for purchase orders. Click on Add, enter name of the payment term and set status (Enable/Disable) for each one. Click Delete to delete a payment term

![Sample](./Image_Growth_m1/image037.png?raw=true)

This tab allows you to choose to apply customer tax before or after Discount. Choose **Before Discount** or **After Discount** from the drop-down list. 

After finish filling all tabs, click on Save Config to save your work. 

### Gift Card 

_Path: **Gift Card > Settings**_

_**Step 1: Fill in General section**_

![Sample](./Image_Growth_m1/image038.png?raw=true)

**Enable Gift Card**: Choose **Yes** if you want to enable Gift Card. Otherwise, choose **No**

**Gift code** 

![Sample](./Image_Growth_m1/image039.png?raw=true)

(1) **Gift Code Pattern**: Configure the **pattern** to auto-generate gift codes for Gift Card products when customers purchase in Web POS frontend

(2) **The number of prefixes shown**: Enter the number of **prefix characters** which are shown in a voucher code

(3) **Replace Hidden Characters by**: Enter one letter to **replace hidden characters**

**Gift Card Usage** 

![Sample](./Image_Growth_m1/image040.png?raw=true)

(1) **Gift Cards codes expire after**: Enter the term of validity that Gift Cards can be used after being activated.

(2) **Maximum time(s) to enter gift code incorrectly**: Enter the maximum time(s) that allows users to enter gift code incorrectly.

(3) **Maximum number of users per gift code**: Enter the maximum number of users per gift code.

(4) **Enable customer’s Gift Card credit balance**: Choose **Yes** to enable customer’s Gift Card Credit Balance. Then, customers can redeem their gift code for credit balance

(5) **Allow customers to redeem Gift Cards with usage conditions**: Select Yes to allow customers to redeem Gift Cards with usage conditions 

(6) **Use Gift Cards for shipping fee**: Choose Yes to allow customer to apply gift card for shipping fee

(7) **Use Gift Cards with coupon codes**: Select Yes to allow customers to use both Gift Card codes and Coupon codes at once. 

(8) **Show the link to check Gift Cards codes on website**: Choose Yes to allow customers to check status of Gift Cards after entering Gift Codes, and vice versa.

(9) **Show Gift Card expiry date on website**: Select Yes to show the expiration date of Gift Cards on website, and vice versa.

**Tax Configuration**

![Sample](./Image_Growth_m1/image041.png?raw=true)

**Apply Gift Card Discount**: Here, you have two options to apply: 

- **After Tax**: to allow applying Gift Card after the tax is applied

- **Before Tax**: to allow applying Gift Card before the tax is applied

_**Step 2: Fill in On Product Page section**_

**Gift Card Value**

![Sample](./Image_Growth_m1/image042.png?raw=true)

(1) **Default Gift Card value**: Enter the default gift card value 

(2) **Description of Gift Card value**: Enter the description of gift card value 

**Gift Card Template**

![Sample](./Image_Growth_m1/image043.png?raw=true)

(1) **Gift Card template**: Select Yes to allow customers to change the image inserted in the template

(2) **Maximum size of image(s)**: Limit the maximum size of images uploaded by customers to 500KB

**Gift Card Shipping Information** 

![Sample](./Image_Growth_m1/image044.png?raw=true)

(1) **Allow shipping Gift Card**: Select **Yes**, then Gift card can be sent through the post office

(2) **Minimum days for store owner to send Gift Card through post office**: Choose **the number of days** that after Customers have ordered Gift Cards for friends and choose Send through post office option, Gift Cards will be sent to recipients within that number of days

(3) **Message max length**: Limit the maximum length of a custom message on Gift Card. Select Yes to allow users to schedule gift card delivery date.

(4) **Enable scheduling Gift Card delivery**: Select **Yes** to enable scheduling Gift Card Delivery. It helps customer flexibly choose their preferred date to send the Gift Card to others 

_**Step 3: Fill in On Shopping Cart Page section**_ 

![Sample](./Image_Growth_m1/image045.png?raw=true)

(1) **Show Gift Card box on shipping cart page**: Select Yes to Enable a Gift Card box for customers to apply gift codes right on the shopping cart page.

(2) **Information displayed on shipping cart page**: Select the data to display on shopping cart page

(3) **Show Gift Card image as product image in shopping cart**: Select Yes to allow showing Gift Card printout preview as product image on shopping cart page

**_Step 4: Fill in On Checkout Page section**_ 

![Sample](./Image_Growth_m1/image046.png?raw=true)

Show **Gift Card box** in the **Payment action**: Select **Yes** to show Gift Card box on the checkout page

**_Step 5: Fill in Email Notification section_**

**General 

![Sample](./Image_Growth_m1/image047.png?raw=true)

(1) **Enable email notification**: Select **Yes** to allow sending notification emails to customers and recipients

(2) **Send Gift Card to friend when Gift Card status is**: Select **Active**, only a gift card which is activated can be sent to a friend

(3) **Sender of email notification**: Set the default sender of notification emails as **General Contact**

(4) **Gift Card notes**: Enter the notes displayed in Gift Card Delivery Email 

(5) **Send Gift Card copy via email**: Select Yes to allow sending a copy of gift card via email if customers choose to ship through post office.

**Notification Email send to Purchaser**

![Sample](./Image_Growth_m1/image048.png?raw=true)

(1) Send-to-purchaser email template: Select the email template **sent to purchasers after buying Gift Card** successfully. 

(2) Send-to-purchaser email template when recipient receives Gift Card: Select the email template **sent to purchasers when recipients receive Gift Cards.**

**Notification Email send to Receiver**

![Sample](./Image_Growth_m1/image049.png?raw=true)

(1) **Send – to – recipient email template**: Select **Yes** to allow sending email notification to recipient when sender refunds Gift Card.

(2) **Send notification email to recipient when purchaser refunds Gift Card**: Select the email template sent to the gift card’s recipient.

(3) **Send-to-recipient email template when Gift Card is refunded**: Choose the email template sent to recipient when gift card is refunded.

(4) **Auto-send reminder email before Gift Card expires**: Enable auto reminder email **sent to Customers before Gift card expires**

(5) **Auto-send reminder email before**: Enter the **number of days** to **send notification to customers before the expiration date of a Gift card.

_**Step 6: Fill in Gift Card Printout section**_ 


![Sample](./Image_Growth_m1/image050.png?raw=true)

(1) **Logo on PDF Printouts**: Click on **Choose File** to upload your Logo image.

Notes: this image is used in PDF and HTML, recommended sixe is 17x63 px adn the supported format is jpeg, jpg and png

(2) **Show barcode on Gift Card**: Choose Yes to show barcode on Gift Card

(3) **Type of Barcode**: Select type of barcode shown on Gift Card 
(if you choose **Yes** on step 2)

(4) **Gift Card notes**: Enter **Gift Card Notes** 

(5) **Gift Card fold paper note**: Enter **Gift Card fold paper note** (recommed to use HTML)

### Reward Points

_**Path: Reward Points > Settings**_ 

_**Step 1: Configure the following session**_ 

**General Configuration** 

![Sample](./Image_Growth_m1/image051.png?raw=true)

(1) **Enable Reward Point extension**: Choose **Yes** to enable Reward Points Module for the Growth Edition of Omnichannel Package

(2) **Label for Point**: Enter the **Point Label**. If you leave it empty, the default label _“Point”_ will be used.

For example, if you enter “P” on this field, then instead of showing “1 Point”, it will show “1 P”.  

(3) **Label for Points (plural)** : Enter the **Point label (plural)**. _(same as step 2)_

(4) **Reward Points image**: **Choose File** to upload Reward Point Image. Notice that: the recommended size is 18x18px. If you leave it blank, the image on the template will be used instead.

(5) **Use Reward Policy page**: Choose **Yes** if you want to use Reward Policy page, otherwise select No. 

(6) **Use Reward Welcome page**: Choose **Yes** to show Reward Welcome Page, otherwise select No. 

**Earning Points Configuration** 

![Sample](./Image_Growth_m1/image052.png?raw=true)

(1) **Rounding Method**:  

You have three options for Rounding Method:

- **Normal**:  for example, 10.2 points generated from an order can be rounded to 10, and 10.8 points generated from an order can be rounded to 11.

- **Up**: for example, 10.2 points generated from an order can be rounded up to 11

- **Down**: for example, 10.2 points generated from an order can be rounded down to 10

If you finish editing the field, remember to re-index **Catalog Earning Rules**, follow the path: **Reward Points > Earning > Catalog Earning Rules** 

![Sample](./Image_Growth_m1/image053.png?raw=true)

(2) **Points expire after**: Enter the **number of dates** after which customers’ points will expire. 

(3) **Number of points in balance allowed**: Enter the **maximum number** of points allowed in Customer’s balance. If you leave it blank, there will be no limitation. 

(4) **Earn points from tax**: Choose **Yes** to allow customers to earn points from their order value including tax

(5) **Earn points from shipping fee**: Choose **Yes** to allow customers to earn points from their order value including shipping fee. 

(6) **Allow earning points when using points to spend**: Choose **Yes** to enable customers to earn points after they spend points.

**Sales Earning Process** section 

![Sample](./Image_Growth_m1/image054.png?raw=true)

(1) **Allow receiving points when invoice is created**: If **Yes**, customers receive points after an invoice is created for their order. If **No**, they receive points only when the order status is complete.

(2) **Hold point transactions for**: Enter the number of days to hold point transactions before points are rewarded to customers. If leaving it empty or zero, customer will receive the points right after they committed the action in field (1) above. 

**Spending Points Configuration Tab** 

![Sample](./Image_Growth_m1/image055.png?raw=true)

(1) **Minimum redeemable points**: Enter the minimum **number of points** in Customer’s Balance is permitted to redeem. If you leave it blank, there will be no limitation

(2) **Maximum spending points per order**: Enter the **maximum number of points** that customers can redeem in an order. If you leave it blank, there will be no limitation

(3) **Use maximum points at checkout by default**: Choose **Yes** if you allow customers to spend maximum points at checkout by default

(4) **Allow using points for Shipping Fee**: Choose **Yes** to allow customers use points as payment for **Shipping Fee**

**Display Configuration Tab**

![Sample](./Image_Growth_m1/image056.png?raw=true)
(1) **Show  total point balance next to My Account link**: Choose **Yes** to show total point balance next to My Account link

Display Collectible Points

(2)**On Product Page**: Choose **Yes** to display collectible Points on **Product Page**

(3) **On Minicart**: Choose **Yes** to display collectible points in **Mini cart**

(4) **On Product Listing Page**: Choose **Yes** to display collectible points on **Product listing page, Category and Search Result Page.**

**Email Configuration Tab**

![Sample](./Image_Growth_m1/image057.png?raw=true)
(1) **Enable notification email**: Choose **Yes** to enable notification email

(2) **Sender**: Choose the **name of the Sender** who can send email about Balance Updates and Expiration Notifications to customers:

- General Contact

- Sale Representative

- Customer Support

- Customer Email 1

- Customer Email 2
(3) **Template of email sent to customer before a transaction expires**: Choose an **Email Template** to send to customers to notify them when a transaction expires.

(4) **Send reminder email before a transaction expires**: Enter a **number of days before** a transaction expires so that your customer can receive a Reminder Email before the expiration date. 

**Loyalty Level Configuration**

![Sample](./Image_Growth_m1/image057.png?raw=true)

(1) **Enable Loyalty Level plugin**: Choose **Yes** to make different Loyalty Levels. 

(2) **Send email before level expires**: Choose **Yes** to send email before level expires

![Sample](./Image_Growth_m1/image058.png?raw=true)

(1) **Enable Rules Plugin**: Choose **Yes** to enable Rules plugin. This plugin will allow you to set rules for your Reward Points program. 

(2) **Show Earning Rule on Shopping Cart Page**: Choose **Yes** to show Earning Rule on Shopping Cart Page

**Step 2**: Remember to click on **Save Config** button to complete your configuration process.
### Store Credit 

### Store Pick up 

#### Manage Store 

#### Manage Holidays 

#### Manage Special Days 

#### Manage Tags 

#### View Pickup Orders 

#### Setiings 

## HOW TO MANAGE USER PERMISSION 

### How to Manage User Roles and Users

#### Decentrialize Roles 

#### Decentrialize Users 

### How to Manage Staff for POS

#### Decentrialize POS Access Permission 

#### Decentrialize POS Staff 

### Basic Role for Each Admin in the System (Reference Only)

#### Store Manager 

#### Inventory Manager 

#### Purchase Management 

#### Ecommerce Manager

#### Accountant 

## HOW TO MANAGE MASTER DATA 

### Product 

#### Attributes 

#### Attribute Sets 

#### Categories 

#### Products

### Customers 

#### Manage Customers 

#### Customer Groups 

### Partner/Vendor

#### Managae Supppliers

#### Add New Supplier

### Warehouse 

#### New Warehouse

#### Warehouse Management 

#### Warehouse Permission

### Location

#### Add New Location

#### Mapping Locations - Warehouses

### POS

#### Create New POS 
#### Manage WEB POS 

## HOW TO USE 

### Web POS 
#### Log in and Manage Account 
#### Manage Session

#### Filer and Search Product Quickly 

#### Add Products to Cart and Edit Product in Carts 

#### Apply Coupon Code or Discount to Cart 

#### Manage Transaction

#### How to Issue Refund 

#### How to View Report

### Retailer POS 

#### Log In and Manage Account 

#### Use Session Management 

#### Filter and Search Products Quickly 

#### Add Product to Carts and Edit Products in Cart 

#### Apply Coupon Code or Discount to Carts

#### Handle Customer's Information and Check Out 

#### Add Comment to An Order

#### Process at Checkout for Customers

#### Create Shipment

#### Issue Refund 

#### Print Receipt and Email Orders 

#### Review Order

#### Run Sales Report 

### Inventory Management 

#### Stock Listing 

#### Transfer Stock

#### Stock Control 

#### Prediction 
 
### Inventory Report 

#### Sales Report 

#### Inventory Reports 

### Barcode Management 

#### Barcode Listing  

#### Barcode Label Templates

#### Generate Barcode 

#### Import Barcode

#### Scan Barcode 

#### Print Barcode 

#### Barcode Generated History

### Purchase Management 

#### Manage Suppliers and Pricelist 

#### Manage Quotation 

#### Manage Purchase Order 

#### Return Order

### Gift Card 

#### How to Manage Gift Card 

#### How Customers Manage Gift Card 

### Reward Points 
#### How Admin Manage Reward Points 

#### How Customers Use Reward Points 

### Store Credit 

#### How Admin Manages Store Credit 

#### How Customers Use Store Credit 

### Store Pickup

#### View Store Information 

#### Use Store Pickup at Checkout 

#### Receive Order Emails



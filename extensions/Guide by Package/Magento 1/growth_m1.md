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

![Sample](./Image_Growth_m1/image058.png?raw=true)

(1) **Enable Loyalty Level plugin**: Choose **Yes** to make different Loyalty Levels. 

(2) **Send email before level expires**: Choose **Yes** to send email before level expires

![Sample](./Image_Growth_m1/image059.png?raw=true)

(1) **Enable Rules Plugin**: Choose **Yes** to enable Rules plugin. This plugin will allow you to set rules for your Reward Points program. 

(2) **Show Earning Rule on Shopping Cart Page**: Choose **Yes** to show Earning Rule on Shopping Cart Page

**Step 2**: Remember to click on **Save Config** button to complete your configuration process.

### Store Credit 

_Path:  **Store Credit > Settings**_

![Sample](./Image_Growth_m1/image060.png?raw=true)

**Step 1: Configure the following session below** 

**General Configuration** 

![Sample](./Image_Growth_m1/image061.png?raw=true)

(1) **Enable Store Credit**: Activate Store Credit on your site
(2) **Allow sending Credit**: If **Yes**, you ‘ll allow customers to send credit to their friends
(3) **Groups can use edit**: Determine which types of customer groups use credits

**Spend Credit On**

![Sample](./Image_Growth_m1/image062.png?raw=true)

(1) **Apply Customer Credit**: If you choose **After tax**, it means customer credit discount will be spent after their order value is taxed. 

(2) **Shipping fee**: If you choose **Yes**, you allow using customer credit for shipping fee. 

**Email Configuration**

![Sample](./Image_Growth_m1/image063.png?raw=true)

(1) **Email template with credit code sent to recipients**: Choose a suitable template with credit code which will be sent to recipients. 
(2) **Email template with a verification code sent to credit sender**: Choose a suitable email template including verification code which will be sent to credit sender. 

(3) **Send-to-customer email template when recipient receives credit**:  Choose a suitable email template to notify recipients when they receive credit.

(4) **Email template notifying customers**: Choose a suitable email template to notify customers.

**Adjust time for Customers credit reports on total used and total received credit**

![Sample](./Image_Growth_m1/image064.png?raw=true)

(1) **Select start time for current year**: choose Start Date and month of the year to report used credit and received credit. 

(2) **Select date for current month**: choose Start Date of the current month to report used credit and received credit. 

**Style Configuration**
On this tab, you will be able to change background and color of Title

![Sample](./Image_Growth_m1/image065.png?raw=true)

(1) **Background of Title**: enter Hexadecimal code

(2) **Color of Title**: enter a Hexadecimal code or choose a color as above.

(3) **Default Font Size**: enter a font size.

**Step 2**:

Remember to click on **Save Config** button to complete your configuration process.

### Store Pick up 

You have seen how Store Pickup works in front-end for customers. The following part will guide you through how to configure and manage the module in back-end.

_Tips_: For quick instructions on where to set up each function and how to get Google Map API Key, you can go to: **Store Pickup > Settings > General**

Click on the link for Google Map API Key Registration Guide

![Sample](./Image_Growth_m1/image066.png?raw=true)

_Update_: **One of the most important Google Maps APIs Standard Plan updates implemented on June 22, 2016 was that** required future product updates are only available for requests made with an API key.

This means active domains created before June 22, 2016, continue to be able to access the Google Maps JavaScript API, Static Maps API, and Street View Image API without an API key. They are not affected by keyless access being unavailable for new domains.

However, Google Maps APIs Standard Plan advises all developers to use a key to guarantee their quality of service. Applications that continue to make keyless requests may experience some periodic service degradation if other keyless applications' usage spikes and draws down the global unchanged quota.

#### Manage Store 

_Path: **Store Pickup > Manage Stores**_

The **Store Manager** grid shows all stores created in your system with their address and status. To add new stores, you can add them manually and import from CSV files.

###### Add Store 

_Path: **Store Pickup > Manage Stores**_

![Sample](./Image_Growth_m1/image067.png?raw=true)

Here you can add new stores by importing via a CSV file or manually input information with **Add New Store** button. You will be navigated to the **Add Store** page, which includes 3 tabs:

- General Information

- Time Schedule

- Customer Message

_Notes_: Before reading the detailed function of each tab, please remember to click **Save Store** after making changes on these tabs to apply the changes before you leave.

![Sample](./Image_Growth_m1/image068.png?raw=true)

**a) General Information** 

**Store Information** 

![Sample](./Image_Growth_m1/image069.png?raw=true)

Users must fill in all required fields, such as _**Store name, Shipping Fee, Address, etc.**_

_Tips_: You can input content for the **Description field** in HTML for better display in frontend, such as customized format, attached links, etc.

**Contact Information**

![Sample](./Image_Growth_m1/image070.png?raw=true)

It allows you to enter information of store’s manager such as email address, phone number, etc. so customers will know how to contact if needed. You can configure to enable automatic emails sent to the store manager when pickup orders’ status is changed.

**Google Map**

![Sample](./Image_Growth_m1/image071.png?raw=true)

Fill your store’s address in this field or pin from the map, remember to click on the Save Store or Save And Continue Edit button to save your work. After that, store’s location will be updated automatically on Google Map.

There are 5 sessions: 

- **Zoom Level**: It is used when previewing the store’s location on Google Map in backend and on the Store Listing page in frontend. The higher number you set, the higher zoom-in level is

- **Store Latitude**: You do not need to fill them out if you do not remember your store’s coordinates. If you pin a store directly from G-map, these fields will be filled automatically

- **Store Longitude**: You do not need to fill them out if you do not remember your store’s coordinates. If you pin a store directly from G-map, these fields will be filled automatically

- **Pin Color**: Set a color to display your store’s pin on Map

- **Store icon**: you can upload your own image to replace the default marker icon of Google on the map

**b) Time Schedule** 

![Sample](./Image_Growth_m1/image072.png?raw=true)

This tab allows you to create a time schedule for store on each day, from Monday to Sunday

(1) **Open** - Choose **Yes** to set Monday as a working day, choose **No** to set Monday as a day off

(2) **Time Interval** – Set interval between 2 shipping Time options, you can choose from a range of 15 minutes, 30 minutes or 45 minutes.

(3) Set up other details as: _**Opening time, Lunch break starts at, Lunch break ends at, Closing Time**_

Similarly, you can set opening hours for each remaining day of the week. To quickly set up, click on the Apply to All button. Other days will have the same working time as Monday.

(4) After entering all the necessary data, remember to click on the **Save Store** or **Save and Continue Edit** button to save your work

**c) Customer Message**

![Sample](./Image_Growth_m1/image073.png?raw=true)

When customers fill in the Contact Form on the Store Detailed page, all messages are saved in this tab allowing admin/ store manager to review later.

###### Import Store

_Path: **Store Pickup > Manage Stores**

![Sample](./Image_Growth_m1/image074.png?raw=true)

Click on the Import Store button on the top right corner of the **Store Manager** page. You will be navigated to the **Import File** page.

**CSV file structure**

You can download the sample _**stores.csv**_ file to view its structure. The columns are attribute values of the store and each row corresponds to one store. The title row (first row) contains the attribute name; you can note it (important!) because the system reads data from CSV files based on the name. If the attribute value of any stores is null, you don’t have to fill data in to it.

![Sample](./Image_Growth_m1/image075.png?raw=true)

**Import File**

- Create a CSV file with information of your store following the sample file structure

- Click on button **Choose File** to select your CSV file

- Select **Save Store** to import the CSV file

###### Edit Store

_Path: **Store Pickup > Manage Stores**_

![Sample](./Image_Growth_m1/image076.png?raw=true)

On the **Store Manager** grid, you click on any store to edit. Besides 3 tabs when you create a new store, you can see more **Related Orders** tab.

![Sample](./Image_Growth_m1/image077.png?raw=true)

This tab shows you all pickup orders of this store.

_Notes_:

When a store is imported or created manually, the system will automatically get the coordinates based on the store address by using Google API. However, in some cases, this way may be not completely accurate. Therefore, the Google Map tab allows you to edit store coordinates manually.

You can see it at the left upper. Click on this tab, the Google map will be displayed. You can reset store position by clicking on any point on the map, and then select **Save Store**.

When you edit the store address (street, city or state/province) in **General Information**, the store coordinates will be auto-updated after being saved. You can also edit the color of store’s pin shown on map and preview it.

#### Manage Holidays 

_Path: **Store Pickup > Manage Holidays**_

![Sample](./Image_Growth_m1/image078.png?raw=true)

In **Holiday Manager** page, click on **Add Holiday** button to set days off for your store.

![Sample](./Image_Growth_m1/image079.png?raw=true)

(1) **Holiday Name**: Enter the holiday name

(2) **Store**: Select store(s) to apply holiday from the list

(3) **Starting Date**: Select the start date of holiday

(4) **End Date**: Select the end date of holiday

(5) **Comment**: Write comment on special holiday(s)

(6) Click on **Save Items** or **Save and Continue Edit** to save your work

#### Manage Special Days 

_Path: **Store Pickup > Manage Special Days**_

![Sample](./Image_Growth_m1/image080.png?raw=true)

To set days with special working time for your stores, in **Special Day Manager**, click on the **Add Special Day** button to create a new one.

![Sample](./Image_Growth_m1/image081.png?raw=true)

On the **Add Special Day** page:

(1) **Special Day Name**: Enter special day name
(2) **Store**: Select store(s) to apply special working days from the list
(3) & (4) **Starting Date & End Date**: Select the start date and end date of special days
(5) **Time Interval**: Set interval between shipping time options shown to customers at checkout, such as 15 minutes
(6) & (7) **Opening Time & Closing Time**: Choose opening and closing time applied to these special days
(8) **Comment**: Write comments on the special days
(9) Click on **Save Special Day** or **Save and Continue Edit** to save your work

_Notes_: Special days have the highest priority compared with holidays and other days. If a specific date is assigned as both store’s special day and holiday, it will be counted as special working day. The store still opens for pickup on that date but with special opening hours as you configured.

#### Manage Tags 

_Path: **Store Pickup > Manage Tags**_

The **Tag Manager** page shows the list of tags that you added. This tags list will be shown on the Store listing page to your customers can filter stores by them.

![Sample](./Image_Growth_m1/image082.png?raw=true)

To add a new tag, click on **Add Tag** button. 

![Sample](./Image_Growth_m1/image083.png?raw=true)

The **Add Tag** page will be shown as above, and you need to fill tag’s name, upload icon and select status for that tag. After that, remember to save your work by clicking on **Save Tag** button or **Save And Continue Edit** button.

#### View Pickup Orders 

_Path: **Sales > Orders**_

On the **Order page** view, choose the order in which the shipping name is the same as the pickup store’s name.

![Sample](./Image_Growth_m1/image084.png?raw=true)

In the Information tab, you can see the information about shipping address changed to the address of pickup store and attached with a map location

![Sample](./Image_Growth_m1/image085.png?raw=true)

**Store Pickup** tab: shows you more detailed information of store location.

#### Setiings 

_Path: **Store Pickup > Setting**_

The configuration of Store Pickup includes 4 tabs: **General, Store List, Checkout** and **Email Template**

**General**

![Sample](./Image_Growth_m1/image086.png?raw=true)

(1) **Enable Store Pickup**: choose **Yes** to enable this module on your site

(2) **Store List link shown in frontend**: Choose among Top Link/Footer Link/ Not Shown	 to show stores link on the top link/ footer link in frontend or not

(3) **Google Map key**: Fill the Google map key into this field to use Google API. You can get this key by following the guide link or going to Store Pickup > Guide

**Store List** 

![Sample](./Image_Growth_m1/image087.png?raw=true)

(1) **Description**: enter description that will be shown on the Store Listing page

(2) **Search Tab**: select types of search tabs that will be shown on the search form

![Sample](./Image_Growth_m1/image088.png?raw=true)

(3) **Store Search**: select the information customers can select when they search by area

(4) **Maximum Radius**: enter the maximum radius that you allow your customer to search

(5) **Unit of distance**: select unit to measure distance between store and customer as Kilometers or Miles

**Check out** 

![Sample](./Image_Growth_m1/image089.png?raw=true)

(1) **Carrier Title**: The title shown in Shipping Method stage at checkout. 

(2) **Method Title**: Method title is shown in Shipping Method stage at checkout 

(3) **Sort Order**: Enter a number that decide which order that checkout method will be displayed in checkout page. The smaller the number, the higher its order in the checkout page will be. 

(4) **Default store at checkout**: Choose this store as the default store in Shipping Method at checkout when customers select the Store Pickup option 

(5) **Display pickup time/date**: Allow customers to select pickup date and time at checkout or not.

(6) **Time format**: Set format of shipping time and store’s working time.

(7) **Applicable payment method(s)**: You can select payment methods applied to Store Pick up here. If you choose Only Selected Payment Methods, it will apply only specific payment methods for pickup orders. 

**Email Template** 

![Sample](./Image_Growth_m1/image090.png?raw=true)

You can modify default email template sent to store manager and admin when pickup order is created, changed status or customers send message through the **Contact Form**. 

After configuring all fields, click on the **Save Config** button to save your work

## HOW TO MANAGE USER PERMISSION 

![Sample](./Image_Growth_m1/image091.png?raw=true)

### How to Manage User Roles and Users

#### Decentrialize Roles 

_Path: **System > Permissions > Roles**_

##### Manage Roles 

![Sample](./Image_Growth_m1/image092.png?raw=true)

(1) You can click on

- **Add New Role**: add new role for your business
- **Reset Roles**: after you add a new role, or reload page to update roles

(2) **Role Management** Field

Management Table:

+ **Role Name**: type the role name that you want to search

+ **ID**: you can search the roles by ID

- **Search**: after you type Role Name or ID, you can click on **Search**, or tap **Enter** on your keyboard

- **Reset Filter**: if you want to come back to the whole role management, click on **Reset Filter**. 

Besides, to edit Roles, you just need to click on the Role Name that you want to edit. Example below:

![Sample](./Image_Growth_m1/image093.png?raw=true)

You can edit **Role Name, Role Resources** and check which Users are using this Role on **Role Users**

![Sample](./Image_Growth_m1/image094.png?raw=true)

Remember to **Save Role** to finish

##### Create a New Role 

_Path: **System > Permissions > Roles > Add New Role**_

**Role Info**

![Sample](./Image_Growth_m1/image095.png?raw=true)

(1) **Role Name**: enter Role Name
(2) **Current Admin Password**: Enter the Role Creator’s Password (for example, IT Admin creates the Role, so enter IT Admin Password)

**Role Resources**

![Sample](./Image_Growth_m1/image096.png?raw=true)

(1) **Resource Access**: you have two options:

- **All**: allow the Role to access all resources of the business

- **Custom**: choose which resource that the Role can access
(2)**Resources**: if you choose Custom on (1), then the **Resources** tab will appear. You need to tick on which resources you allow the Role to access.
Remember to click on **Save Role** to finish

#### Decentrialize Users 

_Path: **System > Permissions > Users**_

##### Manage Users

![Sample](./Image_Growth_m1/image097.png?raw=true)

(1) **User Management** Field:

You can search Users by **ID, User Name, First Name, Last Name, Email** and **Roles**

After you enter the search word, remember to tap **Enter** to find or click on **Search**. After that, to come back the whole user management field, you have to click on **Reset Filter**. 

(2) **Add New User**: to add new user

Besides, you can edit User Info by choosing the User you want to edit.

![Sample](./Image_Growth_m1/image098.png?raw=true)

Then, you can allow warehouse permission for that Users (only for existed Users) by ticking on which warehouses they can access, then click on **Save Warehouse Permissions**.

In addition, you can also assign warehouses, by clicking on **Assign Warehouses**.  A pop-up will appear as below: 

![Sample](./Image_Growth_m1/image099.png?raw=true)

(1) Tick on the **warehouse(s)** you want to assign 

(2) **Add Warehouse Permission**: to save the ticked warehouse

Remember to click on **Save User** to finish

##### Create a New User 

_Path: **System > Permissions > Users > Add New User**_

**User Info**

![Sample](./Image_Growth_m1/image100.png?raw=true)

(1) Enter **User Name**, **First Name**, **Last Name** and **User email**

(2) **Current Admin Password**:  Enter the Role Creator’s Password (for example, IT Admin creates the Role, so enter IT Admin Password)

(3) **Password** and **Password Confirmation**:  enter the User Password. 

_Note_:  enter at least 7 characters. The password must include numbers and alphabets

(4) **The password is**: active or inactive

**User Role**

![Sample](./Image_Growth_m1/image101.png?raw=true)

All existed roles will be displayed. You can leave it blank or tick on roles that you want to assign to the New User.

You can type the **Role Name** and click on **Search**/ tap **Enter** to find Role. Then click on **Reset Filter**, to come back the whole Role Management Display. 

**REST ROle**

![Sample](./Image_Growth_m1/image102.png?raw=true)

REST Role is used for API Web POS on mobile app only. 

You can assign REST-Role by ticking on the list. 

Only Admin can manage and add new REST role by going to **System > Web Services > REST**

- **Roles**. There are two default REST role (unable to delete): **Guest** and **Customer**

Remember to click on **Save User** to finish

### How to Manage Staff for POS

#### Decentrialize POS Access Permission 

##### Manage Access Permission 

_Path: **Sales > Web POS > Web POS Permissions > POS Roles**_

![Sample](./Image_Growth_m1/image103.png?raw=true)

POS Role management will be shown in grid, including columns **named ID, Display Name, Description, Active** and **Action**. You can search for Roles here.

##### Create a New Role 

_Path: On **POS Roles** page, click on **Add Role**_

**Role Information**

![Sample](./Image_Growth_m1/image104.png?raw=true)

(1) **Role Name**: Enter the name

(2) **Permission**:  Choose Permissions that the Role can access

(3) **Maximum Discount Percent (%)**: Choose the highest discount this Role can apply for each customer.

(4) **Description**:  write the description of the Role (if have)

(5) **Status**:  determine if the Role is **Active** or **Inactive** 

**User List**

![Sample](./Image_Growth_m1/image105.png?raw=true)

Select which Users will take charge of this Role

After all, remember to click **Save Role** or **Save And Continue Edit** 

#### Decentrialize POS Staff 

##### Manage Staff 

_**Path: Sales > Web POS > Web POS Permissions > POS Users**_

![Sample](./Image_Growth_m1/image106.png?raw=true)

POS User Management will be shown in grid, including columns named ID, User Name. Email, Display, Location (the store users are taking charge), Role, Status, and Action. You can search for Users here.

##### Create a New Staff

_ Path: **Sales** > **Web POS** section > **Manage permissions** > **POS Users** > Click on **Add User**

![Sample](./Image_Growth_m1/image107.png?raw=true)

Then, you will enter information as following: 

**User Information**

![Sample](./Image_Growth_m1/image108.png?raw=true)

(1) **User Name**:  enter the Name

(2) **Password** and **Password Confirmation**:  enter the User Password (at least 7 characters, including numbers and alphabetic characters)

(3) **Display name**:  enter the name Display on Frontend

(4) **Email Address**:   enter the email address of the User

(5) **PIN Code (App only)**:  enter 4 numbers for PIN Code

 **User Settings**
 
![Sample](./Image_Growth_m1/image109.png?raw=true)

(1) **Customer Group**:  choose which groups the User will take charge of

(2) **Location**:  choose where the User will work (warehouse or which stores)

(3) **Role**:  choose the Role applied for User

(4) **Status**:  choose Enabled to activate the User

Click **Save User** or **Save And Continue to Edit** to finish this phase

### Basic Role for Each Admin in the System (Reference Only)

_Note_: For reference only! With each business feature has different roles for users.

#### Store Manager 

![Sample](./Image_Growth_m1/image110.png?raw=true)

Moreover, Store Manager can access to Sales Tab and decentralize roles for Sale Staff

#### Inventory Manager 

![Sample](./Image_Growth_m1/image111.png?raw=true)

Moreover, Inventory Manager can access to Sales Tab and decentralize Inventory Staff

#### Purchase Management 

![Sample](./Image_Growth_m1/image112.png?raw=true)

Moreover, Purchase Manager can access to Sales Tab and decentralize Purchase Staff

#### Ecommerce Manager

![Sample](./Image_Growth_m1/image113.png?raw=true)

#### Accountant 

![Sample](./Image_Growth_m1/image114.png?raw=true)

## HOW TO MANAGE MASTER DATA 

### Product 

#### Attributes 

_Path: **Catalog > Attributes > Manage Attributes**_

![Sample](./Image_Growth_m1/image115.png?raw=true)

(1) The Management Tab will be shown in grid, including columns named **Attribute Code, Attribute Label, Required, System, Visible, Scope, Searchable, Used in Layered Navigation**, and **Comparable**. 

(2) **Add New Attribute**:  If you do not know how to fill in required fields, click on 

#### Attribute Sets 

_Path: **Catalog > Attributes > Manage Attribute Sets**_

![Sample](./Image_Growth_m1/image117.png?raw=true)

(1) The Attribute Sets will be shown in table

(2) **Add New Set**:  If you do not know how to fill in required fields, click on 

#### Categories 

_Path: **Catalog > Manage Categories**_

![Sample](./Image_Growth_m1/image118.png?raw=true)

When selecting a category on the left, all the information will be displayed on the right.

You can easily edit any Category Information. Remember to click on **Save Category** to complete it. 

Or else, you can delete Category from your store by click on **Delete Category** button.

![Sample](./Image_Growth_m1/image119.png?raw=true)

(1) **Add Root Category** and **Add Subcategory**:  click on the button

(2) **Get help for this page**:  if you are not clear how to fill in required fields, click to read guidelines

(3) **Reset** and **Save Category**:  to save the new category, click on **Save Category**. To delete what you have created, click on **Reset**

#### Products

##### Types 

**Simple Product**

A simple product is a physical item with a single SKU. Simple products have a variety of pricing and of input controls which makes it possible to sell variations of the product. Simple products can be used in association with grouped, bundle, and configurable products.

**Grouped Product**

A grouped product presents multiple, standalone products as a group. You can offer variations of a single product, or group them for a promotion. The products can be purchased separately, or as a group.

**Configurable Product**

A configurable product appears to be a single product with lists of options for each variation. However, each option represents a separate, simple product with a distinct SKU, which makes it possible to track inventory for each variation.

**Virtual Product** 

Virtual products are not tangible products, and are typically used for products such as services, memberships, warranties, and subscriptions. Virtual products can be used in association with grouped and bundle products.

**Bundle Product**

A bundle product let customers “build their own” from an as sort of options. The bundle could be a gift basket, computer, or any things else that can be customized. Each item in the bundle is a separate, standalone product.

**Downloadable Product**

A digitally downloadable product that consists of one or more files that are downloaded. The files can reside on your server or be provided as URLs to any other server

**Custom Sale** 

A custom sale product is a special product that can be ordered personally or customized along Customer Demand. This product will only be shown in POS.

**Store Credit**

A store credit helps customer save and earn credit after purchasing a product, or or refund products “without using money”. Besides, Store Credit can be used in purchasing. 

**Gift Card**

A gift card is a prepaid stored-value money product. Customer can use gift card as an alternative to cash for purchases within a particular store or related business.

##### Manage Product

_Path: **Catalog > Manage Products**

![Sample](./Image_Growth_m1/image120.png?raw=true)

(1) All Products will be shown in grid, including columns named **ID, Name, Type, Attribute Set Name, SKU, Price, Qty, Visibility, Status, Website**, and **Action**.

(2) **Add Product**: click on Add Product to add a new Product. 

Then you will be linked to the page as below:

![Sample](./Image_Growth_m1/image121.png?raw=true)

Choose **Attribute Set** and **Product Type** that you want to create. 

Click on **Continue** to work the next step.

##### Add New Product (Step by Step) 

**a) Simple Product** 
_**Step 1: General Information**_

![Sample](./Image_Growth_m1/image122.png?raw=true)

Here, you need to enter required fields, such as **Name, Description, Short Description, SKU, Status**, and **Visibility**

Besides, you can set up fields such as **Set Product as New from Date … to Date, URL Key, Country of Manufacture, Select the Gift Code Sets**, and **Enable on Web POS**

_**Step 2: Product Prices**_ 

![Sample](./Image_Growth_m1/image123.png?raw=true)

Now, you click on **Prices** tab on your left hand. Then, you enter required fields – **prices** and **tax class**. You can also set up the **Special Price**, the **date** of Special Price, **Cost, Tier Price, Apply Map, Display Actual Price, Manufacturer’s Suggested Retail Price** and **Credit Value**.

_**Step 3: Meta Information, Images, Recurring Profile and Design**_ 

**Meta Information**

![Sample](./Image_Growth_m1/image124.png?raw=true)

This help you improve your SEO. Enter **Meta Title, Meta Keywords** and **Meta Description** (maximum characters = 255)

**Images** 

![Sample](./Image_Growth_m1/image125.png?raw=true)

Click on **Browse files** to select file, then click on **Upload files** to use that file

If you want to remove the image, then tick on **Remove** Column, then click **Save**

**Recurring Profile** 

![Sample](./Image_Growth_m1/image126.png?raw=true)

When you click here, the default will be **No**

Product with recurring profile participates in catalog as nominal items 

**Design**

![Sample](./Image_Growth_m1/image127.png?raw=true)

Here, you can set up **Custom Design**, **the date of Active, Custom Layout Updates, Page Layout** and **Display Product Options in**

_**Step 4: Gift Options**_ 

![Sample](./Image_Growth_m1/image128.png?raw=true)

In this section, you will select whether do you want to **Allow Gift Message** and **Gift Wrapping** for the product. If **Yes**, then enter the price for **Gift Wrapping**

_**Step 5:  Inventory and Barcode**_ 

**Inventory

![Sample](./Image_Growth_m1/image129.png?raw=true)

(1) **Inventory**: 
Set up **Manage Stock**, **Qty (required), Qty for Item’s Status to Become out of Stock, Minimum and Maximum Qty Allowed in Shopping Cart, Qty Uses Decimals, ackorders, Notify for Quantity Below, Enable Qty Increments** and **Stock Availability**

(2) **Warehouse Stocks**:
Click on **Register to Warehouse** button. 

![Sample](./Image_Growth_m1/image130.png?raw=true)

Then, you will select the **warehouse**, enter the **Qty** in **Warehouse** and **Shelf Location**. 
After that, click on **Register to Warehouse** button to add it. 

(3) **Supplier**
Click on **Register to Suppliers**

![Sample](./Image_Growth_m1/image131.png?raw=true)

Then, select the Supplier, enter Supplier Product SKU, Cost and Tax(%)
After that, click on **Register to Suppliers** button to finish

**Barcode**

![Sample](./Image_Growth_m1/image132.png?raw=true)

Select **Barcode Template**
Then select the **Barcode** for the new product
To create a barcode, read Section 2.5. Barcode Management


_**Step 6: Websites and Categories**_

**Website**

![Sample](./Image_Growth_m1/image133.png?raw=true)

Select **Website(s)** that you will sell this new product 

**Categories** 

![Sample](./Image_Growth_m1/image134.png?raw=true)

Select **Product Categories** of the new product. 

_**Step 7: Related Products, Up-sells, and Cross-sells**_

With **Related Products, Up-sells and Cross-sells**, you just need to tick on the products. Then click on Save to activate it. 

![Sample](./Image_Growth_m1/image135.png?raw=true)

_**Step 8: Custom Option

![Sample](./Image_Growth_m1/image136.png?raw=true)

Click on **Add New Option**. Then, enter **Title**, select **Input Type**, **Required** Allowance and enter **Sort Order**

**b) Grouped Product** 

_The price of grouped products will be calculated according to the price of each products in the group._

**Step 1: General Infomation** same here

**Step 2: Associated Products**
This section lies in the bottom of the **Product Information** panel.

![Sample](./Image_Growth_m1/image137.png?raw=true)

Select the **checkbox** of each product that you want to include.

**Step 3: _Meta Information, Images, Recurring Profile and Design same here_**

**Step 4: Gift Option**

**Step 5: _Inventory and Barcode_**

**Inventory**

![Sample](./Image_Growth_m1/image138.png?raw=true)

(1) **_Inventory_**: you just need to activate/inactivate the button Manage Stock, Enable Qty Encrements and Stock Availability

(2) **_Warehouse Stocks_**: 
If you click on **Register to Warehouse** button, then: 

![Sample](./Image_Growth_m1/image139.png?raw=true)

Select the warehouse. Click on **Register to Warehouse** to save

**(3) Supplier** 

If you click on **Register to Suppliers** button, then: 

![Sample](./Image_Growth_m1/image140.png?raw=true)

Select the supplier. Click on **Register to Suppliers** to save

**Step 6:  Websites and Categories**

**Step 7: Related Products, Up-sells, and Cross-sells**

**c) Configurable Product**

![Sample](./Image_Growth_m1/image141.png?raw=true)

Tick on **Select the Gift Code Sets** 

Then, click on **Continue**

Most of the steps here will be similar to Grouped Products, except:

- You have to set up the **price** for **Configurable Product** (similar to what you do with **Simple Product**)

- You also need to set up price for **Gift Wrapping**. 

- Besides, you HAVE the options to set up **Custom Options**.

**d) Virtual Product**

Same as **Simple Product**

**e) Bundle Product** 

**Step 1: General Information**

In addition to basic fields as Simple Product, you need to fill in others.

![Sample](./Image_Growth_m1/image142.png?raw=true)

Set both the **SKU** and **Weight** as **Dynamic** OR **Fixed**

If using a **fixed SKU** or **Weight**, enter the actual value in the field to the right.

**Step 2: Product Prices**

![Sample](./Image_Growth_m1/image143.png?raw=true)

Beside similar fields as **Simple Product**, you need to notice about:

(1) **Price** tab:

You can set the Price as Dynamic or Fixed. 

If using a **fixed Price**, enter the actual value in the field to the right. 

(2) **Price View**
Select to set the Price view **As Low As** the actual price or on the **Price Range**

**Step 3: Meta Information, Images, Recurring Profile and Design**

**Step 4: Gift Option**

**Step 5: Inventory and Barcode**

**Step 6: Websites and Categories**

**Step 7: Related Products, Up-sells, and Cross-sells**

**Step 8**: Custom Option same here. Notice that: Bundle with dynamic pricing cannot include custom defined option. Options will not be saved.

**Step 9**: : Bundle Items

![Sample](./Image_Growth_m1/image144.png?raw=true)

**(1) Shipment**:
**Ship Bundle Items**: select **Together** or **Separately**

**(2)Bundle Items**: 

![Sample](./Image_Growth_m1/image145.png?raw=true)

Click on **Add New Option** button to add bundle items. 

Enter the **Default Title** of bundle items

Select **Input Type, Required** Allowance, and insert **Position** of bundle items

Click on **Add Selection**, then:

![Sample](./Image_Growth_m1/image146.png?raw=true)

Tick on the products that you want to select to add. 

Then, to save it, click on **Add Selected Product(s) to Option** button. 

**f) Downloadable Product**

Most of steps are similar to **Simple Product**, except:

_**Step 9: Downloadable Product**_ 

**Links**: 

![Sample](./Image_Growth_m1/image147.png?raw=true)

(1) **Title**: enter the title for the list of downloadable products

(2) **Links can be purchase separately**: choose **Yes** if you want to offer a multiple download link. 
 
(3) Click on **Add New Row**, then:

![Sample](./Image_Growth_m1/image148.png?raw=true)

- **Title** and **Price**: insert the **Title** and **Price** of the downloadable product

- **Max number of downloads**: enter the highest number of downloads ONE customer can make. To allow unlimited downloads, select the Unlimited checkbox.

- **Shareable**: select **No**, then your customer will NEED to log in their account to access the download link.

- **Sample**: select the sample file to upload to server OR paste the full URL on the URL field. 

- **File**: as above

- **Sort Order**: enter a number to indicate the sequence that this download will be listed with other downloads on the product page

Click on **Add New Row** button, to add another downloadable product.

**Upload Files** button: when you have completed upload files to server, click on Upload Files button to finish.

Click on **Save and Continue to Edit** button to move on. 

**Samples**: 

![Sample](./Image_Growth_m1/image150.png?raw=true)

Click to expand the **Samples** section

Then, enter the **Title** of the list of samples

Click on **Add New Row** to add samples to the list

![Sample](./Image_Growth_m1/image151.png?raw=true)

Insert the **Title** of the Sample, then choose to upload the sample by **File** or paste **URL**. Enter the Sort Order 

After that, if you upload sample **File**, then click on **Upload Files** button to finish. If you choose to paste **URL**, then move straight to the final step - click **Save** to finish all

**g) Store Credit**

**Step 1: General Information**

**Step 2: Product Prices**

![Sample](./Image_Growth_m1/image152.png?raw=true)

- **Tax Class**: select the tax class for the store credit product

- **Type of Store Credit value**: select the type of product value (**Range** or **Dropdown**)

- **Store Credit value**: enter the value of store credit

- **Credit Rate**: enter the credit rate

**Step 3: Meta Information, Images, Recurring Profile and Design 

**Step 4: Gift Options** 

**Step 5: Inventory and Barcode 

**Step 6: Websites and Categories 

**Step 7: Related Products, Up-sells, and Cross-sells 

**Step 8: Custom Option

**h) Gift Card**

**Step 1: General Information

Complate similar fields as **Simple Product**, then:

![Sample](./Image_Growth_m1/image153.png?raw=true)

(1) **SKU** and **Weight**: 

(2) **Select Gift Card Templates**: select the template for your gift card (you can choose more than one)

**Step 2: Product Prices** 

![Sample](./Image_Growth_m1/image154.png?raw=true)

(1) **Tax Class** and **Type of Gift Card value**: similar to **Store Credit**

(2) **Gift Card value**: insert the value of the gift card. Besides, you can select **Type of Gift Card price**. 
You cannot enter **credit value** here. 

**Step 3: Meta Information, Images, Recurring Profile and Design**

**Step 4: Gift Options

**Step 5: Inventory and Barcode 

![Sample](./Image_Growth_m1/image155.png?raw=true)

Set up wheter you want to **Manage Stock** and **Enable Qty Increments**

Enter the **Minimum** and **Maximum Qty Allowed in Shopping Cart**

**Step 6: Websites and Categories

**Step 7: Related Products, Up-sells, and Cross-sells

**Step 8: Custom Option

**Step 9: Shopping Cart Conditions

![Sample](./Image_Growth_m1/image156.png?raw=true)

(1) **Description**: describe conditions applied to shopping card when using this gift code

(2) **Set conditions**: set up the conditions for the sopping cart to use gift card

**Step 10: Cart Item Conditions

![Sample](./Image_Growth_m1/image157.png?raw=true)

Set up the condition for the product in cart when using Gift Card

**i) Custom Sale**

Similar as **Simple Product**, except that you cannot set up the price for custom sale

_Note_: 

- While you are adding products, you can also create a new attribute by clicking on **Create New Attribute** button 

![Sample](./Image_Growth_m1/image158.png?raw=true)

- When you set **Attribute Set** along with your own set (eg: **Clothing**), then it will appear on the left panel

![Sample](./Image_Growth_m1/image159.png?raw=true)

On your right hand, you can set up the product features

### Customers 

#### Manage Customers 

_Path: **Customers** > **Manage Customers**_

![Sample](./Image_Growth_m1/image160.png?raw=true)

(1) The Manage Customers Table will be shown in grid, including columns named **ID, Name, Email, Group, Telephone, Zip, Country, State/Province, Customer Since, Website** and **Action**

You can edit Action by ticking on Customer(s) and choose **Action** on Actions Field, then clicking **Submit** as below:

![Sample](./Image_Growth_m1/image161.png?raw=true)

(2) **Add New Customer**: if you have not known how to add New customer, you can read the Magento Guide by clicking on **Get help for this page**

![Sample](./Image_Growth_m1/image162.png?raw=true)

Besides, you can edit Customers’ Information by clicking on the Customer you want to edit.

#### Customer Groups 

![Sample](./Image_Growth_m1/image163.png?raw=true)

(1) The Customer Groups will be shown in grid, including columns named ID, Group Name and Tax Class.

(2) Add New Customer Group:

![Sample](./Image_Growth_m1/image164.png?raw=true)

**Group Name**: enter the name (less than 32 symbols)
**Tax Class**:  choose the tax class

![Sample](./Image_Growth_m1/image165.png?raw=true)

Then, click on Save Customer Group to finish

### Partner/Vendor

#### Managae Supppliers

_Path: **Supplier** > **Manage Suppliers**_

![Sample](./Image_Growth_m1/image166.png?raw=true)

(1) The Supplier Management will be shown in grid, including columns **named ID, Supplier, Supplier Code, Contact Email, Status** and **Action**

(2) Add New Supplier

#### Add New Supplier

##### Supplier Information

![Sample](./Image_Growth_m1/image167.png?raw=true)

(1) **Supplier Name**:  enter the name
(2) **Supplier Code**:  enter the code. It can be Commercial and Government Entity (CAGE) code of supplier, or supplier number, or supplier code, etc.
(3) **Contact Person**:  enter the name of the contact person
(4) **Email**:  enter the supplier email to contact
(5) **Status**:  enabled or disabled this supplier
(6) **Description**:  enter the description about supplier (if have)

##### Mailing Address 

![Sample](./Image_Growth_m1/image168.png?raw=true)

Fill in **Telephone, Fax, Street Address, City, Country, State/Provice** and **Zip/Postal Code**

##### Product List 

![Sample](./Image_Growth_m1/image169.png?raw=true)

Tick on which product(s) the supplier provide

##### Price List 

![Sample](./Image_Growth_m1/image170.png?raw=true)

Tick on which pricelist(s) the supplier provide
After all, click **Save** to complete the phase

##### Manage Price List 

![Sample](./Image_Growth_m1/image171.png?raw=true)

(1) The Pricelist Management will be shown in grid, including columns named **ID, Product SKU, Product Name, Supplier, Maximum Qty, Purcahse Price (USD), Start Date, End Date** and **Action**

(2) You can click on

**Mass Remove**:  to remove all pricelist
**Mass Update**:  to update what you have editted
**Import Pricelist**:  to import the pricelist. If you click on this, a pop-up will be shown as below:

![Sample](./Image_Growth_m1/image172.png?raw=true)

Choose file and upload a **CSV File** to import
If you do not have it, click on **Download sample file** to get the sample of CSV
After you finish uploading, click on **Import** to complete this phase

### Warehouse 

_Path: **Inventory Management > Stock Listing > Warehouses**_

![Sample](./Image_Growth_m1/image173.png?raw=true)

Inventory Information will be shown in grid, inlcuding columns as **ID, Warehouses, Total SKU, Total Qty, Contact Email, Telephone, Street, City, Country** and **Action**

#### New Warehouse

Click on **Add a New Warehouse** button

![Sample](./Image_Growth_m1/image174.png?raw=true)

Fill basic information about the new Warehouse.

_Notes_: You are required to fill **Warehouse Name** and **Warehouse Code**

#### Warehouse Management 

![Sample](./Image_Growth_m1/image175.png?raw=true)

The grid shows Warehouse basic information such as **ID, Warehouse Name, Total SKUs, Total Qty, Contact Email, Telephone, Street, City, Country, and Action**

Click on **View**

![Sample](./Image_Growth_m1/image176.png?raw=true)

Here, you can edit Warehouse information, including **General Information, Stock On Hand, Stock Movement, Warehouse Permission, and Dashboard**:

**General Information**: name,code, email and location

**Stock On Hand**: illustrate the Qty of products that are availble in the warehouse at the moment. 

**Stock Movement**: show the opening and closing data between dates, such as: purchases made, sales order totals, external transfer and 
internal transfer (send stock) and returned items. 

**Warehouse Permission**: manage and decentralize warehouse permission

**Dashboard**: show Inventory Report in lines and tables. 

Then, remember to click **Save General Information** to save what you have edited.

Or you can click on **Delete Warehouse** to delete the warehouse.

Or click on **Back**, to get back the Management Page.

#### Warehouse Permission

After having created a warehouse, Admin Users can give different warehouse access permissions to different (admin) users.

Click on **View** to see the warehouse’s detail information 

![Sample](./Image_Growth_m1/image177.png?raw=true)

If you want to edit **Warehouse Roles**,

(1) Tick on the staff you want to edit roles

(2) Click on tab to select role. For example:

![Sample](./Image_Growth_m1/image178.png?raw=true)

(3) Click on **Delete** if you want to delete the staff completely.
If you want to add new staff(s), 

(4) Click on **Assign Staffs**. 

Then a pop-up will be shown as below:

![Sample](./Image_Growth_m1/image179.png?raw=true)

(1) Tick on the staff you want to add

(2) Click on tab to select **Admin Role** or **Staff Role** or both

(3) Click on **Add Selected Staff** to finish this phase. 

### Location

_Path: **Sales > Web POS > Manage Locations**_

#### Add New Location

![Sample](./Image_Growth_m1/image180.png?raw=true)

Click on **Add New Location** to add a new one. Then you will have to fill in two sections:

**Location Information**

![Sample](./Image_Growth_m1/image181.png?raw=true)

(1) **Display Name and Address**:  these are required fields

(2) **Decription**:  fill in description about the warehouse

(3) **Warehouse**:  select one of these options:

![Sample](./Image_Growth_m1/image182.png?raw=true)

**Don’t link to any warehouse**:  if the warehouse works separatedly

**Create a new Warehouse**:  if you are creating the location for the new warehouse

**List of warehouses**:  Select one warehouse that you want to add new location

**User list**

![Sample](./Image_Growth_m1/image183.png?raw=true)

(1) Tick on which user you want to edit

(2) Click on the tab in the **Status** Column to edit **Status** of the User.

After all, remember to click **Save Location** to complete the new Location

#### Mapping Locations - Warehouses

_Path: **Sales > Web POS > Manage Locations > Mapping Locations – Warehouses**_

_or_

_Path: **Inventory Management > Stock Listing > Warehouses > Mapping Locations-Warehouses**_

![Sample](./Image_Growth_m1/image184.png?raw=true)

(1) Tick on the **Location** you want to edit. 
Here, you can also edit the Status of the Location. 
**Yes**:  Available
**No**:  Inavailable

(2) **Warehouses**:  select the warehouse you want to link to the location
Besides, you can search for location by filling in the tab on **Locations** Column.

### POS

#### Create New POS 

_Path: **Sales > Web POS section > Manage POS**_

Please refer to **2.1.1.1. Create a New POS** for detailed guide.

_Notes_: Even when you set the warehouse to a certain location, with online store, admin can see clearly any warehouse information in any locations. HOWEVER, with offline store, only Sale Manager can view the warehouse information only in the mapped location.

IT Admin can give other admin permission to view the Inventory information in any location by going to **System > User Roles > Add new role or Edit role > Role Resource, then choosing Order Success > Inventory Management > View Warehouse Information** (this is the most basic step. With each business, the process will be expanded)

#### Manage WEB POS 

_Path: **Sale > Web POS section > Manage POS**

![Sample](./Image_Growth_m1/image185.png?raw=true)

Here, you can view **ID, Name, Location, Store View, Current Staff**, and **Status**.  If you want to view more details and edit any details, you can click on **Detail** in the **Action** column. Besides, you can tick on each **Location Name**, then choose **Action** as **Delete** to remove the location.  

## HOW TO USE 

### Web POS 

#### Log in and Manage Account 

##### Log in 

_Path: **Sales > Web POS section > POS Checkout**_

Or users can directly log in by going to Web POS Front-end and fill in required **Username** and **Password**. Besides, users also need to choose **Main Website** as well as **POS Location** to log in successfully. 

![Sample](./Image_Growth_m1/image186.png?raw=true)

##### Manage Account 

_Path: **Web POS Front-end > Settings section > Account**_

![Sample](./Image_Growth_m1/image187.png?raw=true)

And then, users can edit or adjust account information if they want. In details, they can edit **Display Name** and **Current Password**

![Sample](./Image_Growth_m1/image188.png?raw=true)

##### Manage Settings

_Path: **Web POS Front-end > Settings section > General**_

![Sample](./Image_Growth_m1/image189.png?raw=true)

There are 5 tabs to manage: **Checkout, Catalog, Currency, Customer Credit and Reward Points.**

**Checkout**

![Sample](./Image_Growth_m1/image190.png?raw=true)

You can adjust 2 things: **Use online Mode** and **Auto check the promotion rules on checkout (Offline mode)**

![Sample](./Image_Growth_m1/image191.png?raw=true)

Choose between **Yes** or **No** to active the function of using online mode 

Besides, users can also activate the function of checking promotion rules for offline mode automatically by selecting **Yes**

**Catalog**

Users can adjust the function of displaying out-of-stock products in search results 

![Sample](./Image_Growth_m1/image192.png?raw=true)

**Currency** 

The default currency of system is Dollar 

![Sample](./Image_Growth_m1/image193.png?raw=true)

**Customer Credit** 

Here, users are allowed to change 2 things displayed on screen like the screenshot below

![Sample](./Image_Growth_m1/image194.png?raw=true)

**Reward Point** 

On POS, users can sync or show customer points balance on receipt by doing this action below

![Sample](./Image_Growth_m1/image195.png?raw=true)

#### Manage Session

If you enable Need to create session before working setting in backend (Path: **Sales > Web POS section > Settings**), when the first shift of the day started, POS Manager will open session to create the **Opening Balance** - the amount of cash in your store at that time. (You will need to Close session and enter Closing Balance at the end of the shift). Those amounts will be saved in the system, so POS could provide you information about daily revenue after a working day. 

![Sample](./Image_Growth_m1/image196.png?raw=true)

###### Open Session 

When you log in to POS, the screen will automatically pop-up a window like the screenshot below 

![Sample](./Image_Growth_m1/image197.png?raw=true)

(1) The name of Staff opening this session

(2) The name of POS 

(3) The Opening Balance Details 

(4) The total value of Opening Balance 

###### Manage Session 

_Path: **Web POS front-end > Settings section > Session Management**_

![Sample](./Image_Growth_m1/image198.png?raw=true)

You will see all sessions carried out by this account here. 
Opened session will have an **OPEN** mark next to its date and time in the listing.

![Sample](./Image_Growth_m1/image199.png?raw=true)

And when users click any specific session, the details will be shown like this 

![Sample](./Image_Growth_m1/image200.png?raw=true)

Users can get important information such as:

- Staff working on the POS, POS Name, Session Date and Time

- Summary of Total Cash Payment in Session: 

+ **Opening Balance**: the amount of cash in cash drawer at the beginning of the session

+ **Theoretical Closing Balance**: = Opening Balance + Manually Input Amount of Put Money In/Take Money Out + Total sales (in cash only)

+ **Real Closing Balance**: the real amount of cash in cash drawer at the end of the session

+ The Difference between **Theoretical Closing Balance** and **Real Closing Balance.** 

- For opened session, cashier can **Put Money In/ Take Money Out, Set Closing Balance and End Session.**

- Manually input of cash in/out in the session and transactions in cash are recorded in the **+ Transactions/ - Transactions** links.

- Total Sales by all Payment Methods

###### Record Cash In/ Cash Out

During an opened session, staff is allowed to adjust the money balance by **Take Money Out** or **Put Money In** 

![Sample](./Image_Growth_m1/image201.png?raw=true)

**Put Money In** 

![Sample](./Image_Growth_m1/image202.png?raw=true)

The Staff’s Name does this action will be displayed at the bottom 
And there are 2 fields for him/her to fill in. The first one is the amount of money staff wants to put in and the other is the reason for this action. 

**Take Money Out**

![Sample](./Image_Growth_m1/image203.png?raw=true)

The same window also appears like **Put Money In** and staff also has to fill in those 2 fields in case she/he wants to take money out. 

###### Close Session 

Finally, at the end of the day, POS Managers must undertake mission to create Closing Balance, which means they have to confirm the amount of cash in store after all transactions on that day. Then, the system would be able to provide Session Report for Manager.
To close balance, tap on the yellow button **Set Closing Balance**

![Sample](./Image_Growth_m1/image204.png?raw=true)

Then, the screen will display like this

![Sample](./Image_Growth_m1/image205.png?raw=true)

It demands user to fill in the amount of money in reality to compare this result to **Theoretical Closing Balance** to make sure no loss can happen. 

Base on this algorithm, 2 case can befall: the first one is that 2 numbers of Reality Closing Balance and Theoretical are the same and the other is when they are different. 

- If the **Theoretical** and **Real Balances** are the same, you will go back to the Session window, click on **Validate Closing** to finish closing the session

![Sample](./Image_Growth_m1/image206.png?raw=true)

- If the Theory and Real Balance are not the same, the system will display a notification as below:

![Sample](./Image_Growth_m1/image207.png?raw=true)

You can click Cancel and re-entry the closing balance, OR accept the difference by clicking OK

![Sample](./Image_Growth_m1/image208.png?raw=true)

#### Filer and Search Product Quickly 

##### Configure Process of Searching Product 

##### Search Product in Front-end 

There are 3 ways to search for products in Web POS frontend: 

**Use Category**

![Sample](./Image_Growth_m1/image209.png?raw=true)

Click **All Categories** to quickly search with this method. Users can choose corresponding categories as you prefer in the space below this button

**Use Product Attributes** 

(1) Click on search icon to show search bar. 

(2) Enter your search terms and matching products will display right away

![Sample](./Image_Growth_m1/image210.png?raw=true)

**Use Barcode**

(1) Connect with the Barcode Reader devices (Please refer to Section **2.1.10. How Web POS Works with Peripheral Device**) 

(2) Scan barcode > search box will be automatically filled-in 

(3) The matching product will be shown in the list. 

#### Add Products to Cart and Edit Product in Carts 

##### How to Add Products to Cart

With **Simple Product**: click it to add to cart

With **Configurable, Bundle, Grouped Product**: click them > adjust **attribute** (color, size, etc.) and **Qty.** > Click **Add to cart** button

##### Edit Product on Cart 

After adding products to cart, you can edit the quantity of each product by clicking on the product that needs editing. A popup will display with edited option for **Qty**.

![Sample](./Image_Growth_m1/image211.png?raw=true)

To edit Qty., just enter a wanted number or click on +/-. The number of products will be adjusted in the cart right away

##### Remove Product on Cart

There are 2 ways to remove products in cart: 

(1) Remove one-by-one product: Click “x” button, then cart will be update immediately 

![Sample](./Image_Growth_m1/image212.png?raw=true)

(2) Click waste basket icon to clear the whole cart

![Sample](./Image_Growth_m1/image213.png?raw=true)

##### Add a Custom Sale Item to Cart 

Custom sale item is an item that Web POS user creates when checkout. It is used when the product hasn’t been added to the system or Web POS user cannot find it in the product list.

In frontend, click on **Custom Sale** button if you want to add the custom product to cart

![Sample](./Image_Growth_m1/image214.png?raw=true)

Then it will pop up a window for users to configure this custom product:

(1) **Name**: Enter the name of product

(2) **Description**: Enter the product’s description (optional)

(3) **Price**: Enter the product’s price or use the calculator below

(4) **Non/Taxable Goods**: choose if the product is taxable

(5) **Shippable**: Choose whether this product will be shipped 

After finishing configuration, click on **Add to Cart** button and check out as normally. 

_Notes_: this custom sale product will not be saved for the next checkout.

![Sample](./Image_Growth_m1/image215.png?raw=true)

(1) **Name**: Enter the name of product

(2) **Description**: Enter the product’s description (optional)

(3) **Price**: Enter the product’s price or use the calculator below

(4) **Non/Taxable Goods**: choose if the product is taxable

(5) **Shippable**: Choose whether this product will be shipped 

After finishing configuration, click on **Add to Cart** button and check out as normally. 

_Notes_: this custom sale product will not be saved for the next checkout.

#### Apply Coupon Code or Discount to Cart 

##### Apply Coupon Code or Card Discount 

Here is the tutorial to apply **Coupon Code/ Discount** that you created with Magento’s functions **Catalog Price Rule** and **Cart Price Rules**

To use this function, click **Add Discount**

![Sample](./Image_Growth_m1/image216.png?raw=true)

Then you can choose to apply a Discount amount or Promotion code

**Discount**

![Sample](./Image_Growth_m1/image217.png?raw=true)

- **Name**: enter the name for this account as you will easily check it again

- **Discount type**: choose between percentage or fixed discount

- **Amount**: fill in the value offered to customers. 

Cart will be adjusted immediately after you click **Apply** button

**Promotion**

![Sample](./Image_Growth_m1/image218.png?raw=true)

Fill in available code offered to customer and then click “**Apply**” button.

_(Users can also check this code rules before applying it by clicking on **Check**)_

##### Apply Custom Discount or Custom Price for a Product 

Here you can manually add a custom discount for a product (either by a fixed value or percentage) instead of the whole shopping cart.

After adding products to cart, besides editing the quantity of each product (refer to section **Edit products in cart** for more details), you can click on the product to edit other information. A popup will display with edit option for **Custom Price, Discount**. Remember that you can only change information by Custom Price **OR** Discount, instead of both at once for a product.

**Apply Custom Price** 

You can set custom price for products by clicking on **Custom Price** button. The next popup will be shown as below:

![Sample](./Image_Growth_m1/image219.png?raw=true)

In this popup, choose the promotion type you want to apply, either a fixed amount or percentage.

- If you edit fixed price, the price will be changed to the value you have entered. 

- If you edit by percentage, the price will be the result after multiplying the discount percentage rate by the original price.

Then, products in cart will be automatically updated with the price you edit.

**Apply Discount** 

Click on **Discount** button and choose the type of discount you want to apply

![Sample](./Image_Growth_m1/image220.png?raw=true)

- If you edit discount by fixed number, the price will decrease by the exact value you have entered

- If you edit by percentage, the price will decrease by the percent you have entered (it is as same as Custom Price by percentage).

Then, the product price will be updated in the cart

##### Apply Gift Card Code 

After clicking on **Checkout** button for a shopping cart, in the Shipping and Payment window, cashier can insert Gift Card Code and click **Apply**.

![Sample](./Image_Growth_m1/image221.png?raw=true)

#### Manage Transaction

##### Handle Customer Information at Checkout 

**Customer Checkout** 

Add customer by clicking on **Customer** icon on the right corner. You will see a screen as below:

![Sample](./Image_Growth_m1/image222.png?raw=true)

![Sample](./Image_Growth_m1/image223.png?raw=true)

In the pop-up, you have options to either Create a new Customer as Default Guest Checkout (configuration guide in Section 2.1.7. Configure Default Guest Checkout), Search existing Customer with the Search bar or selecting the most recent Customer from the list.

**Search Customer** 

In the search box, you can quickly find the customer by entering his name, email, phone or address. Choose customer from suggested results in dropdown list.

The information of customer in the system will be auto updated in checkout step. To edit it, please click on name of customer. In the popup, just edit the pieces of information you want to change.

![Sample](./Image_Growth_m1/image224.png?raw=true)

**Create Customer** 

![Sample](./Image_Growth_m1/image225.png?raw=true)

Fill information of the customer such as **First Name, Last Name, Email, Group, Shipping & Billing Address, etc. You can choose whether Billing Address** is similar to Shipping Address or not. Remember to click on **Save** button to save the customer information for the next checkout.

**Guest Checkout** 

When you use Guest Checkout, the default customer that you configure in backend will be used (Please refer to Section **2.1.7.Configure Default Guest Checkout** to configure Default Guest Checkout settings). At checkout, all fields will be auto-filled with that default information.

##### Add Comment to an Order 

**Add comment**

Click on **Add Order Comment** in the top right menu icon. In the **Order Comment** box, type the content that reminds you of this order. Then, save it.

![Sample](./Image_Growth_m1/image226.png?raw=true)

**Check comment** 

There are 2 ways to Check Comment. The first one is on POS Front-end (Web POS Screen) and the other is in POS Back-end. 

- Web POS screen 

_Path: **Web POS > Order History > Comment History**_

![Sample](./Image_Growth_m1/image227.png?raw=true)

![Sample](./Image_Growth_m1/image228.png?raw=true)

- Back - end

_Path: **Sales > Orders > Click on specific order**_

![Sample](./Image_Growth_m1/image229.png?raw=true)

##### Process at Checkout for a Customer 

You have been through steps to add products to cart and add customer, let’s move to the checkout process.
When products are added to cart, click on **Checkout** button at the end of the cart page

![Sample](./Image_Growth_m1/image230.png?raw=true)

You will be redirected to the next page with information of Shipping & Payment Method. Please refer to Section **2.1.5. Enable Payment Method** and **2.1.4. Set up Shipping Method** for further details about payment and shipping method configuration for Web POS.

![Sample](./Image_Growth_m1/image231.png?raw=true)

**Credit Card**: Magestore’s Web POS supports Authorize.net & Stripe. Sales staff can fill in card information manually or swipe card (if the POS system is connected to a card swiper). For more information about how to connect, please go to section 

**Split Payment**: For more information about Split Payment, please go to section **5.1.6.4. Split & Partial Payment with Web POS**

Split and Partial Payment with POS

- Split Payment 

You can allow customers more than 1 method to pay when using Web POS. Particularly, they could pay a part of bill by cash and other part will be paid by credit card. 	

For example: This order values $321.55 and customer wants to pay $100 in cash. Then you have to enter this number in the field of “Web POS- Cash in” and the remain money will be calculated automatically for you. 

![Sample](./Image_Growth_m1/image232.png?raw=true)

To solve **Remain money**, you can click on **Add Payment** button on the left corner of the screen 

![Sample](./Image_Growth_m1/image233.png?raw=true)

After clicking on **Add Payment**, Customers have those options to pay for the remaining money

For instance, Customer chooses **Web POS – Credit Card** and the system will be displayed like this: 

![Sample](./Image_Growth_m1/image234.png?raw=true)

And then, please tap on Place Order button to complete this order. The process is done. 

_Notes:_

+ Support multiple payment methods for one order

+ Not require Cash-in method as compulsory

- Partial Payment 

This function allows customers to pay a part of value first and other parts will be paid later in different interval. Especially when customers want to reserve goods before it’s arrived at store, they could leave a deposit and they will complete the bill after having product in their hand. 

For example, the total value is $321.55, customers want to pay $100 first and $221.55 they will pay later

![Sample](./Image_Growth_m1/image235.png?raw=true)

Enter 100$ in the field of **Web POS – Cash in**

Tap on **MARK AS PARTIAL** 

And when customers come back to pay completely the bill, staff can check this order by checking **Orders History** (Path: from Web POS front-end top left menu icon > **Orders** section > **Orders History**).

![Sample](./Image_Growth_m1/image236.png?raw=true)

Let’s see an example: 

When customer came back and want to pay for the remaining. In the **Orders History**, you have to find out this partial order. For sure you are allowed to use filter to search it quickly in the Searching field. In this example, I prefer to use customer’s name 

![Sample](./Image_Growth_m1/image237.png?raw=true)

Click on this order to show details like this

![Sample](./Image_Growth_m1/image238.png?raw=true)

The total due is the total remain money that customer has to pay. 

Then, in the next step, tap on the button **Take Payment**

![Sample](./Image_Growth_m1/image239.png?raw=true)

Staff has to choose the payment method for the total due 

![Sample](./Image_Growth_m1/image240.png?raw=true)

Staff can keep on adding more payment methods as they want by clicking on **Add more Payment Method**. By clicking **Submit**, total paid will be equal to the whole value of order. Process is done.

##### Keep Order on Hold and Further Purchasing 

Your customers can't make up their mind yet, or are unable to make a payment meanwhile? They may want to purchase items that are for pre-order or currently out of stock? You don't want to lose those potential customers, don't you? Then, Web POS's new feature can put these orders on hold - no limit in time - until they are ready to continue processing!

**Put Orders on Hold** 

After adding products to cart, you can choose **Hold** to put the order into Web POS frontend top left menu > **Orders** section > **On-hold Orders**.

![Sample](./Image_Growth_m1/image241.png?raw=true)

**Check Orders on Hold** 

There are 2 ways to check Orders On-Hold. The first one is on Web POS Screen and the other is in Backend. 

- **Web POS screen**

_Path: **Web POS frontend top left menu > Orders section > On-hold Orders**_

![Sample](./Image_Growth_m1/image242.png?raw=true)

To check orders that have been put on hold, select **On-hold Orders** section. You may select **Checkout** whenever customer is willing to take final action for payment or you may **Delete** it if it is not effective anymore.

- **Backend**

If you turn on Sync on-hold order to server setting in WebPOS Frontend top left menu > **Settings** section > **General** > **Checkout**, you will be able to see on-hold orders in Magento backend > **Sales** > **Orders**.

![Sample](./Image_Growth_m1/image243.png?raw=true)

##### Print Receipt or Email Confirmation

You can print receipt or email order information right after creating an order. Remember that you must be online and have permission to do these actions

![Sample](./Image_Growth_m1/image244.png?raw=true)

Tap **Print** and the receipt will look like this picture below: 

![Sample](./Image_Growth_m1/image245.png?raw=true)

And here is the email of order information:

![Sample](./Image_Growth_m1/image246.png?raw=true)

##### Review Order 

_Path: **Web POS frontend top left menu > Orders section > Order History**_

In POS screen, you can review orders by choosing **Order History** tab. Here you can see the order list and order details:

![Sample](./Image_Growth_m1/image247.png?raw=true)

**Order Status** 

In order list, the status of order is distinguished by color

- **Pending**: Orange (When you create order successfully but have not shipped order and created invoice)

- **Processing**: Blue (When you have shipped order OR created invoice)

- **Complete**: Green (When you shipped order AND created invoice)

- **Canceled**: Gray (When you cancel the order)

- **Closed**: Black (When order has been refunded)

- **Not synced**: Red (When order’s data has not been synced to the system)

**Order Searching** 

To find an order to review, you can search it by Order ID or Customer’s Name/Email

![Sample](./Image_Growth_m1/image248.png?raw=true)

**View Order Information** 

To view detailed information, click on your wanted order. Please make sure that you have permission to check it. The detailed order will be shown like this

![Sample](./Image_Growth_m1/image249.png?raw=true)

##### Issue an Invoice for an Order 

The order can’t be complete if you haven’t issued invoice for customer. 

After the order is created successfully, you will find order’s details on tab **Order History** then click on tab **Invoice**

![Sample](./Image_Growth_m1/image250.png?raw=true)

##### Create Shipment for an Order 

**Create Shipment** 

There are two ways to create shipment using Web POS: **Before Placing an Order** and **When Reviewing Order**

- **Before Placing Order**: 

Before an order is created by clicking **Place Order**, you can create shipment by turn on **Marked as Shipped** as below:

![Sample](./Image_Growth_m1/image251.png?raw=true)

- **After Placing an Order** 

When order has been created successfully but hasn’t been shipped, you can go to **Orders History** (Path: Web POS frontend top left menu > **Orders** section > **Orders History**) and create shipment for that order.

![Sample](./Image_Growth_m1/image252.png?raw=true)

**Partial Shipment**

![Sample](./Image_Growth_m1/image253.png?raw=true)

After placing order successfully, you find that order in **Orders History** (_Path: Web POS frontend top left menu > **Orders** section > **Orders History**)._

Then you click on the menu icon on the right corner and choose **Ship**. 

A pop-up then appears so you can **enter the number of items to be shipped of each product**

Notes: Only orders that have been synced can be shipped.

![Sample](./Image_Growth_m1/image254.png?raw=true)

#### How to Issue Refund 

Some certain staffs have permission to issue refund (which is set by admin in backend. See section **3.2.2 Decentralize POS Staffs to assign access permission**).

Customers can get refund in either Store Credits, points or in cash. 

_Notes_: To enable refund by **Store Credit** and **Reward Points**, these two modules must be installed in your website.

To issue refund, following the path below: 

_Path: **POS screen** > **Orders**> Choose order required to refund > Click on **Refund** button at the top right menu

![Sample](./Image_Growth_m1/image255.png?raw=true)

A popup will display so that you can fill in the information before making refund. Tick **Return to stock** if you want to return those items back to your warehouse. 

![Sample](./Image_Growth_m1/image256.png?raw=true)

- **Adjust Refund**: The fee customers might have to pay for your store when requesting refund.

- **Adjust Fee**: The compensation customers get from your store if they have to request refund.

Check **Send Email** if you want a notification email to be sent to customer and click **Submit Refund** to finish.

After that, you will get the message informing that credit memo is created successfully. Please make sure you have permission to issue refund and you are in online mode.

#### How to View Report

_Path: Magento backend menu > **Sales** > **Web POS** section > **Reports**_

![Sample](./Image_Growth_m1/image257.png?raw=true)


![Sample](./Image_Growth_m1/image258.png?raw=true)

##### Staff Report 

On Staff report row, there are 3 types of reports: **Sales by staff**, **Sales by staff (Daily)** and **Order list for staff. **

![Sample](./Image_Growth_m1/image259.png?raw=true)

**Sales by Staff** 

There are 2 parts will be displayed on screen. The first one is **Filter** and the other is **Record**. 

In the Filter Section: System demand users date filter and **Order Status** to show suitable records and they will be displayed in the other part being at the bottom of the screen. 

This type of report will show the **Order count** as well as the **sales total** of each staff in your stores. 

![Sample](./Image_Growth_m1/image260.png?raw=true)

**Sales by Staff (Daily) 

![Sample](./Image_Growth_m1/image261.png?raw=true)

This kind of report will show the similar one like **Sales by Staff** report but it has one more detail which is showing the day receiving orders. 

**Order List for Staff** 

![Sample](./Image_Growth_m1/image262.png?raw=true)

In the **Order list by staff** report, you can view all order information including ID, value, history and status of each order created by any or each specific sales staff

##### Location Report

There are 3 types of Location Report which are **Sales by Location**, **Sales by Location(Daily)** and **Order List by Location**. 

![Sample](./Image_Growth_m1/image263.png?raw=true)

**Sales by Location** 

The **Sales by location** report shows the number of orders and sales created in each location, in any custom time.

![Sample](./Image_Growth_m1/image264.png?raw=true)

**Sales by Location (Daily)**

It shows the number of orders and sales created in each location by each day.

![Sample](./Image_Growth_m1/image265.png?raw=true)

**Order List by Location** 

You can view all order information including ID, value, history and status of each order created by all or each specific sale location.

![Sample](./Image_Growth_m1/image266.png?raw=true)

##### Payment Report 

The section of Payment Report has 4 different types of report including **Sales by payment method, Sales by payment method (Daily), Order list for payment method and Sales by payment method for location.**

![Sample](./Image_Growth_m1/image267.png?raw=true)

**Sales by Payment Method**

It displays the number of orders and sales paid by each payment method in a custom time period.

![Sample](./Image_Growth_m1/image268.png?raw=true)

**Sales by Payment Method (Daily)**

It shows the number of orders and sales created by each payment method by each day.

![Sample](./Image_Growth_m1/image269.png?raw=true)

**Order List for Payment Method** 

Users can view all order information including ID, value, history and status of each order created by all or each specific payment method.

![Sample](./Image_Growth_m1/image270.png?raw=true)

**Sales by Payment Method for Location** 

It displays the number of orders and sales created by each payment in each sale location

![Sample](./Image_Growth_m1/image271.png?raw=true)

##### Z- Report 

The **Z-Report** page displays overview information of each session recorded in each POS including Session ID, Staff account, POS name, session opening/closing time and balance. 

![Sample](./Image_Growth_m1/image272.png?raw=true)

![Sample](./Image_Growth_m1/image273.png?raw=true)

![Sample](./Image_Growth_m1/image274.png?raw=true)

Z-report shows the cash drawer balance in a certain time like a shift or a working day. All payment methods are listed down with the record of Grand Total in details respectively. If there is no customer use **Cash on Delivery** method to purchase orders, it will not appear in the **Payment Method** section.

The Z-report will be refreshed to serve new shift/working day after you select **Close Store**. Particularly, your cash drawer will be reset to 0 or to the certain amount that you set up in Cash Left. Each Z-report is automatically saved in Magento backend so you can check it again.

### Retailer POS 

Retailer POS module is available on both iPad and Android. In this user guide, we only demonstrate the use of the iPad version. The Android version may look a bit different, but functions are the same.

#### Log In and Manage Account 

**Log in** 

After downloading and installing Retailer POS in your iPad, open the app and you will see login screen. Staffs need to enter **domain, username** and **password**: 

![Sample](./Image_Growth_m1/image275.png?raw=true)

_Notes_: you can hide the Demo button in **Settings > General**

After that, staff needs to choose their POS to start using the app.

![Sample](./Image_Growth_m1/image276.png?raw=true)

After successfully log in, you will see either:

- Checkout screen to start adding products to cart and checkout, if there is an opening session already or if opening session setting is turned off in backend setting (_Path: **Sales > Web POS > Settings > **General Configuration** section > **Need to create session before working** field); OR you will see

- Opening Balance window if you enable **Need to create session before working** field in POS backend (please refer to **5.2.2. Use Session Management** for details about session)

**Manage Account** 

Manage account by clicking on the menu icon at the top left of the screen > **Settings**

There are 5 tabs to configure settings: **General, My Account, Checkout, Print & Currency**

- **General** 

![Sample](./Image_Growth_m1/image277.png?raw=true)

Users can set timing when the screen automatically switch to locking mode, change PIN code and hide demo button on the Login screen

- **My Account** 

![Sample](./Image_Growth_m1/image278.png?raw=true)

Users can change password if they want

- **Checkout** 

![Sample](./Image_Growth_m1/image279.png?raw=true)

(1) **Create shipment when placing order**: if you enable this setting, after an order is checked-out successfully, it will automatically be marked as shipped. 

(2) **Available Qty**: this setting is only available to use in Magento 2. 

(3) **Enable Google Address Suggestion** is also available to use in Magento 2.

-**Print**

![Sample](./Image_Growth_m1/image280.png?raw=true)

You can choose the printer type and preferred settings for each type including paper size (for Air Printer Scroll); paper size, automatically open cash drawer after checkout, number of receipt copies to be printed out, automatically print receipt after checkout and either to display product name or its SKU on the receipt (for Star Micronics Printer).

- **Currency**

![Sample](./Image_Growth_m1/image281.png?raw=true)

Allows changing to another currency that is preset in backend settings. 

_Notes_: all previous orders will be removed from Order History after you change currency.

**Switch between Staffs with PIN Code** 

Based on staff role and responsibility, each staff will be set restrictions. Limit who can make a discount or give a refund.

However, with Retailer POS, staffs can flexibly switch between cashiers in the middle of transaction just with a PIN code (4 digital) which is added to when creating a POS user. Follow the step below to switch between users:

- On the left top of the screen click on **Change icon** and choose the POS user.

![Sample](./Image_Growth_m1/image282.png?raw=true)

- Insert the user's PIN code to continue.

![Sample](./Image_Growth_m1/image283.png?raw=true)

Shortly after can you see that the cashier has changed.

After logged in, you can change your account’s PIN code

#### Use Session Management 

Session Management is a place where records cash flow after each cashier’s shift. You have frequent cash in/out beside normal order transactions like paying electrical bills, balancing cash amount in hand, etc. Retailer POS system records deposits and withdrawals from your working shift then compare them with actual cash amount (counted in notes) after cashier’s shift ends up. 

_Notes_: To enable session, you need to go to backend, follow Path: **Sales > Web POS > Settings > **General Configuration** section, choose **Yes** for **Need to create session before working**

![Sample](./Image_Growth_m1/image284.png?raw=true)

##### Open Session 

After you choose **Yes** in back-end to require opening a session before working and no session is already opened, the following pop-up will be shown after you logged in:

![Sample](./Image_Growth_m1/image285.png?raw=true)

Cashiers will carry out to open a new session before getting started their shift. 

**Responsible**: Role of POS user (Cashier, Order management, etc.)

**Point of sales**: Select POS you are working

**Opening Balance**: Cashier needs to enter the total amount of cash at the beginning of a new session in your drawer

**Set Opening Balance**: to enter the total amount of cash, cashier can click on this to pop-up a window. Then, cashier can enter the specific value and amount of each banknote/bill/coin that adds up to the total amount of cash.

![Sample](./Image_Growth_m1/image286.png?raw=true)

Then click **Open Session** to begin your shift. You will be directed to the **Session** window. 

##### Record Cash In/ Cash Out 

After you start a new session, you will see basic information on the current session in the **Session** window and may make adjustment of cash in/out during your shift, record deposits and withdrawals from your cash drawer. 

You can always access to this Session window by go to top left Menu > **Session Management** section > **Session**

![Sample](./Image_Growth_m1/image287.png?raw=true)

Here you can view all the previous sessions of the Account. Select a session to see its details including date and time, transactions in the session.

![Sample](./Image_Growth_m1/image288.png?raw=true)

During an opened session, cashier can add extra cash in/out of the cash drawer by clicking on **Put Money In/ Take Money Out** buttons in this **Session** window. Cash in and out appears in the drawer history on the iPad, with both the description you enter and the total amount in the drawer.

![Sample](./Image_Growth_m1/image289.png?raw=true)

**Put Money In**: Enter the cash amount you add to your drawer, description and click **Make Adjustment** button

![Sample](./Image_Growth_m1/image290.png?raw=true)

**Take Money Out**: Enter the cash amount you remove from your drawer and a description and click **Make Adjustment** button.

![Sample](./Image_Growth_m1/image291.png?raw=true)

##### End Session 

_Path: from top left Menu > **Session Management** section > **Session**

After your shift is ended, you can close your session by selecting the opened session and click **Close session** button.

![Sample](./Image_Growth_m1/image292.png?raw=true)

You will see the Close Session window as below:

![Sample](./Image_Growth_m1/image293.png?raw=true)

(1) You can **Put Money In** and **Take Money Out** like in _Record Cash In & Cash Out_

(2) The window displays detailed information of the session: **Opening Balance**, **Transaction** in the session, **Theoretical Closing Balance**. Cashier needs to enter the amount of cash in the cash drawer at the end of the shift in the **Real Closing Balance** field. The Difference between **Theoretical Closing Balance** and **Real Closing Balance** is automatically calculated.

(3) To enter the total amount of closing balance in line, cashier can enter the specific value and amount of banknote/bill/coins that add up to the total closing balance here (the screenshot is as below). Then click **Confirm** to finish.

![Sample](./Image_Growth_m1/image294.png?raw=true)

(1) Click **Close Session** to preview your session in the next window.

![Sample](./Image_Growth_m1/image295.png?raw=true)

(2) Click **Validate** to confirm closing session. Or you can **Re-entry Data** to go back to **Close Session** window and correct any mistakes.

#### Filter and Search Products Quickly 

To configure Product Search in back-end, please refer to **2.1.6. Configure Product Search**

In front-end, users could search product in 3 ways: **Categories, Product Attribute** & **Barcode Scanning**

**Categories** 

![Sample](./Image_Growth_m1/image296.png?raw=true)

Click on **All Products** link on the top bar to quickly search products by categories. Choose the corresponding categories as you prefer.

**Product Attribute**

To search by product attributes, use the **Search bar**. Enter your search terms and matching products will display right away as you type. Clicking on a suggested item will add it to the customer’s cart.

![Sample](./Image_Growth_m1/image297.png?raw=true)

**Barcode Scanning** 

Our Retailer POS allows quick product search by scanning barcode. You just need to click on the **Barcode scanning** icon in the **Search bar** and scan the product’s barcode to add it to cart

![Sample](./Image_Growth_m1/image298.png?raw=true)

#### Add Product to Carts and Edit Products in Cart 

##### Add Product to Cart 

- With **Simple Product**, you just need one tap to add it to cart. 

- With **Configurable, Bundle, Grouped Product**, after clicking, you will see a popup shown to choose options (e.g. color, size). Then, tap on **Add to Cart** button: 

![Sample](./Image_Growth_m1/image299.png?raw=true)

##### Edit/Remove Product Quantity on Cart 

After adding products to cart, you can edit the quantity of each product by selecting the product that needs editing. A popup will display with edit option for Qty.

![Sample](./Image_Growth_m1/image300.png?raw=true)

- To edit Qty., just enter a wanted number or tap on +/-. The number of products will be adjusted in the cart right away. 

- Adjust quantity to 0 to remove the item from the cart.

- To delete the whole cart, tap on the trash icon on the left menu bar

![Sample](./Image_Growth_m1/image301.png?raw=true)

##### Add Custom Sale Item to Cart 

**Custom sale item** _is the item that Retailer POS user creates when checkout. It is used when the product hasn’t been added to the system or Retailer POS user cannot find it in the product list_ 

In frontend, select **Custom Sale** button if you want to add the custom product to Cart 

![Sample](./Image_Growth_m1/image302.png?raw=true)

(1) **Name**: Enter the name of custom product

(2) **Shippable**: Choose whether this product will be shipped or not by turning on or off this option

(3) **Price**: Enter the price of this product

After finishing configuration, tap **Add to Cart** button and check out as normal. _Please note that this custom sale product will not be saved for the next checkout._

#### Apply Coupon Code or Discount to Carts

##### Apply Discount 

![Sample](./Image_Growth_m1/image303.png?raw=true)

To apply a discount on the whole cart, tap **Discount** and then this popup will be shown: 

![Sample](./Image_Growth_m1/image304.png?raw=true)

In **Custom Discount** tab:

(1) **Name**: Enter a name for this discount as you will easily check it again

(2) **Discount Type**: Select discount by fixed amount or percentage

(3) **Amount**: Fill in discount value as you offer for your customers.

(4) Then, the cart will be updated automatically after you click on **Apply** button.

After applying Discount, you can remove it by clicking on the **Remove Discount** button.

![Sample](./Image_Growth_m1/image305.png?raw=true)

##### Apply Coupon Code 

![Sample](./Image_Growth_m1/image306.png?raw=true)

Just fill in available coupon you want to offer for your customers. The cart will be updated automatically after you click on **Apply** button.

##### Apply Custom Price or Custom Discount to a Product 

After adding products to cart, besides editing the quantity of each product you can click on the product to edit other information. 

![Sample](./Image_Growth_m1/image307.png?raw=true)

A popup will display with edit option for **Custom Price**, **Discount**. Remember that you can only change information by **Custom Price** _OR_ **Discount** but not both at a time for a product.

- **Custom Price** 

![Sample](./Image_Growth_m1/image308.png?raw=true)

You can set custom price for a product by clicking on the Product and selecting **Custom Price** button.

In the popup, please choose the type you want to adjust for the price, according to fixed number or percentage.

+ If you edit fixed price, the price will be changed to the price you have entered

+ If you edit by percentage, the price will be decreased by the percent you have entered (it is as same as Discount by percentage)

Then, products in cart will be updated with the price you edit

- **Product Discount** 

Editing discount for each product is as similar as **Custom Price**

Click on **Discount** button and choose types of discount–fixed discount or percentage–you want to adjust.

#### Handle Customer's Information and Check Out 

##### Customer Checkout

To use **Customer Checkout**, add customer by clicking on **Add Customer** link. You will see a screen as below:

![Sample](./Image_Growth_m1/image309.png?raw=true)

+ **Search Customer**

In the search box, you can quickly find the customer by entering his name, email, phone or address. Choose customer from suggested results in dropdown list.

The information of customer in the system will be auto updated in checkout step. 

![Sample](./Image_Growth_m1/image310.png?raw=true)

+ **QR code/ Barcode scanning 

Our Retailer POS offers an extremely convenient way for your customer checkout process by allowing scanning customer’s QR Code/ Barcode in their member card or loyalty app.

![Sample](./Image_Growth_m1/image311.png?raw=true)

Click on the **Scan icon** in the Search bar. The system will automatically fill customer info into checkout form. 

+ **Create New Customer** 

Click on **Create Customer** button

![Sample](./Image_Growth_m1/image312.png?raw=true)

Fill enough information of the customer such as **First Name, Last Name, Email, Phone, Group of Customer**. Remember to tap **Save** button to save the customer information for the next checkout.

![Sample](./Image_Growth_m1/image313.png?raw=true)

Fill in the information for **Shipping Address** such as **Phone, Street, City, etc**.

![Sample](./Image_Growth_m1/image314.png?raw=true)

Fill enough information of **Billing Address** such as **Phone, Street, City,** etc.

![Sample](./Image_Growth_m1/image315.png?raw=true)

##### Guest Checkout

When you use Guest Checkout, the default customer that you configure in backend will be used (please refer to **Section 2.1.7. Default Guest Check Out** for more details). At checkout, all fields will be auto-filled with that default information.

![Sample](./Image_Growth_m1/image316.png?raw=true)

#### Add Comment to An Order

##### Add Comment

After selecting an order, from the menu icon on the top right, choose **Add Order Comment** 

![Sample](./Image_Growth_m1/image317.png?raw=true)

In the **Order Comment** box, type in the content and click on **Save**. Click on **Cancel Comment** to exit the comment function.

##### Check Comment

Users can check comment on Retailer POS Screen or in Magento Back-end

- **Retailer POS Screen** 

![Sample](./Image_Growth_m1/image318.png?raw=true)

To view comment of order, you can go to **Orders** tab in Retailer POS top left menu, choose an order then scroll down to see Comment History

- **Magento Back-end**

Go to **Sales** > **Orders** > Click on a specific order. In order details page, scroll down to **Comment History** tab to check whether it has any notes or not.

![Sample](./Image_Growth_m1/image319.png?raw=true)

#### Process at Checkout for Customers

When the products are added to cart, select **Checkout** button at the end of the cart page

![Sample](./Image_Growth_m1/image320.png?raw=true)

You will be redirected to the next page with information of **Shipping & Payment Method**

![Sample](./Image_Growth_m1/image321.png?raw=true)

(1) **Need to Ship**: Turn on to add Shipping Address

(2) **Shipping Method**: Choose a shipping method (please refer to **2.1.4. Set up Shipping Method** for more details)

(3) **Payment Method**: choose a payment method by clicking in an option (please refer to **2.1.5. Enable Payment Method** for Retailer POS for more details). You can add more than one payment method (please refer to **5.1.6.4. Split and Partial Payment**) 

(4) **Gift Card**: enter the Gift Card code to apply discount. You can apply more than one code. (please refer to **Manage Gift Codes** for details about creating gift codes)

(5) **Marked as shipped**: turn it on to mark to order as “Shipped”

(6) **Note**: enter comment for the order (optional)

After that, click on **Place Order** button to complete checkout process. There will be a notification as below:

![Sample](./Image_Growth_m1/image322.png?raw=true)

Click **New Order** to go back to the Checkout window and continue creating order/checkout for another guest. Click **Print** to print the order receipt.

##### Split Payment 

You can use more than 1 payment method for split payments when check out with Retailer POS. 

Here is an example for you: The order value is $45. Your customer wants to pay $20 in cash and the remaining ($25) is paid by Custom Payment. Then, you will fill the amount at the blank space next to “Web POS – Custom Payment 2”. Then click **Place Order** to finish.

![Sample](./Image_Growth_m1/image323.png?raw=true)

_Notes:_ 

+ Support multiple payment methods for an order 

+ Not require cash as compulsory  

##### Create Multi Orders for Different Customers 

Retailer POS allows you to create multi-orders for different customers and keep orders open until customers end up transaction. That means you can open multiple orders to serve lots of different customers at the same time. For example, someone is paying for something in your shop but realize they forget their wallet.  You can keep this order open until they come back with their money while you still can carry on serving the next customer.

_Note_: These orders will be automatically deleted once you log out.

![Sample](./Image_Growth_m1/image324.png?raw=true)

You can **Delete** an opened order by clicking on the **Trash icon**. If you turn on **Need to confirm before deleting order (App only)** setting in backend, you will need to confirm before deleting the order.

#### Create Shipment

##### Create Shipment 

There are 2 ways to create shipment: **Before placing order** & **When reviewing order**

**Before Placing Order** 

Before clicking **Place order** to accomplish customer purchasing process, Staffs can create shipment by turn it on as below and enter Shipping Address.

![Sample](./Image_Growth_m1/image325.png?raw=true)

After verifying shipment method, the system will automatically load to Successful Order Page.

**When reviewing Order** 

_Path: **Order history** > from the top right menu choose **Order** > **Ship**

![Sample](./Image_Growth_m1/image326.png?raw=true)

There will be a message shown to notify you that shipment is created successfully. Please note that to use this way, you need to have permission

##### Partial Shipment 

If you chose to enable Partial Shipment, a box of Items to Ship will appear when you tap **Ship** in Order Tab. Enter the quantity of each product customers want to ship, select **Ship**

![Sample](./Image_Growth_m1/image327.png?raw=true)

#### Issue Refund 

Some certain staffs have permission to issue refund by cash, according to your staff decentralization in section **3.2. How to manage Staff** for POS

To issue refund, go to **Orders** tab in POS screen, you choose the order that is required to refund. Tap on **Refund** button in the end

![Sample](./Image_Growth_m1/image328.png?raw=true)

A popup will display so that you can fill in the information before making refund. Tick **Return to stock** if you want to add those items back to your stock.

![Sample](./Image_Growth_m1/image329.png?raw=true)

After that, you will get the message informing that credit memo is created successfully. Please make sure you have permission to issue refund.

#### Print Receipt and Email Orders 

You can print receipt or email order information right after creating an order. Remember that you must be online and have permission to do these actions.

![Sample](./Image_Growth_m1/image330.png?raw=true)

The receipt will look like the screenshot below with further options in the top right menu.

![Sample](./Image_Growth_m1/image331.png?raw=true)

#### Review Order

In POS screen, you can review orders by choosing **Orders tab** from sidebar. Here you can see the order list and order details

![Sample](./Image_Growth_m1/image332.png?raw=true)

The status of order is distinguished by color: 

(1) **Orange**: Pending: the order is placed but not processed (shipped/invoiced/ etc.)

(2) **Blue**: Processing: the order is processed, but not invoiced

(3) **Green**: Complete: the order is invoiced 

(4) **Grey**: Cancelled: pending order that has been cancelled 

(5) **Black**: Closed: processing order that has been cancelled

To quickly find an order to review, you can search it by Order ID or Customer’s Name/Email

![Sample](./Image_Growth_m1/image333.png?raw=true)

#### Run Sales Report 

Please refer to **5.1.8. How to View Report** for details.

### Inventory Management 

#### Stock Listing 

##### Stocks in Warehouse 

_Path: **Inventory Management** > **Stock Listing** section > **Stocks in Warehouse**

![Sample](./Image_Growth_m1/image334.png?raw=true)

This page provides an overview of stock data in all warehouses and admin can **select a warehouse** to view stocks of that warehouse only. It shows **Available Qty., Qty. to Ship, Total Qty.** and **Shelf Location** of each product in that warehouse. 

![Sample](./Image_Growth_m1/image335.png?raw=true)

After selecting a specific warehouse, admin can easily update stock and shelf location right on the Inventory grid:

(1) Mark the checkbox to select products

(2) **Qty. in Warehouse(s)**: Edit product quantity in line

(3) **Shelf Location**: Input the product’s Shelf location (optional)

(4) Click on **Update Stock** to save changes

##### Non-warehouse product

_Path: **Inventory Management** > **Stock Listing** section > **Non-Warehouse Products**

When a product is newly added to the system, it will be automatically allocated in Non-warehouse. Admin can assign this product to any warehouses. 

![Sample](./Image_Growth_m1/image336.png?raw=true)

From here admin can: 

(1) Select the product by clicking on the checkbox

(2) In Actions menu, add it into warehouse by clicking on its **Add to Warehouse** from the drop-down list

(3) Click **Submit** to finish

##### Warehouse

_Path: **Inventory Management** > **Stock Listing** section > **Warehouses**

After installing, the system will automatically provide a **Primary Warehouse**. This warehouse _cannot be deleted and can only be edited._ All the existing products with stocks level of your website will be automatically allocated in this warehouse first before being sent to other warehouses.

**Add a New Warehouse** 

Please refer to Section **4.4.1. New Warehouse** for details.

**View Warehouse's Information** 

![Sample](./Image_Growth_m1/image337.png?raw=true)

Click on **View** to the warehouse detailed information

![Sample](./Image_Growth_m1/image338.png?raw=true)

In the **View Warehouse** page, there are 6 tabs to manage the warehouse:

(1) **General Information**: Information of the Warehouse including Name, Code, address, etc

(2) **Stock On Hand**: the total number of goods that are available in the warehouse in real time. Here, you can update each product's Qty. in Warehouse(s) and its Shelf Location in-line.

(3) **Stock Movement**: all the changes in stock quantities. Click on each record to view in detail.

(4) **Warehouse Permission** manages staff access to the warehouse. Detailed guide is given in the next section c. Warehouse permissions

(5) **Order**:  records of all orders including status, order ID, purchase date, customer that the order has been billed-to/shipped-to, order value.

(6) **Dashboard** contains reports that are illustrated as table and lines diagrams as below.

![Sample](./Image_Growth_m1/image339.png?raw=true)

![Sample](./Image_Growth_m1/image340.png?raw=true)

**Warehouse Permission** 

_Path: **Inventory Management** > **Stock Listing** section > **Warehouse** > **Warehouse Permissions**

In this section, Admin can give different warehouse access permissions to different (admin) users.
Click on **View** to see the warehouse’s detail information

![Sample](./Image_Growth_m1/image341.png?raw=true)

(1) On the right hand of the **Warehouse Permission** tab, click on **Assign Staff** to give different warehouse access permissions.

Then will be a new pop-up screen shown as below:

![Sample](./Image_Growth_m1/image342.png?raw=true)

Select Staff users to assign permission

(1) Select Staff by marking the checkbox

(2) Choose **Staff Role**

(3) Click on **Add Selected Staff**

![Sample](./Image_Growth_m1/image343.png?raw=true)

(4) Then click on **Save Staff Permissions**

#### Transfer Stock

##### Send Stock and Request Stock 

- **Send Stock** 

_Path: **Inventory Management** > **Transfer Stock** section > **Send Stock**_

If admin wants to send stock from his warehouse to another warehouse, he can use this feature to record stock sending. 

The process to Send stock is: **Add new send stock > Prepare Product list > Select Products > Start Send Stock > Save Receive Stock > Mark as Completed**

+ **Step 1: Add New Send Stock**

![Sample](./Image_Growth_m1/image344.png?raw=true)

(1) Fill the **Transfer Code**

(2) Choose **Source Warehouse**

(3) Choose **Destination Warehouse**

(4) Fill the **Notification recipients** (if any)

(5) Fill in the **Reason box**

+ **Step 2: Prepare The Product List**

![Sample](./Image_Growth_m1/image345.png?raw=true)

To prepare product list, click on the **Prepare Product List** button

If you choose **Select Products**:

![Sample](./Image_Growth_m1/image346.png?raw=true)

(1) Click on the product needed

(2) Choose the quantity to transfer  

(3) Click on **Start Sending**

The system will display a notification when the transfer is completed.

+ **Step 3: Receive Stock**

Destination warehouse can create receives by either _importing_ via a CSV file, scan barcode or _selecting products_ from the list of Sent products.

![Sample](./Image_Growth_m1/image347.png?raw=true)

If you **Select Products** in **Receiving history** tab:

![Sample](./Image_Growth_m1/image348.png?raw=true)

(1) Select the product to receive 

(2) Enter the quantity received in receiving history

(3) Click on **Save Receiving** and the system will display a notification about the Successful Receipt

You can also view and **Download Shortfall List** – the list containing the products that the Destination warehouse does not receive from Source warehouse

Or **Return products**, also on the same page

- **Request Stock**

_Path: **Inventory Management** > **Transfer Stock** section > **Request Stock**

If a warehouse lacks stock, admin can create a Stock request to get stock from other warehouses. The process to request stock is: **Add new request stock > Prepare Product list > Select Products> Start Request Stock > Save Delivery Stock > Save Receive Stock > Mark as Completed**

+ **Step 1: Add New Request Stock 

![Sample](./Image_Growth_m1/image349.png?raw=true)

(1) Fill the **Transfer Code**

(2) Choose **Source Warehouse**

(3) Choose **Destination Warehouse**

(4) Fill the **Notification recipients**

(5) Fill in the **Reason box**

+ **Step 2: Prepare the Product List** 

![Sample](./Image_Growth_m1/image350.png?raw=true)

To prepare product list, click on the **Prepare Product List** button

If you choose **Select Products**:

![Sample](./Image_Growth_m1/image351.png?raw=true)

(1) Click on the product needed

(2) Enter the quantity to transfer 

(3) Click on **Start to request**

The system will display a notification when the transfer is completed.

+ **Step 3: Delivery History**

Source warehouse when receives the stock request can create a stock delivery. When a stock delivery is created, stock will be subtracted immediately from the source warehouse.

![Sample](./Image_Growth_m1/image352.png?raw=true)

You can either import products via a CSV file, scan barcode or click on **Select Products** in delivery history.

If you choose to **Select Products**:

![Sample](./Image_Growth_m1/image353.png?raw=true)

(1) Select the products to be added

(2) Enter the delivered quantity in delivery history 

(3) Click on **Save Delivery**

+ **Step 4: Receiving History**

Destination warehouse can create receives by importing or selecting product then update received Qty. 

![Sample](./Image_Growth_m1/image354.png?raw=true)

(1) Select the products to receive

(2) Enter the quantity received in receiving history  

(3) Click on **Save Receiving**

The system will display a message when the receiving is created successfully. 

After that, stock will be added immediately to the destination warehouse from which the stock request was sent.

You can also download **Shortfall List & Summary** of the Stock Request.

##### Transfer to External Location 

_Path: **Inventory Management** > **Transfer Stock** section > **Transfer to External Location**

This feature allows you to record sending the product to an external destination e.g. when the product is damaged, loss or sent as free gift…

![Sample](./Image_Growth_m1/image355.png?raw=true)

(1) Fill the **Transfer Code**

(2) Choose **Source Warehouse**

(3) Fill the **External Location**

(4) Fill **Notification recipients**

(5) Fill in the **Reason box**

(6) Click on **Prepare Product List**

Then, you can add or import products to transfer stock by **Scan Barcode**, **Import** or **Select Products.**

If you choose to **Select Products** from your inventory:

![Sample](./Image_Growth_m1/image356.png?raw=true)

(1) Select the products to be added

(2) Fill the Qty.

(3) Click on **Start Transferring** to finish 

##### Transfer from External Location 

_Path: **Inventory Management** > **Transfer Stock** section > **Transfer from External Location**

This feature allows you to accept the stocks from outside of the system. Not only from another warehouse but can be from any other source. 

![Sample](./Image_Growth_m1/image357.png?raw=true)

(1) Fill the **Transfer Code**

(2) Choose **Destination Warehouse**

(3) Fill the **External Location**

(4) Fill **Notification recipients**

(5) Fill in the **Reason box**

(6) Click on **Prepare Product List**

Then, you can add or import products to transfer stock by clicking on **Scan Barcode, Import** or **Select Products**.

If you choose to **Select Products** from your inventory:

![Sample](./Image_Growth_m1/image358.png?raw=true)

(1) Select the products to be added

(2) Fill the **Qty**.

(3) Click on **Start Transferring** to finish

##### Transfer Stock History 

![Sample](./Image_Growth_m1/image359.png?raw=true)

This History records stock movements from send stock, request stock, transfer from external and transfer to external.

#### Stock Control 

##### Stock Adjustment & Stock Adjustment History 

- **Link stocks in Warehouse to Front Store View** 

As mentioned in section **2.3.1.Stock Control Configuration**, you can link products and stock data by choosing **Yes** on the **Link stocks in Warehouse to Front Store View** section in _Settings menu_.

- **Add New Stock Adjustment** 

_Path: **Inventory Management** > **Stock Control** section > **New Stock Adjustment**_

![Sample](./Image_Growth_m1/image360.png?raw=true)

Under menu Stock Control, you can create new Stock Adjustment in a few steps:

(1) Choose the Warehouse.

(2) Adjustment Code: is automatically generated. All adjustments are saved in Inventory Management > Stock Control section > Stock 

(3) Adjustment History

(4) Fill the Reason

Then click button **Start to Adjust** 

![Sample](./Image_Growth_m1/image361.png?raw=true)

To change **Stock Adjustment** status to _Completed_, you need to hit button **Adjust**.

_Notes_: you can **Change Qty**. or **Adjusted Qty**., depending on how you configure in **Store Configuration** (please refer to section **2.3.1. Stock Control Configuration**)

Once the Adjustment is _Complete_, there is no way to undo it.

Stock level will be updated instantly in the corresponding warehouse.

- **View Stock Adjustment History**

_Path: **Inventory Management** > **Stock Control** section > **Stock Adjustment History**

![Sample](./Image_Growth_m1/image362.png?raw=true)

You can view all records of Stock Adjustments in this page with information including Time created, staff created, warehouse and status … Click on each Adjustment, you can see stock adjustment details. 

If you click on a **Completed** adjustment, you will be able to export the product list of that specific adjustment by clicking the button **Export**.

##### Stock Taking & Stock Taking History

Physical Stocktaking acts can be used at any time to double-check and correct inventory discrepancy amounts in Inventory Management vs. physical inventory in your warehouses. These consist of:

- A count, in which warehouse staff records the actual number of products in stock at the time of inspection & a manager can rely on it to update inventory in the system later

-Then a confirmation of that count performed by a warehouse manager to officially update the correct number of products in stock (Adjust Stock)

- **Stocktaking Process** 

_Path: **Inventory Management** > **Stock Control** section > **New Stocktaking**_

![Sample](./Image_Growth_m1/image363.png?raw=true)

There are 5 steps in Stock taking using Inventory Management:

+ **Step 1: Fill General Information** 

After finishing this step, Stocktaking Process Status is **Pending** 

![Sample](./Image_Growth_m1/image364.png?raw=true)

(1) Choose Warehouse

(2) Fill the Stocktaking Code

(3) Fill in the Participants (It is optional)

(4) Fill the Stocktaking Time of the action (It is optional)

(5) Fill the Reason

(6) Choose the products to be stock taken by clicking the **Prepare Product List** button (Stage 2) at the top right of the page. Alternatively, you can skip it to go straight to Stage 3 by clicking the **Start Stocktaking** button

+ **Step 2: Prepare products before doing stock take** 

Select or import products to prepare before doing stock take. Stock taking status will change to **Processing**

![Sample](./Image_Growth_m1/image365.png?raw=true)

(1) Mark the checkbox to _select products_ from your product list, _scan barcode_ or _Import products_ from CSV file (template provided)

(2) Click **Save** to stay with your selected products for further edits, or click **Start Stocktaking** to proceed Stage 3.

+ **Step 3: Do Stock Take**

Fill in the Qty. of product. Now status is changed to **Verified**

![Sample](./Image_Growth_m1/image366.png?raw=true)

(1) Select products needed and enter the product quantity that you have recently counted and the reason why there is quantity difference.

(2) Either click **Complete Data Entry** to proceed to Stage 4 and have a review of the changes; click **Complete Stocktaking** to finish the process; or **Save** to continue editing.

+ **Step 4: Complete Data Entry** 

Save the data that has been stock taken and waiting for admin’s approval.

![Sample](./Image_Growth_m1/image367.png?raw=true)

This Stage allows you to have a final review of your recent quantity counts. Click either **Re-entry Data** to edit the quantity or **Complete Stocktaking** to move to Stage 5. If you are not an admin, your counting results will be submitted to the admin/ manager for approval before the new quantity is officially updated and the process is marked **Completed**.

+ **Step 5: Complete Stock Take**

When admin does this, Stock taking status will be changed to **Complete**.

![Sample](./Image_Growth_m1/image368.png?raw=true)

Qty. is adjusted in the warehouse. Similar to Adjust Stock, stock taking cannot be edited after status is Complete. After doing stock take, admin can easily view and export the difference between real stock in the warehouse and the stock level updated by the system

- **Stocktaking History** 

_Path: **Inventory Management** > **Stock Control** section > **Stocktaking History**_

![Sample](./Image_Growth_m1/image369.png?raw=true)

(1) All Stocktaking details are listed here. Click on each record to view all details of the process. Different status shows to which stage the stocktaking process is done:

+ Status _Pending_ means Stage 1: General Information is done

+ Status _Processing_ means Stage 2: Prepare Products is done

+ Status _Verified_ means Stage 3: Stock Counting is done

+ Status _Complete_ means the whole stocktaking process is done

(2) You can also click on **Add Stocktaking** button to start a new stocktaking process from here.

##### Stock Movement History 

_Path: **Inventory Management** > **Stock Control** section > **Stock Movement History**

The module records all the movements of stocks in warehouse. These movements are reflected in **Stock Movement** report under **Stock Control** submenu.

![Sample](./Image_Growth_m1/image370.png?raw=true)

(1) The table shows SKU of the products added or subtracted from warehouse, the changed Qty., Warehouse name, Date and Reference number to see the details on a click.

(2) Export: Admin can also easily export Stock Movement details into _CSV_ or _Excel XML_.

#### Prediction 

##### Supply Needs

_Path: **Inventory Management** > **Prediction** section > **Supply Needs**

This feature predicts how many inventory items a warehouse need for each product within a future period. The system will calculate this number based on your sales history in the corresponding period in the past.

![Sample](./Image_Growth_m1/image371.png?raw=true)

(1) Warehouse(s): Select the warehouse to forecast supply needs.

(2) Sales Period: Select the sales period so that the system will calculate this number based on this sales history.

(3) Forecast Supply Needs Until: Pick the date that you want to see forecast results.

(4) Click to Show Supply Needs button to finally view the prediction.

The forecast data will be shown in the table as below:

![Sample](./Image_Growth_m1/image372.png?raw=true)

(1) The table displays supply needs information as below:

+ Current Qty: the product quantity that you currently have in the warehouse

+ Sold Qty per day: average quantity sold per day of the product during the chosen sales period

+ Availability Date: the system predicts your stock is enough to be sold until this date. After this date, your product is estimated to run out of stock.

+ Supply Need: the quantity of product that expected to be sold until the time stamp you set.

(2) The Supply Need Forecast can be exported to CSV or XML file by hitting Export button.

(3) You can start another prediction by expanding and editing criteria for supply forecast and hit **Show Supply Needs** again to refresh the prediction result.

##### Low Stock Rules 

_Path: **Inventory Management** > **Prediction** section > **Low Stock Rules**

_Notes_: **Low Stock Alert** is when a type of product is on the verge of low-stock, Low Stock Alert will alert the Inventory manager to import more items. This feature avoids lack of items to supply for stores.

![Sample](./Image_Growth_m1/image373.png?raw=true)

Select an existing rule to edit or click **Add New Rule** button at top right of the page. Admin can create unlimited rules to notify low stock status. One rule contains: **Rule Information**, **Conditions & Action**. There is no limitation in the quantity of rules set

- **Rule Information* 

![Sample](./Image_Growth_m1/image374.png?raw=true)

(1) **Rule Name**: Enter the low stock rule name

(2) **Description**: Add a brief about the rule (optional)

(3) **Status**: Select Active to enable the rule

(4) Use Calendar to choose From and To date for a term of validity (optional)

(5) Select an _update time_: either Daily or Monthly 

The system periodically checks stock availability and automatically send email notifications admin and warehouse managers.

(6) **Select hours** the warning message will be sent

- **Conditions** 

There are _2 types_ of low stock rule:

![Sample](./Image_Growth_m1/image375.png?raw=true)

+ **Type 1: Availability Quantity 

_Availability Qty._: you can select Qty. threshold that the system will notify to import.

(1) Low-stock Threshold Type: Select Availability Qty.

(2) Threshold (quantity): Set the number of threshold quantity

(3) Notification Scope: Select Both Warehouse and Global for notification scope

(4) Warehouse(s): Select Warehouses for those rules will be applied.

![Sample](./Image_Growth_m1/image376.png?raw=true)

+ **Type 2: Availability Day**: _you can select Day Threshold that system can notify you to import items. You do not need to enter the Qty. here because the system will automatically calculate the selling rate based on the sale period you provided and the real Qty. in your warehouse and (store)._

(1) Low-stock Threshold Type: Select Availability Days

(2) Threshold (days): Set the number of threshold days

(3) Sales Period (days): Set the number of sales period days

(4) Notification Scope: Select Both Warehouse and Global for notification scope

(5) Warehouse(s): Select warehouses for those rules will be applied.

- **Action** 

![Sample](./Image_Growth_m1/image377.png?raw=true)

(1) Notification recipient list: Enter an email list to send the low stock notifications to

(2) Warning Message: Enter content of the warning message

(3) Click Save Rule or Save and Apply to finish

+ Save and Continue Edit: to save the process and continue edit on the current page.

+ Save and Apply: you can apply rule immediately

+ Save Rule: you can save the rule, but it will not be applied, in case you need to ask for permission before applying or double-check with other people.

_Note_: You can edit the rule that you **Save and Apply** or Save by going to **Stock Management > Prediction section > Low Stock Rules > clicking on Edit**

![Sample](./Image_Growth_m1/image378.png?raw=true)

##### Low Stock Notification 

_Path: **Inventory Management** > **Prediction** section > **Low Stock Notifications**_ 

![Sample](./Image_Growth_m1/image379.png?raw=true)

**Low Stock Notifications** list displays warning messages about the products which are nearly out of stock in warehouses. It shows all notification with information including Sent at, Update Type, Email received, Recipients and Action. Each notification log can show details of all products that have been low stock including Name, SKU, Image, Qty. Notified and Time Notified.

### Inventory Report 

_Path: **Retailer Reports > Manage Reports**_ 

![Sample](./Image_Growth_m1/image380.png?raw=true)

In the _Retailer Reports_ view, you can access to **Sales Reports** and **Inventory Reports**. Click on each report to view the detailed information.

#### Sales Report 
There are 6 types of Sales report: Products, Warehouse, Shipping Method, Payment Method, Order Status and Customers. Click in the report name and do 3 following steps to view detailed information.

![Sample](./Image_Growth_m1/image381.png?raw=true)

(1) Choose a period of time to view report

(2) Choose warehouse(s) to view report, you can choose to see report in one warehouse, some warehouses or all warehouses. 

(3) Click on Show Report button to view report

For example, above is the Sales report by products SKU in last 7 days in 2 warehouses (LA 1354 and LAX1253).

#### Inventory Reports 

There are 5 types of Inventory Reports, click on each report to see detailed information

##### Value of Stock on Hand 

![Sample](./Image_Growth_m1/image382.png?raw=true)

To view Inventory Report by Value of Stock on Hand, select a warehouse from the drop-down list. 

##### Stock Quantity 

![Sample](./Image_Growth_m1/image383.png?raw=true)

To view Inventory Report by Stock Quantity, select a warehouse from the drop-down list.

##### Compare by Warehouse 

![Sample](./Image_Growth_m1/image384.png?raw=true)

To view Inventory Report that show comparison among warehouses, follow the following 3 steps:

(1) Select warehouses to compare

(2) Select type of value to compare, you can choose among Available Qty, Qty to ship, Qty in Warehouse, Inventory Stock, Inventory Value, Retails Value, Potential Profit, Profit Margin

(3) Click on Show Report button to view detailed report

##### Incoming Stock 

![Sample](./Image_Growth_m1/image385.png?raw=true)

To view _Inventory Report_ by Incoming Stock, just click in **Incoming Stock** in the REPORTSUCCESS view and the detailed information will be shown as above.

##### Historical Inventory 

![Sample](./Image_Growth_m1/image386.png?raw=true)

To view _Historical Inventory_ Report, just click in **Historical Inventory** in the REPORTSUCCESS view and the detailed information will be shown as above.

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



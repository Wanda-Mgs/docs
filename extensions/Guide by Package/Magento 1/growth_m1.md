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



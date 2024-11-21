# **Magento 2 KNET Payment Integration**

**Magento 2 KNET Payment Integration** enables businesses to securely accept payments through KNET, a popular payment gateway in the Middle East. This integration is designed to provide customers with a smooth and convenient online payment experience while ensuring secure transactions for store owners. By incorporating KNET into your Magento 2 store, you can offer more payment flexibility to your customers, particularly those in Kuwait and surrounding regions.

## **How It Works**

The Magento 2 KNET Payment Gateway Integration facilitates seamless transactions between the online store and the KNET payment system. After customers select KNET as their payment option, they are redirected to the secure KNET payment page to complete the transaction. The payment status is then sent back to the store, ensuring a smooth checkout experience for both the customer and the store owner. The extension supports a range of features, including payment notifications, automatic status updates, and easy integration with Magento 2\.

## **Key Features**

* **Secure Transactions**: Offers an encrypted payment gateway to ensure safe and secure transactions.  
* **Multiple Currency Support**: Supports multiple currencies, allowing businesses to cater to a wider audience.  
* **Easy Integration**: The integration process is simple, allowing store owners to implement KNET with minimal setup time.  
* **Redirects to KNET Gateway**: Customers are redirected to the KNET payment page for transaction processing, ensuring enhanced security.  
* **Order Status Update**: Automatic updates on order status once the payment is successfully processed.  
* **Customizable Settings**: Configure payment methods, transaction modes, and other settings directly from the Magento admin panel.

## **Secure Payment Gateway**

The Magento 2 KNET Payment Integration uses KNET's secure payment system, ensuring that all transactions are encrypted and processed safely. With KNET, customers can make payments with confidence, knowing their sensitive information is protected.

## **Easy to Configure Payment Settings**

The extension provides simple, straightforward configuration options for Magento store owners. You can easily configure the KNET Payment Gateway from the Magento admin panel to suit your store's needs.

## **Multiple Payment Options**

Magento 2 KNET Payment Integration supports a variety of payment methods for customers, including credit cards, debit cards, and bank transfers, all processed via KNET’s secure gateway.

## **Extension Installation**

To install the Magento 2 KNET Payment Integration extension:

### **Step 1:**

Extract the zip folder and upload our extension to the root of your Magento 2 directory via FTP.

### **Step 2:**

### Login to your SSH and run below commands step by step:

* php bin/magento setup:upgrade  
* For Magento version 2.0.x to 2.1.x \- php bin/magento setup:static-content:deploy  
* For Magento version 2.2.x & above \- php bin/magento setup:static-content:deploy –f  
* php bin/magento cache:flush

## **How to Configure Magento 2 KNET Payment Integration Extension**

To configure the Magento 2 KNET Payment Integration, follow these steps:

### **Step 1: Log in to Magento Admin Panel**

Log in to your Magento 2 admin panel to access the settings for the KNET Payment Integration extension.

### **Step 2: Navigate to Payment Methods**

Go to **Stores \> Configuration \> Sales \> Payment Methods**

Under the **KNET Payment** section, you will find various settings to customize and enable the payment gateway.

### **Step 3: Configure Payment Settings**

Configure the KNET payment gateway by entering your KNET credentials, selecting the payment modes, and adjusting other settings to suit your store's needs.

![Configuration](https://github.com/user-attachments/assets/893fab50-377d-4232-92fc-bc302da066d8)

* **Enabled**: Set to **"YES"** to enable the KNET payment method.  
* **Title**: Enter the title for the payment method as it will appear on the frontend (e.g., "KNET Payment").  
* **Sandbox Mode**: Select **"YES"** to enable sandbox mode for testing purposes or Switch to **"NO"** for live transactions.  
* **Transportal ID**: Enter the **Transportal ID** provided by KNET during registration.  
* **Transportal Password**: Enter the **Transportal Password** shared by KNET.  
* **Terminal Resource Key**: Enter the **Terminal Resource Key** provided during registration.  
* **Payment Language**: Choose the preferred language for the payment gateway (e.g., English or Arabic).  
* **Auto Invoice**: Select **"YES"** to automatically generate invoices for orders paid via KNET.  
* **Payment From Applicable Countries**: Choose **"All Allowed Countries"** or specify selected countries where this payment method will be available.  
* **Sort Order**: Define the order in which the payment method appears on the frontend checkout page.

### **Step 4: Implement KNET Payments on the Frontend**

![KNET Payments in Frontend](https://github.com/user-attachments/assets/aa212904-04a2-4bfd-9b3d-85b0bdd266ec)

During checkout, customers can select the KNET payment option to securely complete their transactions through the gateway.

* **Adding Card Details :** Add card details and click the submit button as shown here.

![Adding Card Details](https://github.com/user-attachments/assets/a7c30667-105c-4718-b970-20593f2ae9d6)

* **Confirm Card Details:** Click the confirm button to confirm the card details.

![Confirm Card Details](https://github.com/user-attachments/assets/a0b823b2-85ca-42b1-9ac7-80a18c3ab9fc)

* **KNET Payments in “My Account” section:** Once the order is placed, the payment method details is shown in the Account dashboard, in “My Orders” tab which includes method title, payment id, transaction status, transaction ID, Authorization number and Tracking ID.

![KNET Payments in “My Account” section](https://github.com/user-attachments/assets/48ae022d-30f8-4442-8224-35a946e8d72d)

* **KNET Payments in Order Email:** After the order is placed, KNET payment and transaction details are sent in order Email to customers.

![KNET Payments in Order Email](https://github.com/user-attachments/assets/072a79ed-42e1-4256-babe-28ec77e6d2e0)

* **KNET Payments in the Backend:** The Order View backend shows the payment information to the admin. It displays the payment method name, payment ID, transaction status, transaction ID, Authorization number and Tracking ID.

![KNET Payments in the Backend](https://github.com/user-attachments/assets/e054f484-c96e-4095-9b8f-738e3a993373)

## Download our [Magento 2 KNET Payment Integration](https://meetanshi.com/magento-2-knet-payment-gateway-integration.html) Extension

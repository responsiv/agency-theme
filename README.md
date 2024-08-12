Agency Theme
==========

![Screenshot](https://raw.githubusercontent.com/responsiv/agency-theme/main/assets/images/theme-preview.png)

Implements a basic theme for taking invoice payments.

# Getting Started with this Theme

Follow these instructions to create your first invoice.

## Configure a Payment Method

First we will need to create a payment method for accepting payments. Currently the payment methods supported are Stripe, PayPal and Offline Payments.

1. From the admin panel, navigate to **Payments → Payment Methods**
2. Click on **Add Payment Method** and select a supported payment gateway
3. Follow the instructions in the form

## Create a Customer

Before we create an invoice, we should create a customer in the admin panel.

1. Navigate to **Users** and select **New User**
2. Fill out the user fields including a password
3. Uncheck the email invitation
4. In the **Address Book** tab, create an address for the user
5. Click **Create** to save the user

## Create an Invoice

Now it's time to create an invoice for our first customer.

1. Navigate to **Payments → Invoices** and select **New Invoice**
2. Select **Create Line Item** and enter a quantity, price and description
3. In the **Customer** tab, select a **User** from the customer created earlier
4. Click **Create** to save the invoice

## Send the Invoice to the Customer

You are ready to send the invoice to the customer, give them the following details:

- Their invoice number (eg: `23`)
- Their Email address

Give them these instructions:

1. Open the website and click **Pay My Invoice**
2. Enter the invoice number and their email address
3. Click **Lookup Invoice** to open the payment page
4. From here they can select a payment method and pay for the invoice

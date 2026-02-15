Lenco Pay WHMCS Payment Gateway

Official Lenco Pay payment gateway module for WHMCS.

This module enables seamless Mobile Money and Card payments directly inside WHMCS using Lenco Pay’s secure API and webhook verification system.

✅ Features

Inline payment integration

Secure webhook verification

Automatic invoice confirmation

Real-time payment processing

Production tested

## 🎥 Watch the Full Installation Guide

[![Watch the video](https://img.youtube.com/vi/e01fG35SqzM/maxresdefault.jpg)](https://youtu.be/e01fG35SqzM)


Supports Mobile Money & Card payments

📌 Requirements

WHMCS 8.0 or higher

PHP 8.0 or higher

Active Lenco Pay merchant account

🚀 Installation Guide

Follow the steps carefully below.

Step 1: Download the Module

Visit the GitHub repository

Click the green Code button

Select Download ZIP

Extract the downloaded file (lencopay-whmcs-module.zip)

Inside the extracted folder, you will find another ZIP file named:

modules.zip


Extract modules.zip.

Step 2: Upload Gateway File

After extracting:

Navigate to:

modules/gateways/


You will find:

lencopay.php


Upload this file to your WHMCS installation:

https://your-domain-name.com/modules/gateways/lencopay.php

Step 3: Upload Callback File

Inside the extracted folder:

modules/gateways/callback/


You will find another:

lencopay.php


Upload this file to:

https://your-domain-name.com/modules/gateways/callback/lencopay.php

Step 4: Upload Debug Log File

Inside the callback folder, upload:

lenco_debug.log


To:

https://your-domain-name.com/modules/gateways/callback/lenco_debug.log


This file is used for debugging webhook responses.

🔑 Lenco Pay API Configuration

Log in to your Lenco Pay dashboard:
https://app.lenco.co/

From the left menu, click:
Lenco Pay → APIs

Click Create New API Key

Copy your:

Public Key

Secret Key

Webhook Setup

In the Lenco dashboard, click the Webhook tab

Set your webhook URL to:

https://your-domain-name.com/modules/gateways/callback/lencopay.php


Click Save

⚙️ Activate Gateway in WHMCS

Log in to your WHMCS Admin Dashboard

Go to:

Configuration → System Settings → Payment Gateways


Locate LencoPay

Click Activate

Enter:

Public Key

Secret Key

Click Save Changes

🎉 Done!

Your WHMCS installation can now accept:

Mobile Money Payments

Card Payments

via Lenco Pay.

🛠 Troubleshooting

Ensure webhook URL is correctly set

Verify API keys are correct

Check lenco_debug.log for webhook logs

👨‍💻 Author

BIG VOICE TECHNOLOGIES
https://www.bigvoice.info

## 🎥 Watch the Full Installation Guide

[![Watch the video](https://img.youtube.com/vi/e01fG35SqzM/maxresdefault.jpg)](https://youtu.be/e01fG35SqzM)

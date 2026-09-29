# YouTube Wale Baba — Website

## Files
- index.html — main website
- style.css — design
- script.js — form/WhatsApp logic
- qr-placeholder.svg — temporary QR placeholder

## Before publishing
Open `script.js` and change:
1. `UPI_ID` → your real UPI ID
2. `WHATSAPP_NUMBER` → your WhatsApp number with country code, e.g. `919876543210`
3. `QR_IMAGE` → your real QR image filename/path

## Important
The included HTML/CSS/JS is a front-end demo. It does NOT actually verify that ₹150 was received. A user can submit a fake screenshot.

For a real paid service, use a payment gateway or a secure backend that verifies the payment server-side before unlocking WhatsApp/contact details.

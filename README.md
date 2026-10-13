# Sparkling Foxx Studio Website

## Included
- Responsive one-page studio website
- Logo and SVG favicon
- Services, 7 years of experience, packages, gallery, enquiry form
- Booking and payment modals
- WhatsApp booking/enquiry handoff
- UPI payment handoff placeholder

## Run locally
Open `index.html` in a modern browser. Internet is needed for Google Fonts and remote gallery images.

## Before publishing
Open `index.html` and edit the `STUDIO_CONFIG` object near the bottom:
- `whatsappNumber`: your WhatsApp number including country code, digits only
- `upiId`: your verified UPI ID
- `upiPayeeName`: the name shown by UPI apps
- `email` and `phoneDisplay`: your real studio contact details

The website's UPI option opens a UPI app; it does not verify payment or save transaction records. For reliable online payment collection (cards/netbanking/UPI with payment confirmation), set up a payment gateway such as Razorpay with a secure backend that creates orders and verifies signatures. Never put a payment gateway secret key in frontend code. Test in sandbox before going live.

Package prices and testimonials are starter placeholders; confirm your actual prices and replace sample testimonials with genuine client reviews.

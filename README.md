# Privacy Policy for Krammute Mail Scanner Extension

**Effective Date:** August 29, 2026

Thank you for choosing the **Krammute Mail Scanner** Chrome Extension ("the Extension"). This Extension is a product of Krammute ("we", "us", or "our"). We believe that your financial data and emails are strictly your business. Our Extension is built entirely around a "Local-First Privacy" architecture. 

This Privacy Policy explains what data this specific Extension interacts with and how it protects your privacy.

## 1. 100% Local Processing (No Cloud Collection)

The Krammute Mail Scanner operates entirely within your local browser environment. 

* **We do not read, collect, store, or transmit your emails.**
* **We do not send your purchase receipts or financial data to any Krammute servers or external databases.**
* The scanning, parsing, and PDF generation processes happen exclusively on your device (client-side) using background workers.

## 2. Information We Interact With

To provide the core functionality of finding and exporting receipts, the Extension requires permission to read the active DOM (Document Object Model) of your open Gmail (`mail.google.com`) tabs. 

* **Email Content:** The Extension temporarily reads the sender, subject, date, and HTML body of your emails solely for the purpose of identifying receipts and converting them into PDF files for your ZIP download. 
* **Volatile Memory:** This data exists only in your browser's temporary volatile memory during the active scan and is immediately discarded once your ZIP file is generated.

## 3. License Key and Authentication

If you upgrade to the Pro version of Krammute Mail Scanner, the Extension will verify your license key.

* We use LemonSqueezy as our Merchant of Record (MoR) to process payments and validate license keys.
* When you enter a license key, the Extension makes a secure API request to LemonSqueezy to verify its validity. We do not store your credit card information, billing address, or personal identity on Krammute servers.

## 4. Third-Party Access

Because we do not collect your personal data, we have no data to sell, rent, or share with third parties, advertisers, or analytics companies.

## 5. Changes to This Privacy Policy

We may update this Privacy Policy from time to time as the Krammute Mail Scanner product evolves. Since we do not collect your email address, we cannot notify you directly of changes. We encourage you to review this page periodically.

## 6. Contact Us

If you have any questions or concerns regarding this Privacy Policy or how your data is handled by our Extension, please contact us at: **support@krammute.com**

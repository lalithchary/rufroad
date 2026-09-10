# Privacy Policy for Rufpage

**Effective Date: September 10, 2026**

Rufpage ("we," "us," or "our") is committed to protecting your privacy. This Privacy Policy explains how we handle your data when you use the Rufpage Chrome extension.

## 1. Data Collection and Usage

Rufpage is designed with a "privacy-first" approach.

- **User-Generated Content:** All notes, code snippets, checklists, and headings you create are stored **locally** on your device using the `chrome.storage` API. We do not have access to this data.
- **Authentication Data:** If you choose to use the Google Drive sync feature, the extension uses Google OAuth2 via the `chrome.identity` API. We do not see or store your Google password or credentials. The access token is stored locally on your device to facilitate communication with your Google Drive account.
- **Payment Information:** Payments for premium features (like Cloud Sync) are handled through third-party merchants (e.g., Gumroad, Lemon Squeezy). We do not collect or store your credit card or financial information.

## 2. Permissions Justification

- **storage**: Required to save your notes and settings locally on your computer.
- **unlimitedStorage**: Allows you to save a large number of notes without hitting browser-imposed limits.
- **clipboardWrite**: Allows you to copy code snippets to your clipboard for use in other apps.
- **identity**: Used to securely connect to your Google account for optional cloud synchronization.

## 3. Third-Party Services

- **Google Drive API**: If enabled, the extension interacts directly with your Google Drive account to create and update a backup file in your hidden "AppData" folder. This data is private to you and is not shared with us or any third parties.

## 4. Data Sharing and Disclosure

We **do not** sell, trade, or transfer your data to outside parties. Your data remains entirely within your control—either locally on your device or within your private Google account.

## 5. Security

We use industry-standard browser APIs to ensure that your data is handled securely. Because we do not use central servers to store your notes, your data remains as secure as your local machine and your Google account.

## 6. Your Rights

You can delete all your data at any time by:

1. Clearing the extension data in Chrome settings.
2. Deleting the `rufpage_backup.json` file from your Google Drive (if sync was enabled).
3. Uninstalling the extension.

## 7. Changes to This Policy

We may update this Privacy Policy from time to time. Any changes will be reflected in the extension's update notes and on our official listing.

## 8. Contact

If you have questions about this policy, please contact us through the support link on our Chrome Web Store listing.

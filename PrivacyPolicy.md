# Privacy Policy for JP Zip Autofill Assistant
Last Updated: 2026-04

## Overview
JP Zip Autofill Assistant is a Chrome extension designed to improve the efficiency of entering Japanese addresses on web forms.

This extension automatically fills address fields based on a 7-digit postal code and provides a search tool for postal codes and addresses.

We respect user privacy and are committed to not collecting or misusing user data.

---

## Data Collection
This extension does **not collect, store, or transmit any personally identifiable information (PII)**.

The extension processes the following data locally within the browser:
- Postal codes entered by the user
- Address form field values (for autofill purposes)
- Search queries entered in the popup

This data is used only for providing the extension's functionality and is not sent to any external servers except for required API requests.

---

## External API Usage
To perform address lookup, the extension sends postal codes or address queries to publicly available APIs:

- https://zipcloud.ibsnet.co.jp (postal code → address)
- https://postcode.teraren.com (address → postal code)

These requests are strictly limited to the input data required for lookup.

No additional user data is transmitted.

---

## Data Storage
The extension uses Chrome's storage API (`chrome.storage.sync`) to store:

- User settings
- Site-specific templates
- Custom address dictionary entries
- Search history
- Favorite addresses

All stored data:
- Remains on the user's device or Chrome account
- Is not transmitted to external servers
- Can be deleted by the user at any time

---

## Permissions Usage
This extension requires the following permissions:

### storage
Used to store user preferences, templates, and history locally.

### tabs
Used to interact with the currently active tab when applying autofill or scanning page structure.

### scripting
Used to inject scripts into web pages to detect postal code input fields and perform autofill.

### host permissions
Used to:
- Access web pages where address forms exist
- Call external APIs required for address lookup

---

## Data Sharing
This extension:
- Does **not sell**
- Does **not share**
- Does **not transfer**

any user data to third parties.

---

## User Control
Users can:

- Enable or disable autofill
- Manage templates and custom dictionary entries
- Clear search history and stored data
- Uninstall the extension at any time to remove all stored data

---

## Security
All processing is performed locally within the browser.

No background data collection or tracking mechanisms are implemented.

---

## Changes to This Policy
This Privacy Policy may be updated if the functionality of the extension changes.

Users will be informed of significant changes through the Chrome Web Store listing.

---

## Contact
For questions or support, please contact:
discord.recorder.labs@gmail.com

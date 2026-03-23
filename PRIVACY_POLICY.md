# Privacy Policy for Gemini Width Adjuster

Last updated: March 23, 2026

## 1. Overview and Scope
This Privacy Policy describes the practices regarding data collection and usage for the Chrome extension "**Gemini Width Adjuster**" (Item ID: lbednbonndcjdlcbnmdeicppamfjhck).

We adhere to the strict interpretation of "Privacy by Design." This extension is a localized UI enhancement utility with a zero-data footprint.

## 2. Information Collection and Non-Collection
We are proud to state that Gemini Width Adjuster **does not collect, store, or transmit any personally identifiable information, browsing history, or chat data.**

A full analysis of our source code confirms:

* **Chat Content:** We do not read, listen to, or process user queries or AI responses.
* **Personal Data:** We have no access to names, email addresses, or identification numbers.
* **Third-Party Analytics:** No analytics tracking (e.g., Google Analytics) is implemented.

## 3. Permissions Usage (Data Stewardship)
Our code requests minimal permissions solely to fulfill its core functionality as a localized UI tool.

* **Storage Permission:** Used exclusively to save user-defined numerical values (e.g., width=1200) and toggles (e.g., codeWrap=true) locally on the user's browser. No settings are synced to external servers.
* **Host Permissions (`*://gemini.google.com/*`):** Used solely to identify the official Gemini domain and to inject CSS `<style>` tags to modify the page layout. No data is read from the page DOM.

## 4. Local Data Processing (JS Injection)
As verified by our `content.js` source code, all data processing is localized within the user's browser via pure CSS injection. No communication with external APIs occurs.

## 5. Third-Party Sharing and Selling
We do not sell, trade, or transfer any user data to third parties, outside of the approved use cases (which currently is non-existent as we handle no data).

## 6. Contact
If you have any questions, please contact the developer via the official Chrome Web Store channel.

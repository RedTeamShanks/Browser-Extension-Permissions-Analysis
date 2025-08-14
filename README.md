## 🔍 Browser Extension Permissions Analysis
### 📌 Overview

This project documents and analyzes the permissions requested by various browser extensions commonly used in cybersecurity and web application testing. Understanding extension permissions is crucial for assessing potential security risks, privacy implications, and the overall trustworthiness of browser add-ons.

### 🛠️ Tools & Extensions Analyzed

The following extensions were inspected by reviewing their manifest.json files:

| Extension Name     | Permissions                                                                                                       |
| ------------------ | ----------------------------------------------------------------------------------------------------------------- |
| **Cookies Editor** | `cookies`, `tabs`, `storage`                                                                                      |
| **Header Editor**  | `tabs`, `webRequest`, `webRequestBlocking`, `contextMenus`, `storage`, `downloads`, `*://*/*`, `unlimitedStorage` |
| **Hunter**         | `tabs`, `storage`, `contextMenus`                                                                                 |
| **Wappalyzer**     | `cookies`, `storage`, `tabs`, `webRequest`, `http://*/*`, `https://*/*`                                           |
| **HackTools**      | *No permissions specified*                                                                                        |

### 📂 Methodology

Locate Extension Files
- Downloaded or extracted the extension package (e.g., .zip or .xpi file).
- Navigated to the extension’s root directory.
- Inspect manifest.json
   Opened the manifest.json file.
   Identified the permissions field for each extension.
- Document Findings
     Compiled permissions into a comparative table for quick review.

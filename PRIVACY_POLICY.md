# Privacy Policy — Y-DM All Download Manager + Ad Blocker

**Last Updated:** November 23, 2026  
**Developer:** Y-ARDIANSYAH

## 1. Overview
**Y-DM All Download Manager + Ad Blocker** ("the Extension") is a browser companion extension designed to integrate your web browser with the local Y-DM desktop application and filter intrusive pop-ups and advertisements. Your privacy is our top priority.

## 2. Data Collection & Sharing
We do **not** collect, store, sell, or transmit any personal data, browsing history, credentials, or usage analytics to any external server or third party.

## 3. Local-Only Communication
All download metadata (such as the target file URL, filename, referrer, and session cookies required for authenticated file downloads) is sent **exclusively** to the user's own local Y-DM desktop application running on `http://127.0.0.1:19455` (localhost). No data ever leaves your device.

## 4. Permissions Usage
The Extension requests only the permissions strictly necessary for its core functionality:
- **`downloads`**: To intercept browser downloads and forward them to the local Y-DM desktop application when active.
- **`tabs`**: To detect active tab URLs as referrers, display the blocked ad badge count per tab, and automatically close intrusive pop-under ad tabs.
- **`cookies`**: To pass local session cookies exclusively to `127.0.0.1:19455` so authenticated file downloads can succeed in the desktop app.
- **`storage`**: To save your extension preferences locally in your browser.
- **`contextMenus`**: To provide a right-click "Fast Download with Y-DM" menu option.
- **`declarativeNetRequest`**: To block known ad and tracker domains locally.
- **`alarms`**: To periodically sync ad-filter preferences with the local Y-DM desktop application.
- **`host_permissions` (`<all_urls>`, `http://127.0.0.1/*`)**: To detect downloadable media/files on web pages, apply cosmetic ad filtering, and communicate with the local desktop app.

## 5. Contact
If you have any questions regarding this Privacy Policy, please contact the developer via GitHub:  
https://github.com/Yusuf-Ardiansyah/ydm-ota
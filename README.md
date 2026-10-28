---

# 🛡️ Privacy Policy for Dear Days

**Last Updated:** October 28, 2026  
**Effective Date:** October 28, 2026  
**Developer:** Shah Zaib ([GitHub Profile](https://github.com/Shah-Zaib219))

Welcome to **Dear Days**. Your privacy is our highest priority. This Privacy Policy explains our practices regarding your data when you use the Dear Days mobile application.

---

### 1. 🔒 100% Offline & Zero Data Collection
- **No Account Required:** You do not need to register, log in, or provide an email address, phone number, or name to use the app.
- **Zero Cloud Transmission:** Dear Days is built with an offline-first architecture. All journal entries, diary thoughts, calendar events, audio tracks, and reminders stay **strictly on your physical device**.
- **No Remote Servers:** We do not own, operate, or connect to any cloud servers, databases, or external APIs to collect or process your personal memories.
- **No Analytics & No Trackers:** Dear Days contains **zero advertising SDKs, zero user tracking scripts, and zero third-party analytics tools** (no Firebase Analytics, no Facebook SDK, no Google AdMob).

---

### 2. 🔐 Device Permissions & How They Are Used
Dear Days only requests the minimum necessary permissions required to deliver core functionality locally on your phone:

| Permission | Purpose |
| :--- | :--- |
| **Media / Photos / Storage** | Required solely to allow you to select, attach, and display photos or import local background music from your device into your journal entries. Your files never leave your device. |
| **Notifications (`POST_NOTIFICATIONS`)** | Used exclusively to trigger scheduled reminder alerts and to display foreground playback controls for your background music player. |
| **Exact Alarm (`SCHEDULE_EXACT_ALARM`)** | Used to trigger smart reminder notifications at the precise date and time you set. |
| **Foreground Service (`FOREGROUND_SERVICE_MEDIA_PLAYBACK`)** | Used to keep your selected local music playing smoothly when the app is minimized or running in the background. |

---

### 3. 🛡️ Data Storage & Security
- **Local Storage:** All journal posts, reminders, and user settings are stored in a private local SQLite database on your device.
- **Hardware-Encrypted Security:** When PIN protection is enabled, your PIN code is stored using the device's hardware-backed secure storage (Android Keystore via `flutter_secure_storage`), protecting it from unauthorized access.
- **Data Ownership:** You maintain 100% ownership and control of your data at all times.

---

### 4. 🗑️ Data Retention & Deletion
Because all data resides exclusively on your local device:
- **Instant Deletion:** Deleting an entry, photo, or reminder inside the app removes it permanently from your local database immediately.
- **Complete Eradication:** Uninstalling the Dear Days application automatically and permanently erases all associated data, logs, and database records from your device.

---

### 5. 👶 Children’s Privacy (COPPA)
Dear Days does not collect, store, or transmit personal information from anyone, including children under the age of 13. It is safe for users of all ages.

---

### 6. 🔄 Changes to This Privacy Policy
We may update our Privacy Policy from time to time. Any changes will be published in this repository with an updated revision date.

---

### 7. 📬 Contact Us
If you have any questions, suggestions, or concerns regarding this Privacy Policy, please open an issue in this repository or contact the developer:

- **Developer:** Shah Zaib
- **GitHub Repository:** [https://github.com/Shah-Zaib219/dear-days](https://github.com/Shah-Zaib219/dear-days)
- **Issues & Inquiries:** [Open an Issue](https://github.com/Shah-Zaib219/dear-days/issues)

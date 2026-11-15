# Privacy Policy, Terms of Use & Customer Support

**Last Updated:** November 15, 2026  
**Application:** Scrum Master: PSM Exam Prep (`com.baka3k.learn.sm` — iOS & Android)  
**Developer:** Baka Team

Welcome to **Scrum Master: PSM Exam Prep**. This document outlines our data privacy practices, terms of use (EULA), and official support channels.

---

## 1. Privacy Policy

**Scrum Master is a 100% offline-first educational application.**  
We are firmly committed to user privacy: **we do not collect, store, sell, or transmit any personal user data.**

### 1.1 Information We Do NOT Collect
- **No Personal Identifiers:** We do not collect names, email addresses, phone numbers, contacts, or location data.
- **No Account Required:** You do not need to register, create an account, or log in to use the App.
- **Zero Third-Party Ads or Trackers:** The App contains no advertising SDKs, analytics SDKs, tracking pixels, or cross-app identifiers.
- **No Biometric or Sensor Data:** The App does not access device location, microphones, cameras, or contacts.
- **Offline by Design:** The App does not require internet access or request network permissions to function.

### 1.2 On-Device Data Storage & Security
All practice exam attempts, study progress, bookmarks, spaced-repetition (SM-2) statistics, and preferences are stored **strictly on your local device** inside an **AES-256 encrypted SQLCipher / SQLite database**.
- On Android, automatic cloud backup (`allowBackup`) is disabled to keep your local study database strictly on your device.
- Deleting the application removes your local study database and preferences from your device.
- During an active Practice Exam session, screen-capture privacy protection (`FLAG_SECURE` on Android and a privacy blur shield on iOS) is enabled to simulate authentic exam conditions and protect app-switcher previews.

### 1.3 iOS Privacy Manifest & Platform Processing
- **Apple Privacy Manifest (`PrivacyInfo.xcprivacy`):** The App declares zero tracking (`NSPrivacyTracking = false`) and zero collected data types. It accesses only standard system APIs required for local operation: `UserDefaults` (`CA92.1`) for local preferences and `FileTimestamp` (`C617.1`) for local database file management.
- **Purchases & Diagnostics:** Purchases are processed securely by Apple (App Store) or Google (Google Play). We do not collect, view, or retain your payment details. Anonymous, aggregated diagnostic and crash reports may be provided by Apple App Store / TestFlight or Google Play Console if enabled in your device settings.

### 1.4 Children’s Privacy
This App is an educational study tool designed for professionals preparing for Scrum Master certification exams. We do not knowingly collect any personal data from children under 13.

---

## 2. Terms of Use (EULA)

### 2.1 One-Time Paid License
Purchasing **Scrum Master: PSM Exam Prep** once on the Google Play Store or Apple App Store grants you a non-exclusive, non-transferable, personal license to use 100% of the application, all 664+ practice questions, and all 7 exam modes permanently on your authorized devices—with **zero recurring subscriptions, zero in-app purchases, and zero advertisements**.
- **Restoring Purchases:** Reinstall using the same Apple ID or Google account to restore access at no extra cost.
- **Refunds:** Refund requests are governed by Apple Media Services Terms and Conditions ([reportaproblem.apple.com](https://reportaproblem.apple.com)) or [Google Play Help](https://support.google.com/googleplay/answer/2479637).

### 2.2 Educational Purpose & Disclaimer
Scrum Master is an independent study and exam simulator application. All mock tests and rationales are for personal study purposes only. We do not guarantee passing scores on any official certification examination.

### 2.3 Trademark & Non-Affiliation Notice
Scrum Master is an independent study and exam simulator application. It is **not affiliated with, endorsed by, or sponsored by Scrum.org**.  
**PSM™**, **Professional Scrum Master™**, and **Scrum Guide™** are trademarks of **Scrum.org**.

### 2.4 Intellectual Property & Anti-Tampering
All question banks, explanations, flashcards, software code, encrypted assets, and UI designs are the intellectual property of Baka Team. Reverse engineering, decompiling, extracting encrypted database assets, or redistributing modified APKs/IPAs is strictly prohibited.

---

## 3. Customer Support & Contact

If you have questions, feedback, need technical support, or want to report an issue with a question:

- **Developer Email Support:** [baka3k@gmail.com](mailto:baka3k@gmail.com)  
  *Response time: Within 24–48 business hours*
- **GitHub Issue Tracker:** [https://github.com/baka3k/privacy-policy/issues](https://github.com/baka3k/privacy-policy/issues)
- **Official Policy URL:** [https://baka3k.github.io/privacy-policy/scrum-master.html](https://baka3k.github.io/privacy-policy/scrum-master.html)
- **Alternate Policy URL:** [https://baka3k.github.io/privacy-policy/psm1-exam-prep.html](https://baka3k.github.io/privacy-policy/psm1-exam-prep.html)

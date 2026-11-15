# Privacy Policy, Terms of Use & Customer Support

**Last Updated:** November 15, 2026  
**Application:** AWS SAA-C03 Exam Prep & Quiz (`com.baka3k.learn.aws` on Android / `com.baka3k.learn.aws.associate` on iOS)  
**Developer:** Baka Team

Welcome to **AWS SAA-C03 Exam Prep & Quiz** (also listed as **AWS SAA-C03 Practice** / **SAA Exam Prep**). This document outlines our data privacy practices, terms of use (EULA), and official support channels.

---

## 1. Privacy Policy

**AWS SAA-C03 Exam Prep & Quiz is an offline-first educational application.**  
We are committed to protecting your privacy: **we do not collect, store, sell, or share any personally identifiable information (PII).**

### 1.1 Information We Do NOT Collect
- **No Personal Identifiers:** We do not ask for or collect names, email addresses, physical addresses, phone numbers, contacts, or location data.
- **No Account Required:** You do not need to register, create an account, or log in to use the App.
- **Zero Third-Party Ads or Ad Trackers:** The App contains no advertising SDKs, tracking pixels, or cross-app behavioral tracking identifiers.
- **No Biometric or Sensor Data:** The App does not access device GPS, microphones, cameras, or contact lists.
- **No Payment Details Stored:** Purchases are processed directly by Google Play or Apple App Store; we never receive or store your credit card or billing information.

### 1.2 On-Device Data Storage & Security
All of your quiz attempts, mock exam scores, bookmarks, personal study notes, and preferences are stored **strictly on your local device** inside an **encrypted SQLCipher / SQLite database** and local app preferences (`SharedPreferences` / `UserDefaults`).
- **Offline Study:** All 300+ scenario questions, explanations, flashcards, and 8 exam modes are bundled locally and work 100% offline.
- **Android Backup Disabled:** On Android, automatic OS cloud backup (`android:allowBackup="false"`) is disabled to keep your local study database strictly on your device.
- **Data Deletion:** Because no user account or personal data is stored on our servers, uninstalling the App or clearing App storage from your device settings permanently removes all local study data.

### 1.3 Analytics, App Integrity & Platform Processing
To ensure technical stability, prevent tampering, and improve the learning experience, the App uses minimal, privacy-preserving platform services:
- **Firebase Analytics:** Collects anonymous, aggregated product interaction and usage statistics (not linked to your personal identity and not used for cross-app tracking).
- **Firebase App Check:** Uses platform attestation (**Google Play Integrity** on Android and **Apple DeviceCheck** on iOS) solely for app functionality, license verification, and fraud prevention.
- **Encrypted in Transit:** All network communication with store verification or Firebase services is encrypted via HTTPS/TLS.
- **Store Purchases & Crash Diagnostics:** One-time app purchases are processed securely by **Google Play Billing** or **Apple App Store**. Anonymous, aggregated crash reports may be provided by Google Play Console or Apple App Store / TestFlight if enabled in your device settings.

### 1.4 iOS Privacy Manifest (`PrivacyInfo.xcprivacy`)
In accordance with Apple App Store requirements:
- **Tracking:** Declared as `NSPrivacyTracking = false` (zero cross-app tracking).
- **Required Reason API:** Declares `NSPrivacyAccessedAPICategoryUserDefaults` (`CA92.1`) strictly for local app preferences.
- **App Functionality Data:** Declares `Purchase History` (`Linked = false`, `Tracking = false`, Purpose: `App Functionality`) for store purchase/license verification.

### 1.5 Children’s Privacy
This App is an educational study tool designed for learners and professionals preparing for AWS certification exams. We do not knowingly collect any personal data from children under the age of 13.

### 1.6 Links to External Resources
The App or its support pages may reference official AWS documentation or external educational resources. We are not responsible for the content or privacy practices of external websites.

---

## 2. Terms of Use (EULA)

### 2.1 One-Time Paid License
Purchasing **AWS SAA-C03 Exam Prep & Quiz** once on the Google Play Store or Apple App Store grants you a non-exclusive, non-transferable, personal license to use 100% of the application, all 300+ practice questions, all 8 exam modes, 2-sided flashcards, and Knowledge & Mastery Advisor permanently on your authorized devices—with **zero recurring subscriptions, zero in-app purchases, and zero advertisements**.
- **Restoring Purchases:** Reinstall using the same Google account or Apple ID to restore access at no extra cost.
- **Refunds:** Refund requests are governed by [Google Play Help](https://support.google.com/googleplay/answer/2479637) or Apple Media Services Terms and Conditions ([reportaproblem.apple.com](https://reportaproblem.apple.com)).

### 2.2 Educational Purpose & Disclaimer
AWS SAA-C03 Exam Prep & Quiz is an independent study and exam simulator application. All mock tests, scaled scores, and explanations are for personal study and self-assessment purposes only. We do not guarantee passing scores on any official certification examination.

### 2.3 Trademark & Non-Affiliation Notice
AWS SAA-C03 Exam Prep & Quiz is an independent educational product and is **not affiliated with, endorsed by, or sponsored by Amazon Web Services, Inc. (AWS)**.  
**AWS®**, **Amazon Web Services®**, and **AWS Certified Solutions Architect – Associate (SAA-C03)** are trademarks or registered trademarks of **Amazon.com, Inc.** or its affiliates.

### 2.4 Intellectual Property & Anti-Tampering
All question banks, explanations, flashcards, software code, encrypted assets, and UI designs are the intellectual property of Baka Team. Reverse engineering, decompiling, extracting encrypted database assets, or redistributing modified APKs/IPAs is strictly prohibited.

---

## 3. Customer Support & Contact

If you have questions about this Privacy Policy, your purchase, or want to report an issue with a question:

- **Developer Email Support:** [baka3k@gmail.com](mailto:baka3k@gmail.com)  
  *Response time: Within 24–48 business hours*
- **GitHub Issue Tracker:** [https://github.com/baka3k/privacy-policy/issues](https://github.com/baka3k/privacy-policy/issues)
- **Official Policy URL:** [https://baka3k.github.io/privacy-policy/aws-sa-associated.html](https://baka3k.github.io/privacy-policy/aws-sa-associated.html)

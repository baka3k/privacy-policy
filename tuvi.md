# Privacy Policy & Terms of Service

**Effective Date:** November 1, 2026  
**Application:** Huyền Cơ Mệnh Lý (Mystic Metaphysics – Tinix Tu Vi & BaZi)  
**Package Name:** `com.tinix.tuvi.tinix_mobile`  
**Developer:** Baka Team  
**Contact:** [baka3k@gmail.com](mailto:baka3k@gmail.com)

---

Welcome to **Huyền Cơ Mệnh Lý** (also known as *Mystic Metaphysics*, *Tinix Tử Vi & Bát Tự*). We value your trust and are deeply committed to protecting your personal privacy. This document outlines how our application operates, how data is processed, and the terms governing your use of our services and in-app subscriptions.

---

## Part 1: Privacy Policy

### 1.1 Core Principles: Guest-First & Privacy by Design
Huyền Cơ Mệnh Lý is engineered from the ground up with a **guest-first, local-first, and privacy-preserving architecture**:
* **No Mandatory Account Registration:** You are not required to create an account, log in, or provide personal contact details (such as your phone number, email address, or social media accounts) to explore charts and utilize features.
* **On-Device Data Storage:** Your astrological profiles (Hồ sơ lá số), saved birth charts, personalized notes, and reading history are stored locally on your device via encrypted on-device storage. We do not maintain a central database containing your personal profiles or private charts.

---

### 1.2 Information We Process

#### A. Astrological Input Data & Readings (Ephemeral Processing)
To generate your astrological charts (Tử Vi Đẩu Số, Bát Tự Tứ Trụ, Kinh Dịch Quẻ Mệnh, Chọn Ngày Lành) and personalized interpretations:
* **Input Parameters:** You enter birth information (solar/lunar birth date, birth hour, gender, and optional profile name) and your questions for consultation.
* **Secure Transmission:** When you request an in-depth chart reading or consultation, these parameters are transmitted over a secure TLS-encrypted connection (HTTPS) to our computational engine and language processing service.
* **Ephemeral Real-Time Processing:** This data is processed strictly in real time to calculate celestial positions, stem-branch interactions (Can Chi), palace distributions (Cung Mệnh), and generate the textual interpretation.
* **No Profiling or Selling:** Your birth information and queries are never used to build advertising profiles, are never sold to data brokers, and are never shared with unauthorized third parties.

#### B. Subscriptions & In-App Purchases
Huyền Cơ Mệnh Lý offers optional subscription tiers (*Basic* and *Pro*) to provide extended monthly consultation quotas:
* **Payment Processing:** All payment processing, transactions, and billing information (credit cards, banking instruments, app store balances) are handled exclusively and securely by **Google Play Billing** (Google LLC) on Android and **Apple In-App Purchase** (Apple Inc.) on iOS.
* **No Financial Data Stored by Us:** The developer never receives, accesses, or stores your credit card numbers, billing addresses, or bank account details.
* **Cryptographic Verification:** When a subscription or purchase is made, the platform issues an anonymous digital transaction token (`purchaseToken` or receipt data). Our backend validates this token directly with the store developer APIs solely to confirm entitlement status and assign your monthly consultation quota.

#### C. Anonymous Technical Identifiers & Rate Limiting
To ensure fair server resource distribution, enforce monthly plan limits, and protect backend infrastructure against automated abuse:
* The application generates an anonymous, random installation identifier (`X-Install-Id`) stored on your device.
* This identifier is strictly technical, contains no personally identifiable information (PII), and cannot be used to identify your real-world identity.

#### D. Device Permissions
The application requests only minimal, necessary system permissions:
* **Internet Access (`android.permission.INTERNET`):** Required to connect to our secure server for astronomical solar-lunar calendar synchronization, generating in-depth interpretations, and verifying subscription receipts.
* **Storage / Photo Library Access (`READ_MEDIA_IMAGES` / `WRITE_EXTERNAL_STORAGE`):** Requested only when you explicitly select the "Export Chart as Image" (Xuất ảnh lá số) or "Export PDF" (Xuất file PDF) feature to save or share your chart graphic. The application does not scan, inspect, or access your other personal photos or files.

#### E. Diagnostics & Performance
Anonymous, aggregated crash reports and performance metrics (such as device model, operating system version, and stack traces) may be collected through standard store developer consoles to help us resolve crashes and improve application performance.

---

### 1.3 Third-Party Services
We rely on industry-standard, trusted third-party providers for platform distribution and infrastructure:
* **Google Play Services & Google Play Billing** (Google LLC) — For Android distribution, update delivery, and secure subscription checkout.
* **Apple App Store & In-App Purchase** (Apple Inc.) — For iOS distribution and subscription management.
* **Cloudflare** (Cloudflare, Inc.) & Hosting Infrastructure — For secure API gateway routing, TLS encryption, and anti-DDoS mitigation.
* **Natural Language & Computational Interpretation Engine** — Cloud-based automated engine for generating context-aware interpretations and answers based on classical Eastern metaphysics traditions.

---

### 1.4 Data Retention & Deletion
* **Local Data:** Because all saved chart profiles and reading history are stored on your device, you can delete your data at any moment by clearing the application storage in device settings or by uninstalling the app.
* **Transaction Records:** Anonymous transaction validation records are retained solely for the period required to maintain active subscription validation and comply with legal, tax, and accounting standards.
* **Assistance & Requests:** You may contact us at [baka3k@gmail.com](mailto:baka3k@gmail.com) at any time with any questions regarding data handling or your subscription status.

---

### 1.5 Children’s Privacy
Huyền Cơ Mệnh Lý is not intended for or directed toward children under 13 years of age (or under 16 in the European Economic Area). We do not knowingly collect personal information from children. If we discover that any information has been inadvertently collected from a child under the relevant age, we will immediately take steps to remove it.

---

## Part 2: Terms of Service & Subscription Conditions

### 2.1 Cultural Heritage & Entertainment Disclaimer
* **For Cultural Appreciation, Reflection & Entertainment:** Eastern Metaphysics (Tử Vi Đẩu Số, Bát Tự Tứ Trụ, Kinh Dịch, Phong Thủy) is an ancient cultural, philosophical, and astrological tradition. All calculations, chart layouts, interpretations, and consultations provided in this app are intended strictly for cultural reflection, personal insight, philosophical exploration, and entertainment purposes.
* **Not Professional Advice:** Interpretations and consultations **do not** constitute medical, psychological, psychiatric, legal, tax, investment, or financial advice. You should never make important life, health, legal, or financial decisions based upon astrological readings.
* **No Predictive Guarantees:** We make no claims, promises, or warranties regarding the deterministic accuracy, predictive efficacy, or future outcomes of any chart reading or advice.

---

### 2.2 Subscriptions, Quotas, and Cancellation

#### A. Subscription Tiers & Benefits

| Subscription Tier | Monthly Consultation Limit | Price (USD) | Key Features |
| :--- | :--- | :--- | :--- |
| **Free Tier** | 15 consultations / month | **Free ($0.00)** | Unlimited Tử Vi & Bát Tự chart plotting, I Ching divination, Auspicious date selection, local profile management. |
| **Basic Plan** | 50 consultations / month | **$5.99 / month\*** | Expanded consultation quota, in-depth lifetime analysis, marriage compatibility (Hợp Hồn), Hexagram inquiries. |
| **Pro Plan (Best Value)** | 300 consultations / month | **$11.99 / month\*** | High-volume consultation capacity, priority server processing, high-resolution PDF and image export. |

*\*Prices in local currencies (e.g., VND, EUR, JPY) are set and converted by Google Play and Apple App Store according to regional pricing matrices and local taxes.*

#### B. Auto-Renewal Terms
* Subscriptions are billed on a recurring monthly cycle through your Google Play or Apple App Store account.
* **Automatic Renewal:** Your subscription automatically renews at the end of each billing period unless you cancel it at least 24 hours prior to the renewal date.
* **Account Charges:** Your account will be charged for renewal within 24 hours prior to the end of the current billing cycle at the applicable plan rate.

#### C. How to Cancel or Manage Subscriptions
You may pause, change, or cancel your subscription at any time without penalty.

**On Android (Google Play):**
1. Open the **Google Play Store** app on your device.
2. Tap your profile picture at the top right > select **Payments & subscriptions** > **Subscriptions**.
3. Select **Huyền Cơ Mệnh Lý** and tap **Cancel subscription**.
4. You can also manage your subscriptions via the web at: [https://play.google.com/store/account/subscriptions](https://play.google.com/store/account/subscriptions).

**On iOS (Apple App Store):**
1. Open the **Settings** app on your iPhone or iPad.
2. Tap your **Name / Apple ID** at the top > select **Subscriptions**.
3. Select **Huyền Cơ Mệnh Lý** and tap **Cancel Subscription**.

*Note: After cancellation, you will continue to have access to your paid subscription benefits until the end of your current paid billing period.*

#### D. Restoring Purchases & Refunds
* **Restore Purchases:** If you reinstall the app or change devices, simply tap the **"Khôi phục gói mua" (Restore Purchases)** button in the Subscription screen or Settings to immediately re-sync your active tier.
* **Refunds:** All refund inquiries are governed by the refund policies of Google Play or Apple App Store. Refund requests must be submitted directly through your Google Play or Apple account order history.

---

### 2.3 User Conduct & Intellectual Property
* You agree not to reverse-engineer, decompile, scrape, or perform denial-of-service attacks against the application or its underlying backend APIs.
* All visual designs, custom chart layouts, star diagrams, typography, textual analyses, and software code are the intellectual property of Baka Team and are protected under international copyright and intellectual property laws.

---

### 2.4 Changes to This Policy
We may periodically update this Privacy Policy and Terms of Service to reflect enhancements to features, infrastructure, or legal obligations. When changes are made, the revised policy will be posted on this page with an updated "Effective Date".

---

### 2.5 Contact Us
If you have any questions, feedback, or suggestions regarding this Privacy Policy or the terms of the service, please reach out to us:

* **Developer:** Baka Team
* **Email:** [baka3k@gmail.com](mailto:baka3k@gmail.com)

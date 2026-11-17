# Privacy Policy & Terms of Service

**Effective Date:** November 17, 2026  
**Application:** Mystic Tarot (Huyền Cơ Tarot)  
**Developer:** Baka Team  
**Contact:** [baka3k@gmail.com](mailto:baka3k@gmail.com)  
**Support Page:** [https://baka3k.github.io/privacy-policy/tarot-support](https://baka3k.github.io/privacy-policy/tarot-support)

---

Welcome to **Mystic Tarot** (also known as *Huyền Cơ Tarot*). We respect your privacy and are committed to protecting your personal data. This document outlines how our application operates across iOS and Android, how data is handled, and the terms governing the use of our services and in-app subscriptions.

---

## Part 1: Privacy Policy

### 1.1 Core Principles: Guest-First & Privacy by Design
Mystic Tarot is built with a **guest-first, privacy-by-design architecture**:
* **No Account Required:** You do not need to register, create an account, or provide personal details such as your full name, email address, phone number, or social media profile to use the app.
* **On-Device Data Storage:** All your reading history, drawn Tarot cards, personal reflections, and questions are stored locally on your device. We do not store or synchronize your private readings on any central server database.

---

### 1.2 Information We Process

#### A. Questions and Tarot Interpretations (Ephemeral Processing)
When you submit a question for an AI-assisted Tarot interpretation, your question and selected card identifiers are transmitted over an encrypted TLS connection (HTTPS) to our proxy service.
* This data is used **solely to generate the reading in real time**.
* Questions and readings are **ephemeral** and are not permanently stored on our servers, used to build advertising profiles, sold to data brokers, or shared with unauthorized third parties.

#### B. Subscriptions & In-App Purchases (Apple App Store & Google Play)
Mystic Tarot offers optional auto-renewable subscription tiers (*Tarot Basic* and *Tarot Pro*) to unlock higher monthly reading quotas:
* **Payment Processing:** All financial transactions, billing details, and payment methods are handled exclusively and securely by **Apple In-App Purchase** (Apple Inc.) on iOS and **Google Play Billing** (Google LLC) on Android.
* **Store Receipt & Purchase Token Verification:** When you make a purchase, the store provides an anonymous transaction receipt or purchase token (`purchaseToken`). Our server validates this token directly with Apple App Store or Google Play Developer APIs solely to confirm your subscription entitlement and assign your reading quota.
* **No Financial Data Collection:** We never receive, store, or have access to your credit card numbers, billing addresses, or bank account information.

#### C. Anonymous Device Identifiers & Rate Limiting
To enforce reading quotas (including the 5 lifetime free trial readings) and protect our backend against automated abuse:
* The app derives an anonymous, one-way **SHA-256 cryptographic hash** of `ANDROID_ID` on Android or a random installation UUID on iOS.
* This identifier is used exclusively to enforce reading quotas and verify subscription entitlements. It is **not** used for advertising or cross-app tracking, is **never** shared with third parties, and cannot be reversed to reveal your real-world identity.

#### D. Diagnostics & Crash Reporting
Apple App Store and Google Play Services may collect anonymous, aggregated crash logs, device hardware models, OS versions, and performance diagnostics to help us identify bugs and maintain stability.

---

### 1.3 Third-Party Services
We partner with trusted service providers to deliver the application:
* **Apple App Store & In-App Purchase** (Apple Inc.) — For iOS distribution and secure subscription billing.
* **Google Play Services & Google Play Billing** (Google LLC) — For Android distribution, updates, and secure subscription billing.
* **Cloudflare Workers** (Cloudflare, Inc.) — For secure API gateway routing, TLS encryption, and anti-DDoS protection.
* **AI Interpretation Engine** — Cloud-based language processing service used solely to generate real-time interpretive text based on traditional Tarot symbolism.

Each third-party service processes information in accordance with its respective privacy policy.

---

### 1.4 Data Retention & Deletion
* **Local Data:** Since your reading history is stored strictly on your device, you can delete your reading history inside the app at any time, or permanently remove all local data by clearing app storage or uninstalling the app.
* **Server Data:** Anonymous transaction validation records are retained only as required to maintain subscription validity and comply with accounting and tax regulations.
* **Data Deletion Requests:** You may contact us at [baka3k@gmail.com](mailto:baka3k@gmail.com) at any time to request assistance regarding server-side quota records, your data, or subscriptions.

---

### 1.5 Children’s Privacy
Mystic Tarot does not knowingly collect or solicit personal information from children under 13 years of age (or under 16 for residents of the European Economic Area). If we learn that we have inadvertently collected data from a child under the relevant age, we will take immediate steps to delete it.

---

## Part 2: Terms of Service (EULA) & Subscription Conditions

### 2.1 Entertainment & Guidance Disclaimer
* **For Entertainment & Reflection Only:** Mystic Tarot is designed as an interactive tool for self-reflection, spiritual guidance, philosophical curiosity, and entertainment.
* **Not Professional Advice:** Tarot readings and AI interpretations **do not** constitute medical, psychological, legal, financial, or investment advice. You should never make critical life, medical, or financial decisions based solely on a Tarot reading.
* **No Guarantees:** We make no claims or guarantees regarding the accuracy, predictive value, or outcome of any card interpretation.

---

### 2.2 Subscriptions, Billing, and Cancellation

#### A. Subscription Tiers & Quotas
Each single-card AI interpretation or holistic synthesis counts as **1 reading unit**.

| Plan | Reading Quota | Standard Price (USD) | Key Features |
| :--- | :--- | :--- | :--- |
| **Free Tier** | 5 free trial reading units (lifetime, no monthly reset) | **Free ($0.00)** | Full 78-card deck, standard spreads, local reading history. |
| **Tarot Basic** | 150 reading units / month | **$5.99 / month\*** | Expanded monthly reading capacity and multi-card AI synthesis. |
| **Tarot Pro (Best Value)** | 400 reading units / month | **$11.99 / month\*** | High-volume monthly capacity and priority AI interpretation engine. |

*\*Prices in local currencies (such as VND, EUR, JPY) are converted and displayed by Apple App Store and Google Play according to regional pricing matrices and applicable taxes.*

#### B. Auto-Renewal Terms
* Subscriptions are billed on a recurring monthly basis through your Apple ID or Google Play account upon confirmation of purchase.
* **Automatic Renewal:** Your subscription automatically renews at the end of each billing period unless auto-renew is turned off at least 24 hours prior to the end of the current billing period. Your account will be charged for renewal within 24 hours prior to the end of the current period.
* **Standard Apple EULA:** On iOS, use of this app is also governed by Apple's Standard Licensed Application End User License Agreement: [https://www.apple.com/legal/internet-services/itunes/dev/stdeula/](https://www.apple.com/legal/internet-services/itunes/dev/stdeula/).

#### C. How to Cancel or Manage Subscriptions
You may manage or cancel your subscription at any time without penalty:

**On iOS (Apple App Store):**
1. Open the **Settings** app on your iPhone or iPad.
2. Tap your **Name / Apple ID** at the top > **Subscriptions**.
3. Select **Mystic Tarot** and tap **Cancel Subscription**.

**On Android (Google Play):**
1. Open the **Google Play Store** app on your Android device.
2. Tap your profile icon in the top-right corner > **Payments & subscriptions** > **Subscriptions**.
3. Select **Mystic Tarot** and tap **Cancel subscription**.
4. Alternatively, manage your subscriptions online at: [https://play.google.com/store/account/subscriptions](https://play.google.com/store/account/subscriptions).

Upon cancellation, you will continue to enjoy your subscription benefits until the end of the current billing cycle.

#### D. Refunds & Restoring Purchases
* **Restore Purchases:** If you reinstall the app or switch devices, tap the **"Restore Purchases"** button in the Paywall or Settings to re-sync your active subscription.
* **Refunds:** All refund requests are governed by Apple App Store or Google Play's official refund policies. For iOS purchases, visit [https://reportaproblem.apple.com](https://reportaproblem.apple.com). For Android purchases, submit requests via your Google Play order history.

---

### 2.3 User Conduct & Intellectual Property
* You agree not to reverse-engineer, decompile, scrape, or flood the API services supporting Mystic Tarot.
* All visual assets, card artwork, text interpretations, branding, and application code are the intellectual property of Baka Team and protected by applicable copyright and intellectual property laws.

---

### 2.4 Changes to This Policy
We may periodically update this Privacy Policy and Terms of Service to reflect new features, operational practices, or legal requirements. Updated versions will be published on this page with a revised "Effective Date".

---

### 2.5 Contact Us
If you have any questions, suggestions, or concerns regarding this Privacy Policy or the terms of the service, please contact us:

* **Email:** [baka3k@gmail.com](mailto:baka3k@gmail.com)  
* **Support Page:** [https://baka3k.github.io/privacy-policy/tarot-support](https://baka3k.github.io/privacy-policy/tarot-support)  
* **Developer Team:** Baka Team

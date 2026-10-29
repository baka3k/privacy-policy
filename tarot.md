# Privacy Policy & Terms of Service

**Effective Date:** October 29, 2026  
**Application:** Mystic Tarot (Huyền Cơ Tarot)  
**Developer:** Baka Team  
**Contact:** [baka3k@gmail.com](mailto:baka3k@gmail.com)

---

Welcome to **Mystic Tarot** (also known as *Huyền Cơ Tarot*). We respect your privacy and are committed to protecting your personal data. This document outlines how our application operates, how data is handled, and the terms governing the use of our services and in-app subscriptions.

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
* This data is used **solely to generate the reading in real-time**.
* Questions and readings are **ephemeral** and are not used to build advertising profiles, sold to data brokers, or shared with unauthorized third parties.

#### B. Subscriptions & In-App Purchases (Google Play Billing)
Mystic Tarot offers optional subscription tiers (*Basic* and *Pro*) to unlock higher reading quotas:
* **Payment Processing:** All financial transactions, billing details, and payment methods (credit cards, mobile wallets, Google Play balance) are handled exclusively and securely by **Google Play Billing** (Google LLC).
* **Store Purchase Tokens:** When you make a purchase, Google Play provides an anonymous cryptographic purchase token (`purchaseToken`). Our server verifies this token directly with Google Play Developer APIs to activate your subscription tier and assign your reading quota.
* **No Financial Data Collection:** We never receive, store, or have access to your credit card numbers, billing addresses, or bank account information.

#### C. Anonymous Technical Identifiers & Rate Limiting
To ensure fair server resource allocation and prevent abusive automated requests:
* The app generates an anonymous, random installation identifier (`X-Install-Id`) stored locally on your device.
* This identifier is used exclusively to enforce monthly quota limits (Free: 40 readings/month, Basic: 150 readings/month, Pro: 400 readings/month) and rate-limit excessive traffic. It is not linked to your identity or personal information.

#### D. Diagnostics & Crash Reporting
Google Play services may collect anonymous crash logs, device hardware models, OS versions, and performance diagnostics to help us identify bugs and maintain stability. This information is aggregated and anonymous.

---

### 1.3 Third-Party Services
We partner with trusted service providers to deliver the application:
* **Google Play Services & Google Play Billing** (Google LLC) — For app distribution, updates, and secure subscription billing.
* **Cloudflare Workers** (Cloudflare, Inc.) — For secure API gateway routing, TLS encryption, and anti-DDoS protection.
* **Google Gemini AI** (Google LLC) — For generating AI-assisted interpretive text based on traditional Tarot symbolism.

Each third-party service processes information in accordance with their respective privacy policies.

---

### 1.4 Data Retention & Deletion
* **Local Data:** Since your reading history is stored strictly on your device, uninstalling the app or clearing app storage will permanently delete all local reading records.
* **Server Data:** Anonymous transaction validation records are retained only as required to maintain subscription validity and comply with accounting and tax regulations.
* **Data Deletion Requests:** You may contact us at [baka3k@gmail.com](mailto:baka3k@gmail.com) at any time to request assistance regarding your data or subscriptions.

---

### 1.5 Children’s Privacy
Mystic Tarot does not knowingly collect or solicit personal information from children under 13 years of age (or under 16 for residents of the European Economic Area). If we learn that we have inadvertently collected data from a child under the relevant age, we will take immediate steps to delete it.

---

## Part 2: Terms of Service & Subscription Conditions

### 2.1 Entertainment & Guidance Disclaimer
* **For Entertainment & Reflection Only:** Mystic Tarot is designed as an interactive tool for self-reflection, philosophical curiosity, creative inspiration, and entertainment.
* **Not Professional Advice:** Tarot readings and AI interpretations **do not** constitute medical, psychological, legal, financial, or investment advice. You should never make critical life, medical, or financial decisions based solely on a Tarot reading.
* **No Guarantees:** We make no claims or guarantees regarding the accuracy, predictive value, or outcome of any card interpretation.

---

### 2.2 Subscriptions, Billing, and Cancellation (Google Play)

#### A. Subscription Tiers & Quotas
* **Free Tier:** 40 readings per calendar month.
* **Basic Plan ($5.99 USD / month or regional equivalent):** 150 readings per billing cycle.
* **Pro Plan ($11.99 USD / month or regional equivalent):** 400 readings per billing cycle, priority processing.

#### B. Auto-Renewal Terms
* Subscriptions are billed on a recurring monthly basis through your Google Play account.
* **Automatic Renewal:** Your subscription automatically renews at the end of each billing period unless canceled at least 24 hours prior to the renewal date.
* **Price Changes:** Any changes to subscription pricing will be communicated in advance, and you will have the opportunity to accept or cancel prior to the effective date.

#### C. How to Cancel or Manage Subscriptions
You may cancel, pause, or change your subscription at any time directly through Google Play:
1. Open the **Google Play Store** app on your Android device.
2. Tap your profile icon in the top-right corner.
3. Select **Payments & subscriptions** > **Subscriptions**.
4. Select **Mystic Tarot** and tap **Cancel subscription**.
5. Alternatively, manage your subscriptions online at: [https://play.google.com/store/account/subscriptions](https://play.google.com/store/account/subscriptions).

Upon cancellation, you will continue to enjoy your subscription benefits until the end of the current billing cycle.

#### D. Refunds & Restoring Purchases
* **Restore Purchases:** If you reinstall the app or switch devices, tap the **"Restore Purchases"** button in the Paywall or Settings to re-sync your active Google Play subscription.
* **Refunds:** All refund requests are subject to Google Play’s official Refund Policy. You can submit refund requests directly through Google Play order history.

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
* **Developer Team:** Baka Team

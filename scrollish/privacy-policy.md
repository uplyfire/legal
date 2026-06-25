# Privacy Policy

**Last Updated:** June 25, 2026
**Effective Date:** June 25, 2026
**Policy Version:** 1.0

---

## Table of Contents

1. [Information We Collect](#1-information-we-collect)
2. [How We Use Information](#2-how-we-use-information)
3. [Consent Management (EEA, UK, and Switzerland)](#3-consent-management-eea-uk-and-switzerland)
4. [Third-Party Services](#4-third-party-services)
5. [Subscriptions and In-App Purchases](#5-subscriptions-and-in-app-purchases)
6. [Data Storage and Security](#6-data-storage-and-security)
7. [Data Retention and Deletion](#7-data-retention-and-deletion)
8. [Children's Privacy](#8-childrens-privacy)
9. [Permissions](#9-permissions)
10. [International Data Transfers](#10-international-data-transfers)
11. [Your Rights](#11-your-rights)
12. [Future Changes to Data Practices](#12-future-changes-to-data-practices)
13. [EU Digital Services Act (DSA) Disclosures](#13-eu-digital-services-act-dsa-disclosures)
14. [Changes to This Privacy Policy](#14-changes-to-this-privacy-policy)
15. [Contact Us](#15-contact-us)
16. [Additional Disclosures](#16-additional-disclosures)

---

Uplyfire ("we," "us," or "our") operates the Scrollish mobile application (the "App"), an application for learning English. This Privacy Policy describes how we collect, use, store, and protect information when you use our App. Please read this Privacy Policy carefully to understand our data practices. Where our processing of your personal data relies on consent as its legal basis (such as analytics and crash reporting), we obtain that consent separately through appropriate mechanisms (e.g., the in-app consent dialog presented to users in the European Economic Area, the United Kingdom, and Switzerland) in compliance with applicable law.

We are committed to protecting your privacy and ensuring transparency about our data practices. This policy is designed to comply with applicable data protection regulations, including the General Data Protection Regulation (GDPR), the UK GDPR, the California Consumer Privacy Act as amended by the California Privacy Rights Act (CCPA/CPRA), the Brazilian General Data Protection Law (Lei Geral de Proteção de Dados, LGPD), the Children's Online Privacy Protection Act (COPPA), and the Google Play Developer Program Policies.

**Summary of our approach:** Scrollish is designed to be private by default. Your learning content — your progress, streaks, saved cards, achievements, and the optional name you choose — is stored **only on your device** and is not transmitted to us. The App does not require you to create an account, and we do not ask for your email address, phone number, or location. The limited information that does leave your device is used to (a) deliver the optional daily reminder notifications you ask for, and (b) — only with your consent — measure app performance and diagnose crashes. The App does **not** display advertisements.

---

## 1. Information We Collect

### 1.1 Information We Do NOT Collect

Scrollish does **not** collect, request, or process:

- Your email address, phone number, mailing address, or date of birth
- Your real-world identity or government identifiers
- Location or GPS data
- Contacts, calendar, or phone data
- Photos, files, or media from your device
- Microphone or camera input (the App has no speech recognition, recording, or camera features)
- Biometric data
- Health or fitness data
- Financial information (credit/debit card numbers, bank accounts)
- Browsing history or activity in other apps
- Social media profiles or credentials
- Hardware device identifiers such as IMEI or IMSI

### 1.2 Information You Provide and Information Stored Locally on Your Device

The following information is created as you use the App and is stored **exclusively on your device**. It is **not** transmitted to our servers or to any third party by the App:

- **Optional name or nickname.** During onboarding (and later in Settings → Account), you may optionally enter a name or nickname so the App can greet you. This step can be skipped, and the App functions fully without it. The name is stored only on your device and is never sent to us. (If you create a backup file — see Section 1.4 and Section 6.3 — the name is included in that file, which remains under your control.)
- **Learning progress.** Per-card learning state used by the spaced-repetition algorithm (e.g., card status, review intervals, ease factors, number of correct/incorrect attempts).
- **Activity and gamification data.** Learning sessions, daily streaks, daily activity totals (cards answered, minutes, experience points), streak shields, and unlocked achievements.
- **Saved cards.** Identifiers of cards you bookmark.
- **Preferences and settings.** Your daily goal, chosen reminder time(s), theme, audio autoplay, sound and haptics settings, selected level, and onboarding state.

This data is stored using a local database (SQLite via the Room library) and remains under your direct control. It is **not** included in Android's standard automatic cloud backup (see Section 6.3).

### 1.3 Information Collected and Transmitted by Integrated Services

To provide certain features, Scrollish integrates the following Google and Firebase services. Each is described below, including what it processes and when.

#### a) Firebase Analytics and Firebase Crashlytics (consent-gated)

We use **Firebase Analytics** to understand, in aggregate, how the App is used (for example, which features are opened and how learning sessions progress) so we can improve it, and **Firebase Crashlytics** to detect and diagnose crashes and technical errors.

**These services are disabled by default and are activated only after you provide consent** through the in-app consent dialog (see Section 3). Until consent is granted — and at all times if you decline — no analytics or crash-reporting data is collected or transmitted.

When enabled, these services may process:

- App-usage events and aggregated interaction data (e.g., screens opened, sessions started/completed)
- A pseudonymous app-instance identifier generated by Firebase
- Device and technical information (device model, operating system version, language, region, app version)
- Crash logs, stack traces, and device state at the time of a crash (Crashlytics)
- The Android Advertising ID (AAID), which the Google SDKs may use for analytics measurement

We do **not** use this data to identify you personally, and we do not combine it with the locally stored learning data described in Section 1.2.

#### b) Daily Reminder Notifications — Firebase Cloud Messaging and Cloud Functions

If you enable reminder notifications, the App registers your device with our reminder service so that your daily reminders fire reliably. This service is built on **Firebase Cloud Messaging (FCM)**, **Firebase Cloud Functions**, **Firebase Anonymous Authentication**, and **Firebase App Check**.

When you enable reminders, the following information is sent to and stored in our backend (Google Firestore), keyed to an **anonymous, randomly generated Firebase identifier** that is not linked to your real identity:

- The **FCM registration token** for your device (a device-specific push identifier)
- A **brand identifier** indicating which of our apps you are using (e.g., "english")
- Your device's **time zone**
- The **local times** you chose for your reminders, and the next scheduled fire time

**We do not send your name, your learning progress, your email, or any content you study to this backend.** The record exists solely to schedule and deliver your reminders. The notifications themselves are generated on your device from text bundled in the App; no server selects or personalizes their content based on your activity.

You can delete this backend record at any time by turning reminders off in the App, which instructs our backend to delete it. Uninstalling the App stops reminders from being delivered, but on its own does not delete the record (see Section 7).

#### c) Google Play Billing

When you start a free trial or purchase a subscription, the transaction is processed entirely by **Google Play**. We do not collect or store your payment information. Google Play processes:

- Purchase and subscription records for the App (product identifiers, purchase tokens, timestamps, subscription status)
- The Google Account information necessary to process the transaction

The App receives from Google Play only the information needed to determine your entitlement (whether you have an active subscription or trial). For more information, see [Google Play's Terms of Service](https://play.google.com/about/play-terms/).

#### d) Google User Messaging Platform (UMP)

We use the **Google UMP SDK** to present the consent dialog and to record your consent choices for users in the EEA, the UK, and Switzerland (see Section 3).

#### e) Google Play Services and Firebase App Check

The App relies on **Google Play Services** for core infrastructure and uses **Firebase App Check (Play Integrity)** to verify that requests to our reminder backend come from a genuine, untampered instance of the App. App Check processes a device/app integrity attestation token issued by Google; it does not identify you.

### 1.4 Backup Files You Create

If you are a Premium subscriber, you can use the in-app **"Back up & transfer your progress"** feature to export your learning data (including the optional name, progress, streaks, saved cards, and achievements) to a single JSON file. You choose where this file is saved using your device's system file picker. **We do not receive, store, or have access to this file** — it remains entirely under your control. Where you save it (for example, to a personal cloud-storage location) and how it is protected is your decision.

---

## 2. How We Use Information

We use information for the following purposes:

| Purpose | Data Used | Legal Basis (GDPR Art. 6) |
|---------|-----------|---------------------------|
| Providing core App functionality (lessons, scoring, spaced-repetition scheduling, progress tracking, streaks, achievements) | Learning data stored locally on your device | Performance of a contract (Art. 6(1)(b)) |
| Saving and restoring your preferences, settings, and optional name | Preferences stored locally on your device | Performance of a contract (Art. 6(1)(b)) |
| Delivering the daily reminder notifications you request | FCM token, time zone, chosen reminder times, brand identifier, anonymous identifier | Consent (Art. 6(1)(a)) — given when you enable reminders and the notification permission |
| Measuring app usage to improve features (Firebase Analytics) | Aggregated usage events, app-instance ID, device/technical info, Advertising ID | Consent (Art. 6(1)(a)), obtained via the in-app consent dialog |
| Detecting and fixing crashes and technical errors (Firebase Crashlytics) | Crash logs, device state, technical info | Consent (Art. 6(1)(a)), obtained via the in-app consent dialog |
| Processing subscriptions and trials, and verifying entitlement | Purchase data processed by Google Play | Performance of a contract (Art. 6(1)(b)) |
| Protecting our reminder backend from abuse | Firebase App Check attestation token | Legitimate interest (Art. 6(1)(f)) — security and integrity |

We do **not** use any information for:

- Advertising or ad personalization (the App displays no advertisements)
- Selling personal information (as defined under CCPA/CPRA)
- Profiling or automated decision-making that produces legal or similarly significant effects (GDPR Art. 22)
- Direct marketing or email campaigns
- Cross-app or cross-device tracking

---

## 3. Consent Management (EEA, UK, and Switzerland)

If you are located in the European Economic Area, the United Kingdom, or Switzerland, the App presents a consent dialog (powered by the Google UMP SDK) on first launch. **Firebase Analytics and Firebase Crashlytics collection remains disabled until you grant consent.** If you decline, the App continues to work fully and no analytics or crash-reporting data is collected.

You can review or change your consent choice at any time through: **Settings → "Privacy & ad settings."**

For users outside the EEA, UK, and Switzerland, analytics and crash reporting may be enabled by default in accordance with applicable law; you can still limit collection using the device-level controls described in Section 9 and Section 11, and analytics/crash data is processed as described in this policy.

Reminder notifications are always opt-in: they are delivered only if you grant the Android notification permission and enable reminders in the App.

---

## 4. Third-Party Services

Scrollish relies on the following third-party services, all provided by Google LLC:

| Service | Provider | Purpose | Privacy Policy |
|---------|----------|---------|----------------|
| Firebase Analytics | Google LLC | Aggregated app-usage measurement (consent-gated) | [Google Privacy Policy](https://policies.google.com/privacy) |
| Firebase Crashlytics | Google LLC | Crash and error diagnostics (consent-gated) | [Google Privacy Policy](https://policies.google.com/privacy) |
| Firebase Cloud Messaging | Google LLC | Delivery of reminder notifications | [Google Privacy Policy](https://policies.google.com/privacy) |
| Firebase Cloud Functions + Firestore | Google LLC | Scheduling of reminder notifications | [Google Privacy Policy](https://policies.google.com/privacy) |
| Firebase Authentication (Anonymous) | Google LLC | Anonymous identifier for the reminder backend | [Google Privacy Policy](https://policies.google.com/privacy) |
| Firebase App Check (Play Integrity) | Google LLC | Backend abuse and integrity protection | [Google Privacy Policy](https://policies.google.com/privacy) |
| Google Play Billing | Google LLC | Subscription and trial processing | [Google Play Terms](https://play.google.com/about/play-terms/) |
| Google Play Services | Google LLC | Core app infrastructure | [Google Privacy Policy](https://policies.google.com/privacy) |
| Google User Messaging Platform (UMP) | Google LLC | Consent management (EEA/UK/Switzerland) | [Google Privacy Policy](https://policies.google.com/privacy) |

We do not share your information with any other third parties, data brokers, advertising networks, or analytics providers.

**Data Processing Agreements:** Our use of Google and Firebase services is governed by Google's data processing terms, including the [Google Ads Data Processing Terms](https://privacy.google.com/businesses/processorterms/) (where applicable) and the [Firebase Data Processing and Security Terms](https://firebase.google.com/terms/data-processing-terms), together with applicable Standard Contractual Clauses (SCCs) for international data transfers. For the services above, Google acts as a data processor on our behalf, and as an independent data controller for its own purposes as described in Google's privacy policy.

---

## 5. Subscriptions and In-App Purchases

Scrollish offers an auto-renewing premium subscription ("Scrollish Premium"):

- **Monthly** and **annual** subscription plans
- A short **free trial** at the start of the subscription, where offered

A portion of the App's content is available for free; Premium unlocks the full course, premium themes, the progress backup feature, and additional streak shields.

All purchases and subscriptions are processed by **Google Play**. We do not collect, process, or store your payment information. Subscriptions are tied to your Google Account and renew automatically until cancelled. You can manage or cancel your subscription at any time via **Settings → "Manage subscription"** (which opens Google Play) or directly in the Google Play Store. You can restore an existing purchase via **Settings → "Restore purchases."**

Refunds are governed by [Google Play's refund policy](https://support.google.com/googleplay/answer/2479637). Pricing, billing, and cancellation terms are described in our [Terms of Service](terms.md).

---

## 6. Data Storage and Security

### 6.1 Local Storage

Your learning data, preferences, and optional name are stored locally on your device using:

- A **SQLite database** (via the Room library) for learning progress, sessions, streaks, saved cards, achievements, and preferences

This data never leaves your device through the App, other than the limited reminder-scheduling information described in Section 1.3(b) and any backup file you choose to create (Section 1.4).

### 6.2 Security Measures

- All local data is stored in the App's private storage directory, inaccessible to other applications
- All network communication uses encrypted connections (HTTPS/TLS)
- Requests to our reminder backend are protected by Firebase App Check
- Analytics and crash reporting are disabled until consent is granted (where consent applies)
- The App does not load or execute remote scripts or code; learning content (text, images, audio) is bundled with the App

### 6.3 Android Auto Backup

The App **excludes** its database and preferences from Android's automatic cloud backup and device-transfer features. This means your learning data is not automatically copied to your Google Account by the operating system. To move your progress to a new device, use the in-app backup-and-transfer feature described in Section 1.4 (available to Premium subscribers).

---

## 7. Data Retention and Deletion

### 7.1 Retention

Your learning data is retained on your device for as long as you keep the App installed and do not delete it. We do not retain this data on our servers.

The reminder-scheduling record described in Section 1.3(b) is retained on our backend until it is deleted. It is deleted when you turn reminders off in the App (or on request — see Section 7.2). If you uninstall the App without first turning reminders off, the record stops being used to deliver reminders and is marked inactive, but it is not automatically deleted; you can ask us to delete it at any time (see Section 7.2).

### 7.2 Deleting Your Data

You may delete your data at any time:

- **Delete all in-app data:** Open **Settings → "Delete all my data"** and confirm in the dialog. This permanently deletes all your progress, streaks, settings, and the optional name from your device.
- **Turn off reminders:** Disabling reminders in **Settings → Notifications** instructs our backend to delete the reminder-scheduling record for your device.
- **Clear app data:** Android Settings → Apps → Scrollish → Storage → Clear Data.
- **Uninstall the App:** Removes all locally stored data from your device and stops reminder delivery. Uninstalling does **not**, by itself, delete the reminder-scheduling record on our backend. To delete that record, turn reminders off (Settings → Notifications) before uninstalling, or email us (see below).
- **By email request:** You may contact us at [uplyfire@gmail.com](mailto:uplyfire@gmail.com). Because your learning data is stored locally on your device, we will provide instructions for the methods above; for the reminder-scheduling record, we can delete it on request. We will respond to deletion requests within 30 days.

### 7.3 Web-Based Data Deletion Request (Google Play Requirement)

In accordance with Google Play's data deletion policy, you may also review the deletion process and submit a request via our website at: **https://uplyfire.github.io/legal/scrollish/data-deletion**

For data processed by Firebase Analytics and Crashlytics, you may manage or delete data associated with your device through your [Google Account settings](https://myaccount.google.com/data-and-privacy). Purchase and subscription history managed by Google Play cannot be deleted through the App; to review it, visit [Google Play Order History](https://play.google.com/store/account/orderhistory).

---

## 8. Children's Privacy

Scrollish is an educational application intended for a **general audience aged 13 and over**. It is **not directed to children under the age of 13**, and we do **not** knowingly collect personal information from children under 13 (or the applicable age of digital consent in your jurisdiction).

The App does not:

- Require account creation or registration
- Collect names, email addresses, or other personal identifiers (the optional in-app name is stored only on the device and is never transmitted to us)
- Enable communication between users
- Display advertising

If you are a parent or guardian and believe a child under 13 has provided personal information through the App, please contact us at [uplyfire@gmail.com](mailto:uplyfire@gmail.com) so we can take appropriate action.

**Age of digital consent by jurisdiction:** For users in the EEA, the age of digital consent varies by member state (13–16 years under GDPR Art. 8). For users in Brazil, parental consent is required for processing data of children under 12 (LGPD Art. 14). If you are under the applicable age of consent in your jurisdiction, you must have a parent or legal guardian's permission to use the App, and a parent or guardian must make any consent decision (such as enabling analytics) on your behalf.

---

## 9. Permissions

Scrollish requests the following Android permissions:

| Permission | Purpose | Required? |
|------------|---------|-----------|
| `INTERNET` | Connecting to Google Play (purchases), Firebase (reminders and, with consent, analytics/crash reporting). Not used to transmit your learning data. | Yes |
| `ACCESS_NETWORK_STATE` | Detecting network connectivity. | Yes |
| `POST_NOTIFICATIONS` | Showing the daily reminder notifications you opt into (Android 13+). | Optional — requested only if you enable reminders |
| `RECEIVE_BOOT_COMPLETED` | Re-scheduling your reminders after the device restarts (scheduled alarms do not survive a reboot). | Yes (used only if you enable reminders) |

The App does **not** request access to location, camera, microphone, contacts, storage, phone state, SMS, or Bluetooth.

**Advertising ID (`com.google.android.gms.permission.AD_ID`):** The Google SDKs included in the App (Firebase Analytics) declare this permission. When you have consented to analytics, Firebase Analytics may use the Android Advertising ID for measurement purposes. You can reset or delete your Advertising ID, or opt out of its personalization, in your device settings: Android Settings → Google → Ads. The App does **not** use the Advertising ID for advertising, as it displays no ads.

---

## 10. International Data Transfers

The reminder-scheduling information and, where consented, analytics and crash data are processed by Google/Firebase on infrastructure that may be located outside your country of residence, including in the United States.

For transfers of personal data from the European Economic Area (EEA), the United Kingdom (UK), or Switzerland to countries that have not received an adequacy decision from the European Commission, Google relies on the following transfer mechanisms:

- **Standard Contractual Clauses (SCCs)** approved by the European Commission
- **UK International Data Transfer Addendum** where applicable
- Additional technical and organizational safeguards as described in [Google's Data Transfer Frameworks documentation](https://policies.google.com/privacy/frameworks)

For transfers from Brazil, Google maintains compliance with LGPD requirements for international data transfers (LGPD Art. 33).

---

## 11. Your Rights

Depending on your jurisdiction, you may have the following rights regarding your data. Because your learning data is stored locally on your device, most of these rights are exercisable directly through the in-app data controls (Section 7) and your device settings. For data processed by Firebase, you may also exercise rights directly with Google.

### 11.1 GDPR Rights (European Economic Area and United Kingdom)

If you are located in the EEA or UK, you have the following rights under the GDPR (and UK GDPR):

- **Right of access (Art. 15)** — Request a copy of the personal data we process about you
- **Right to rectification (Art. 16)** — Correct inaccurate or incomplete personal data
- **Right to erasure (Art. 17)** — Request deletion of your personal data (see Section 7)
- **Right to restrict processing (Art. 18)** — Limit how your personal data is processed
- **Right to data portability (Art. 20)** — Receive your personal data in a structured, commonly used, machine-readable format. Premium subscribers can export their learning data to a JSON file via the in-app backup feature; regardless of whether you subscribe, you may also request your data from us at no charge using the contact details in Section 15
- **Right to object (Art. 21)** — Object to processing based on legitimate interest
- **Right to withdraw consent (Art. 7(3))** — Withdraw consent for analytics, crash reporting, or reminders at any time (via Settings → "Privacy & ad settings" or by disabling reminders), without affecting the lawfulness of processing before withdrawal
- **Right to lodge a complaint (Art. 77)** — Lodge a complaint with your local data protection supervisory authority. A list of EEA supervisory authorities is available at [https://edpb.europa.eu/about-edpb/about-edpb/members_en](https://edpb.europa.eu/about-edpb/about-edpb/members_en)

**Data Protection Officer:** Given the nature and scale of our data processing activities, we are not required to appoint a Data Protection Officer under GDPR Art. 37. For all privacy-related inquiries, please contact us using the details in Section 15.

### 11.2 CCPA/CPRA Rights (California Residents)

If you are a California resident, you have the following rights under the CCPA as amended by the CPRA:

- **Right to know (Cal. Civ. Code § 1798.100)** — Request disclosure of the categories and specific pieces of personal information collected, the sources, the purposes, and the categories of third parties with whom it is shared
- **Right to delete (§ 1798.105)** — Request deletion of personal information we have collected
- **Right to correct (§ 1798.106)** — Request correction of inaccurate personal information
- **Right to opt-out of sale or sharing (§ 1798.120)** — Opt out of the sale or sharing of personal information
- **Right to limit use of sensitive personal information (§ 1798.121)** — We do not collect sensitive personal information as defined by the CPRA
- **Right to non-discrimination (§ 1798.125)** — Not be discriminated against for exercising your privacy rights

**Sale and Sharing of Personal Information:** Scrollish does **not** "sell" or "share" personal information as those terms are defined under the CCPA/CPRA. The App displays no advertising and engages in no cross-context behavioral advertising. To submit a verifiable consumer request, contact us at the email address in Section 15. We will respond within 45 days as required by law.

**California "Shine the Light" (Cal. Civ. Code § 1798.83):** We do not disclose personal information to third parties for their direct marketing purposes.

### 11.3 LGPD Rights (Brazilian Residents)

If you are located in Brazil, you have the rights set out in Art. 18 of the Lei Geral de Proteção de Dados (LGPD, Law No. 13,709/2018), including confirmation of processing, access, correction, anonymization/blocking/deletion, portability, information about sharing, information about consent, and revocation of consent.

**Legal basis for processing under LGPD:** Reminder notifications, analytics, and crash reporting are based on your consent (Art. 7(I)). Processing for subscriptions is based on contractual necessity (Art. 7(V)). Backend integrity protection is based on legitimate interest (Art. 7(IX)).

To exercise your LGPD rights, contact us at the email address in Section 15. We will respond within 15 days as recommended by the ANPD (Autoridade Nacional de Proteção de Dados).

---

## 12. Future Changes to Data Practices

We may in the future introduce additional features that change our data practices. These may include:

- **Advertising.** We may introduce advertising (for example, through Google AdMob) to support a free version of the App. If we do, the App would collect and share information such as the Android Advertising ID, IP address, and device information with ad networks to deliver and, where consented, personalize ads. For users in the EEA and UK, we would request advertising consent through an IAB Transparency and Consent Framework (TCF)-compliant dialog before serving personalized ads, and we would offer an ad-free experience to subscribers. **As of the Effective Date, the App displays no advertisements and collects no data for advertising purposes.**
- **Additional in-app purchases.** We may offer one-time in-app purchases of additional content (for example, optional add-on courses) in addition to the subscription. These would be processed by Google Play in the same way as the subscription, and we would not collect or store your payment information.
- **Expanded analytics or new services.** We may integrate additional measurement or infrastructure services to improve the App.

**If and when we enable any such feature, we will:**

1. Update this Privacy Policy **before** any new data collection begins
2. Clearly describe what additional data is collected and for what purpose
3. Update the Google Play Data Safety declaration accordingly
4. Where the change relies on consent (such as personalized advertising), obtain that consent before the change takes effect
5. Notify users through the App or the Google Play Store listing where appropriate

No data collection beyond what is described in Sections 1–4 of this Privacy Policy will occur without a published update to this policy.

---

## 13. EU Digital Services Act (DSA) Disclosures

For users in the European Union, in accordance with Regulation (EU) 2022/2065 (the Digital Services Act):

- **Advertising transparency:** The App displays no advertisements. Should advertising be introduced in the future, we will provide the transparency information required by the DSA at that time.
- **Recommender systems:** Scrollish does not use profiling-based recommender systems. The order in which learning cards are presented is determined by a spaced-repetition algorithm based on your own answers and review schedule on your device, not by profiling for commercial purposes.
- **Content moderation:** Scrollish does not host user-generated content and therefore does not perform content moderation.
- **Point of contact:** For DSA-related inquiries, please contact us at [uplyfire@gmail.com](mailto:uplyfire@gmail.com) (see Section 15).

---

## 14. Changes to This Privacy Policy

We may update this Privacy Policy from time to time to reflect changes in our practices, technology, legal requirements, or other factors. When we make changes:

- **For all updates:** We will update the "Last Updated" date and Policy Version number at the top of this document
- **For material changes** (new data collection, new third-party services, changes to data sharing): We will notify users through an in-app notice or the Google Play Store listing before the changes take effect
- **For non-material changes** (clarifications, formatting, updated links): Changes take effect upon posting

Where changes affect processing activities that rely on your consent, we will seek your renewed consent before applying the changes. For other changes, your continued use of the App after changes are posted constitutes your acknowledgment of the revised policy, to the extent permitted by applicable law.

---

## 15. Contact Us

If you have any questions, concerns, or requests regarding this Privacy Policy or our data practices, please contact us at:

**Uplyfire**
Email: [uplyfire@gmail.com](mailto:uplyfire@gmail.com)

You may also contact us through the developer contact information listed on the [Scrollish Google Play Store listing](https://play.google.com/store/apps/details?id=com.scrollish.android).

We aim to respond to all privacy-related inquiries within 30 days. For GDPR-related requests, we will respond within one month as required by Art. 12(3). For CCPA/CPRA requests, we will respond within 45 days. For LGPD requests, we will respond within 15 days.

---

## 16. Additional Disclosures

### 16.1 Google Play Data Safety Section

In accordance with Google Play requirements, the following summarizes our data practices as declared in the Data Safety form for the current version of the App. **The App displays no advertisements; no data is collected or shared for advertising purposes.**

| Data Category | Data Type | Collected? | Shared? | Purpose | Optional? |
|---------------|-----------|------------|---------|---------|-----------|
| App activity | App interactions / usage events | Yes (Firebase Analytics) | Shared with Google as processor | Analytics | Yes — consent-gated |
| Device or other IDs | App-instance ID; Advertising ID (AAID) | Yes (Firebase Analytics) | Shared with Google as processor | Analytics | Yes — consent-gated |
| App info and performance | Crash logs, diagnostics | Yes (Firebase Crashlytics) | Shared with Google as processor | App stability / diagnostics | Yes — consent-gated |
| Device or other IDs | Push token (FCM) | Yes | Processed by Google (FCM) | Reminder notifications | Yes — only if reminders enabled |
| App activity | Reminder schedule and time zone | Yes (reminder backend) | No | Reminder notifications | Yes — only if reminders enabled |
| Financial info | Purchase/subscription history | Yes (by Google Play) | No | App functionality | No (only if you purchase) |
| App activity | Learning progress, streaks, saved cards, achievements | Stored locally only — not collected by us | No | App functionality | No |
| Personal info | Name / nickname | Stored locally only — not collected by us | No | App functionality | Yes — optional |

**Data handling declarations:**
- **Encryption in transit:** Yes — all network communication uses HTTPS/TLS
- **Data deletion:** Users can delete local data in-app (Settings → "Delete all my data"), clear app data, or uninstall; the reminder-scheduling record is deleted when reminders are turned off. A web-based deletion request is available at https://uplyfire.github.io/legal/scrollish/data-deletion. For data held by Google (Firebase, Play), see [Google's data controls](https://myaccount.google.com/data-and-privacy)
- **Data is not sold or shared for advertising:** We do not sell user data and display no advertising
- **Consent:** Analytics and crash reporting are disabled until consent is granted (EEA/UK/Switzerland) and can be changed in Settings

> **Note for the publisher (not part of the policy):** Before each release, ensure the Play Console Data Safety form matches the shipped build. In particular, the `AD_ID` permission is present (added by the Firebase Analytics SDK), so the Advertising ID must be declared as collected for analytics. If advertising or additional in-app purchases are enabled in a future release, update both this policy (Section 12) and the Data Safety form before that release.

### 16.2 Apple App Store Compatibility

If Scrollish becomes available on iOS, this Privacy Policy will also cover the iOS version, and the App Store "App Privacy" labels will be made consistent with the disclosures in this Privacy Policy. Any iOS-specific mechanisms (such as Apple's App Tracking Transparency framework) would be addressed at that time; as the App currently performs no tracking and shows no ads, no cross-app tracking permission would be requested for the features described in this policy.

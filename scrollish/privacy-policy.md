# Privacy Policy

**Last Updated:** September 3, 2026
**Effective Date:** September 3, 2026
**Policy Version:** 1.1

---

## Table of Contents

1. [Information We Collect](#1-information-we-collect)
2. [How We Use Information](#2-how-we-use-information)
3. [Consent and Your Controls](#3-consent-and-your-controls)
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
16. [Google Play Data Safety Summary](#16-google-play-data-safety-summary)

---

Uplyfire ("we," "us," or "our") operates the Scrollish mobile application (the "App"), an application for learning English. This Privacy Policy describes how we collect, use, store, and protect information when you use our App. Please read it carefully. Where our processing of your personal data relies on consent as its legal basis, we obtain that consent through the mechanisms described in Section 3.

This policy is designed to comply with applicable data protection regulations, including the General Data Protection Regulation (GDPR), the UK GDPR, the California Consumer Privacy Act as amended by the California Privacy Rights Act (CCPA/CPRA), the Brazilian General Data Protection Law (Lei Geral de Proteção de Dados, LGPD), the Children's Online Privacy Protection Act (COPPA), and the Google Play Developer Program Policies.

**Summary of our approach:** Scrollish is designed to be private by default. The content of what you study — card text, questions, answers, your saved cards and the optional name you choose — is stored **only on your device** and is never uploaded by the App. The App does not require you to create an account, and we do not ask for your email address, phone number, or location. What does leave your device is limited to: (a) a small record used to deliver the optional daily reminder notifications you ask for; (b) analytics and crash-reporting data processed by Google Firebase, which includes numeric measurements of how you use the App (such as the lesson you reached, your accuracy and your streak) — collected only with your consent in the EEA, the UK and Switzerland, and enabled by default elsewhere (see Section 3); and (c) your device's IP address, which necessarily reaches Google's servers whenever the App connects to them. The App displays **no advertisements** and collects no data for advertising purposes.

---

## 1. Information We Collect

### 1.1 Information We Do NOT Collect

Scrollish does **not** collect, request, or process:

- Your email address, phone number, mailing address, or date of birth
- Your real-world identity or government identifiers
- Precise or GPS location. The App has no location permission and never requests your position. Where analytics is enabled, Google derives an **approximate, city- or region-level location from your IP address** for reporting purposes, as described in Section 1.3(a); we cannot see your address or precise position
- Contacts, calendar, or phone data
- Photos, files, or media from your device
- Microphone or camera input (the App has no speech recognition, recording, or camera features)
- Biometric data
- Health or fitness data
- Payment information (credit/debit card numbers, bank accounts) — handled entirely by Google Play
- Browsing history or activity in other apps
- Social media profiles or credentials
- Hardware device identifiers such as IMEI or IMSI

### 1.2 Information You Provide and Information Stored Locally on Your Device

The following information is created as you use the App and is stored **on your device**. We do not upload the content of what you study — no card text, no questions, no answers and no lesson content ever leaves your device. Where analytics is enabled (Section 1.3(a)), a limited set of **numeric measurements derived from this data** (for example the lesson number you reached, your accuracy percentage, experience points, streak length and level) is sent to Firebase Analytics so we can see how the App is used. Everything else in the list below stays on your device:

- **Optional name or nickname.** During onboarding (and later in Settings → Account), you may optionally enter a name or nickname so the App can greet you. This step can be skipped, and the App functions fully without it. The name is stored only on your device and is never sent to us. (If you create a backup file — see Section 1.4 and Section 6.3 — the name is included in that file, which remains under your control.)
- **Learning progress.** Per-card learning state used by the spaced-repetition algorithm (e.g., card status, review intervals, ease factors, number of correct/incorrect attempts).
- **Activity and gamification data.** Learning sessions, daily streaks, daily activity totals (cards answered, minutes, experience points), streak shields, and unlocked achievements.
- **Saved cards.** Identifiers of cards you bookmark.
- **Preferences and settings.** Your daily goal, chosen reminder time(s), theme, audio autoplay, sound and haptics settings, selected level, and onboarding state.

This data is stored using a local database (SQLite via the Room library) and remains under your direct control. It is **not** included in Android's standard automatic cloud backup (see Section 6.3).

### 1.3 Information Collected and Transmitted by Integrated Services

To provide certain features, Scrollish integrates the following Google and Firebase services. Each is described below, including what it processes and when.

#### a) Firebase Analytics and Firebase Crashlytics

We use **Firebase Analytics** to understand how the App is used so we can improve it, and **Firebase Crashlytics** to detect and diagnose crashes and technical errors.

**Where consent is required (EEA, UK, Switzerland), these services are disabled by default and are activated only after you grant consent** through the in-app consent dialog (see Section 3). If you decline, they stay off and no analytics or crash-reporting data is collected or transmitted.

**Elsewhere, these services are enabled when you first open the App**, because consent is not legally required in your jurisdiction. Collection is off at process start and is switched on once the App has determined that no consent dialog is required for your region. Section 3 explains how to have collection stopped.

When enabled, these services process:

- **Individual app-usage events**, each recorded against a pseudonymous app-instance identifier, with mechanic-level parameters. These include: screens opened; sessions started and completed; lesson number reached, number of cards, accuracy percentage and experience points earned; card type and whether an answer was correct; the identifier of a card you explicitly report, mark as too easy, or mark as not interesting; streak milestones; your chosen daily goal and self-declared level; whether the in-app review prompt was shown; and subscription events (plan, price, currency, trial start, conversion, renewal, cancellation).
- **Persistent profile attributes** attached to that pseudonymous identifier: your level, tier, subscription status, current streak length and daily goal.
- A pseudonymous **app-instance identifier** generated by Firebase.
- **Device and technical information** (device model, operating system version, language, region, app version).
- **Your IP address**, from which Google derives an approximate (city- or region-level) location for reporting; Google masks the address and does not retain it in its raw form (see Sections 1.1 and 10).
- The **Google Play install referrer** (which store campaign or link led to your install), which Google's measurement library may read for install attribution.
- **Crash logs, stack traces, and device state** at the time of a crash (Crashlytics).
- The **Android Advertising ID (AAID)**, which the Google measurement library may collect for analytics measurement (see Section 9).

We do **not** transmit the content of your learning material — no card text, no questions, no answers, no notes. We do not use this data to identify you by name, and we do not ask Google to link it to any account. This data is **pseudonymous rather than anonymous**: it is tied to a per-installation identifier and, taken together, describes the learning behaviour of a single installation.

#### b) Daily Reminder Notifications — Firebase Cloud Messaging and Cloud Functions

If you enable reminder notifications, the App registers your device with our reminder service so that your daily reminders fire reliably. This service is built on **Firebase Cloud Messaging (FCM)**, **Firebase Cloud Functions**, **Firebase Anonymous Authentication**, and **Firebase App Check**.

When you enable reminders, the following information is sent to and stored in our backend (Google Cloud Firestore, `europe-west1` region), keyed to an **anonymous, randomly generated Firebase identifier** that is not linked to your real identity:

- The **FCM registration token** for your device (a device-specific push identifier)
- A **brand identifier** indicating which of our apps you are using (e.g., "english")
- Your device's **time zone**
- The **local times** you chose for your reminders, and the next scheduled fire time
- A delivery-health flag and the time of the last update

Your IP address reaches Google when the App calls this service. **We do not send your name, your learning progress, your email, or any content you study to this backend.** The record exists solely to schedule and deliver your reminders. The notifications themselves are generated on your device from text bundled in the App; no server selects or personalizes their content based on your activity.

You can delete this backend record at any time by turning reminders off in the App, which instructs our backend to delete it. Uninstalling the App stops reminders from being delivered, but on its own does not delete the record (see Section 7).

#### c) Google Play Billing

When you start a free trial or purchase a subscription, the transaction is processed entirely by **Google Play**. We do not collect or store your payment information. Google Play processes:

- Purchase and subscription records for the App (product identifiers, purchase tokens, timestamps, subscription status)
- The Google Account information necessary to process the transaction

The App receives from Google Play only the information needed to determine your entitlement (whether you have an active subscription or trial). Where analytics is enabled, the App also records the **fact and shape** of a purchase — which plan, the displayed price and currency, and whether a trial started, converted or was cancelled — as described in Section 1.3(a); Firebase Analytics also logs purchase and subscription events automatically (product identifier, product name and price). It never records your payment method, card details or billing address, none of which the App can see. For more information, see [Google Play's Terms of Service](https://play.google.com/about/play-terms/).

#### d) Google User Messaging Platform (UMP)

We use the **Google UMP SDK** to present the consent dialog and to record your consent choices for users in the EEA, the UK, and Switzerland (see Section 3). Your consent choice is stored on your device.

#### e) Google Play Services, Firebase App Check and the Google authentication library

The App relies on **Google Play Services** for core infrastructure and uses **Firebase App Check (Play Integrity)** to verify that requests to our reminder backend come from a genuine, untampered instance of the App. App Check processes a device/app integrity attestation token issued by Google; it does not identify you. Because the App uses Firebase Anonymous Authentication, Google's authentication library is bundled with the App; the App never asks you to sign in to any account and does not use the library's sign-in, federated-identity or reCAPTCHA features.

#### f) Google Play In-App Review

The App may occasionally show Google Play's own in-app review prompt. The review you write (if any) is submitted directly to Google Play and is governed by Google's terms; the App is not told whether you left a review or what it said. Where analytics is enabled, we record only that the prompt was shown.

#### g) Google Mobile Ads SDK (present, not used)

The App currently includes the Google Mobile Ads SDK as a software dependency, but **it is never initialised, no advertisements are requested or displayed, and no data is collected for advertising purposes.** Its presence is why the advertising-related permissions listed in Section 9 appear in the App's manifest. Should we ever enable advertising, Section 12 applies.

### 1.4 Backup Files You Create

If you are a PRO subscriber, you can use the in-app **"Back up & transfer your progress"** feature to export your learning data (including the optional name, progress, streaks, saved cards, and achievements) to a single JSON file. You choose where this file is saved using your device's system file picker. **We do not receive, store, or have access to this file** — it remains entirely under your control. Where you save it (for example, to a personal cloud-storage location) and how it is protected is your decision.

---

## 2. How We Use Information

We use information for the following purposes:

| Purpose | Data Used | Legal Basis (GDPR Art. 6) |
|---------|-----------|---------------------------|
| Providing core App functionality (lessons, scoring, spaced-repetition scheduling, progress tracking, streaks, achievements) | Learning data stored locally on your device | Performance of a contract (Art. 6(1)(b)) |
| Saving and restoring your preferences, settings, and optional name | Preferences stored locally on your device | Performance of a contract (Art. 6(1)(b)) |
| Delivering the daily reminder notifications you request | FCM token, time zone, chosen reminder times, brand identifier, anonymous identifier | Consent (Art. 6(1)(a)) — given when you enable reminders and the notification permission |
| Measuring app usage to improve features (Firebase Analytics) | Individual usage events and profile attributes, app-instance ID, device/technical info, IP address (approximate location), install referrer, Advertising ID | Consent (Art. 6(1)(a)) in the EEA, UK and Switzerland, obtained via the in-app consent dialog; elsewhere, legitimate interest in understanding and improving the App (Art. 6(1)(f)) or the equivalent basis under local law |
| Detecting and fixing crashes and technical errors (Firebase Crashlytics) | Crash logs, device state, technical info | As above |
| Processing subscriptions and trials, and verifying entitlement | Purchase data processed by Google Play | Performance of a contract (Art. 6(1)(b)) |
| Protecting our reminder backend from abuse | Firebase App Check attestation token, IP address | Legitimate interest (Art. 6(1)(f)) — security and integrity |

We do **not** use any information for:

- Advertising or ad personalization (the App displays no advertisements)
- Selling personal information (as defined under CCPA/CPRA)
- Profiling or automated decision-making that produces legal or similarly significant effects (GDPR Art. 22)
- Direct marketing or email campaigns
- Cross-app or cross-device tracking

---

## 3. Consent and Your Controls

**EEA, UK and Switzerland.** If you are located in the European Economic Area, the United Kingdom, or Switzerland, the App presents a consent dialog (powered by the Google UMP SDK) on first launch. **Firebase Analytics and Firebase Crashlytics collection remains disabled until you grant consent.** If you decline, the App continues to work fully and no analytics or crash-reporting data is collected. You can review or change your consent choice at any time through **Settings → "Privacy & ad settings"**; this option is shown to users in the EEA, the UK and Switzerland, where consent is legally required.

**Everywhere else.** Analytics and crash reporting are enabled when you first open the App, as permitted by applicable law. If you want us to stop collecting analytics and crash data for your installation, email us at [uplyfire@gmail.com](mailto:uplyfire@gmail.com) and we will disable it and delete the data associated with your installation using Firebase's data-deletion tools, or you can uninstall the App. Resetting your Advertising ID (Android Settings → Google → Ads) limits identifier-based measurement but does not stop event collection.

Reminder notifications are always opt-in: they are delivered only if you grant the Android notification permission and enable reminders in the App.

---

## 4. Third-Party Services

Scrollish relies on the following third-party services, all provided by Google LLC:

| Service | Provider | Purpose | Privacy Policy |
|---------|----------|---------|----------------|
| Firebase Analytics | Google LLC | App-usage measurement (consent-gated in the EEA/UK/Switzerland) | [Google Privacy Policy](https://policies.google.com/privacy) |
| Firebase Crashlytics | Google LLC | Crash and error diagnostics (consent-gated in the EEA/UK/Switzerland) | [Google Privacy Policy](https://policies.google.com/privacy) |
| Firebase Cloud Messaging | Google LLC | Delivery of reminder notifications | [Google Privacy Policy](https://policies.google.com/privacy) |
| Firebase Cloud Functions + Firestore | Google LLC | Scheduling of reminder notifications | [Google Privacy Policy](https://policies.google.com/privacy) |
| Firebase Authentication (Anonymous) | Google LLC | Anonymous identifier for the reminder backend | [Google Privacy Policy](https://policies.google.com/privacy) |
| Firebase App Check (Play Integrity) | Google LLC | Backend abuse and integrity protection | [Google Privacy Policy](https://policies.google.com/privacy) |
| Google Play Billing | Google LLC | Subscription and trial processing | [Google Play Terms](https://play.google.com/about/play-terms/) |
| Google Play In-App Review | Google LLC | Showing the optional in-app "rate this app" prompt | [Google Play Terms](https://play.google.com/about/play-terms/) |
| Google Play Services | Google LLC | Core app infrastructure | [Google Privacy Policy](https://policies.google.com/privacy) |
| Google User Messaging Platform (UMP) | Google LLC | Consent management (EEA/UK/Switzerland) | [Google Privacy Policy](https://policies.google.com/privacy) |

We do not share your information with any other third parties, data brokers, advertising networks, or analytics providers.

**Data Processing Agreements:** Our use of Google and Firebase services is governed by Google's data processing terms, including the [Firebase Data Processing and Security Terms](https://firebase.google.com/terms/data-processing-terms) and the [Google Ads Data Processing Terms](https://privacy.google.com/businesses/processorterms/) (where applicable), together with the transfer mechanisms described in Section 10. For the services above, Google acts as a data processor (service provider) on our behalf, and as an independent data controller for its own purposes as described in Google's privacy policy.

---

## 5. Subscriptions and In-App Purchases

Scrollish offers an auto-renewing premium subscription ("Scrollish PRO"):

- **Monthly** and **annual** subscription plans
- A short **free trial** at the start of the subscription, where offered

A portion of the App's content is available for free; PRO unlocks the full course, PRO colour themes, the progress backup-and-transfer feature, and additional streak shields.

All purchases and subscriptions are processed by **Google Play**. We do not collect, process, or store your payment information. Subscriptions are tied to your Google Account and renew automatically until cancelled. You can manage or cancel your subscription at any time via **Settings → "Manage subscription in Google Play"** or directly in the Google Play Store. You can restore an existing purchase via **Settings → "Restore purchases."**

Refunds are governed by [Google Play's refund policy](https://support.google.com/googleplay/answer/2479637). Pricing, billing, and cancellation terms are described in our [Terms of Service](terms.md).

---

## 6. Data Storage and Security

### 6.1 Local Storage

Your learning data, preferences, and optional name are stored locally on your device using:

- A **SQLite database** (via the Room library) for learning progress, sessions, streaks, saved cards, achievements, and preferences
- **App preference files** written by the Google libraries the App uses (for example your stored consent choice). These are also excluded from Android's automatic backup — see Section 6.3

Apart from the reminder-scheduling information (Section 1.3(b)), the analytics and crash data described in Section 1.3(a), and any backup file you choose to create (Section 1.4), this data does not leave your device through the App.

### 6.2 Security Measures

- All local data is stored in the App's private storage directory, inaccessible to other applications
- All network communication uses encrypted connections (HTTPS/TLS)
- Requests to our reminder backend are protected by Firebase App Check, and our database rules deny all direct client access
- Analytics and crash reporting are disabled until consent is granted where consent applies
- The App does not load or execute remote scripts or code; learning content (text, images, audio) is bundled with the App

### 6.3 Android Auto Backup

The App **excludes** its database and preferences from Android's automatic cloud backup and device-transfer features. This means your learning data is not automatically copied to your Google Account by the operating system. To move your progress to a new device, use the in-app backup-and-transfer feature described in Section 1.4 (available to PRO subscribers).

---

## 7. Data Retention and Deletion

### 7.1 Retention

Your learning data is retained on your device for as long as you keep the App installed and do not delete it. We do not retain this data on our servers.

The reminder-scheduling record described in Section 1.3(b) is kept for as long as it is needed to deliver your reminders. It is deleted immediately when you turn reminders off in the App or when you ask us to delete it (Section 7.2). If your device stops accepting notifications (for example because you uninstalled the App without turning reminders off), the record is marked inactive and is no longer used to deliver reminders; it is not currently deleted automatically, so we recommend turning reminders off before uninstalling, or emailing us. We hold no other data about you on our servers.

Analytics and crash data are retained by Google Firebase according to its retention settings (currently up to 14 months for event data) and can be deleted on request as described in Section 3.

### 7.2 Deleting Your Data

You may delete your data at any time:

- **Delete all in-app data:** Open **Settings → "Delete all data"** and confirm in the dialog. This permanently deletes all your progress, streaks, XP, achievements, saved cards, reminders and settings, and the optional name, from your device. It does not by itself delete the reminder-scheduling record described in Section 1.3(b); to delete that record, turn reminders off in Settings → Notifications, or email us.
- **Turn off reminders:** Disabling reminders in **Settings → Notifications** instructs our backend to delete the reminder-scheduling record for your device.
- **Clear app data:** Android Settings → Apps → Scrollish → Storage → Clear Data.
- **Uninstall the App:** Removes all locally stored data from your device and stops reminder delivery. Uninstalling does **not**, by itself, delete the reminder-scheduling record on our backend. To delete that record, turn reminders off (Settings → Notifications) before uninstalling, or email us (see below).
- **By email request:** You may contact us at [uplyfire@gmail.com](mailto:uplyfire@gmail.com). For the reminder-scheduling record and for analytics and crash data associated with your installation, we will delete them on request and confirm when it is done; for data stored only on your device, we will guide you through the methods above. We will respond to deletion requests within 30 days.

### 7.3 Web-Based Data Deletion Request (Google Play Requirement)

In accordance with Google Play's data deletion policy, you may also review the deletion process and submit a request via our website at: **https://uplyfire.github.io/legal/scrollish/data-deletion**

Purchase and subscription history managed by Google Play cannot be deleted through the App; to review it, visit [Google Play Order History](https://play.google.com/store/account/orderhistory). Google's own data controls are available at [Google Account settings](https://myaccount.google.com/data-and-privacy).

---

## 8. Children's Privacy

Scrollish is an educational application intended for a **general audience aged 13 and over**. It is **not directed to children under the age of 13**, and we do **not** knowingly collect personal information from children under 13 (or the applicable age of digital consent in your jurisdiction). Our Google Play "Target audience" declaration is 13 years and over; the App is not enrolled in Google Play's Designed for Families programme and does not present itself as a children's app.

The App does not:

- Require account creation or registration
- Collect names, email addresses, or other personal identifiers (the optional in-app name is stored only on the device and is never transmitted to us)
- Enable communication between users
- Display advertising

If you are a parent or guardian and believe a child under 13 has provided personal information through the App, please contact us at [uplyfire@gmail.com](mailto:uplyfire@gmail.com) so we can take appropriate action.

**Age of digital consent by jurisdiction:** For users in the EEA, the age of digital consent varies by member state (13–16 years under GDPR Art. 8). For users in Brazil, parental consent is required for processing data of children under 12 (LGPD Art. 14). If you are under the applicable age of consent in your jurisdiction, you must have a parent or legal guardian's permission to use the App, and a parent or guardian must make any consent decision (such as enabling analytics) on your behalf.

---

## 9. Permissions

The App's manifest declares the following Android permissions. The first four are declared by the App itself; the rest are declared by the Google libraries bundled in the App and merged into the manifest automatically.

| Permission | Purpose | Required? |
|------------|---------|-----------|
| `INTERNET` | Connecting to Google Play (purchases) and Firebase (reminders; analytics and crash reporting where enabled). Not used to transmit the content of your lessons, cards or answers; where analytics is enabled, numeric usage measurements are transmitted as described in Section 1.3(a). | Yes |
| `ACCESS_NETWORK_STATE` | Detecting network connectivity. | Yes |
| `POST_NOTIFICATIONS` | Showing the daily reminder notifications you opt into (Android 13+). | Optional — requested only if you enable reminders |
| `RECEIVE_BOOT_COMPLETED` | Re-scheduling your reminders after the device restarts. | Yes (used only if you enable reminders) |
| `WAKE_LOCK`, `FOREGROUND_SERVICE` | Allowing a reminder to be prepared and posted reliably when the device is idle (declared by the Firebase Cloud Messaging and WorkManager libraries). The App does not run foreground services. | Yes |
| `com.android.vending.BILLING`, `com.google.android.c2dm.permission.RECEIVE`, `READ_GSERVICES` | Google Play purchases, push-message delivery, and Google Play Services infrastructure (declared by the respective Google libraries). | Yes |
| `BIND_GET_INSTALL_REFERRER_SERVICE`, `ACCESS_ADSERVICES_AD_ID`, `ACCESS_ADSERVICES_ATTRIBUTION`, `ACCESS_ADSERVICES_TOPICS` | Declared by Google's measurement and Mobile Ads libraries. Where analytics is enabled, Google may read the Google Play **install referrer** (which store campaign or link led to your install) for install attribution. The App shows no advertisements and uses none of these for advertising. | Yes (used only where analytics is enabled) |

All of the above are **normal** permissions granted at install time; none of them prompts you, and none gives the App access to your files, location, contacts, camera or microphone. `POST_NOTIFICATIONS` is the only runtime permission the App requests. The App does **not** request access to location, camera, microphone, contacts, storage, phone state, SMS, or Bluetooth.

**Advertising ID (`com.google.android.gms.permission.AD_ID`):** This permission is declared by Google libraries bundled in the App — the Google Mobile Ads SDK (present as a dependency although no ads are shown, see Section 1.3(g)) and Google's measurement library — and is merged into the App's manifest automatically. Where analytics is enabled, Firebase Analytics may use the Android Advertising ID for measurement purposes. You can reset or delete your Advertising ID, or opt out of its personalization, in your device settings: Android Settings → Google → Ads. The App does **not** use the Advertising ID for advertising, as it displays no ads.

---

## 10. International Data Transfers

The reminder-scheduling record described in Section 1.3(b) is stored in Google Cloud Firestore in the **`europe-west1` region (Belgium, European Union)**, and the function that writes it runs in the same region. Push-message delivery (Firebase Cloud Messaging) and, where enabled, Firebase Analytics and Crashlytics are global Google services and involve processing on Google infrastructure outside the European Economic Area, **including in the United States**.

For transfers of personal data from the European Economic Area (EEA), the United Kingdom (UK), or Switzerland to countries without a European Commission adequacy decision, Google relies on the following:

- the **EU–U.S. Data Privacy Framework**, its UK Extension and the Swiss–U.S. Data Privacy Framework, under which Google LLC is certified;
- **Standard Contractual Clauses (SCCs)** approved by the European Commission, where the Framework does not apply;
- the **UK International Data Transfer Addendum** where applicable;
- additional technical and organisational safeguards as described in [Google's Data Transfer Frameworks documentation](https://policies.google.com/privacy/frameworks).

You can obtain a copy of the applicable safeguards by contacting us (Section 15). For transfers from Brazil, Google maintains compliance with LGPD requirements for international data transfers (LGPD Art. 33).

---

## 11. Your Rights

Depending on your jurisdiction, you may have the following rights regarding your data. Because your learning data is stored locally on your device, most of these rights are exercisable directly through the in-app data controls (Section 7) and your device settings. For data processed by Firebase, we will act on your request as described in Sections 3 and 7, and you may also exercise rights directly with Google.

### 11.1 GDPR Rights (European Economic Area and United Kingdom)

If you are located in the EEA or UK, you have the following rights under the GDPR (and UK GDPR):

- **Right of access (Art. 15)** — Request a copy of the personal data we process about you
- **Right to rectification (Art. 16)** — Correct inaccurate or incomplete personal data
- **Right to erasure (Art. 17)** — Request deletion of your personal data (see Section 7)
- **Right to restrict processing (Art. 18)** — Limit how your personal data is processed
- **Right to data portability (Art. 20)** — Receive your personal data in a structured, commonly used, machine-readable format. PRO subscribers can export their learning data to a JSON file via the in-app backup feature; regardless of whether you subscribe, you may also request your data from us at no charge using the contact details in Section 15
- **Right to object (Art. 21)** — Object to processing based on legitimate interest
- **Right to withdraw consent (Art. 7(3))** — Withdraw consent for analytics and crash reporting at any time via Settings → "Privacy & ad settings" (EEA, UK and Switzerland), and for reminders by disabling them in Settings → Notifications, without affecting the lawfulness of processing before withdrawal
- **Right to lodge a complaint (Art. 77)** — Lodge a complaint with your local data protection supervisory authority. In Poland this is the President of the Personal Data Protection Office (Prezes Urzędu Ochrony Danych Osobowych, UODO, [https://uodo.gov.pl/](https://uodo.gov.pl/)). A list of EEA supervisory authorities is available at [https://edpb.europa.eu/about-edpb/about-edpb/members_en](https://edpb.europa.eu/about-edpb/about-edpb/members_en); in the UK, the Information Commissioner's Office ([https://ico.org.uk/](https://ico.org.uk/))

**Data Protection Officer:** Given the nature and scale of our data processing activities, we are not required to appoint a Data Protection Officer under GDPR Art. 37. For all privacy-related inquiries, please contact us using the details in Section 15.

### 11.2 CCPA/CPRA Rights (California Residents)

We extend the following rights to California residents voluntarily, whether or not we meet the CCPA's "business" thresholds:

- **Right to know (Cal. Civ. Code § 1798.100)** — Request disclosure of the categories and specific pieces of personal information collected, the sources, the purposes, and the categories of third parties with whom it is shared
- **Right to delete (§ 1798.105)** — Request deletion of personal information we have collected
- **Right to correct (§ 1798.106)** — Request correction of inaccurate personal information
- **Right to opt-out of sale or sharing (§ 1798.120)** — We do not sell or share personal information, so there is nothing to opt out of; see below
- **Right to limit use of sensitive personal information (§ 1798.121)** — We do not collect sensitive personal information as defined by the CPRA (the IP-derived location described in Section 1.3(a) is approximate, not precise geolocation)
- **Right to non-discrimination (§ 1798.125)** — Not be discriminated against for exercising your privacy rights

**Sale and Sharing of Personal Information:** Scrollish does **not** "sell" or "share" personal information as those terms are defined under the CCPA/CPRA. The App displays no advertising and engages in no cross-context behavioral advertising. To submit a verifiable consumer request, contact us at the email address in Section 15. We will respond within 45 days, and will tell you if we need a further 45 days as permitted by § 1798.130(a)(2).

**California "Shine the Light" (Cal. Civ. Code § 1798.83):** We do not disclose personal information to third parties for their direct marketing purposes.

### 11.3 LGPD Rights (Brazilian Residents)

If you are located in Brazil, you have the rights set out in Art. 18 of the Lei Geral de Proteção de Dados (LGPD, Law No. 13,709/2018), including confirmation of processing, access, correction, anonymization/blocking/deletion, portability, information about sharing, information about consent, and revocation of consent.

**Legal basis for processing under LGPD:** Reminder notifications are based on your consent (Art. 7(I)). Analytics and crash reporting are based on our legitimate interest in understanding and improving the App (Art. 7(IX)), and you may object at any time and have collection stopped as described in Section 3. Processing for subscriptions is based on contractual necessity (Art. 7(V)). Backend integrity protection is based on legitimate interest (Art. 7(IX)).

To exercise your LGPD rights, contact us at the email address in Section 15. Where you request access to or confirmation of processing, we will respond in simplified form immediately where practicable and in complete form within the 15 days required by Art. 19 of the LGPD.

---

## 12. Future Changes to Data Practices

We may in the future add features that change what data the App collects — for example advertising to support a free tier, one-time in-app purchases of additional content, or additional measurement services.

**If and when we do, we will, before the change takes effect:**

1. Update this Privacy Policy and describe exactly what additional data is collected and why;
2. Update the Google Play Data safety declaration to match;
3. Where the change relies on consent (such as personalised advertising), obtain that consent through an appropriate consent mechanism;
4. Describe the change in the Google Play Store listing where appropriate.

No data collection beyond what is described in Sections 1–4 of this Privacy Policy will occur without a published update to this policy.

---

## 13. EU Digital Services Act (DSA) Disclosures

For users in the European Union, in accordance with Regulation (EU) 2022/2065 (the Digital Services Act):

- **Advertising transparency:** The App displays no advertisements. Should advertising be introduced in the future, we will provide the transparency information required by the DSA at that time.
- **Recommender systems:** Scrollish does not use profiling-based recommender systems. The order in which learning cards are presented is determined by a spaced-repetition algorithm based on your own answers and review schedule on your device, not by profiling for commercial purposes.
- **Content moderation:** Scrollish does not host user-generated content and therefore does not perform content moderation.
- **Trader information:** We act as a trader when offering the PRO subscription. Our identity and contact details are set out in Section 15 and on the Google Play listing.
- **Point of contact:** For DSA-related inquiries, please contact us at [uplyfire@gmail.com](mailto:uplyfire@gmail.com) (see Section 15).

---

## 14. Changes to This Privacy Policy

We may update this Privacy Policy from time to time to reflect changes in our practices, technology, legal requirements, or other factors. When we make changes:

- **For all updates:** We will update the "Last Updated" date and Policy Version number at the top of this document
- **For material changes** (new data collection, new third-party services, changes to data sharing): We will publish the updated policy at this address with a new version number and Effective Date, and describe the change in the Google Play Store listing's release notes, before the changes take effect
- **For non-material changes** (clarifications, formatting, updated links): Changes take effect upon posting

Where changes affect processing activities that rely on your consent, we will seek your renewed consent before applying the changes. For other changes, your continued use of the App after changes are posted constitutes your acknowledgment of the revised policy, to the extent permitted by applicable law.

---

## 15. Contact Us

If you have any questions, concerns, or requests regarding this Privacy Policy or our data practices, please contact us at:

**Controller / trader**
Uplyfire — [FULL LEGAL NAME OF THE SOLE TRADER]
[STREET, POSTAL CODE, CITY], Poland
[NIP / REGON, if registered]
Email: [uplyfire@gmail.com](mailto:uplyfire@gmail.com)

We are a sole trader — a natural person acting in the course of a business — established in Poland, and we are the data controller for the processing described in this policy. You may also contact us through the developer contact information listed on the [Scrollish Google Play Store listing](https://play.google.com/store/apps/details?id=com.scrollish.android).

We aim to respond to all privacy-related inquiries within 30 days. For GDPR-related requests, we will respond within one month as required by Art. 12(3). For CCPA/CPRA requests, we will respond within 45 days (extendable once by 45 days with notice). For LGPD access and confirmation requests, within 15 days as required by Art. 19 of the LGPD.

---

## 16. Google Play Data Safety Summary

In accordance with Google Play requirements, the following summarizes our data practices as declared in the Data Safety form for the current version of the App. **The App displays no advertisements; no data is collected or shared for advertising purposes.**

| Data Category | Data Type | Collected? | Shared? | Purpose | Optional? |
|---------------|-----------|------------|---------|---------|-----------|
| App activity | App interactions / usage events (see Section 1.3(a)) | Yes (Firebase Analytics) | No | Analytics | Consent-gated in the EEA/UK/Switzerland; enabled by default elsewhere (see Section 3) |
| App info and performance | Crash logs, diagnostics | Yes (Firebase Crashlytics, Firebase Analytics) | No | Analytics / app stability | As above |
| Location | Approximate location derived by Google from the IP address | Yes (Firebase Analytics) | No | Analytics | As above |
| Financial info | Purchase/subscription history (plan, price, currency, trial and renewal events) | Yes — by Google Play for the transaction, and by Firebase Analytics where analytics is enabled | No | App functionality; analytics | Transaction: only if you purchase; analytics portion: as above |
| Device or other IDs | App-instance ID, Firebase installation ID, Crashlytics installation ID, Advertising ID (AAID), anonymous Firebase identifier, FCM push token, App Check attestation token | Yes | No | App functionality; analytics; fraud prevention, security and compliance | Required for the features in use (reminder-related identifiers only if reminders are enabled) |
| App activity | Reminder schedule and time zone | Yes (reminder backend) | No | Reminder notifications | Yes — only if reminders enabled |
| App activity | Learning content, progress, streaks, saved cards, achievements | Stored locally only — not collected by us (numeric measurements are reported as "App interactions" above) | No | App functionality | No |
| Personal info | Name / nickname | Stored locally only — not collected by us | No | App functionality | Yes — optional |

**On "sharing":** Google acts as our **service provider (processor)** for Firebase Analytics, Crashlytics, Cloud Messaging, Cloud Functions, Firestore, Anonymous Authentication and App Check, processing data only on our instructions under the [Firebase Data Processing and Security Terms](https://firebase.google.com/terms/data-processing-terms). Under Google Play's Data safety definitions, a transfer to a service provider is **not** "sharing", which is why these rows are marked "No". Google separately processes some data as an independent controller for its own purposes, as described in [Google's Privacy Policy](https://policies.google.com/privacy). We do not transfer your data to any other organisation.

**Data handling declarations:**
- **Encryption in transit:** Yes — all network communication uses HTTPS/TLS
- **Data deletion:** Users can delete local data in-app (Settings → "Delete all data"), clear app data, or uninstall; the reminder-scheduling record is deleted when reminders are turned off or on request; analytics and crash data associated with an installation are deleted on request. A web-based deletion request is available at https://uplyfire.github.io/legal/scrollish/data-deletion
- **Data is not sold or shared for advertising:** We do not sell user data and display no advertising
- **Account creation:** The App has no user accounts

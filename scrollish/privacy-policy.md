# Privacy Policy

**Last Updated:** [PUBLICATION DATE]
**Effective Date:** [PUBLICATION DATE]
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
12. [EU Digital Services Act (DSA) Disclosures](#12-eu-digital-services-act-dsa-disclosures)
13. [Changes to This Privacy Policy](#13-changes-to-this-privacy-policy)
14. [Contact Us](#14-contact-us)
15. [Google Play Data Safety Summary](#15-google-play-data-safety-summary)

---

Uplyfire ("we," "us," or "our") operates the Scrollish mobile application (the "App"), an application for learning English. Uplyfire is the trading name of the person identified in Section 14, who is the data controller for the processing described in this policy. This Privacy Policy describes how we collect, use, store, and protect information when you use the App. Please read it carefully.

This policy is designed to comply with applicable data protection laws, including the General Data Protection Regulation (GDPR), the UK GDPR, the Swiss Federal Act on Data Protection, the California Consumer Privacy Act as amended by the California Privacy Rights Act (CCPA/CPRA) where it applies, the Brazilian General Data Protection Law (Lei Geral de Proteção de Dados, LGPD), and the Google Play Developer Program Policies.

**Summary of our approach:** Scrollish does not require an account, and we do not ask for your email address, phone number or location. The content of what you study — card text, questions, the text of your answers — and the optional name you choose are stored **on your device** and are never uploaded to us by the App. What does leave your device is limited to:

- **Technical identifiers:** on every installation, a Firebase installation identifier and basic technical information, sent so the App can receive operational settings from us, such as switching off a feature that does not work correctly (Section 1.3(f)), and a push token that Google's messaging library creates when the App starts (Section 1.3(b));
- **Reminder record:** while notifications are allowed for the App, a small record on our server used to deliver your reminder notifications (Section 1.3(b));
- **Purchases:** if you buy PRO, what Google Play needs for the purchase and the order information it shows us (Section 1.3(c));
- **Usage data:** analytics, crash reports and performance measurements processed by Google Firebase, which include pseudonymous events about how you use the App (for example the lesson you reached, which card you answered and whether the answer was correct) — collected only with your consent in the EEA, the UK and Switzerland, and enabled by default elsewhere; you can turn them off at any time with the **"Share anonymous usage data"** switch in Settings (Section 3);
- **IP address:** your device's IP address, which necessarily reaches Google's servers whenever the App connects to them;
- **Android backup:** if you use Android's backup, a copy of the App's progress database in your own Google Account (Section 6.3).

The App displays **no advertisements** and collects no data for advertising purposes.

---

## 1. Information We Collect

### 1.1 Information We Do NOT Collect

Scrollish does **not** collect, request, or process:

- Your email address, phone number, mailing address, or date of birth (unless you email us yourself — see Section 1.6)
- Your real-world identity or government identifiers
- Precise or GPS location. The App has no location permission and never requests your position. Where analytics is enabled, Google derives an **approximate, city- or region-level location from your IP address** for reporting purposes, as described in Section 1.3(a); we cannot see your address or precise position
- Contacts, calendar, or phone data
- Photos, files, or media from your device (apart from a backup file you explicitly choose to restore, Section 1.4)
- Microphone or camera input (the App has no speech recognition, recording, or camera features)
- Biometric data
- Health or fitness data
- Payment information (credit/debit card numbers, bank accounts) — handled entirely by Google Play
- Browsing history or activity in other apps
- Social media profiles or credentials
- Hardware device identifiers such as IMEI or IMSI

### 1.2 Information You Provide and Information Stored Locally on Your Device

The following information is created as you use the App and is stored **on your device**. We do not upload the content of what you study: no card text, no questions and no text of your answers ever leaves your device through the App.

When analytics is enabled (Section 1.3(a)), the App sends **pseudonymous events tied to your installation**, derived from this data: the lesson, your accuracy, experience points (XP), your streak and level, the card type, the card's identifier and version, whether an answer was correct, and the card's learning state before you answered it or hid it. A crash report contains the card that was on screen when the App crashed. Apart from these events — which can also report what you do with the data below, for example that you saved a card (with its identifier) or which daily goal you chose — the list below stays on your device, except for the copy that Android's backup can keep in your own Google Account (Section 6.3):

- **Optional name or nickname.** In Settings → Account ("Your name") you may enter a name or nickname so the App can greet you. It is optional and the App works fully without it. The name is never sent to us. It is included in Android's backup of the App's database (Section 6.3) and in any backup file you create (Section 1.4).
- **Learning progress.** Per-card learning state used by the spaced-repetition algorithm (for example card status, review intervals, ease factors, number of correct and incorrect attempts) and the lessons you have completed.
- **Activity and gamification data.** Learning sessions, daily streaks, daily activity totals (cards answered, minutes, experience points), streak shields, and unlocked achievements.
- **Saved cards and card reports.** Identifiers of cards you bookmark, and of cards you reported as containing an error (with the time of the report).
- **Preferences and settings.** Your daily goal, notification settings and reminder times, theme and colours, audio autoplay, sound and haptics settings, and onboarding state.
- **Technical state.** For example your analytics choice, a short history of the notifications already shown (so the same reminder is not repeated), and a random technical token the App uses to recognise its own database.

This data is stored in a local database (SQLite via the Room library) and remains under your direct control.

### 1.3 Information Collected and Transmitted by Integrated Services

To provide certain features, Scrollish integrates the following Google and Firebase services. Each is described below, including what it processes and when.

#### a) Firebase Analytics, Firebase Crashlytics and Firebase Performance Monitoring

We use **Firebase Analytics** to understand how the App is used so we can improve it, **Firebase Crashlytics** to detect and diagnose crashes and technical errors, and **Firebase Performance Monitoring** to measure how quickly the App starts and loads cards. The three services are controlled together by one decision (Section 3):

- **EEA, UK and Switzerland:** these services are off until you give consent in the in-app consent dialog (except in the case described in the next paragraph). If you decline, they stay off and no analytics, crash-reporting or performance data is collected or transmitted.
- **Everywhere else:** these services are enabled when you first open the App, on the basis of our legitimate interest in understanding and improving the App (Section 2).
- **Everywhere:** you can turn them off, or back on, at any time with the **"Share anonymous usage data"** switch in Settings → About.

If the consent dialog cannot be loaded the first time you open the App (for example because you are offline), the App cannot tell whether consent is required where you are. In that case these services run as they do outside the EEA until the App next starts with an internet connection; the consent dialog is then shown where it applies, and your answer replaces that setting.

When enabled, these services process:

- **Individual app-usage events**, each recorded against a pseudonymous app-instance identifier, with mechanic-level parameters. These include: screens opened; feed tabs selected; sessions (batches of cards) started; lessons completed, with the lesson's identifier and number, number of cards, accuracy percentage and XP earned; each card answered, skipped, revealed, saved, marked as too easy or not interesting, or reported — with the card type, the card's identifier and content version, whether the answer was correct, whether the card was new, and the card's learning state (for example new, learning or mastered) before the answer or hide; streak milestones, daily goals met and streak-shield use; onboarding steps and your chosen daily goal; paywall views and the steps of a purchase (the plan, price and currency, trial start, conversion and cancellation, and technical error codes); notification events (shown, opened, dismissed, suppressed, and whether you allowed notifications); settings actions (for example a theme chosen, a backup exported or restored, or that a name was changed — never the name itself); the rating you choose on the end-of-free-content page; and whether the in-app review prompt was shown. Google Analytics also records some events automatically, such as the first open of the App, app updates and in-app purchases.
- **Persistent profile attributes** attached to that pseudonymous identifier: your level, tier, subscription status, current streak length and daily goal.
- A pseudonymous **app-instance identifier** generated by Firebase, the **Firebase installation identifier**, and the **Crashlytics installation identifier**.
- **Device and technical information** (device model, operating system version, language, region, app version, and for performance measurements also network type and mobile carrier).
- **Your IP address**, from which Google derives an approximate (city- or region-level) location for reporting; Google does not give us the raw address (see Sections 1.1 and 10).
- The **Google Play install referrer** (which store campaign or link led to your install), which Google's measurement library may read for install attribution.
- **Crash logs, stack traces and device state** at the time of a crash (Crashlytics), together with technical context we attach, for example the screen that was open, the card on screen (its identifier, type and version), the content version, the active tab or mode, whether the App was in the foreground, your level and whether you have a subscription, and a short trail of the App's recent analytics events.
- **Performance measurements** (Performance Monitoring): how long the App took to start and to show its first card, how long a batch of cards took to load and whether it loaded, and the standard measurements the Performance Monitoring library takes itself, such as app start and screen rendering times.
- The **Android Advertising ID (AAID)**, which Google's measurement library may collect for analytics measurement. It is not used for advertising (see Sections 1.3(d) and 9).

We do **not** transmit the content of your learning material — no card text, no questions, no text of your answers, no notes — and we never send your name. We do not use this data to identify you by name, and we do not ask Google to link it to any account. This data is **pseudonymous rather than anonymous**: it is tied to identifiers of your installation and, taken together, describes the learning behaviour of a single installation.

#### b) Reminder Notifications — Firebase Cloud Messaging and Cloud Functions

The App's reminders (for example about your streak, your daily goal or cards that are due for review) are delivered through our reminder service, which is built on **Firebase Cloud Messaging (FCM)**, **Firebase Cloud Functions**, **Firebase Anonymous Authentication**, and **Firebase App Check**.

Google's messaging library creates a push token (an FCM registration token) for the App when the App starts, on every installation; creating it involves Google's servers, not ours. The App registers your device with our reminder service — and only then sends the token to our backend — when notifications are allowed for the App and are switched on in Settings → Notifications ("All notifications", on by default). On Android 13 and later, notifications are allowed only after you grant the notification permission. On Android 12 and earlier, Android allows an app's notifications unless you turn them off, so the App registers when you first use it. The App refreshes the registration when you use it (at most about once a day) and when the push token, the time zone or the device clock changes.

The following information is sent to and stored in our backend (Google Cloud Firestore, `europe-west1` region), keyed to an **anonymous, randomly generated Firebase identifier** that is not linked to your real identity:

- The **FCM registration token** for your device (a device-specific push identifier)
- A **brand identifier** indicating which of our apps you are using (for example "english")
- Your device's **time zone**
- The **local times** of your reminders and the next scheduled time for each
- Delivery-health information (whether the last delivery worked, the number of failed attempts) and the time of the last update
- A retention date, after which the record is deleted automatically (Section 7.1)

To limit abuse, the service also keeps, under the same anonymous identifier, the times of your recent registration requests for 24 hours.

Your IP address reaches Google when the App calls this service. **We do not send your name, your learning progress, your email, or any content you study to this backend.** The record exists solely to schedule and deliver your reminders. The notifications themselves are generated on your device from text bundled in the App; no server selects or personalizes their content based on your activity.

The record is deleted when you turn notifications off in Settings → Notifications (if you turn them off in Android's settings instead, the next time you open the App) or when you use **"Delete all data"**, which also deletes the anonymous Firebase account (Section 7.2). If you uninstall the App without doing either, the record is deleted automatically 90 days after the App last refreshed it. Copies can remain in our database backups for a limited time (Section 7.1).

#### c) Google Play Billing

When you start a free trial or purchase a subscription, the transaction is processed entirely by **Google Play**. We do not collect or store your payment information. Google Play processes:

- Purchase and subscription records for the App (product identifiers, purchase tokens, timestamps, subscription status)
- The Google Account information necessary to process the transaction

The App receives from Google Play only the information needed to determine your entitlement (whether you have an active subscription or trial), and checks it on your device, where it also keeps a short record of your purchases (for example when a trial ends). When you start a purchase, the App gives Google Play a random identifier derived from this installation (an "obfuscated account ID"), so that the purchase can be matched to the installation that made it; it does not identify you. In the Google Play Console we see order information for our sales — such as the order number, product, price, date and status, the buyer's country and, in sales reports, region and postal code — which we need for our accounts. Where analytics is enabled, the App also records the **fact and shape** of a purchase — which plan, the price and currency, and whether a trial started, converted or was cancelled — as described in Section 1.3(a). Firebase Analytics also logs purchase and subscription events automatically (product identifier, product name and price), and because our Google Play and Firebase accounts are linked, Google Analytics also receives in-app purchase and subscription data from Google Play for our reports. We never receive your payment method or card details. For more information, see [Google Play's Terms of Service](https://play.google.com/about/play-terms/).

#### d) Google User Messaging Platform (UMP) and Google Mobile Ads SDK

We use the **Google UMP SDK** to present the consent dialog to users in the EEA, the UK and Switzerland and to record their choices (Section 3). On each launch, UMP contacts Google to find out whether consent is required where you are (based on your IP address) and, where it is, to load the consent form. Your consent choice is stored on your device.

The App also contains the **Google Mobile Ads SDK** as a software dependency, but in the current version of Scrollish **the App never initialises it, never requests or displays advertisements, and collects no data for advertising purposes.** Only the SDK's own start-up component runs when the App opens, without loading any ads. The Mobile Ads SDK and Google's measurement library are the reason the advertising-related permissions listed in Section 9, including the Advertising ID permission, appear in the App's manifest. Should we ever show advertising, we will update this policy first (Section 13).

#### e) Google Play Services, Firebase App Check and the Google authentication library

The App relies on **Google Play Services** for core infrastructure and uses **Firebase App Check (Play Integrity)** to verify that requests to our reminder backend come from a genuine, untampered instance of the App. App Check processes a device and app integrity attestation token issued by Google; it does not identify you. Because the App uses Firebase Anonymous Authentication, Google's authentication library is bundled with the App; the App never asks you to sign in to any account and does not use the library's sign-in, federated-identity or reCAPTCHA features.

#### f) Firebase Remote Config

The App uses **Firebase Remote Config** to receive a small set of operational settings from us: for example, to temporarily switch off a feature or card type that does not work correctly, or to ask users of an outdated version to update. These settings can only switch things off or require an update; they never turn on advertising or any other feature, and we do not use them for experiments (A/B tests), personalisation, or to target users based on analytics data. The App checks for new settings in the background, at most about once an hour and only after the consent dialog (where it is shown) has been answered, and applies them the next time the App starts.

Each check sends Google the **Firebase installation identifier** of this installation of the App, the App's package name and version, the operating-system version, the device language, country code and time zone, and the SDK version. If analytics is enabled, a check may also carry the analytics profile attributes described in a) (for example your level and current streak) and the time the App was first opened. If you decline or withdraw consent, or turn analytics off, the App deletes this analytics data from your device, so it is not sent.

These checks happen **regardless of your analytics choice**. They are strictly necessary to keep the App working safely as you use it, so they do not require consent; their legal basis is our legitimate interest (Section 2).

#### g) Google Play In-App Review and In-App Updates

The App may occasionally show Google Play's own in-app review prompt. The review you write (if any) is submitted directly to Google Play and is governed by Google's terms; the App is not told whether you left a review or what it said. Where analytics is enabled, we record only that the prompt was shown and closed.

The App uses **Google Play In-App Updates** to ask Google Play whether a newer version is available and, where an update is required (Section 1.3(f)) or available, to show Google Play's update screen. Any download is handled by Google Play.

### 1.4 Backup Files You Create

Anyone can use the in-app **"Back up & transfer your progress"** feature (Settings → Backup & transfer) to export their learning data (including the optional name, progress, streaks, saved cards, achievements and settings) to a single file, and **"Restore backup"** to load such a file, which replaces the progress on the device. You choose where the file is saved and which file is restored, using your device's system file picker. **We do not receive, store, or have access to this file** — it remains entirely under your control. Where you save it (for example, to a personal cloud-storage location) and how it is protected is your decision.

### 1.5 Sharing Cards

When you share a card, the App creates an image of it on your device and passes it to the app you choose in Android's share sheet. We do not receive the image or learn where you sent it.

### 1.6 When You Contact Us

If you email us — for example through **"Report a problem"** in a card's menu, the feedback option behind "Rate this app" in Settings, or the feedback buttons on the end-of-free-content page — the App opens your email app with the message prepared, and you decide whether to send it. A card report contains the description you type and the card's identifier, version and type; feedback from the end-of-free-content page contains the rating you chose and the App version. When you send the message, we receive your email address, the message and anything you add to it. We use this only to reply to you and to fix the problem, and we keep it as described in Section 7.1.

### 1.7 Is Providing Information Required?

No law or contract requires you to provide any of the information described in this policy. You can use the App without a name, with notifications turned off and with analytics turned off, wherever you are. Whatever you choose, the App still sends the technical information needed for operational settings (Section 1.3(f)) and for the consent check (Section 1.3(d)), the request with which Google's messaging library creates the push token (Section 1.3(b)), your IP address when it connects to Google, and, if you subscribe, what Google Play needs for the purchase.

---

## 2. How We Use Information

We use information for the following purposes:

| Purpose | Data Used | Legal Basis (GDPR Art. 6) |
|---------|-----------|---------------------------|
| Providing core App functionality (lessons, scoring, spaced-repetition scheduling, progress tracking, streaks, achievements) | Learning data stored locally on your device | Performance of a contract (Art. 6(1)(b)) |
| Saving and restoring your preferences, settings, and optional name, including through Android backup and backup files you create | Data stored locally on your device; the backup in your Google Account or your backup file | Performance of a contract (Art. 6(1)(b)) |
| Delivering the reminder notifications you allow | FCM token (created by Google's messaging library on every installation), time zone, reminder times, brand identifier, anonymous identifier, delivery-health information | Performance of a contract (Art. 6(1)(b)) — reminders are part of the App's service (Terms of Service, Sections 2 and 5) and you can switch them off at any time |
| Receiving operational settings (switching off a feature that does not work, requiring an update) | Firebase installation identifier, app and OS version, language, country code, time zone | Legitimate interest (Art. 6(1)(f)) in keeping the App working and secure; strictly necessary, so no consent is required |
| Measuring app usage to improve features (Firebase Analytics) | Individual usage events and profile attributes, app-instance ID, device/technical info, IP address (approximate location), install referrer, Advertising ID | Consent (Art. 6(1)(a)) in the EEA, UK and Switzerland, given in the in-app consent dialog; elsewhere, legitimate interest in understanding and improving the App (Art. 6(1)(f)) or the equivalent basis under local law |
| Detecting and fixing crashes, errors and slowness (Firebase Crashlytics, Firebase Performance Monitoring) | Crash logs, device state, technical context, performance measurements, installation identifiers, technical info | As above |
| Processing subscriptions and trials, and verifying entitlement | Purchase data processed by Google Play, the obfuscated account ID, the purchase record on your device | Performance of a contract (Art. 6(1)(b)) |
| Keeping accounts and tax records of our sales | Order information shown in the Google Play Console | Legal obligation (Art. 6(1)(c)) — outside the EEA and the UK we are the seller of the subscription |
| Asking for consent where it is required and keeping a record of your choice | IP address (Google UMP), your consent choice and the time it was made (on your device) | Legal obligation (Art. 6(1)(c), together with Art. 7(1)) |
| Protecting our reminder backend from abuse | Firebase App Check attestation token, IP address, recent request times | Legitimate interest (Art. 6(1)(f)) — security and integrity |
| Answering your messages and card reports | Your email address, your message, card identifier, version and type | Legitimate interest (Art. 6(1)(f)) in answering you and correcting our content; where your message concerns your use of the App or a purchase, performance of a contract (Art. 6(1)(b)) |

Where we rely on legitimate interest, you can object at any time (Section 11). For analytics, crash reporting and performance monitoring the simplest way is the "Share anonymous usage data" switch.

We do **not** use any information for:

- Advertising or ad personalization (the App displays no advertisements)
- Selling personal information (as defined under CCPA/CPRA)
- Profiling or automated decision-making that produces legal or similarly significant effects (GDPR Art. 22)
- Direct marketing or email campaigns
- Cross-app or cross-device tracking

---

## 3. Consent and Your Controls

**Everyone.** Settings → About has a **"Share anonymous usage data"** switch. It turns Firebase Analytics, Firebase Crashlytics and Firebase Performance Monitoring on or off together, in every country. When you turn it off, analytics and performance collection stop at once and crash reporting from the next start of the App, the App deletes the analytics data still stored on your device and any crash reports not yet sent, and nothing further is collected until you turn it back on. Data sent before that is deleted at the end of its retention period (Section 7.1). Despite the switch's short name, this data is pseudonymous rather than anonymous, as explained in Section 1.3(a).

**EEA, UK and Switzerland.** On first launch the App shows a consent dialog (powered by the Google UMP SDK). **Analytics, crash reporting and performance monitoring stay off until you give consent** (except when the dialog cannot be loaded on the first launch, Section 1.3(a)). If you decline, the App works fully and none of this data is collected. You can change your decision at any time with the "Share anonymous usage data" switch, or by reopening the consent form through **Settings → About → "Ad privacy settings"**, which is shown where consent is legally required. Withdrawing consent does not affect the lawfulness of processing before the withdrawal.

**Everywhere else.** Analytics, crash reporting and performance monitoring are enabled when you first open the App, on the basis of our legitimate interest (Section 2). You can turn them off at any time with the "Share anonymous usage data" switch. Section 1.3(a) explains what happens if the consent dialog cannot be loaded on the first launch.

**Operational settings** (Firebase Remote Config, Section 1.3(f)) are not affected by this switch, because they are strictly necessary for the App to work safely.

**Advertising ID.** You can reset or delete your Advertising ID in Android Settings → Google → Ads (the wording varies by device). This limits identifier-based measurement but does not by itself stop event collection — use the switch for that.

**Reminder notifications** are delivered only while notifications are allowed for the App. You can turn them off at any time in **Settings → Notifications** ("All notifications") or in Android's notification settings for the App; this also deletes the reminder record on our backend (Section 1.3(b)).

**"Delete all data"** (Section 7.2) keeps your analytics choice, so an earlier decision to turn analytics off is not undone.

---

## 4. Third-Party Services

Scrollish relies on the following third-party services, all provided by Google:

| Service | Provider | Purpose | Privacy Policy |
|---------|----------|---------|----------------|
| Firebase Analytics | Google LLC | App-usage measurement (consent-gated in the EEA/UK/Switzerland; switchable everywhere) | [Google Privacy Policy](https://policies.google.com/privacy) |
| Firebase Crashlytics | Google LLC | Crash and error diagnostics (as above) | [Google Privacy Policy](https://policies.google.com/privacy) |
| Firebase Performance Monitoring | Google LLC | App start and loading-time measurements (as above) | [Google Privacy Policy](https://policies.google.com/privacy) |
| Firebase Remote Config and Firebase Installations | Google LLC | Operational settings (switching a feature off, minimum supported version); the installation identifier used by Firebase services | [Google Privacy Policy](https://policies.google.com/privacy) |
| Firebase Cloud Messaging | Google LLC | Delivery of reminder notifications | [Google Privacy Policy](https://policies.google.com/privacy) |
| Firebase Cloud Functions + Firestore | Google LLC | Scheduling of reminder notifications | [Google Privacy Policy](https://policies.google.com/privacy) |
| Firebase Authentication (Anonymous) | Google LLC | Anonymous identifier for the reminder backend | [Google Privacy Policy](https://policies.google.com/privacy) |
| Firebase App Check (Play Integrity) | Google LLC | Backend abuse and integrity protection | [Google Privacy Policy](https://policies.google.com/privacy) |
| Google Play Billing | Google LLC | Subscription and trial processing | [Google Play Terms](https://play.google.com/about/play-terms/) |
| Google Play In-App Review and In-App Updates | Google LLC | The optional "rate this app" prompt; checking for and installing App updates | [Google Play Terms](https://play.google.com/about/play-terms/) |
| Google Play Services | Google LLC | Core app infrastructure | [Google Privacy Policy](https://policies.google.com/privacy) |
| Google User Messaging Platform (UMP) | Google LLC | Consent management (EEA/UK/Switzerland) | [Google Privacy Policy](https://policies.google.com/privacy) |
| Google Mobile Ads SDK | Google LLC | Present in the App but never initialised; no ads are shown (Section 1.3(d)) | [Google Privacy Policy](https://policies.google.com/privacy) |
| Android Backup | Google LLC | Optional backup and device transfer of the App's progress database in your Google Account, controlled by you in Android settings (Section 6.3) | [Google Privacy Policy](https://policies.google.com/privacy) |
| Google BigQuery | Google LLC | Storage and analysis of the exported analytics, crash and performance data | [Google Privacy Policy](https://policies.google.com/privacy) |

We do not share your information with any other third parties, data brokers, advertising networks, or analytics providers.

**Data processing terms:** Our use of Google and Firebase services is governed by Google's data processing terms, including the [Firebase Data Processing and Security Terms](https://firebase.google.com/terms/data-processing-terms) and the [Google Ads Data Processing Terms](https://privacy.google.com/businesses/processorterms/) (which cover Google Analytics), together with the transfer mechanisms described in Section 10. For the Firebase services, Google Analytics and BigQuery, Google acts as a data processor (service provider) on our behalf; for some purposes of its own, described in Google's privacy policy, Google acts as an independent controller. For Google Play (billing, in-app review and updates), Google Play Services, the UMP consent service and Android Backup, Google acts as an independent controller under its own terms. [OWNER: confirm that Google signals and data sharing with Google for its own purposes are switched off in Google Analytics, then keep this sentence:] We have not enabled Google signals and do not share analytics data with Google for Google's own purposes. Android Backup is a service Google provides to you under your Google Account; we have no access to the backups it stores.

---

## 5. Subscriptions and In-App Purchases

Scrollish offers an auto-renewing subscription, **Scrollish PRO**:

- **Monthly** and **annual** subscription plans
- A short **free trial** at the start of the subscription, where offered

The first module of the course is free. PRO unlocks the full course, PRO colour themes, longer daily goals, and more streak shields each month.

All purchases and subscriptions are processed by **Google Play**. We do not collect, process, or store your payment information. Subscriptions are tied to your Google Account and renew automatically until cancelled. You can manage or cancel your subscription at any time through the **"Manage in Google Play"** button on the PRO card in Settings, or directly in the Google Play Store under Payments & subscriptions. You can restore an existing purchase through **Settings → About → "Restore purchases"**.

Refunds and the right of withdrawal are described in Sections 4.7 and 4.10 of our [Terms of Service](terms.md) and in [Google Play's refund policy](https://support.google.com/googleplay/answer/2479637).

---

## 6. Data Storage and Security

### 6.1 Local Storage

Your learning data, preferences, and optional name are stored locally on your device using:

- A **SQLite database** (via the Room library) for learning progress, sessions, streaks, saved cards, achievements, preferences and settings
- **App preference and data files** written by the App and by the Google libraries it uses (for example the operational settings, a record of your purchases, your stored choice in the consent dialog, the Firebase identifiers and unsent crash reports). These are never included in Android's backup (Section 6.3)

Apart from the reminder record (Section 1.3(b)), the operational-settings checks (Section 1.3(f)), the analytics, crash and performance data described in Section 1.3(a), messages you choose to send us (Section 1.6), the Android backup you control (Section 6.3) and any backup file you choose to create (Section 1.4), this data does not leave your device through the App.

### 6.2 Security Measures

- All local data is stored in the App's private storage directory, inaccessible to other applications
- All network communication uses encrypted connections (HTTPS/TLS)
- Requests to our reminder backend are protected by Firebase App Check, and our database rules deny all direct client access
- Where consent is required, analytics, crash reporting and performance monitoring stay off until consent is given (subject to the first-launch case in Section 1.3(a))
- The App does not load or execute remote scripts or code; learning content (text, images, audio) is bundled with the App

### 6.3 Android Backup and Device Transfer

If backup is turned on in your Android settings, Android can include the App's **progress database** — your progress, streaks, XP, saved cards, achievements, settings and the optional name — in the backup it keeps in **your Google Account**, and in a transfer to a new device. Nothing else from the App is included: its other files and preferences, such as the Firebase identifiers and the choice stored by the consent dialog, stay on the device. We cannot access these backups. Google stores them under your Google Account and Google's terms, and you can turn backup off or delete backups in Android or Google Account settings (for example Settings → Google → Backup; the wording varies by device).

The database also holds a few settings that belong to the old device, such as the state of the reminder registration, the notification history and your analytics choice. When a backup or transfer is restored on a device, the App keeps your learning data and clears those settings once. Your analytics choice therefore does not travel with a backup: on the new device the consent dialog or the default described in Section 3 applies again, and you can use the "Share anonymous usage data" switch.

After **"Delete all data"**, the copy in your Google Account still contains your earlier data until Android makes its next backup, which normally happens about once a day when the device is idle, charging and connected to Wi-Fi.

To move your progress yourself, you can also use the backup-file feature described in Section 1.4.

---

## 7. Data Retention and Deletion

### 7.1 Retention

- **Data on your device** is kept for as long as you keep the App installed and do not delete it (Section 7.2). We do not keep this data on our servers.
- **Android backup:** the copy in your Google Account is replaced at each new backup and is otherwise kept and deleted by Google according to your Google Account settings (Section 6.3).
- **Reminder record:** deleted when you turn notifications off or use "Delete all data" (Section 1.3(b)). Otherwise it is deleted automatically **90 days after the App last refreshed it** — in practice, 90 days after you last used the App; the database usually removes an expired record within 24 hours. The record of recent registration requests is deleted 24 hours after the last request.
- **Backups of our database:** deleted reminder records and registration counters can remain in our database's automatic backups for up to 7 days (point-in-time recovery) and in its weekly backups for up to 8 weeks. We use these backups only to recover from data loss, and if we ever restore one, we delete again the records that had been deleted after it was made.
- **Anonymous Firebase account** used by the reminder service: it holds only the anonymous identifier and technical sign-in information. It is deleted when you use "Delete all data" or on request; turning notifications off does not delete it, and it is not deleted automatically. Firebase keeps the IP addresses it logs for this service for a few weeks.
- **Technical logs of our reminder backend** (which can contain the anonymous identifier, error details and the IP address of requests) are kept for 30 days.
- **Firebase installation identifier** (used for operational settings and for delivering notifications): Google keeps it until it is deleted, and the App does not delete it — so it remains in Google's systems after you uninstall the App or clear its data, although it is no longer used; a new identifier is created on the next installation. After deletion, Google removes it from its systems within 180 days.
- **Firebase Analytics:** event-level data linked to the app-instance identifier is kept for **[OWNER: GA4 data retention setting — 2 months or 14 months]**, then deleted by Google. Aggregated reports that do not identify an installation may be kept longer.
- **Firebase Crashlytics:** crash reports and their identifiers are kept for 90 days.
- **Firebase Performance Monitoring:** measurements associated with an IP address are kept for 30 days; measurements linked to an installation identifier for 60 days.
- **Exports to Google BigQuery:** we keep copies of analytics, crash and performance data in our Google BigQuery project for analysis, for **[OWNER: BigQuery retention period for the Analytics, Crashlytics and Performance exports]**.
- **Firebase App Check tokens** are valid for at most 7 days and are not stored by us.
- **Emails and card reports you send us:** kept for as long as needed to handle your message, and then for no longer than **[OWNER: retention period for support emails]**, unless we need them longer to establish, exercise or defend legal claims.
- **Purchase records:** the record of your purchases on your device is kept until you delete the App's data or uninstall it. We keep the order information from the Google Play Console for **[OWNER: retention period required by accounting and tax law]**. Google Play keeps its own records under Google's terms.

### 7.2 Deleting Your Data

You may delete your data at any time.

**Delete all data in the App.** Open **Settings → Danger zone → "Delete all data"**, type DELETE and confirm. This:

- permanently deletes from your device all your progress, streaks, XP, achievements, saved cards, card reports, reminders and settings, and the optional name;
- instructs our backend to delete the reminder record and the anonymous Firebase account; if the device is offline, the App retries the next time it is online;
- switches notifications off (turn them back on in Settings → Notifications if you want reminders again);
- gives your installation a new Google Analytics identifier and deletes crash reports not yet sent, so later Google Analytics events are not linked to your earlier ones (the Firebase installation identifier and the Crashlytics installation identifier stay the same);
- keeps your analytics choice and a few technical records the App needs to work correctly, for example a note that the rating prompt was already shown, the random technical token mentioned in Section 1.2, the operational settings, the record of your purchases and the Firebase identifiers.

It does not delete analytics, crash and performance data already sent to Google, or copies in our database backups (both deleted at the end of the periods in Section 7.1), your choice in the consent dialog, your purchases (managed by Google Play), backup files you exported, or the copy in your Android backup until Android makes its next backup (Section 6.3).

**Other ways to delete your data:**

- **Turn off notifications:** in **Settings → Notifications** ("All notifications") or in Android's notification settings for the App. This instructs our backend to delete the reminder record for your device (after a change in Android's settings, the next time you open the App).
- **Turn off analytics:** use the **"Share anonymous usage data"** switch (Section 3).
- **Clear app data:** Android Settings → Apps → Scrollish → Storage → Clear data. This deletes the data on your device but does not contact our backend; the reminder record is then deleted automatically after 90 days, or on request.
- **Uninstall the App:** removes all locally stored data from your device and stops reminder delivery. Uninstalling does **not**, by itself, delete the reminder record or the anonymous Firebase account. To delete them, use "Delete all data" before uninstalling; otherwise the reminder record is deleted automatically after 90 days.
- **By email request:** contact us at [OWNER: contact email]. The data on our side — the reminder record, the anonymous Firebase account, and analytics, crash and performance data — is pseudonymous: we cannot find it by your name or email address. If the App is still installed, the quickest way is "Delete all data" or turning notifications off. Otherwise tell us what you would like deleted. Where we can identify your installation from the information you give us (Section 14), we will delete its reminder record, its anonymous Firebase account and its Google Analytics data, and confirm when it is done; Google offers no way to delete the crash and performance data of a single installation, so that data is deleted at the end of the periods in Section 7.1. Where we cannot identify your installation, we will tell you so. For data stored only on your device, we will guide you through the methods above. We respond to deletion requests within one month.

### 7.3 Web-Based Data Deletion Request (Google Play Requirement)

In accordance with Google Play's data deletion policy, you can review the deletion process and how to submit a request on our website at: **https://uplyfire.github.io/legal/scrollish/data-deletion**

Purchase and subscription history managed by Google Play cannot be deleted through the App; to review it, visit [Google Play Order History](https://play.google.com/store/account/orderhistory). Google's own data controls are available at [Google Account settings](https://myaccount.google.com/data-and-privacy).

---

## 8. Children's Privacy

Scrollish is an educational application intended for users **aged 16 and over**. It is **not directed to children**, and we do **not** knowingly collect personal information from anyone under 16. Our Google Play "Target audience" declaration is 16–17 and 18 and over; the App is not enrolled in Google Play's Designed for Families programme and does not present itself as a children's app.

The App does not:

- Require account creation or registration
- Collect names, email addresses, or other personal identifiers (the optional in-app name is stored only on the device and in backups you control, and is never transmitted to us)
- Enable communication between users
- Display advertising

If you are a parent or guardian and believe that a child under 16 is using the App, please contact us at [OWNER: contact email]. We will help you delete the data on the device and will delete the reminder record and any other data we can identify.

---

## 9. Permissions

The App's manifest declares the following Android permissions. The first three are declared by the App itself; the rest are declared by the Google and AndroidX libraries bundled in the App and merged into the manifest automatically.

| Permission | Purpose | Required? |
|------------|---------|-----------|
| `INTERNET` | Connecting to Google Play (purchases, updates) and Firebase (reminders, operational settings; analytics, crash reporting and performance monitoring where enabled). Not used to transmit the content of your lessons, cards or answers; where analytics is enabled, usage events are transmitted as described in Section 1.3(a). | Yes |
| `POST_NOTIFICATIONS` | Showing reminder notifications (Android 13+). | Optional — the only permission the App asks you for |
| `RECEIVE_BOOT_COMPLETED` | Restoring scheduled work after the device restarts. | Yes |
| `ACCESS_NETWORK_STATE` | Detecting network connectivity (declared by WorkManager, Firebase and the Google Mobile Ads SDK). | Yes |
| `WAKE_LOCK`, `FOREGROUND_SERVICE` | Allowing a reminder to be prepared and posted reliably when the device is idle (declared by the Firebase Cloud Messaging and WorkManager libraries). The App does not run foreground services. | Yes |
| `com.android.vending.BILLING`, `com.google.android.c2dm.permission.RECEIVE`, `READ_GSERVICES` | Google Play purchases, push-message delivery, and Google Play Services infrastructure (declared by the respective Google libraries). | Yes |
| `BIND_GET_INSTALL_REFERRER_SERVICE` | Reading the Google Play install referrer for install attribution where analytics is enabled (declared by Google's measurement library). | Yes (used only where analytics is enabled) |
| `com.google.android.gms.permission.AD_ID`, `ACCESS_ADSERVICES_AD_ID`, `ACCESS_ADSERVICES_ATTRIBUTION`, `ACCESS_ADSERVICES_TOPICS` | Declared by the Google Mobile Ads SDK and Google's measurement library. Where analytics is enabled, Firebase Analytics may use the Advertising ID for measurement. The App shows no advertisements and uses none of these for advertising. | Yes (used only where analytics is enabled) |
| `DYNAMIC_RECEIVER_NOT_EXPORTED_PERMISSION` | An internal permission created by the AndroidX libraries so that only the App itself can send certain messages to the App. | Yes |

`POST_NOTIFICATIONS` is the only permission the App asks you for. The others are granted at install time without a prompt (`DYNAMIC_RECEIVER_NOT_EXPORTED_PERMISSION` is a signature permission that only the App itself holds), and none of them gives the App access to your files, location, contacts, camera or microphone. The App does **not** request access to location, camera, microphone, contacts, storage, phone state, SMS, or Bluetooth.

**Advertising ID (`com.google.android.gms.permission.AD_ID`):** where analytics is enabled, Firebase Analytics may collect the Android Advertising ID for measurement purposes. You can reset or delete your Advertising ID, or opt out of its personalization, in Android Settings → Google → Ads. The App does **not** use the Advertising ID for advertising, as it displays no ads.

---

## 10. International Data Transfers

The reminder record described in Section 1.3(b) is stored in Google Cloud Firestore in the **`europe-west1` region (Belgium, European Union)**, and the functions that write and use it run in the same region. Push-message delivery (Firebase Cloud Messaging), Firebase Authentication, Remote Config, App Check and, where enabled, Firebase Analytics, Crashlytics and Performance Monitoring are global Google services and involve processing on Google infrastructure outside the European Economic Area, **including in the United States**. Android backups are stored by Google under your Google Account. The copies of analytics, crash and performance data we export to Google BigQuery are stored in **[OWNER: BigQuery dataset location, e.g. EU multi-region or US]**.

For transfers of personal data from the European Economic Area (EEA), the United Kingdom (UK), or Switzerland to countries without an adequacy decision, Google relies on the following:

- the **EU–U.S. Data Privacy Framework**, its UK Extension and the Swiss–U.S. Data Privacy Framework, under which Google LLC is certified;
- **Standard Contractual Clauses (SCCs)** approved by the European Commission, where the Framework does not apply;
- the **UK International Data Transfer Addendum** where applicable;
- additional technical and organisational safeguards as described in [Google's Data Transfer Frameworks documentation](https://policies.google.com/privacy/frameworks).

You can obtain a copy of the applicable safeguards by contacting us (Section 14). For transfers from Brazil, Google maintains compliance with LGPD requirements for international data transfers (LGPD Art. 33).

---

## 11. Your Rights

Depending on your jurisdiction, you may have the following rights regarding your data. Because your learning data is stored locally on your device, most of these rights are exercisable directly through the in-app controls (Sections 3 and 7) and your device settings. For data processed by Firebase, we will act on your request as described in Section 7.2, and you may also exercise rights directly with Google. Because the App has no accounts, we may need information from you to find the data a request concerns (Section 14).

### 11.1 GDPR Rights (European Economic Area, United Kingdom and Switzerland)

If you are located in the EEA, the UK or Switzerland, you have the following rights under the GDPR, the UK GDPR or the Swiss data protection law:

- **Right of access (Art. 15)** — Request a copy of the personal data we process about you
- **Right to rectification (Art. 16)** — Correct inaccurate or incomplete personal data
- **Right to erasure (Art. 17)** — Request deletion of your personal data (see Section 7)
- **Right to restrict processing (Art. 18)** — Limit how your personal data is processed
- **Right to data portability (Art. 20)** — Receive your personal data in a structured, commonly used, machine-readable format. Anyone can export their learning data to a file with the in-app "Back up & transfer your progress" feature (Section 1.4), and you may also ask us for the data we hold, at no charge
- **Right to object (Art. 21)** — Object to processing based on legitimate interest, including analytics outside the EEA (the "Share anonymous usage data" switch does this immediately)
- **Right to withdraw consent (Art. 7(3))** — Withdraw consent for analytics, crash reporting and performance monitoring at any time with the "Share anonymous usage data" switch or through Settings → About → "Ad privacy settings", without affecting the lawfulness of processing before withdrawal
- **Right to lodge a complaint (Art. 77)** — Lodge a complaint with your local data protection supervisory authority. Because we are established in Poland, you may also complain to the Polish authority: the President of the Personal Data Protection Office (Prezes Urzędu Ochrony Danych Osobowych, UODO), ul. Stanisława Moniuszki 1A, 00-014 Warszawa, Poland, [https://uodo.gov.pl/](https://uodo.gov.pl/). A list of EEA supervisory authorities is available at [https://edpb.europa.eu/about-edpb/about-edpb/members_en](https://edpb.europa.eu/about-edpb/about-edpb/members_en); in the UK you can contact the Information Commissioner's Office ([https://ico.org.uk/](https://ico.org.uk/)) and in Switzerland the Federal Data Protection and Information Commissioner ([https://www.edoeb.admin.ch/](https://www.edoeb.admin.ch/))

**Data Protection Officer:** Given the nature and scale of our data processing activities, we are not required to appoint a Data Protection Officer under GDPR Art. 37. For all privacy-related inquiries, please contact us using the details in Section 14.

### 11.2 CCPA/CPRA Rights (California Residents)

Where the CCPA applies to our processing, California residents have the following rights:

- **Right to know (Cal. Civ. Code § 1798.100, § 1798.110)** — Request disclosure of the categories and specific pieces of personal information collected, the sources, the purposes, and the categories of third parties to whom it is disclosed
- **Right to delete (§ 1798.105)** — Request deletion of personal information we have collected
- **Right to correct (§ 1798.106)** — Request correction of inaccurate personal information
- **Right to non-discrimination (§ 1798.125)** — Not be discriminated against for exercising your privacy rights

**Sale and sharing of personal information:** Scrollish does **not** "sell" or "share" personal information as those terms are defined under the CCPA/CPRA, and does not engage in cross-context behavioural advertising. We do not collect sensitive personal information as defined by the CPRA (the IP-derived location described in Section 1.3(a) is approximate, not precise geolocation). To submit a request, contact us at the email address in Section 14. We will respond within 45 days, and will tell you if we need a further 45 days.

**California "Shine the Light" (Cal. Civ. Code § 1798.83):** We do not disclose personal information to third parties for their direct marketing purposes.

### 11.3 LGPD Rights (Brazilian Residents)

If you are located in Brazil, you have the rights set out in Art. 18 of the Lei Geral de Proteção de Dados (LGPD, Law No. 13,709/2018), including confirmation of processing, access, correction, anonymization/blocking/deletion, portability, information about sharing, information about consent, and revocation of consent.

**Legal basis for processing under LGPD:** Analytics, crash reporting and performance monitoring are based on our legitimate interest in understanding and improving the App (Art. 7(IX)); you can oppose them at any time with the "Share anonymous usage data" switch. Reminder notifications and subscriptions are based on the performance of a contract (Art. 7(V)). Operational settings (Remote Config), backend integrity protection and answering your messages are based on legitimate interest (Art. 7(IX)). Sales records and the record of consent choices are based on compliance with a legal obligation (Art. 7(II)).

To exercise your LGPD rights, contact us at the email address in Section 14. Where you request access to or confirmation of processing, we will respond in simplified form immediately where practicable and in complete form within the 15 days required by Art. 19 of the LGPD.

---

## 12. EU Digital Services Act (DSA) Disclosures

For users in the European Union, in accordance with Regulation (EU) 2022/2065 (the Digital Services Act):

- **Advertising transparency:** The App displays no advertisements. Should advertising be introduced in the future, we will provide the transparency information required by the DSA at that time.
- **Recommender systems:** Scrollish does not use profiling-based recommender systems. The order in which learning cards are presented is determined by a spaced-repetition algorithm based on your own answers and review schedule on your device, not by profiling for commercial purposes.
- **Content moderation:** Scrollish does not host user-generated content and therefore does not perform content moderation.
- **Trader information:** We act as a trader within the meaning of the DSA when offering the PRO subscription (in the EEA and the UK, Google Play is the seller of the subscription itself). Our identity and contact details are set out in Section 14 and on the Google Play listing.
- **Point of contact:** For DSA-related inquiries, please contact us at [OWNER: contact email] (see Section 14).

---

## 13. Changes to This Privacy Policy

We may update this Privacy Policy from time to time to reflect changes in our practices, technology, legal requirements, or other factors. When we make changes:

- **For all updates:** We will update the "Last Updated" date and Policy Version number at the top of this document
- **For material changes** (new data collection, new third-party services, changes to data sharing): We will publish the updated policy at this address with a new version number and Effective Date, and describe the change in the Google Play Store listing's release notes, before the changes take effect
- **For non-material changes** (clarifications, formatting, updated links): Changes take effect upon posting

Where changes affect processing that relies on your consent, we will ask for your consent again before applying the changes. For other changes, your continued use of the App after changes are posted constitutes your acknowledgment of the revised policy, to the extent permitted by applicable law.

---

## 14. Contact Us

If you have any questions, concerns, or requests regarding this Privacy Policy or our data practices, please contact us. The controller of your personal data, and the trader offering Scrollish PRO within the meaning of the DSA, is:

- **Name:** [OWNER: full name or business name], trading as Uplyfire
- **Legal form:** [OWNER: legal form — sole trader registered in CEIDG, or unregistered activity]
- **Address:** [OWNER: postal address as shown on Google Play], Poland
- **NIP / REGON:** [OWNER: NIP and REGON — delete this line if not registered]
- **Email:** [OWNER: contact email]
- **Phone:** [OWNER: phone number as shown on Google Play]

You may also contact us through the developer contact information listed on the [Scrollish Google Play Store listing](https://play.google.com/store/apps/details?id=com.scrollish.android).

We aim to respond to all privacy-related inquiries within 30 days. For GDPR-related requests, we will respond within one month as required by Art. 12(3) (extendable by two further months for complex requests, in which case we will tell you within the first month). For CCPA/CPRA requests, we will respond within 45 days (extendable once by 45 days with notice). For LGPD access and confirmation requests, within 15 days as required by Art. 19 of the LGPD.

Because the App has no accounts, we usually cannot link a request to data we hold by your name or email address alone. To act on a request about the reminder record or analytics data, we may ask you for information that lets us identify your installation; we will not ask for more than we need and will use it only to handle your request.

---

## 15. Google Play Data Safety Summary

In accordance with Google Play requirements, the following summarizes our data practices as declared in the Data safety form for the current version of the App. **The App displays no advertisements; no data is collected or shared for advertising purposes.** "Optional" means that every user, in every region, can turn the collection off ("Share anonymous usage data" switch, or notifications off).

| Data Category | Data Type | Collected? | Shared? | Purpose | Optional? |
|---------------|-----------|------------|---------|---------|-----------|
| Location | Approximate location derived by Google from the IP address | Yes (Firebase Analytics, Performance Monitoring) | No | Analytics | Optional |
| Financial info | Purchase history (plan, price, currency, trial, conversion and cancellation events) | Yes (Firebase Analytics) — the transaction itself is processed by Google Play | No | Analytics | Optional |
| App activity | App interactions: usage events, including card signals (see Section 1.3(a)); reminder times and time zone (reminder backend) | Yes (Firebase Analytics; reminder backend) | No | Analytics; App functionality | Optional |
| App info and performance | Crash logs | Yes (Firebase Crashlytics) | No | Analytics | Optional |
| App info and performance | Diagnostics (performance measurements, device state) | Yes (Firebase Performance Monitoring, Crashlytics, Analytics) | No | Analytics | Optional |
| Device or other IDs | Firebase installation ID, app-instance ID, Crashlytics installation ID, Advertising ID (AAID), anonymous Firebase identifier, FCM push token, App Check attestation token | Yes | No | App functionality; Analytics; Fraud prevention, security and compliance | Required (the Firebase installation ID is sent for operational settings on every installation) |
| App activity | Learning content, progress, streaks, saved cards, achievements | Stored on the device only (and in Android backups you control) — not collected by us; usage events derived from it are reported as "App interactions" above | No | App functionality | — |
| Personal info | Name / nickname | Stored on the device only (and in backups you control) — not collected by us | No | App functionality | — |

**On "sharing":** Google acts as our **service provider (processor)** for Firebase Analytics, Crashlytics, Performance Monitoring, Remote Config, Installations, Cloud Messaging, Cloud Functions, Firestore, Anonymous Authentication and App Check, processing data on our instructions under the [Firebase Data Processing and Security Terms](https://firebase.google.com/terms/data-processing-terms) and, for Google Analytics, the [Google Ads Data Processing Terms](https://privacy.google.com/businesses/processorterms/). Under Google Play's Data safety definitions, a transfer to a service provider is **not** "sharing", which is why these rows are marked "No". Google separately processes some data as an independent controller for its own purposes, as described in [Google's Privacy Policy](https://policies.google.com/privacy). We do not transfer your data to any other organisation.

**Data handling declarations:**

- **Encryption in transit:** Yes — all network communication uses HTTPS/TLS
- **Data deletion:** Users can delete their data in the App (Settings → "Delete all data", which also deletes the reminder record and the anonymous Firebase account), turn off notifications (which deletes the reminder record), turn off analytics, clear app data, or uninstall; the reminder record is also deleted automatically after 90 days without use; other data is deleted on request. A web page describing deletion is available at https://uplyfire.github.io/legal/scrollish/data-deletion
- **Data is not sold or shared for advertising:** We do not sell user data and display no advertising
- **Account creation:** The App has no user accounts

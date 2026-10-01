# Privacy Policy

**Last Updated:** October 1, 2026
**Effective Date:** October 1, 2026
**Policy Version:** 1.3

---

## Table of Contents

1. [Information We Collect](#1-information-we-collect)
2. [How We Use Information](#2-how-we-use-information)
3. [Third-Party Services](#3-third-party-services)
4. [Advertising](#4-advertising)
5. [In-App Purchases](#5-in-app-purchases)
6. [Data Storage and Security](#6-data-storage-and-security)
7. [Data Retention and Deletion](#7-data-retention-and-deletion)
8. [Children's Privacy](#8-childrens-privacy)
9. [Permissions](#9-permissions)
10. [International Data Transfers](#10-international-data-transfers)
11. [Your Rights](#11-your-rights)
12. [Changes to Our Data Practices](#12-changes-to-our-data-practices)
13. [EU Digital Services Act (DSA) Disclosures](#13-eu-digital-services-act-dsa-disclosures)
14. [Changes to This Privacy Policy](#14-changes-to-this-privacy-policy)
15. [Contact Us](#15-contact-us)
16. [Additional Disclosures](#16-additional-disclosures)
17. [YouTube API Services](#17-youtube-api-services)

---

Uplyfire ("we," "us," or "our") operates the MapGenius mobile application (the "App"). This Privacy Policy describes how we collect, use, store, and protect information when you use our App. Please read this Privacy Policy carefully to understand our data practices. Where our processing of your personal data relies on consent as its legal basis (such as personalized advertising), we will obtain that consent separately through appropriate mechanisms (e.g., the in-app consent dialog for EEA/UK users) in compliance with applicable law.

We are committed to protecting your privacy and ensuring transparency about our data practices. This policy is designed to comply with applicable data protection regulations, including the General Data Protection Regulation (GDPR), the California Consumer Privacy Act as amended by the California Privacy Rights Act (CCPA/CPRA), the Brazilian General Data Protection Law (Lei Geral de Protecao de Dados, LGPD), the Children's Online Privacy Protection Act (COPPA), and Google Play Developer Program Policies.

**In short:** MapGenius has no sign-up and never asks for your name or email address. To run the daily challenges and the global rankings, the App creates a random **Player ID** for your installation and stores your game results, your ranking nickname and your optional country flag on our Firebase backend in the European Union. Your nickname, flag and scores are visible to other players in the rankings. Google services we use for advertising, analytics, crash reporting and purchases also collect data, as described below. You can ask us to delete your data at any time (Section 7).

---

## 1. Information We Collect

### 1.1 Information We Do NOT Collect

MapGenius does **not** collect, request, or process:

- Personal identification information (real name, email address, phone number, mailing address, date of birth). The optional ranking nickname and country you may set are described in Section 1.2(d)
- Precise location or GPS data. The App does not request the location permission. Google's advertising and analytics services estimate an approximate area (such as a city or region) from your IP address, as described in Section 1.2(b)
- Contacts, calendar, or phone data
- Photos, files, or media from your device
- Microphone or camera input
- Biometric data
- Health or fitness data
- Payment card or bank account details
- Browsing history
- Social media profiles or credentials
- Device identifiers such as IMEI or IMSI

### 1.2 Information Collected Automatically and Through Your Use of the App

MapGenius does not ask for your name, email address or any account. Most of the information described below is **pseudonymous**: it is linked to a random identifier (the Player ID described in Section 1.2(d), or an identifier created by one of the Google services in Section 1.2(b)) rather than to your name. Under the GDPR and similar laws, pseudonymous information is still **personal data**, and we treat it as personal data throughout this policy.

#### a) Data Stored on Your Device

- Quiz scores, results, and completion statistics from Genius Mode and Study Mode
- Per-country performance metrics (times asked, times correct, average response time)
- Game settings and preferences (sound, vibration, theme, language, auto-advance, daily reminder)
- Progress and achievement data (stars, best scores, best times)
- A local copy of your daily challenge state and of the rankings you opened, and results waiting to be sent while you are offline

This data is stored on your device using a local database (SQLite via Room), local preferences (Jetpack DataStore) and the local cache of the Firebase SDK. Most of it never leaves your device. What is sent to our backend is listed in Section 1.2(d).

#### b) Information Collected by Third-Party Services

MapGenius integrates the following services, all provided by Google. Each may collect information as described below.

**Google AdMob (Advertising)**

We use Google AdMob to display advertisements. AdMob may automatically collect:

- Device advertising identifier (Google Advertising ID / AAID) and the app set ID
- IP address (for ad delivery and to estimate the general location of the device)
- Device information (model, operating system version, screen size)
- Ad interaction data (impressions, clicks, engagement)
- App usage data relevant to ad delivery (app launches, session length, app foreground state)
- Diagnostic data (performance metrics such as app launch time and other diagnostic information collected automatically by the Google Mobile Ads SDK)

> **Prominent Disclosure (Google Play User Data Policy):** The Google AdMob SDK integrated in MapGenius collects your device's Advertising ID, IP address, and device information to deliver and measure advertisements. For users who have granted consent (EEA/UK/Switzerland) or who have not opted out of ad personalization (other regions), this data is also used to personalize the ads you see. This data is transmitted to Google's servers over an encrypted connection whenever the App is in use. You can control or stop this collection by: (1) opting out of ad personalization in your device settings, (2) purchasing MapGenius Pro, after which the App no longer requests or shows any ads (see Section 4.3), or (3) uninstalling the App.

For more information, see [Google's Privacy Policy](https://policies.google.com/privacy) and [How Google Uses Information from Sites or Apps That Use Our Services](https://policies.google.com/technologies/partner-sites).

**Google User Messaging Platform (Consent Management)**

In the EEA, the UK and Switzerland, the App uses Google's User Messaging Platform to show the advertising consent dialog and to store your choice on the device (Section 4.2).

**Google Analytics for Firebase (Usage Analytics)**

We use Google Analytics for Firebase to understand how the App is used, so we can fix problems and decide what to improve. It may collect:

- A Firebase app instance ID (a pseudonymous identifier for your installation of the App) and, where available, the device's Advertising ID
- Events describing in-app actions (screens opened, quizzes and daily challenges started and completed, hints, settings changed, ranking tabs opened, nickname or country changed, reminders received and opened, purchase steps and their outcome, advertising and consent outcomes)
- Properties of your installation (whether you own the Pro upgrade, total games and stars, preferred quiz type and continent, selected map theme, advertising consent state, Daily Map stars and rounds)
- Device and app information (model, operating system version, app version, language) and an approximate location (city or region) that Google derives from your IP address
- Your Player ID (Section 1.2(d)), set as the Analytics user ID so that events can be matched with the progress stored under the same Player ID. Your nickname is never sent to Analytics

We do not use Analytics data to identify you, and we do not combine it with any name, email address or account.

**Google Crashlytics (Crash and Error Reporting)**

We use Google Crashlytics to learn about crashes and errors so they can be fixed. When a problem occurs it may collect:

- A crash stack trace and the state of the App at the time of the error
- A Crashlytics installation identifier (pseudonymous, specific to your installation)
- Your Player ID, set as the Crashlytics user identifier so that an error can be matched with the progress it happened on
- Device and app information (model, operating system version, app version, available memory and storage)
- Diagnostic keys and log lines we attach to help interpret an error (for example, a billing response code)

**Firebase Authentication (Anonymous Sign-In)**

When the App is first opened, Firebase Authentication creates an **anonymous account** for your installation: a random identifier (UID), shown in the App as your Player ID. It is created silently, there is no sign-in screen, and it involves no name, email address, password or Google account. Google processes your IP address during sign-in to protect the service from abuse. If you uninstall the App or clear its data, the identifier is removed from your device and the App creates a new one on the next launch (Section 7).

**Cloud Firestore and Cloud Functions for Firebase (Our Backend)**

Your game results, ranking entries and player profile are stored in Cloud Firestore, a Google-hosted database, in the European Union (Google Cloud region `europe-west1`), and are written only by Cloud Functions that we operate in the same region. What is stored is listed in Section 1.2(d).

**Firebase App Check with Google Play Integrity**

Before the App may call our backend, Firebase App Check asks the Google Play Integrity API to confirm that the request comes from a genuine, unmodified copy of MapGenius installed from Google Play on a genuine Android device. This protects the daily limits and the rankings from automated abuse. Play Integrity evaluates the device and the app, not you, and returns a short-lived token; the assessment is made by Google. We receive only the verdict that the request may proceed, never a device fingerprint or an account name.

**Firebase Cloud Messaging and Firebase Remote Config (Daily Reminder)**

The optional daily reminder (Section 9) works like this: once an hour our backend sends one silent message to a group ("topic") named after an hour of the day, and every installation that has the reminder switched on listens to the topic that corresponds to about 8 PM in its time zone. The App then decides on the device whether to show a notification. To deliver these messages, Firebase Cloud Messaging uses a registration token and a Firebase installation ID that identify your installation to Google; the topic you listen to reveals only your approximate time zone. We do not store the registration token on our backend, and the reminder sends nothing from your device to us. Firebase Remote Config lets us switch the reminder off for everyone without an app update; it receives technical information such as the app version, language, country code and time zone.

**Google Play Billing**

When you make an in-app purchase, the transaction is processed entirely by Google Play. We never see your payment details. Google Play may collect:

- Purchase history for the App (product identifiers, purchase tokens, order numbers, timestamps)
- Google Account information necessary for transaction processing

When you start a purchase, the App passes Google Play a one-way SHA-256 hash of your Player ID (the "obfuscated account ID"), which Google uses to detect fraudulent purchases. What our backend does with a purchase is described in Sections 1.2(d) and 5.

For more information, see [Google Play's Terms of Service](https://play.google.com/about/play-terms/).

#### c) Android Backup and Device Transfer

If you have enabled Android's automatic backup, the App's local databases (your Genius and Study history, scores and statistics, and the local copy of your daily challenge state) may be backed up to your Google account. When you move to a new phone with Android's device-to-device transfer, those databases and the App's settings may be copied as well. These are Android system features controlled by your device settings, not by MapGenius, and we do not access, read, or manage these backups.

#### d) Player ID, Player Profile and Game Results (Stored on Our Backend)

The daily challenges (Daily Quiz, Daily Map and Daily Duel) and the global rankings need a server: the daily limits, the order in which content unlocks and the rankings cannot be trusted to a device clock. When the App is first opened with an internet connection, it creates a record on our backend for your installation, whether or not you play a daily challenge. The following is stored under your Player ID:

- **Player ID:** the anonymous identifier (UID) created by Firebase Authentication. The App shows it to you under **Settings → Data**, so that you can quote it in a data request (Section 7.2)
- **Nickname:** it starts as a generated one of the form "Genius-7K4M", derived from your Player ID by a one-way hash. You can replace it with a nickname of your choice under **Settings → Player profile** (3 to 16 letters, digits, spaces, "-" or "_"), at most once every 24 hours. It is shown to other players in the rankings (Section 1.2(e)), so do not use your real name or anything else that identifies you. Nicknames are checked against a list of offensive words, and we may reset a nickname that breaks the [Terms and Conditions](https://uplyfire.github.io/legal/mapgenius/terms)
- **Country:** shown as a flag next to your nickname in the rankings. Until you choose one yourself, it is taken from the region set in your device's language settings (not from your location, GPS or IP address). You can change it, or choose "No country", at any time under **Settings → Player profile**
- **Technical details:** the time zone of your device when the record was created (a zone name such as `Europe/Warsaw`, never coordinates), the App version, when the record was created and when the App last contacted the backend
- **Daily Quiz and Daily Duel results:** the quiz or duel identifier, the number of correct answers, score and time, whether the attempt was the first (ranked) one, and, for each question, which answer you chose, whether it was correct and how long you took. The 20 most recent attempts per quiz are kept to detect duplicate submissions
- **Daily Map progress:** which maps you have started, stars, best score, best time, number of plays and dates per map, and the daily allowance bookkeeping (which local day you last played and how many plays are left)
- **Genius Mode records:** for every quiz round where you set a new personal best, the round identifier, correct answers, question count, score and time. After you update to version 1.3.0, the best results already saved on your device are sent once, so that your earlier records count in the rankings. Study Mode is never sent
- **Ranking totals:** your points, times and number of completed rounds per mode, and which rankings you have entered
- **Pro status:** whether your Pro purchase has been verified with Google Play, the product, the Google Play order number, when Pro was granted, a one-way SHA-256 hash of the purchase token and, if Google Play later reports the purchase as refunded or cancelled, when Pro was withdrawn (Section 5)
- **Purchase claim record:** under the hash of each purchase token, the product, the order number, and the Player IDs (at most ten) that have claimed it. This exists so that a single purchase can be restored after a reinstall but cannot unlock Pro on an unlimited number of installations
- **Abuse protection:** a counter of how many backend calls the installation has made today, and a flag if we have excluded the Player ID from the rankings under the Terms
- **Per-quiz totals:** for each Daily Quiz and Daily Duel, the number of participants and the sums used for averages, which contain no Player ID

This data is not used for advertising, is not sold, and is not combined with data from any other source.

#### e) What Other Players Can See

The rankings show, for the top 20 players of each ranking (the overall ranking, one ranking per mode - Genius Mode, Daily Quiz, Daily Map and Daily Duel - and one ranking per Genius quiz round):

- your nickname and country flag
- your points, total time and, on the overall and per-mode rankings, the number of rounds you have completed

The ranking data downloaded by the App also contains the Player ID of each listed player in technical form. The App does not display it, but it is technically readable by other installations of the App. Your place in any ranking, including your place in each Daily Quiz and Daily Duel, is calculated by our backend and shown only to you. Your Daily Map progress, your individual answers, your country (when you are not in a top 20) and everything else in Section 1.2(d) are never shown to other players.

#### f) Information You Send Us

If you email us (for example through **Settings → Send Feedback**, which opens your own email app), we receive your email address and whatever you write, and use them only to answer you and to handle your request. We keep that correspondence for as long as needed to handle the request and to document how we handled data requests.

---

## 2. How We Use Information

We use the information described above for the following purposes:

| Purpose | Data Used | Legal Basis (GDPR Art. 6) |
|---------|-----------|---------------------------|
| Providing core App functionality (quizzes, scoring, progress tracking, settings) | Game data and preferences stored locally | Performance of a contract (Art. 6(1)(b)) |
| Running the daily challenges: daily limits, unlocking content in order, keeping your stars and results | Player ID and the game data in Section 1.2(d) | Performance of a contract (Art. 6(1)(b)) |
| Running the global rankings and showing your nickname, flag and scores to other players | Player ID, nickname, country, Genius records and daily results (Sections 1.2(d) and 1.2(e)) | Performance of a contract (Art. 6(1)(b)); for the country taken from your device region until you choose one, our legitimate interest (Art. 6(1)(f)) in a ranking that shows where players come from, which you can switch off at any time |
| Enforcing the nickname rules and keeping the rankings fair (excluding cheating or abusive players) | Nickname, results, Player ID | Legitimate interest (Art. 6(1)(f)) |
| Confirming that a Pro purchase is genuine before granting Pro on the backend, restoring it after a reinstall, and withdrawing it after a refund | Purchase token and its hash, order number, product, Player IDs that claimed it, Google Play verification result | Performance of a contract (Art. 6(1)(b)) and legitimate interest in preventing fraud (Art. 6(1)(f)) |
| Protecting the backend and the rankings from automated abuse | App Check / Play Integrity verdict, per-installation call counter, IP address processed by Google during sign-in and requests | Legitimate interest (Art. 6(1)(f)) - to keep the rankings honest and the service affordable |
| Sending the optional daily reminder | Firebase Cloud Messaging registration token and topic (approximate time zone) | Performance of a contract at your request (Art. 6(1)(b)); you can switch it off at any time |
| Understanding how the App is used and fixing crashes and errors | Analytics events and properties, crash reports, Player ID as analytics and crash user ID | Legitimate interest (Art. 6(1)(f)) - to keep the App working and improve it |
| Displaying personalized advertisements to support the free version of the App | Data collected by AdMob (Advertising ID, IP address, device info) | Consent (Art. 6(1)(a)) where the law requires it (EEA, UK, Switzerland), obtained via the consent dialog (IAB TCF v2.2 Consent Management Platform) |
| Displaying non-personalized advertisements | Contextual data, IP address and device information processed by AdMob | Legitimate interest (Art. 6(1)(f)) - to fund the free version of the App |
| Processing in-app purchases | Data processed by Google Play Billing | Performance of a contract (Art. 6(1)(b)) |
| Answering your emails and data requests | Your email address, message and Player ID | Legal obligation (Art. 6(1)(c)) for data protection requests, otherwise legitimate interest (Art. 6(1)(f)) |

The advertising consent dialog controls advertising. It does not switch off usage analytics or crash reporting, which we base on our legitimate interest; you can object to that processing at any time (Section 11).

We do **not** use any information for:

- Profiling or automated decision-making that produces legal or similarly significant effects (GDPR Art. 22). Our backend automatically rejects results that are technically impossible (for example, faster than a person can answer) and nicknames on our list of offensive words; these checks only affect your ranking entries, and you can contact us if you believe one was wrong
- Selling personal information (as defined under CCPA/CPRA)
- Direct marketing or email campaigns
- Cross-app or cross-device tracking initiated by us (note: Google AdMob may perform cross-context behavioral advertising as described in Section 4)

---

## 3. Third-Party Services

MapGenius relies on the following third-party services:

| Service | Provider | Purpose | Privacy Policy |
|---------|----------|---------|----------------|
| AdMob | Google LLC | Advertising (banner, interstitial, rewarded) | [Google Privacy Policy](https://policies.google.com/privacy) |
| Google User Messaging Platform (UMP) | Google LLC | Consent management for advertising (EEA, UK, Switzerland) | [Google Privacy Policy](https://policies.google.com/privacy) |
| Google Play Billing | Google LLC | In-app purchase processing | [Google Play Terms](https://play.google.com/about/play-terms/) |
| Google Play Developer API | Google LLC | Server-side verification of Pro purchases and of refunds | [Google Privacy Policy](https://policies.google.com/privacy) |
| Google Play Services | Google LLC | Core app infrastructure | [Google Privacy Policy](https://policies.google.com/privacy) |
| Google Analytics for Firebase | Google LLC | Usage analytics (how the App is used, to fix and improve it) | [Google Privacy Policy](https://policies.google.com/privacy) |
| Google Crashlytics | Google LLC | Crash and error reporting | [Google Privacy Policy](https://policies.google.com/privacy) |
| Firebase Authentication | Google LLC | Anonymous Player ID (no account, no sign-in screen) | [Google Privacy Policy](https://policies.google.com/privacy) |
| Cloud Firestore and Cloud Functions for Firebase | Google LLC | Storing and processing game results, rankings and player profiles (EU, `europe-west1`) | [Google Privacy Policy](https://policies.google.com/privacy) |
| Firebase App Check with Google Play Integrity | Google LLC | Verifying that a backend request comes from a genuine copy of the App | [Google Privacy Policy](https://policies.google.com/privacy) |
| Firebase Cloud Messaging | Google LLC | Delivering the optional daily reminder | [Google Privacy Policy](https://policies.google.com/privacy) |
| Firebase Remote Config | Google LLC | Switching the daily reminder on or off remotely | [Google Privacy Policy](https://policies.google.com/privacy) |

All of the services listed above are provided by Google. We do not sell your information, and we do not share it with data brokers or with any analytics or advertising provider other than those named in this table.

**Data Processing Agreements:** Our use of Firebase and Google Cloud is governed by Google's data processing terms, under which Google processes the data on our behalf as our processor. Our use of AdMob is governed by the [Google Ads Data Processing Terms](https://privacy.google.com/businesses/processorterms/) and the Google Ads Controller-Controller Data Protection Terms: Google acts as a data processor on our behalf for certain advertising operations, and as an independent data controller for its own purposes (for example, ad personalization and measurement) as described in Google's privacy policy. Applicable Standard Contractual Clauses (SCCs) cover international data transfers (Section 10).

---

## 4. Advertising

### 4.1 Types of Ads

MapGenius displays the following types of advertisements to users of the free version:

- **Banner ads:** Displayed at the bottom of some screens, such as the home screen, the continent and category selection, Study Mode and game screens
- **Interstitial ads:** Full-screen ads shown when a game starts, at most at every second game start across all modes, and never directly before or after a rewarded ad
- **Rewarded ads:** Optional video ads that you can choose to watch to receive a hint during a game

The App does not show app-open ads, and game summary screens carry no ads.

### 4.2 Ad Personalization and Consent

**EEA, UK and Swiss Users:** Before displaying personalized ads, the App presents a consent dialog compliant with the IAB Transparency and Consent Framework (TCF v2.2). You may grant or withhold consent for personalized advertising. If you withhold consent, only non-personalized, contextual ads will be shown. If you are in a region where this applies, you may change your consent choice at any time through: **Settings → Manage Ad Consent**.

**All Users:** You can further control ad personalization through:

- **Android device settings:** Settings → Google → Ads → Opt out of Ads Personalization
- **Resetting your Advertising ID:** Settings → Google → Ads → Reset Advertising ID
- **Deleting your Advertising ID:** On Android 12 and above, Settings → Google → Ads → Delete Advertising ID

The App limits advertising content to the PG rating (suitable for ages 7 and up, cartoonish violence at most).

### 4.3 Removing Ads

You may remove all advertisements permanently by purchasing MapGenius Pro within the App. Once the App has confirmed your purchase with Google Play, which normally happens within a second of opening the App, it no longer requests or shows any ads. The Google Mobile Ads SDK remains part of the App and may still start up and contact Google, but no ads are requested for Pro users.

---

## 5. In-App Purchases

MapGenius offers a single in-app purchase:

- **MapGenius Pro** - a one-time, non-recurring lifetime purchase that removes all advertisements and unlocks all premium content and features (Section 4 of the [Terms and Conditions](https://uplyfire.github.io/legal/mapgenius/terms)).

All purchases are processed by Google Play. We do not collect, process, or store your payment information. Purchases are tied to your Google account and can be restored on any device signed into the same account.

To unlock Pro in the daily challenges, the App sends the purchase token issued by Google Play to our backend. The backend checks it with the Google Play Developer API, acknowledges the purchase if needed, and stores the result as described in Section 1.2(d). The purchase token itself is not stored: we keep only its one-way SHA-256 hash, together with the order number and product. Every few hours the backend also asks Google Play for purchases that were refunded or charged back, and withdraws Pro from the Player IDs that claimed such a purchase.

Refunds are governed by [Google Play's refund policy](https://support.google.com/googleplay/answer/2479637).

---

## 6. Data Storage and Security

### 6.1 Local Storage

Game data on your device is stored using:

- **SQLite database** (via Room ORM) for Genius and Study history, country statistics, and user progress
- **Jetpack DataStore** and Android preferences for app settings, the reminder state and results waiting to be sent
- **The Firebase SDK's local cache** for a copy of your daily challenge state and of the rankings you opened

This data stays in the App's private storage. What is sent to our backend is listed in Section 1.2(d).

### 6.1a Backend Storage

Backend data is held in Cloud Firestore in the European Union (Google Cloud region `europe-west1`). Security rules deny **every** write from the App: nothing is stored unless one of our Cloud Functions decides to store it, after checking the request.

The App may read only:

- your own record, results and ranking document (never anyone else's)
- the published lists of Daily Quizzes and Daily Duels
- the ranking boards, each holding the top 20 entries described in Section 1.2(e)

Purchase claim records are readable by no installation at all.

### 6.2 Security Measures

- All local data is stored in the App's private storage directory, inaccessible to other applications
- The App itself loads no remote scripts or code. Advertisements are an exception by nature: ad creatives are fetched and rendered by the Google Mobile Ads SDK, which may load remote content and scripts supplied by Google and its advertising partners
- The WebView component used for map rendering loads only local assets bundled with the App
- Network communication is limited to the Google services listed in Section 3
- All network traffic uses HTTPS/TLS; unencrypted connections are disabled in the App's network security configuration
- Every backend call must carry a valid App Check token and a valid anonymous sign-in, and the backend limits how many calls one installation can make per day
- Access to the backend console is limited to the developer

---

## 7. Data Retention and Deletion

### 7.1 Retention

| Data | Where | How long we keep it |
|------|-------|---------------------|
| Genius and Study history, statistics, settings | Your device | Until you reset your progress, clear the App's data or uninstall the App |
| Player ID, profile, results, ranking entries, Pro status (Section 1.2(d)) | Our backend (EU) | Until you ask us to delete them (Section 7.2) or we discontinue the daily challenges and rankings. They are not deleted automatically when you uninstall the App |
| Attempt history used to detect duplicate submissions | Our backend (EU) | The 20 most recent attempts per quiz |
| Daily call counter | Our backend (EU) | Reset every day |
| Purchase claim records (hash of the purchase token, order number, product) | Our backend (EU) | For as long as needed to prevent a purchase from being reused and to handle refunds; after a deletion request, without your Player ID |
| Technical request logs of our backend | Google Cloud (EU) | Normally 30 days |
| Crash reports | Google Crashlytics | 90 days |
| Analytics events | Google Analytics for Firebase | According to the retention period set in our Analytics property, at most 14 months for event-level data; aggregated reports contain no Player ID |
| Advertising data | Google AdMob | According to [Google's retention policies](https://policies.google.com/technologies/retention) |
| Your emails to us | Our mailbox | As long as needed to handle your request and to document how we handled it |

### 7.2 Deletion

**Data on your device** can be deleted at any time:

- **In-App:** Open **Settings** → tap **"Reset All Progress"** → confirm in the dialog. This deletes your Genius and Study history, scores and statistics on this device. It does **not** delete your Player ID, profile, results or ranking entries on our backend
- **Clearing App Data:** Android Settings → Apps → MapGenius → Storage → Clear Data
- **Uninstalling the App:** Removes all locally stored data from your device

**Data on our backend.** Uninstalling the App or clearing its data removes the Player ID from your device. The App then creates a new Player ID on the next launch and can no longer reach the data stored under the old one; that old record is **not** deleted by uninstalling, and your nickname and scores remain in the rankings.

To have it erased, email **uplyfire@gmail.com** and include your **Player ID**, shown in the App under **Settings → Data** (tap it to copy). It is what lets us find your record. Please use the Player ID rather than your nickname: several players may use the same nickname, and only the Player ID points to exactly one record. If you only want your nickname and scores removed from the public rankings while keeping your progress, say so in your email.

Please copy the Player ID **before** you uninstall the App or clear its data. Once it is gone from your device, we may have no way of telling which pseudonymous record was yours, and we will say so rather than delete somebody else's.

We respond within 30 days. What we delete and what we keep is described in detail on our data deletion page (Section 7.3).

You can also change your nickname, or remove your country flag, yourself at any time under **Settings → Player profile**.

### 7.3 Web-Based Data Deletion Request (Google Play Requirement)

In accordance with Google Play's data deletion policy, the steps for requesting deletion, and the list of data that is deleted or kept, are published at: **[https://uplyfire.github.io/legal/mapgenius/data-deletion](https://uplyfire.github.io/legal/mapgenius/data-deletion)**

For data collected by Google AdMob, you may manage or delete your data through your [Google Account settings](https://myaccount.google.com/data-and-privacy). Purchase history managed by Google Play cannot be deleted through the App. To manage purchase records, visit [Google Play Order History](https://play.google.com/store/account/orderhistory).

---

## 8. Children's Privacy

MapGenius is an educational geography quiz application suitable for general audiences. It is intended for users aged 13 and over and is not directed at children under the age of 13. We do **not** knowingly collect personal information from children under the age of 13 (or the applicable age of consent in your jurisdiction).

The App does not:

- Require account creation or registration. The daily challenges and rankings use an anonymous Player ID created in the background (Section 1.2(b)); there is no sign-in, no password and no email address
- Ask for a name, email address, or other contact details. The ranking nickname is generated automatically; a player can replace it with a nickname of their choice, which the App and the Terms tell players must not be their real name or contain personal information
- Enable private messaging or any other communication between users
- Share data with third parties for behavioral advertising targeted at children

If you are a parent or guardian and believe your child has provided personal information through the App, for example a real name as a nickname, please contact us at the address provided in Section 15 with the Player ID shown under **Settings → Data**, and we will reset the nickname or delete the record.

**Note regarding advertising:** The App is not directed at children under 13, and we do not set the AdMob `tagForChildDirectedTreatment` flag. Google AdMob may serve personalized ads based on the device's advertising settings. If the device is used by a child, we strongly recommend that a parent or guardian either (a) configure the device's ad settings to disable ad personalization, (b) use a Google Family Link managed account, or (c) purchase MapGenius Pro to remove all advertising.

**Age of digital consent by jurisdiction:** For users in the EEA, the age of digital consent varies by member state (13-16 years under GDPR Art. 8). For users in Brazil, parental consent is required for processing data of children under 12 (LGPD Art. 14). If you are under the applicable age of consent in your jurisdiction, you must have a parent or legal guardian's permission to use the App.

---

## 9. Permissions

MapGenius requests the following device permissions:

| Permission | Purpose | Required? |
|------------|---------|-----------|
| `INTERNET` | Loading advertisements, processing in-app purchases, consent management, sending usage analytics and crash reports, and running the daily challenges and rankings (Section 1.2(d)). | Yes |
| `ACCESS_NETWORK_STATE` | Detecting whether a network connection is available, so that results saved offline are sent when the connection returns. | Yes |
| `POST_NOTIFICATIONS` | Showing the optional daily reminder. On Android 13 and above the App asks for your permission at the end of onboarding, on the home screen after an update, or when you switch the reminder on in Settings. You can refuse it, and you can switch the reminder off at any time under **Settings → Daily reminder**. | No |
| `VIBRATE` | Optional haptic feedback during quizzes. Can be disabled in the App's Settings. | Yes |
| `com.google.android.gms.permission.AD_ID` | Access to the Google Advertising ID, used by AdMob to deliver and measure advertisements and by Google Analytics for Firebase. Declared by the Google SDKs. | Yes |
| `ACCESS_ADSERVICES_AD_ID`, `ACCESS_ADSERVICES_ATTRIBUTION`, `ACCESS_ADSERVICES_TOPICS` | Android Privacy Sandbox interfaces used by the advertising SDK for ad measurement. Declared by the advertising SDK. | Yes |
| `com.android.vending.BILLING` | Processing in-app purchases through Google Play. | Yes |
| `com.google.android.c2dm.permission.RECEIVE` | Receiving messages from Firebase Cloud Messaging (the daily reminder). Declared by the Firebase SDK. | Yes |
| `com.google.android.finsky.permission.BIND_GET_INSTALL_REFERRER_SERVICE` | Allows Google Play to report how the App was installed. Declared by Google Play services. | Yes |
| `com.google.android.providers.gsf.permission.READ_GSERVICES`, `WAKE_LOCK`, `FOREGROUND_SERVICE` | Declared by Google Play services and Firebase components; not used directly by MapGenius features. | Yes |

Most of the permissions above are declared automatically by the Google SDKs the App includes, rather than requested by MapGenius itself. The only one that asks for your approval at runtime is `POST_NOTIFICATIONS`.

The App does **not** request access to: location, camera, microphone, contacts, storage, phone state, SMS, Bluetooth, or any other sensitive permissions.

---

## 10. International Data Transfers

Our backend data (Section 1.2(d)) is stored and processed in the European Union (Google Cloud region `europe-west1`). Google may access it for support and operations from outside the EU. Google AdMob, Google Play Billing, Google Analytics for Firebase, Crashlytics, Firebase Authentication, Firebase Cloud Messaging and Remote Config may process data on servers located outside your country of residence, including in the United States.

For transfers of personal data from the European Economic Area (EEA), the United Kingdom (UK), or Switzerland to countries that have not received an adequacy decision from the European Commission, Google relies on the following transfer mechanisms:

- **The EU-U.S. Data Privacy Framework** (and its UK and Swiss extensions), under which Google LLC is certified
- **Standard Contractual Clauses (SCCs)** approved by the European Commission
- **UK International Data Transfer Addendum** where applicable
- Additional technical and organizational safeguards as described in [Google's Data Transfer Frameworks documentation](https://policies.google.com/privacy/frameworks)

For transfers from Brazil, Google maintains compliance with LGPD requirements for international data transfers, including adherence to adequate levels of protection or contractual safeguards as required under LGPD Art. 33.

---

## 11. Your Rights

Depending on your jurisdiction, you may have the following rights regarding your data:

### 11.1 GDPR Rights (European Economic Area and United Kingdom)

If you are located in the EEA or UK, you have the following rights under the GDPR (and UK GDPR):

- **Right of access (Art. 15)** - Request a copy of the personal data we process about you
- **Right to rectification (Art. 16)** - Correct inaccurate or incomplete personal data. You can change your nickname and country yourself under **Settings → Player profile**
- **Right to erasure (Art. 17)** - Request deletion of your personal data (see Section 7.2)
- **Right to restrict processing (Art. 18)** - Limit how your personal data is processed
- **Right to data portability (Art. 20)** - Receive your personal data in a structured, commonly used, machine-readable format
- **Right to object (Art. 21)** - Object to processing based on legitimate interest, including usage analytics, crash reporting, the display of your country flag and non-personalized advertising
- **Right to withdraw consent (Art. 7(3))** - Withdraw consent for personalized advertising at any time (**Settings → Manage Ad Consent**) without affecting the lawfulness of processing based on consent before its withdrawal
- **Right to lodge a complaint (Art. 77)** - Lodge a complaint with your local data protection supervisory authority; in Poland, the President of the Personal Data Protection Office (Prezes Urzedu Ochrony Danych Osobowych, [uodo.gov.pl](https://uodo.gov.pl)). A list of EEA supervisory authorities is available at [https://edpb.europa.eu/about-edpb/about-edpb/members_en](https://edpb.europa.eu/about-edpb/about-edpb/members_en)

MapGenius holds no name, email address or account. The data on your device is under your control through the in-app reset and your device settings. For the data on our backend (Section 1.2(d)), send access, portability, objection and deletion requests to uplyfire@gmail.com and include your Player ID from **Settings → Data**. The Player ID is what lets us locate a pseudonymous record; without it we may be unable to identify your data (GDPR Art. 11), and we will tell you so. For data processed by Google AdMob, you may also exercise your rights directly with Google as described in [Google's Privacy Policy](https://policies.google.com/privacy).

**Data Protection Officer:** Given the nature and scale of our data processing activities, we are not required to appoint a Data Protection Officer under GDPR Art. 37. For all privacy-related inquiries, please contact us using the details in Section 15.

### 11.2 CCPA/CPRA Rights (California Residents)

If you are a California resident, you have the following rights under the CCPA as amended by the CPRA:

- **Right to know (Cal. Civ. Code Section 1798.100)** - Request disclosure of the categories and specific pieces of personal information collected, the categories of sources, the business or commercial purpose for collection, and the categories of third parties with whom personal information is shared
- **Right to delete (Section 1798.105)** - Request deletion of personal information we have collected
- **Right to correct (Section 1798.106)** - Request correction of inaccurate personal information
- **Right to opt-out of sale or sharing (Section 1798.120)** - Opt out of the sale of personal information and the sharing of personal information for cross-context behavioral advertising
- **Right to limit use of sensitive personal information (Section 1798.121)** - We do not collect sensitive personal information as defined by the CPRA
- **Right to non-discrimination (Section 1798.125)** - Not be discriminated against for exercising your privacy rights

**Categories of personal information:** identifiers (Player ID, Advertising ID and other device identifiers, ranking nickname), commercial information (whether you bought Pro, order number), internet or other electronic network activity (in-app events, game results, ad interactions), approximate geolocation derived from your IP address by Google, and the country you display in the rankings.

**Sale and Sharing of Personal Information:** MapGenius does **not** "sell" personal information as defined under the CCPA/CPRA. However, the use of Google AdMob may constitute "sharing" of personal information (specifically, the Advertising ID and device information) for the purpose of cross-context behavioral advertising as defined under CPRA Section 1798.140(ah). You have the right to opt out of this sharing by:

- Disabling ad personalization: Android Settings → Google → Ads → Opt out of Ads Personalization
- Deleting your Advertising ID (Android 12+): Android Settings → Google → Ads → Delete Advertising ID
- Purchasing MapGenius Pro to remove all advertising

To submit a verifiable consumer request, contact us at the email address in Section 15 and include your Player ID. We will respond within 45 days as required by law. You may also designate an authorized agent to make a request on your behalf.

**California "Shine the Light" (Cal. Civ. Code Section 1798.83):** We do not disclose personal information to third parties for their direct marketing purposes.

### 11.3 LGPD Rights (Brazilian Residents)

If you are located in Brazil, you have the following rights under the Lei Geral de Protecao de Dados (LGPD, Law No. 13,709/2018):

- **Confirmation of processing (Art. 18(I))** - Confirm whether your personal data is being processed
- **Access (Art. 18(II))** - Access your personal data
- **Correction (Art. 18(III))** - Correct incomplete, inaccurate, or out-of-date personal data
- **Anonymization, blocking, or deletion (Art. 18(IV))** - Request anonymization, blocking, or deletion of unnecessary or excessive data, or data processed in non-compliance with the LGPD
- **Portability (Art. 18(V))** - Request portability of your personal data to another service provider
- **Deletion (Art. 18(VI))** - Request deletion of personal data processed with your consent
- **Information about sharing (Art. 18(VII))** - Obtain information about public and private entities with which your data has been shared
- **Information about consent (Art. 18(VIII))** - Obtain information about the possibility of denying consent and the consequences of such denial
- **Revocation of consent (Art. 18(IX))** - Revoke consent at any time

**Legal basis for processing under LGPD:** Personalized advertising through Google AdMob is based on your consent (Art. 7(I)); non-personalized advertising, usage analytics, crash reporting and abuse protection are based on legitimate interest (Art. 7(IX)). The daily challenges, rankings and in-app purchases are based on contractual necessity (Art. 7(V)).

To exercise your LGPD rights, contact us at the email address in Section 15 and include your Player ID. We will respond within 15 business days as recommended by the ANPD (Autoridade Nacional de Protecao de Dados).

---

## 12. Changes to Our Data Practices

Version 1.3 of this policy covers MapGenius 1.3.0. Compared with version 1.2, it describes:

- the global rankings for every mode, including Genius Mode: your Genius records, including the best results already saved on your device, are now sent to our backend (Sections 1.2(d) and 1.2(e))
- the Daily Duel, whose results are stored like those of the Daily Quiz
- the player profile: a nickname of your choice and a country flag that other players can see
- the optional daily reminder (Firebase Cloud Messaging, Remote Config and the `POST_NOTIFICATIONS` permission)
- server-side verification of Pro purchases, including the order number and the withdrawal of Pro after a refund
- the Player ID being set as the user identifier in Google Analytics for Firebase and Crashlytics
- retention periods for each kind of data (Section 7.1)

Earlier versions said that data from Genius Mode stays on your device and that MapGenius does not host user-generated content. Both statements no longer apply from version 1.3.0 of the App.

We do not currently use any analytics, advertising or reporting service other than those named in Section 3.

**If we enable an additional service, we will:**

1. Update this Privacy Policy and its version number
2. Clearly describe what additional data is collected and for what purpose
3. Update the Google Play Data Safety declaration accordingly

---

## 13. EU Digital Services Act (DSA) Disclosures

For users in the European Union, in accordance with Regulation (EU) 2022/2065 (the Digital Services Act):

- **Advertising transparency:** All advertisements displayed in the App are served by Google AdMob. We do not independently select, target, or curate the specific advertisements shown to you. Information about why a particular ad was shown to you is available through Google's "Why this ad?" feature displayed alongside each advertisement.
- **Recommender systems:** MapGenius does not use recommender systems or algorithmic content curation. Quiz content is determined by user-selected categories, continent filters, and difficulty levels, and by the fixed order of the daily challenges, not by profiling or automated recommendations. Rankings are ordered by points and time only.
- **Content moderation:** The only content players can publish is their ranking nickname (and the country flag they choose). Nicknames are checked automatically against a list of offensive words when they are set, and we may reset a nickname or exclude a player from the rankings if they break the rules in the [Terms and Conditions](https://uplyfire.github.io/legal/mapgenius/terms). You can report a nickname to uplyfire@gmail.com; how we handle reports is described in the Terms.
- **Point of contact:** For DSA-related inquiries, including notices from authorities and users, please contact us at uplyfire@gmail.com (see Section 15). We communicate in English and Polish.

---

## 14. Changes to This Privacy Policy

We may update this Privacy Policy from time to time to reflect changes in our practices, technology, legal requirements, or other factors. When we make changes:

- **For all updates:** We will update the "Last Updated" date and Policy Version number at the top of this document
- **For material changes** (new data collection, new third-party services, changes to data sharing): We will notify users through an in-app notice or the Google Play Store listing before the changes take effect
- **For non-material changes** (clarifications, formatting, updated links): Changes take effect upon posting

We encourage you to review this Privacy Policy periodically. Where changes affect processing activities that rely on your consent (such as personalized advertising), we will seek your renewed consent before applying the changes. For other changes, your continued use of the App after changes are posted constitutes your acknowledgment of the revised policy, to the extent permitted by applicable law.

---

## 15. Contact Us

If you have any questions, concerns, or requests regarding this Privacy Policy or our data practices, please contact us at:

**Uplyfire** (the controller of the personal data described in this policy)
Email: uplyfire@gmail.com

You may also contact us through the developer contact information listed on the [MapGenius Google Play Store listing](https://play.google.com/store/apps/details?id=com.uplyfire.mapgenius).

We aim to respond to all privacy-related inquiries within 30 days. For GDPR-related requests, we will respond within one month as required by Art. 12(3). For CCPA/CPRA requests, we will respond within 45 days as required by Sec. 1798.145. For LGPD requests, we will respond within 15 business days.

---

## 16. Additional Disclosures

### 16.1 Google Play Data Safety Section

In accordance with Google Play requirements, the following summarizes our data practices as declared in the Data Safety form. "Shared" follows Google Play's definition: data that Google processes on our behalf as our service provider (Firebase, Google Cloud, Crashlytics) is collected but not shared; data that Google AdMob uses for its own advertising purposes is shared.

| Data Category | Data Type | Collected? | Shared? | Purpose | Optional? |
|---------------|-----------|------------|---------|---------|-----------|
| Location | Approximate location (estimated from IP address by AdMob and Analytics, not from GPS) | Yes | Yes (AdMob) | Advertising, Analytics, Fraud prevention | No |
| Personal info | Name (ranking nickname) | Yes | No | App functionality | Yes |
| Personal info | User IDs (Player ID) | Yes | No | App functionality, Analytics, Fraud prevention | No |
| Personal info | Other info (country shown in the rankings, from device region settings or chosen by you) | Yes | No | App functionality | Yes |
| Financial info | Purchase history (Pro status, order number, hash of the purchase token) | Yes | No | App functionality, Fraud prevention, Analytics | Yes |
| App activity | App interactions (in-app events, ad interactions) | Yes | Yes (AdMob) | Analytics, Advertising, Fraud prevention | No |
| App activity | Other actions (game results, scores, times, answers in the daily challenges) | Yes | No | App functionality, Analytics, Fraud prevention | No |
| App info and performance | Crash logs | Yes | No | Analytics | No |
| App info and performance | Diagnostics | Yes | Yes (AdMob) | Analytics, Advertising, Fraud prevention | No |
| Device or other IDs | Advertising ID, app set ID, Firebase installation and app instance IDs, Crashlytics installation ID, Cloud Messaging token | Yes | Yes (AdMob) | Advertising, Analytics, App functionality, Fraud prevention | No |

Game data and preferences that stay on your device are not "collected" in Google Play's sense and are not listed.

**Data handling declarations:**
- **Encryption in transit:** Yes - all network communication uses HTTPS/TLS
- **Data deletion:** Users can delete local data via **Settings → Reset All Progress**, by clearing the App's data or by uninstalling the App, and can request deletion of the data held on our backend by email, as described at [https://uplyfire.github.io/legal/mapgenius/data-deletion](https://uplyfire.github.io/legal/mapgenius/data-deletion). For data held by Google (AdMob, Play), users should refer to [Google's data controls](https://myaccount.google.com/data-and-privacy)
- **Data is not sold:** We do not sell user data to third parties
- **Pro users:** The App requests no ads for Pro users, so AdMob collects no ad request or ad interaction data from them

### 16.2 Apple App Store Compatibility

If MapGenius becomes available on iOS, this Privacy Policy also covers the iOS version. On iOS:

- The App will use Apple's **App Tracking Transparency (ATT)** framework to request your permission before tracking your activity across other companies' apps and websites
- If you decline tracking, only non-personalized, contextual ads will be served
- You can change your tracking preference at any time via iOS Settings > Privacy & Security > Tracking
- The App Store "App Privacy" nutrition labels will match the data disclosures in this Privacy Policy

---

## 17. YouTube API Services

In addition to the MapGenius mobile application, Uplyfire operates **MapGenius
Publisher**, an internal, first-party tool that uses **YouTube API Services**
to upload MapGenius promotional videos to our own YouTube channel
(@mapgenius-app) and to read that channel's video statistics.

By interacting with our YouTube channel or with the MapGenius Publisher tool,
you also agree to the [YouTube Terms of Service](https://www.youtube.com/t/terms).
Google's handling of data in connection with YouTube API Services is described
in the [Google Privacy Policy](http://www.google.com/policies/privacy).

**What data the tool accesses and stores:**
- Our own channel's video metadata and performance statistics (views, likes,
  comments count, watch-time metrics), retrieved via the YouTube Data API and
  YouTube Analytics API.
- This data concerns only our own channel and our own videos. The tool does
  not access, collect, or store any personal data of YouTube users or viewers,
  and it serves no third-party users.
- Retrieved statistics are stored locally by Uplyfire for internal performance
  reporting and can be deleted at any time. They are never sold or shared.

**Revoking access:** authorized Google accounts can revoke MapGenius
Publisher's access to their YouTube data at any time via the
[Google security settings page](https://security.google.com/settings/security/permissions).

**Contact:** for any questions about our use of YouTube API Services, contact
uplyfire@gmail.com.

# Privacy Policy

**Last updated: May 14, 2026**

Uplyfire ("we", "us", or "our") operates the Compoundly mobile application ("the App"). This Privacy Policy explains how we collect, use, disclose, and safeguard your information when you use our App.

By using the App, you agree to the collection and use of information in accordance with this Privacy Policy.

---

## 1. Information We Collect

### 1.1 Information You Provide

- **Calculation Data**: Financial calculations you create and save (initial amounts, interest rates, investment periods, results). This data is stored locally on your device and is never transmitted to our servers.
- **User Preferences**: Settings such as preferred currency, language, and default calculator values. Stored locally on your device.

### 1.2 Information Collected Automatically

- **Advertising Data**: When ads are displayed, our advertising partner Google AdMob may collect device advertising identifiers, IP address, and general device information to serve and measure ads. See Section 4 for details.
- **Purchase Data**: When you make an in-app purchase, Google Play processes the transaction. We receive a purchase token and order ID to verify your purchase status. We do not collect or store your payment method, credit card number, or billing address.
- **Consent Data**: If you are located in the European Economic Area (EEA) or United Kingdom, the Google User Messaging Platform (UMP) SDK manages your ad personalization consent preferences. These preferences are stored locally on your device using the IAB Transparency and Consent Framework (TCF 2.0).
- **Analytics Data**: With your consent (Section 4.A below), the App uses **Firebase Analytics** to collect aggregate, pseudonymous usage data — which screens are viewed, which features are used, purchase outcomes, app version, OS version, device model, language, approximate country (derived from IP, IP itself is discarded), and a pseudonymous app instance ID. We do **not** transmit your calculation inputs (initial amount, interest rate, monthly contribution, tax rate, inflation rate), saved-calculation names, or any free-text content. See Section 3.4.
- **Crash Diagnostics**: With your consent (Section 4.A below), the App uses **Firebase Crashlytics** to send anonymous crash reports — stack traces, breadcrumbs, app version, device model, OS version. Used solely to diagnose and fix software defects. See Section 3.5.

### 1.3 Information We Do NOT Collect

- We do **not** require account creation or login.
- We do **not** collect your name, email address, phone number, or any other personal contact information (unless you voluntarily email us via the feedback feature).
- We do **not** collect precise location data (only approximate country derived from your IP for analytics, with your consent).
- We do **not** collect photos, files, or media from your device.
- We do **not** transmit your saved calculation inputs or names to our servers or to Firebase. Calculation data stays on your device.
- We do **not** operate any servers that receive your data directly. Data described in Section 1.2 is processed by Google's services on our behalf.

---

## 2. How We Use Your Information

We use the limited information described above solely for the following purposes:

| Purpose | Data Used | Legal Basis (GDPR) |
|---------|-----------|-------------------|
| Provide core calculator functionality | Calculation data, preferences | Contractual necessity |
| Display advertisements | Advertising identifiers via AdMob | Consent (EEA/UK) or Legitimate interest (other regions) |
| Process in-app purchases | Purchase tokens via Google Play | Contractual necessity |
| Restore purchases after reinstallation | Purchase verification via Google Play | Contractual necessity |
| Comply with legal obligations | As required by law | Legal obligation |

We do **not** sell, rent, or share your personal information with third parties for their own marketing purposes.

---

## 3. Third-Party Services

The App integrates the following third-party services, each with their own privacy policies:

### 3.1 Google AdMob (Advertising)

We use Google AdMob to display banner and interstitial advertisements. AdMob may collect:
- Device advertising ID (GAID/IDFA)
- IP address (for geographic ad targeting)
- General device information (model, OS version, screen size)
- Ad interaction data (impressions, clicks)

For EEA/UK users, personalized ads are shown only with your explicit consent via the UMP consent dialog. If you decline, you may still see non-personalized (contextual) ads, or no ads if consent is required for all ad serving.

**Google Privacy Policy**: https://policies.google.com/privacy
**Google Ads Privacy**: https://policies.google.com/technologies/ads

### 3.2 Google Play Billing

We use Google Play Billing for the one-time Pro plan purchase. Google Play processes payments and provides us with:
- Purchase token (to verify purchase validity)
- Order ID (transaction reference)

We do not receive or store your payment details.

**Google Play Terms**: https://play.google.com/about/play-terms/

### 3.3 Google User Messaging Platform (UMP)

For users in the EEA/UK, we use Google's UMP SDK to present a consent dialog in compliance with the EU General Data Protection Regulation (GDPR) and ePrivacy Directive. Your consent choices are stored locally on your device and can be changed at any time via Settings > Manage Ad Consent.

### 3.4 Firebase Analytics (Google LLC)

With your consent, we use Firebase Analytics to understand how the App is used in aggregate. Firebase Analytics processes:

- App usage events (which screens you viewed, which features you used, onboarding flow, purchase outcomes)
- Approximate country (derived from your IP at request time; the IP itself is then discarded)
- Device model, OS version, app version, language, screen size
- A pseudonymous app instance ID (not linked to your identity; reset when you uninstall or clear app data)

We do **not** send your calculation inputs, calculation names, contributions, interest rates, or any free-text content.

Consent Mode v2 is implemented: when you decline analytics consent, no Analytics data leaves your device.

**Firebase Privacy**: https://firebase.google.com/support/privacy
**Google Privacy Policy**: https://policies.google.com/privacy

### 3.5 Firebase Crashlytics (Google LLC)

With your consent, we use Firebase Crashlytics to receive anonymous crash reports. Crashlytics processes:

- Crash stack traces and breadcrumbs (the sequence of app events leading to the crash)
- App version, device model, OS version, language
- An anonymous installation ID (not linked to your identity)

Crash reports are used solely to diagnose and fix software defects. With analytics consent declined, no Crashlytics data leaves your device.

**Crashlytics Privacy**: https://firebase.google.com/support/privacy

---

## 4. Advertising, Analytics, and Your Choices

### 4.A Consent for Analytics and Crashlytics

For all users (regardless of region), we treat Firebase Analytics and Crashlytics as **opt-in**. The same consent dialog that handles ad personalization (Settings > Manage Ad Consent) also controls analytics and crash reporting:

- **Accept**: Analytics events and crash reports are sent to Firebase as described in Sections 3.4 and 3.5.
- **Decline**: Firebase Consent Mode v2 sets all signals (analytics_storage, ad_storage, ad_user_data, ad_personalization) to `denied`, and Crashlytics collection is disabled at the SDK level. No data leaves your device.
- **Change your choice**: at any time via Settings > Manage Ad Consent.

For users outside the EEA/UK where UMP doesn't show a dialog, analytics and crash reporting are enabled by default (consistent with the local legal basis of legitimate interest); you can still disable them via the same Settings entry where available.

### 4.B Advertising — For EEA/UK Users
Before displaying personalized ads, we request your consent through a GDPR-compliant consent dialog. You may:
- **Accept** personalized ads based on your interests
- **Decline** personalized ads (you may see contextual ads or no ads)
- **Change your choice** at any time in Settings > Manage Ad Consent

### 4.C Advertising — For All Users
You can limit ad personalization through your device settings:
- **Android**: Settings > Google > Ads > Opt out of Ads Personalization
- **Purchase Pro**: The Pro plan ($2.99, one-time) permanently removes all advertisements

### Ad-Related Identifiers
You can reset your advertising ID at any time through your device settings. This does not affect the App's functionality.

---

## 5. Data Storage and Security

### 5.1 Local Storage
All your data (calculations, preferences, consent choices) is stored locally on your device using:
- **SQLite Database** (Room): Saved calculations
- **SharedPreferences**: User settings (currency, language, default values)
- **IAB TCF 2.0 keys**: Consent preferences (managed by UMP SDK)

### 5.2 Cloud Backup
If you have Android cloud backup enabled, your saved calculations and non-sensitive preferences may be backed up to your Google account. Sensitive data (purchase tokens, ad preferences) is excluded from backups.

### 5.3 Data Security
We implement appropriate technical measures to protect your data:
- Purchase verification uses Google Play's secure API
- No data is transmitted to third-party servers (other than the advertising and billing services described above)
- ProGuard/R8 code obfuscation is enabled in release builds

---

## 6. Data Retention

- **Calculation data**: Stored until you delete it from the App, clear the App's data, or uninstall the App.
- **Preferences**: Stored until you change them, clear the App's data, or uninstall the App.
- **Purchase status**: Verified with Google Play on each app launch; local cache is kept until app data is cleared. Your purchase is permanently associated with your Google account by Google Play.
- **Consent choices**: Stored until you change them via Settings > Manage Ad Consent, or clear the App's data.

You may also submit a data deletion request via our website at: **https://uplyfire.github.io/legal/compoundly/data-deletion**

---

## 7. Your Rights

### 7.1 Under GDPR (EEA/UK Users)
You have the right to:
- **Access**: Know what data is processed about you
- **Rectification**: Correct inaccurate data
- **Erasure**: Delete your data ("right to be forgotten")
- **Restriction**: Limit how your data is processed
- **Portability**: Receive your data in a portable format
- **Object**: Object to data processing based on legitimate interest
- **Withdraw Consent**: Withdraw ad personalization consent at any time via Settings > Manage Ad Consent

Since all your data is stored locally on your device, you can exercise most of these rights directly:
- **Delete data**: Clear App data in Android Settings, or uninstall the App
- **Export data**: Use the App's built-in CSV/PDF export feature
- **Change consent**: Settings > Manage Ad Consent

For AdMob-collected data, contact Google directly: https://support.google.com/policies/answer/9581826

### 7.2 Under CCPA (California Residents)
You have the right to:
- **Know** what personal information is collected
- **Delete** your personal information
- **Opt-out** of the sale of personal information

We do **not** sell personal information. All data described in this policy is used solely for the purposes stated.

### 7.3 Under LGPD (Brazil)
You have similar rights to access, correct, delete, and port your data. Contact us using the information in Section 11.

---

## 8. Children's Privacy

The App is not directed to children under the age of 13 (or applicable age in your jurisdiction). We do not knowingly collect personal information from children. If you believe a child has provided us with personal information, please contact us and we will delete it.

---

## 9. International Data Transfers

Advertising data collected by Google AdMob may be transferred to and processed in countries outside your country of residence, including the United States. Google maintains appropriate safeguards for such transfers, including Standard Contractual Clauses approved by the European Commission.

---

## 10. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. Changes will be posted within the App. The "Last updated" date at the top indicates when the policy was last revised. Your continued use of the App after changes constitutes acceptance of the updated policy.

---

## 11. Contact Us

If you have questions, concerns, or requests regarding this Privacy Policy or your data:

**Email**: uplyfire@gmail.com
**Developer**: Uplyfire

For GDPR-related requests, we will respond within 30 days. For CCPA-related requests, we will respond within 45 days.

---

## 12. Summary Table

| Data Type | Collected By | Stored Where | Shared With | Your Control |
|-----------|-------------|-------------|-------------|-------------|
| Calculations | App | Device only | Nobody | Delete in App |
| Preferences | App | Device only | Nobody | Change in Settings |
| Ad identifiers | Google AdMob | Google servers | Google ad partners | Device settings / Consent |
| Purchase tokens | Google Play | Device + Google | Google | Linked to Google account |
| Consent choices | UMP SDK | Device only | Google (TCF string) | Settings > Manage Ad Consent |

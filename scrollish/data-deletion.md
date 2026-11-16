# Data Deletion — Scrollish

**Last Updated:** [PUBLICATION DATE] · Corresponds to Privacy Policy version 1.1

Scrollish (by Uplyfire) stores your learning data — your progress, streaks, saved cards, achievements, settings, and the optional name you choose — **on your device**. We do not keep this data on our servers and we do not maintain user accounts.

What leaves your device is (a) a small reminder record, while notifications are allowed for the App, (b) a Firebase installation identifier, a push token created by Google's messaging library and basic technical information used to receive operational settings, (c) analytics, crash and performance data processed by Google Firebase (with your consent in the EEA, UK and Switzerland; enabled by default elsewhere; you can turn it off everywhere), (d) your device's IP address whenever the App connects to Google, (e) if you use Android's backup, a copy of the App's progress database in your own Google Account, and (f) if you buy PRO, the order information that Google Play shows us, which we keep for our accounts. This page explains how to delete what can be deleted.

## Delete your data in the App

Open **Settings → Danger zone → "Delete all data"**, type DELETE and confirm. This:

- permanently deletes from your device all your progress, streaks, XP, achievements, saved cards, card reports, reminders and settings, and your optional name;
- instructs our backend to delete your reminder record and the anonymous Firebase account behind it (if you are offline, the App retries the next time it is online);
- switches notifications off;
- gives the App a new Google Analytics identifier and deletes crash reports not yet sent, so later Google Analytics events are not linked to your earlier ones (the Firebase and Crashlytics installation identifiers and, where it is collected, the Advertising ID stay the same).

It keeps your analytics choice (so an earlier "off" stays off) and a few technical records the App needs to work correctly, such as a note that the rating prompt was already shown, the operational settings, the record of your purchases and the Firebase identifiers. It does not delete:

- analytics, crash and performance data already sent to Google — that is deleted automatically at the end of its retention period, and our copies in Google BigQuery are kept as described in the Privacy Policy, Section 7.1; Google Analytics data and our BigQuery copies can also be deleted on request (below);
- copies of the reminder record in our database backups, which are kept for up to 8 weeks and used only to recover from data loss;
- the record of your recent registration requests, which is deleted about 24 hours after the last request;
- the copy in your Android backup, which is replaced at Android's next backup, normally within about a day; you can also delete backups in your Android or Google Account settings;
- backup files you exported yourself, and your purchase history, which Google Play manages.

## Other ways to delete your data

- **Turn off notifications:** in **Settings → Notifications** ("All notifications"), or in Android's notification settings for the App. This instructs our backend to delete your reminder record (after a change in Android's settings, the next time you open the App).
- **Turn off analytics:** in **Settings → About**, switch off **"Share anonymous usage data"**. Collection stops and the analytics data still stored on your device is deleted.
- **Clear app data:** Android Settings → Apps → Scrollish → Storage → Clear data. This deletes the data on your device only.
- **Uninstall the App:** removes all data stored on your device and stops reminders, but does **not** by itself delete the reminder record or the anonymous Firebase account. Use "Delete all data" before uninstalling; otherwise the reminder record is deleted automatically 90 days after the App last refreshed it.

## What the reminder record contains

A push token, which of our apps it is for, your time zone, the times at which the App may show a notification (your reminder times and a few other times that depend on the notification groups you have switched on), delivery-health information and a retention date, keyed to an anonymous identifier — **no name, no learning data, no email**. It is stored on our reminder backend in the European Union (Belgium) and deleted as described above, or automatically after 90 days without use. Copies can remain in our database backups for up to 8 weeks; we use them only to recover from data loss.

## Data managed by third parties

- **Firebase Analytics, Crashlytics and Performance Monitoring (Google):** collected only while analytics is on. Turn it off with the "Share anonymous usage data" switch; in the EEA, UK and Switzerland you can also use **Settings → About → "Ad privacy settings"**. Google's own controls are at [Google Account — Data & Privacy](https://myaccount.google.com/data-and-privacy).
- **Android backup (Google):** managed in your Android and Google Account settings.
- **Google Play:** subscription and purchase history is managed by Google Play. Visit [Google Play Order History](https://play.google.com/store/account/orderhistory).

## Request deletion by email

Email us at **[uplyfire@gmail.com](mailto:uplyfire@gmail.com)**. The data on our side is pseudonymous, so we cannot find it by your name or email address alone: tell us what you would like deleted, and we will ask only for the information we need to identify your installation. Where we can identify it, we will delete its reminder record, its anonymous Firebase account, its Google Analytics data and its rows in the copies we exported to Google BigQuery, and confirm when it is done (in Firebase itself, crash and performance data cannot be deleted per installation and is deleted automatically after 90 and 60 days); where we cannot identify it, we will tell you so. We respond within one month. Because your learning data is stored only on your device, we will guide you through the in-app steps above for that data.

## Contact

- **Name:** Uplyfire (the developer of Scrollish on Google Play)
- **Email:** [uplyfire@gmail.com](mailto:uplyfire@gmail.com)

Full details: [Privacy Policy](privacy-policy.md) · [Terms of Service](terms.md)

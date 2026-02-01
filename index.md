---
layout: default
title: Privacy Policy
---

# BatchBuddy Privacy Policy

**Last updated: January 31, 2026**

BatchBuddy ("the App") is a gig economy offer analysis tool for Android. This policy explains what data the App collects, how it is used, and your choices.

## 1. Data We Collect

### Approximate Location
- **What:** Your state and city, detected via device location services.
- **Why:** To apply the correct minimum wage rules (e.g., California Prop 22 city-specific rates).
- **Precision:** Location is converted to a 0.5-mile grid cell for crowd intelligence. Exact coordinates are never stored or transmitted.
- **Required:** No. Location is optional and can be skipped.

### Device Identifier
- **What:** A one-way SHA-256 hash of your Android ID. The raw ID is never stored or sent.
- **Why:** To prevent spam in crowd-sourced data submissions (one upload per device per 24 hours).

### Offer Analysis Data
- **What:** Details of offers analyzed by the App, including platform, pay amount, distance, item count, classification result, and whether you accepted or declined.
- **Why:** To power your history dashboard, earnings tracking, and CSV export.
- **Stored:** Locally on your device only. This data is not uploaded to any server.

### Crowd Intelligence Data (Optional)
If you opt in to crowd intelligence, the App collects anonymized statistics during normal use:
- Zone grid identifiers (0.5-mile precision, not exact locations)
- Number of offers seen per zone and hour
- Customer ID hashes (SHA-256, not actual names or IDs)
- Tip behavior changes (same, increased, reduced, or removed)
- Store name hashes (SHA-256, not actual names)
- Store ratings and parking difficulty

**All identifiers are irreversibly hashed before storage and transmission. No personal information is included.**

### Purchase History
- **What:** Subscription status (active, expired, etc.) via Google Play Billing.
- **Why:** To determine free vs. premium feature access.
- **Handled by:** Google Play Services.

### Screen Captures
- **What:** The App uses Android MediaProjection to capture screen frames from Instacart and Lyft for OCR text extraction.
- **Important:** Captured frames are processed entirely on your device using Google ML Kit. No screenshots or images are stored, uploaded, or transmitted. Frames are discarded immediately after text extraction.

## 2. Data We Share

### With Our Servers (GitHub)
If you opt in to crowd intelligence, anonymized data is uploaded once per day over WiFi to a private GitHub repository. This includes only the anonymized fields listed above (zone grids, hashed IDs, tip behavior, store ratings). No personal information is ever transmitted.

### With Google (Ads)
The App uses Google AdMob to show optional rewarded video ads for free-tier users. The Google Mobile Ads SDK may collect device identifiers, approximate location, and diagnostic data in accordance with [Google's privacy policy](https://policies.google.com/privacy). Premium users see no ads, and ad data collection does not apply to them.

You can manage your ad preferences through the in-app consent dialog (powered by Google's User Messaging Platform) or through your device's ad settings.

### With Google (Billing)
Subscription purchases are processed by Google Play Billing. Purchase tokens and subscription status are exchanged with Google Play Services. BatchBuddy does not collect or store your payment method details.

## 3. Data We Do NOT Collect
- Names, email addresses, phone numbers, or mailing addresses
- Precise GPS coordinates
- Contacts, photos, files, or calendar data
- Browsing history
- Health or fitness data

We do not use Firebase Analytics, Crashlytics, or any analytics SDKs.

## 4. Data Retention

| Data | Retention |
|------|-----------|
| Offer history (free users) | Automatically deleted after 90 days |
| Offer history (premium users) | Kept until you delete it |
| Crowd intelligence data | Automatically deleted after 30 days |
| Ad bonus credits | Expire after 24 hours |

## 5. Your Choices and Controls

- **Disable crowd intelligence:** Toggle off "Contribute to crowd intelligence" in Settings at any time. This immediately stops all data collection and uploads.
- **Ad consent:** Manage ad personalization preferences via the in-app consent dialog or your device settings.
- **Delete local data:** Uninstalling the App deletes all data stored on your device (database, preferences, and cache).
- **Request data deletion:** Submit a request through our [data deletion form](https://docs.google.com/forms/d/e/YOUR_FORM_ID/viewform) or email us at hello.birdsoftware@gmail.com. Note that all uploaded data is anonymized with irreversible hashes and cannot be linked back to any individual user.
- **Export your data:** Premium users can export their full offer history as a CSV file via the History screen.

## 6. Data Security

- All network traffic uses HTTPS encryption.
- All personal identifiers are hashed with SHA-256 before storage and transmission.
- Local data is stored in the App's private directory, inaccessible to other apps.
- GitHub access tokens are obfuscated in the application binary.

## 7. Children's Privacy

BatchBuddy is not directed at children under 13. We do not knowingly collect data from children. If you believe a child has provided data through the App, please contact us and we will delete it.

## 8. Changes to This Policy

We may update this policy from time to time. The "Last updated" date at the top will reflect the most recent revision. Continued use of the App after changes constitutes acceptance of the updated policy.

## 9. Contact Us

For questions about this privacy policy or data practices:

**Email:** hello.birdsoftware@gmail.com

---

*BatchBuddy is developed by Bird Software.*

---
layout: default
title: Pawlaris Privacy Policy
permalink: /privacy/
alt_en: /privacy/
alt_zh: /zh/privacy/
---

[繁體中文](../zh/privacy/)

# Pawlaris Privacy Policy

**Effective date: 2026-11-06**

Pawlaris ("the App") is developed and operated by Sentira Labs ("we", "us"). This policy explains what data we process when you use the App, why, who helps us process it, and how you can control it.

## Summary

- **No account required.** We do not collect your name, email, phone number or location.
- **No advertising or analytics trackers.** We do not track you across apps or websites.
- **Label photos are used only for that scan and are not stored.**
- **Your pet profiles and scan history stay on your device** and are not synced to the cloud.
- To count free analyses and the daily scan limit, our server stores **an App Store–issued identifier for the App and usage counts**. It contains no name or email and is not linked to what you scan.
- **Subscriptions are handled by Apple.** We never receive your payment information.

## 1. Data we process

### 1.1 Label photos

When you take or pick a photo of a pet food label, the App sends it to our server for text recognition (OCR) and turns the recognised text into nutrition and ingredient data.

- Photos are processed for that request only. **We do not store photos** on our servers or in cloud storage.
- Please photograph only the packaging. If a photo accidentally includes faces, documents or other personal information, that content is read during recognition but is not stored.
- The App reads only the photo you choose; it does not browse your photo library.

### 1.2 Pet information

To calculate a fit score and write feeding suggestions, the following is sent to our server with each analysis:

- Species (dog/cat), age, weight, life stage
- Allergens you selected
- Health conditions you selected (optional)

This is used for that analysis, the suggestion text and health-related ingredient notes. The server keeps only **species and life stage**, together with the scores, in an **anonymous scan record with no user identifier** (see 1.3). Age, weight, allergens and health conditions **are not stored**. Your pet's name stays on your device and is never sent to our server.

### 1.3 Anonymous scan records and product data

To improve scoring and build our product database, the server stores:

- **Product data**: brand, product name, ingredients and nutrition values read from the label. This is information about the product, not about you.
- **Anonymous scan records**: the product, pet species and life stage, scores, an optional price you entered, and a timestamp. These records **contain no account, device identifier or anything that identifies you**, and cannot be matched to the usage counts in 1.4.

### 1.4 Free analyses and daily scan limit

Each Apple ID gets 5 free full analyses and up to 20 photo scans per day. To count these, the App sends the Apple-signed app download record (AppTransaction) with its requests. After verifying Apple's signature, our server reads the **app identifier (appTransactionId)** from it and stores:

- **The number of free analyses used**: only the identifier and a count, with no timestamps and no record of which products were scanned.
- **Photo scan counts for today and yesterday**: older counts are deleted automatically, so no daily history builds up.
- **Scan tokens**: issued when a photo scan succeeds and deleted once the analysis completes; unused tokens are cleared automatically after they expire, and their creation time is recorded only to the hour.

Apple generates this identifier for the App and your Apple ID. It is not your Apple ID itself, contains no name, email or payment information, and does not let us identify who you are. It is never used for advertising or cross-app tracking. Because it stays the same for your Apple ID, deleting and reinstalling the App or switching phones does not reset your free analyses.

### 1.5 Subscriptions

Pawlaris Pro purchases, payments, renewals and refunds are handled entirely by Apple. **We never receive your payment information, name or email.**

If you subscribe, the App sends Apple-signed subscription transaction information with its requests so our server can confirm the subscription is active and skip the free-analysis count. The server verifies it for that request only and **does not store it**. Your subscription status is determined by Apple StoreKit on your device.

### 1.6 Data stored on your device

Pet profiles (including names), scan history, PawPoints, a cached subscription status and app settings are stored on your device (Apple SwiftData / UserDefaults). We cannot access them. Deleting the App deletes this data.

### 1.7 Server logs

Like most online services, our cloud host automatically records technical logs when it receives a request, which may include IP address, time and error details. We use them for operations, debugging and abuse prevention. They are deleted automatically under our cloud provider's default retention, and we do not use them to identify or track individuals.

### 1.8 Data we do not collect

- Accounts, names, email addresses, phone numbers
- Payment information (handled by Apple)
- Precise or coarse location
- Contacts, calendars, or health (HealthKit) data
- Advertising identifier (IDFA); the App does not ask for tracking permission
- Usage analytics or crash reports (the App uses no analytics or crash-reporting SDK)

## 2. How we use data

Only to:

1. recognise label text and calculate nutrition and fit scores;
2. generate personalised feeding suggestions and health-related ingredient notes;
3. count free analyses, confirm subscription status and enforce the daily scan limit;
4. maintain the product and ingredient database and improve scoring;
5. operate the server, fix errors and prevent abuse.

We **do not sell** your data and **do not use it for advertising**.

## 3. Service providers

The following providers process data on our behalf, only on our instructions and under their own privacy and data-protection terms:

| Provider | Purpose | Data processed |
|---|---|---|
| Google Cloud (Cloud Run, Cloud Vision) | Hosting our server; photo text recognition | Photos, request content, server logs |
| Anthropic (Claude API) | Structuring recognised text; reading the photo directly when OCR fails; writing suggestions | Photos or recognised text, pet information (including health conditions) |
| Supabase | Database | Product data, anonymous scan records, app identifiers and usage counts |

These providers' servers may be located outside your country or region (for example in the United States or Asia), so data may be transferred across borders.

Subscription purchases and payments are processed by Apple under its own privacy policy and do not pass through the providers above.

Apart from the above, and where required by law or needed to protect the safety of users or others, we do not share data with third parties.

## 4. Retention and security

- Photos: not stored; discarded after processing.
- Age, weight, allergens, health conditions: not stored.
- Subscription transaction information: not stored; verified per request only.
- App identifier and free-analysis count: kept while the service operates, so reinstalling does not reset the count.
- Daily photo scan counts: kept for today and yesterday only, then deleted automatically.
- Product data and anonymous scan records: kept while the service operates. Because they contain no identifiers, we cannot locate or delete a particular user's records.
- On-device data: kept on your device until you delete the App.

All traffic between the App and our server is encrypted with HTTPS.

## 5. Your choices and rights

- **Camera and photo access** can be turned off at any time in iOS Settings. You can still view existing records, but cannot scan new labels.
- **Health conditions are optional.**
- **Subscriptions** can be managed or cancelled at any time in iOS Settings → your name → Subscriptions.
- **Deleting data**: deleting the App removes all on-device data. The only server data related to you is the app identifier and usage counts, which contain no name, email or scan content.
- Depending on where you live (for example Taiwan's Personal Data Protection Act, the EU GDPR or the California CCPA), you may have rights to access, correct or delete your data. Contact us at the address below with any request or question.

## 6. Children's privacy

The App is not directed to children under 13, and we do not knowingly collect personal information from children.

## 7. Changes to this policy

If the App changes in ways that affect how data is handled (for example adding accounts or cloud sync), we will update this policy and its effective date, and highlight significant changes in the App or on this page.

## 8. Contact

Support<br>
Email: [pawlaris@sentiralabs.app](mailto:pawlaris@sentiralabs.app)

---

© 2026 Sentira Labs

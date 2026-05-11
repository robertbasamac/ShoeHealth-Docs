# Shoe Health Privacy Policy

**Effective Date:** May 11, 2026
**Owner:** Robert Iulian Basamac
**App:** Shoe Health (iOS) — App Store ID 6648781147

---

## 1. Summary (Plain English)

Shoe Health is built around one principle: **your training data belongs to you, and stays with you.**

- Your shoe profiles, workouts, and Apple Health data live on your device and your private iCloud container. We never transmit them.
- Premium purchases are handled by Apple; we never see your payment details.
- The App includes the **Meta SDK** to measure the performance of advertising campaigns we run on Facebook and Instagram. Meta receives a limited set of standard events (install, sessions, in-app purchase events) tied to anonymous device identifiers — and only with your permission for full attribution. The exact list is in Section 3.5, and you control it through the iOS tracking prompt.
- We do **not** operate our own servers, analytics platforms, or marketing email lists.

The full document below explains the same thing in detail and lists your rights under GDPR (EU/EEA/UK) and CCPA (California).

---

## 2. Who We Are

Shoe Health is developed by **Robert Iulian Basamac**, an independent developer based in Romania. For privacy questions, write to 📧 **basamacr@icloud.com**.

We are the data controller under GDPR for the limited data described in this Policy.

---

## 3. Data We Access

### 3.1 Apple Health (with your permission)

Shoe Health requests read access to selected Apple Health data so it can attribute workouts to specific shoes:

- **Running Workouts** — distance, duration, pace
- **Walking + Running Distance** — for cumulative wear tracking
- **Step Count** — used in internal wear calculations
- **Heart Rate** — displayed for context, not used in calculations
- **Running Power** — optional, displayed for reference only

You can grant or revoke each permission at any time in **Settings → Health → Data Access & Devices → Shoe Health**.

### 3.2 Shoe Profile Data (entered by you)

Brand, model, nickname, photo, purchase date, run-type assignment, plus the wear and statistics computed from your workouts. Stored on your device and synced through your private iCloud container.

### 3.3 In-App Purchase Data

When you buy Premium, Apple processes the transaction. We receive only an anonymous purchase token used to verify your entitlement on-device. We do **not** see your name, payment method, or billing address. See Apple's [Privacy Policy](https://www.apple.com/legal/privacy/) for how Apple handles your purchase data.

### 3.4 Diagnostic Data (Apple-managed, opt-in)

If you have enabled "Share with App Developers" in **iOS Settings → Privacy & Security → Analytics & Improvements**, Apple may share aggregated, anonymous crash and performance reports with us through App Store Connect. We use these only to diagnose bugs and improve stability. We never receive personally identifiable information through this channel.

### 3.5 Marketing Attribution (Meta SDK)

To measure the effectiveness of advertising campaigns we run on Facebook and Instagram, Shoe Health includes the Meta SDK (also known as the Facebook SDK for iOS). This SDK transmits a limited set of standard events to **Meta Platforms, Inc.** ("Meta") whenever the App is opened:

- **Install event** — fired once, the first time you open the App after installing it.
- **App activation and session events** — when you open the App and the duration of your session.
- **In-app purchase events** — when you start a free trial or buy a subscription: product identifier, currency, and transaction amount. Apple processes the actual payment; we never see your payment method, and Meta receives only the transaction event (no card data or billing details).
- **Technical context** — device model, iOS version, locale, time zone, App version, and your device's IP address (implicit from the network request).
- **Device identifiers** — a per-vendor anonymous identifier (**IDFV**) is always shared. Your advertising identifier (**IDFA**) is shared **only if you grant tracking permission** through the iOS App Tracking Transparency prompt.

We **never** share with Meta:

- ❌ Apple Health data (workouts, distance, heart rate, running power, steps)
- ❌ Your shoe profiles (brands, models, photos, nicknames, purchase dates, wear data)
- ❌ Any text you enter inside the App
- ❌ Your location

#### Your control

The first time you finish the onboarding flow, iOS shows a system prompt asking whether to allow tracking. You may also change this at any time in **Settings → Privacy & Security → Tracking → Shoe Health**.

- **"Allow"** — Meta receives your IDFA, enabling more accurate campaign attribution and audience matching with your Facebook/Instagram profile.
- **"Ask App Not to Track"** — Meta receives only anonymous, aggregated reports through Apple's privacy-preserving **SKAdNetwork** framework. No IDFA is shared, and no event-level data can be tied back to your social-media profile.

Either way, the technical context above and the IDFV are still sent. If you wish to send no events at all, you may uninstall the App.

#### Legal basis under GDPR

Where GDPR applies, our legal basis for sharing identifier-linked events with Meta is **your consent**, given through the ATT prompt (Art. 6(1)(a) GDPR). If you do not consent, only SKAdNetwork's aggregated reports — which carry no individual identifier — are exchanged, and the legal basis is our **legitimate interest** in measuring overall campaign performance in a privacy-preserving manner (Art. 6(1)(f) GDPR).

For details on how Meta processes data it receives from app developers, see Meta's [Privacy Policy](https://www.facebook.com/privacy/policy/) and their [Business Tools Terms](https://www.facebook.com/legal/terms/businesstools).

---

## 4. What We Do NOT Collect

- ❌ No name, email, account, or login
- ❌ No location, GPS, or geolocation data
- ❌ No transmission of Apple Health data — workouts, distance, heart rate, power, and steps never leave your device
- ❌ No transmission of your shoe profiles — brands, models, photos, nicknames, and wear data never leave your device
- ❌ No third-party analytics platforms beyond the Meta marketing-attribution events described in Section 3.5 (no Firebase, Mixpanel, Amplitude, Google Analytics, etc.)
- ❌ No device fingerprinting beyond the standard device context described in Section 3.5
- ❌ No first-party advertising shown inside the App

The App Store "App Privacy" labels reflect the limited tracking described in Section 3.5. All Health data, shoe profiles, and workout statistics remain on your device — they are never transmitted to us or to any third party.

---

## 5. How We Use Your Data

Apple Health data and your shoe profiles are used **exclusively** to:

1. Calculate per-shoe wear, total distance, and statistics.
2. Estimate retirement dates based on your training pace.
3. Generate rotation suggestions across your run types.
4. Trigger local notifications (overuse, wear-threshold, recovery, ready).

All of the above processing happens **on your device**. Apple Health data and your shoe profiles are never received, stored, or transmitted on our servers — we do not operate any servers that handle this data.

The marketing-attribution events described in Section 3.5 are used to measure how many users discover and install the App through advertising campaigns we run on Meta platforms, and to optimize those campaigns. They are not combined with your Apple Health data or shoe profiles in any way.

---

## 6. Storage and Security

- **On-device** — your shoe profiles are stored in the App's local SwiftData store.
- **iCloud** — synced through Apple's CloudKit using your private container; encrypted in transit and at rest by Apple.
- **Apple Health** — read in-memory only; never copied to a database, file, or server.
- **No third-party cloud, no third-party access.**

When you delete the App, all on-device data is removed by iOS. iCloud-synced data remains in your iCloud account until you delete it (Settings → [your name] → iCloud → Manage Storage → Shoe Health) or restore it on a new device with the same Apple ID.

---

## 7. Sharing of Data

We do not sell or rent your personal information. We share only the limited data described in Section 3.5 with one third party, and only for the marketing-attribution purpose stated there. The entities involved in the App's operation are:

- **Apple** — App Store distribution, Apple Health data access, iCloud sync, in-app purchase processing. Apple acts as an independent data controller for these flows under its own [Privacy Policy](https://www.apple.com/legal/privacy/).
- **Meta Platforms, Inc.** — the marketing-attribution events described in Section 3.5 only. Meta acts as an independent data controller for the events it receives, under its own [Privacy Policy](https://www.facebook.com/privacy/policy/). No Apple Health data and no shoe-profile data is ever shared with Meta.

---

## 8. Your Rights

### 8.1 GDPR (EEA / UK)

You have the right to:

- **Access** the data Shoe Health holds about you;
- **Rectify** inaccurate data;
- **Erase** ("right to be forgotten") your data — you can do this yourself by deleting the App and its iCloud data;
- **Restrict** or **object** to processing;
- **Portability** of your data;
- **Withdraw consent** at any time (revoke Health permissions, uninstall the App);
- **Lodge a complaint** with your local supervisory authority.

To exercise these rights, write to **basamacr@icloud.com**. We respond within 30 days.

### 8.2 CCPA (California)

California residents have the right to know what personal information is collected, the right to delete it, and the right not to be discriminated against for exercising privacy rights. Shoe Health does **not sell** personal information.

### 8.3 Other Jurisdictions

Where local privacy laws apply (e.g. LGPD in Brazil, PIPEDA in Canada, POPIA in South Africa), we honour the equivalent rights.

---

## 9. Children's Privacy

Shoe Health is **not directed at children under 13** (or under the digital-consent age in your country, where higher). We do not knowingly collect personal information from children. If you believe a child has provided us with information, contact us and we will delete it.

---

## 10. Data Retention

We do not retain personal data on external servers. Your data lives only on your device and in your iCloud account, controlled entirely by you. When you uninstall the App, on-device data is removed by iOS; iCloud data persists until you delete it through Apple's iCloud settings.

---

## 11. International Transfers

We do not collect or store user data on our own servers, so no international transfer happens directly through us. However, two of the data flows described above involve processing outside your home jurisdiction:

- **Apple** may process iCloud, App Store, and Apple Health data on infrastructure outside your home jurisdiction; this is governed by Apple's own policies and safeguards.
- **Meta** processes the marketing-attribution events described in Section 3.5 on infrastructure that includes data centers in the United States. For users in the EEA, the UK, and Switzerland, Meta relies on Standard Contractual Clauses and the EU-US Data Privacy Framework as transfer safeguards. Details are in Meta's [Privacy Policy](https://www.facebook.com/privacy/policy/).

---

## 12. Changes to This Policy

We may update this Privacy Policy as features evolve or laws change. The "Effective Date" at the top reflects the current version. Significant changes will be announced inside the App and on the App Store listing. We encourage periodic review.

---

## 13. Contact

For privacy questions, data requests, or media inquiries:
📧 **basamacr@icloud.com**

If you are based in the EEA or UK and remain unsatisfied with our response, you may contact your national data protection authority.

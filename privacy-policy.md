<?php
header('Content-Type: text/markdown; charset=utf-8');

echo <<<'MD'
# Privacy Policy — DualLens Pro

**Effective date:** June 16, 2026

This Privacy Policy describes how **BharatVantage LLP** (“we”, “us”, or “our”) collects, uses, discloses, and protects information when you use the DualLens Pro mobile application (“DualLens Pro”, “the App”), a dual-camera video and photo creation tool for content creators. By installing or using the App you agree to the practices described in this Policy.

## 1. Who We Are
- **Data Controller**: BharatVantage LLP
- **App Name**: DualLens Pro
- **Contact for privacy inquiries**: **[privacy@yourdomain.example]** (replace with your operational privacy contact email)

## 2. Summary (Key Points)
- DualLens Pro requires real-time access to the device **camera(s)** and **microphone** to record dual-stream video and audio and to synchronize teleprompter scripts.
- All video, audio, teleprompter scripts, and optional location geotags are **processed locally on the device** using an embedded **FFmpeg** engine. We **do not upload**, store, or monitor these raw media streams on our external servers.
- The App uses local storage (device gallery) and Android/iOS local storage APIs (e.g., `SharedPreferences` on Android) to save media assets, app settings, and user scripts.
- We integrate **Google AdMob** for advertising. AdMob and other third-party service providers may collect data (e.g., Advertising IDs) under their own policies.
- Because most data is stored and processed locally, you retain practical control over your data; deleting media from your gallery or clearing the App data removes it from your device.

## 3. Information We Collect & Why

### A. Information collected only on-device (no server transfer)
- **Camera & Microphone streams**
  - **Purpose:** Real-time dual-stream recording and teleprompter synchronization.
  - **Processing:** **All capture and processing of raw video and audio (including mixing, encoding, trimming and export) occurs locally on the device using an embedded FFmpeg engine.** These streams are **not uploaded** to our servers.
- **Teleprompter scripts and user-created content**
  - **Purpose:** Used to display and synchronize prompts during recording and for later editing.
  - **Storage:** Saved locally (e.g., `SharedPreferences`, local files) on the device unless the user manually exports or shares them.
- **Output media (photos & videos)**
  - **Purpose:** For user use, sharing, and saving to the device gallery.
  - **Storage:** Saved directly to the device gallery or chosen local storage location.
- **Optional Location Data (Geotagging)**
  - **Purpose:** If you enable geotagging for recordings, the App collects device location (GPS). Geotagging is **optional** and, when enabled, **location data is used and stored locally** with the media file’s metadata. The App does not transmit location data to our servers unless you explicitly choose to share exported media externally via other apps or services.

### B. Information collected by third parties
- **Google AdMob (advertising)**
  - **Purpose:** Ad delivery and analytics for monetization.
  - **Data:** Ad networks (including Google AdMob) may collect identifiers such as Advertising IDs, device identifiers, IP addresses, and other device-related information in accordance with their policies. We do not control how third parties use or retain such information; please review their privacy policies for details (for example, Google Privacy & Terms: https://policies.google.com/privacy).
- **Local persistence (SharedPreferences)**
  - **Purpose:** App settings, user preferences, and optional saved scripts are persisted locally using platform storage APIs (for example `SharedPreferences` on Android). This data stays on-device and is not transmitted by the App unless you choose to export or share it.

## 4. How We Use Information
We use information to:
- Provide, operate, and improve the App’s core features (local recording, editing, teleprompter synchronization).
- Save your media assets and preferences locally so that you can access and edit them.
- Enable advertising revenue (via Google AdMob) to support App development.
- Respond to user support and privacy-related requests.

## 5. On-Device Processing (Important)
- **All raw camera streams, microphone audio, teleprompter scripts, and optional geotagging are processed locally on your device using an embedded FFmpeg engine.**
- We **do not** upload raw camera footage, microphone audio, or user scripts to our servers for processing, storage, or review. The only exceptions are files you explicitly export or share via other apps or services (e.g., sharing a finished video to a cloud service or social network), or if a user explicitly opts into a cloud backup or sync feature (not provided by default).

## 6. Permissions & Access
The App will request only the permissions necessary for its functions. Typical permissions include:
- **Camera:** Required for front and rear camera capture.
- **Microphone / Record Audio:** Required for audio capture.
- **Local storage / Photos & Media access:** Required to save output media to the device gallery or selected storage location.
- **Location (optional):** Required only if you enable geotagging for your recordings.

We request these permissions at runtime and provide in-app explanations for why each permission is needed. You may revoke permissions via your device settings; some App features will then be unavailable.

## 7. Third-Party Services & Links
- **Google AdMob:** We use AdMob to serve advertisements. AdMob may collect device and usage data (including Advertising IDs). For details on how Google collects and processes data, see Google’s privacy resources: https://policies.google.com/privacy and AdMob help documentation.
- **SharedPreferences** (or equivalent local storage): Used solely for local persistence of app settings and saved scripts. This is local device storage and not an external third-party transmission.

## 8. Cookies & Similar Technologies
The App is a native mobile application and does not use browser cookies in-app. Third-party ad SDKs (such as AdMob) may use local identifiers or SDK-managed storage to deliver and measure ads. See the third-party provider’s privacy documentation for details.

## 9. Data Retention & User Control
- **Local retention:** Because the App primarily stores data locally, you control retention. Deleting media files from your device gallery or deleting saved scripts within the App removes those items from your device.
- **Clearing App data:** Clearing the App’s data via your device settings (or uninstalling the App and choosing to remove app data) permanently erases locally stored media, preferences, and scripts.
- **Third-party data retention:** Data collected by third parties (for example AdMob) is retained according to their policies, not ours. Consult the third party’s privacy policy for retention details.

## 10. Your Rights (GDPR & CCPA)

### A. GDPR (for users in the European Economic Area)
If you are located in the EEA, you have the following rights with respect to your personal data:
1. **Right of access** — request a copy of personal data we hold about you.
2. **Right to rectification** — request correction of inaccurate or incomplete data.
3. **Right to erasure (“right to be forgotten”)** — request deletion of your personal data (note: deleting local files on your device or clearing app data accomplishes deletion of locally stored content).
4. **Right to restriction of processing** — request restriction of processing where applicable.
5. **Right to data portability** — request a machine-readable copy of personal data you provided to us (note: since most data is local, exporting or sharing media and scripts from the App is the primary mechanism).
6. **Right to object** — object to processing based on our legitimate interests (where applicable).
7. **Right to withdraw consent** — withdraw consent at any time for processing that was based on consent (e.g., if any future optional features require consent).

To exercise these rights, contact us at **[privacy@yourdomain.example]**. We may ask to verify your identity before responding.

### B. CCPA (for residents of California)
If you are a California resident, you have the following rights:
1. **Right to Know** — request disclosure of the categories and specific pieces of personal information collected, sold, or disclosed.
2. **Right to Delete** — request deletion of personal information we maintain about you (note: local files can be deleted by you; for information retained by third parties (e.g., AdMob), please contact those providers).
3. **Right to Opt-Out of Sale** — you may opt out of the sale of personal information. Some advertising networks may be considered a “sale” under CCPA; you can opt out of interest-based advertising via Google Ads Settings (https://adssettings.google.com) and/System-level ad tracking or opt-out tools such as the Digital Advertising Alliance: https://optout.aboutads.info/?c=2&lang=EN.
4. **Right to Non-Discrimination** — you will not be discriminated against for exercising CCPA rights.

To submit a CCPA request, contact us at **[privacy@yourdomain.example]** and include “CCPA Request” in the subject line. For authorized agents acting on your behalf, we may require proof of authorization.

## 11. How to Exercise Your Rights
To exercise any privacy right listed above, please:
- Send an email to: **[privacy@yourdomain.example]** with a clear subject line (for example: “Data Access Request”, “Delete My Data”, “CCPA Opt-Out Request”).
- Include the email address associated with your account (if applicable), a brief description of your request, and a copy of a government-issued ID if necessary to verify identity for sensitive requests. We will respond within legally required timelines (e.g., 30 days where applicable), or notify you if more time is needed.

## 12. Children’s Privacy (COPPA)
- DualLens Pro is **not intended** for children under 13. We **do not knowingly collect** personally identifiable information from children under the age of 13. If we become aware that we have collected personal information from a child under 13 in a way that violates applicable law, we will take steps to delete such information. If you are a parent or guardian and believe that your child has provided us with personal information, please contact us at **[privacy@yourdomain.example]**.

## 13. Security
We implement reasonable organizational, technical, and administrative measures to protect data stored within the App and to reduce the risk of unauthorized access. Because the App stores media and scripts locally, the security of such data is also dependent on your device’s security (for example PIN, passcode, biometric locks, and device encryption). We encourage you to keep your device and OS updated and to use secure device settings.

## 14. International Transfers
Since the App processes and stores most user data locally, DualLens Pro does not transfer media or scripts to our servers by default. However, third-party services used by the App (such as Google AdMob) may process data in countries outside your jurisdiction. Those third parties are responsible for complying with applicable cross-border transfer rules and their own privacy obligations. Consult third-party policies for details.

## 15. Disclosure & Legal Requests
We may disclose information if required by law, regulation, or valid legal process (for example, a court order or law enforcement request). Because most user data is stored locally, DualLens Pro has limited ability to provide user-generated media unless the user exports or uploads content to our servers or expressly opts into a cloud backup service.

## 16. Changes to This Policy
We may update this Privacy Policy from time to time. We will post the revised policy with a new effective date. If we make material changes that affect your rights, we will take reasonable steps to inform you (for example, via an in-app notification).

## 17. Google Play Store Compliance
DualLens Pro follows Google Play policies regarding user privacy, permissions, and data safety. The App requests only permissions necessary for its functions and provides in-app explanations for each. If your device or platform requires disclosures (for example, Google Play’s Data safety form), we will provide accurate details there consistent with this Policy.

## 18. Third-Party Links & Exported Content
If you choose to export or share media or scripts from the App (for example, uploading a video to a social network or cloud storage), the recipient service’s privacy policy will govern how that service uses or retains the shared content. We are not responsible for those services’ practices.

## 19. Contact Us
For privacy questions, to exercise your rights, or to report a privacy concern, please contact:

BharatVantage LLP
Email: **[privacy@yourdomain.example]**
(Please replace [privacy@yourdomain.example] with your actual support or privacy contact email.)

## 20. Additional Resources
- Google Privacy & Terms: https://policies.google.com/privacy
- Google Ads Settings: https://adssettings.google.com
- Digital Advertising Alliance opt-out: https://optout.aboutads.info

### Acknowledgements & Notices
- **Legal basis (GDPR):** Where the App processes any personal data that is subject to GDPR, our lawful basis is typically **consent** (where applicable) or **performance of the App’s contract with you** (providing the app’s features). Because core media and teleprompter processing is local to your device, there is minimal centralized personal data processing by us.
- **Third-party policies:** Please review Google AdMob’s and other third-party providers’ privacy notices prior to use; they control and are responsible for their own data collection and uses.

MD;

?>

---
layout: default
title: Privacy Policy
brand: HandyBird
permalink: /licenses/handybird/privacy/
---

**Last Updated:** September 7, 2026

This Privacy Policy describes how HandyBird ("we," "us," or "our"), published by Deniz Şafak, collects, uses, and shares information when you use our mobile application ("App").

**Scope note:** This policy is written to cover the full monetized version of HandyBird — including advertising (Google AdMob), analytics (Google Analytics for Firebase), and optional in-app subscriptions (Google Play Billing / Apple StoreKit) — so it stays accurate as those features roll out. If your installed version does not yet include a given feature, the corresponding collection described in Sections 4, 5, and 7 does not yet occur; those sections apply if and when the feature is enabled in your version. Sections 4–5 and 7 therefore use conditional language ("if and when"); Section 6 (ML Kit) is written in the present tense because it describes functionality already in the App.

## 1. Our Privacy Approach: Local-First
Our core design principle is local-first processing. Media conversion (video, audio, image, document, PDF), text recognition (OCR), background removal, and document scanning all run **on your device**. Your personal files are never uploaded to our servers for conversion — we operate no conversion servers and have no user accounts, so we never see your files.

Exceptions to purely local processing are limited to the following, each described below: (a) advertising and analytics SDKs (Sections 4–5), which — if and when enabled in your version — communicate with Google; (b) one-time downloads of on-device ML models over the network (Section 6); (c) the in-app Privacy Policy / Terms screens, which fetch this policy text from our public documentation site so you always see the current version (Section 8); and (d) links you choose to open in external apps, such as map locations from scanned QR codes (Section 8).

## 2. Information We Collect Ourselves
We do not operate a registration system and we collect **no name, email address, phone number, or account data**. We operate no servers that receive your personal data. Specifically:

* **Your files stay on your device.** Files you select, convert, scan, or generate (including camera images, scanned documents, and OCR text) are processed locally and stored only in app-private or device-shared storage you control. They are never transmitted to us.
* **No first-party tracking.** We do not set our own cookies, fingerprint your device, or build advertising profiles.
* **Settings and preferences** (e.g., language, tool options, game history/scores) are stored locally on your device using on-device storage, and are deleted if you clear the app's data or uninstall the App.

The remaining data collection in the App comes exclusively from the third-party SDKs listed in Section 9, each governed by its own privacy documentation.

## 3. Device Identifiers and Technical Data
If and when the advertising/analytics SDKs are enabled in your version (Sections 4–5), Google may collect device identifiers (such as the Android Advertising ID, and the IDFA on iOS where permitted), IP address, device and OS information, app-interaction events, and diagnostic/crash data. Any such collection is performed by Google's SDKs under Google's privacy terms (see Section 9), not by our servers. We use any such data only in aggregated form (e.g., crash-free rates, feature usage) to maintain and improve the App.

We do not sell personal information. To the extent that sharing device identifiers with advertising partners could be characterized as a "sale" or "sharing" under California law (CCPA/CPRA), you may opt out as described in Sections 4 and 12.

## 4. Google AdMob (Advertising)
If and when the App displays advertisements, they are served by **Google AdMob**. (No advertising SDK is present in versions of the App that predate the ads rollout, in which case no ad-related collection occurs.)

* **What is shared:** If and when ads are enabled, then to serve and measure those ads, AdMob may collect or receive your device's advertising identifier, IP address, coarse location (derived from IP, not GPS), device information, ad-interaction data, and diagnostic signals. Google may use cookies or similar identifiers to serve personalized ads based on your interests. We do not provide Google with your files, contacts, or precise location.
* **Personalized vs. non-personalized ads:** If and when ads are enabled, then where supported, you may be shown personalized ads (based on interests/inferred data) or non-personalized ads (based only on contextual information such as the current app content, and coarse location). Non-personalized ads do not use your past behavior or interest profile.
* **Consent in the EEA/UK:** Before serving personalized ads to users in the European Economic Area or the United Kingdom, the App will present a consent screen from a Google-certified Consent Management Platform (Google UMP), as required by Google's [EU User Consent Policy](https://www.google.com/about/company/user-consent-policy/). Your choice will be stored on-device and honored for subsequent ad requests; you will be able to change it at any time from the App's settings (Privacy/Ad consent option) where provided, or by reinstalling the App.
* **Children and ad personalization:** If and when ads are enabled, ads served in contexts directed to children, or to users Google identifies as below the relevant age, are treated as non-personalized and do not use interest-based targeting, consistent with Google Play's Families Policy and applicable child-privacy rules (see Section 10).
* **Opt-out:** You can limit personalized advertising at any time through your device settings ("Delete advertising ID" / "Opt out of Ads Personalization" on Android; "Limit Ad Tracking" / "Ask App Not to Track" on iOS). Deleting or resetting your advertising ID does not remove ads, but reduces personalization.
* **Google's own terms:** Any ad data collected once ads are enabled is processed under the [Google Privacy Policy](https://policies.google.com/privacy) and Google's [Advertising data documentation](https://policies.google.com/technologies/ads).

## 5. Google Analytics for Firebase (Analytics)
If and when analytics is enabled in your version, the App uses **Google Analytics for Firebase** to understand aggregate usage (e.g., which features are used, conversion success rates, crash-free sessions) so we can fix bugs and improve performance. (Versions of the App that predate the analytics rollout contain no analytics SDK and perform no analytics collection.)

* **What is collected:** If and when analytics is enabled, the following would be collected: app-instance identifiers, device model/OS, app version, language/region, session and interaction events (screens viewed, features used), and crash/performance diagnostics. Analytics does not receive the content of your files, camera images, contacts, or precise location.
* **Retention:** Any Analytics data collected once the feature is enabled is retained for a maximum of **14 months** and is then automatically deleted by Google in accordance with our data-retention setting.
* **Opt-out:** Once analytics is enabled, collection can be disabled per device: on Android, via "Opt out of Ads Personalization" / deleting the advertising ID and, where offered, an in-app analytics toggle; on iOS, via App Tracking Transparency (the App does not request tracking permission, so IDFA-based collection stays off). Uninstalling the App stops all future collection. Google's explanations and controls are described in [Firebase Privacy and Security](https://firebase.google.com/support/privacy) and [Google's Business data documentation](https://policies.google.com/privacy).
* **Legal basis (EEA/UK):** Where required, analytics collection will rely on your consent, requested before collection begins (e.g., when you first open a version of the App that includes analytics); you may withdraw it at any time with effect for the future.

## 6. Google ML Kit (On-Device Machine Learning)
The App uses the following **Google ML Kit** APIs, and input processing for all of them happens **on your device** — your images and documents are not sent to Google for recognition:

* **Text Recognition (OCR):** extracts text from images and scanned PDFs locally (Latin and other script models run on-device). Recognized text never leaves your device except as part of files you yourself choose to save or share.
* **Subject Segmentation (background removal, Android only):** runs on-device. The segmentation model is downloaded to your device over the network — at app install time via Google Play Services (declared install-time dependency) — and thereafter runs fully offline. No image content is transmitted to download or use the model.
* **Document Scanner:** on Android, ML Kit's on-device document scanner (full mode, gallery import supported); on iOS, Apple's on-device VisionKit document camera. Scanned page images stay on your device.

Note: the ML Kit SDKs themselves collect limited device/app information, performance metrics, and diagnostics for Google's own analytics (encrypted in transit, not shared with third parties by Google), as documented in Google's [ML Kit data-disclosure guidance for Google Play](https://developers.google.com/ml-kit/android-data-disclosure) and [for the App Store](https://developers.google.com/ml-kit/ios-data-disclosure). ML Kit use is subject to the [ML Kit Terms & Privacy](https://developers.google.com/ml-kit/terms).

## 7. In-App Subscriptions (Payments)
The App may in the future offer optional paid subscriptions (e.g., an ad-free or premium tier); none are available in versions predating the subscriptions rollout. **If and when subscriptions are offered, all payments are processed exclusively by Apple (App Store / StoreKit) or Google (Google Play Billing).** We never see, collect, or store your credit-card numbers, bank details, or full billing credentials — those go directly to the store operator under its own terms ([Google Play Terms of Service](https://play.google.com/about/play-terms/); Apple Media Services Terms where applicable). The only purchase-related information we may process on-device is the store-provided entitlement status (active/expired) needed to unlock or lock premium features. Full subscription mechanics — plans, pricing, trials, renewal, cancellation, refunds — are governed by our [Terms of Service](https://denizsafak.github.io/licenses/handybird/terms/) and the applicable store's policies.

## 8. Permissions and Feature Mapping
The App requests device permissions only when the feature that needs them is used, and, except where stated, the resulting data never leaves your device:

| Permission | Feature that triggers it | Does the data leave the device? |
|---|---|---|
| Camera | QR/Barcode Scanner; Mirror (front-camera vanity mirror); Color Picker (live camera sampling); Document Scanner; picking a photo via camera | No — images are processed on-device (QR decoding, ML Kit OCR/segmentation). Nothing is uploaded by us. |
| Photo / Media library (images, video, audio) | Selecting files to convert; saving converted output to shared storage | No — file access stays local; on modern OS versions the system picker grants access only to files you choose. |
| Storage (legacy Android ≤ 9 only) | Reading/saving files on older Android versions | No — same local use as above. |
| Notifications | Stopwatch/Timer and Countdown completion alerts; Emergency-tool alerts; foreground-service status while a conversion runs in the background | No — notifications are generated locally. |
| Foreground service + battery-optimization exemption (Android) | Keeping long media conversions and active timers running when the App is backgrounded | No data transmission; a persistent system notification is shown while the service runs, as Android requires. |
| Sensors / motion (compass, spirit level, rotation) | Compass, Spirit Level, Vibration Monitor, and rotation-aware tools | No — sensor readings are used live on-device and are not stored or transmitted. |
| Microphone | Not currently requested by any feature. The permission framework supports it for potential future use; if a future feature requires it, this table will be updated before release. | N/A |
| Bluetooth | Not currently requested by any feature; reserved in the permission framework only. | N/A |
| Location (fine, Android ≤ 8 only, for Wi-Fi scanning) | Connecting to a Wi-Fi network from a scanned Wi-Fi QR code on older Android versions, where the OS requires location permission to scan networks | No — location is used by the OS only to authorize the Wi-Fi scan; we do not read, store, or transmit your location. The App has no GPS/map-tracking feature. |
| Internet | Loading ads (AdMob — if and when enabled); analytics/crash reporting (Firebase — if and when enabled); one-time ML model downloads; fetching this Privacy Policy / Terms text from our public docs site | Yes — limited to those purposes (see Sections 4–6 and below). |
| Contacts (via system UI only) | QR Scanner: saving a scanned vCard to your address book | Via the OS contact editor — you review and confirm; we do not read your existing contacts. |
| Calendar (via system UI only) | QR Scanner: adding a scanned calendar event | Via the OS calendar UI — you review and confirm. |
| Flashlight/torch, screen brightness, audio playback, vibration | Emergency tool (siren/flash), screen-brightness and volume helpers, game audio/haptics | No — device outputs only. |

Additional network-related disclosures:

* **In-app policy viewer:** the Privacy Policy and Terms screens inside the App fetch the current Markdown text of these pages from our public documentation repository (`raw.githubusercontent.com`) so you always see the latest version. This HTTPS request exposes only standard connection metadata (IP address, user agent) to GitHub as hosting provider; no personal content is sent.
* **QR actions you initiate:** opening a scanned location launches your installed maps app with those coordinates; opening a scanned link, phone number, email, or SMS opens the corresponding external app (browser, dialer, mail). Data is shared with those apps only because you tapped the action.
* **Wi-Fi QR:** joining a network from a scanned QR code shares the network credentials you scanned with the OS Wi-Fi service to establish the connection.

## 9. Third-Party SDKs and Their Policies
*Note: the AdMob, Firebase Analytics, Google Play Billing, and Apple StoreKit rows describe integrations covered for the monetized release; if your version does not include them, no corresponding collection occurs. The ML Kit, Play Services, GitHub, and OS-service rows apply as described.*
| SDK / Service | Purpose | Data types involved | Provider documentation |
|---|---|---|---|
| Google AdMob | In-app advertising | Advertising ID, IP address, device info, ad interactions, coarse location from IP | [Google Privacy Policy](https://policies.google.com/privacy); [Google Ads data](https://policies.google.com/technologies/ads) |
| Google Analytics for Firebase | Aggregate usage & crash analytics | App-instance ID, device/OS info, interaction events, diagnostics | [Firebase Privacy and Security](https://firebase.google.com/support/privacy) |
| Google Play Services (incl. ML model delivery) | ML model download, device APIs on Android | Device info, model-delivery diagnostics | [Google Privacy Policy](https://policies.google.com/privacy) |
| Google ML Kit (Text Recognition, Subject Segmentation, Document Scanner) | On-device OCR, background removal, document scanning | Images processed on-device; SDK diagnostics as above | [ML Kit Terms & Privacy](https://developers.google.com/ml-kit/terms); [Play data disclosure](https://developers.google.com/ml-kit/android-data-disclosure); [App Store data disclosure](https://developers.google.com/ml-kit/ios-data-disclosure) |
| Google Play Billing | Subscription purchases on Android | Purchase/entitlement status (payment credentials go to Google, never to us) | [Google Play Terms](https://play.google.com/about/play-terms/); [Manage your subscriptions on Google Play](https://support.google.com/googleplay/answer/7018481) |
| Apple StoreKit / App Store | Subscription purchases on iOS | Purchase/entitlement status (payment credentials go to Apple, never to us) | [Apple Standard EULA](https://www.apple.com/legal/internet-services/itunes/dev/stdeula/) |
| Apple VisionKit (iOS) | On-device document scanning on iOS | Scanned images processed on-device | [Apple Privacy Policy](https://www.apple.com/legal/privacy/) |
| GitHub (docs hosting) | Hosting/fetching policy text | Connection metadata (IP, user agent) | [GitHub Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-privacy-statement) |
| OS services (contacts, calendar, maps, dialer, mail) | Completing QR-code actions you tap | Only the data in the scanned code, passed to the app you chose | Governed by your OS vendor's privacy policy |

We have no control over third-party providers' practices; we encourage you to review the linked documents. Links were verified as current on the Last Updated date above; if a link has moved, search the provider's site for the document title.

## 10. Children's Privacy
HandyBird is a general-utility app whose primary audience is adults and older teens, and it is **not specifically directed to children under 13**. However, the "Lab" section contains games and playful tools (e.g., 2048, math game, finger picker, tap war, spin bottle, flip coin, arcade-style games, coloring/picker-style utilities) that may be appealing to children, so we treat the App as having a **mixed audience**:

* We do not knowingly collect personal information directly from children under 13 — we operate no accounts and collect no names, emails, or precise location from any user.
* If and when Google's advertising/analytics SDKs are enabled, ads shown in potentially child-appealing contexts are served as non-personalized ads without interest-based targeting, and analytics collection is minimized, consistent with Google Play's Families Policy, COPPA, and the Google Play data-safety requirements.
* The App is not designed for unsupervised use by young children; a parent or guardian should supervise a child's use, including any subscription purchase flow (minors may not enter paid subscriptions without a parent/guardian — see Terms of Service).
* If you are a parent or guardian and believe a child has provided personal information through the App (for example via a third-party SDK), contact us at denizsafak98@gmail.com and we will take reasonable steps to delete it and adjust handling.

Age-gating and store-level parental controls (Google Play parental controls, Apple Screen Time / Ask to Buy) remain the primary enforcement mechanisms; we encourage parents to enable them.

* **Content rating (separate from age eligibility):** Based on the App's actual content, HandyBird is expected to receive an all-ages content rating (for example, PEGI 3 in Europe via Google Play's IARC questionnaire, and 4+ on the Apple App Store) — meaning the content itself contains no violence, mature language, sexual content, gambling, or similar restricted material. A content rating is generated from the questionnaire answers given at submission time and may be reviewed by the rating authorities; the rating shown on each store's listing page is authoritative. This content rating is separate from, and does not change, the account, data-collection, and purchase eligibility rules in this section and in the Terms of Service: the App's mixed-audience status described above, and the 13+ age-eligibility requirement in the Terms, remain unaffected by the content rating.

## 11. Data Retention
* **Your files:** stored only on your device until you delete them; we hold no copies and cannot recover files lost to app deletion or device failure.
* **Analytics/diagnostics (Google) — if and when analytics is enabled:** retained up to 14 months (Section 5), then auto-deleted by Google.
* **Ad data (Google) — if and when ads are enabled:** retained per Google's policies linked in Section 9.
* **Purchase entitlements — if and when subscriptions are offered:** the store operators retain transaction records per their policies; on-device entitlement flags are removed when you cancel, let a subscription lapse, or uninstall the App.

## 12. Your Rights
### EU / UK (GDPR / UK GDPR)
We act as Data Controller for the limited technical data described above (primarily consent records and any correspondence you send us). You have the right to access, rectify, erase, restrict, port, and object to processing of your personal data, and to withdraw consent at any time with future effect. Because file content never reaches us, erasure requests concerning your files are fulfilled by deleting them from your device. Data held by Google (ads/analytics, if and when those features are enabled) must be exercised against Google via the controls in Sections 4–5 and Google's privacy pages; we will reasonably assist and forward requests we cannot fulfill ourselves. You may lodge a complaint with your local supervisory authority (e.g., the ICO in the UK or your EU member-state authority).

### California / US States (CCPA/CPRA and similar)
You have the right to know, delete, and correct personal information, to opt out of any "sale" or "sharing" of personal information (see Sections 3–4 for the advertising opt-out), to limit use of sensitive personal information (we collect none), and to non-discrimination for exercising these rights. Submit requests to denizsafak98@gmail.com; we will verify and respond within applicable statutory deadlines. We do not knowingly sell or share personal information of consumers under 16.

### Türkiye (KVKK)
We process the limited technical data above in compliance with Law No. 6698 (KVKK). Under Article 11 you may request to learn whether data is processed, obtain information, learn processing purposes and third-party recipients, request rectification, erasure, or anonymization, object to automated processing producing adverse results, and claim compensation for unlawful processing. Applications under KVKK may be sent to denizsafak98@gmail.com; we respond within 30 days as required.

### How to exercise your rights
Email denizsafak98@gmail.com with the subject "Privacy Request" and describe your request. Because we hold no accounts, we may need device-level details (e.g., app version, approximate dates, advertising ID if relevant) to locate SDK-held data, and we will direct you to Google/Apple controls where the data sits with them.

## 13. International Data Transfers
Google, Apple, and GitHub may process technical data on servers outside your country, including in the United States. Where personal data is transferred internationally out of the EEA/UK, the relevant providers rely on appropriate safeguards such as the EU Standard Contractual Clauses (SCCs) and the UK extension/addendum, supplemented by technical measures (notably HTTPS encryption in transit). Details are in each provider's documentation linked in Section 9. We ourselves transfer no file content anywhere.

## 14. Security
We protect your data primarily by architecture: local-only processing, no accounts, no servers holding your files, and encrypted (HTTPS) connections for the network uses in Sections 4–6 and 8. No method of transmission or storage is perfectly secure; you remain responsible for device-level security (screen lock, OS updates, backups).

## 15. Changes to This Policy
We may update this policy as the App evolves (e.g., new SDKs, permissions, or features). Material changes will be reflected in a new "Last Updated" date and the current text will be available both here and via the in-app viewer, which always fetches the latest version. Your continued use of the App after changes take effect constitutes acceptance of the updated policy.

## 16. Contact Us
Data controller: Deniz Şafak. For privacy questions, rights requests, or reports concerning children's data: **denizsafak98@gmail.com**.

# Privacy Policy for HomeAI

**Effective Date:** November 7, 2026  
**Last Updated:** November 7, 2026  
**Contact Email:** [neosdevshelp@gmail.com](mailto:neosdevshelp@gmail.com)

Welcome to **HomeAI** ("we", "our", or "us"). We respect your privacy and are committed to protecting your personal data in full compliance with Apple’s App Store Review Guidelines, the General Data Protection Regulation (GDPR), and the California Consumer Privacy Act (CCPA).

---

## 1. Information We Do NOT Collect
HomeAI operates on a **privacy-first, registration-free architecture**:
- **No Personal Identifiers:** We do not ask for or collect your name, email address, physical address, phone number, or social media handles.
- **No Third-Party Advertising Trackers:** We do not integrate third-party advertising SDKs (such as Google AdMob, Meta Audience Network, or Unity Ads) or track your IDFA (Identifier for Advertisers).
- **No Payment or Financial Details:** All in-app purchases and subscription transactions are processed directly by Apple via **StoreKit 2**. We never receive, process, or store credit card or bank details.

---

## 2. Information Processed to Provide the Service
To transform your rooms, building facades, and gardens with AI, HomeAI processes:
- **User-Selected Photos:** Photos you capture or pick from your device library are compressed and transmitted via HTTPS (TLS 1.3) to our dedicated AI inference processing servers.
- **Ephemeral Processing:** Uploaded images are used solely in real time to generate your requested redesign. The temporary processing cache is purged once generation completes. We never use your photos to train public foundational AI models.
- **Inpainting Masks & Custom Prompts:** Custom style selections, room categories, and brush mask strokes are transmitted only to instruct the AI render for your active generation session.
- **Anonymous Device Keychain Identifier:** A randomly generated UUID is stored in your device's hardware Secure Enclave Keychain (`kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly`) to maintain your credit balance and daily free generation allowance without requiring personal login credentials.

---

## 3. Local Device Storage
All saved designs and rendered images are stored **locally on your device** inside the application's sandboxed storage directory. You retain complete ownership over all designs generated using HomeAI.

---

## 4. In-App Purchases & Subscriptions
HomeAI offers optional Consumable Credit Packs and Auto-Renewable Subscriptions (Weekly and Annual Pro). These purchases are authenticated and fulfilled directly by Apple StoreKit 2. Apple provides cryptographically signed verification tokens (JWS) to unlock your credits without disclosing your identity or billing details to us.

---

## 5. Account & Data Deletion (App Store Guideline 5.1.1(v))
HomeAI provides an immediate, in-app data deletion mechanism:
- Navigate to **Profile & Settings > Delete Account & Data**.
- Tapping this permanently purges your local design index, removes all cached images, resets your Keychain credentials, and sends a purge request to clear any associated cloud session records.

---

## 6. Device Permissions
- **Camera (`NSCameraUsageDescription`):** Required only when capturing room, exterior, or garden photos directly within the app.
- **Photo Library (`NSPhotoLibraryUsageDescription`):** Required to select an existing room photo or blueprint for redesign.
- **Save to Photos (`NSPhotoLibraryAddUsageDescription`):** Required to export and save your final generated designs to your iOS Photos album.

---

## 7. Children's Privacy
HomeAI does not knowingly collect or solicit any personal information from children under 13 years of age.

---

## 8. Contact Us
If you have any questions or concerns regarding this Privacy Policy, please contact:
- **Support Email:** [neosdevshelp@gmail.com](mailto:neosdevshelp@gmail.com)

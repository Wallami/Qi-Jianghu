# Qi - Jianghu: Account & Data Deletion Request

**Effective Date:** November 2, 2026  
**Application:** Qi - Jianghu (Android / Web)  
**Developer:** Michael Cupofjava (`michael.cupofjava@gmail.com`)  
**Privacy Policy:** [Qi-Jianghu Privacy Policy](https://github.com/Wallami/Qi-Jianghu/blob/main/PrivacyPolicy.txt)

---

## 1. Overview
In compliance with Google Play Developer Data Safety policies and international privacy regulations (including GDPR and CCPA), players of **Qi - Jianghu** have the right to request the complete and permanent deletion of their account, authentication credentials, and all associated cloud save data.

You can request account deletion **either directly inside the app** or **externally via web/email** if you have uninstalled the application.

---

## 2. In-App Account Deletion (Recommended)
If you still have **Qi - Jianghu** installed on your mobile device:
1. Open the game and tap the **Account** tab (`◎`) on the bottom navigation bar.
2. Scroll to the bottom of the Account sanctuary to the **"Account Deletion & Data Privacy"** section.
3. Tap **"Delete Account & Wipe Cloud Data"**.
4. Read the warning prompt and confirm deletion.
5. Your authentication session, Cloud Firestore documents (`/users/{uid}`), Jade Slip backups, and local storage data will be deleted immediately, returning you to an unlinked guest state.

---

## 3. Web & External Deletion Request (Without App Installed)
If you have already uninstalled the application or cannot access your device, you can submit an external deletion request directly to the developer:

* **Contact Email:** `michael.cupofjava@gmail.com`
* **Email Subject Line:** `Account Deletion Request - Qi Jianghu`
* **Information to Include:**
  - The registered email address associated with your Google / Google Play account used to sign into the game.
  - Your Cultivator ID / UID (optional, if known).

### Verification:
To protect player security and prevent unauthorized erasure of accounts, requests must be dispatched from the registered email address linked to the account.

---

## 4. What Data Is Deleted
Upon processing an account deletion request:
* **Authentication Profile:** Your Firebase Authentication profile, registered email, and unique User Identifier (`UID`).
* **Cloud Save Data:** All Cloud Firestore documents under `/users/{uid}`, including cultivation progress, equipment inventories, spirit beast bonds, and Jade Slip backup records.
* **Diagnostic Logs:** Any temporary error reports or diagnostic logs linked to your Cultivator ID.

---

## 5. What Data May Be Retained
* **Non-Personal Aggregated Metrics:** Anonymized, aggregated system performance statistics that cannot be linked back to any individual identity.
* **Legal Compliance:** In rare cases where transaction or financial records are mandated by tax or legal statutes, only minimal necessary purchase transaction IDs may be retained in secure accounting archives.

---

## 6. Processing Timeline
* In-app deletions take effect **immediately**.
* Email requests submitted via `michael.cupofjava@gmail.com` are verified and processed manually within **7 to 14 business days**.
* Once deletion is completed, all cultivation progress and Jade Slip imprints are permanently expunged and cannot be recovered.


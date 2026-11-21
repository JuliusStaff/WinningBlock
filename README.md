# PRIVACY POLICY & DATA PROTECTION (GDPR)
**Winning Block**
*Last updated: November 2026*

This Privacy Policy describes how personal data of users of the **Winning Block** application (hereinafter referred to as the "Application" or the "Game") is collected, used, retained, and protected, in compliance with the **European Union General Data Protection Regulation (Regulation EU 2016/679 - GDPR)**, the **ePrivacy Directive (2002/58/EC)**, and applicable data protection legislation.

---

## 1. Data Controller
The Data Controller is:
- **Winning Block Development Team**
- Official Repository & Support: [https://github.com/JuliusStaff/BlockWinner](https://github.com/JuliusStaff/WinningBlock)
- Privacy Contact: via the official GitHub repository communication channels.

---

## 2. Categories of Data Processed

### A. Gameplay Data Stored Exclusively on Your Device (Local Storage)
Winning Block implements a strict **Privacy by Design** architecture:
- The game **does not require registration**, user accounts, or login credentials.
- Your gameplay progress — including high scores (*Best Score*), unlocked boost inventory (*Remove, Rotate, Shuffle, Revive*), audio preferences (*SFX, Music*), vibration settings, and advertising consent preference — is stored **exclusively on your device** via an AES-256 encrypted local save file (`user://pilot_save.dat`), with automatic migration from legacy plaintext files.
- **No gameplay progress data is transmitted, shared, or stored on remote servers owned by us.**

### B. Advertising Framework & Offline Privacy Status (Google AdMob)
Winning Block includes integration hooks for **Google Ireland Limited / Google LLC** ("Google AdMob") for optional rewarded videos and advertising.

> [!NOTE]
> **Current Privacy Status**: In the current release, all advertising services are **deactivated by default** (`ADS_ENABLED = false`). The game operates **100% offline and locally**, transmitting zero network telemetry, device identifiers, or tracking cookies to Google or third parties.

When advertising services are activated in future releases or store builds, Google AdMob and its certified partners may process:
- **Unique device identifiers:** Mobile advertising identifiers (Google Advertising ID - *GAID* on Android, or *IDFA* on iOS);
- **IP Address:** Used by Google for coarse city/country-level geolocation, fraud prevention, and security purposes;
- **Diagnostic and technical data:** Device model, operating system version, system language, screen resolution;
- **Ad interaction data:** Ad impressions, views, clicks, and completion of rewarded videos.

---

## 3. Purposes of Processing & Legal Bases (Art. 6 GDPR)

Data processing pursues the following purposes:

| Purpose | Legal Basis (GDPR) | Ad Type |
| :--- | :--- | :--- |
| **Core gameplay operation and progress saving** | **Performance of Service / Legitimate Interest** (Art. 6(1)(f)) | No profiled ads |
| **Delivery of non-personalized ads and generic rewarded videos** | **Legitimate Interest** (Art. 6(1)(f)) to support development costs and prevent fraud | Generic and contextual ads |
| **Delivery of personalized ads and profiling** | **Explicit and Free Consent of the Data Subject** (Art. 6(1)(a) and Art. 7) | Interest-based and profiled ads |

---

## 4. Legal Bases & Consent Management

- **Free and Optional Consent:** Consenting to personalized ads is completely optional. If the user rejects consent by selecting `"ESSENTIAL ONLY"`, the game remains fully functional and only generic, contextual ads will be displayed.
- **Withdrawal and Modification at Any Time:** You can modify or withdraw your consent at any time directly from within the game:
  > **Open the `⚙ OPTIONS` menu ➔ Tap `🛡 PRIVACY & GDPR SETTINGS` ➔ Select your new preference.**
  Withdrawal of consent does not affect the lawfulness of processing based on consent before its withdrawal.

---

## 5. Data Recipients & International Transfers

Data collected via AdMob is processed by Google as a processor or independent data controller. For more information on how Google manages data:
- [Google Privacy & Terms](https://policies.google.com/privacy)
- [How Google uses information from sites or apps that use our services](https://policies.google.com/technologies/partner-sites)

Transfers of data outside the European Economic Area (EEA) take place pursuant to the **EU-U.S. Data Privacy Framework** and standard contractual clauses (**Standard Contractual Clauses - SCC**) approved by the European Commission.

---

## 6. Data Subject Rights (Arts. 15-22 GDPR)

Pursuant to Regulation (EU) 2016/679, you have the right to:
1. **Access and Rectification:** Verify the processed data.
2. **Erasure (Right to be Forgotten):** Because all gameplay data is saved exclusively on your device, you can delete it completely at any time by uninstalling the application or clearing application cache/data in device settings (*Settings ➔ Apps ➔ Winning Block ➔ Clear Data*).
3. **Restriction and Objection:** Object at any time to processing for personalized advertising purposes.
4. **Lodge a Complaint:** If you believe data processing violates GDPR provisions, you have the right to lodge a complaint with a competent supervisory Data Protection Authority.

---

## 7. Protection of Minors (Art. 8 GDPR)

Winning Block is intended for a general audience and does not knowingly collect personal data from minors under 16 without parental consent or permission of a legal guardian.
If the user is under 16 years of age, they should use the application with `"ESSENTIAL ONLY"` active or with parental authorization.

---

## 8. Data Retention Period

- **Local Data:** Retained on the device until manual deletion or application uninstallation by the user.
- **Google AdMob Data:** Retained according to retention policies defined by Google LLC.

---

## 9. Changes to This Privacy Policy

We reserve the right to update or modify this Privacy Policy upon game updates or regulatory changes. Any material changes will be notified directly within the application upon subsequent launch.

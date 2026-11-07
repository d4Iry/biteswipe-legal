# BiteSwipe Privacy Policy

**Effective Date:** November 6, 2026

This Privacy Policy describes how BiteSwipe ("we," "us," or "our") collects, uses, and shares information about you when you use the BiteSwipe mobile application (the "App"). By using the App, you agree to the practices described in this policy.

---

## 1. Information We Collect

### 1.1 Information You Provide via Google Sign-In
When you sign in with your Google account through Firebase Authentication, we receive:
- Your **display name**
- Your **email address**
- Your **profile photo URL**

We do not receive your Google account password.

### 1.2 Location Information
To surface relevant restaurant options, we collect:
- **Precise GPS coordinates** when you grant location permission — used solely to find nearby restaurants for the current session.
- **Session location** — the location you set when starting a swipe session (which may be GPS coordinates or a city/area name) is stored in Firestore as part of the session record and is visible to other members of your group.

We do not store your location permanently on your user profile. Location data is stored only within session records for the duration of the session and group.

### 1.3 App Activity Data
- **Swipe history:** which restaurant cards you swiped yes or no on, and timestamps.
- **Group membership:** groups you create or join, group names, and member associations.
- **Chat messages:** text messages sent within group chats inside the App.

### 1.4 Usage Analytics
We collect anonymous or pseudonymous analytics to understand how the App is used, including:
- Session duration, feature interactions, and crash reports.
- Device type, operating system version, and app version.

This data is collected through Firebase Analytics (Google) and may be linked to your Firebase user ID.

### 1.5 Sponsored Content Interactions
When you view or swipe on a **Sponsored** restaurant card, we record that interaction (impression and/or swipe-right) for billing purposes with the sponsoring restaurant. This data is used to charge restaurants for placement and to improve relevance of sponsored content.

---

## 2. How We Use Your Information

| Purpose | Data Used |
|---|---|
| Core app functionality (group creation, restaurant matching) | Account info, swipe history, group membership |
| Restaurant search and display | Location (ZIP/city), Google Maps Places API |
| Sponsored card targeting and billing | Location, swipe history, sponsored interaction logs |
| App improvement and debugging | Usage analytics, crash reports |
| Communications (account notices, policy updates) | Email address |

We do **not** sell your personal information to third parties.

---

## 3. Third-Party Services

The App integrates the following third-party services, each governed by their own privacy policies:

| Service | Purpose | Privacy Policy |
|---|---|---|
| Firebase Authentication (Google) | Sign-in and identity | https://policies.google.com/privacy |
| Cloud Firestore (Google) | Data storage | https://policies.google.com/privacy |
| Firebase Analytics (Google) | Usage analytics | https://policies.google.com/privacy |
| Google Maps Places API | Restaurant data and search | https://policies.google.com/privacy |
| Google Play Services | App distribution and payments | https://policies.google.com/privacy |

**Future services:** We may integrate additional advertising networks or analytics providers in the future. This policy will be updated before any such integration, and you will be notified.

---

## 4. Data Sharing

We share your data only in the following circumstances:

- **Within your group:** Group members can see each other's display names and profile photos. Swipe results (match/no-match) are shared with the group only in aggregate (i.e., "It's a match!" — not individual swipes).
- **Service providers:** We share data with Firebase/Google as a data processor to operate the App. Google's data processing terms apply.
- **Sponsored restaurants:** Restaurants receive aggregate impression and swipe-right counts. They do **not** receive your name, email, or individual identity.
- **Legal requirements:** We may disclose information if required by law, court order, or to protect the rights and safety of our users.
- **Business transfers:** In the event of a merger, acquisition, or sale of assets, user data may be transferred. We will notify you via the App or email beforehand.

---

## 5. Data Retention

| Data Type | Retention Period |
|---|---|
| Account information | Until account deletion |
| Swipe history | 12 months from creation, or until account deletion |
| Group data and chat messages | Until the group is deleted by all members, or until account deletion |
| Usage analytics | As determined by Firebase Analytics (typically 14 months) |
| Sponsored interaction logs | 24 months for billing and audit purposes |

You may request deletion of your account and associated data at any time (see Section 7).

---

## 6. Data Security

We use industry-standard security practices including:
- Firebase's built-in encryption in transit (TLS) and at rest.
- Firestore Security Rules to enforce per-user data access controls.
- Principle of least privilege for backend service accounts.

No system is completely secure. In the event of a data breach affecting your rights, we will notify affected users as required by applicable law.

---

## 7. Your Rights

### 7.1 All Users
You may:
- **Access** your personal data by contacting us.
- **Delete** your account and associated data by contacting us at tthayer16@gmail.com or using the in-app account deletion feature (where available).
- **Correct** inaccurate data by updating your Google account profile.

### 7.2 GDPR Rights (EEA, UK, and Switzerland Residents)
If you are located in the European Economic Area, the United Kingdom, or Switzerland, you have the following additional rights under the General Data Protection Regulation (GDPR) or applicable local law:

- **Right of access** (Art. 15 GDPR): Request a copy of personal data we hold about you.
- **Right to rectification** (Art. 16 GDPR): Request correction of inaccurate data.
- **Right to erasure / "Right to be Forgotten"** (Art. 17 GDPR): Request deletion of your personal data, subject to our legal obligations to retain certain records.
- **Right to restriction of processing** (Art. 18 GDPR): Request that we limit how we use your data.
- **Right to data portability** (Art. 20 GDPR): Request your data in a machine-readable format.
- **Right to object** (Art. 21 GDPR): Object to processing based on legitimate interests, including profiling for ad targeting.
- **Right to lodge a complaint** with your local supervisory authority.

**Legal basis for processing:** We process your data on the following bases:
- **Contract performance** (Art. 6(1)(b)): Account data, group functionality, and core features necessary to deliver the service.
- **Legitimate interests** (Art. 6(1)(f)): Usage analytics, security, and sponsored content interaction logging.
- **Consent** (Art. 6(1)(a)): Location access (you may withdraw consent at any time via device settings).

### 7.3 CCPA Rights (California Residents)
If you are a California resident, the California Consumer Privacy Act (CCPA) as amended by the CPRA grants you the following rights:

- **Right to Know:** Request disclosure of the categories and specific pieces of personal information we have collected about you.
- **Right to Delete:** Request deletion of personal information we have collected from you, subject to certain exceptions.
- **Right to Correct:** Request correction of inaccurate personal information.
- **Right to Opt-Out of Sale or Sharing:** We do not sell your personal information. We do not share your personal information with third parties for cross-context behavioral advertising. If this practice changes, we will update this policy and provide an opt-out mechanism.
- **Right to Non-Discrimination:** We will not discriminate against you for exercising any of your CCPA rights.

**Categories of personal information collected (CCPA categories):**
- Identifiers (name, email, user ID)
- Commercial information (subscription status, sponsored interaction history)
- Internet/electronic network activity (swipe history, session analytics)
- Geolocation data (precise GPS coordinates and session location)
- Communications (chat messages)

To exercise any of the above rights, contact us at tthayer16@gmail.com.

---

## 8. Children's Privacy

BiteSwipe is not directed at children under the age of 13. We do not knowingly collect personal information from children under 13. If you believe we have inadvertently collected such information, please contact us immediately at tthayer16@gmail.com and we will delete it promptly.

---

## 9. Changes to This Policy

We may update this Privacy Policy from time to time. When we do, we will update the "Effective Date" at the top of this page and, for material changes, provide notice via the App or email. Continued use of the App after changes become effective constitutes your acceptance of the updated policy.

---

## 10. Contact Us

If you have questions, requests, or concerns about this Privacy Policy, please contact:

**BiteSwipe**  
Email: tthayer16@gmail.com  
Michigan, United States

---

*This Privacy Policy was drafted for Google Play Store submission and is intended to comply with GDPR, CCPA/CPRA, Google Play Developer Program Policies, and applicable U.S. state privacy laws. Founder should review before public launch and obtain legal counsel before monetization features go live.*

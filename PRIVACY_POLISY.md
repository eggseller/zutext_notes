# Privacy Policy for Zutext

**Last Updated**: January 29, 2026
**Effective Date**: January 29, 2026

---

## 1. Introduction

Welcome to Zutext! This Privacy Policy explains how we collect, use, store, and protect your information when you use our note-taking application ("the App"). Your privacy is important to us, and we are committed to protecting it.

**Key Principles**:
- **Local-First**: All your notes are stored locally on your device
- **Minimal Data Collection**: We only collect what's necessary for app functionality
- **User Control**: You decide when and how to back up your data
- **Transparency**: This policy clearly explains what we do (and don't do) with your data

By using Zutext, you agree to the terms outlined in this Privacy Policy.

---

## 2. Data We Collect

### 2.1 Data You Provide

**When using the app WITHOUT Google Sign-In**:
- **Note Content**: Notes, titles, tags, folders, and reminders you create
- **App Settings**: Theme preferences, font size, language settings
- **Storage**: ALL this data is stored **locally on your device** in an SQLite database

**When using Google Sign-In (Optional)**:
- **Google Account Information**:
  - Email address
  - Display name
  - Profile photo URL
  - Google OAuth ID
- **Purpose**: Authentication for Google Drive backup feature only

### 2.2 Data Automatically Collected

**Crash and Performance Data** (via Firebase Crashlytics):
- Device model and manufacturer
- Operating system version
- App version
- Crash logs and stack traces
- **NO personally identifiable information** is included in crash reports

**Usage Analytics** (via Firebase Analytics):
- App opens and session duration
- Screen views (which screens you visit)
- Feature usage (e.g., notes created, tags added)
- **NO note content** is ever collected

### 2.3 Data We DO NOT Collect

We **DO NOT** collect, store, or transmit:
- ❌ Your note content to our servers (unless you back up to YOUR Google Drive)
- ❌ Location data
- ❌ Contacts or phone numbers
- ❌ Photos or media (except profile photo from Google)
- ❌ Browsing history
- ❌ Financial information
- ❌ Health data

---

## 3. How We Use Your Data

### 3.1 Note Content (Local Storage)

- **Stored**: Exclusively on your device in an encrypted SQLite database
- **Used for**: Displaying, editing, organizing, and searching your notes
- **Never sent** to any server unless you choose to back up to Google Drive

### 3.2 Google Account Information

- **Used for**: Authentication and authorization for Google Drive backup
- **Stored**: Only your email, name, and OAuth ID in your local database
- **Never shared**: With third parties or used for marketing

### 3.3 Crash and Analytics Data

- **Used for**:
  - Identifying and fixing bugs
  - Improving app performance
  - Understanding feature usage to prioritize improvements
- **Anonymized**: All data is aggregated and anonymized
- **Retention**: Automatically deleted after 60 days (Firebase default)

---

## 4. Data Storage & Security

### 4.1 Local Data Storage

- **Location**: All notes stored in device's local SQLite database
- **Access**: Only you and the app have access
- **Protection**: App requires device unlock (fingerprint, PIN, etc.)

### 4.2 Backup Encryption (AES-256-GCM)

When you choose to back up to Google Drive:
- **Encryption**: All backup files are encrypted using **AES-256-GCM** (military-grade)
- **Encryption Key**: Unique per user, derived from your Google OAuth ID + secret salt
- **Security**: Encrypted file stored in YOUR Google Drive (not our servers)
- **Access**: Only you can decrypt your backups

### 4.3 Data Transmission

- **HTTPS**: All communication with Google services uses HTTPS
- **No Third-Party Servers**: We do not operate any servers for note storage
- **Direct Connection**: Backup connects directly to Google Drive API

## 4.4 Data Deletion Instructions
Since we do not store your data on our own servers, we do not have a "database" from which to delete your information. You have full control over your data:

- **Delete Local Data**: Simply uninstall the app or use the "Clear Data" option in your Android system settings.
- **Delete Backups**: Use the "Delete Backup" feature within the app settings to remove files from your Google Drive.
- **Revoke App Access**: You can revoke the app's access to your Google Account at any time through [Google Account Security Settings](https://myaccount.google.com/permissions).
- **Manual Deletion**: You can manually delete the app's data folder directly from your Google Drive storage.
- **Support**: If you have any questions about managing or deleting your data, please contact the developer at: **<sunjjoo@gmail.com>**.

---

## 5. Third-Party Services

We use the following third-party services:

### 5.1 Firebase (by Google)

**Services Used**:
- **Firebase Crashlytics**: Crash reporting and diagnostics
- **Firebase Analytics**: App usage analytics
- **Firebase Authentication**: Google Sign-In integration

**Data Shared**: Device info, crash logs, anonymized usage data
**Privacy Policy**: <https://firebase.google.com/support/privacy>
**Data Processing**: Governed by Google's privacy policies

### 5.2 Google Drive API

**Purpose**: Optional cloud backup storage
**Data Stored**: Encrypted database backup files in YOUR Google Drive
**Access**: Only you have access to your Drive files
**Privacy Policy**: <https://policies.google.com/privacy>

### 5.3 Google Sign-In

**Purpose**: Authentication for Google Drive backup
**Data Received**: Email, name, profile photo, OAuth ID
**Privacy Policy**: <https://policies.google.com/privacy>

**Important**: We do NOT sell, rent, or share your data with third parties for marketing purposes.

---

## 6. Your Rights

### 6.1 Access Your Data

- **Local Notes**: All your notes are accessible anytime in the app
- **Backup Files**: Accessible in your Google Drive (if you enabled backup)

### 6.2 Edit or Delete Your Data

- **Edit Notes**: Anytime within the app
- **Delete Notes**: Individual notes or entire folders can be deleted
- **Delete Backups**: Delete backup files directly from your Google Drive

### 6.3 Export Your Data

- **Share Notes**: Export individual notes as text
- **Backup File**: Download encrypted .db file from Google Drive
- **Future Feature**: Export to CSV/PDF (planned for v2.0)

### 6.4 Opt-Out of Analytics

- **How**: Go to Settings → Privacy → Disable Analytics (coming soon)
- **Current**: Analytics cannot be disabled in v1.0 (but data is anonymized)

### 6.5 Delete Your Account

- **How**: Uninstall the app and delete backup files from Google Drive
- **Effect**: All local data is permanently deleted upon uninstall
- **No Account**: We don't maintain user accounts, so no server-side deletion needed

---

## 7. Children's Privacy

Zutext is **not intended for children under 13** (or under 16 in the EU). We do not knowingly collect personal information from children. If you believe a child has provided us with personal information, please contact us immediately, and we will delete it.

---

## 8. International Users & GDPR

### 8.1 Data Location

- **Local Storage**: Data stored on your device (wherever you are)
- **Backups**: Stored in Google Drive (Google's servers, varies by region)
- **Firebase**: Data processed by Google (may involve international transfer)

### 8.2 GDPR Rights (EU Users)

Under the General Data Protection Regulation (GDPR), EU users have the following rights:
- ✅ **Right to Access**: Request a copy of your data (use app's export feature)
- ✅ **Right to Rectification**: Correct inaccurate data (edit notes in app)
- ✅ **Right to Erasure**: Delete your data (uninstall app, delete Drive backups)
- ✅ **Right to Data Portability**: Export your data (backup feature)
- ✅ **Right to Object**: Object to analytics (disable in Settings - coming soon)

To exercise these rights, contact us at the email below.

### 8.3 Legal Basis for Processing (GDPR)

- **Local Data**: Legitimate interest (providing app functionality)
- **Google Sign-In**: User consent (you choose to sign in)
- **Firebase Analytics**: Legitimate interest (improving app quality)

---

## 9. Data Retention

| Data Type | Retention Period |
|-----------|------------------|
| Local Notes | Until you delete them or uninstall the app |
| Backup Files | Until you delete them from Google Drive |
| Firebase Crash Logs | 60 days (automatic deletion) |
| Firebase Analytics | 14 months (Google's default) |
| Google Account Info | Until you sign out or uninstall the app |

---

## 10. Changes to This Policy

We may update this Privacy Policy from time to time. When we do:
- **Notification**: We'll update the "Last Updated" date at the top
- **Significant Changes**: We'll notify you via in-app message
- **Your Rights**: Continued use after changes means you accept the updated policy

**Recommendation**: Review this policy periodically to stay informed.

---

## 11. Security Measures

We implement the following security measures:

- **Encryption**: AES-256-GCM for backup files
- **HTTPS**: All network communication encrypted
- **No Central Server**: No single point of failure or data breach risk
- **Minimal Permissions**: App requests only necessary Android/iOS permissions
- **Regular Updates**: Security patches and updates released promptly

**However**: No system is 100% secure. Use device lock (PIN, fingerprint) to protect local data.

---

## 12. Contact Us

If you have questions, concerns, or requests regarding this Privacy Policy or your data:

**Email**: [your-support-email@example.com]
**Response Time**: We aim to respond within 3 business days

**For GDPR Requests**: Use the same email with subject line "GDPR Request"

**For Security Issues**: Use subject line "Security Issue" for priority handling

---

## 13. Acceptance of This Policy

By downloading, installing, or using Zutext, you acknowledge that you have read and understood this Privacy Policy and agree to its terms.

If you do not agree, please do not use the app.

---

**This Privacy Policy is effective as of January 28, 2026.**

---

## Changelog

- **v1.0 (2026-01-28)**: Initial privacy policy for v1.0.0 release

---

**Document Version**: 1.0
**Language**: English
**Korean Version**: Available at [PRIVACY_POLICY_KO.md]

---

*Zutext is developed independently and is not affiliated with or endorsed by Google LLC, Apple Inc., or any third-party services mentioned in this policy.*

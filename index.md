---
layout: default
title: SoundDeck Privacy Policy
description: Privacy policy for the SoundDeck Android app — what data we collect, why, and your GDPR rights.
---

# SoundDeck — Privacy Policy

**Last updated:** 2026-05-29
**Effective for:** SoundDeck Android app, version 0.9.0 and later.

This policy describes what data the SoundDeck mobile companion app collects,
why it collects it, and what your rights are under the EU General Data
Protection Regulation (GDPR).

---

## 1. Who is responsible for your data

The data controller is:

**JFS-Audio**
Justin Schöllmann (sole proprietor)
Ostertorwall 23a
31785 Hameln
Germany
Email: justin@jfs-audio.com

If you have questions about your data, write to that email.

---

## 2. What we collect and why

### 2.1 Account data
When you log in to SoundDeck, we receive and store the following on our
servers (hosted on Render in the EU):

| Field | Why we need it |
|---|---|
| Username | To identify your account and serve your projects |
| Password | To authenticate you when you log in |
| Display name | To show in the app UI |

We issue a session token after login. The token is stored on your device in
the platform keystore (Android Keystore on Android, encrypted at rest).

### 2.2 User content
SoundDeck synchronises audio projects you create on the SoundDeck desktop
app. The mobile app downloads and caches:

- Audio files (WAV) belonging to your projects.
- Project metadata: project names, version names, lyrics, notes.

We do **not** access your microphone, camera, contacts, location, or any
other on-device data. The mobile app does not record or upload anything you
have not explicitly added through the desktop app.

### 2.3 Crash reports
If the app crashes or hits an unexpected error, an automatic crash report is
sent to our self-hosted error tracker (GlitchTip, an open-source
Sentry-compatible service running on app.glitchtip.com). Crash reports
contain:

- Stack trace of the crash.
- App version, OS version, device model.
- A randomly-generated install ID (no link to your username unless the crash
  occurs in code that includes it).

Crash reports do **not** include your password, audio content, lyrics, or
notes.

---

## 3. Legal basis (GDPR Art. 6)

| Purpose | Legal basis |
|---|---|
| Authentication & content sync | Performance of the contract you enter when using the app (Art. 6(1)(b)) |
| Crash reports | Legitimate interest in maintaining a working product (Art. 6(1)(f)) |

---

## 4. How long we keep your data

- **Account + content data**: as long as your account exists. If you ask us
  to delete your account (see Section 6) we erase your username, password,
  display name, and all uploaded audio + project metadata within 30 days.
- **Crash reports**: 90 days, then automatically purged.

---

## 5. Who we share data with

We do not sell your data. We do not use it for advertising. We share it only
with the infrastructure providers required to run the service:

| Provider | Role | Location |
|---|---|---|
| Render (render.com) | Backend hosting | EU (Frankfurt) |
| GlitchTip (app.glitchtip.com) | Crash report storage | EU |

Both providers act as data processors under GDPR Art. 28. We do not transfer
your data outside the EU/EEA.

---

## 6. Your rights

Under GDPR you can ask us to:

- **Access** all data we hold about you (Art. 15).
- **Correct** inaccurate data (Art. 16).
- **Delete** your account and all associated data (Art. 17).
- **Export** your data in a machine-readable form (Art. 20).
- **Object** to processing for legitimate interests (Art. 21).

Send any of these requests to **justin@jfs-audio.com**. We respond within 30
days. You also have the right to lodge a complaint with your local data
protection authority.

---

## 7. Security

- Network traffic between the app and our backend is encrypted with TLS 1.2+.
- The session token is stored in the Android Keystore (hardware-backed where
  available).
- We do not store payment data — the app is free and has no in-app purchases.

---

## 8. Children

SoundDeck is not directed at children under 16. We do not knowingly collect
data from anyone under 16. If you believe a child has created an account,
write to us and we will delete it.

---

## 9. Changes to this policy

If we change this policy in a meaningful way, we will note the new "Last
updated" date and surface the change in the app on next login. Continued use
of the app after a change means you accept the new policy.

---

## 10. Contact

**JFS-Audio**
Justin Schöllmann
Ostertorwall 23a, 31785 Hameln, Germany
Email: justin@jfs-audio.com

For technical questions: justin@jfs-audio.com
For data deletion requests: justin@jfs-audio.com

---
title: Nuntteum Privacy Policy
lang: en
---

[한국어](./)

# Nuntteum Privacy Policy

Effective date: 2026-10-12

Nuntteum ("the app", "we") is an alarm app. Its core features (alarms, missions, planner, voices) work **only on your phone, without our servers**.
We send data to our servers only when you use the features listed below.

## 1. What we process and why

### Stored only on your phone (never sent to us)

| Data | Purpose |
|---|---|
| Alarm settings, affinity and wake-streak records, episodes viewed | Alarms and characters |
| Goals, daily tasks (calendar), notes | Planner |
| Voices you record or import ("my person") | Played by your alarms |
| Motion data for the steps mission (accelerometer) | Checking the mission. Not stored |

### Stored on our servers

| Feature | Data | Kept until |
|---|---|---|
| Account | An anonymous account ID. If you link Google, your Google account email and ID | You delete your account |
| Backup (automatic and manual) | From the list above: alarm settings, progress records and planner content (including notes). **Voice files are not included** | You delete your account (each backup replaces the previous one) |
| Couple mode | The name your partner sees, whether your alarm is ringing, the date and time you finished your mission, nudges, the couple wake streak | You unpair or delete your account |
| Couple morning calls | A voice recording you send to your partner (up to 30 seconds) | It's replaced by a new one, you unpair, or you delete your account |
| Subscription | Google Play purchase token, product, expiry time, status | You delete your account |
| Daily limits | Number of requests per day for personalized lines and character voices, and the date they were counted on | You delete your account |

### Processed by our servers but not stored
- **Personalized lines (Premium, can be turned off in Settings):** the tasks you wrote for your next alarm day, the titles and countdowns of goals with a deadline,
  and your character's affinity stage are sent to an AI model (Google Gemini via OpenRouter) to write the next morning's lines. The lines are saved on your phone; what was sent is not stored on our servers.
- **Character voices:** the day's lines (which may include your task text) are sent to Google Cloud Text-to-Speech to create audio. The audio is saved on your phone; the text is not stored on our servers.
- **Time zone and language:** your phone's time-zone offset and app language are sent with these requests so daily limits reset at your local midnight and lines are written in your language. They are not stored.

### Speech recognition on your phone
- The read-aloud mission uses your phone's speech recognition. **We use on-device recognition when available.** Otherwise your phone's default
  speech recognition service (for example Google) may process it. The app does not store the audio or send it to us.

## 2. Legal bases (EEA/UK users)

| Processing | Legal basis (GDPR Art. 6) |
|---|---|
| Account, backup, couple mode, subscription | Performance of a contract (providing the features you use) |
| Personalized lines, character voices | Consent (you can turn personalized lines off in Settings at any time) |
| Microphone use | Consent (Android permission, can be withdrawn in system settings) |
| Security of the service (e.g. hashed device secrets, daily limits) | Legitimate interests |

## 3. Permissions

| Permission | Purpose | If you deny it |
|---|---|---|
| Notifications, full-screen notifications | Show the alarm screen over the lock screen | The alarm screen may appear late or not at all |
| Exact alarms | Ring at the exact time | The app can't work as an alarm |
| Microphone (optional) | Read-aloud mission, recording voices and morning calls | Only those features are unavailable |
| Battery optimization exception (optional) | Prevent power saving from delaying alarms | Alarms may be late on some phones |

## 4. Service providers and international transfers
We do not sell your data or use it for advertising. These companies process data to run the service:

| Company | What they do |
|---|---|
| Supabase Inc. | Hosting accounts, backups, couple mode and subscription records |
| OpenRouter, Inc. / Google LLC | Writing personalized lines (see section 1) |
| Google LLC | Google sign-in, Google Play billing and subscription checks, Cloud Text-to-Speech |

- Account, backup, couple and subscription records are stored on Supabase servers in **South Korea (Seoul, AWS ap-northeast-2)**.
  For EEA users, this transfer is covered by the European Commission's adequacy decision for the Republic of Korea.
- Personalized lines and character voices are processed on OpenRouter and Google servers in the **United States** and elsewhere, over encrypted connections (HTTPS), and are not stored.
  These transfers rely on the European Commission's Standard Contractual Clauses in our providers' data processing agreements.
- Google sign-in and Google Play billing are handled under Google's policies.

## 5. Retention and deletion
- **Settings > Delete account** immediately deletes everything on our servers (account, backups, couple pairing and morning calls, subscription records).
- Unpairing deletes both partners' couple records and morning-call recordings.
- Data on your phone is deleted when you uninstall the app.
- Deleting your account does not cancel a subscription. Cancel it in Google Play.

## 6. Your rights
You can access, correct, delete, or export your data, object to or restrict processing, and withdraw consent at any time.
In the app you can restore backups, turn off personalized lines, unpair, and delete your account. For anything else, contact us below.
EEA/UK users can also complain to their local data protection authority.

## 7. Children
The app is not directed to children under 13, and we do not knowingly collect personal data from children under 13 (or the higher age required in your country, up to 16 in the EEA).
If you believe a child has given us personal data, contact us and we will delete it.

## 8. Security
- Server connections are encrypted (HTTPS).
- Server data is protected by access rules so only your own account can reach it. Morning-call audio is kept in private storage and downloaded only through short-lived links.
- The device secret used by alarms in couple mode is stored only as a hash, not in plain text.

## 9. Contact
- Controller: Hyun Taek Oh
- Email: mylvoh0714@gmail.com

## 10. Changes
If this policy changes, we will let you know in the app or on this page 7 days before it takes effect.

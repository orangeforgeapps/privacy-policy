# Privacy Policy for Prep4Inburgering
**Last updated: October 26, 2026** (applies from app version 1.10)
**Developer:** OrangeForge  
**Contact:** orangeforge.apps@gmail.com

---

## 1. Introduction

Prep4Inburgering ("the App") is a Dutch language learning app designed to help people prepare for inburgering (civic integration) in the Netherlands.

This app is independently developed by OrangeForge and is not affiliated with the Dutch government or any official inburgering program. For official inburgering information, visit: [www.inburgeren.nl](https://www.inburgeren.nl)

This privacy policy explains how the App handles your information.

---

## 2. Data We Collect

**Prep4Inburgering does not collect personal identifiers such as your name, email, or account information**, and the App does not require an account. Most of your activity stays on your device. The App communicates with servers in the following ways:

- **Learning content sync**: vocabulary, exercises, and grammar content are downloaded from our backend (Supabase) so the App can stay up to date. This is one-way content delivery and does not involve sending your personal data.
- **Learning progress**: which items you've practiced, your streaks, your scores, and your settings are stored locally on your device using Android's SharedPreferences and are not uploaded to our servers. If Android backup is turned on for your Google account, Android may include this data in your device backup so it can be restored on a new phone or after reinstalling. That backup is handled by Google under your Google account settings; we have no access to it.
- **Optional AI feedback (Writing & Speaking)**: if you choose to tap "Get AI feedback" after a writing or speaking exercise, the text you wrote or the transcript of what you said, along with the relevant exercise context, is sent to Anthropic, a third-party AI provider, to generate feedback. This only happens when you actively request it and is never automatic. See Section 5 for details.
- **Anonymous usage statistics (from version 1.10)**: to understand how the App is used and to improve it, the App sends anonymous usage statistics to our backend (Supabase, EU/Frankfurt). You can turn this off at any time in **Settings → Anonymous usage statistics** (see Section 3).

---

## 3. Anonymous Usage Statistics

**What is sent.** When the setting is on, the App sends small records about how the App is used, for example:
- that the App was opened, and how much time was spent in each part of the App per day (for example listening, reading, grammar, exams);
- that an exercise or exam was started or finished, the exercise number, and the score in percent;
- the choices made during the welcome steps (exam level, rough exam timing such as "within a month", optional "how did you find this app" answer, daily goal, reminder on or off);
- whether a daily reminder was shown or opened, and whether a review request was shown;
- counts of technical problems (for example a failed audio download) and of AI feedback requests (count only, not their content);
- general information: app version, app language, selected exam level, and whether your phone has a Dutch text-to-speech voice.

**What is never sent.** Your name, email address, the exact date of your exam, any text you type, your answers to writing or speaking tasks, audio recordings, your location, your contacts, your advertising ID, or your device's hardware identifiers.

**How records are linked.** Records are linked by a random number that the App creates the first time it is opened (an installation ID). This number is not connected to your name, your Google account, or your phone, and we cannot use it to find out who you are.

**Why.** We use these statistics only to improve the App: to see where new users get stuck, which features are used, which exercises are too hard or contain mistakes, and whether technical problems occur. We do not sell this data, share it with third parties for their own purposes, or use it for advertising. Under the EU General Data Protection Regulation, the legal basis is our legitimate interest in improving the App. You can object at any time by turning the setting off.

**How long.** Records are deleted automatically after 13 months.

**Turning it off.** Go to **Settings → Anonymous usage statistics** and switch it off. From that moment, nothing is collected or sent, and any statistics still waiting on your device are deleted. Because the records are not linked to your identity, we generally cannot identify which earlier records came from your installation.

---

## 4. Data We Do NOT Collect

We do not collect:
- Your name, email address, or any personal identifiers
- Location data
- Advertising IDs or hardware device identifiers (the only identifier is the random installation ID described in Section 3)
- The text of your writing answers or speaking transcripts for any purpose other than generating AI feedback you asked for
- Audio recordings (speech is processed on-device for recognition; see Section 5)

We do not use advertising networks, third-party analytics SDKs, crash-reporting SDKs, or social media integrations.

---

## 5. Permissions and Device Features Used

The App uses the following device features:

- **Microphone (Speaking practice)**: used for on-device speech recognition (Android's built-in `SpeechRecognizer`) so you can practice speaking Dutch. Audio is processed by your device's speech recognition service to produce a text transcript; we do not record or store raw audio. If you request AI feedback on a speaking exercise, the resulting **text transcript** (not audio) is sent to our AI feedback service (see Section 6).
- **Text-to-Speech (TTS)**: used to pronounce Dutch vocabulary and listening content aloud, using your device's built-in TTS engine, processed entirely on-device.
- **Notifications**: used to send an optional daily study reminder. You choose whether to turn it on during the welcome steps and can change this later in **Settings → Remind me to practise**. Reminders are scheduled locally on your device. If anonymous usage statistics are on, the App counts whether a reminder was shown or opened (see Section 3).
- **Local Storage**: used to save your learning progress on your device.

No camera, contacts, or location permissions are requested or used.

---

## 6. Third-Party Services

Prep4Inburgering uses the following third-party services:

- **Supabase** (backend hosting, EU/Frankfurt region): delivers learning content (vocabulary, exercises, grammar) to the App, relays optional AI feedback requests, and stores the anonymous usage statistics described in Section 3. Supabase acts as our backend infrastructure provider (data processor).
- **Anthropic** (AI feedback provider): only when you tap "Get AI feedback" on a Writing or Speaking exercise, your submitted text or speech transcript and the relevant exercise prompt are sent to Anthropic's API to generate feedback. This is opt-in per use: nothing is sent unless you tap the button. We do not send your name or any other personal identifier alongside this request. Anthropic's own privacy practices are described at: [https://www.anthropic.com/legal/privacy](https://www.anthropic.com/legal/privacy)
- **Google Play In-App Review**: the App may occasionally ask you to rate it on Google Play (for example after you pass a practice exam). The rating window is shown and handled by Google Play; we do not see whether you rated the App or what you wrote.

---

## 7. Children's Privacy

The App does not knowingly collect personal data from anyone, including children under the age of 13. The App does not require an account or ask for personal identifiers. Users of the optional AI feedback feature should be aware that submitted text/speech is processed by a third-party AI provider as described in Section 6.

---

## 8. Data Security

Your learning progress is stored locally on your device; its security depends on your device's own security settings (screen lock, encryption, etc.). We have no access to your device or your locally stored data.

Content sync, AI feedback requests, and anonymous usage statistics are transmitted over encrypted (HTTPS) connections. Usage statistics are stored in a database that the App can only add records to; they cannot be read back through the App. We do not store your writing or speech submissions on our servers beyond what's needed to process an AI feedback request.

---

## 9. Your Choices

- Turn anonymous usage statistics off or on: **Settings → Anonymous usage statistics**.
- Turn the daily reminder off or on: **Settings → Remind me to practise**, or in your phone's notification settings.
- Use AI feedback only when you want: it is never sent automatically.
- Delete all data stored on your device: uninstall the App or clear its data in your phone's app settings.

---

## 10. Changes to This Policy

If the App is updated with features that change how data is handled, this privacy policy will be updated accordingly. The "Last updated" date at the top of this page will reflect any changes.

---

## 11. Contact

If you have any questions about this privacy policy, please contact us:
**Email:** orangeforge.apps@gmail.com

---

*This privacy policy applies to the Prep4Inburgering Android app published on Google Play.*

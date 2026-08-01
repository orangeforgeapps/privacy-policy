# Privacy Policy for Prep4Inburgering
**Last updated: August 2, 2026**
**Developer:** OrangeForge  
**Contact:** orangeforge.apps@gmail.com

---

## 1. Introduction

Prep4Inburgering ("the App") is a Dutch language learning app designed to help people prepare for inburgering (civic integration) in the Netherlands.

This app is independently developed by OrangeForge and is not affiliated with the Dutch government or any official inburgering program. For official inburgering information, visit: [www.inburgeren.nl](https://www.inburgeren.nl)

This privacy policy explains how the App handles your information.

---

## 2. Data We Collect

**Prep4Inburgering does not collect personal identifiers such as your name, email, or account information**, and most of your activity stays on your device. However, the App does communicate with servers in the following ways:

- **Learning content sync** — vocabulary, exercises, and grammar content are downloaded from our backend (Supabase) so the App can stay up to date. This is one-way content delivery and does not involve sending your personal data.
- **Learning progress** — which items you've practiced, your streaks, and your scores are stored locally on your device using Android's SharedPreferences and are not uploaded to our servers.
- **Optional AI feedback (Writing & Speaking)** — if you choose to tap "Get AI feedback" after a writing or speaking exercise, the text you wrote or the transcript of what you said, along with the relevant exercise context, is sent to Anthropic, a third-party AI provider, to generate feedback. This only happens when you actively request it — it is never automatic. See Section 5 for details.

---

## 3. Data We Do NOT Collect

We do not collect:
- Your name, email address, or any personal identifiers
- Location data
- Device identifiers or advertising IDs
- Usage analytics or crash reports
- Audio recordings (speech is processed on-device for recognition; see Section 4)

---

## 4. Permissions Used

The App uses the following device features:

- **Microphone (Speaking practice)** — used for on-device speech recognition (Android's built-in `SpeechRecognizer`) so you can practice speaking Dutch. Audio is processed by your device's speech recognition service to produce a text transcript; we do not record or store raw audio. If you request AI feedback on a speaking exercise, the resulting **text transcript** (not audio) is sent to our AI feedback service — see Section 5.
- **Text-to-Speech (TTS)** — used to pronounce Dutch vocabulary and listening content aloud, using your device's built-in TTS engine, processed entirely on-device.
- **Notifications** — used to send optional daily study reminders. These are scheduled locally on your device and do not involve any server-side tracking of you individually.
- **Local Storage** — used to save your learning progress on your device.

No camera, contacts, or location permissions are requested or used.

---

## 5. Third-Party Services

Prep4Inburgering uses the following third-party services:

- **Supabase** (backend hosting, EU/Frankfurt region) — delivers learning content (vocabulary, exercises, grammar) to the App and relays optional AI feedback requests. Supabase acts as our backend infrastructure provider.
- **Anthropic** (AI feedback provider) — only when you tap "Get AI feedback" on a Writing or Speaking exercise, your submitted text or speech transcript and the relevant exercise prompt are sent to Anthropic's API to generate feedback. This is opt-in per use — nothing is sent unless you tap the button. We do not send your name or any other personal identifier alongside this request. Anthropic's own privacy practices are described at: [https://www.anthropic.com/legal/privacy](https://www.anthropic.com/legal/privacy)

We do not use advertising networks, analytics SDKs, or social media integrations.

---

## 6. Children's Privacy

The App does not knowingly collect personal data from anyone, including children under the age of 13. The App does not require an account or ask for personal identifiers. Users of the optional AI feedback feature should be aware that submitted text/speech is processed by a third-party AI provider as described in Section 5.

---

## 7. Data Security

Your learning progress is stored locally on your device; its security depends on your device's own security settings (screen lock, encryption, etc.). We have no access to your device or your locally stored data.

Content sync and AI feedback requests are transmitted over encrypted (HTTPS) connections. We do not store your writing or speech submissions on our servers beyond what's needed to process an AI feedback request.

---

## 8. Changes to This Policy

If the App is updated with features that change how data is handled, this privacy policy will be updated accordingly. The "Last updated" date at the top of this page will reflect any changes.

---

## 9. Contact

If you have any questions about this privacy policy, please contact us:
**Email:** orangeforge.apps@gmail.com

---

*This privacy policy applies to the Prep4Inburgering Android app published on Google Play.*

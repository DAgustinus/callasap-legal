# CallASAP — Privacy Policy

**Last updated: 19 July 2026**

CallASAP ("the app", "we", "us") lets you schedule a simulated ("fake") incoming phone call to **your own device**, where an AI plays a caller you describe. This policy explains what data we collect, why, who processes it, and the choices you have.

**Contact:** dapcollections@gmail.com
**Developer:** DAP Collections

---

## 1. The short version

- We do **not** ask for your name, email address, or phone number. There is **no account to create**.
- We do **not** sell your personal information.
- The text you write (who's calling and what the call is about) **is sent to our servers** to generate the call and to run an automated safety check.
- If you pick a real contact, their **photo never leaves your phone**. Their **first name only** is sent, because it is the name the AI caller uses.
- During a *live conversation*, your microphone audio is streamed to the AI in real time so it can reply. It is **not recorded and not stored**.
- The app can only ever ring **your own device**. It cannot place a call to anyone else.

---

## 2. Information we collect

### 2.1 Information you provide
- **Caller name and call description ("your prompt").** The persona and the reason for the call. This is sent to our servers to generate the call script and audio, or to run a live conversation, and to perform an automated safety check.
- **Reports.** If you use "Report this call", we store the reported call and its content for review.

### 2.2 Information created automatically
- **Anonymous user ID.** On first launch we create a random, anonymous Firebase Authentication ID. It is not linked to your name, email, phone number, or Google account. We use it to track your token balance and your call history.
- **Call records.** Times, call type (voice message or live conversation), status (scheduled, completed, missed, declined, cancelled, failed), and the generated script.
- **Token records.** Your balance and a log of token grants and spends.
- **Safety moderation records.** Every automated content-check decision is logged. Where a request is **flagged**, the request text and caller name are retained for review. Where a request is **allowed**, we keep only a short truncated sample (about 60 characters).
- **Diagnostics.** Basic crash and performance data to keep the app stable.

### 2.3 Contacts (optional)
If you choose "Use a real contact":
- The contact's **photo** is copied into the app's private storage on your device so it can appear on the call screen. **The photo is never uploaded to our servers.**
- The contact's **first name only** (for example "Dan" from "Dan James Patrick") is sent to our servers, because it is the name the AI caller uses and it is checked by our safety screening. We do not send the surname, phone number, email address, or any other contact field.
- Using a real contact is entirely optional. The app works fully without contacts access.

### 2.4 Microphone (live conversations only)
For a *live conversation* call, your microphone audio is streamed in real time to the AI service so it can respond to you. **This audio is not recorded, not stored by us, and not used to train models.** The microphone is not used for recorded voice-message calls, and not used at any other time.

### 2.5 Advertising
The app shows optional rewarded video ads through **Google AdMob** (watch an ad to earn tokens). AdMob may collect and process device and advertising identifiers in accordance with Google's policies. We request **non-personalised ads**. When you complete an ad, your anonymous user ID is passed to Google so the reward can be verified and credited to the correct account. **We never share your prompts, your contacts, or your call content with advertisers.**

---

## 3. How we use your information

- To provide the service: generate call scripts and audio, run live conversations, ring your device at the time you chose, and track your token balance and history.
- To keep the service safe: automatically screen requests, act on reports, and prevent abuse and fraud.
- To maintain reliability and fix problems.

We do **not** use your prompts or call content for advertising, and we do **not** sell your personal information.

---

## 4. Who processes your data

We use the following providers purely to operate the app:

| Provider | Purpose |
|---|---|
| Google Firebase (Authentication, Firestore, Cloud Storage, Cloud Functions) | Anonymous identity, token balance, call records, temporary audio storage |
| Google Cloud Run | Relays live conversations between your device and the AI |
| Google Vertex AI (Gemini) | Generates the call script and voice; powers live conversations; performs the automated safety check |
| Google AdMob | Optional rewarded ads and reward verification |

These providers process data on our behalf. We do not sell your data or allow it to be used to build advertising profiles from your call content.

Data is processed on Google Cloud infrastructure, which may involve transfers to and storage in the United States and other countries.

---

## 5. Retention

- **Generated call audio** is stored briefly so it can be delivered to your device, and is deleted from your device once the call ends.
- **Call records and token records** are kept while the app remains installed and associated with your anonymous ID.
- **Safety moderation records and reports** are retained as long as needed for safety, abuse prevention, and legal compliance.
- **Live conversation audio** is never retained.

---

## 6. Your choices and rights

- **Contacts and microphone** are optional and can be refused or revoked at any time in Android Settings. The app continues to work without them.
- **Notifications** can be turned off, though incoming calls will not appear without them.
- **Ads:** you can reset or delete your advertising ID in Android Settings → Privacy → Ads.
- **Deleting your data:** because your account is anonymous and stored only on your device, **uninstalling the app ends your access to it**. To request deletion of the server-side records associated with your anonymous ID, email us at the address above; we will need that ID, which you can find in the app under **Menu → Account**.
- Depending on where you live (for example the EEA, the UK, or California), you may have rights to access, correct, delete, or restrict the processing of your personal information, and to lodge a complaint with your local regulator. Contact us at the address above to exercise these rights.

---

## 7. Children

CallASAP is **not directed to children**. It is intended for users aged 13 and over (16 in some jurisdictions). We do not knowingly collect personal information from children. If you believe a child has provided us with information, please contact us and we will delete it.

---

## 8. Security

Data is transmitted over encrypted connections (HTTPS/WSS) and stored using Google Cloud's security infrastructure. Your token balance and call records can only be written by our servers, not by the app, and you can read only your own records. No system is perfectly secure, but we take reasonable measures to protect your information.

---

## 9. AI-generated content

Call scripts and voices are generated by AI and are clearly labelled as AI-generated within the app during a call. Requests are automatically screened, and we prohibit content that impersonates real businesses or officials, demands money or personal information, simulates genuine emergencies, or targets or harasses a real person.

---

## 10. Changes to this policy

We may update this policy from time to time. The "Last updated" date at the top will change, and material changes will be highlighted in the app or on this page.

---

## 11. Contact

Questions, requests, or complaints: dapcollections@gmail.com

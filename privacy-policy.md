# HALO Privacy Policy

**Last updated: 10 October 2026**

HALO is a health and performance application published by **HelgesenHealth Corp.**
("HALO", "we", "us"). This policy explains what the app collects, where it is
stored, who it is shared with, and what control you have over it.

HALO handles sensitive health information — blood test results, sleep, body
composition, medications and supplements. We have tried to describe this
plainly rather than generically, including the places where your data leaves
our systems.

**Contact:** mjhelgesen10@gmail.com

---

## 1. Information we collect

### Account
- Email address and authentication credentials, used to create and secure your account.

### Profile and health background
- Date of birth, biological sex, ethnicity, height, weight, body-fat percentage, goal weight
- Chronic conditions, family medical history
- Current medications, supplements and peptides, including doses
- Hormone therapy status (TRT/HRT) and dosing, where you provide it

Ethnicity is collected because several clinical reference ranges are stratified
by it. It is used for that purpose only.

### Blood work
- Lab panels: biomarker names, values, units, reference ranges, flags, lab source and draw date
- **PDF lab reports you upload**
- Blood-draw appointments you record

### Nutrition
- Meals and foods logged, including portions, macronutrients and micronutrients
- Meal preferences, meal timing, dietary restrictions and allergies
- Foods scanned by barcode
- Free-text descriptions of meals you type

### Training
- Workout sessions, exercises, sets, weights, repetitions and reps-in-reserve
- Routines and custom exercises you create
- Perceived session difficulty and related subjective ratings
- Cardio sessions, heart-rate zones and estimated maximum heart rate

### Sleep and recovery
- Sleep sessions: duration, stages, efficiency
- Heart-rate variability, resting heart rate, skin temperature
- Daily vitals, including blood pressure if you choose to track it

### Connected devices
If you connect a wearable, we receive the data that device exposes:
- **Oura** — sleep, readiness, activity summaries
- **WHOOP** — strain, recovery, sleep
- **Apple Health** — heart rate, HRV, activity, workouts, sleep

Connecting a device is optional. HALO works without one.

### Subscription and technical data
- Subscription and purchase status, handled by RevenueCat
- Device push-notification tokens, used for reminders you enable
- Basic diagnostic information such as error logs

---

## 2. How your information is used

- To calculate your nutrition targets, training plan, sleep guidance and supplement recommendations
- To interpret blood work against clinical and optimal reference ranges
- To adapt those plans over time as your logged data changes
- To send reminders and notifications you have enabled
- To operate, secure, support and improve the service

We do **not** sell your personal information. We do **not** use your health data
for advertising.

---

## 3. Where your data is stored

Your data is stored in a **Supabase** (PostgreSQL) database hosted on Amazon Web
Services in the **US-West-2 (Oregon)** region, in the United States.

Access is restricted by row-level security policies so that your records are
readable and writable only by your authenticated account.

Authentication tokens for connected wearables are stored **on your device** in
the operating system's secure keychain, not on our servers.

If you are located outside the United States, your information will be
transferred to and processed in the United States.

---

## 4. Third parties who process your data

### Anthropic (Claude API) — important

HALO uses Anthropic's Claude API for several features. In the course of those
features, the following is transmitted to Anthropic:

- **The PDF lab reports you upload.** When you add blood work, the document is
  sent to Anthropic's API so the biomarker values can be extracted
  automatically. The report's contents — including your name and any other
  personal details printed on it — are included in that transmission.
- **Blood-work analysis context**, when interpretation is generated.
- **Free-text meal descriptions** you type, so they can be parsed into foods and
  portions.
- **Meal composition data**, when a meal is checked for coherence.

Anthropic processes this data as a service provider in order to return a result
to the app. Their handling is governed by Anthropic's own privacy policy and
commercial terms.

If you prefer not to have lab reports processed this way, do not upload PDF lab
reports; biomarker values can be entered manually instead.

### Other processors

| Provider | Purpose | What they receive |
|---|---|---|
| **Supabase** | Database and authentication | All account and health data described above |
| **RevenueCat** | Subscription management | Purchase and subscription status, device identifiers |
| **Expo / EAS** | App delivery and push notifications | Device push tokens, crash and build diagnostics |
| **USDA FoodData Central** | Nutrition reference data | Food search terms only |
| **Open Food Facts** | Barcode lookups | Scanned barcode numbers only |
| **Oura, WHOOP** | Wearable data, if connected | Authorization requests; we read data from them |
| **Apple HealthKit** | Wearable data, if permitted | Processed on your device under Apple's permissions |

### Links to other services

HALO contains links to outside services — food-delivery apps, supplement
retailers, laboratory providers and research databases. Following a link takes
you to that company's own site, governed by their privacy policy. We do not
transmit your health data to them.

---

## 5. Your choices and rights

- **Access and export.** You may request a copy of your data.
- **Correction.** Profile, logs and blood work can be edited in the app.
- **Deletion.** You may delete your account, which removes your personal data from our systems. Request this in the app or by email.
- **Disconnect a device.** Wearable connections can be revoked at any time in the app; revoking deletes the stored tokens from your device.
- **Notifications.** Reminders can be disabled in the app or in your device settings.
- **Health permissions.** Apple Health access can be withdrawn in iOS Settings → Privacy & Security → Health.

Depending on where you live, you may have additional rights — including rights
under the EU/UK GDPR or the California Consumer Privacy Act — such as the right
to object to processing, to request portability, or to lodge a complaint with a
supervisory authority. Contact us at the address above to exercise them.

---

## 6. Data retention

We retain your data while your account is active. When you delete your account,
your personal data is deleted from our production database. Backups are purged
on their normal rotation schedule.

---

## 7. Security

- All data is transmitted over encrypted connections (TLS).
- Database access is restricted per user by row-level security.
- Wearable tokens are held in the device secure keychain.

No system is perfectly secure, and we cannot guarantee absolute security.

---

## 8. Children

HALO is not intended for anyone under 18, and we do not knowingly collect
information from children. If you believe a child has provided us data, contact
us and we will delete it.

---

## 9. Medical disclaimer

HALO is not a medical device and does not provide medical advice, diagnosis or
treatment. Its outputs — including blood-work interpretation, supplement
suggestions and training or nutrition plans — are informational. Always consult
a qualified clinician before acting on them, particularly regarding
medications, supplements or any diagnosed condition.

---

## 10. Changes to this policy

We may update this policy. Material changes will be announced in the app or by
email, and the "Last updated" date above will change.

---

## 11. Contact

**HelgesenHealth Corp.**
mjhelgesen10@gmail.com

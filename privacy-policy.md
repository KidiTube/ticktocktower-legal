# Privacy Policy — TickTockTower

**Effective Date:** March 22, 2026
**Last Updated:** March 22, 2026

TickTockTower Games ("we", "our", or "us") operates the TickTockTower mobile application (the "App"). This Privacy Policy explains what information we collect, how we use it, and your rights regarding that information.

By downloading or using the App, you agree to the practices described in this policy.

---

## 1. Information We Collect

### 1.1 Account Information
When you create an account using Apple Sign-In, we receive:
- Your Apple-assigned user identifier (a unique, stable ID)
- Your name (only on first sign-in, if you choose to share it)
- Your email address (only if you choose to share it with us via Apple's private relay or directly)

When you use email/password registration, we collect:
- Email address
- Display name (chosen by you, max 15 characters)

We do **not** collect passwords — these are managed securely by Firebase Authentication.

### 1.2 Gameplay Data
We collect data about your in-game activity to power the App's features:
- Player display name and profile settings
- Game scores, high scores, and total points
- Coins and gems (virtual currency balances and history)
- Player rank and competitive tier (Bronze, Silver, Gold, Master, Grandmaster)
- Tower floor progression (current and maximum floor reached)
- Skill stats (Focus, Memory, Logic, Speed — each scored 0–100)
- Individual game-type levels and performance history
- Achievement progress and unlocked achievements
- Win/loss streaks, combo counts, and prestige level
- Daily challenge completion records
- Last login date and login streak

### 1.3 Friend Data
If you use the Friends feature:
- Your 6-character friend code (auto-generated)
- Friend connections (by user ID)
- Friends' publicly visible profile info: display name, high score, rank, win rate

### 1.4 Game Session History
Each completed game session generates a record containing:
- Game type played
- Score achieved
- Whether the session was successful
- Timestamp

### 1.5 Device and Technical Information
We and our third-party partners (see Section 4) may automatically collect:
- Device type, model, and operating system version
- App version
- IP address (used by Firebase infrastructure, not stored by us directly)
- **Advertising Identifier (IDFA)** — only on iOS, and only if you grant permission via the App Tracking Transparency (ATT) prompt

---

## 2. How We Use Your Information

We use the information collected to:

- **Provide the App's features** — game saves, cloud sync, leaderboards, achievements, Tower progression, and the Friends system
- **Personalise your experience** — display your rank, skills, and progress
- **Enable competitive features** — global and friends leaderboards, ranked mode
- **Deliver advertising** — display ads via Google AdMob (see Section 4)
- **Improve the App** — via aggregated, anonymised analytics (only with your ATT consent on iOS)
- **Fulfil account deletion requests** — permanently erase all your data when requested
- **Security and fraud prevention** — detect and prevent abuse or cheating

---

## 3. App Tracking Transparency (iOS)

On iOS 14 and later, we display Apple's **App Tracking Transparency (ATT)** prompt before enabling any personalised advertising or cross-app tracking.

- **If you allow tracking:** Personalised ads are enabled and Firebase Analytics is turned on. Your IDFA may be shared with Google AdMob and Google Analytics for ad personalisation and performance measurement.
- **If you decline tracking:** You will still see ads, but they will not be personalised. Firebase Analytics remains disabled. We request non-personalised ads only (`requestNonPersonalizedAdsOnly: true`).

You can change your choice at any time:
**iPhone Settings → Privacy & Security → Tracking → TickTockTower**

---

## 4. Third-Party Services

We share data with the following third parties, each governed by their own privacy policies:

### Google Firebase
- **Firebase Authentication** — manages your login credentials securely
- **Cloud Firestore** — stores your game data and profile in Google's cloud
- **Firebase Analytics** — collects aggregated usage data (only with ATT consent)
- Privacy policy: https://firebase.google.com/support/privacy

### Google AdMob
- Serves banner, interstitial, and rewarded video ads within the App
- May collect your Advertising Identifier (IDFA) for ad targeting (only with ATT consent)
- Opt out of personalised ads: https://www.google.com/settings/ads
- Privacy policy: https://policies.google.com/privacy

### Apple
- Handles **Sign in with Apple** authentication
- Apple does not share your Apple ID password or private information with us
- Privacy policy: https://www.apple.com/legal/privacy

We do **not** sell your personal data to any third party.

---

## 5. Virtual Currency and In-App Purchases

TickTockTower uses two virtual currencies:
- **Coins** — earned by playing games and completing daily goals
- **Gems** — earned through achievements, Tower milestones, and prestige rewards

**Important:** Neither Coins nor Gems can be purchased with real money. The App contains **no real-money in-app purchases**. Virtual currency has no monetary value and cannot be exchanged for real currency.

---

## 6. Children's Privacy

TickTockTower is not directed at children under the age of **13** (or under 16 in the European Union / EEA). We do not knowingly collect personal information from children under 13.

If you are a parent or guardian and believe your child has provided us with personal information, please contact us at **barsbuildme@gmail.com** and we will delete the information promptly.

---

## 7. Data Retention

- **Account data** is retained for as long as your account is active.
- **Game session history** is retained indefinitely for leaderboard and achievement purposes.
- **Local device data** is stored in your device's local storage (AsyncStorage) and is cleared if you uninstall the App.
- When you **delete your account** (Settings → Delete Account & Data), all of the following is permanently and irreversibly deleted within **30 days**:
  - Your Firebase Authentication account
  - Your Firestore profile (`/users/{uid}`)
  - Your player stats document (`/players/{uid}`)
  - All game history (`/players/{uid}/games`)
  - All friend connections (`/players/{uid}/friends`)
  - All daily challenge records (`/players/{uid}/dailyChallenges`)

---

## 8. Your Rights

Depending on your location, you may have the right to:

- **Access** the personal data we hold about you
- **Correct** inaccurate data (update your display name in-app)
- **Delete** your data (via in-app account deletion or by contacting us)
- **Object** to or **restrict** processing of your data
- **Withdraw consent** for tracking at any time via iOS ATT settings
- **Data portability** — request a copy of your data by contacting us

To exercise any of these rights, use the in-app **Delete Account** feature or email us at **barsbuildme@gmail.com**.

---

## 9. Data Security

We implement the following measures to protect your data:

- All data is transmitted over **HTTPS/TLS encryption**
- Firebase Authentication uses industry-standard credential hashing
- Firestore Security Rules enforce that only you can read or write your own data
- We do not store passwords — authentication is handled by Firebase and Apple

However, no system is completely secure. We cannot guarantee the absolute security of your information.

---

## 10. International Data Transfers

Your data is stored in Google Cloud infrastructure, which may be located outside your country of residence. By using the App, you consent to the transfer of your data to these servers. Google Cloud and Firebase comply with applicable data protection regulations including GDPR and CCPA.

---

## 11. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. We will notify you of significant changes by updating the "Last Updated" date at the top of this policy. Continued use of the App after changes constitutes acceptance of the revised policy.

---

## 12. Contact Us

If you have any questions, concerns, or requests regarding this Privacy Policy or your personal data, please contact us:

**Email:** barsbuildme@gmail.com
**App:** TickTockTower — Daily Focus Challenge
**Developer:** TickTockTower Games

---

*© 2026 TickTockTower Games. All rights reserved.*

---

*Developed by [BarsBuild.me](https://barsbuildme.com)*

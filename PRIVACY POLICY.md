# ROBLOX RADAR – PRIVACY POLICY  
_Last updated: **May 27 2025**_

Roblox Radar (“we,” “our,” or “extension”) is a browser add-on created by Benjamin Asmark (SpecT1e).  
**We do not transmit, sell, or store any of your personal data on our servers.**  
This document explains what data the extension touches, why, where it lives, and what rights you have.

---

## 1. Data We Handle

| Category | What it is | Where it is stored | Why we need it |
|----------|------------|--------------------|----------------|
| **User settings** | Theme, last-active tab, notification preferences | Locally in your browser via `chrome.storage.local` / `browser.storage.local` | To remember your preferences |
| **Tracked players** | Roblox **UserIDs and/or Usernames** you manually add | Locally in your browser | To let Player Tracker notify you |
| **Ephemeral Roblox API data** | Server lists, player status, game info pulled from `*.roblox.com` | Nowhere (held in RAM, shown, then discarded) | To power Server Finder / Player Finder / Player Tracker |
| **Clipboard content** | Server ID you choose to copy | Your OS clipboard (until you overwrite it) | Convenience |

No analytics, no ads, no third-party SDKs.

---

## 2. How Data Flows

* All network calls go **directly from your browser to Roblox’s official APIs** over HTTPS.  
* We are **not** a man-in-the-middle and never see your Roblox credentials; your browser sends the normal Roblox cookies only to `roblox.com`.  
* Everything we write stays in your local profile. **Clear storage or uninstall to delete it.**

---

## 3. Children’s Privacy (COPPA)

Roblox is popular with kids under 13. Roblox Radar is a **general-audience** tool but may be used by children.

* We **do not knowingly collect** children’s personal information on our servers—nothing leaves the device.  
* **Parents:** If your child added player IDs locally and you wish to remove them, open the extension → Settings → “Clear tracked players,” or uninstall the add-on.  
* If you believe we inadvertently received child data, email **benjamin.asmark@gmail.com** and we will delete it.

Because processing never leaves the child’s own device, COPPA’s server-side consent and deletion rules are not triggered, yet we still encourage parental supervision.

---

## 4. Your Rights

| Jurisdiction | Your rights | How to exercise |
|--------------|-------------|-----------------|
| **EU / EEA (GDPR)** | Access, rectification, erasure, restriction, portability, objection | Manage data in-extension or clear browser storage; email us if you need help |
| **California (CCPA/CPRA)** | Know, delete, correct, opt-out of sale/share | We **do not sell or share** data. Delete it locally at any time. |
| **Everyone** | Withdraw consent | Stop using the feature or uninstall |

Because data never leaves your machine, you hold the keys.

---

## 5. Security

We follow secure-coding practice; the source is public on GitHub (<https://github.com/TheBengine/Roblox-Radar>) for audit.  
Local data security depends on **your OS account, browser profile, and physical device security**. Keep them safe.

---

## 6. Chrome Web Store “Limited Use” Statement

Our use and transfer of information received from the Chrome Storage API **fully complies with the Chrome Web Store User Data Policy, including its “Limited Use” requirements.**

---

## 7. Data Retention

Local data persists until **you** delete it via the extension UI, browser settings, or by uninstalling Roblox Radar. We retain **zero** server-side copies.

---

## 8. Policy Changes

If we ever introduce cloud features or analytics, we will:

1. update this Policy and bump the “Last updated” date;  
2. show a prominent in-extension notice;  
3. require new affirmative consent **before** collecting anything.

Staying silent means no data collection.

---

## 9. Contact

Privacy questions or complaints?  
Email **benjamin.asmark@gmail.com** or open an issue at  
<https://github.com/TheBengine/Roblox-Radar>.

---

_By installing or using Roblox Radar you acknowledge this Privacy Policy._

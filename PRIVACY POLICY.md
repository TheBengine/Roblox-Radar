[PRIVACY POLICY.md](https://github.com/user-attachments/files/28961026/PRIVACY.POLICY.md)
# ROBLOX RADAR – PRIVACY POLICY  
_Last updated: **June 12 2026**_

Roblox Radar (“we,” “our,” or “extension”) is a browser add-on created by Benjamin Asmark (SpecT1e).  
**We do not transmit, sell, or store any of your personal data on our servers.**  
This document explains what data the extension touches, why, where it lives, and what rights you have.

---

## 1. Data We Handle

| Category | What it is | Where it is stored | Why we need it |
|----------|------------|--------------------|----------------|
| **User settings** | Theme, last-active tab, form values, notification preferences | Locally in your browser via `chrome.storage.local` / `browser.storage.local` | To remember your preferences |
| **Tracked players** | Roblox **UserIDs and/or Usernames** you manually add | Locally in your browser | To let Player Tracker notify you |
| **Search history** | Recent Place IDs and usernames you searched for | Locally in your browser (max 20 each) | To offer autocomplete suggestions |
| **Backup copy (automatic)** | A small mirror of your tracked players and search history | Your browser’s **extension sync storage** (`storage.sync`) — see Section 2 | So your player list survives if local browser data is wiped |
| **Backup file (manual)** | A JSON file you create with the “Backup” button | Wherever **you** save it on your device | So you can restore or move your list yourself |
| **Ephemeral Roblox API data** | Server lists, player status, game info pulled from `*.roblox.com` | Nowhere (held in RAM, shown, then discarded) | To power Server Finder / Player Finder / Player Tracker |
| **Clipboard content** | Server ID you choose to copy | Your OS clipboard (until you overwrite it) | Convenience |

No analytics, no ads, no third-party SDKs.

---

## 2. How Data Flows

* All network calls go **directly from your browser to Roblox’s official APIs** over HTTPS.  
* We are **not** a man-in-the-middle and never see your Roblox credentials; your browser sends the normal Roblox cookies only to `roblox.com`.  
* The automatic backup uses your browser’s built-in **extension sync storage**. If you have browser sync turned on (e.g., a Google or Firefox account), your browser vendor stores and syncs that small backup under **your own account**, governed by the vendor’s privacy policy — **we never receive or can access it.** If sync is off, the backup simply stays on your device.  
* Manual backup files are created locally and saved where you choose. **They never leave your device unless you move them.**  
* Everything we write stays in your local profile or your own browser account. **Clear your tracked players in-extension (which also clears the sync mirror), clear storage, or uninstall to delete it.**

---

## 3. Children’s Privacy (COPPA)

Roblox is popular with kids under 13. Roblox Radar is a **general-audience** tool but may be used by children.

* We **do not knowingly collect** children’s personal information on our servers—nothing reaches us.  
* **Parents:** If your child added player IDs and you wish to remove them, open the extension → **Player Tracker** tab → press the red **trash-can (Clear All)** button. This also clears the automatic sync backup. Delete any manual backup files your child saved, then uninstall the add-on if desired.  
* If you believe we inadvertently received child data, email **benjamin.asmark@gmail.com** and we will delete it.

Because processing never leaves the child’s own device or browser account, COPPA’s server-side consent and deletion rules are not triggered, yet we still encourage parental supervision.

---

## 4. Your Rights

| Jurisdiction | Your rights | How to exercise |
|--------------|-------------|-----------------|
| **EU / EEA (GDPR)** | Access, rectification, erasure, restriction, portability, objection | Manage or export data in-extension (the “Backup” button is your portability right in action) or clear browser storage; email us if you need help |
| **California (CCPA/CPRA)** | Know, delete, correct, opt-out of sale/share | We **do not sell or share** data. Delete it locally at any time. |
| **Everyone** | Withdraw consent | Stop using the feature or uninstall |

Because data never leaves your machine or your own browser account, you hold the keys.

---

## 5. Security

We follow secure-coding practice; the source is public on GitHub (<https://github.com/TheBengine/Roblox-Radar>) for audit.  
Local data security depends on **your OS account, browser profile, and physical device security**. Treat manual backup files like any personal file. Keep them safe.

---

## 6. Chrome Web Store “Limited Use” Statement

Our use and transfer of information received from the Chrome Storage API **fully complies with the Chrome Web Store User Data Policy, including its “Limited Use” requirements.**

---

## 7. Data Retention

Local data persists until **you** delete it via the extension UI, browser settings, or by uninstalling Roblox Radar.  
The automatic sync backup is overwritten whenever your list changes and is emptied when you press **Clear All**; if browser sync is enabled, it may persist in your browser account after uninstalling (and will restore your list if you reinstall) — clear the list before uninstalling to remove it everywhere.  
Manual backup files are ordinary files under your control; delete them whenever you like. We retain **zero** server-side copies.

---

## 8. Policy Changes

If we ever introduce cloud features of our own or analytics, we will:

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

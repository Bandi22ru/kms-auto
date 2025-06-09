# 🔐 KMSAuto++ Portable

> Lightweight activator for Windows & Office VL editions.  
> No installation required. No .NET needed.

Created by **Ratiborus** (MSFree Inc.)

---

## 💻 Supported Systems

**Windows:**
- XP, Vista, 7, 8, 8.1, 10  
- Server 2008 / 2008 R2 / 2012 / 2012 R2 / 2016 / 2019

**Office (Volume Editions Only):**
- 2010, 2013, 2016, 2019  
> 📝 *Yes, Office 2010 VL works even on Windows XP*

---

## ⚙️ Features

- One-click activation for supported Windows & Office VL editions
- Built-in GVLK key installer
- Optional KMS-Service installation
- Custom KMS server support
- Silent command-line mode for automation
- Task scheduler setup for auto-reactivation
- Offline compatible — no internet required

No setup. No .NET. Just run and go.

---

## 🚀 Command-Line Options

Run KMSAuto++ with these switches for silent operations:

| Switch         | Action                                              |
|----------------|-----------------------------------------------------|
| `/win=act`     | Activate Windows and close                          |
| `/ofs=act`     | Activate Office and close                           |
| `/wingvlk=inst`| Install GVLK key for Windows                        |
| `/ofsgvlk=inst`| Install GVLK key(s) for Office                      |
| `/sched=win`   | Schedule reactivation for Windows (every 25 days)  |
| `/sched=ofs`   | Schedule reactivation for Office (every 25 days)   |

> ✅ Switches can be combined.  
> ⚠️ Office Retail → VL conversion only works if it's not already activated.

---

## 🛠 Built-in KMS Server

You can optionally install a local KMS server from the **Settings** tab.  
Great for activating other machines in your network:

- Default IP: `127.0.0.2:<port>`
- Compatible with Windows 7–8 and Office VL
- Doesn’t conflict with other activation methods
- For Windows 8.1, a temporary driver is used and auto-removed

You can also set an external KMS address without changing system settings — they’ll revert after activation.

---

## 🧱 Troubleshooting

- **Windows 7 Ultimate** and other non-VL editions are **not supported**
- Antivirus may block activation — exclude these folders:
  - `C:\Windows\KMSAutoS`
  - `KMSAuto_Files`
- Error `0xC004F074`? Check your firewall — it may block KMS connections

---

## 📝 Changelog Highlights

- **v1.5.4** — SYSTEM-level tasks with WinDivert/Hook
- **v1.5.1** — Office uninstaller added
- **v1.4.5** — KMS38 activation support
- **v1.4.0** — Added Windows 10 Digital License method
- **v1.3.7** — Full code rewrite
- **v1.1.7** — Activation backup/restore added
- **v1.0.8** — English UI added

> See full version history in `CHANGELOG.md`

---

## 📎 Legal Disclaimer

KMSAuto++ is a research and educational tool.  
Using it may violate Microsoft’s license terms depending on your country and use case.  
You're responsible for how you use this software.

---

## 💡 Tip

Once the scheduler is set, you can safely delete the app. Activation will continue on autopilot.

---

© Ratiborus / MSFree Inc.  

Download KMSauto: https://weblifeplus.ru/windows-kms/

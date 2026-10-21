# Orbit - Releases

Download hub for **Orbit**, the Chrome extension by Barbas Digital that adds a side panel with tools for Elementor: Figma to Elementor, a shared block library, icons, animations and more.

> This repository only distributes builds. There is no source code here.

## Editions

| Edition | For whom | File |
|---------|----------|------|
| **Barbas** | The Barbas Digital team. Connects to the company project; nothing to configure. | `orbit-extension-vX.Y.Z.zip` |
| **Open** | Anyone. On first run you enter your own Supabase project URL and public (anon) key. | `orbit-extension-open-vX.Y.Z.zip` |

Grab the zip from the [latest release](../../releases/latest).

## Install

1. Download the zip for your edition and extract it to a folder you will keep (do not delete it afterwards).
2. Open `chrome://extensions` and turn on **Developer mode**.
3. Click **Load unpacked** and pick the extracted folder.
4. Pin the Orbit icon and open the side panel.

## Update

Orbit checks this repository (at most every 6 hours) and shows **"New version available"** at the top of the panel.

1. Download the new zip from the link in the notice.
2. Extract it **over the same folder**.
3. In `chrome://extensions`, click the reload icon on the Orbit card.

## Verify a download (optional)

Each release lists the SHA-256 of its zips, also available in `latest.json`.

```powershell
Get-FileHash .\orbit-extension-vX.Y.Z.zip -Algorithm SHA256
```

## Files in this repository

| File | Purpose |
|------|---------|
| `latest.json` | Current version of the Barbas edition (read by the extension). |
| `latest-open.json` | Current version of the Open edition. |

## Support

Questions or problems: guilherme@barbas.digital

---

Made by [Barbas Digital](https://barbas.digital).

# PMI Card Editor v1 — Installation, Usage & Uninstallation Guide

---

## WHAT IS INCLUDED IN THE ZIP

```
pmi-card-editor-v1/
├── pmi-card-editor.html                  ← The application (open this file)
├── PMI-Card-Editor_Install-and-Uninstall.md   ← This guide
└── PMI-Card-Editor_How-To-Use.md         ← Detailed how-to-use guide
```

---

## SYSTEM REQUIREMENTS

| Requirement | Details |
|---|---|
| **Operating System** | Windows 10/11, macOS, Linux, ChromeOS — any OS with a modern browser |
| **Browser** | Chrome 90+, Edge 90+, Firefox 88+, Safari 15+ (Chrome or Edge recommended) |
| **Internet Connection** | Required on first open to load fonts and libraries. After first load, the card editor itself works offline. AI features require internet at all times. |
| **Disk Space** | ~2 MB for the HTML file |
| **Software to Install** | None — no installation required |

---

## INSTALLATION — ZERO INSTALL REQUIRED

This is a **self-contained single HTML file**. There is nothing to install.

### How to open the app

**Option A — Double-click (easiest):**
1. Locate `pmi-card-editor.html` on your computer
2. Double-click it
3. It opens in your default web browser automatically
4. The app is ready to use

**Option B — Drag into browser:**
1. Open Chrome, Edge, or Firefox
2. Drag and drop `pmi-card-editor.html` into the browser window
3. The app loads immediately

**Option C — Right-click "Open with":**
1. Right-click `pmi-card-editor.html`
2. Select **Open with** → Choose your browser (Chrome, Edge, etc.)

### Recommended: Pin to taskbar or desktop for quick access

1. Open the file in Chrome or Edge
2. In the browser address bar, you'll see a local file path like `file:///C:/Users/YourName/.../pmi-card-editor.html`
3. To create a desktop shortcut: right-click the browser taskbar icon → Pin, or create a shortcut to the file itself

---

## SHARING THE APP

### Sharing via email or file transfer

1. Zip the entire `pmi-card-editor-v1/` folder
2. Email the zip file or share via any file transfer method (USB, OneDrive, Google Drive, etc.)
3. Recipient unzips the folder and double-clicks `pmi-card-editor.html`

**Important note about saved data:** Each user's saved designs, templates, and contacts are stored locally in their own browser's storage on their own computer. Saved data does NOT travel with the HTML file when you share it. Each recipient starts fresh with no saved data.

### If the file won't open after emailing

Some email clients and antivirus software may flag or block `.html` files. If this happens:
- ZIP the file before emailing (most email clients allow zipped attachments)
- Or share via a file link (OneDrive, Google Drive, Dropbox)

---

## DATA STORAGE — WHERE YOUR WORK IS SAVED

The app saves data to your **browser's local storage** (a built-in, private, per-browser database). This means:

- Your saved designs, contacts, and custom templates are stored in your browser, not in the HTML file
- Data persists across sessions — close and reopen the file and your saves are still there
- Data is tied to the specific browser and computer you used
- Clearing your browser's history/storage will delete saved data
- If you open the file in a different browser, you will not see saves from the other browser

### Storage keys used (for IT reference)

The app stores data under the following localStorage keys:
- `pmi_card_card_configs` — saved card design configurations
- `pmi_card_card_people` — saved contact/person profiles
- `pmi_card_card_custom_templates` — saved custom template categories

---

## IMPORTANT NOTES BEFORE USING

### Internet connection on first launch
On first open, the browser loads:
- Google Fonts (Montserrat family)
- React framework libraries from CDN (cdnjs.cloudflare.com)
- Babel transpiler from CDN

After the first successful load, the scripts are cached by your browser. Subsequent opens in the same browser typically work offline (unless the cache is cleared).

### AI Features require internet
The AI Studio (Step 5) always requires an active internet connection to communicate with:
- Anthropic API (Claude)
- OpenAI API (ChatGPT / DALL-E)
- xAI API (Grok)

AI features also require API keys from those providers (see How-To-Use guide for details).

### Browser security warnings
Some browsers may show a warning when opening local HTML files. This is normal. The app does not contact any server except the CDN for libraries and the AI APIs (only when you actively use the AI features). It is safe to proceed.

---

## UNINSTALLATION — COMPLETE REMOVAL

Since nothing was installed on your system, "uninstallation" simply means removing the file and optionally clearing browser storage.

### Step 1 — Delete the HTML file (and folder)

1. Locate the `pmi-card-editor-v1/` folder (or wherever you saved the file)
2. Delete it — move to Recycle Bin, then empty it
3. The application is removed

### Step 2 — Clear saved app data from your browser (optional)

If you want to completely erase all saved designs, contacts, and custom templates:

#### Chrome / Edge:
1. Press `F12` to open Developer Tools
2. Click the **Application** tab
3. In the left panel, expand **Storage** → click **Local Storage**
4. Find the entry for the file path (e.g., `file://...pmi-card-editor.html`)
5. Delete all keys that start with `pmi_card_`
6. Or to clear everything, right-click the entry and select **Clear**

#### Firefox:
1. Press `F12` → click **Storage** tab
2. Expand **Local Storage** in the left panel
3. Find and delete the `pmi_card_*` keys

#### Alternative — Clear all browser storage for local files:
- In Chrome: Settings → Privacy and security → Clear browsing data → Check "Cookies and other site data" → Clear data
- Note: This clears ALL local file storage for ALL local HTML apps, not just this one

### Step 3 — Remove any shortcuts (if created)

Delete any desktop shortcuts or taskbar pins you created pointing to the file.

---

## TROUBLESHOOTING

| Problem | Solution |
|---|---|
| App is blank / shows white screen | Ensure internet connection is active on first load; try refreshing (F5) |
| Fonts look wrong / plain | Internet connection required for Google Fonts on first load |
| "Export PDF" button doesn't work | Check internet connection (jsPDF loads from CDN); try refreshing |
| Saved data disappeared | Browser storage may have been cleared; data is browser-specific |
| AI features not responding | Check your API key and internet connection |
| File won't open on double-click | Right-click → Open with → Choose Chrome or Edge manually |
| Security warning in browser | Click "Allow" or proceed — the file is safe |

---

*PMI Card Editor v1 — Self-Contained Portable Application*

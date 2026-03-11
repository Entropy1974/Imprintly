# PMI Card Editor v1 — How to Use Guide

---

## OVERVIEW & PROCESS FLOW

The PMI Card Editor creates professional double-sided business cards. The workflow is organized into **6 steps** navigated via tabs in the left panel. The right side shows a live preview of your card updating in real time.

```
STEP 1: START       → Choose template or import background
    ↓
STEP 2: DESIGN      → Set colors, typography, ribbon/swoosh styles
    ↓
STEP 3: ELEMENTS    → Add logo, choose layout, fine-tune positions
    ↓
STEP 4: CONTENT     → Enter person details, company, taglines
    ↓
STEP 5: AI STUDIO   → Get AI design advice, logo concepts, template search
    ↓
STEP 6: SAVE        → Save contacts & designs, export PDF/PNG/JPG/SVG
```

You can also jump between steps in any order using the tab bar at the top of the left panel.

**Navigation tip:** The **← Prev** and **Next →** buttons at the bottom of the left panel step you through the workflow in order.

---

## SCREEN LAYOUT

```
┌─────────────────────────────────────────────────────────┐
│  PMI Card Editor v1                              [?] Help│
├──────────────────────┬──────────────────────────────────┤
│  STEP TABS (top)     │                                  │
│  [1][2][3][4][5][6]  │     LIVE CARD PREVIEW            │
│                      │                                  │
│  LEFT PANEL          │     [Front card shown here]      │
│  (controls for       │                                  │
│   current step)      │     [Back card shown here]       │
│                      │     (with QR code)               │
│                      │                                  │
├──────────────────────│                                  │
│  [← Prev] [Next →]   │  Zoom: [slider] [Fit] [Full]     │
├──────────────────────┴──────────────────────────────────┤
│  EXPORT BAR (bottom-left): PDF | PNG | JPG | SVG        │
└─────────────────────────────────────────────────────────┘
```

---

## STEP 1 — START (Templates & Background)

This is where you choose the starting visual style for your card.

### Layout Toggle

At the top of the templates panel, two buttons let you choose your card layout **before** picking a template:

- **◧ Classic Split** — A diagonal two-panel split is always visible. Best for cards that emphasize the left-panel logo area alongside a right-panel contact section.
- **▨ Modern Split** — A wider dark right panel with a pronounced diagonal split. Best for bold, high-contrast designs.

All template thumbnails **instantly update** to show how each design looks in your chosen layout. When you click a template, both the template style *and* the selected layout are applied together in one click — no extra step needed.

> **Tip:** You can always fine-tune the split position, angle, and layout type later in Step 3 → Layout tab.

### Built-in Templates

The template library is organized into categories:
- **PMI Signature** — PMI-branded cards (white/dark with pink arc)
- **Modern Split** — Contemporary diagonal two-panel layouts
- **Minimal & Clean** — Simple, understated designs
- **Executive** — Navy, gold, and dark premium styles
- **Bold & Creative** — High-contrast vibrant designs
- **Gradient** — Cards with gradient accent ribbons
- **Dark & Moody** — All-dark cards with glow accents

**How to use:** Select your preferred layout (Classic or Modern Split), click a category tab, then click any template thumbnail. The card preview instantly updates. A gold banner at the bottom of the screen confirms the change was applied and gives you a **Revert** option if you want to go back.

### Custom Templates (Added section)

At the bottom of the templates panel, "Custom Added" shows your personally saved designs. First create a category (e.g., "Client A", "Dark Versions"), then save your current design into it. These persist in your browser between sessions.

- **+ New Category** — Creates a named group for your custom saves
- **+ Save Current Design** — Saves the current card state as a named custom template in a category you choose
- Click any saved template to apply it; use the ✕ button to delete

### Import Background / Template

Click this button to jump directly to the Background upload section (Step 3, Background tab). You can upload a PNG, JPG, or SVG image to use as your card background. After uploading, sliders let you control brightness, contrast, saturation, and opacity of the background image.

The app can also use **AI to analyze an uploaded card image** and recreate its layout as an editable template. This requires a Claude or OpenAI API key.

### Search Templates with AI

This button switches to the AI Studio in Template Search mode. Ask the AI to suggest templates, colors, or design styles. It provides links to Dribbble, Behance, Canva, and other resources. Works with Claude Free (no API key required).

---

## STEP 2 — DESIGN (Colors & Typography)

### Colors tab

Controls the visual palette of the card:

| Field | What it controls |
|---|---|
| **Light Panel** | Background color of the left/light side of the card |
| **Dark Panel** | Background color of the right/dark side |
| **Accent Color** | Primary accent — drives the ribbon/swoosh, icons, divider lines |
| **Accent Color End** | Second color for gradient accents (ribbon end color) |
| **Icon Color** | Color of the phone/email/website icons on the front |
| **Divider Color** | Color of the horizontal rule lines between sections |
| **Back Card: Background** | The back side uses its own background (defaults to dark panel color) |
| **Back Card: QR Color** | Color of the QR code on the back |
| **Back Card: Tagline Colors** | Bold/Light tagline colors on the back |

Click any color swatch to open a color picker, or type a hex value directly.

### Typography tab

Every text element on the card has its own typography settings:

- **Person Name** — Large name text (front)
- **Title / Position** — Job title line (front)
- **Phone / Email / Website** — Contact info lines (front)
- **Tagline Bold** — First tagline line
- **Tagline Light** — Second tagline line
- **Company Name** — Large company name (back)
- **Company Subtitle** — Smaller subtitle below company name (back)

For each element you can set:
- Font size (px)
- Bold / Italic / Underline toggles
- Text color
- Font family (10 options: Montserrat, Arial, Georgia, Verdana, and more)
- Letter spacing

**Reset Typography** button at the top resets all typography to the active template defaults.

### Modern Split tab (also under Design)

Controls the diagonal split and ribbon/swoosh decoration:

| Setting | Description |
|---|---|
| **Split Position** | How far across the card the split line falls (0–100%). 100 = no split (full single color). |
| **Split Angle** | Angle of the split diagonal (60–120°). 90° = straight vertical. Lower = leans left-top. |
| **Ribbon Visible** | Toggle the decorative ribbon/swoosh on/off |
| **Ribbon Style** | Shape of the ribbon: Arc, Arc Fade, PMI Ribbon, Arc Low, Arc Top, Double, Diagonal, Wave, Corner, Slash, Filled Arc |
| **Ribbon Thickness** | Stroke width of the ribbon |
| **Ribbon Opacity** | Transparency of the ribbon (0–100%) |
| **Ribbon Fade** | If on, the ribbon fades from solid to transparent across the card |

---

## STEP 3 — ELEMENTS (Logo, Layout, Position)

### Logo tab

Manage what appears in the left panel of the card:

**Logo Mode:**
- **PMI Logo** — Use the bundled PMI logo (default, pre-loaded)
- **Upload Logo** — Upload your own PNG or SVG
- **Draw Logo** — Use a simple canvas tool to sketch a logo
- **Company Text** — Display company name/subtitle as large text instead of a graphic logo

**Logo Upload:** Click "Upload Logo" or drag a file. PNG and SVG work best. Transparent backgrounds are supported.

**Logo Color Swap (uploaded logos only):**
Click the color picker icon to open the Logo Color Editor. Hover over the logo preview to see pixel colors. Click a color in the logo to sample it as a "swap from" color, then set a "swap to" color. This lets you recolor specific parts of your logo to match the card's color scheme. Front and back logo colors are set independently.

**Logo Size & Position:** Handled in the Position tab (see below).

### Layout tab

Choose the overall card layout:

- **Classic** — Standard business card layout: logo on the left, contact info stacked on the right
- **Modern Split** — Two-panel design: large company elements top-left, name and contacts spread across two quadrants

### Position tab

Fine-tune X/Y coordinates and sizes for every element:

- **Logo X / Logo Y** — Position of the logo
- **Logo Width** — Size of the logo
- **Name X / Name Y** — Position of the person's name
- **Title X / Title Y** — Position of the title line
- **Phone / Email / Website X / Y** — Individual contact item positions
- **Tagline positions** — Fine-tune where taglines appear
- **QR X / QR Y / QR Size** — Size and position of the QR code on the back

Each control has a **reset** button (↺) to return to the template default for that element.

### Background tab

Upload a background image for the front or back of the card:

1. Click "Upload Front Background" or "Upload Back Background"
2. Choose a PNG, JPG, or SVG file
3. Use sliders to adjust:
   - **Opacity** — How transparent the background image is
   - **Brightness** — Lighten or darken
   - **Contrast** — Increase or reduce contrast
   - **Saturation** — Color intensity

The background image layer is below the card elements and above the color panels.

---

## STEP 4 — CONTENT (Text & People)

### Person Details

Fill in the cardholder's information:

| Field | Front card location | Back card |
|---|---|---|
| **Name** | Large name text, right panel | — |
| **Title** | Below name | — |
| **Phone** | Contact row with ☎ icon | Used in QR vCard |
| **Email** | Contact row with ✉ icon | Used in QR vCard |
| **Website** | Contact row with ⊕ icon | Used in QR vCard |
| **Address** | Optional contact row with 📍 icon | — |

### Company Details

| Field | Where it appears |
|---|---|
| **Company Name** | Large text, back of card (also optionally front left) |
| **Company Subtitle** | Below company name (e.g., "CONSULTING LLC") |

### Taglines

Two tagline lines appear on the **back** of the card, below the QR code area:

- **Bold Tagline** — Primary tagline (appears with emphasized styling)
- **Light Tagline** — Secondary tagline or descriptor (lighter styling)

Both taglines support **inline rich text**: select text and use the Bold / Italic / Color buttons in the tagline editor to style individual words.

### Divider Lines

Toggle the thin horizontal rule lines on the front card:
- **Divider Line 1** — Between title and contact info
- **Divider Line 2** — Below contact info, above taglines

### People Manager (also in Step 6)

Save named contact profiles to quickly switch between different cardholders without changing the design:

1. Fill in content fields for a person
2. Type a name in the "Profile Name" field
3. Click **Save Person Profile**
4. The profile appears in the list below

To load a profile: click **Load** next to any saved profile. The content fields update while the design (colors, layout, logo) stays the same.

Profiles can be edited in-place or deleted.

---

## STEP 5 — AI STUDIO

The AI Studio connects to AI services to help you improve and explore your design.

### Choosing an AI Provider

| Provider | Free Tier | API Key Required | Notes |
|---|---|---|---|
| **Claude (Anthropic)** | Yes (Haiku) | Optional | Best for design review. Key unlocks Claude Sonnet. |
| **ChatGPT (OpenAI)** | No | Always required | Key required; unlocks GPT-4o and DALL-E image gen |
| **Grok (xAI)** | No | Always required | Get key from console.x.ai |

**How to get a Claude API key (free tier available):**
1. Go to console.anthropic.com
2. Sign up for a free account
3. Navigate to API Keys and create a new key
4. Paste it in the "API Key" field in AI Studio

**How to get an OpenAI key:**
1. Go to platform.openai.com
2. Create an account and add billing
3. Go to API Keys and create a new key

### AI Modes

**🎨 Design Review**
The AI analyzes your current card and gives structured feedback on:
- Color harmony
- Typography choices
- Visual hierarchy and balance
- Whitespace and layout

When the AI suggests specific changes (colors, ribbon styles), a **Suggestion Panel** appears below the response showing a before/after comparison. Click **Apply** to try the change. Click **Save as New Template** to save both versions.

**⚡ Impact Score**
Rates your card design across 5 dimensions (each 0–10):
- Visual Impact
- Professionalism
- Memorability
- Color Harmony
- Typography

Displayed as a progress bar. Includes an overall score and specific improvement tips.

**🔍 Template Search**
Describe what you're looking for (e.g., "dark luxury tech company card") and the AI suggests matching templates with links to Dribbble, Behance, Canva, Moo, and similar sites.

**🎯 Logo Concept**
Describes logo design ideas based on your company name and industry. With a paid OpenAI API key, this mode generates actual logo images using DALL-E 3. Generated images have a **"Use as Card Logo"** button to apply them directly.

### Design Suggestions

When AI responses include specific recommendations (embedded in the response as structured data), a **Design Suggestions** panel appears:

- Each suggestion shows **Current vs. Suggested** as a side-by-side mini card preview
- Click **Apply…** to apply a single suggestion
- Click **Apply All** to apply all suggestions at once
- After applying, a **Revert** banner appears at the bottom of the screen with an undo option
- Click **Save as New Template** to save the applied version as a custom template

### Quick Prompts

When the conversation is empty, Quick Prompt buttons appear. Click any to send a pre-written question tailored to your current design state.

---

## STEP 6 — SAVE & EXPORT

### Saved Configurations

Save complete design snapshots (colors, layout, typography, ribbon settings, logo position — everything):

1. Type a configuration name in the "Config Name" field
2. Optionally enter a company/group name to organize by
3. Click **Save Configuration**

To restore a saved config: expand the company group, click **Load** next to any config name.

### People / Contacts

Same as the People Manager in Step 4. Accessible here for convenience at the end of the workflow.

### Custom Templates

Same as in Step 1. Accessible here if you want to save your current design as a template after finishing.

---

## EXPORT OPTIONS

Located at the bottom of the left panel (visible from all steps):

### PDF Export (recommended for printing)
**⬇ Export PDF — Both Sides (Print-Ready)**

Generates a professional print-ready PDF:
- Both card sides on one page
- 3.5" × 2" standard business card size
- 300 DPI (1050 × 600 px per card side)
- Suitable for home printing or professional print shops

### PNG Export
- **PNG Front** — Front card only
- **PNG Back** — Back card only
- **PNG Both** — Both sides as a single combined image

High resolution at 1050 × 600 px (3.5" × 2" at 300 dpi).

### JPG Export
- **JPG Front / JPG Back** — JPEG format, slightly smaller file size than PNG

### SVG Export
- **SVG Front / SVG Back / SVG Both** — Vector format (scalable to any size, no quality loss)
- SVG is ideal for professional print shops or further editing in vector applications like Adobe Illustrator or Inkscape

### Copy Config
Copies the current card configuration as JSON text to the clipboard. Advanced use: allows pasting into another app session to reproduce a design exactly.

### Reset All
Resets every setting to factory defaults. **This cannot be undone** unless you have a saved configuration.

---

## THE CARD BACK — QR CODE

The back of the card always shows:
- Company name (large) and subtitle
- Taglines
- A **QR code** that encodes a vCard (virtual contact card)

**What the QR code contains:**
When someone scans it with a phone, it offers to save the cardholder as a contact in their phone's address book. The QR code automatically includes:
- Full name
- Job title
- Phone number
- Email address
- Website URL
- Company name

This updates automatically as you type in the Content fields.

---

## REVERT / UNDO

Whenever a template, AI suggestion, or saved configuration is applied, a **Revert Banner** slides up from the bottom of the screen:
- **Revert → Discard Change** — Undoes the applied change and restores the previous state
- **Save Current First, Then Revert** — Saves the newly applied state as a custom template (so you don't lose it), then reverts to the previous state
- Click **✕** to dismiss the banner and keep the change

The revert is only available until the banner is dismissed or until another change is applied.

---

## TIPS & BEST PRACTICES

1. **Start with a template** — Applying a template first saves time. You can always override individual colors or typography afterward.

2. **Content first vs. design first** — For most users: fill in content (Step 4) first so the card looks realistic as you design. For template exploration, just browse with placeholder text.

3. **Save frequently** — Use "Save Configuration" (Step 6) to save named snapshots before making major changes. This gives you a reliable undo history.

4. **AI Review before export** — Run an Impact Score (Step 5) before exporting to catch common design issues.

5. **Export as PDF for printing** — The PDF export is pre-configured for professional printing at correct dimensions and resolution.

6. **For multiple people, same design** — Save the design as a Configuration, then use the People Manager to load each person's details and export separately.

---

*PMI Card Editor v1 — Professional Business Card Design Tool*

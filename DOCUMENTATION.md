# Imprintly — Complete User Guide

> **Version:** 1.1 | **Last Updated:** 2026-03-11
> This document is the canonical reference for all Imprintly features.
> Update this file whenever features are added or changed.

---

## TABLE OF CONTENTS

1. [Overview & Process Flow](#overview)
2. [Screen Layout](#layout)
3. [Getting Started — Your First Card in 5 Minutes](#quickstart)
4. [Tab 1: Style](#style)
5. [Tab 2: Media](#media)
6. [Tab 3: Text](#text)
7. [Tab 4: Tools](#tools)
8. [Tab 5: Save & Export](#export)
9. [Tab 6: AI Studio](#ai)
10. [Keyboard Shortcuts](#shortcuts)
11. [Export & Print Guide](#printing)
12. [Troubleshooting & FAQ](#faq)

---

## 1. Overview & Process Flow {#overview}

Imprintly creates professional double-sided business cards with a guided 6-step workflow. Each step is a tab in the sidebar — work through them in order, or jump to any tab at any time.

```
STEP 1: STYLE    → Choose template, set colors, typography, layout
    ↓
STEP 2: MEDIA    → Upload logo, import background images
    ↓
STEP 3: TEXT     → Enter contact details, company info, taglines
    ↓
STEP 4: TOOLS    → Fine-tune positions, cover/erase, color swap, QR config
    ↓
STEP 5: SAVE & EXPORT   → Save configurations, batch export, card back variants
    ↓
STEP 6: AI       → AI design review, impact scoring, template search
```

**Key concepts:**
- All changes preview **live** on the card to the right
- **Undo/Redo** with Ctrl+Z / Ctrl+Y (10-level history)
- Your work **auto-saves** to browser storage — return anytime to continue
- On desktop, the Export bar is always visible at the bottom of the sidebar regardless of which tab you're on. On mobile, Export controls appear when you tap the Export icon in the bottom navigation bar

---

## 2. Screen Layout {#layout}

### Desktop (1024px+)
```
┌──────────────────────────────────────────────────────────┐
│  Imprintly                          [📖 Guide] [? Help]  │
├──────────────────────┬───────────────────────────────────┤
│  TAB BAR             │                                   │
│  Style Media Text    │     FRONT CARD PREVIEW            │
│  Tools Export AI     │     (live updating)               │
│                      │                                   │
│  SUB-TABS            │                                   │
│  (per-tab options)   │                                   │
│                      │     BACK CARD PREVIEW             │
│  CONTROLS            │     (with QR code)                │
│  (current tab)       │                                   │
│                      │     Zoom: [slider] [Fit] [Full]   │
├──────────────────────┤                                   │
│  [← Prev] [Next →]  │                                   │
├──────────────────────┴───────────────────────────────────┤
│  EXPORT BAR: □ Crop marks  □ CMYK | PDF PNG JPG SVG     │
└──────────────────────────────────────────────────────────┘
```

### Mobile / Tablet (≤1024px)
```
┌──────────────────────────┐
│                          │
│    FRONT CARD PREVIEW    │
│    (full-width, ~40vh)   │
│                          │
│    BACK CARD PREVIEW     │
│                          │
├──────────────────────────┤ ← slide-up panel (60vh)
│  [Sub-tab pills]         │
│  CONTROLS (current tab)  │
│  (scrollable)        [×] │
│                          │
├──────────────────────────┤
│ Style Media Text Tools   │ ← fixed bottom nav (60px)
│  Export  AI              │
└──────────────────────────┘
```

- **Fixed bottom navigation bar** with 6 SVG icon buttons (Style, Media, Text, Tools, Export, AI)
- Tap an icon to open that tab's controls in a **slide-up panel** (60vh height, animates from bottom)
- Tap the same icon again or tap × to close the panel
- Card preview remains visible above the panel (~40vh)
- Semi-transparent overlay behind panel — tap to dismiss
- Touch targets sized at 38px minimum for compact but accessible controls
- Template grid uses 2-column layout on phones, auto-fill on tablets

---

## 3. Getting Started — Your First Card in 5 Minutes {#quickstart}

1. **Pick a template** — Tab 1 (Style) > Templates shows 92 designs across 10 categories in a browsable grid. Click one to apply instantly.
2. **Add your logo** — Tab 2 (Media) > Upload a PNG/SVG logo. Choose "Upload Logo" mode and pick your file.
3. **Enter your details** — Tab 3 (Text) > Fill in your name, title, phone, email, and website.
4. **Export** — Scroll to the bottom export bar and click "Export PDF — Both Sides" for a print-ready file.

That's it! The remaining tabs let you fine-tune colors, positions, and advanced features.

---

## 4. Tab 1: Style {#style}

### Templates
Browse **92 template variations** across 10 categories in a responsive grid. Use the category filter pills (All, Modern, Minimal, Executive, etc.) to narrow your selection:
- **Modern** — Diagonal two-panel designs
- **Minimal** — Simple, elegant layouts
- **Executive** — Professional, corporate styles
- **Bold** — Eye-catching, colorful designs
- **Gradient** — Smooth color transitions
- **Dark** — Deep, dramatic backgrounds
- **Elegant** — Refined, sophisticated styles
- **Creative** — Artistic, unique layouts
- **Tech** — Technology-themed designs
- **Ribbon** — Featuring decorative ribbon/swoosh elements

Each template is built from one of 26 base designs with color and font variations. Thumbnails update live to show your current background image and cover rectangles.

**Custom Templates:** Save your current design to a named category with "+ Save Current Design". Custom templates appear alongside built-ins for one-click reuse.

**Layout Toggle:** Switch between **Classic Split** and **Modern Split** layout modes. This affects all templates.

### Colors
Individual color pickers for every card element:
- **Front Card:** Light Panel, Dark Panel, Accent Color, Accent End (for gradients), Icon Color, Divider Color
- **Back Card:** Background, QR Color, Tagline Bold Color, Tagline Light Color

Click any color swatch to open the picker. Type hex values directly for precise control. "Reset All Colors" restores template defaults.

### Typography
Per-field controls for **9 text elements**: Person Name, Title, Phone, Email, Website, Tagline Bold, Tagline Light, Company Name, Company Subtitle.

Each field offers:
- **Font family** dropdown
- **Font size** slider
- **Bold / Italic / Underline** toggles
- **Text alignment** — Left, Center, Right (L/C/R buttons)
- **Color** picker
- **Letter spacing** control
- **Reset** per field or all at once

### Layout
Toggle between two card structures:
- **Classic Split** — Traditional business card with separate left/right panels
- **Modern Split** — Diagonal or curved split with watermark overlay

### Modern Split (advanced)
Only visible when Modern Split layout is selected:
- **Watermark:** Color, opacity, and size controls
- **Logo & Name Sizes:** Adjust logo scale and name font size
- **Color Tokens:** Fine-tune subtle text, contact text, accent bullets, panel backgrounds, divider
- **Quick Themes:** 6 one-click color presets (Violet, Emerald, Coral, Navy, Rose, Slate)

---

## 5. Tab 2: Media {#media}

### Logo
Four logo modes:
1. **PMI Logo** — Built-in bundled logo
2. **Upload Logo** — Upload your own PNG/SVG/JPG. Separate front/back color tinting available.
3. **Draw Logo** — Simple canvas drawing tool for quick logo sketches
4. **Company Text** — Uses your company name as a text-based logo

**Logo Library:** Upload multiple logos, name them, and switch between them. Logos persist in browser storage.

### Background Import
Upload a background image (PNG, JPG, SVG) for the front or back card:
- **Opacity** slider (0-100%)
- **Brightness** slider
- **Contrast** slider
- **Saturation** slider

The image becomes the card's background layer behind all other elements.

**AI Template Analysis:** With an API key configured, the AI can analyze an uploaded background and suggest complementary colors and typography.

---

## 6. Tab 3: Text {#text}

### Person Details
- **Full Name** — As it appears on the card front
- **Title / Role** — Job title or position
- **Reset Person** button clears all person fields

### Contact Information
- **Phone** — Format as you want it printed (e.g., 405-795-0571)
- **Email** — Full email address
- **Website** — URL (http/https prefix auto-stripped for display)
- **Address** — Optional street address (toggle to show/hide)

### Company Details
- **Company Name** — Main company/brand name in the header area
- **Company Subtitle** — Secondary line (e.g., "CONSULTING LLC")

### Taglines
Two tagline lines on the back card:
- **Bold Tagline** — Prominent, accent-colored text
- **Sub Line** — Secondary descriptor, lighter weight

Both support rich text editing with bold/italic formatting.

### Divider Lines
Toggle visibility of the two horizontal divider lines on the card front.

### People Manager
Save multiple contact profiles by name. Each profile stores only the content fields (name, title, phone, email, website) — not the design. Load a profile to instantly populate all content fields while keeping your current design intact. Great for creating cards for multiple team members.

---

## 7. Tab 4: Tools {#tools}

### Position (sub-tab)
Fine-tune the X/Y position and size of every element:
- **Logo:** X position, Y position, Width/Scale
- **Text elements:** Name, Title, Phone, Email, Website, Tagline positions (X and Y)
- **QR Code:** X position, Y position, Size
- **Bleed safe zone** toggle — shows/hides dashed red guide overlay on the card

Reset individual elements or all positions at once.

### Cover / Erase (sub-tab)
Draw rectangles over the card to cover template-baked content you want to hide:
- **Draw mode:** Click and drag to create a rectangle
- **Auto-fill:** Rectangles automatically fill with the card's panel color
- **Manual color:** Override with any color via picker
- **Gradient modes:**
  - **G2** — 2-point linear gradient
  - **G4** — 4-point gradient (custom at each corner)
  - **IMG** — Image-based gradient from the background
- **Feathered edges** — Soft edge blending for seamless coverage
- **Front/Back toggle** — Work on either card side
- **Eyedropper** — 120px magnifier with 8x zoom, crosshair, and hex readout for picking colors

### Color Swap (sub-tab)
Intelligently recolor areas of the card:
- **Magic Wand mode** — Click a color region to select it for replacement
- **Rectangle mode** — Draw a rectangle to define the recolor area
- **Hue Shift** slider (0-360°) — Rotate the hue of selected colors
- **Flat Replace** toggle — Replace with a single solid color instead of shifting
- **Tolerance** slider — Control how similar colors must be to be included
- **Front/Back toggle** — Work on either card side

### QR Code Configuration
Located within the Position sub-tab, the QR section controls the back card's QR code:

**QR Label Text** — Customize the text below the QR code (default: "SCAN TO ADD CONTACT")

**QR Data Mode** — Three modes:
1. **vCard** (default) — QR encodes a full vCard contact file. When scanned, the phone prompts to save the contact.
2. **URL** — QR encodes any custom URL you enter. When scanned, it opens that link.
3. **Digital Card** — Generate a standalone HTML landing page:
   - Choose **Dark or Light theme** for the page
   - Toggle **company logo inclusion**
   - **Preview** the digital card right in the sidebar
   - **Download** the HTML file to host anywhere
   - Enter the **hosted URL** — the QR code links to this page
   - The landing page includes contact info, clickable links (phone, email, website), and a "Save to Contacts" button

**QR Dot Style** — Choose the shape of QR code dots:
- ■ Square (default), ▢ Rounded, ● Circle, ◆ Diamond

**QR Corner Style** — Choose finder pattern style:
- Sharp (default), Rounded

**QR Gradient Fill** — Optional gradient coloring across QR dots with customizable start/end colors

**QR Center Logo** — Upload a small logo to display in the center of the QR code (25% exclusion zone maintains scannability)

---

## 8. Tab 5: Save & Export {#export}

### Save (sub-tab)
**People / Contacts** — Save and load contact profiles (see Text > People Manager above).

**Batch Export All People** — Generate a single multi-page PDF containing cards for every saved person. Each person gets a front and back page using the current design. Great for printing an entire team's cards at once.

**Saved Design Configurations** — Save complete design snapshots (colors, typography, layout, logos, everything). Organize by company name and config name. Load any saved configuration to restore the full design state.

**Backup & Restore** — Export all configurations as a JSON backup file, or import a backup to restore.

### Card Backs (sub-tab)
**Card Back Variants** (Printfinity-style) — Create multiple unique back card designs:
- The **Default Back** always uses your current design
- Click **"+ Add Back Variant"** to create additional back designs
- Each variant can have its own background, colors, taglines, and QR styling
- When exporting PDF, all variants are included as additional back pages
- Perfect for creating variety packs or A/B testing designs

---

## 9. Tab 6: AI Studio {#ai}

### Provider Selection
Choose your AI provider:
- **Claude (Anthropic)** — Free tier available (Haiku model, no API key needed)
- **ChatGPT (OpenAI)** — Requires API key
- **Grok (xAI)** — Requires API key

### AI Modes

**Review** — The AI analyzes your current card and provides structured feedback on:
- Color harmony and contrast
- Typography choices and readability
- Whitespace and breathing room
- Visual hierarchy
- Overall professionalism

**Impact Score** — Rates your card across 5 dimensions (each scored 0-10):
- Visual Impact, Professionalism, Memorability, Color Harmony, Typography
- Includes specific improvement recommendations

**Template Search** — Describes your design style and suggests external resources from Dribbble, Behance, Canva, and more with direct links.

**Logo Concept** — Describes logo design ideas based on your company. With a paid OpenAI key, generates actual logo images via DALL-E 3 that can be applied directly.

### Design Suggestions
When the AI recommends specific changes (colors, layouts, etc.), a **Suggestion Panel** appears with before/after card previews. Options:
- **Apply** — Try one suggestion
- **Apply All** — Apply all recommendations
- **Save as Template** — Keep both your original and the AI's version

### Quick Prompts
Pre-written questions appear when the conversation is empty — click one to start an AI interaction without typing.

---

## 10. Keyboard Shortcuts {#shortcuts}

| Shortcut | Action |
|----------|--------|
| **Ctrl+Z** | Undo (10 levels) |
| **Ctrl+Y** or **Ctrl+Shift+Z** | Redo |

Undo/redo tracks all design changes: color picks, position moves, text edits, template switches, and more.

---

## 11. Export & Print Guide {#printing}

### Export Formats
| Format | Use Case |
|--------|----------|
| **PDF** | Print-ready, both sides, 3.5" × 2" at 300 DPI |
| **PNG** | High-res raster images (1050 × 600 px) — front, back, or both |
| **JPG** | Compressed raster — front or back |
| **SVG** | Vector format for professional editing in Illustrator/Inkscape |

### Print Preparation Options
- **☐ Crop marks & bleed area** — Adds 3.175mm bleed and L-shaped crop marks at corners for professional print shops
- **☐ CMYK color preview** — Shows approximate CMYK values on color pickers with out-of-gamut warnings (note: true CMYK conversion requires ICC profiles — this is an approximation)

### Print Tips
1. For professional printing, use **PDF export with crop marks enabled**
2. Standard business card size is **3.5" × 2"** (88.9 × 50.8 mm)
3. Keep important content **away from edges** — use the bleed guide to check safe zones
4. Verify colors match expectations — screen colors may differ from print
5. If your print shop requires specific formats, use SVG export for maximum flexibility

### Batch Printing
Use **Export All People as PDF** (Export > Save tab) to generate a single file with all saved contacts on the same design. Each person gets 2 pages (front + back).

---

## 12. Troubleshooting & FAQ {#faq}

### Common Issues

**Q: My design disappeared when I reopened the app.**
A: Imprintly auto-saves to browser localStorage. If you cleared browser data, the save is lost. Use Export > Save > Backup & Restore to create external backups.

**Q: The card preview looks blank or broken.**
A: Try refreshing the page (F5). If using a very large background image, the browser may need a moment to render.

**Q: Colors look different when printed.**
A: Screen (RGB) and print (CMYK) color spaces differ. Enable the CMYK preview checkbox in the Export bar to see approximate print values. For critical color matching, request a proof from your print shop.

**Q: The QR code won't scan.**
A: Ensure sufficient contrast between QR dots and background. Avoid very small QR sizes. If using a center logo, keep it under 25% of the QR area (the app handles this automatically). Test with multiple QR reader apps.

**Q: Can I use this on mobile/tablet?**
A: Yes! The app is fully responsive with touch support. On mobile, controls appear in a bottom sheet — swipe up to expand. Pinch-to-zoom works on the card preview. All touch targets are 44px minimum.

**Q: How do I share my Digital Card?**
A: In Tools > QR > Digital Card mode: download the HTML file, upload it to any web host (GitHub Pages, Netlify, your website), then paste the URL into the "Hosted URL" field. The QR code will link to your hosted page.

**Q: The Babel deoptimization warning appears in the console.**
A: This is normal and expected. The app uses in-browser Babel transpilation for the large script. It doesn't affect functionality.

### Browser Support
- Chrome 90+ (recommended)
- Firefox 88+
- Safari 14+
- Edge 90+

### Data Storage
All data is stored in browser **localStorage** with the `imprintly_` prefix. No data is sent to any server (unless you use the AI features, which send design state to the selected AI provider's API).

---

## Maintainer Notes

### Updating This Documentation
When adding new features:
1. Add the feature to the relevant tab section above
2. Update the in-app `HELP_DOCS` object (line ~6201 in index.html)
3. Update the in-app `GUIDE_SECTIONS` object (search `GUIDE_SECTIONS` in index.html)
4. Add a screenshot if the feature has significant UI
5. Update the feature count in MEMORY.md

### Key Code Locations for Documentation
- `HELP_DOCS` — Contextual help content (search `var HELP_DOCS`)
- `GUIDE_SECTIONS` — Full user guide content (search `var GUIDE_SECTIONS`)
- `HelpDrawer` — Help panel component (search `function HelpDrawer`)
- `UserGuide` — Full guide overlay component (search `function UserGuide`)
- `STAGES` — Tab structure definition (search `const STAGES`)
- `DEFAULT_STATE` — All state fields (search `var DEFAULT_STATE`)

# Imprintly — Complete User Guide

> **Version:** 2.0 | **Last Updated:** 2026-03-15
> This document is the canonical reference for all Imprintly features.
> Update this file whenever features are added or changed.

---

## TABLE OF CONTENTS

1. [Overview & Process Flow](#overview)
2. [Screen Layout](#layout)
3. [Getting Started — Your First Card in 5 Minutes](#quickstart)
4. [Step 1: Templates](#templates)
5. [Step 2: Content](#content)
6. [Step 3: Media](#media)
7. [Step 4: Design](#design)
8. [Step 5: QR Code](#qrcode)
9. [Step 6: Bulk](#bulk)
10. [Step 7: Export](#export)
11. [AI Studio](#ai)
12. [Theme Toggle](#theme)
13. [Keyboard Shortcuts](#shortcuts)
14. [Export & Print Guide](#printing)
15. [Troubleshooting & FAQ](#faq)

---

## 1. Overview & Process Flow {#overview}

Imprintly creates professional double-sided business cards with a guided 7-step workflow. Each step is a section in the sidebar — work through them in order, or jump to any section at any time.

```
STEP 1: TEMPLATES  -> Choose a template, browse categories, use Builder
    |
STEP 2: CONTENT    -> Enter name, title, phone, email, company details
    |
STEP 3: MEDIA      -> Upload logo, import background images
    |
STEP 4: DESIGN     -> Colors, typography, layout & effects
    |
STEP 5: QR CODE    -> QR code style, data mode, dot/corner styles
    |
STEP 6: BULK       -> People manager, CSV import/export, batch export
    |
STEP 7: EXPORT     -> Save configs, export PDF/PNG/SVG, card back variants
```

**Key concepts:**
- All changes preview **live** on the card canvas
- **Front / Back / Digital** view toggle at the top to switch card sides
- **Undo/Redo** with Ctrl+Z / Ctrl+Y (10-level history)
- Your work **auto-saves** to IndexedDB — return anytime to continue
- **Light/Dark theme** toggle in the header
- **Card size selector** — US Standard (3.5x2"), EU (85x55mm), Square, Mini
- Toolbar chips: **Align, Snap, Grid, Bleed** overlays for precision

---

## 2. Screen Layout {#layout}

### Desktop (1024px+)
```
+----------------------------------------------------------+
|  Imprintly  "Design the impression you leave."           |
|  [Undo] [Redo]  US Standard 3.5"x2"  [sun/moon toggle]  |
+----+----+------------------------------------------------+
| N  | S  |  [Front] [Back] [Digital]                      |
| A  | I  |  [Align] [Snap] [Grid] [Bleed]  Zoom: [===]   |
| V  | D  |                                                |
|    | E  |      FRONT CARD PREVIEW                        |
| R  | B  |      (live updating)                           |
| A  | A  |                                                |
| I  | R  |      BACK CARD PREVIEW                        |
| L  |    |      (with QR code)                            |
|    +----+                                                |
| 7 icons |                                  Right Panel:  |
| + More  |                                  [Font] [Size] |
+---------+------------------------------------------------+
```

- **Left nav rail** — 7 section icons (Templates, Content, Media, Design, QR, Bulk, Export) plus optional AI
- **Sidebar** — Controls for the active section with sub-tabs
- **Card canvas** — Front and back card previews with zoom controls
- **Right panel** (collapsible) — Quick access to font and card size
- **Toolbar** — Front/Back/Digital toggle, Align/Snap/Grid/Bleed chips

### Mobile (< 768px)
```
+---------------------------+
|                           |
|    FRONT CARD PREVIEW     |
|    (full-width, ~40vh)    |
|                           |
|    BACK CARD PREVIEW      |
|                           |
+---------------------------+ <- slide-up panel (60vh)
|  [Sub-tab pills]          |
|  CONTROLS (current tab)   |
|  (scrollable)         [x] |
|                           |
+---------------------------+
| [icon] [icon] [icon]      | <- fixed bottom nav (60px)
| [icon] [icon] [More...]   |
+---------------------------+
```

- **Fixed bottom nav** with 5 icon buttons + **More** menu (opens remaining sections)
- Tap an icon to open that section's controls in a **slide-up panel** (60vh, animates from bottom)
- Tap again or tap x to close. Semi-transparent overlay behind panel.
- Card preview remains visible above the panel
- Touch targets sized at 44px minimum for accessible controls
- Template grid uses 2-column layout on phones, auto-fill on tablets

### Tablet (768-1024px)
- Hybrid layout: narrower sidebar with card canvas
- Touch-optimized controls with larger tap targets

---

## 3. Getting Started — Your First Card in 5 Minutes {#quickstart}

1. **Pick a template** — Step 1 (Templates) > Gallery shows 92 designs across 10 categories. Click one to apply instantly.
2. **Add your logo** — Step 3 (Media) > Upload a PNG/SVG logo. Choose "Upload Logo" mode and pick your file.
3. **Enter your details** — Step 2 (Content) > Fill in your name, title, phone, email, and website.
4. **Export** — Step 7 (Export) > Click "Quick Export" for a print-ready PDF.

That's it! The remaining steps let you fine-tune colors, QR code, and advanced features.

---

## 4. Step 1: Templates {#templates}

### Gallery (sub-tab)
Browse **92 template variations** across 10 categories in a responsive grid. Use the category filter pills to narrow your selection:
- **Modern Split** — Diagonal two-panel designs
- **Minimal & Clean** — Simple, elegant layouts
- **Executive** — Professional, corporate styles
- **Bold & Creative** — Eye-catching, colorful designs
- **Gradient** — Smooth color transitions
- **Dark & Moody** — Deep, dramatic backgrounds
- **Elegant** — Refined, sophisticated styles
- **Creative** — Artistic, unique layouts
- **Tech** — Technology-themed designs
- **Ribbon** — Featuring decorative ribbon/swoosh elements

Each template is built from one of 26 base designs with color and font variations. Thumbnails update live to show your current background image, cover rectangles, and feathered edges.

**Layout Toggle:** Switch between **Classic Split** and **Modern Split** at the top.

### Builder (sub-tab)
**Custom Templates:** Save your current design to a named category with "+ Save Current Design". Custom templates appear alongside built-ins with an "Imported" filter for one-click reuse.

---

## 5. Step 2: Content {#content}

### Person Details
- **Full Name** — As it appears on the card front
- **Title / Role** — Job title or position
- **Reset Person** button clears all person fields

### Contact Information
- **Phone** — Format as you want it printed
- **Email** — Full email address
- **Website** — URL (http/https prefix auto-stripped for display)
- **Address** — Optional street address (toggle to show/hide)

### Social Media
- **LinkedIn** — Handle, profile URL, or full URL (auto-prefixed)
- **Twitter/X** — Handle or URL (auto-prefixed)
- **Instagram** — Handle or URL (auto-prefixed)

Social links are encoded in the vCard QR code and appear on the digital card landing page.

### Company Details
- **Company Name** — Main company/brand name in the header area
- **Company Subtitle** — Secondary line (e.g., "CONSULTING LLC")

### Taglines
Two tagline lines on the back card:
- **Bold Tagline** — Prominent, accent-colored text
- **Sub Line** — Secondary descriptor, lighter weight

Both support **rich text editing** with per-character bold/italic formatting and individual color control.

### Divider Lines
Toggle visibility of the two horizontal divider lines on the card front.

---

## 6. Step 3: Media {#media}

### Logo (sub-tab)
Four logo modes:
1. **PMI Logo** — Built-in bundled logo
2. **Upload Logo** — Upload your own PNG/SVG/JPG. Separate front/back uploads supported.
3. **Draw Logo** — Simple canvas drawing tool for quick logo sketches
4. **Company Text** — Uses your company name as a text-based logo

**Front/Back Independence:** Front and back cards can use different logos, different color tinting, and different image effects. Toggle "Force white text on back" to control automatic white conversion.

**Logo Library:** Upload multiple logos, name them, and switch between them. Logos persist in IndexedDB storage.

**Image Effects:** Per-side brightness, contrast, and saturation adjustments.

### Background (sub-tab)
Upload a background image (PNG, JPG, SVG) for the front or back card:
- **Opacity** slider (0-100%)
- **Brightness** slider
- **Contrast** slider
- **Saturation** slider

The image becomes the card's background layer behind all other elements.

---

## 7. Step 4: Design {#design}

### Colors (sub-tab)
Individual color pickers for every card element:
- **Front Card:** Light Panel, Dark Panel, Accent Color, Accent End (for gradients), Icon Color, Divider Color
- **Back Card:** Background, Light BG, Dark BG, QR Color, Tagline Bold Color, Tagline Light Color, QR Label Color, QR Background Color

Click any color swatch to open the picker. Type hex values directly for precise control. "Reset All Colors" restores template defaults.

**"Match Front" buttons** — One-click sync of back card colors from front card values.

### Typography (sub-tab)
Per-field controls for **9 text elements**: Person Name, Title, Phone, Email, Website, Tagline Bold, Tagline Light, Company Name, Company Subtitle.

Each field offers:
- **Font family** dropdown (10 fonts: Montserrat, Arial, Arial Black, Trebuchet MS, Georgia, Verdana, Tahoma, Impact, Courier New, Times New Roman)
- **Font size** slider
- **Bold / Italic / Underline** toggles
- **Text alignment** — Left, Center, Right
- **Color** picker
- **Letter spacing** control
- **Reset** per field or all at once

### Layout (sub-tab)
- **Card Size** — US Standard (3.5"x2"), EU (85x55mm), Square, Mini. Auto-scales Y positions when switching.
- **Card Corners** — Corner radius slider for rounded cards
- **Split Position** — Adjust the diagonal split point (0-100%)
- **Split Angle** — Control the angle of the diagonal divide
- **Layout Mode** — Classic Split vs Modern Split

### Effects (sub-tab)
- **Ribbon/Swoosh** — 19 ribbon styles (arc, brand ribbon, double, filled arc, diagonal, wave, corner, slash, etc.)
- **Ribbon controls:** Thickness, opacity, fade, position offset, angle, color gradient
- **Contact icons** — 6 icon styles (circle-filled, circle-outline, square, rounded-square, minimal, none)
- **Icon color** picker

---

## 8. Step 5: QR Code {#qrcode}

### QR Style (sub-tab)
Controls for the back card's QR code appearance and behavior.

**QR Data Mode** — Three modes:
1. **vCard** (default) — Encodes a full vCard contact file. When scanned, the phone prompts to save the contact.
2. **URL** — Encodes any custom URL you enter.
3. **Digital Card** — Generate a standalone HTML landing page:
   - Choose **Dark or Light theme** for the page
   - Toggle **company logo inclusion**
   - **Preview** the digital card in the sidebar
   - **Download** the HTML file to host anywhere
   - Enter the **hosted URL** — the QR code links to this page
   - Includes clickable contact links and "Save to Contacts" button

**QR Label** — Customize the text below the QR code (default: "SCAN TO ADD CONTACT"). Adjustable size, offset, and color.

**QR Dot Style** — Choose the shape of QR code dots:
- Square (default), Rounded, Circle, Diamond

**QR Corner Style** — Finder pattern: Sharp or Rounded

**QR Gradient Fill** — Optional gradient coloring with customizable start/end colors

**QR Center Logo** — Upload a small logo for the center of the QR code (25% exclusion zone maintains scannability)

**QR Position & Size** — X, Y, and size sliders for precise placement

---

## 9. Step 6: Bulk {#bulk}

### People (sub-tab)

**People Manager** — Save multiple contact profiles by name. Each profile stores content fields (name, title, phone, email, website, social links) — not the design. Load a profile to instantly populate all content fields while keeping your design intact.

**CSV Import** — Upload a CSV file to import contacts in bulk:
- Supports .csv, .tsv, .txt files
- **Auto-mapping** intelligently matches CSV columns to card fields (name, email, phone, etc.)
- **Manual remapping** via dropdown selects for each field
- **Preview table** shows first 5 rows before importing
- Imported contacts include batch metadata for tracking

**CSV Export** — Export all saved people as a CSV file for use in other tools.

**Batch Export All People** — Generate a single multi-page PDF containing cards for every saved person. Each person gets front + back pages using the current design. Ideal for printing an entire team's cards at once.

---

## 10. Step 7: Export {#export}

### Export (sub-tab)

**Saved Design Configurations** — Save complete design snapshots (colors, typography, layout, logos, everything). Organize by company name and config name. Load any saved configuration to restore the full design state.

**Backup & Restore** — Export all configurations as a JSON backup file, or import a backup to restore. Supports merge or replace import modes.

**Export Format:**
- **Crop marks & bleed** checkbox — Adds 3.175mm (0.125") bleed and L-shaped crop marks for print shops
- **CMYK color preview** checkbox — Shows approximate C/M/Y/K values on color pickers with out-of-gamut warnings
- **Gamut warning** — Alerts when colors fall outside CMYK gamut before export
- **Quick Export** button — One-click PDF export
- **Copy Config / Reset All** — Utility buttons

### Card Backs (sub-tab)
**Card Back Variants** (Printfinity-style) — Create multiple unique back card designs:
- The **Default Back** always uses your current design
- Click **"+ Add Back Variant"** to create additional back designs
- Each variant has a **color swatch thumbnail** for visual identification
- **Drag to reorder** variants (HTML5 drag/drop)
- Each variant can have its own background, colors, taglines, and QR styling
- When exporting PDF, all variants are included as additional back pages
- Perfect for variety packs or A/B testing designs

---

## 11. AI Studio {#ai}

### Provider Selection
Choose your AI provider:
- **Claude (Anthropic)** — Free tier available (Haiku model, no API key needed)
- **ChatGPT (OpenAI)** — Requires API key
- **Grok (xAI)** — Requires API key

### AI Modes

**Review** — The AI analyzes your current card and provides structured feedback on color harmony, typography, whitespace, visual hierarchy, and professionalism.

**Impact Score** — Rates your card across 5 dimensions (each scored 0-10): Visual Impact, Professionalism, Memorability, Color Harmony, Typography. Includes specific improvement recommendations.

**Template Search** — Describes your design style and suggests external resources from Dribbble, Behance, Canva, and more with direct links.

**Logo Concept** — Describes logo design ideas based on your company. With a paid OpenAI key, generates actual logo images via DALL-E 3 that can be applied directly.

### Design Suggestions
When the AI recommends specific changes, a **Suggestion Panel** appears with before/after card previews:
- **Apply** — Try one suggestion
- **Apply All** — Apply all recommendations
- **Save as Template** — Keep both your original and the AI's version

### Quick Prompts
Pre-written questions appear when the conversation is empty — click one to start an AI interaction without typing.

---

## 12. Theme Toggle {#theme}

Click the **sun/moon icon** in the header to switch between light and dark themes.

- **Dark theme** (default) — Dark backgrounds with light text, optimized for extended design sessions
- **Light theme** — Light backgrounds with dark text

The theme preference is saved to localStorage and restored on page load with no flash of wrong theme (inline script applies theme before first paint).

All UI panels, buttons, inputs, and controls respect the active theme via CSS custom properties.

---

## 13. Keyboard Shortcuts {#shortcuts}

| Shortcut | Action |
|----------|--------|
| **Ctrl+Z** | Undo (10 levels) |
| **Ctrl+Y** or **Ctrl+Shift+Z** | Redo |

Undo/redo tracks all design changes: color picks, position moves, text edits, template switches, and more.

---

## 14. Export & Print Guide {#printing}

### Export Formats
| Format | Use Case |
|--------|----------|
| **PDF** | Print-ready, both sides, at 300 DPI |
| **PNG** | High-res raster images (1050 x 600 px) — front, back, or both |
| **JPG** | Compressed raster — front or back |
| **SVG** | Vector format for professional editing in Illustrator/Inkscape |

### Card Sizes
| Size | Dimensions | Millimeters |
|------|-----------|-------------|
| **US Standard** | 3.5" x 2" | 88.9 x 50.8 mm |
| **EU Standard** | — | 85 x 55 mm |
| **Square** | — | 65 x 65 mm |
| **Mini** | — | 70 x 28 mm |

### Print Preparation Options
- **Crop marks & bleed area** — Adds 3.175mm bleed and L-shaped crop marks at corners for professional print shops
- **CMYK color preview** — Shows approximate CMYK values on color pickers with out-of-gamut warnings (note: true CMYK conversion requires ICC profiles — this is an approximation)

### Print Tips
1. For professional printing, use **PDF export with crop marks enabled**
2. Keep important content **away from edges** — use the Bleed overlay to check safe zones
3. Use the **Grid** overlay for alignment and the **Align** overlay for rule-of-thirds
4. Enable **Snap** for precise positioning (snaps to 45px grid)
5. Verify colors match expectations — screen colors may differ from print
6. If your print shop requires specific formats, use SVG export for maximum flexibility

### Batch Printing
Use **Batch Export All People** (Step 6: Bulk) to generate a single file with all saved contacts on the same design. Each person gets 2 pages (front + back), plus additional pages for each card back variant.

---

## 15. Troubleshooting & FAQ {#faq}

### Common Issues

**Q: My design disappeared when I reopened the app.**
A: Imprintly auto-saves to IndexedDB (browser storage). If you cleared browser data, the save is lost. Use Export > Backup & Restore to create external JSON backups regularly.

**Q: The card preview looks blank or broken.**
A: Try refreshing the page (F5). If using a very large background image, the browser may need a moment to render.

**Q: Colors look different when printed.**
A: Screen (RGB) and print (CMYK) color spaces differ. Enable the CMYK preview checkbox in Export to see approximate print values. For critical color matching, request a proof from your print shop.

**Q: The QR code won't scan.**
A: Ensure sufficient contrast between QR dots and background. Avoid very small QR sizes. If using a center logo, keep it under 25% of the QR area (the app handles this automatically). Test with multiple QR reader apps.

**Q: Can I use this on mobile/tablet?**
A: Yes! The app is fully responsive with touch support. On mobile, controls appear in a slide-up panel from the bottom nav bar. Pinch-to-zoom works on the card preview. All touch targets are 44px minimum.

**Q: How do I share my Digital Card?**
A: In QR Code > Digital Card mode: download the HTML file, upload it to any web host (GitHub Pages, Netlify, your website), then paste the URL into the "Hosted URL" field. The QR code will link to your hosted page.

**Q: How do I import contacts from a spreadsheet?**
A: Go to Step 6 (Bulk) > expand CSV Import > upload your .csv file. The system auto-maps columns to card fields. Review the mapping, adjust if needed, and click Import.

### Browser Support
- Chrome 90+ (recommended)
- Firefox 88+
- Safari 14+
- Edge 90+

### Data Storage
All data is stored in browser **IndexedDB** (database: `imprintly_db`, store: `kv`). No data is sent to any server unless you use the AI features, which send design state to the selected AI provider's API. Theme preference is stored in localStorage for instant load.

---

## Maintainer Notes

### Updating This Documentation
When adding new features:
1. Add the feature to the relevant step section above
2. Update the in-app `HELP_DOCS` object (search `var HELP_DOCS` in index.html)
3. Update the in-app `GUIDE_SECTIONS` object (search `var GUIDE_SECTIONS` in index.html)
4. Update the feature count in MEMORY.md
5. Keep the STAGES array in sync with the documentation structure

### Key Code Locations for Documentation
- `HELP_DOCS` — Contextual help content (search `var HELP_DOCS`)
- `GUIDE_SECTIONS` — Full user guide content (search `var GUIDE_SECTIONS`)
- `HelpDrawer` — Help panel component (search `function HelpDrawer`)
- `UserGuide` — Full guide overlay component (search `function UserGuide`)
- `STAGES` — Navigation structure definition (search `const STAGES`)
- `DEFAULT_STATE` — All state fields (search `var DEFAULT_STATE`)
- `CARD_SIZES` — Card dimension definitions (search `var CARD_SIZES`)
- `DataService` — Storage abstraction (search `window.DataService`)

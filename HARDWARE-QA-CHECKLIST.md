# Hardware QA Checklist — Imprintly

Test on: iPhone (Safari), iPad (Safari), Android phone (Chrome), Android tablet (Chrome)

## 1. Navigation & Layout
- [ ] Mobile nav bar (5 icons + More) renders at bottom, no overflow
- [ ] More menu opens/closes, all 3 extra tabs accessible
- [ ] Tapping a nav icon opens the correct slide-up panel
- [ ] Panel slides up to ~60vh, doesn't cover entire screen
- [ ] Swiping down on panel dismisses it
- [ ] Desktop/tablet: vertical nav rail visible, sidebar scrolls independently

## 2. Card Canvas
- [ ] Front card renders centered, no clipping
- [ ] Back card renders below front, QR code visible
- [ ] Pinch-to-zoom works (two fingers on card area)
- [ ] Zoom slider in toolbar matches pinch level
- [ ] Front/Back toggle buttons work
- [ ] Card doesn't jump or reposition on orientation change

## 3. Touch Interactions
- [ ] Logo drag on canvas: touch-and-drag moves logo smoothly
- [ ] No accidental scroll while dragging logo
- [ ] Color picker (CF component): opens on tap, selects colors
- [ ] Sliders (SL component): thumb drags smoothly, no jitter
- [ ] Range inputs for position: responsive to touch without delay
- [ ] Template thumbnails: tap selects and applies template
- [ ] Buttons: all tap targets ≥44px (comfortable touch)

## 4. Toolbar Chips (Align/Snap/Grid/Bleed)
- [ ] Chips visible on mobile (may need horizontal scroll)
- [ ] Tapping toggles chip active state
- [ ] Grid overlay renders on card when active
- [ ] Bleed overlay shows trim/safe zone lines
- [ ] Align overlay shows rule-of-thirds

## 5. Template Gallery
- [ ] Template grid scrolls smoothly
- [ ] Category filter chips are tappable
- [ ] Template thumbnails load without lag
- [ ] Applying a template updates card immediately

## 6. Text Input
- [ ] Person name, title, phone, email fields accept keyboard input
- [ ] Virtual keyboard doesn't obscure the input field
- [ ] Scrolling panel while keyboard is open works correctly
- [ ] Dismissing keyboard returns to normal layout

## 7. Export
- [ ] Quick Export button triggers PDF download
- [ ] PDF opens correctly on device
- [ ] Crop marks appear if enabled
- [ ] Batch export (multiple people) generates multi-page PDF

## 8. CSV Import (Bulk tab)
- [ ] File picker opens on tap
- [ ] CSV file loads, column mapping UI shows
- [ ] Preview table scrolls horizontally if needed
- [ ] Import button works, people appear in list

## 9. Variant Manager (Export > Card Backs)
- [ ] Add variant button works
- [ ] Variant swatches display colors
- [ ] Switching between variants updates back card
- [ ] Delete variant works

## 10. Theme Toggle
- [ ] Light/dark toggle (sun/moon icon) switches theme
- [ ] All panels, buttons, inputs reflect theme change
- [ ] No flash of wrong theme on page reload

## 11. Performance
- [ ] No visible lag when switching tabs
- [ ] Scrolling panels is smooth (no jank)
- [ ] Card rendering doesn't flicker
- [ ] No blank screen or loading delays > 2s

## Known Limitations
- Drag reorder of variants uses HTML5 drag/drop (may not work on mobile — touch-based reorder would need separate implementation)
- Snap-to-grid only affects slider controls, not direct canvas drag

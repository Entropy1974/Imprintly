# Imprintly — Project Guidelines & Working Rules

> **Owner:** Jeff Berkowitz
> **Last Updated:** 2026-03-13
> **Purpose:** These rules govern how Claude proposes and implements changes to Imprintly. Jeff may update these at any time — ask Claude to present them for editing.

---

## 1. Best Practice Approach

- Always use the **best practice approach** for any proposed solution, even if it requires more work.
- Prefer the **right way** over workarounds, shortcuts, or easy fixes.
- If a solution involves a tradeoff between effort and quality, choose quality.
- Code should be clean, maintainable, and follow established patterns in the codebase.

## 2. Solution Proposals

- **Propose solutions** rather than just implementing — present options with tradeoffs.
- Emphasize: **usability, efficiency, workflow, and UI consistency**.
- Every proposal should consider:
  - How it fits with existing UI patterns and user workflow
  - Whether it improves or complicates the user's experience
  - Long-term maintainability and future redesign compatibility
- If a change requires more work but is the correct approach, that is the preferred route.

## 3. Mobile & Desktop Validation

- **All changes must be validated on both mobile (375×812) and desktop (1440×900).**
- Before implementing any feature that affects mobile:
  - Present options for how it will impact the mobile experience
  - The desktop version is expected to be **more robust and feature-rich**
  - Mobile should be a **lighter, more efficient** version — not a cramped desktop clone
  - Consider touch targets, panel space, and simplified workflows for mobile
- When proposing UI changes, describe the desktop AND mobile behavior separately.

## 4. Future Redesign Awareness

- Any solution should be built with a **future screen/tab redesign in mind**.
- Avoid scattering related controls across multiple tabs/screens:
  - Example: Position controls for related elements should be consolidated, not spread across Style, Tools, and Text tabs
  - When controls are grouped, the **workflow** (what the user does step-by-step) should drive the grouping
- Prefer modular, relocatable code patterns so panels/sections can be moved between tabs without major refactoring.
- Think in terms of **user tasks** ("I want to position my elements") not **code organization** ("this belongs in the Tools component").

## 5. Cost Efficiency & Session Management

- **Break work into smaller, focused segments** to limit context usage per session.
- Propose solutions that can be implemented in **discrete, testable chunks** rather than one massive change.
- Strategies to keep costs down:
  - **Plan first, implement second** — use plan mode to agree on approach before writing code
  - **Focused sessions** — each session should tackle 1-2 specific features, not open-ended exploration
  - **Reusable scripts** — write Python scripts that can be re-run if needed, rather than one-off edits
  - **Clear handoff notes** — end each session with updated MEMORY.md so the next session doesn't waste context re-discovering the codebase
  - **Incremental commits** — commit working changes frequently so progress isn't lost if a session runs long
  - **Avoid rabbit holes** — if a fix is taking too long, propose an alternative approach rather than burning context debugging
  - **Reference memory files** — read MEMORY.md and this file early in each session instead of re-exploring the codebase

---

## How to Update These Guidelines

Ask Claude: *"Show me the project guidelines so I can edit them."*
Claude will display this file's contents and you can provide updated text.

**File location:** `C:\Users\jberk\OneDrive\Documents\Claude Projects\Business Card\pmi-card-editor-v1_1\PROJECT-GUIDELINES.md`

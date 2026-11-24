---
name: dropout-cis
description: Enforce DropOut Tech (琢奧科技) Corporate Identity System (CIS v6.1) across websites, SaaS dashboards (DoBusiness, DoOffice, OneOffice, EverythingOS), business emails, signatures, contracts, and quotations. Applies Dual-White hierarchy (#FFFFFF + #EEF8F7), DropOut Aurora gradients, approved 2-element sub-brand marks (G1/F2/F3/H4), Anti-AI-Slop Swiss-grid modular diagrams & Micro-UI rules, and ADHD-friendly cognitive-safety UI standards.
---

# dropout-cis — 琢奧科技品牌視覺與反 AI Slop 規範

Apply this skill whenever creating, redesigning, or auditing any DropOut Tech (`dropout.tw`, `DoBusiness`, `EverythingOS`, `Do*`) frontend, landing page, or product UI.

## 1. Dual-White Hierarchy (純白 × 薄荷白分工)

- **Marketing Sites (`dropout.tw`)**: **80% Pure White `#FFFFFF` + 20% Ice Mist `#EEF8F7`**.
  - Hero & primary reading sections sit on `#FFFFFF` with ultra-subtle radial Aurora mist.
  - Case studies, workflow, and comparison card sections alternate to `#EEF8F7` so `#FFFFFF` cards lift cleanly without heavy drop shadows.
- **SaaS Dashboards (`DoBusiness`, `EverythingOS`)**: **`#EEF8F7` Canvas + `#FFFFFF` Elevated Cards** for long-session eye comfort and instant visual hierarchy.
- **Deep Anchor**: `#153D61` (Abyss Navy) for headings, sidebars, and footer.
- **Primary Brand & Action**: `#3CA59E` (DropOut Teal) for structural accents; `#F09336` (Action Amber) reserved **strictly** for the primary CTA button and high-priority alerts.

See `tokens.css` and `DESIGN.md` in this skill directory for exact CSS variables and gradient formulas.

## 2. Official Logo & `DO` Sub-Brand Architecture

- **Light-First Rule**: Always use the official full-color lockup (`logo-hud-lockup-color.png` horizontal or `logo-lockup-color.png` vertical) on `#FFFFFF` or `#EEF8F7`. Never invent broken white-segment inversions or stretch aspect ratios. Maintain `1.2X` clear space (`X` = height of `D`).
- **Approved Standalone Sub-Brand Logos (Ultra-Minimalist 2-Element Geometry)**:
  - **`DoBusiness` (G1)**: 270° Teal-Navy ring + 90° top-right Amber growth arc (`assets/dobusiness-mark.svg`, `assets/dobusiness-lockup.svg`)
  - **`DoOffice` (F2)**: Solid Teal-Navy half-disk `D` + hollow Amber ring `O` (`assets/dooffice-mark.svg`, `assets/dooffice-lockup.svg`)
  - **`OneOffice` (F3)**: Solid Teal-Navy vertical pill `1` + hollow Amber ring `O` (`assets/oneoffice-mark.svg`, `assets/oneoffice-lockup.svg`)
  - **`EverythingOS` (H4)**: Horizontal Teal-Navy pill + solid Amber core circle (`assets/everythingos-mark.svg`, `assets/everythingos-lockup.svg`)
  - Every sub-brand mark uses **at most 2 pure geometric elements** (1 Teal-Navy shape + 1 Amber `#F09336` shape) with zero decorative clutter.

## 3. Strict Anti-AI-Slop & Zero Stock Icons Rule

- **BANNED**: Generic stock icon libraries (Lucide/Heroicons/FontAwesome) placed inside `40px` tinted rounded-square boxes, emojis (`✨ 🚀 🧠 ⚙️ 🤖`), and decorative floating blobs/jellyfish.
- **REQUIRED**:
  1. **Real Micro-UI Snapshots**: Replace decorative icons with actual mini product UI (e.g., `$798,187` + sparkline for financial ops; `預約 → 點名 → 結算` status pill for workflows; `來電自動建單中 00:14` live bar for AI voice).
  2. **Modular Swiss-Grid Architecture Diagrams**: Core concepts like **3-Layer Modular Stack** (`Layer 01 DoBusiness/DoOffice/OneOffice` → `Layer 02 EverythingOS` → `Layer 03 FDE Infra`) and **FDE 2-Week Sprint Loop** (clean 3-node horizontal pipeline + dashed return feedback rail) must use clean, flat horizontal Swiss-grid cards — never tilted isometric clip-art diamonds or crooked freehand Bezier loops.

## 4. Business Collateral: Email, Signature, Contracts & Quotations (Logo Placement)

| Collateral | Logo Variant | Placement | Size | Key Rules |
|---|---|---|---|---|
| **Official Email / EDM** | Horizontal full-color (`logo-hud-lockup-color.png`) | Top-left of white `600px` card | `26–32px` height (`>= 16px` margin) | `2–3px` Teal divider below header; max 1 Amber CTA; **no duplicate logo in footer** |
| **Team Email Signature** | Vertical/Square full-color (`logo-lockup-color.png`, 1.15:1) | Far-left, vertically centered beside text | `64–72px` width (2x transparent PNG) | **Tight-cropped with zero wasted whitespace** so it matches the 4-line text block height; `1px` `#D5E6E5` vertical divider |
| **Legal Contract (A4)** | Horizontal full-color (`logo-hud-lockup-color.png`) | Running header top-left | `7–8mm` height (`20mm` page margin) | Contract No. top-right; **zero watermark over signature/stamp boxes** |
| **Quotation / Proposal (A4)** | Horizontal full-color (`logo-hud-lockup-color.png`) | Top-left above company tax ID | `42–45mm` width | Title + Quote No. top-right; `tabular-nums` for all currency columns |

## 5. ADHD-Friendly Cognitive Safety Rules

1. **Max 2 Hero Exits**: 1 Primary CTA (`#F09336`) + 1 Secondary CTA (`#FFFFFF` with `#3CA59E` border). No 10-chapter bottom docks or presentation-mode toggles.
2. **Zero Auto-Rotation**: Never auto-advance tickers, pain-point phrases, or quote carousels. All state changes must be user-initiated.
3. **Zero-Overlap Safe Zone**: Floating widgets/FABs must never cover right-aligned CTAs, card links, or form submit buttons.
4. **Single-Line Controls**: All `<input>` and `<select>` controls are `48px` tall with custom right-aligned chevrons so native arrows never wrap to a second line.
5. **Portrait & Mockup Unification**: All team portraits use `4:3` framing on unified soft studio `#DCEBEA` (no neon-yellow blocks or mixed anime collages). All system screenshots sit inside unified light browser frames (`1px solid #D5E6E5`).

## 5. Verification Checklist Before Shipping

Before declaring any DropOut UI task done:
- Verify in a real browser at both desktop (`1280px` / `1024px`) and mobile (`375px`).
- Confirm zero horizontal overflow, zero overlapping floating elements, zero `48px` `<select>` caret wrapping, and zero stock-icon-in-a-box slop.

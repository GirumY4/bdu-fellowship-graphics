# BDU Fellowship Graphics (`bdu-fellowship-graphics`)

A curated collection of premium, print-ready, and social-media-optimized graphic posters for the **Bahir Dar University Christian Fellowship**. 

This repository houses four distinct visual announcements designed with a unified brand identity. Transitioning away from generic web-like landing pages, these graphics are built as high-fidelity editorial poster compositions tailored for Instagram, Telegram, Facebook, and high-quality printing.

---

## 🎨 Visual Identity & Design System

The project relies on a centralized design system defined in `theme.css`. All four graphics share a cohesive, premium church branding aesthetic characterized by:

* **Single-Page Constraint:** Every graphic is meticulously constrained to render on exactly **one page** with comfortable margins—strictly eliminating empty second-page overflows during PDF export or printing.
* **Refined Typography:** High-contrast font pairing, adjusted tracking, and deliberate line spacing to elevate both English and Amharic typography. Bible verses are treated with elegant, calm layouts while titles command attention.
* **Sophisticated Branding:** The VLM (Vessel of Life Ministry) logo features a transparent background and is scaled proportionally to sit as an elegant brand signature rather than a large decoration.
* **Soft Color Gradients:** Replaced harsh, artificial solid overlays with soft, subtle gradients that keep the background photography visible while maintaining optimal text contrast.
* **Decluttered Layouts:** Shifted away from dashboard components, card shadows, and excess icon decorations in favor of professional, Figma-level poster compositions.

---

## 📁 Repository Structure

```text
bdu-fellowship-graphics/
│
├── reference/
├── assets/
│   ├── fonts/
│   ├── icons/
│   ├── images/
│   ├── logos/
│   ├── social-media-qrcode/
│   ├── theme.css
│   └── typography.css
│
├── 01-online-fellowship-announcement/
├── 02-program-announcement/
├── 03-program-hosts/
├── 04-verse-card/
│
├── src/
│   └── input.css      # Tailwind source
│
├── package.json
├── package-lock.json
└── AGENTS.md

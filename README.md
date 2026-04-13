# GenInvoice

A professional invoice generator with live preview, built as my first programming project while learning web development.

## What it does

Fill in your details on the left, watch the invoice update in real time on the right, then export it as a Word document or PDF.

## Features

- **Live preview** — the invoice updates instantly as you type
- **5 languages** — English, Spanish, Portuguese (PT-BR), Chinese (Mandarin) and Russian
- **Logo upload** — drag & drop your logo with automatic resizing if needed
- **Multi-currency** — USD, EUR, GBP, BRL and CAD
- **Line items** — add as many services/products as needed, with quantity, unit price and automatic totals
- **Tax support** — configurable tax rate with automatic calculation
- **Optional sections** — Logo and Notes & Payment can be toggled on/off
- **Export** — Word (.docx) and PDF export *(Phase 2 — backend in progress)*

## How to use (Phase 1)

Just open `geninvoice.html` in any modern browser. No installation, no server, no dependencies.

```
geninvoice/
└── geninvoice.html    ← open this in your browser
```

## Tech stack

| Layer    | Technology                        |
|----------|-----------------------------------|
| Markup   | HTML5                             |
| Styling  | CSS3 (custom design system)       |
| Logic    | Vanilla JavaScript (ES6+)         |
| Fonts    | Cormorant Garamond + DM Sans      |
| Export   | Node.js + docx library *(Phase 2)*|

## Roadmap

- [x] Phase 1 — Frontend with live preview
- [x] Multi-language support (EN / ES / PT / ZH / RU)
- [x] Logo upload with auto-resize
- [x] Overflow-safe invoice layout
- [ ] Phase 2 — Node.js backend
- [ ] Export to .docx
- [ ] Export to PDF
- [ ] Save / load invoice drafts

## About

This is my first real project built while learning programming from scratch. Every feature was planned, built and refined step by step — from a blank page to a fully functional international invoice tool.

---

*Built with curiosity and a lot of trial and error.*

# Advanced Isoconversional Method (AIC) — Vyazovkin, Epoxy Cure Kinetics

Browser-based tool for model-free cure kinetics of epoxy thermosets from non-isothermal DSC:
Vyazovkin advanced isoconversional method (Eα(α)), KAS cross-check, model-free isothermal prediction.

**Version:** 3.10.0 · **Author:** Flavio Pendolino · **License:** PolyForm Noncommercial 1.0.0

## Use online
GitHub Pages (after enabling, see below):
`https://penfla.github.io/advanced-isoconversi-method-aic-/`

## Use locally
1. Download [`advanced-isoconversi-method-AIC-.html`](advanced-isoconversi-method-AIC-.html) (Raw → Save As, or `git clone`).
2. Open it in any modern browser (double-click). No build, no server, no install.

Chart.js 4.4.1 (cdnjs), SheetJS xlsx 0.20.2 (jsDelivr) and the Inter / JetBrains Mono fonts are loaded from CDN:
**an internet connection is required on first load** (fonts fall back to system fonts; Chart.js/xlsx are required for plots and Excel I/O).

## Enable GitHub Pages
Settings → Pages → Source: *Deploy from a branch* → Branch: `main` / root → Save.

## Files
| File | Role |
|---|---|
| `advanced-isoconversi-method-AIC-.html` | The application (single self-contained HTML/JS file) |
| `index.html` | Redirect to the app (Pages root URL) |
| `.nojekyll` | Serve files as-is on Pages |
| `LICENSE` | PolyForm Noncommercial 1.0.0 |

## Disclaimer
Validate the results against your own reference samples before any analytical, engineering, safety or regulatory use.
This tool performs deterministic calculations; it does not use generative AI (Art. 50 AI Act not applicable).
Commercial use: penfla@me.com

© 2026 Flavio Pendolino | PolyForm Noncommercial 1.0.0

# Road Safety Explainer (Task 1: Website)

Article: *"Sense & Licence"* (Times of India editorial). Question: **why do road deaths rise despite stricter rules?**

## Run it
No install needed. Double-click `index.html`, or serve it locally:
```
python -m http.server 8000      # then open http://localhost:8000
```
Online version (GitHub Pages): <!-- paste link here after enabling Settings > Pages -->

## What it shows
Fatality trend (2015 vs 2025), India vs Vietnam vs Singapore comparison, causes, and the enforcement gap (unpaid e-challans).
All numbers are in `data.js` and sourced to the editorial.

## Tech stack
Plain HTML, CSS and JavaScript. Chart.js 4.4.1 from cdnjs for charts (needs internet). Fonts: Archivo and Source Serif 4 (Google Fonts).

## Design principles (Pragmatic Programmer)
- **DRY:** every statistic lives once in `data.js`; edit numbers only there.
- **Orthogonality:** structure (`index.html`), style (`style.css`), behaviour (`app.js`) and data (`data.js`) are separate.
- **Small iterations:** one commit per feature.
- **Documentation:** `SPEC.md` describes the page; each statistic carries a source note.
- Mobile-first layout, reduced-motion respected.

## Related repos
- Policy agent: <!-- link to road-safety-agent repo -->
- Fine-tuned LLM: <!-- link to road-safety-llm repo -->

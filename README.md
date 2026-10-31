# EnterpriseX

EnterpriseX is a responsive, local-first business intelligence prototype. It uses plain HTML, CSS and JavaScript so it runs without a package installation, paid API or secret key.

## Run locally

Open `index.html` in a modern browser, or serve this folder over HTTP:

```powershell
cd outputs/enterprisex
python -m http.server 8000
```

Then open `http://localhost:8000`. User profile changes, saved opportunities, comparisons, estimates, equipment and diligence statuses persist in that browser's local storage. **Reset demo data** in Settings restores the seeded state.

## Included modules

- Executive dashboard with sample marketplace summaries, charts, activity and maintenance alerts.
- Searchable acquisition marketplace with filters, listing profiles, saved items, comparisons and evaluation handoff.
- Editable new venture and acquisition cost estimators, with text report download.
- Loan, funding, cash flow, break-even and ROI calculators.
- Business digital twin with adjustable revenue, rent and salary inputs plus scenario cases.
- Rules-based equipment monitoring, sample sensor trends, editable readings and maintenance records.
- Illustrative risk screening, due diligence checklist and local file selection.
- Equity-first funding match: calculates a project range from available cash, compares editable bank EMI scenarios, and ranks acquisitions and startup categories against illustrative area population and demand profiles.
- Simulated location comparison with sample catchment populations, contextual demo advisor and risk-aware opportunity matching.
- CSV exports and browser print-to-PDF report flow.

## Prototype limits

The marketplace, lender-rate assumptions, catchment populations, location indicators and sensor readings are illustrative sample data. Bank names link to official product pages, but no live bank rates, pre-qualification or loan sanction is provided. A 90% finance share is a user-selected planning scenario, not a guaranteed lender margin. The estimator, advisor and maintenance module use transparent heuristics and threshold rules; no trained ML model is running. Authentication is a local demo profile, not production identity management. Data is stored in the current browser only. No Supabase, live market feeds, map provider, IoT connection, cloud document upload, legal verification or external LLM is configured. Third-party fonts are optional; system fallbacks keep the UI usable offline.

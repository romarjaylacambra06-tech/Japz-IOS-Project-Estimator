# Japz Project Estimator — iPhone Standalone v8

Professional Philippine construction cost-planning PWA for detailed preliminary BOQ generation and project option analysis.

## v8 upgrades
- Dashboard now has a **Project Overview** panel modeled on the supplied reference layout.
- The dashboard identifies the selected **Basic / Bare, Standard / Modern, or Luxury** finish and displays its photographic reference image.
- Finish selector on the dashboard lets you switch Basic / Standard / Luxury before regenerating the BOQ.
- Project overview shows project type, use, location, GFA, storeys, bedrooms, CRs, kitchens, estimate and estimated cost/m².
- AI Advisor now generates a detailed **ChatGPT analysis prompt** from the current project, BOQ and cost structure.
- **Ask ChatGPT** copies the prompt and opens `chatgpt.com`; paste the generated prompt into ChatGPT for a deeper recommendation using current information when appropriate.
- This browser/PWA build deliberately does **not** embed an OpenAI API key in client-side code. A production API connection should use a secure backend/proxy.
- Dashboard cost composition and project-specific costing trend are visible at a glance.
- Separate **Mobilization**, **Temporary Facilities**, **Permits/Clearances**, **Demobilization**, and optional **Groundbreaking Ceremony**.
- Separate **Miscellaneous**, **Contingency**, **Contractor Profit**, and optional **VAT** calculations.
- Detailed **Unit Cost Derivation** showing material/labor extensions, waste, adjusted rates, unit cost and total.
- **Inflation / escalation engine** with price year, annual escalation %, and manual market adjustment %.
- Location and site-access pricing factors remain active.
- Project-specific historical costing line chart stores the last 12 generated BOQs locally.
- AI Advisory provides local rule-based cost-driver, economic-option, benchmark and completeness checks.
- Photographic visual guides: `visual-basic.png`, `visual-standard.png`, `visual-luxury.png`.

## Pricing note
The app uses planning rates and adjustment factors. It is designed for preliminary estimating and option analysis. Final tender pricing should be reconciled against project plans/specifications, supplier quotations, delivered-to-site freight, taxes, and actual site conditions.

## GitHub Pages upload
Upload these files to the root of your GitHub Pages repository:
- `index.html`
- `manifest.webmanifest`
- `sw.js`
- `icon.svg`
- `visual-basic.png`
- `visual-standard.png`
- `visual-luxury.png`

Then enable GitHub Pages from `main` → `/ (root)`.

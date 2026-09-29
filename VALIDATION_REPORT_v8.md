# Japz Project Estimator v8 Validation

## Static JavaScript validation
- Extracted embedded JavaScript from `index.html`.
- `node --check` passed.

## Calculation-engine validation
Test project:
- 2 storeys
- floor heights 3.0 m and 3.6 m
- Luxury finish
- 2 main doors
- 2 CRs
- 3 bedrooms
- 1 kitchen
- 1 living room
- 1 dining room
- 1 office
- optional groundbreaking included
- VAT enabled

Observed:
- GFA: 106.88 m²
- BOQ lines: 57
- Total project: approximately ₱4,206,679
- General requirements: approximately ₱212,904
- Groundbreaking: ₱30,000
- Miscellaneous: approximately ₱162,596
- Contractor profit: approximately ₱341,451

## v8 feature checks
- Dashboard project overview renders.
- Finish image switches between Basic, Standard and Luxury.
- Dashboard displays project type/use and key project statistics.
- AI Advisor renders the generated ChatGPT prompt.
- Prompt contains project, cost, BOQ and requested analysis instructions.
- Ask ChatGPT action copies the prompt and opens `https://chatgpt.com/`.
- Historical project costing remains available.

## Scope limitation
Full browser UI automation was not claimed in this environment. The calculation engine and JavaScript syntax were tested. Final market pricing must be validated against current project-specific supplier quotations and specifications.

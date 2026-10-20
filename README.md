# Atlas — GCC Intelligence (Flexiple Product Intern prototype)

A polished, working, static web prototype focused on **evidence-aware market discovery and location decision support**. No package install is required.

## Run locally

Open `index.html` in Chrome, Edge, Firefox, or Safari. For a reliable local server and clipboard support:

```bash
cd gcc-atlas
python -m http.server 8080
# open http://localhost:8080
```

## Deploy publicly (required for submission)

Option A: Netlify Drop: drag the `gcc-atlas` folder to https://app.netlify.com/drop and obtain a public site URL.

Option B: GitHub Pages: commit the folder contents to a public GitHub repository; use repository Settings → Pages → Deploy from branch → root. Ensure `index.html` is at the published root.

These deployment actions require the owner's account; no public URL is bundled or claimed.

## Reviewer workflow

1. **Overview**: compare the 2,117 GCC organizations with 3,728 operating units and see evidence citations.
2. **GCC explorer**: search/filter *explicitly synthetic* example records.
3. **City comparison**: change either city and inspect quantitative and qualitative evidence labels.
4. **Partner directory**: filter service-provider categories and review proof requirements.
5. **Decision brief**: enter a project, choose team and goals, generate, copy or download a `.txt` memo.
6. **Research sources**: click the footer link and verify the cited primary report and evidence limitations.

## Architecture

- `index.html`: shell and accessible navigation.
- `styles.css`: design system, responsive layouts, focus states.
- `app.js`: dataset, SPA routing, search, selection and memo builder.
- `sources.html`: transparent source register.

This is a **client-side evaluation prototype**, not an authenticated commercial production system. It intentionally requires no persistent storage and sends no visitor data to an API. Real production use would require server-side identity, licensing, verified entity records, data processing, audit logs, permission management, observability and automated tests.

## Source trust

- Nasscom–Zinnov GCC Landscape 2026: https://zinnov.com/centers-of-excellence/zinnov-nasscom-india-gcc-landscape-2026-report/
- PDF geographic exhibit: https://media.zinnov.com/wp-content/uploads/2026/05/zinnov-nasscom-india-gcc-landscape-2026-report.pdf
- Flexiple statistical aggregation: https://flexiple.com/gcc/statistics

The report supplies aggregate metrics and rounded city GCC-unit counts. **The sample company directory is synthetic.** City qualitative descriptions, indices, category providers and recommendation rules are **illustrative**, not sourced factual benchmarks or vetted business recommendations. The app never claims to contain verified company-level records.

## Next production milestone

Start with one buyer group (international expansion / strategy leads) and a verified India GCC directory plus a decision brief. Build the ingest/verification backend; partner onboarding only after sourcing, consent and dispute processes are defined. Gate SaaS monetization on observed repeat usage and the actual data-licensing position.

## Limits

No backend, login, external LLM, real-time ingestion or live pricing is present. The decision memo is a transparent offline rules engine. HTTPS is recommended for clipboard functionality. No public deployment performed by this artifact.

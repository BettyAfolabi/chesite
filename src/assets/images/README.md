Drop real photos into these folders, matching PROJECT_INSTRUCTIONS.md:

- headshot/         → hero portrait
- field-exposure/    → Mobil plant, ABInBev brewery, She Code Africa, Metis, AScIN, YES Summit, SPE symposium, AIChE exchange
- competitions/      → ChemE-Sports 2022 team/event photos
- certifications/    → optional cert backdrop or scan thumbnails

Use Astro's <Image /> component (astro:assets) once real files are in place,
so images get automatic responsive srcset + lazy loading — important for the
"loads fast on low network" requirement in the spec.

# CareLend Partner HR Portal

Clickable demo of the CareLend partner portal for HR teams at partner companies, built from the "CareLend Partner Portal (HR)" Claude Design canvas.

- `index.html` — the same small renderer as the MVP site, which runs the canvas screens as a plain website
- `screens.json` — every screen of the canvas
- `assets/` — logo, the employee upload Excel template, and the sample National ID image
- `vercel.json` — sends every page address to `index.html`

No build step. Vercel serves the folder as static files. `/signin` opens sign-in, `/demo` opens the Demo guide.

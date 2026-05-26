# DD Studio Plan & Usage Page — Prototypes

Hi-fi static-HTML prototypes of the Datadog Studio Plan & Usage page, hosted via GitHub Pages for stakeholder review.

**Live site:** https://omkarhanamsagar.github.io/dd-studio-plan-usage/

## Credits

- **Designer** — Omkar Hanamsagar
- **Design mentor** — Monica Chen
- **Timeline** — February – April 2026

## Pages

- **Landing** — `index.html`
- **Free plan** — `free.html`
- **Premium plan** — `premium.html`

## Local preview

Just open `index.html` in a browser — no build step.

```bash
open index.html
```

Or serve over http (some browsers are stricter about local files):

```bash
python3 -m http.server 8080
# then visit http://localhost:8080
```

## Notes

- All data is mocked. No backend.
- The floating **Prototype Controls** panel in the bottom-right of each prototype is meta — it's only there to simulate different usage states for review, and is not part of the production design.
- Best viewed on desktop at ≥1280px.

## Source

These prototypes originate from the [DataDog/web-ui](https://github.com/DataDog/web-ui) monorepo at:

```
packages/apps/quick-start/toolkit/page-quick-start/components/products/usage-planning/
  ├── usage-overview-prototype-hifi.html         → free.html
  └── usage-overview-prototype-hifi-premium.html → premium.html
```

This standalone repo is a one-way snapshot — to refresh it, re-copy from the monorepo and push.

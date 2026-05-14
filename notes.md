# Portfolio Notes

## File structure

**Decision: keep everything in one `index.html`.**

Current breakdown: ~280 lines CSS, ~15 lines JS, ~125 lines HTML.

Don't split until:
- CSS grows past ~600–800 lines
- A build step (Vite etc.) is added
- JS grows beyond the theme toggle

Reason: splitting without a bundler trades 1 HTTP request for 3 with no tooling benefit at this scale.

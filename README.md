# Command Broker — AOO &amp; Supplier Engagement (site)

A small static site mapping the practices by which an asset owner/operator (AOO) and a supplier engage to put a governed generative-AI tool into service in critical infrastructure. One spine — the CB-CT six-gate engagement journey — read through two lenses (AOO / Vendor).

Modeled on the Eclectic Technologies `ai-governance-course` site: a single `index.html` shell renders Markdown content via marked.js and hash routing. Deploy on GitHub Pages (a `.nojekyll` file is included). Content pages load by `fetch`, so the site must be served over HTTP (GitHub Pages, or a local `python -m http.server`) — opening `index.html` directly from disk shows a placeholder.

Status: walking skeleton — the engagement spine and track pages are populated; concept, worked-example, and corpus pages are stubs.

# NPO Handbook Viewer

The Handbook for the Countering of Terrorist Financing for Prescribed Non-Profit Organisations is published as a PDF. This renders it as a colour-coded web page instead: each clause is tagged as a statutory requirement, a code of practice or a guidance note, and you can toggle those categories on and off, switch to dark mode, and hover a defined term to read its meaning inline.

The handbook text lives in `policy.md`, fetched and rendered with marked.js.

## Run

The page loads `policy.md` with `fetch()` and pulls marked.js from a CDN, so it needs a local server and a network connection. Opening `index.html` straight off disk will not work in most browsers.

```
python -m http.server 8080
# then open http://localhost:8080
```

## Standing

An old personal prototype, built in my own time and long since moved on from. It is not a work product, and it is not affiliated with, endorsed by or representative of any employer or of the body that publishes the handbook. It does not replace the official published handbook, which remains the authority.

# D3BUG.REG — blog

Static security-research blog. No build step, no dependencies — plain HTML + CSS.
Free hosting via GitHub Pages.

## Preview locally

```bash
cd ~/workspace/projects/d3bug-reg-blog
python3 -m http.server 8000
# open http://localhost:8000
```

## Publish (GitHub Pages)

1. Create a public repo named `d3bug-reg` on GitHub (account: overlinderosier0-afk).
2. Push this folder's contents to `main`.
3. Repo → Settings → Pages → Source: `main` branch, `/ (root)` → Save.
4. Live at `https://overlinderosier0-afk.github.io/d3bug-reg/` within a minute or two.

## Add a new write-up

1. Copy `writeups/template.html` → `writeups/your-slug.html`.
2. Fill in title, date, category, content (follow the TODOs).
3. Add a card for it in `index.html` and in `writeups/index.html`.
4. Commit + push.

## Rules

- Methodology and technique posts only.
- Never publish a live, undisclosed vulnerability. Report privately first;
  publish only after remediation or explicit permission.
- Authorized targets only, always.

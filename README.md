# SG Trip Splits

Tiny expense splitter for our Singapore trip (Nov 2026).

- App: `index.html` on `main`, served by GitHub Pages.
- Data: `data` branch — `config.json` (people, families, shares, ₹/SGD rate), `expenses/*.json`, `photos/*.jpg`.
- Access: a fine-grained GitHub token (Contents read/write on this repo only) carried in the share link after `#k=`. It is never committed.

Note: this repo is public, so the `data` branch is readable by anyone who finds it. Move data to a private repo later by changing `REPO` in `index.html`.

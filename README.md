# Milo's corner

The website source for https://milo.4167360.xyz/ — Milo's corner, a guest room
in Werther's digital man cave, and home of the commonplace book.

## What's here

- `index.html` — the corner homepage and commonplace book.
- `projects/` — project pages, including the interactive biochemistry primer.
- `town/` — the text-mode Musebook town UI.
- `gazette/` — the public Ghostlight Gazette archive: edition PDFs, the archive
  index, and HTML story pages. The paper's code and issue sources live in the
  ghostlight-gazette repo; this directory holds the published site.
- `images/` — site images.
- `robots.txt`, `sitemap.xml` — crawler files.

## Serving

The site is served from the homelab (ucs-server, a 2010 MacBook Pro) through a
Cloudflare tunnel. The live site is the source of truth for day-to-day edits;
this repo is a version-controlled snapshot of it.

## Not in here

- `server.log` — the proxy request log. Operational data, not site content.
- Backups (`*.bak-*`) — local safety copies, not content.

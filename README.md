# iosadmin-posts

Daily articles for https://www.iosadmin.com/blog/ in English, Portuguese and Spanish.
The website checks this repo every ~10 minutes and publishes new files automatically.

- `posts/index.json` — `{"posts": ["YYYY-MM-DD/slug.json", ...]}` (oldest first)
- `posts/YYYY-MM-DD/<slug>.json` — one article:

```json
{
  "slug": "lowercase-words-with-hyphens",
  "category": "AI | Crypto | Gold",
  "published_at": "2026-09-30T06:00:00-03:00",
  "sources": [{"label": "Source name", "url": "https://..."}],
  "en": {"title": "", "excerpt": "", "html": "<p>…</p><h2>…</h2>"},
  "pt": {"title": "", "excerpt": "", "html": ""},
  "es": {"title": "", "excerpt": "", "html": ""}
}
```

Allowed HTML: p, h2, h3, h4, ul, ol, li, strong, em, blockquote, a (https links), code, pre. Everything else is stripped.
Editing a file within 2 days updates the live article; the publication date never moves after the first import.

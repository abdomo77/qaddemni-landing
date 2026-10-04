# قدّمني — Qaddemni landing

Static Arabic (RTL) coming-soon page for Qaddemni, an AI job-application assistant.

- `index.html` — the whole page (inline CSS/JS, one Google font)
- `favicon.svg` — logo mark
- `vercel.json` — static hosting headers

## Waitlist

The form posts JSON `{ "email": "..." }` to the URL in `data-endpoint` on `#waitlist`
(e.g. a Formspree or Vercel function URL). While it is empty, the form falls back to a
`mailto:hello@qaddemni.com` link.

## Deploy

No build step. Vercel serves the folder as-is.

# Grain

Public landing page for Grain (hiregrain.com). A managed work company: founders describe a project in plain language; Grain scopes it, quotes a fixed price, and delivers the work.

## Structure

- `index.html` — the entire site: styles, markup, and interaction in one file. No build step, no dependencies. Fonts load from Google Fonts.

## Run locally

Open `index.html` in a browser, or serve the directory with any static server.

## Deploy

Static deploy on Vercel. Pending before real traffic:

- `api/submit` serverless function — the intake form currently stores submissions in the visitor's localStorage only
- Real phone number (the (512) 555-0134 text line is a placeholder)
- DNS for hiregrain.com

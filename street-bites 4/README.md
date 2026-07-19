# Street Bites

This is a static frontend for the Street Bites street-food discovery app.

## Included features

- Email-style entry screen that lets users select Customer or Shop Owner mode.
- Customer map with drag-to-pan, mouse-wheel zoom, Zoom in, Zoom out, and Reset map controls.
- Typed area search alongside food and shop search.

## Run locally

From this folder, run:

```sh
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

## Deploy online

Upload this entire folder to Netlify, Vercel, or GitHub Pages. The service must serve `index.html` from the project root.

## Important

The current version is a frontend demo. New shop listings stay in the browser only while the page is open. Connect the form to a backend such as Supabase or Firebase to make listings permanent and shared.

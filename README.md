# VitaCelerr Static Site

Static one-page medical courier landing site.

## Files

- `index.html` — page content and forms
- `styles.css` — responsive visual system
- `script.js` — mobile menu, reveal animation, static email-form behavior

## Run locally

Open `index.html` in your browser, or run:

```bash
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Change before publishing

Search and replace:

- `(706) 555-0147`
- `dispatch@vitacelerr.com`
- `vitacelerr.com`
- hours of operation
- training/compliance claims only after completed

## Form behavior

The forms are static. On submit, JavaScript opens an email draft to `dispatch@vitacelerr.com`.

For production, connect the forms to Netlify Forms, Formspree, Basin, or your own backend.

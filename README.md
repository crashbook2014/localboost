# LocalBoost Website

Mobile-first bilingual (Arabic + English) one-page site for LocalBoost.

## Files
- `index.html` — Arabic (default)
- `en/index.html` — English
- `policies.html` + `en/policies.html`
- `assets/styles.css`

## WhatsApp Number
Open both `index.html` and `en/index.html` and replace:

```js
const WHATSAPP_NUMBER = "YOUR_WHATSAPP_NUMBER";
```

with your number (e.g. `9665xxxxxxxx` without + or spaces).  
All main buttons will then open WhatsApp automatically.

## Deploy free on GitHub Pages

1. Create a new public repository on GitHub (e.g. `localboost` or `yourusername.github.io`).
2. Upload all these files and folders keeping the structure:
   - index.html
   - policies.html
   - assets/
   - en/
3. Go to Settings → Pages → Source: Deploy from branch → main / root.
4. Your site will be live at:
   - `https://yourusername.github.io/localboost/` (project site)
   - or `https://yourusername.github.io/` (if you named the repo yourusername.github.io)

### Notes
- Update the JSON-LD `url` fields in both HTML files with your real GitHub Pages URL.
- Arabic is the default (RTL). Language switcher is in the header.
- The “Get Automated” package is marked Coming Soon and not clickable.
- No fake reviews or guarantees.

Built for LocalBoost — North Riyadh. Independent freelance service.

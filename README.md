# Banbunchee Phitsanulok Website

Bilingual responsive website for **บ้านบัญชี พิษณุโลก / Banbunchee Phitsanulok**, developed from the approved visual mockup.

## Current status

- [x] Responsive one-page layout
- [x] Thai / English language switch
- [x] Services, company profile, pricing, process and contact sections
- [x] Mobile navigation
- [x] LINE, email, telephone and Facebook calls to action
- [x] GitHub Pages-compatible static site
- [ ] Confirm the exact LINE OA ID and QR code
- [ ] Confirm the full office address
- [ ] Confirm all telephone numbers and email
- [ ] Confirm final wording, prices and public statistics
- [ ] Add custom domain when available

## File structure

```text
.
├── index.html
├── css/style.css
├── js/main.js
├── assets/
│   ├── banbunchee-logo.png
│   ├── flowaccount-partner.png
│   └── hero-accounting.jpg
├── docs/
│   ├── CONTENT_CHECKLIST.md
│   └── PROJECT_DECISIONS.md
├── CHANGELOG.md
└── .nojekyll
```

## Editing

- Main page content: `index.html`
- Colours, spacing and responsive layout: `css/style.css`
- Thai/English text and menu behaviour: `js/main.js`
- Images: `assets/`

## Local preview

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## GitHub Pages

In repository settings, open **Pages**, choose **Deploy from a branch**, then select `main` and `/ (root)`.

# VEGZ — Farm-to-Business Vegetable Supply

**Live website:** https://vegz.online/  
**GitHub Pages repository:** https://github.com/Manojhole/vegz-app-in.github.io

VEGZ is a Kannada/English business introduction website for a farm-to-business vegetable supply concept in Karnataka. It presents the brand, explains the intended farmer-to-business model, highlights vegetable categories and service areas, and helps visitors make an enquiry.

## Website highlights

- Nature-inspired green and cream visual design.
- Responsive layout for mobile, tablet and desktop.
- Animated hero, scroll-reveal sections, reading-progress indicator, refined hover interactions and subtle desktop card tilt.
- Accessible keyboard focus, mobile-menu keyboard handling and support for `prefers-reduced-motion`.
- Kannada-first content with English search/social metadata.
- Search metadata, canonical URL, Open Graph/Twitter cards and Schema.org structured data.
- FAQ accordion and contact enquiry flow.

## Tech stack

- HTML5
- CSS3 (responsive layout and motion)
- Vanilla JavaScript
- GitHub Actions
- GitHub Pages

## Repository structure

```text
.
├── index.html
├── README.md
└── .github/
    └── workflows/
        └── static.yml
```

## Local preview

No build step or package installation is required. Open `index.html` in a browser, or start a local static server from the repository root:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Deployment

The workflow at `.github/workflows/static.yml` deploys the repository root to GitHub Pages when changes are pushed to `main`. You can also start it manually from **Actions → Deploy static content to Pages → Run workflow**.

Repository settings should have **Settings → Pages → Build and deployment → Source: GitHub Actions** selected.

## SEO and content maintenance

The page includes a title and description, canonical URL, social preview metadata and structured data. Keep the business details accurate as the service launches.

Before publishing real contact details, update and verify the email address and social profile URLs in `index.html`. The enquiry button currently prepares an email in the visitor's email application; it does **not** send data to a server. A backend or form provider is needed for direct form submissions.

Do not add fake phone numbers, placeholder WhatsApp links, hidden keyword-stuffed text or unverified service claims. Update service areas, availability, opening hours, prices and claims only when confirmed.

## Contributing

This repository contains the public-facing static website. Use a feature branch and pull request for substantial changes, and check the GitHub Actions deployment result after merging.

## License

Business website content and branding are owned by VEGZ. All rights reserved unless the repository owner specifies otherwise.

---

Made with care in Karnataka 🌱

# Nova Management

Website for Nova Management, a creator management agency that scales creators and models into the top 0.1% with 24/7 chatting, branding and marketing, hybrid and full management.

## Pages
- **Home**: hero, services, results path, process, FAQ.
- **Apply** (`#apply`): a 3-step sign-up form (about you, how we reach you, your page) with a confirmation screen.

## Getting applications by email
Open `index.html`, find `const FORM_ENDPOINT = "";` near the bottom, and paste a form endpoint such as a Formspree URL (`https://formspree.io/f/xxxxxxx`). Every application is then emailed to your team. Left empty, the form still works and shows the confirmation, but the details are not sent anywhere.

## Hosting
It's a single static file. GitHub Pages serves it from the `main` branch root.

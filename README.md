# Vatsal Bokarvadiya — Portfolio

A single-file, pure frontend portfolio website. No backend, no APIs.

## How to use
1. Keep the `assets` folder next to `index.html` — certificate images load from `assets/certificates/`.
2. Open `index.html` in any browser — that's it.
3. To host it for free, drag this whole folder onto Netlify, or push it to a GitHub repo and enable GitHub Pages.

## Features
- Dark/Light (black & white) theme toggle — top-right button in the nav
- Sections: Hero, About, Skills, Experience, Projects, Certificates (13 certs, filterable by issuer), Contact
- Click any certificate card to open the real certificate image in a full-screen viewer, with download and "open in new tab" options
- Custom cursor, typewriter animation, scroll reveal animations
- Fully responsive (mobile-friendly)

## Customize
- Update GitHub project links in the Projects section (search for `href="#"`)
- Update LinkedIn/GitHub URLs in the Contact section
- Edit certificate entries inside the `#certificates` section in `index.html`

Built with HTML, CSS, and vanilla JavaScript only.

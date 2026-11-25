# LoriAni Consulting

Additional version with company information and adapted Instagram copy. The original design version is maintained separately in `SamirAh90/loriani_consulting`.

A responsive Swedish consulting website based on the supplied black, ivory and champagne gold designs.

**Public website:** https://samirah90.github.io/loriani_consulting_extra/

## Pages

- `index.html` – Home
- `tjanster.html` – Services
- `om-oss.html` – About
- `kontakt.html` – Contact

The website uses plain HTML, CSS and JavaScript. It needs no build step, package installation, API keys or backend. All page links and assets use relative paths compatible with GitHub Pages project hosting.

## Local preview

Run `python -m http.server 8080` from this directory, then open http://localhost:8080.

## Editing

Edit the HTML files for page content, `assets/site.css` for the original design, `assets/content.css` for the company and editorial sections, and `assets/site.js` for the mobile menu and contact interaction. The SVG logo and icons are scalable recreations of the supplied references. The office and growth images were generated for this website; prompts are recorded in `assets/IMAGE-PROMPTS.txt`.

Company copy and details are based on the material supplied by the business: LoriAni Consulting AB, organisation number 559486-4125, Sikvägen 16, 135 41 Tyresö. The home page includes evergreen articles adapted from its Instagram copy. Financial statements, credit ratings and third-party advertisements are not part of the marketing website.

## Contact form

The contact form validates the required fields and prepares an email to **loriani.consulting@gmail.com** in the visitor's email app. The visitor sends the email from that app. The website does not store submissions or claim that a message has been sent. A working email app is required; the address is also available as a direct email link.

## GitHub Pages

Deploy from **main / (root)** in the repository's **Settings → Pages**. `.nojekyll` lets GitHub serve the files directly. Updates to `main` are published automatically.

The two display fonts load from Google Fonts, with local Georgia and Arial fallbacks. No analytics, cookies or third-party form processing are included.

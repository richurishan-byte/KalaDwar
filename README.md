# KalaDwar – From Craft to Click

A simple online portfolio for traditional Indian artists. Artists can show their work, tell their story, and share a single link or QR code so buyers, galleries, and visitors can reach them.

Built for **ART//CODE 2026 · PS-02 Artist Visibility**.

**Live site:** [https://richurishan-byte.github.io/KalaDwar/](https://richurishan-byte.github.io/KalaDwar/)

## What it does

- Browse featured artists and a gallery of sample artworks (Madhubani, Warli, Kerala Mural, Pattachitra, Gond)
- Open an artist page with bio, artworks, and a shareable artwork card
- Copy captions in **English** or **Malayalam**
- Share a portfolio with a **QR code** or native share sheet
- Send a buy / commission / workshop enquiry by email
- Create a new portfolio from a short form (stored in the current browser session)

Sample profiles and artworks are illustrative.

## How to run locally

This is a static site. No build step or server-side code is required.

1. Open `index.html` in a browser, or
2. Serve the folder with any static file server, for example:

```bash
npx serve .
```

Then visit the URL printed in the terminal.

## Deploy on GitHub Pages

The site is published from the `main` branch root.

1. Push this repository to GitHub
2. In the repo: **Settings → Pages**
3. Set source to **GitHub Actions** (or **Deploy from a branch** → `main` / `/ (root)`)

After Pages is enabled, the site is available at:

`https://richurishan-byte.github.io/KalaDwar/`

## Tech

- Single-page `index.html` (HTML, CSS, JavaScript)
- Hash-based routing (`#artist-id`, `#create`)
- SVG artwork motifs generated in the browser
- [QRCode.js](https://cdnjs.cloudflare.com/ajax/libs/qrcodejs/1.0.0/qrcode.min.js) for portfolio QR codes
- Google Fonts: Playfair Display and Inter

## Repository

[https://github.com/richurishan-byte/KalaDwar](https://github.com/richurishan-byte/KalaDwar)

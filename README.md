# Bhakti Vriksha Website

A single-page, mobile-first website for visitors who scan a QR code at the booth.

- `index.html` is the entire site. The logo is embedded inside it, so no other files are needed.
- Call and Text buttons use the number +1 (972) 768-3436. To change it, search `19727683436` in `index.html` and replace every match.

## Sign-up form
Near the bottom of `index.html`, find `var FORM_ENDPOINT = "";` and paste your Formspree address between the quotes (it looks like `https://formspree.io/f/abcdwxyz`). Until then, the form opens a text message to the contact number instead.

## Deploy (Render Static Site)
- Build Command: leave blank
- Publish Directory: `.`

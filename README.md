# AdiArts — Original Artwork Website

A responsive portfolio for **Aditya Bhardwaj**, a 10-year-old pencil-sketch artist.

## What's included

- **17 original drawings** supplied for this project. Photographs have been correctly oriented, cropped to emphasize the sketchbook art, and gently optimized without redrawing the art or erasing the artist's pencil marks/signatures.
- Homepage featuring the original peacock drawing and a portrait of Aditya Bhardwaj.
- Original, unaltered photo of the young artist used in the hero mini-polaroid and About section; a close framing is additionally optimized for the smaller card.
- **Separate `instagram.html` page** with an Instagram-style preview of Aditya’s artwork (not a live feed), his portrait, an external link to the real `@adi_arts05` account, and the provided original orange QR code. The homepage also shows the QR and profile preview, and the gallery links to this social page.
- **Separate `gallery.html` page** with all 17 original drawings, category filters (Wildlife, Portraits, Devotional, and Imagination), and full-screen artwork viewer. Homepage displays a selection of six featured sketches with a link to the complete gallery.
- Artwork viewer with full-resolution image, descriptions, next/previous arrows, and Escape-key close.
- Instagram buttons linking to **[@adi_arts05](https://www.instagram.com/adi_arts05/)** in the navigation, contact section and footer.
- Responsive layouts for desktop, tablet and mobile. No frontend build process necessary.
- Credits appear in both page footers: **Developed by Akshay Goyal** and **Designed by Aditi Bhardwaj**.

## Open the website

Double-click **`index.html`** to open the homepage in a modern browser. Click **Art gallery** in the navigation or **Open the full art gallery** to open **`gallery.html`**. You can also directly open `gallery.html`.

The core site works offline. Google Fonts load from Google when internet is available and fall back to local fonts otherwise. Instagram links require internet.

## File layout

```text
index.html
gallery.html
instagram.html
styles.css
script.js
artworks.json
assets/
  favicon.svg
  social/
    adiarts-instagram-qr.png
  artist/
    aditya-portrait.webp
    aditya-headshot.webp
  drawings/
    regal-peacock.webp
    regal-peacock-thumb.webp
    ... 16 more full-size originals + 16 thumbnails
```

## Add drawings in the future

1. Export a correctly oriented WebP or JPG photo into `assets/drawings/`.
2. Open `script.js` and add an entry to the `artworks` array near the beginning of the file. The entry should contain a unique `id`, `title`, `category`, `image` path, optional `thumbnail` path, descriptive `alt`, `description`, `sample: false`, and optional `width` / `height` dimensions.
3. Categories supported by the existing filter buttons: `wildlife`, `portraits`, `devotional`, `imagination`.
4. Update the *All drawings* number on `gallery.html` if you add images, and update the homepage teaser text/count as needed.
5. Optionally update `artworks.json` to keep the editable metadata in sync.

## Publish on Hostinger

Upload **the contents** of this folder (not the folder itself) to your domain's `public_html` directory. Make sure `index.html`, `gallery.html`, `instagram.html`, `styles.css`, `script.js`, and `assets/` are together in the same folder. SSL and a domain/subdomain are configured separately in hosting.

## Publish on GitHub Pages

Upload the contents of this folder to a repository, then enable GitHub Pages (Settings → Pages → Deploy from branch → `main` → root). Relative asset paths work from a normal Pages repository path.

## Child privacy

The website displays the child's portrait, supplied for publication by the website owner. Confirm parent/guardian consent before publishing it publicly. The website contains no child's phone number, email address, school, street address, or open contact form. The Instagram account was supplied by the website owner for use in the portfolio. An adult should oversee any account access, public messages, social media uploads, and enquiries.

## Credits

Artwork: Aditya Bhardwaj. Website name: AdiArts. **Developed by Akshay Goyal. Designed by Aditi Bhardwaj.**

## Instagram profile preview and QR

The QR image under `assets/social/adiarts-instagram-qr.png` is the **original user-provided QR artwork**. It has been copied without re-encoding or modification. The QR card is clickable and links to https://www.instagram.com/adi_arts05/; visitors can also open the original QR at full resolution. QR scanning behavior depends on the Instagram app/device, so a direct link is always available.

The profile-like design on the homepage and `instagram.html` is a **local preview of the AdiArts art gallery**, NOT an official Instagram embed or automatically updated live feed. We do not show invented Instagram post counts, likes, followers, or content. A live embed would require eligible public content and Instagram-provided embed code or approved API integration.

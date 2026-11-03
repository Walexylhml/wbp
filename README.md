# We Became the Proof website

A three-page static website: Home, the 1967 Championship Legacy, and Amir Is Still Unhoused / The Morrill Acts. No database, no build step, no login. Plain HTML and CSS, so anyone on the team can edit the words.

## The files

| File | What it is |
|---|---|
| `index.html` | The Home page |
| `1967.html` | The 1967 Championship Legacy page |
| `amir.html` | The Amir / Morrill Acts page |
| `styles.css` | The look of the whole site: colors, fonts, spacing (shared by all pages) |
| `assets/` | All images. Replace a file here with a real one of the same name and it updates everywhere. |
| `vercel.json` | Hosting settings for Vercel (caching). You rarely touch this. |

## How to change the words on a page (no coding needed)

1. On GitHub, open the page file (for example `1967.html`).
2. Click the pencil (Edit) button.
3. Find the sentence you want to change. The visible text sits between tags like `<p>…</p>` or `<h2>…</h2>`. Change only the words, not the tags.
4. Scroll down, click **Commit changes**. Vercel republishes the site in under a minute.

Tip: if you ever break the layout, GitHub keeps every old version, so you can always revert.

## How to replace an image

Each image is referenced by its file name inside `assets/`. To swap one:

1. Put your real image in a file with the exact same name as the placeholder (for example `assets/19510.jpg`).
2. On GitHub, open the `assets` folder, choose **Add file → Upload files**, drop your image in, then **Commit**.

The page uses it automatically. Keep roughly the same shape (wide photos stay wide) so the layout still fits.

### Images to replace with final, approved versions
- `WBP_Official_Transparent_Logo.png` is the official logo. Once it is in place, switch the header text for the logo image.

Real images already in place: the restored and original 1967 team photo, and the Amir campaign artwork.

## The survey

`survey.html` is the branded Connection Check form. It posts responses straight into a
Google Form, which feeds a Google Sheet, so the data lives where the team expects it.
The form's field IDs are set once in the `GFORM` block near the bottom of `survey.html`.
The landing-page QR code (`assets/survey-qr.png`) and the "Open the survey" button both
point to `survey.html`.

## The brand colors

All colors live at the top of `styles.css` in the `:root` block as named variables
(`--red`, `--red-deep`, `--ink`, `--paper`, and so on). The red values are placeholders.
Replace them with the exact colors pulled from the official WBP logo. Change them in that
one place and the whole site updates. Do not use the Thoughts 2 Lyfe colors.

## Deployment

The repo is connected to Vercel. Every commit to the main branch auto-deploys.
To use the custom domain: Vercel project → **Settings → Domains → Add** `webecametheproof.com`,
then add the DNS records Vercel shows at your registrar. HTTPS is automatic.

## Notes carried over from the brief
- No payments, login, shop, contact forms, or impact statistics (those wait for evidence-backed data).
- The historical sources are cited on their pages.
- Verify image and photo rights before public launch. The 1967 photo shown as the hero is digitally restored, so keep the authentic original for the archival record.

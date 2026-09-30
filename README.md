# Kartik Singh — Portfolio

A single self-contained file (`kartik-singh-portfolio.html`) — no build step, no
dependencies to install. Rename it to `index.html` and it's ready to host
anywhere that serves static files.

**What's inside:**
- Fonts (Bangers, Kalam, Inter, IBM Plex Mono) load from Google Fonts, so the
  page needs internet access to render correctly.
- The résumé PDF is embedded directly in the file (as base64), so the
  "Download Résumé" button works immediately, with zero extra setup — on
  GitHub Pages, Netlify, or any other static host.
- Everything else — CSS, JS, all page content — is inlined in that one file.

---

## Deploy it — GitHub Pages (free, permanent)

### 1. Create a new repository
Go to [github.com/new](https://github.com/new). Name it exactly:

```
Kartik281204.github.io
```

(your username + `.github.io` — this exact name tells GitHub "this is my
personal site" and publishes it at the root of that URL, with nothing extra
in the path). Set visibility to **Public** — GitHub Pages requires this on a
free account. Click **Create repository**.

### 2. Upload the file
On the new repo's page, click **uploading an existing file** (or
**Add file → Upload files** from the toolbar). Drag in
`kartik-singh-portfolio.html`.

### 3. Rename it to `index.html`
Before committing, click into the filename field and rename the file to
exactly:

```
index.html
```

GitHub Pages only auto-serves a file with this exact name as the homepage —
anything else and visitors get a 404 instead of your site.

### 4. Commit
Scroll down and click **Commit changes** (the default `main` branch is fine).

### 5. Turn on GitHub Pages
Go to the repo's **Settings** tab → **Pages** (left sidebar). Under
**Build and deployment**:

- Source: `Deploy from a branch`
- Branch: `main`, folder: `/ (root)`

Click **Save**.

### 6. Wait about a minute, then visit your URL
Refresh the Pages settings screen. It'll show a banner like:

> Your site is live at `https://kartik281204.github.io/`

That's your permanent portfolio URL from now on.

---

## Updating the site later
Open `index.html` in the repo, click the pencil (edit) icon, make your
change, commit. The live site updates automatically in about a minute — no
separate deploy step.

## Want a link right now, before setting up GitHub?
Go to [netlify.com/drop](https://netlify.com/drop) and drag the HTML file
(renamed to `index.html`) onto the page. You get a live URL in seconds, no
account required. It's only temporary unless you claim it with a free
account afterward — treat GitHub Pages as the permanent home, and this as a
quick way to grab a link to share today.

## Custom domain (optional)
Once GitHub Pages is live, you can point a domain you already own (e.g.
`kartiksingh.dev`) at it from **Settings → Pages → Custom domain**. GitHub's
own docs walk through the exact DNS records your domain registrar needs.

---

## Other files in this folder
- `Kartik_Singh_Resume.docx` / `Kartik_Singh_Resume.pdf` — your résumé, for
  emailing directly to recruiters or attaching to applications. Not part of
  the site deployment above.

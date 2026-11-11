# RISEN at Norwich University

Website for RISEN (Research in Sport, Education & Neuroscience) and the proposed project *Real-time neurofeedback to enhance cognitive resilience*.

## Files

```
index.html        the whole page (text, layout, styles)
images/           logos, team headshots, lab photo, infographic
README.md         this file
```

## Publish it free with GitHub Pages

1. Sign in at github.com and click **+ → New repository**.
   - Name it something like `risen` (this becomes part of the web address).
   - Set it to **Public**. Leave the other options alone and click **Create repository**.
2. On the new repo page, click **uploading an existing file**.
3. Unzip `risen-site.zip` on your computer. Drag **index.html**, **README.md** and the whole **images** folder into the upload box. Click **Commit changes**.
   - Check that the `images` folder shows up in the repo with all 8 pictures inside. The page needs it.
4. Go to **Settings → Pages** (left sidebar).
   - Under **Build and deployment**, set **Source** to *Deploy from a branch*.
   - Set **Branch** to `main` and folder `/ (root)`. Click **Save**.
5. Wait 1–2 minutes and refresh the Pages screen. Your address appears at the top:
   `https://YOUR-USERNAME.github.io/risen/`
6. Open that address on your phone to check it, then use it for the QR code.

## Making changes later

- **Text:** open `index.html` in the repo, click the pencil icon, edit, then **Commit changes**. The live site updates in about a minute.
  - Team names, titles and bios are in the `TEAM` list near the bottom of the file.
- **Photos:** upload the new file into `images/` with the same file name to replace one.
- **New lab photo:** upload it to `images/`, then copy one `<figure>...</figure>` line in the "In action" section and change the file name.

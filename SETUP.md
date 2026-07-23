# दुर्गेश रुद्र सिंह — Website + Photo Admin

Simple guide to put the site online and change photos yourself.

## Files
- `index.html` — the website
- `admin.html` — the photo manager (private — for you only)
- `content.json` — remembers which photos are set (managed automatically)
- `assets/` — where uploaded photos are stored

## One-time: put it online (GitHub Pages, free)
1. Create a free account at github.com.
2. Make a new repository named `durgesh-singh-portfolio` (Public).
3. Upload ALL these files into it (drag-and-drop works): `index.html`, `admin.html`, `content.json`, and the `assets` folder.
4. In the repo: **Settings → Pages → Branch: main → Save**.
5. After a minute your site is live at: `https://<your-username>.github.io/durgesh-singh-portfolio/`

## Changing photos (anytime)
1. Open `admin.html` — either the live one (`.../durgesh-singh-portfolio/admin.html`) or just double-click the file on your computer.
2. **Step 1 — Connect (only the first time):**
   - GitHub username, repository name (`durgesh-singh-portfolio`), branch `main`.
   - Access token: open https://github.com/settings/personal-access-tokens/new
     - Repository access → **Only select repositories** → pick this repo
     - Permissions → Repository → **Contents** → **Read and write**
     - Generate, copy, paste it into the admin panel, click **Save & Connect** (should say "Connected ✓").
3. **Step 2 — Change photos:** each card is one photo on the site. Choose an image, click **Upload**. Done — the live site updates within a minute.

Big phone photos are resized automatically, so uploads stay fast.

## Notes
- The token is stored only in your own browser. Keep the token private; anyone with it can edit the repo.
- Videos are placeholders for now — send them later and they can be wired in.
- Contact details on the site: **Singhdurgeshrudra@gmail.com · +91 98118 82131**.

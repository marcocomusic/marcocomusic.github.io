# MARCOCO

Portfolio site for MARCOCO, Berlin house & techno DJ — https://marcocomusic.github.io

- `index.html` — the site. All text, links and media come from `content.json`.
- `admin/` — the editor at https://marcocomusic.github.io/admin
  - Sign-in: email + password + authenticator app code.
  - `admin/vault.json` holds the GitHub key, encrypted with the admin password (AES-GCM, PBKDF2-SHA256 310k).
  - Lost access? Delete `admin/vault.json` and open /admin to run first-time setup again. Content is not affected.
- New uploads from the admin go to `assets/uploads/`.

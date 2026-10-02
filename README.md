<div align="center">

# ☁️ Kumo

**A personal, end-to-end encrypted cloud file explorer on top of your own Google Drive accounts.**

[Home page](https://f0rd2017.github.io/kumo-site/) · [Privacy policy](https://f0rd2017.github.io/kumo-site/privacy.html)

</div>

---

This repository hosts the public home page and privacy policy of **Kumo**, used on the Google OAuth
consent screen.

## What Kumo does

- 🔒 **Encrypts on your device.** Files are split into chunks, compressed where it helps and encrypted
  (XChaCha20-Poly1305) before upload. Google stores only unreadable encrypted data.
- 🧩 **Spreads across accounts.** Chunks are distributed evenly across all the Google Drive accounts you
  connect.
- 🗂️ **Feels like a file manager.** A native desktop app with grid and list views, previews, a video
  player and a text editor.
- 🙈 **Sees only its own files.** Access is limited to the `drive.file` scope — Kumo never touches the
  rest of your Drive. There is no server and no developer backend.

## Site

Plain static HTML served by GitHub Pages:

| File | Purpose |
|---|---|
| [`index.html`](index.html) | Home page |
| [`privacy.html`](privacy.html) | Privacy policy |

## License

[MIT](LICENSE)

# kokupocket

This repository contains a simple **Kokurikulum Merit Calculator** web page.

Open `index.html` in a browser to try the calculator. The form lets you enter:

- **Kehadiran** (attendance)
- **Penglibatan Berterusan / Penilaian Berterusan**
- **Penglibatan** level selection
- **Pencapaian** (achievement) across four categories (highest value chosen)
- **Jawatan** (position)
- **Bonus** activities

Click *Calculate* to see your cocurriculum mark as a percentage (out of 100).

Feel free to modify the weights or options in the HTML/JS file.

---

## Publishing a permanent link

You can make the calculator available via GitHub Pages:

1. Push this repository to GitHub under your account (e.g. `m-9054672-pixel/kokupocket`).
2. Enable Pages in **Settings → Pages** and select the `gh-pages` branch (the workflow below will create it automatically).
3. A workflow is included at `.github/workflows/pages.yml` that deploys the repository root on every push to `main`.

Once configured, the site will be available at:

```
https://<your-username>.github.io/kokupocket/
```

(or the custom URL shown in the Pages settings).

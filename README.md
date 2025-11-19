# Prae Celebration Modal

Self-contained celebration page for Prae’s research milestone. It features:

- Kanit + Noto Sans Thai/Emoji typography
- Animated paw confetti and floating card
- Bible verse (Isaiah 43:19) and Thai love note
- Golden Retriever portrait (`prae-with-golden-min.png`)

## Files

| File | Description |
| --- | --- |
| `CongratsModal.html` | Main HTML/CSS/JS page. Includes the confetti animation and modal card layout. |
| `prae-with-golden-min.png` | Anime illustration displayed inside the photo frame. |

## Preview locally

Open `CongratsModal.html` directly in your browser (double-click the file) – everything is self-contained.

_Optional_: run a simple server if you prefer testing over HTTP:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080/CongratsModal.html`.

## Deploy with GitHub Pages

1. Commit the repo.
2. In GitHub → Settings → Pages, select your branch (e.g., `main`) and the `/root` folder.
3. After GitHub Pages builds, access `https://<username>.github.io/<repo>/CongratsModal.html`.

## Customization

- Edit the copy inside `CongratsModal.html` to change messages or verses.
- Update `prae-with-golden-min.png` with another portrait (keep the same filename or update the `<img src>`).
- Animation speed: adjust the `animation` value on `.card-orbit` for faster/slower floating.

Feel free to fork and tailor to a different celebration. The layout is fully static, so any static host (Pages, Netlify, Vercel, etc.) will work.

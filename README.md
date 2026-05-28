# Proxy Policy Tuning — project page

Anonymous project page for the CoRL 2026 submission **"Proxy Policy Tuning:
Inference-Time Adaptation of Robotic Foundation Models"**. Live at
<https://proxypolicytuning.github.io>.

The page is based on the [Nerfies project page template](https://github.com/nerfies/nerfies.github.io)
(CC-BY-SA 4.0) with all author-identifying links removed.

## Editing locally

The page is plain static HTML in `index.html` + assets under `static/`.

To preview, open `index.html` in a browser or run a tiny static server:

```bash
python3 -m http.server -d webpage 8000
# then open http://localhost:8000
```

## Placeholders to fill in before / after the review window

- `index.html`: replace `href="#"` on the Paper / Code buttons with the real
  URLs once the submission has a public-facing PDF / repo.
- `static/images/method.png`: add a method-overview diagram (not yet checked in).
- `static/images/teaser.png`: currently a copy of the tasks+results figure — swap
  in a dedicated teaser if you make one.

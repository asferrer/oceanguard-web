# oceanguard-web

Static landing page of OceanGuard AI, an Android application for offline marine debris detection and reporting
with Gemma 4. The page (English and Spanish) presents the application, its on-device stack, the privacy model,
the related publications and the APK download links.

## Structure

```
index.html   Single-file page (HTML, CSS and JavaScript; EN/ES language toggle)
assets/      Logo and favicons
```

There is no build step and no dependency except the Google Fonts stylesheet loaded from the page head.

## Preview and deployment

```bash
python -m http.server 8000      # then open http://localhost:8000
```

The page can be served by any static host. For GitHub Pages, publish the repository root.

## Content notes

- The page gives no accuracy figures for the application's fine-tuned model; they will be added when the retrained
  adapter is available.
- Download links point to the releases of [oceanguard-app](https://github.com/asferrer/oceanguard-app).

## License

Page source: Apache License 2.0 (see `LICENSE`). The OceanGuard AI name and logo are not covered by that license.
Gemma weights are governed by the [Gemma Terms of Use](https://ai.google.dev/gemma/terms).

## Author

Alejandro Sánchez Ferrer, Universidad de Alicante.

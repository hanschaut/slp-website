# Schwarzlicht Photography — Website

Website des Fotografen Hannes (Marke „Schwarzlicht Photography").
Live unter https://schwarzlichtphotography.com

## Was ist das?

Eine handgeschriebene, statische HTML-Website. Es gibt keinen Build-Schritt –
die Dateien im Repo-Wurzelverzeichnis werden genau so ausgeliefert.

Die echten Seiten:

- `index.html` – Startseite
- `portfolio.html` – Portfolio/Galerie
- `kontakt.html` – Kontakt
- `impressum.html`, `datenschutz.html`, `agb.html` – Rechtliches
- `404.html` – Fehlerseite

Gestaltet mit [Tailwind CSS](https://tailwindcss.com) (über das CDN).
Bilder und sonstige Assets liegen im Ordner `public/`.

## Deployment

Gehostet auf **Cloudflare Pages**, verbunden mit diesem GitHub-Repo.
Jeder Push auf den Branch `main` veröffentlicht die Seite automatisch –
direkt aus dem Repo-Wurzelverzeichnis, ohne Build.

## Lokal ansehen

```sh
python3 -m http.server 8000
# → http://localhost:8000/index.html
```

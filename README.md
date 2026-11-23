# Schoonwerk – klikbare preview

Een klikbare demo van schoonmaakbeheersoftware: planning, klanten, opdrachten, checklists,
factuurontwerp, klantenportaal en medewerker-app. Alle gegevens zijn fictief.

Het is één bestand (`index.html`) zonder server of externe afhankelijkheden.

## Lokaal openen

Dubbelklik op `index.html`, of draai een kleine server:

```bash
python3 -m http.server 8000
```

Open daarna http://localhost:8000

## Via GitHub Pages

1. Maak op github.com een nieuwe repository (bijvoorbeeld `schoonwerk-preview`).
2. Push deze map (zie hieronder).
3. Ga naar **Settings → Pages**, kies bij *Source* **Deploy from a branch**, branch `main`, map `/ (root)`.
4. Na een minuut staat de demo op `https://<gebruikersnaam>.github.io/schoonwerk-preview/`.

```bash
git remote add origin https://github.com/<gebruikersnaam>/schoonwerk-preview.git
git push -u origin main
```

Let op: GitHub Pages werkt op een gratis account alleen bij een publieke repository.

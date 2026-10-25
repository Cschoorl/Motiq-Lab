# Mushin Lab – website

Statische website (HTML + één `style.css`, geen JavaScript, geen build-stap).

De stijl volgt het Mushin-Lab design system (brandguide v3): kleuren, letters (Quicksand als hoofdletter, Geist Mono voor data), afrondingen en componenten staan als tokens bovenaan `style.css`. Logo's staan in `assets/` (lockup en teken, licht en donker); `favicon.svg` is het app-icoon.

| Pagina | Bestand |
| --- | --- |
| Home | `index.html` |
| Research (overzicht van alle notes, met filter) | `research.html` |
| Aanpak (missie, principes, hypotheses, roadmap) | `aanpak.html` |
| Bronnen (alle 27 bronnen) | `bronnen.html` |
| Note 01 · Systeemontwerp | `hoe-het-werkt.html` |
| Note 02 · Marktanalyse | `markt.html` |
| Note 03 · Concurrentie | `concurrentie.html` |
| Note 04 · Onderzoeksplan MVP | `mvp.html` |
| Note 05 · Bouwen op LeRobot | `lerobot.html` |
| Note 06 · Veiligheid | `veiligheid.html` |
| Note 07 · Validatieplan | `validatie.html` |

## Contactadres invullen

Zoek in elk HTML-bestand naar `[jouw-e-mailadres]` (in de footer) en vervang de regel door bijvoorbeeld:

```html
<p><a href="mailto:naam@domein.nl">naam@domein.nl</a></p>
```

## Lokaal bekijken

Open `index.html` in je browser, of draai `python3 -m http.server` en ga naar http://localhost:8000.

## Online zetten (gratis)

- **GitHub Pages:** repo → Settings → Pages → Source: *Deploy from a branch* → branch `main`, map `/ (root)`. De site staat dan op `https://<gebruikersnaam>.github.io/<repo>/`.
- **Netlify:** ga naar app.netlify.com/drop en sleep deze map erin. Je krijgt direct een link.

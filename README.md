# Mushin lab – website

Statische website (HTML + één `style.css`, geen JavaScript, geen build-stap).

De stijl volgt het Mushin-Lab design system (brandguide v3): kleuren, letters (Quicksand als hoofdletter, Geist Mono voor data), afrondingen en componenten staan als tokens bovenaan `style.css`. Logo's staan in `assets/` (lockup en teken, licht en donker); `favicon.svg` is het app-icoon.

| Pagina | Bestand |
| --- | --- |
| Home | `index.html` |
| Research (overzicht van alle notes, met filter) | `research.html` |
| Aanpak (naam, missie en visie, principes, hypotheses, route naar de maan) | `aanpak.html` |
| Bronnen (alle 34 bronnen) | `bronnen.html` |
| Note 01 · Het probleem en de oplossing | `probleem.html` |
| Note 02 · Systeemontwerp | `hoe-het-werkt.html` |
| Note 03 · Architectuur: wat draait waar | `architectuur.html` |
| Note 04 · Onderzoeksplan MVP | `mvp.html` |
| Note 05 · Bouwen op LeRobot | `lerobot.html` |
| Note 06 · Veiligheid | `veiligheid.html` |
| Note 07 · Discipline rond de agent | `discipline.html` |
| Note 08 · Mogelijke eerste toepassing: lasersnijden | `markt.html` |
| Note 09 · Concurrentie | `concurrentie.html` |
| Note 10 · Markten wereldwijd | `markten.html` |
| Note 11 · Validatieplan | `validatie.html` |

De inhoud volgt het werkdocument "Robot Studio MVP-plan" (Mushin lab). De interne hoofdstukken (netwerk, cofounder zoeken, risico's) staan bewust niet op de site.

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

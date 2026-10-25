# Mushin Lab – website

Statische website (HTML + één `style.css`, geen JavaScript, geen build-stap). Logo: `logo.svg`, favicon: `favicon.svg`.

| Pagina | Bestand |
| --- | --- |
| Home | `index.html` |
| Hoe het werkt | `hoe-het-werkt.html` |
| Markt | `markt.html` |
| MVP | `mvp.html` |
| Research | `research.html` |

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

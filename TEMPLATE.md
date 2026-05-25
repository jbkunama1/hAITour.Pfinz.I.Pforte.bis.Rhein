# 🗺️ hAITour Template – Anleitung

Dieses Verzeichnis enthält ein wiederverwendbares Template für 3-Abschnitt-Fahrradtour-Dokumentationen auf GitHub Pages.

---

## 📂 Template-Dateien

```text
template/
├─ index.html   ← GitHub Pages Startseite (mit Platzhaltern)
└─ README.md    ← Projektbeschreibung (mit Platzhaltern)
```

---

## 🚀 Neue Tour erstellen – Schritt für Schritt

### 1. Neues GitHub-Repository anlegen

Erstelle ein neues Repo (z.B. `hAITour.OrtA.bis.OrtB`).

### 2. Template-Dateien kopieren

Kopiere `template/index.html` und `template/README.md` ins Root des neuen Repos.

### 3. Platzhalter ersetzen

Ersetze alle `{{PLACEHOLDER}}`-Variablen in beiden Dateien:

| Platzhalter          | Bedeutung                                      | Beispiel                          |
|----------------------|------------------------------------------------|-----------------------------------|
| `{{TOUR_TITLE}}`     | Name der Tour                                  | `hAITour: OrtA → OrtB`           |
| `{{TOUR_META_DESCRIPTION}}` | Meta-Beschreibung für SEO                | `Fahrradtour von OrtA nach OrtB`  |
| `{{TOUR_SUBTITLE}}`  | Kurzbeschreibung unter dem Titel               | `Von OrtA über OrtB bis OrtC`    |
| `{{TOUR_STATUS}}`    | Status-Badge-Text                              | `in tour` / `completed` / `planned` |
| `{{LOGO_FILE}}`      | Dateiname des Tour-Logos                       | `logo_MeineTour.png`             |
| `{{GITHUB_USER}}`    | GitHub-Benutzername                            | `jbkunama1`                      |
| `{{GITHUB_REPO}}`    | GitHub-Repository-Name                         | `hAITour.OrtA.bis.OrtB`         |
| `{{CHIP_ROUTE}}`     | Kurztext der Route im Header-Chip              | `OrtA → OrtB`                    |
| `{{CHIP_PHOTO_COUNT}}` | Geplante Bildanzahl im Header-Chip           | `10–15`                          |
| `{{OVERVIEW_TEXT}}`  | Überblick-Absatz                               | `Diese Tour führt von ...`        |
| `{{PART1_NAME}}`     | Name des 1. Abschnitts                         | `Start an der Pfinz`             |
| `{{PART1_EMOJI}}`    | Emoji für Abschnitt 1                          | `🌳`                              |
| `{{PART1_DESCRIPTION}}` | Kurzbeschreibung Abschnitt 1               | `Einrollen entlang der Pfinz`    |
| `{{PART1_MAPS_URL}}` | Google Maps Link Abschnitt 1                   | `https://maps.app.goo.gl/...`    |
| `{{PART2_NAME}}`     | Name des 2. Abschnitts                         | `Mittlerer Abschnitt`            |
| `{{PART2_EMOJI}}`    | Emoji für Abschnitt 2                          | `🏘️`                             |
| `{{PART2_DESCRIPTION}}` | Kurzbeschreibung Abschnitt 2               | `Verbindungsetappe mit Orten`    |
| `{{PART2_MAPS_URL}}` | Google Maps Link Abschnitt 2                   | `https://maps.app.goo.gl/...`    |
| `{{PART3_NAME}}`     | Name des 3. Abschnitts                         | `Finale bis zum Ziel`            |
| `{{PART3_EMOJI}}`    | Emoji für Abschnitt 3                          | `🌊`                             |
| `{{PART3_DESCRIPTION}}` | Kurzbeschreibung Abschnitt 3               | `Letzte Etappe bis zum Ziel`     |
| `{{PART3_MAPS_URL}}` | Google Maps Link Abschnitt 3                   | `https://maps.app.goo.gl/...`    |
| `{{GALLERY_COUNT}}`  | Anzahl geplanter Fotos                         | `10–15`                          |
| `{{GALLERY_01}}`–`{{GALLERY_05}}` | Beschriftungen der Galerie-Platzhalter | `Start an OrtA`         |

### 4. Logo hinzufügen

Erstelle oder exportiere ein Tour-Logo und lege es als `{{LOGO_FILE}}` ins Root des neuen Repos.

### 5. Bilder-Ordner anlegen

```text
images/
├─ teil1/
├─ teil2/
└─ teil3/
```

### 6. GitHub Pages aktivieren

Settings → Pages → Branch `main`, Root → Save.

Die Tour-Seite ist dann erreichbar unter:
`https://{{GITHUB_USER}}.github.io/{{GITHUB_REPO}}/`

---

## 💡 Tipps

- **Mehr als 3 Abschnitte?** Kopiere einfach ein `<article class="card">` in `index.html` und passe die Nummer an.
- **Echte Kartenbilder einbinden?** Ersetze `<div class="map-thumb">` durch `<img src="images/teilX/map_partX.png" ...>`.
- **Galerie mit echten Fotos?** Ersetze `<div class="placeholder-img">` durch `<img src="images/teilX/foto.jpg" ...>`.
- **Status nach der Tour ändern:** Badge-URL in `index.html` und `README.md` von `in%20tour` auf `completed` setzen.

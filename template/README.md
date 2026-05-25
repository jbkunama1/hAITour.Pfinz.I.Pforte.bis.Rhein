# {{TOUR_TITLE}} 🚴‍♂️

<p align="center">
  <!-- TODO: Logo-Datei ersetzen -->
  <img src="{{LOGO_FILE}}" alt="{{TOUR_TITLE}} Logo" width="220" />
</p>

![GitHub Pages](https://img.shields.io/badge/view%20on-GitHub%20Pages-blueviolet?style=for-the-badge)
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)
![Status](https://img.shields.io/badge/status-{{TOUR_STATUS}}-orange?style=for-the-badge)

> **Hybrid AI Tour** – {{TOUR_SUBTITLE}} 🤖🚴

---

## 🌍 Überblick

{{OVERVIEW_TEXT}}

Die Tour ist in drei Abschnitte aufgeteilt:

1. **Teil 1 – {{PART1_NAME}}**
   Route: [Google Maps Link]({{PART1_MAPS_URL}})
2. **Teil 2 – {{PART2_NAME}}**
   Route: [Google Maps Link]({{PART2_MAPS_URL}})
3. **Teil 3 – {{PART3_NAME}}**
   Route: [Google Maps Link]({{PART3_MAPS_URL}})

Die zugehörige GitHub Pages Seite (inkl. Karten-Ausschnitte und Bilder der Wegpunkte) wird in `index.html` bereitgestellt.

---

## 🗺️ Karten & Abschnitte

### Teil 1: {{PART1_NAME}}
- {{PART1_DESCRIPTION}}
- Route als Link: [Teil 1 auf Google Maps]({{PART1_MAPS_URL}})
- Geplanter Kartenausschnitt: Einbettung der Route als Screenshot / statische Karte in `index.html`

### Teil 2: {{PART2_NAME}}
- {{PART2_DESCRIPTION}}
- Route als Link: [Teil 2 auf Google Maps]({{PART2_MAPS_URL}})

### Teil 3: {{PART3_NAME}}
- {{PART3_DESCRIPTION}}
- Route als Link: [Teil 3 auf Google Maps]({{PART3_MAPS_URL}})

---

## 🖼️ Bilder & Medien

Geplant sind **{{GALLERY_COUNT}} Bilder** der einzelnen Wegpunkte:

- {{GALLERY_01}}
- {{GALLERY_02}}
- {{GALLERY_03}}
- {{GALLERY_04}}
- {{GALLERY_05}}

Strukturvorschlag für Bilder im Repo:

```text
📁 images/
 ├─ teil1/
 │   ├─ 01_start.jpg
 │   ├─ 02_wegpunkt.jpg
 ├─ teil2/
 │   ├─ 01_ort.jpg
 ├─ teil3/
 │   ├─ 01_ziel.jpg
 │   ├─ 02_panorama.jpg
```

Diese Bilder werden später in `index.html` als Galerie eingebunden.

---

## 🧱 Projektstruktur

```text
{{GITHUB_REPO}}/
├─ README.md                  ← diese Datei
├─ index.html                 ← GitHub Pages Startseite
├─ LICENSE                    ← MIT Lizenz
├─ {{LOGO_FILE}}              ← Tour-Logo
├─ images/                    ← Bilder der Tour (Wegpunkte, Panorama, etc.)
└─ docs/                      ← optionale zusätzliche Dokumente (z.B. GPX, Banner)
```

---

## 🚀 GitHub Pages

Die Seite wird über **GitHub Pages** veröffentlicht.

- Branch: `main`
- Seite: `index.html`
- URL (nach Aktivierung von Pages, Standard):
  `https://{{GITHUB_USER}}.github.io/{{GITHUB_REPO}}/`

Du kannst sie in den **Repository Settings → Pages** aktivieren.

---

## 📌 Todo-Liste

- [ ] GitHub Pages aktivieren
- [ ] Kartenausschnitte (Screenshots) der drei Teile hinzufügen
- [ ] {{GALLERY_COUNT}} Bilder der Wegpunkte in `images/` hochladen
- [ ] Bilder-Galerie in `index.html` vervollständigen
- [ ] Optional: GPX/KML-Dateien der Route ergänzen

---

## 📄 Lizenz

Dieses Projekt steht unter der **MIT-Lizenz**. Details siehe [`LICENSE`](LICENSE).

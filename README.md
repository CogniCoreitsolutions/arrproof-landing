# ARRproof Landingpage

Statische Landingpage für ARRproof, eine Beratungsleistung der CogniCore IT Solutions GmbH.

- `index.html` Startseite, `fakten/index.html` Faktenseite (Grounding-Seite nach dem Muster von docu.cognicore.de/fakten, mit schema.org-Daten und FAQ). Beide mit eingebettetem CSS, keine Build-Schritte. Schrift Red Hat über Google Fonts, Designsprache wie die ARRproof-App.
- Englisch: `en/index.html` und `en/facts/index.html` (gleicher Aufbau). Schalter DE/EN in der Leiste ganz oben. Ein Skript im `<head>` jeder Seite wählt beim Einstieg die Sprache: gespeicherte Wahl (`localStorage` `arrproof-lang`, gesetzt beim Klick auf den Schalter), sonst die primäre Browsersprache (`de…` = Deutsch, sonst Englisch). Klicks innerhalb der Seite leiten nicht um. `hreflang` de, en, x-default = en.
- Checkliste: `checkliste/index.html` und `en/checklist/index.html`, 27 Fragen aus den Prüfregeln, abhakbar und druckbar, ohne Formular.
- Logo: freigegebenes Logo-Paket unter `brand/arrproof/` (`svg/`, `png/`, Favicons, Icons; Quelle `ARRproof-Logo-Dateien.zip`, Entwurf v2). Kopfzeile aller Seiten mit `brand/arrproof/svg/arrproof-logo.svg`, auf dunklen Flächen `arrproof-logo-dark.svg`. Favicons `brand/arrproof/svg/favicon.svg`, `favicon.ico`, `apple-touch-icon.png`; die Root-Favicons sind Kopien aus dem Paket. Logos nicht neu zeichnen, umfärben oder strecken. `assets/arrproof-mark*` ist der alte Nachbau und wird nicht mehr verwendet.
- `img/app-herkunft.webp` Bildschirmfoto der App (synthetischer Testdatensatz), `img/dominik-siegers.webp` Porträt von inqa-nrw.de.
- `img/` enthält außerdem Bilder der ersten Fassung, derzeit nicht eingebunden. `assets/` außerdem Schrift und CogniCore-Logo der ersten Fassung, nicht mehr eingebunden.

Veröffentlicht über GitHub Pages aus dem Branch `main` unter https://arrproof.com. Die Seiten sind mit `noindex` markiert, bis Name, Marke und Angebot geklärt sind.

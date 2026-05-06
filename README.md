# Schöneweider KiezKarte — Landing Page

Single-file HTML-Landingpage für die Schöneweider KiezKarte. Mobile-first, im Stil des Mitmach-Flyers.

## Dateien in diesem Ordner

| Datei | Beschreibung |
|---|---|
| `index.html` | Die Landingpage. Komplett selbstständig, keine externen Abhängigkeiten. |
| `kiezkarte.png` | Das Karten-Mockup mit Kaisersteg-Silhouette (Aufmacher-Bild). |
| `industriesalon_logo.png` | Industriesalon-Logo (transparent). |
| `werk116_logo.png` | WERK 116-Logo (transparent). |
| `README.md` | Diese Datei. |

## Lokal anschauen

`index.html` einfach im Browser öffnen — Doppelklick reicht. Funktioniert ohne Server.

## Auf GitHub Pages veröffentlichen

### Variante A: Neues Repository unter dem Industriesalon-Account

1. Auf **github.com** anmelden mit dem Industriesalon-Account.
2. Oben rechts auf **„+" → „New repository"** klicken.
3. Repository-Name: `kiezkarte` (oder `schoeneweider-kiezkarte`).
4. **Public** auswählen, **„Add a README file"** ankreuzen, dann **„Create repository"**.
5. Auf der Repo-Seite auf **„Add file" → „Upload files"** klicken.
6. Alle vier Dateien aus diesem Ordner hochladen (`index.html`, `kiezkarte.png`, `industriesalon_logo.png`, `werk116_logo.png`) — den `README.md` kann man auch mitnehmen oder weglassen.
7. **„Commit changes"** drücken.
8. Im Repo zu **„Settings" → „Pages"** wechseln.
9. Bei **„Source"** den Branch `main` wählen, Ordner `/ (root)`, dann **„Save"**.
10. Nach 1–2 Minuten ist die Seite online unter:

   ```
   https://industriesalon.github.io/kiezkarte/
   ```

   (Der Account-Name in der URL hängt davon ab, unter welchem GitHub-Account das Repo angelegt wurde.)

### Variante B: In bestehendes Repository einfügen

Wenn schon ein Repository wie `futura-biennale.github.io` oder ähnlich existiert: Einfach einen Unterordner `kiezkarte/` anlegen und die vier Dateien dort hochladen. Die Seite ist dann erreichbar unter:

```
https://<account>.github.io/<repo>/kiezkarte/
```

## Anpassungen

### Inhalt ändern

Alle Texte stehen direkt in `index.html` — kein CMS, keine Templating-Sprache. Mit jedem Texteditor öffnen, ändern, speichern.

### Design ändern

Alle Farben, Schriftgrößen und Abstände stehen am Anfang von `index.html` im `<style>`-Block. Wichtige CSS-Variablen (in `:root`):

- `--ink: #1A1A1A` — Hauptschriftfarbe
- `--cream: #FAF7F2` — Hintergrund
- `--red: #D72E1F` — Industriesalon-Rot, Akzentfarbe
- `--maxw: 1080px` — Maximale Inhaltsbreite

### Anmelde-Link ändern

Der Knopf „Jetzt anmelden" und der Top-Bar-Link „Mitmachen" zeigen aktuell auf `https://www.werk116.de/mwk-tn`. Wenn sich der URL ändert, an zwei Stellen suchen und ersetzen.

## Hinweise zur Performance

Die Landingpage hat keine externen Skripte, keine Tracking-Pixel, keine Drittanbieter-Schriften. Alle Schriften sind Systemschriften (Apple, Windows, Linux nutzen jeweils ihre Standard-Sans-Serif). Lädt schnell auch über Mobilfunk.

## Letzte Aktualisierung

- v1, Mai 2026 — initiale Version basierend auf Mitmach-Flyer v18

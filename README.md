# Dein Wasserverbrauch – Web-Version

Interaktive Simulation zum Wasserfußabdruck im Alltag (Hornmoldhaus).
Dieser Ordner ist fertig für **GitHub Pages** vorbereitet.

## Inhalt

```
index.html            Spiel (Web-Version)
.nojekyll             sorgt dafür, dass GitHub alle Dateien unverändert ausliefert
images/               16 Hintergrundbilder
audio/                8 Sprachaufnahmen
lib/jspdf.umd.min.js  PDF-Erzeugung für „Liste als PDF speichern“
```

## Veröffentlichen auf GitHub Pages

1. Auf github.com anmelden → **New repository** → Name z. B. `wasserverbrauch`, **Public** → *Create repository*.
2. Auf „uploading an existing file“ klicken und den **Inhalt** dieses Ordners
   (nicht den Ordner selbst) ins Browserfenster ziehen. Die Unterordner bleiben erhalten.
   → *Commit changes*.
   Hinweis: Die Datei `.nojekyll` ist unter Windows evtl. ausgeblendet – sie ist nicht zwingend nötig.
3. **Settings → Pages** → Source: *Deploy from a branch* → Branch `main`, Ordner `/ (root)` → *Save*.
4. Nach 1–2 Minuten ist das Spiel erreichbar unter
   `https://<BENUTZERNAME>.github.io/wasserverbrauch/`

## In Google Sites einbetten

1. Google Site bearbeiten → rechts **Einfügen → Einbetten** → Tab **Per URL**.
2. GitHub-Pages-Adresse einfügen → *Gesamte Seite* → *Einfügen*.
3. Rahmen groß ziehen (am besten volle Breite, Format 16:9) → **Veröffentlichen**.

## Unterschiede zur Kiosk-Version (`game.html`)

- Audiodatei `END_E.mp3` wird jetzt mit korrekter Groß-/Kleinschreibung geladen
  (Webserver unterscheiden das, Windows nicht).
- Kein automatischer Rücksprung zum Titelbild nach 3 Minuten (nur noch im Kiosk aktiv).
- Neue Buttons in der Seitenleiste: **Vollbild** und – wenn eingebettet –
  **In neuem Tab öffnen** (praktisch auf dem Handy oder falls der PDF-Download im Rahmen blockiert wird).
- Bilder werden beim Start vorgeladen, damit Szenenwechsel ohne Verzögerung klappen.

## Änderungen später

Datei im Repository ersetzen (Add file → Upload files) – die Google Site zeigt automatisch die neue Version.

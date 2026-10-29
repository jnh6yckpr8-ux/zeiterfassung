# Zeiterfassung Schleswig-Holstein

Gleitzeit-Saldo, Urlaub, Krank und Überstundenabbau erfassen – mit den gesetzlichen Feiertagen in Schleswig-Holstein. Eine einzelne HTML-Seite ohne Server, ohne Konto, ohne Tracking.

**App öffnen:** `https://<dein-benutzername>.github.io/zeiterfassung/`

## Dateien

| Datei | Zweck |
|---|---|
| `index.html` | Die App |
| `anleitung.html` | Installationsanleitung (iPhone / Mac) |
| `manifest.webmanifest`, `*.png` | Symbol und Name für den Home-Bildschirm |

## Datenschutz

Die erfassten Zeiten liegen **nur im Browser des jeweiligen Geräts** (localStorage) bzw. in der eigenen `Zeiterfassung.json` in iCloud Drive. Auf GitHub liegt ausschließlich der Programmcode. `.gitignore` verhindert, dass versehentlich eine `.json` mit Zeitdaten hochgeladen wird.

## iPhone

1. Die App-Adresse in **Safari** öffnen.
2. Teilen ↑ → „Zum Home-Bildschirm“ → Hinzufügen.
3. Die App **vom Home-Bildschirm** starten und unter „iCloud-Synchronisation“ einmal **Laden ↓** → `Zeiterfassung.json` aus iCloud Drive wählen.

Abgleich mit dem Mac: nach dem Erfassen **Sichern ↑** → „In Dateien sichern“ → iCloud Drive (vorhandene Datei ersetzen). Vor dem Arbeiten auf dem anderen Gerät **Laden ↓**.

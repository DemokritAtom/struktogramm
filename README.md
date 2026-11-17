# Struktogramm-Editor

Browser-Editor für Struktogramme nach DIN 66261.

**Live:** https://demokritatom.github.io/struktogramm/

- Läuft komplett im Browser, nichts wird hochgeladen, keine Installation nötig.
- Der aktuelle Stand wird automatisch im Browser gespeichert (`localStorage`).
- Export als **PDF**, **Word (.docx)**, **SVG** und **PNG**.
- Speichern/Öffnen als `.nsd.json` zum Weiterbearbeiten.
- Fürs Handy optimiert und als **App installierbar (PWA)**, läuft dann auch offline.

## Updates

`index.html` ändern, committen, pushen. Wenn sich Icons oder andere Dateien ändern, in `sw.js` die `VERSION` hochzählen, damit installierte Apps die neuen Dateien laden.

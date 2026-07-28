# CWT v0.1.0

Erste lauffähige Foundation der CWT Golf-Clash-Begleit-App.

## Ordnerstruktur

```text
CWT_v0.1.0/
├── index.html
├── manifest.webmanifest
├── service-worker.js
├── css/
│   └── app.css
├── js/
│   ├── app.js
│   ├── data.js
│   └── storage.js
├── assets/
│   └── icons/
├── data/
└── docs/
    └── PROJECT_BOOK.md
```

## Lokal testen

Ein Service Worker funktioniert nur über HTTP/HTTPS, nicht direkt über `file://`.

Mit Python:

```bash
python3 -m http.server 8080
```

Danach im Browser öffnen:

```text
http://localhost:8080
```

## GitHub Pages

Alle Dateien in das Stammverzeichnis des Repositorys hochladen und unter **Settings → Pages** den Branch `main` sowie `/root` auswählen.

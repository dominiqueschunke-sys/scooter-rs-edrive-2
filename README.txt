# Scooter RS e-Drive Web-App

## Auf dem iPhone 15 Pro öffnen
1. Lade die ZIP-Datei herunter und entpacke sie auf einem Computer oder in einer Datei-App, die ZIP-Archive öffnen kann.
2. Um sie als installierbare Home-Screen-Web-App zu nutzen, veröffentliche die enthaltenen Dateien auf einem statischen HTTPS-Host (z. B. GitHub Pages oder Netlify).
3. Öffne die HTTPS-Adresse in Safari → Teilen → „Zum Home-Bildschirm“.

Ein lokales HTML-Dokument kann direkt in Safari getestet werden, aber Offline-/PWA-Funktionen benötigen in der Regel HTTPS oder localhost.

## Grenzen
Dies ist eine funktionierende UI-Demo. Live-Scooter-Daten, GPS-Track/Karte und Hardwaresteuerung sind nicht implementiert. iOS Safari unterstützt Web Bluetooth nicht allgemein; echte Bluetooth-Steuerung benötigt eine native iOS-App oder einen anderen expliziten Vermittlungsweg. Tuning-Regler sind reine Vorschau und senden keine Befehle.

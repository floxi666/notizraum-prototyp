# Notizraum – Version 0.1

Dies ist ein erster mobiler Web-App-Prototyp für iPhone.

## Enthalten
- Begrüßung, Name, Datum und täglicher Spruch
- Startseite mit Neue-Notiz- und Kalenderbereich
- Notizen mit Text und abhaktbaren Listenpunkten
- Bis zu fünf geöffnete Notiz-Tabs
- Suche über Notiztitel, Text und Listenpunkte
- Wochenkalender mit Montag bis Sonntag und seitlichen Notizfeldern
- Schriftgröße, Icon-Größe und Hell-/Dunkelmodus
- Lokale Speicherung im Browser
- Backup-Export und -Import als JSON-Datei
- Cloud-Anbieter nur als deaktivierte Platzhalter

## Wichtig zur Datenspeicherung
Die App verwendet localStorage im Browser. Die Daten verbleiben im Browserprofil dieses Geräts und werden nicht an einen Server gesendet.
Das ist ein Prototyp, keine fertige native iOS-App. Browserdaten können verloren gehen, etwa wenn Safari-Daten gelöscht werden. Exportiere deshalb regelmäßig ein Backup.

## Testen auf dem iPhone
1. Entpacke die ZIP-Datei.
2. Für einen einfachen ersten Blick kannst du `index.html` in einer Vorschau öffnen. Das ist aber nicht der zuverlässigste Weg für dauerhafte Datenspeicherung.
3. Für eine echte Installation auf dem Home-Bildschirm muss die Datei über eine HTTPS-Adresse bereitgestellt werden.
4. Öffne die HTTPS-Adresse in Safari.
5. Tippe auf „Teilen“ und dann „Zum Home-Bildschirm“.
6. Starte die App über das neue Symbol.

Für eine echte Offline-PWA wird zusätzlich eine Web-App-Manifestdatei und ein Service Worker benötigt. Diese erste Version ist bewusst als einzelner HTML-Prototyp gehalten, damit sie leicht geprüft und verändert werden kann.

## Nächste Ausbaustufen
- PWA-Manifest und Service Worker
- lokale Datenbank (IndexedDB/SQLite je nach Zielplattform)
- robuste Backup-Rotation (z. B. maximal 10 Sicherungsstände)
- Bildzuschnitt, eigene Icons und GIF-Unterstützung
- native iOS-/Android-Verpackung
- optionale Cloud-Synchronisierung

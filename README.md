# Workout – iPhone Web-App

## Funktionen
- Wochenübersicht von Montag bis Sonntag mit Tagesnotizen und Trainingstyp
- Übungen erstellen, bearbeiten und löschen
- Satz-Tracking mit Wiederholungen und Gewicht pro Satz
- Fünf Fortschrittskategorien mit Wochenzielen
- Trainingsserie und Aktivitätsverlauf
- Hell-/Dunkelmodus
- Lokale Speicherung auf dem Gerät
- Daten als JSON exportieren und importieren
- Offline-Unterstützung als PWA

## Auf dem iPhone installieren
1. Lade den Ordner auf einen Webhost (z. B. GitHub Pages) hoch oder öffne die Seite über einen HTTPS-Webserver.
2. Öffne die Web-Adresse in Safari.
3. Tippe auf **Teilen** → **Zum Home-Bildschirm** → **Hinzufügen**.
4. Starte Workout über das neue Symbol auf deinem Home-Bildschirm.

Die Trainingsdaten bleiben im lokalen Speicher des jeweiligen Browsers/Geräts. Nutze unter **Fortschritt → Daten exportieren** regelmäßig ein Backup.

## Lokal testen
Im Projektordner einen lokalen Webserver starten, z. B.:

```bash
python3 -m http.server 8000
```

Dann `http://localhost:8000` öffnen. Für PWA-Installation und Offline-Funktionen wird HTTPS benötigt (localhost ist zum Testen ebenfalls erlaubt).

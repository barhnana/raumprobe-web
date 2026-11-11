# Raumprobe

Grundriss hochladen, Räume zeichnen und Möbel maßstabsgetreu in 3D im Raum platzieren. Läuft komplett im Browser: kein Konto, kein Server, hochgeladene Grundrisse verlassen das Gerät nicht.

## Ausprobieren

**https://barhnana.github.io/raumprobe-web/**

## Funktionen

- Grundriss als Bild oder PDF hochladen (TIFF und HEIC werden ebenfalls unterstützt)
- Maßstab einmessen: bekannte Strecke im Plan anklicken und echte Länge angeben
- Räume, einzelne Wände, Türen und Fenster zeichnen
- Möbel anlegen mit Maßen, Farbe, Höhe und Rotation, inklusive eigenem Produktbild
- 2D-Grundriss und 3D-Ansicht des eingerichteten Raums
- Automatisches Speichern im Browser, ohne Konto
- Design per Link teilen, ohne Dateien zu verschicken
- Projekt als JSON-Datei exportieren und wieder importieren
- Helle und dunkle Oberfläche

## Nutzung

1. Grundriss hochladen.
2. Maßstab über eine bekannte Strecke im Plan einmessen.
3. Räume zeichnen oder Wände setzen, Türen und Fenster einfügen.
4. Möbel anlegen, in 2D platzieren, in 3D prüfen.

## Speichern und Teilen

- **Speichern:** Jede Änderung wird automatisch in diesem Browser auf diesem Gerät gespeichert, samt Grundrissbild und Produktbildern. Wer die Browserdaten löscht oder ein privates Fenster nutzt, verliert den Stand.
- **Sichern:** **Exportieren** schreibt das ganze Projekt in eine Datei, **Importieren** lädt sie wieder, auch auf einem anderen Gerät.
- **Teilen:** **Link teilen** erzeugt einen Link, der Räume, Wände, Türen, Fenster und Möbel enthält. Wer ihn öffnet, bekommt eine eigene Kopie. Bilder sind nicht enthalten, spätere Änderungen kommen nicht mit. Die Daten stehen in der Adresse selbst und werden nirgends hochgeladen.

## Selbst hosten

`index.html` ist eine einzelne, eigenständige Datei: herunterladen, im Browser öffnen, fertig. Für dauerhaften Betrieb dieses Repository forken und GitHub Pages aktivieren (Settings → Pages → Branch `main`).

## Technik

Eine HTML-Datei mit Vanilla JavaScript; three.js sowie TIFF- und HEIC-Unterstützung werden per CDN geladen. Kein Backend, keine Datenbank, keine Tracking-Dienste.

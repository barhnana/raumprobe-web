# Raumprobe

Grundriss hochladen, Räume zeichnen und Möbel maßstabsgetreu in 3D im Raum platzieren. Läuft komplett im Browser: kein Konto, kein Server, hochgeladene Grundrisse verlassen das Gerät nicht.

## Ausprobieren

**https://barhnana.github.io/raumprobe-web/**

(aktiv nach einmaliger Aktivierung von GitHub Pages, siehe unten)

## Funktionen

- Grundriss als Bild oder PDF hochladen (TIFF und HEIC werden ebenfalls unterstützt)
- Maßstab einmessen: bekannte Strecke im Plan anklicken und echte Länge angeben
- Räume, einzelne Wände, Türen und Fenster zeichnen
- Möbel anlegen mit Maßen, Farbe, Höhe und Rotation, inklusive eigenem Produktbild
- 2D-Grundriss und 3D-Ansicht des eingerichteten Raums
- Projekt als JSON-Datei exportieren und wieder importieren
- Helle und dunkle Oberfläche

## Nutzung

1. Grundriss hochladen.
2. Maßstab über eine bekannte Strecke im Plan einmessen.
3. Räume zeichnen oder Wände setzen, Türen und Fenster einfügen.
4. Möbel anlegen, in 2D platzieren, in 3D prüfen.

Der aktuelle Stand wird im Browser nicht dauerhaft gespeichert. Über **Exportieren** lässt sich das Projekt jederzeit als Datei sichern und mit **Importieren** wiederherstellen.

## Selbst hosten

`index.html` ist eine einzelne, eigenständige Datei: herunterladen, im Browser öffnen, fertig. Für dauerhaften Betrieb dieses Repository forken und GitHub Pages aktivieren (Settings → Pages → Branch `main`).

## Technik

Eine HTML-Datei mit Vanilla JavaScript; three.js sowie TIFF- und HEIC-Unterstützung werden per CDN geladen. Kein Backend, keine Datenbank, keine Tracking-Dienste.

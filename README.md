
<img width="256" height="256" alt="icon_256x256 1" src="https://github.com/user-attachments/assets/376ff8f3-cddf-479c-8949-4adf94007a95" />

# Shuno

Ein nativer, schlanker Clipboard-Manager für macOS. Merkt sich kopierte Texte, Links, Bilder, Code und Dateien in einem übersichtlichen Fenster und ist zusätzlich über eine Menüleisten-Kurzliste jederzeit griffbereit.

## Systemanforderungen

- Mac mit Apple Silicon (M1 oder neuer) — Intel-Macs werden NICHT unterstützt
- macOS 26 (Tahoe) oder neuer

## Funktionen

### Oberfläche
- Seitenleiste mit Kategorien: Alle, Text, Links, Bilder, Code, Favoriten, Verbergen, Papierkorb
- Kategorien werden automatisch erkannt und farblich unterschieden (auch kopierter Quellcode)
- Vorschau-Button für Bilder und lange Texte in voller Größe
- Folgt automatisch der Systemeinstellung (hell/dunkel)

### Dateien einfügen
- Kopierte Dateien (Bilder, Dokumente, Code-Dateien) lassen sich später wieder überall einfügen — als echte Datei oder als reine Bilddaten, je nachdem was die Ziel-App erwartet
- Läuft über einen reinen Pfad-Verweis statt einer Kopie, damit kein zusätzlicher Speicherplatz verbraucht wird

### Datenschutz
- Einträge lassen sich per Schloss-Symbol verstecken — erst nach Touch ID oder Mac-Passwort wieder sichtbar
- Der komplette Verlauf (Text, Bilder, Dateien) ist AES-256-verschlüsselt auf der Festplatte gespeichert, inklusive Live-Test-Button in den Einstellungen, der das direkt nachweist
- Der "Verbergen"-Reiter lässt sich in den Einstellungen optional komplett aus der Seitenleiste ausblenden

### Papierkorb
- Gelöschte Einträge landen erst im Papierkorb (ebenfalls Touch-ID-gesichert) und lassen sich wiederherstellen
- Nach 30 Tagen automatische, endgültige Löschung

### Aufräumen
- Alte Einträge lassen sich nach einer frei wählbaren Anzahl Stunden oder Tage automatisch löschen — Favoriten und angepinnte Einträge bleiben davon immer ausgenommen
- Eigener Button, um verwaiste Dateireste im Speicherordner aufzuräumen

### Backup
- Optionales, verschlüsseltes iCloud-Backup (Einstellungen → iCloud) — schützt den Verlauf, falls der Mac mal kaputt geht oder ersetzt wird

### Updates
- Automatische Update-Prüfung mit einstellbarem Intervall
- Updates können vollautomatisch heruntergeladen, installiert und neu gestartet werden — mit Bestätigungsdialog vor dem Schließen der App
- Nach einem Update erscheint einmalig ein kleines Banner mit den wichtigsten Änderungen

### Sonstiges
- Menüleisten-Kurzliste: die letzten oder manuell angepinnten Einträge direkt kopieren, ohne das Fenster zu öffnen
- Favoriten markieren und schnell wiederfinden
- Mehrfachauswahl per Shift-Klick, Escape zum schnellen Abbrechen
- Link-Vorschau (optional): zeigt Titel und Favicon zu kopierten Links
- Feedback-Formular direkt in den Einstellungen
- Willkommensbildschirm mit kurzem Tutorial (Einstellungen → Allgemein → jederzeit erneut aufrufbar)
- "Shuno vollständig deinstallieren" in den Einstellungen, falls man wirklich alle Daten (lokal + iCloud + Schlüsselbund) loswerden möchte

## Installation

1. Neueste Version unter [Releases](../../releases) herunterladen
2. Shuno.dmg öffnen
3. Shuno.app in den Programme-Ordner ziehen (nicht im Downloads-Ordner liegen lassen)
4. Rechtsklick auf Shuno.app → Öffnen (nur beim ersten Start nötig)

## Warnhinweis beim ersten Start

macOS zeigt beim ersten Öffnen die Meldung "Apple konnte nicht überprüfen, ob 'shuno' frei von Schadsoftware ist". Das ist normal und liegt daran, dass die App nicht mit einem kostenpflichtigen Apple Developer-Zertifikat signiert ist — kein echtes Sicherheitsproblem.

So lässt sich das umgehen:
1. Mit der rechten Maustaste auf shuno.app klicken → "Öffnen" auswählen
2. Falls dort kein "Trotzdem öffnen"-Button erscheint: Systemeinstellungen → Datenschutz & Sicherheit → nach unten scrollen → "Trotzdem öffnen" klicken

Das ist bei jeder neu installierten Version erneut nötig, da Shuno kein bezahltes Zertifikat hat — auch beim automatischen Update.

## Datenschutz im Detail

Alle kopierten Inhalte werden ausschließlich lokal (oder optional in deiner privaten iCloud) gespeichert, niemals an einen eigenen Server geschickt. Der komplette Verlauf liegt AES-256-verschlüsselt vor; der Schlüssel dazu liegt im macOS-Schlüsselbund, nicht in der Verlaufsdatei selbst.

Drei optionale Funktionen kontaktieren das Internet, nur wenn aktiv eingeschaltet oder ausgelöst: die Link-Vorschau (ruft die jeweilige Webseite auf, um Titel/Favicon zu laden), die Update-Prüfung (fragt eine kleine Textdatei ab, um auf neue Versionen hinzuweisen) und das Feedback-Formular (sendet deine Nachricht an einen externen Formular-Dienst). Keines davon sendet persönliche Daten ohne dein aktives Zutun.

## Haftungsausschluss

Dies ist ein privates Hobby-Projekt, kostenlos und ohne Gewinnabsicht bereitgestellt. Die Nutzung erfolgt auf eigene Verantwortung. Es wird keine Haftung für Datenverlust, Fehlfunktionen oder Schäden jeglicher Art übernommen, die durch die Nutzung dieser Software entstehen könnten. Es besteht kein Anspruch auf Support, Updates oder Fehlerbehebung.

## Hinweis

Diese App wurde mit Liebe und mit der Unterstützung von Claude (Anthropic) entwickelt.


## App Screenshot

<img width="1272" height="889" alt="Bildschirmfoto 2026-09-03 um 23 43 01" src="https://github.com/user-attachments/assets/1da9df7e-75ea-4a6e-8a35-9f16357d0866" />




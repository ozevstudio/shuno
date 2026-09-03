
<img width="256" height="256" alt="icon_256x256 1" src="https://github.com/user-attachments/assets/376ff8f3-cddf-479c-8949-4adf94007a95" />

# Shuno

Ein nativer, schlanker Clipboard-Manager für macOS. Merkt sich kopierte Texte, Links, Bilder und Code in einem übersichtlichen Fenster und ist zusätzlich über eine Menüleisten-Kurzliste jederzeit griffbereit.

## Systemanforderungen

- Mac mit Apple Silicon (M1 oder neuer) — Intel-Macs werden NICHT unterstützt
- macOS 26 (Tahoe) oder neuer

## Funktionen

### Oberfläche
- Seitenleiste mit Kategorien: Alle, Text, Links, Bilder, Code, Favoriten, Verbergen
- Kategorien werden automatisch erkannt und farblich unterschieden
- Vorschau-Button für Bilder und lange Texte in voller Größe

### Datenschutz
- Einträge lassen sich per Schloss-Symbol verstecken — erst nach Touch ID oder Mac-Passwort wieder sichtbar
- Der komplette Verlauf (Text **und** Bilder) ist verschlüsselt auf der Festplatte gespeichert, nicht nur in der App-Ansicht gefiltert
- Der "Verbergen"-Reiter lässt sich in den Einstellungen optional komplett aus der Seitenleiste ausblenden

### Backup
- Optionales, iCloud-Backup (Einstellungen → iCloud) — schützt den Verlauf, falls der Mac mal kaputt geht oder ersetzt wird

### Sonstiges
- Menüleisten-Kurzliste: die letzten oder manuell angepinnten Einträge direkt kopieren, ohne das Fenster zu öffnen
- Favoriten markieren und schnell wiederfinden
- Mehrfachauswahl per Shift-Klick, Escape zum schnellen Abbrechen
- Link-Vorschau (optional): zeigt Titel und Favicon zu kopierten Links
- Automatische Update-Prüfung mit einstellbarem Intervall
- Willkommensbildschirm mit kurzem Tutorial (Einstellungen → Allgemein → jederzeit erneut aufrufbar)

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

Das ist nur beim allerersten Start nötig.

## Datenschutz im Detail

Alle kopierten Inhalte werden ausschließlich lokal (oder optional in deiner privaten iCloud) gespeichert, niemals an einen eigenen Server geschickt. Der komplette Verlauf liegt AES-256-verschlüsselt vor; der Schlüssel dazu liegt im macOS-Schlüsselbund, nicht in der Verlaufsdatei selbst.

Zwei optionale Funktionen kontaktieren das Internet, nur wenn aktiv eingeschaltet: die Link-Vorschau (ruft die jeweilige Webseite auf, um Titel/Favicon zu laden) und die Update-Prüfung (fragt eine kleine Textdatei ab, um auf neue Versionen hinzuweisen). Beide senden keine persönlichen Daten.

## Haftungsausschluss

Dies ist ein privates Hobby-Projekt, kostenlos und ohne Gewinnabsicht bereitgestellt. Die Nutzung erfolgt auf eigene Verantwortung. Es wird keine Haftung für Datenverlust, Fehlfunktionen oder Schäden jeglicher Art übernommen, die durch die Nutzung dieser Software entstehen könnten. Es besteht kein Anspruch auf Support, Updates oder Fehlerbehebung.

## Hinweis

Diese App wurde mit Unterstützung von Claude (Anthropic) entwickelt.

## App Screenshot

<img width="1012" height="584" alt="Bildschirmfoto 2026-09-02 um 21 45 56" src="https://github.com/user-attachments/assets/04541d22-08c6-42ce-ba4d-f5ad8af05330" />



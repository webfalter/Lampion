# Lampion
<img src="img/AppIcon.png" alt="Screenshot" width="130" align="right">

Native macOS-App, die deinen lokalen Web-Stack (Apache, MySQL, PHP) zum Leuchten bringt, Apache, MySQL und PHP verwalten, PHP-Version wechseln und Datenbanken sichern.
Läuft auf **Apple Silicon und Intel** (Universal-Binary).

## Voraussetzungen

- macOS 15 Sequoia oder neuer (Liquid-Glass-Optik ab macOS 26 Tahoe) und Xcode 26
- Homebrew (`/opt/homebrew` auf Apple Silicon, `/usr/local` auf Intel – wird automatisch erkannt)

## Starten
Beim ersten Start bietet Lampion an, sich selbst in den Programme-Ordner zu verschieben (über das Package [MoveToApplications](https://github.com/webfalter/MoveToApplications)).

Einstellungen (⌘,) → MySQL-Benutzer und Passwort eintragen. Das Passwort landet im Schlüsselbund.

## Funktionen

| Bereich | Inhalt |
|---|---|
| Übersicht | Live-Status aller Dienste, Alles starten / stoppen, Einzelsteuerung, Websites aus deinen VirtualHosts (inkl. HTTPS/Port), Schnellzugriff |
| PHP | Installierte Versionen, Wechsel per Klick, fehlende Versionen installieren, php.ini öffnen |
| Datenbanken | Datenbankliste, Sicherung aller DBs, Sicherungen wiederherstellen, löschen, im Finder zeigen |
| Konfiguration | httpd.conf, vhosts, php.ini, Fehlerprotokoll, `apachectl -t`, /etc/hosts-Editor |
| Einrichtung | Fehlendes installieren (Apache, MySQL, PHP 8.2–8.5, phpMyAdmin), alles aktualisieren |
| Protokoll | Ausgabe aller Befehle, kopierbar |
| Menüleiste | Status, Starten/Stoppen, PHP wechseln, Websites, Sichern – auch bei geschlossenem Fenster |


## Lizenz und Urheberrecht / License

© 2026 webfalter. Alle Rechte vorbehalten. / All rights reserved.

Dieses Repository dient ausschließlich der **Präsentation des Projekts und der Bereitstellung vorkompilierter App-Releases**. Der Quellcode der App ist proprietär. 

- Es ist **nicht gestattet**, die App, Grafiken, Texte oder Bestandteile dieses Repositories ohne explizite schriftliche Genehmigung zu kopieren, zu modifizieren, zu forken oder für eigene kommerzielle sowie nicht-kommerzielle Zwecke zu verbreiten.
- Die bereitgestellten App-Binaries dürfen ausschließlich zur persönlichen Nutzung für die lokale Entwicklung verwendet werden.

*This repository is for demonstration and binary distribution purposes only. The underlying source code is proprietary. Redistribution, modification, or commercial use of any assets or binaries within this repository without prior written permission is strictly prohibited.*


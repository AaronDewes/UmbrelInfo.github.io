---
layout: default
title: FAQ
nav_order: 20
---
# Häufig gestellte Fragen
{: .no_toc }

Verschiedene Fragen und weitere Informationen zu der in Umbrel eingestzten Technologie.

Fragen zur den spezifischeren Umbrel-Funktionen werden auf einer [Troubleshooting-Seite](troubleshooting.md) beantwortet.

## Inhaltsverzeichnis
{: .no_toc .text-delta }

1. TOC
{:toc}

### Kann ich durch Lightning-Payments reich werden?

Niemand weis es. Wahrscheinlich nicht. Du wirst nur minimale Beträge erhalten. Ist mir egal. Genieß' das Abenteur!

### Kann ich die externe Festplatte mit meinem Windows-Computer verbinden?

Ext4 funktioniert normalerweise nicht mit Windows, aber mit externe Software wie [Linux File Systems](https://www.paragon-software.com/home/linuxfs-windows/#faq) von Paragon Software (10tägige Testversion) geht's.

### Wass machen die ganzen Linux-Befehle?

Dies ist eine (sehr) kurze Liste verschiedener Linux-Befehle. Für einen bestimmten Befehl kann `man [command]` weitere Informationen liefern (`q` zum Beenden eingeben).

| Befehl       | Beschreibung                                 | Beispiel                                     |
| ------------ | -------------------------------------------- | -------------------------------------------- |
| `cd`         | Ein Verzeichnis öffnen                       | `cd /home/umbrel`                            |
| `ls`         | Ordnerinhalte anzeigen                       | `ls -la /home/umbrel/umbrel`                 |
| `cp`         | Kopieren                                     | `cp datei.txt newdatei.txt`                  |
| `mv`         | Verschieben                                  | `mv datei.txt andere_datei.txt`              |
| `rm`         | Löschen                                      | `rm datei.txt`                               |
| `mkdir`      | Ordner erstellen                             | `mkdir /home/umbrel/NeuerOrdner`             |
| `ln`         | Link erstellen                               | `ln -s /zielordner /link`                    |
| `sudo`       | Befehl als Administrator ausführen           | `sudo nano textdatei.txt`                    |
| `su`         | switch to different user account             | `sudo su root`                               |
| `chown`      | change file owner                            | `chown umbrel:umbrel datei.txt`              |
| `chmod`      | Dateiberechtigungen ändern                   | `chmod +x einSkript.sh`                      |
| `nano`       | Texteditor                                   | `nano textdatei.txt`                         |
| `tar`        | Archivtool                                   | `tar -cvf archiv.tar datei1.txt datei2.txt`  |
| `exit`       | Aktuelle Sitzung beenden                     | `exit`                                       |
| `systemctl`  | Systemd service verwalten                    | `sudo systemctl start umbrel-startup`        |
| `journalctl` | System-Logs anzeigen                         | `sudo journalctl -u umbrel-external-storage` |
| `htop`       | Prozesse & Ressourcennutzung anzeigen        | `htop`                                       |
| `shutdown`   | Raspberry Pi neu starten oder herunterfahren | `sudo shutdown -r now`                       |

### Wo kann ich mehr erfahren?

If you want to learn more about Bitcoin and are curious about the inner workings of the Lightning Network, the following articles in Bitcoin Magazine offer a very good introduction:

- [What is Bitcoin?](https://bitcoinmagazine.com/guides/what-bitcoin)
- [Understanding the Lightning Network](https://bitcoinmagazine.com/articles/understanding-the-lightning-network-part-building-a-bidirectional-payment-channel-1464710791/)
- [Bitcoin resources](https://www.lopp.net/bitcoin-information.html) and [Lightning Network resources](https://www.lopp.net/lightning-information.html) by Jameson Lopp

### Does Umbrel support .....?

Currently not, but Umbrel has an application infrastructure, so third-party developers can add apps to Umbrel and publish them in its [App Store](https://medium.com/getumbrel/introducing-the-umbrel-app-store-7a2068c64a10).

---

This General FAQ guide will be constantly updated with findings that have been or will be reported in the issues section. Feel free to contribute via a pull request.

---
# rpi-toolbox

WARNUNG: Dieses Tool kann tief in das System eingreifen. Bei falscher Nutzung kann es zu Datenverlust, Instabilität oder Hardwaredefekten kommen. Der Autor übernimmt keine Haftung. Verwendung auf eigene Gefahr.

## Features (Beispiel)
- info: Systeminformationen anzeigen
- backup: SD-Karten-Image mit `dd` erstellen
- governor: CPU governor wechseln
- overwrite-bootloader: (Sperrmechanismus; nicht automatisch ausführbar)

## Installation
1. Auf Raspberry Pi kopieren
2. `chmod +x main.py`
3. Ausführen mit `sudo ./main.py info`

## Hinweise für Entwickler
- kritische Aktionen benötigen root
- Logging: `/var/log/rpi-toolbox.log`
- Überlege, Snapshots oder automatisierte Image-Backups vor gefährlichen Aktionen anzubieten

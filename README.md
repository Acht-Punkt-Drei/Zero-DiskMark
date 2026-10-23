# Zero-DiskMark

Portable drive benchmark for Windows 10/11 (x64), with German and English interface, result comparison and temperature recording.

## Download

[Download the latest version / Aktuelle Version herunterladen](https://github.com/Acht-Punkt-Drei/Zero-DiskMark/releases/latest)

Extract the ZIP and start `Zero-DiskMark.exe`. No installation or additional .NET runtime is required. The ZIP includes instructions and both DiskSpd licenses and provenance files. The portable EXE is not digitally signed.

ZIP entpacken und `Zero-DiskMark.exe` starten. Keine Installation und keine zusätzliche .NET-Installation erforderlich. Anleitung, beide DiskSpd-Lizenzen und Herkunftsnachweise sind enthalten. Die portable EXE ist nicht digital signiert.

## Features / Funktionen

- German and English interface, automatic Windows-language selection and a saved manual override.
- SLC cache analysis with a bounded write test, live chart and estimated transition range. Suggested benchmark settings require explicit confirmation.
- Sequential and random read/write tests with adjustable parameters and Standard, NVMe SSD and Flash Memory presets.
- CrystalDiskMark DiskSpd 2.2 and Microsoft DiskSpd 2.3 engines, with IoRing, BypassIO, CPU affinity and buffer options.
- Drive information, result history and horizontal comparison bars.
- Temperature/throughput charts and tables, point selection and swappable axes.
- Selectable results file, including USB drives, CSV export and elapsed-time display.

Die SLC-Analyse liefert eine Schätzung des aktuell beobachteten Cache-Verhaltens, keine garantierte physische Cache-Größe. Ohne eindeutigen Übergang wird keine Größe angegeben. Die Messung kann große Datenmengen schreiben; Schreiblimit wählen und den Cache vor einer Wiederholung im Leerlauf erholen lassen.

Both bundled DiskSpd engines use the MIT license. Their licenses and provenance are included in the download. Zero-DiskMark has an independent interface.

This repository provides Windows builds and release notes. / Dieses Repository stellt die Windows-Builds und Versionshinweise bereit.

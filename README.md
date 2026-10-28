# Zero-DiskMark

Portable drive benchmark for Windows 10/11 (x64), with German and English interface, result comparison and temperature recording.

## Download

[Microsoft Store](https://apps.microsoft.com/detail/9NXB8LQ45L11) · [Latest portable version / Aktuelle portable Version](https://github.com/Acht-Punkt-Drei/Zero-DiskMark/releases/latest)

The Microsoft Store version is signed and updated through the Store. The portable EXE/ZIP remains available separately. Extract the ZIP and start `Zero-DiskMark.exe`. No installation or additional .NET runtime is required. The ZIP includes instructions and both DiskSpd licenses and provenance files. The portable EXE is not digitally signed.

Die Store-Version wird über den Microsoft Store signiert und aktualisiert. Die portable EXE/ZIP bleibt separat verfügbar. ZIP entpacken und `Zero-DiskMark.exe` starten. Keine Installation und keine zusätzliche .NET-Installation erforderlich. Anleitung, beide DiskSpd-Lizenzen und Herkunftsnachweise sind enthalten. Die portable EXE ist nicht digital signiert.

## New in 1.8.0 / Neu in 1.8.0

- Automatically checks DiskSpd 2.3 IoRing, registered buffers, BypassIO and CPU topology for the selected test folder. Unsupported or unconfirmed options are disabled with explanations and a refresh button.
- Prüft DiskSpd-2.3-Optionen für den ausgewählten Testordner automatisch. Nicht unterstützte oder unbestätigte Optionen sind mit Begründung ausgegraut und können erneut geprüft werden.
- New M.2 SSD, binary data, RAM and stopwatch icon / Neues Icon mit M.2-SSD, Bits, RAM und Stoppuhr.
- A small compatibility query uses an owned empty temporary file; it does not start a performance test. Settings change only after explicit confirmation. Capabilities are checked again before a benchmark.

## Features / Funktionen

- German and English interface, automatic Windows-language selection and a saved manual override.
- SLC cache analysis with a bounded write test, live chart and estimated transition range. Suggested benchmark settings require explicit confirmation.
- Sequential and random read/write tests with adjustable parameters and Standard, NVMe SSD and Flash Memory presets.
- CrystalDiskMark DiskSpd 2.2 and Microsoft DiskSpd 2.3 engines, with IoRing, BypassIO, CPU affinity and buffer options.
- Drive information, result history and horizontal comparison bars.
- Temperature/throughput charts and tables, point selection and swappable axes.
- Selectable results file, including USB drives, CSV export and elapsed-time display.

Die SLC-Analyse liefert eine Schätzung des aktuell beobachteten Cache-Verhaltens, keine garantierte physische Cache-Größe. Ohne eindeutigen Übergang wird keine Größe angegeben. Die Messung kann große Datenmengen schreiben; Schreiblimit wählen und den Cache vor einer Wiederholung im Leerlauf erholen lassen.

Both bundled DiskSpd engines use the MIT license. Their full licenses and provenance are included in the download and accessible in the app. The Microsoft 2.3 source build has a documented compatibility-query extension; its benchmark routine is unchanged. Zero-DiskMark has an independent interface.

This repository provides Windows builds and release notes. / Dieses Repository stellt die Windows-Builds und Versionshinweise bereit.

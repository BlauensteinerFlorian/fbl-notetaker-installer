# FBL Notetaker

**Meeting-Notizen, die deinen Rechner nie verlassen.**

FBL Notetaker nimmt Meetings auf deinem Windows-Rechner auf, schreibt mit, erkennt, wer gesprochen hat, und erstellt daraus strukturierte Notizen – mit To-dos, Entscheidungen und offenen Fragen. Alles läuft lokal: keine Cloud, kein Bot im Call, kein Konto nötig. Die App funktioniert mit jedem Konferenz-Tool (Teams, Zoom, Webex, Google Meet im Browser …) und wartet unauffällig im Infobereich der Taskleiste.

**[⬇ Neueste Version herunterladen](../../releases/latest)** · kostenlos, auch für die berufliche Nutzung ([Lizenz](LICENSE.md))

> **English:** FBL Notetaker is a free, local-first Windows app that records meetings, transcribes them, tells speakers apart and writes structured notes – fully on-device, no cloud, no meeting bot. The interface is German, with an English option (Settings → General). [Download the latest version](../../releases/latest) · [License (German, with English translation)](LICENSE.md)

---

## Funktionen

**Aufnahme**
- Mikrofon und Systemton als zwei getrennte Spuren, unabhängig vom Konferenz-Tool
- Auf Wunsch automatisch: Die Aufnahme startet, sobald Teams, Zoom, Webex oder ein Browser das Mikrofon nutzt oder du am Laptop über Bluetooth telefonierst (z. B. mit Smartphone-Link), und endet mit dem Call
- Übersteht Gerätewechsel (Headset ↔ Lautsprecher) und Abstürze; Audio wird laufend gespeichert
- Drei Modi: **Online** (Call am Rechner), **Präsenz** (alle im Raum sprechen ins Mikrofon) und **Hybrid** (beides) – die Sprechererkennung arbeitet jeweils auf der passenden Spur
- Geräte für Mikrofon und Systemton wählbar, Pegel-Test eingebaut

**Mitschrift und Sprecher**
- Die Mitschrift läuft schon während des Meetings mit – nach dem Stopp liegt sie in Sekunden vor
- Deutsch als Standard, Englisch über ein zusätzliches Modell; mit Whisper auf Wunsch abgestimmt auf österreichisches Deutsch (Wien und Niederösterreich)
- Sprechererkennung nach dem Meeting; Sprecher umbenennen und zusammenführen
- „Transkript verbessern“: neuer Durchlauf über die ganze Aufnahme, auf Wunsch mit anderem Modell und Wörterbuch für Namen und Fachbegriffe

**Notizen**
- Zusammenfassung durch ein lokales Sprachmodell nach Vorlage: Standard-Meeting, Kundentermin, Jour fixe, Workshop – oder eigene Vorlagen mit frei definierbaren Abschnitten
- To-dos mit Verantwortlichen und Fälligkeit als Checkliste
- Notizen bearbeiten und neu zusammenfassen; frühere Fassungen bleiben erhalten

**Export und Suche**
- Nach OneNote, als Word- oder Markdown-Datei oder formatiert in die Zwischenablage
- Volltextsuche über alle Mitschriften und Notizen; Filter nach Zeitraum, Programm und Vorlage

**Komfort**
- Lebt im Infobereich, startet auf Wunsch mit Windows
- Oberfläche auf Deutsch oder Englisch
- Heller und dunkler Modus nach Windows
- Tonaufnahmen werden auf Wunsch nach einer Frist gelöscht; Mitschrift und Notizen bleiben
- Nutzt eine vorhandene Grafikkarte automatisch, sonst den Prozessor

## Datenschutz

- Aufnahmen, Mitschriften und Notizen bleiben auf deinem Rechner. Keine Telemetrie.
- Die App geht nur ins Netz, um Modelle von **Hugging Face** zu laden (beim ersten Start und wenn du weitere Modelle wählst), – nur wenn du den OneNote-Export einrichtest – für die **Anmeldung bei Microsoft** und, sobald automatische Updates aktiv sind, einmal am Tag für die **Update-Prüfung** hier auf GitHub (abschaltbar).
- Die vollständige [Datenschutzerklärung](DATENSCHUTZ.md) gilt für den Installer von hier und für die Fassung aus dem Microsoft Store.

## Systemvoraussetzungen

- Windows 10 oder 11, 64 Bit
- mindestens 8 GB Arbeitsspeicher, besser 16 GB
- rund 4 GB freier Speicher für die Modelle
- Eine Grafikkarte ist nicht nötig, beschleunigt die Notizen aber deutlich

## Installation

1. Unter **[Releases](../../releases/latest)** die Datei `FBL.Notetaker_<Version>_x64-setup.exe` herunterladen und ausführen. Administratorrechte sind nicht nötig.
2. Der Installer ist noch nicht signiert. Windows SmartScreen kann deshalb warnen („Der Computer wurde durch Windows geschützt“). Dann auf **„Weitere Informationen“** → **„Trotzdem ausführen“** klicken.
3. Beim ersten Start führt ein Assistent durch die Einrichtung: Modelle laden (rund 3,4 GB, einmalig), Mikrofon und Lautsprecher testen, Startoptionen wählen.
4. Danach wartet die App als Symbol unten rechts in der Taskleiste (eventuell unter dem kleinen Pfeil). Linksklick öffnet das Fenster, Rechtsklick das Menü mit „Aufnahme starten“.

**Aktualisieren:** einfach den neuen Installer über die vorhandene Version installieren. Meetings, Notizen und Modelle bleiben erhalten.

**Deinstallieren:** über „Einstellungen“ → „Apps“ in Windows. Meetings und Modelle liegen unter `%APPDATA%\FBL Notetaker` und können danach von Hand gelöscht werden.

## Erste Schritte

1. **Aufnehmen:** Knopf oben rechts im Fenster oder Rechtsklick auf das Symbol → „Aufnahme starten“.
2. **Mitlesen:** Ein Klick auf das Meeting zeigt die Mitschrift, die während der Aufnahme wächst.
3. **Sprecher benennen:** Nach dem Stopp im Reiter „Sprecher“ Namen eintippen; danach „Neu zusammenfassen“, damit die Namen in den Notizen stehen.
4. **Notizen:** Sie entstehen nach dem Meeting von selbst im Reiter „Notizen“ und lassen sich bearbeiten und exportieren.
5. **Automatisch:** Unter „Einstellungen“ → „Automatische Aufnahme“ startet die App von selbst, sobald ein Call beginnt.

## Fehler melden und Wünsche

Fehler und Ideen bitte als [Issue](../../issues) melden. **Bitte keine Inhalte aus Meetings, Mitschriften oder Notizen in ein Issue schreiben.** Hilfreich ist das Fehler-Protokoll („Einstellungen“ → „Über“ → „Fehler-Protokoll öffnen“) – es enthält keine Inhalte aus Meetings.

## Wichtig: Aufnahmen und Recht

Ob und wann ein Gespräch aufgenommen werden darf, verantwortest du selbst. Hol im Zweifel die Zustimmung aller Beteiligten ein und beachte die Regeln deines Arbeitgebers (in Österreich u. a. § 120 StGB, Persönlichkeitsrecht, DSGVO).

## Lizenz

FBL Notetaker ist **Freeware**: kostenlos für alle, privat und beruflich, auch kommerziell. Verkaufen, Weiterverbreiten außerhalb der eigenen Organisation und Verändern sind nicht erlaubt. Die vollständigen Bedingungen stehen in [LICENSE.md](LICENSE.md), Bestandteile Dritter und Modelle in [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).

Der Quellcode ist nicht öffentlich. Dieses Repository enthält nur die Installer.

© 2026 Florian Blauensteiner

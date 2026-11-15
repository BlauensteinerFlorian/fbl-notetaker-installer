# Datenschutzerklärung – FBL Notetaker

*English version below.*

Stand: 15.11.2026 · gilt für FBL Notetaker aus dem Microsoft Store und für den Installer von GitHub

## Kurz gesagt

FBL Notetaker verarbeitet alles **auf Ihrem eigenen Rechner**. Tonaufnahmen, Mitschriften, Sprecher und Notizen verlassen das Gerät nicht. Der Herausgeber erhält keine Daten von Ihnen – es gibt keine Konten, keine Telemetrie, keine Werbung und keine Analyse der Nutzung.

## Verantwortlich

Florian Blauensteiner, Österreich. Kontakt für Fragen zum Datenschutz: [assistant@blauensteiner.io](mailto:assistant@blauensteiner.io)

## Welche Daten die App verarbeitet – und wo

| Daten | Zweck | Ort |
| --- | --- | --- |
| Ton vom Mikrofon und vom Systemton (was der Rechner abspielt) | Aufnahme eines Meetings – nur während einer Aufnahme, die Sie starten oder die Sie für erkannte Calls ausdrücklich eingeschaltet haben | Auf Ihrem Rechner |
| Mitschrift, erkannte Sprecher (Stimmmerkmale nur während der Erkennung im Arbeitsspeicher), Namen, die Sie vergeben, Notizen, Vorlagen | Funktion der App | Datenbank auf Ihrem Rechner |
| Einstellungen | Funktion der App | Auf Ihrem Rechner |
| Welche Programme gerade Ton aufnehmen oder abspielen (Audio-Sitzungen von Windows: Programmname und Gerät, keine Töne) | Erkennen, ob ein Call oder ein Telefonat über Bluetooth läuft – nur bei eingeschalteter automatischer Aufnahme oder wenn Sie „Erkennung jetzt prüfen“ drücken | Nur im Arbeitsspeicher Ihres Rechners, wird nicht gespeichert |
| Fehler-Protokoll | Fehlersuche; enthält **keine** Inhalte aus Meetings | Auf Ihrem Rechner, wird nie übertragen |
| Anmeldung bei Microsoft (nur wenn Sie den Export nach OneNote nutzen) | Seiten in Ihrem OneNote anlegen | Zugangsschlüssel in der Windows-Anmeldeinformationsverwaltung |

Die Spracherkennung, die Sprechererkennung und das Sprachmodell für die Notizen laufen vollständig auf Ihrem Gerät. Die Notizen erstellt ein lokales KI-Sprachmodell; sie können Fehler enthalten.

## Verbindungen ins Internet

Die App baut nur in diesen Fällen eine Verbindung auf:

1. **Herunterladen von Modellen** von Hugging Face (huggingface.co und dessen Download-Server), wenn Sie Modelle laden oder per Link importieren. Übertragen werden dabei nur die technisch nötigen Angaben (z. B. Ihre IP-Adresse) an Hugging Face; es gelten die Datenschutzbestimmungen von Hugging Face. Inhalte Ihrer Meetings werden nicht übertragen.
2. **Export nach OneNote**, wenn Sie ihn einrichten und nutzen: Anmeldung bei Microsoft und Übertragung der Notizen, die Sie exportieren, an Microsoft Graph in Ihr eigenes OneNote. Es gelten die Datenschutzbestimmungen von Microsoft.
3. **Nur beim Installer von GitHub** (nicht in der Store-Fassung), sobald Updates in der Version eingerichtet sind: Die App fragt von selbst einmal am Tag bei github.com nach einer neuen Version (übertragen werden nur die technisch nötigen Angaben wie die IP-Adresse); abschaltbar unter „Einstellungen“ → „Updates“. Die Store-Fassung wird über den Microsoft Store aktualisiert.

Fall 1 und 2 löst nur Ihre eigene Handlung aus.

Darüber hinaus sendet die App nichts.

## Aufnahme anderer Personen

Die App nimmt auf, was am Mikrofon und im Systemton zu hören ist, also auch andere Personen im Gespräch. Ob und wann Sie aufnehmen dürfen, hängt vom geltenden Recht und von den Regeln Ihres Arbeitgebers ab. Holen Sie die Zustimmung der Beteiligten ein, wo das nötig ist. Windows zeigt während jeder Aufnahme das Mikrofon-Symbol in der Taskleiste.

## Speicherdauer und Löschen

- Daten bleiben, bis Sie sie löschen: einzelne Tonaufnahmen („Audio löschen“), ganze Meetings („Meeting löschen“) oder automatisch alle Tonaufnahmen nach einer wählbaren Frist („Einstellungen“ → „Aufbewahrung“).
- Store-Fassung: Beim Deinstallieren löscht Windows den Datenordner der App mit allen Meetings, Notizen und Modellen. Haben Sie Audio oder Modelle unter „Einstellungen“ → „Speicherort“ an einen anderen Ort gelegt, bleiben diese Ordner bestehen und lassen sich von Hand löschen.
- Installer von GitHub: Die Daten liegen unter `%APPDATA%\FBL Notetaker` und bleiben nach der Deinstallation erhalten, bis Sie den Ordner löschen.

## Ihre Rechte

Da der Herausgeber keine Daten von Ihnen erhält oder speichert, gibt es bei ihm nichts auszukunften, zu berichtigen oder zu löschen – alle Daten liegen in Ihrer Hand auf Ihrem Gerät. Bei Fragen erreichen Sie uns unter der oben genannten Adresse. Sie haben das Recht auf Beschwerde bei der österreichischen Datenschutzbehörde (dsb.gv.at).

## Änderungen

Ändert sich, welche Daten die App verarbeitet oder wohin sie Verbindungen aufbaut, wird diese Erklärung vorher angepasst.

---

# Privacy Policy – FBL Notetaker

Last updated: 15 November 2026 · applies to FBL Notetaker from the Microsoft Store and to the installer from GitHub

## In short

FBL Notetaker processes everything **on your own computer**. Audio recordings, transcripts, speakers and notes never leave the device. The publisher receives no data from you – there are no accounts, no telemetry, no advertising and no usage analytics.

## Controller

Florian Blauensteiner, Austria. Contact for privacy questions: [assistant@blauensteiner.io](mailto:assistant@blauensteiner.io)

## What data the app processes – and where

| Data | Purpose | Location |
| --- | --- | --- |
| Sound from the microphone and system audio (what the computer plays) | Recording a meeting – only during a recording that you start or that you have explicitly enabled for detected calls | On your computer |
| Transcript, recognised speakers (voice features only in memory during recognition), names you assign, notes, templates | App functionality | Database on your computer |
| Settings | App functionality | On your computer |
| Which programs are currently recording or playing sound (Windows audio sessions: program name and device, no sound) | Detecting whether a call or a Bluetooth phone call is in progress – only with automatic recording switched on or when you press "Check detection now" | Only in your computer's memory, not stored |
| Error log | Troubleshooting; contains **no** meeting content | On your computer, never transmitted |
| Microsoft sign-in (only if you use the OneNote export) | Creating pages in your OneNote | Access token in Windows Credential Manager |

Speech recognition, speaker recognition and the language model for the notes run entirely on your device. The notes are written by a local AI language model and may contain mistakes.

## Internet connections

The app only connects to the internet in these cases:

1. **Downloading models** from Hugging Face (huggingface.co and its download servers) when you download models or import them via a link. Only the technically necessary information (e.g. your IP address) is transmitted to Hugging Face; Hugging Face's privacy policy applies. No meeting content is transmitted.
2. **Export to OneNote**, if you set it up and use it: sign-in with Microsoft and transmission of the notes you export to Microsoft Graph, into your own OneNote. Microsoft's privacy policy applies.
3. **Only for the installer from GitHub** (not the Store version), once updates are set up in that version: the app checks github.com for a new version by itself once a day (only technically necessary information such as the IP address is transmitted); can be switched off under "Settings" → "Updates". The Store version is updated through the Microsoft Store.

Cases 1 and 2 are only triggered by your own action.

Apart from that, the app sends nothing.

## Recording other people

The app records what can be heard on the microphone and in system audio, which includes other people in the conversation. Whether and when you may record depends on applicable law and your employer's rules. Obtain the consent of the participants where required. Windows shows the microphone icon in the taskbar during every recording.

## Retention and deletion

- Data stays until you delete it: individual recordings ("Delete audio"), whole meetings ("Delete meeting"), or automatically all recordings after a period you choose ("Settings" → "Retention").
- Store version: when you uninstall, Windows deletes the app's data folder with all meetings, notes and models. If you have moved audio or models to another location under "Settings" → "Storage location", those folders remain and can be deleted manually.
- Installer from GitHub: the data is stored under `%APPDATA%\FBL Notetaker` and remains after uninstalling until you delete the folder.

## Your rights

As the publisher does not receive or store any of your data, there is nothing to disclose, correct or erase on the publisher's side – all data is in your hands on your device. For questions, contact us at the address above. You have the right to lodge a complaint with the Austrian Data Protection Authority (dsb.gv.at).

## Changes

If the data the app processes or the connections it makes change, this policy will be updated beforehand.

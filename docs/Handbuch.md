# MeeriDEX · Handbuch und Hilfe

[Zurück zur Startseite](../README.md) · [Windows herunterladen](https://github.com/Coupe5E/MerriDex/releases/latest) · [Android herunterladen](https://github.com/Coupe5E/MerriDex/releases/tag/companion-v0.8.13)

Hier findest du die ausführlichen Installationsschritte und Hilfen. Die kurze Vorstellung und alle Downloads stehen auf der Startseite.

## Inhalt

- [Windows installieren](#desktop-installieren-und-aktualisieren) · [.NET Framework](#net-framework-kostenlos-nachinstallieren) · [SmartScreen](#windows-smartscreen-beim-download-oder-start)
- [Probleme am PC](#probleme-am-pc) · [Windows 7](#hinweis-zu-windows-7)
- [Android installieren](#android-installieren--schritt-für-schritt) · [Android-Warnungen](#android-warnungen-richtig-einordnen) · [Probleme in der App](#probleme-in-der-app)
- [WLAN-Sync](#pc-und-app-synchronisieren)
- [Eigene Tiere und Stammbaum](#eigene-tiere-und-stammbaum-richtig-anlegen) · [A4/PDF](#stammbaum-als-a4-pdf-exportieren-und-drucken)
- [Würfe](#würfe-auf-pc-und-android) · [Abgabe](#abgabe-übernehmende-personen-und-zuchten) · [MeeriHimmel](#meerihimmel)
- [Zuchtlogo](#eigenes-zuchtlogo) · [Chipnummer/TASSO](#chipnummer-prüfen-und-bei-tasso-registrieren) · [MeeriPro3-Import](#meeripro3-datei-oder-zip-übernehmen)
- [Genstatus und Zucht-Favoriten](#genstatus-herkunft-und-zucht-favoriten)
- [Problem melden](#problem-melden)

## Windows · Einziehen und Aktualisieren

### Desktop installieren und aktualisieren

**Neue Installation:**

1. Den [Windows-Installer MeeriDEX-Setup.exe](https://github.com/Coupe5E/MerriDex/releases/latest/download/MeeriDEX-Setup.exe) herunterladen und starten.
2. Die Windows-Abfrage bestätigen und den Assistenten durchgehen. Desktop- und Startmenü-Verknüpfungen werden angelegt. Am Ende kann MeeriDEX direkt starten.
3. Eine bereits eindeutig gefundene Kartei wird ab 1.9.35 automatisch geprüft und gesichert übernommen. Bei mehreren unterschiedlichen Karteien folgt eine Auswahl; ohne gefundene Kartei kannst du den bisherigen Ordner wählen oder neu beginnen.
4. Falls erforderlich die Lizenz aktivieren und das Züchterprofil vervollständigen.

**Vorhandene Installation aktualisieren:** In MeeriDEX **Updates prüfen** verwenden oder MeeriDEX schließen und denselben aktuellen Installer starten. Vor automatischen Updates erstellt MeeriDEX eine ZIP- und Excel-Sicherung. Nur Installation und Programmupdates benötigen die Windows-Bestätigung; im Alltag läuft MeeriDEX ohne Administratorrechte.

Ab 1.9.35 werden ungeeignete Speicherorte vor dem Download erkannt. **Automatisch einrichten** lädt den geprüften offiziellen Installer und führt den Umstieg weiter. Während eines laufenden Updates wird kein zweiter Updatevorgang für dasselbe Ziel gestartet. Ein abgebrochener oder fehlgeschlagener Installationsversuch derselben Version löst beim nächsten Programmstart keinen erneuten automatischen Download aus: Mit **Updates prüfen** setzt du ihn fort. Ein vorhandener Download wird nach erneuter Größen- und SHA-256-Prüfung wiederverwendet. Der Abschluss prüft die tatsächlich installierte Programmversion und die Programmdatei.

**Setup-Code 5:** Bedeutet einen Abbruch während der Installation oder nach einer Setup-Rückfrage; er bedeutet nicht automatisch „Zugriff verweigert“. Ab 1.9.35 zeigt die Updateübergabe Setup-Rückfragen an und nennt bei Fehlern den Pfad zum festen `installation.log` neben dem geladenen Installer. Die Installation in denselben bisherigen Programmordner ist normal. Bei einer Dateisperre den angebotenen regulären Abschluss der betroffenen Anwendung verwenden oder offene MeeriDEX-Fenster schließen und im Setup erneut versuchen. Es wird kein erzwungenes Beenden angefordert. [Bedeutung der Setup-Codes](https://jrsoftware.org/ishelp/topic_setupexitcodes.htm).

**Speicherorte:** Das Programm liegt standardmäßig unter `C:\Programme\MeeriDEX` beziehungsweise `C:\Program Files\MeeriDEX`. Tierkartei, Fotos, Profil und Sicherungen liegen getrennt unter `%LOCALAPPDATA%\MeeriDEX\Daten`. Über **Datenordner öffnen** erreichst du sie direkt. Eine Deinstallation lässt die Tierdaten erhalten.

### Von einer alten Version umziehen

1. Die bisherige MeeriDEX-Version schließen und den [aktuellen Windows-Installer](https://github.com/Coupe5E/MerriDex/releases/latest/download/MeeriDEX-Setup.exe) starten. Bei alten Versionen mit „Zugriff verweigert“, „Ungültiger Update-Speicherort“ oder einer zu kleinen Downloadgrenze ist dieser einmalige manuelle Schritt nötig. Alte EXE-Dateien können ihre Updatefehler erst nach einem Austausch beheben.
2. Die neue MeeriDEX-Verknüpfung verwenden. Ab 1.9.35 sucht MeeriDEX an bekannten bisherigen Installationsorten und berücksichtigt den beim automatischen Umstieg übergebenen Datenordner. Eine eindeutig gefundene Kartei zieht automatisch ein. Liegt sie an einem anderen Ort, fragt MeeriDEX nach dem bisherigen Ordner mit `meeridex.sqlite` oder `tiere.json`.
3. Tiere, Fotos, Profil, Einstellungen und Zucht-Favoriten werden kopiert und geprüft. Eine Bestätigung nennt die Zahl der übernommenen Tiere und Fotos. Eine ZIP- und Excel-Sicherung entsteht automatisch. Die Originalkartei und ihre bisherigen Sicherungen bleiben im alten Ordner erhalten.

**Mehrere Karteien:** Identische Kopien erfordern keine zusätzliche Auswahl. Bei unterschiedlichen gefundenen Karteien wählst du einmal die richtige aus. Ist im neuen Benutzerordner bereits eine andere Kartei vorhanden und wurde ein alter Datenordner ausdrücklich zum Umstieg übergeben, fragt MeeriDEX ebenfalls nach. Bei einem Wechsel wird die bisherige Zielkartei zusätzlich gesichert und als eigener Ordner neben dem Datenordner aufbewahrt. Es werden keine Karteien automatisch zusammengeführt.

**Alte Verknüpfungen:** Bei einer geprüften Übernahme werden passende persönliche Desktop-, Startmenü- und angeheftete Verknüpfungen auf die neue Programmdatei angepasst. Erkennt eine neue Programmversion beim Start eine neuere Installation mit derselben Kartei, öffnet sie diese. Bei anderen Karteien erfolgt kein stiller Wechsel. Sehr alte EXE-Dateien kennen diese Erkennung noch nicht: bitte die neue MeeriDEX-Verknüpfung verwenden.

Die bestehende Aktivierung im selben Windows-Benutzerkonto bleibt an ihrem bisherigen Speicherort. Die einzelne Programm-EXE im Release bleibt eine technische Kompatibilitätsdatei für ältere Auto-Updater; für manuelle Installationen und Updates den **Installer** verwenden. Eine EXE allein enthält keine Tierdaten.

**Daten aufbewahren:** `meeridex.sqlite` enthält die Kartei, `Profil` unter anderem Züchterdaten und Tierfotos; `Sicherungen` enthält Backups. Die automatische Sicherung ersetzt keine zusätzliche Kopie auf einem anderen Datenträger. Der neue lokale Updatebericht liegt unter `%LOCALAPPDATA%\MeeriDEX\Einrichtung\Diagnose\letzte-update-pruefung.txt`.

### .NET Framework kostenlos nachinstallieren

Falls MeeriDEX wegen einer fehlenden .NET-Laufzeit nicht startet: **[Offiziellen .NET Framework 4.8 Offline-Installer bei Microsoft herunterladen](https://dotnet.microsoft.com/en-us/download/dotnet-framework/thank-you/net48-offline-installer)**.

1. Den Microsoft-Installer herunterladen und MeeriDEX schließen.
2. Den Installer starten und die Windows-Abfrage nach Administratorrechten bestätigen. Benötigt wird die **Runtime**, kein Developer Pack und keine moderne „.NET Desktop Runtime“.
3. Nach der Installation neu starten, falls der Installer dazu auffordert, und anschließend `MeeriDEX.exe` öffnen.

Auf Windows 10/11 ist eine passende Laufzeit häufig bereits vorhanden. Wenn bereits eine neuere passende .NET-Framework-4.x-Version vorhanden ist, muss sie nicht ersetzt werden. Für **Windows 7 SP1** ist **4.8** vorgesehen, **nicht 4.8.1**. Die frühere `winsqlite3.dll`-Meldung wird durch MeeriDEX ab **1.7.2** behoben; eine .NET-Installation allein ersetzt diese Korrektur nicht.

Programmpakete ab 1.7.3 enthalten zusätzlich `NET-Framework-4.8-herunterladen.url` und `NET-Framework-Hilfe.txt`. Der Verweis führt direkt zum Microsoft-Download; der Installer wird nicht automatisch gestartet.

### Windows-SmartScreen beim Download oder Start

Die aktuelle Windows-Version von MeeriDEX ist **noch nicht digital signiert**. Bei einer neuen oder wenig verbreiteten Datei können Microsoft Edge und Windows deshalb eine Warnung zu einer unbekannten Anwendung anzeigen. Eine Signatur-/Reputationswarnung ist von einer konkreten Schadsoftware-Erkennung zu unterscheiden.

1. MeeriDEX ausschließlich von den [offiziellen GitHub-Releases dieses Projekts](https://github.com/Coupe5E/MerriDex/releases/latest) herunterladen. Unter **Assets** für Installation und manuelle Updates `MeeriDEX-Setup.exe` auswählen; `Source code` und `.sha256` sind keine Installationspakete.
2. Falls Edge den Download als selten heruntergeladen meldet: Im Downloadmenü bei der Datei **…** öffnen. Wenn angeboten, **Beibehalten** und anschließend **Mehr anzeigen → Trotzdem beibehalten** wählen – erst nachdem Herkunft und genaue Warnung geprüft wurden. Die Bezeichnungen können je nach Edge-Version abweichen.
3. `MeeriDEX-Setup.exe` öffnen, die Windows-Bestätigung prüfen und die Installation durchlaufen. MeeriDEX anschließend über die Desktop- oder Startmenü-Verknüpfung öffnen.
4. Erscheint beim Start die SmartScreen-Meldung **„Der Computer wurde durch Windows geschützt“** wegen einer unbekannten App, auf **Weitere Informationen** klicken. Wenn du dem Download aus diesem Projekt vertraust und die Option angeboten wird, **Trotzdem ausführen** wählen.
5. Beim ersten Start unter **Lizenz / Aktivierung** Vorname, Nachname, Zuchtname und Lizenzcode eingeben. Alle Angaben müssen zur ausgestellten Lizenz passen; zur Aktivierung ist Internet erforderlich.

**Andere Sicherheitsmeldung oder keine Fortsetzungsoption?** Den genauen Meldungstext beziehungsweise einen Screenshot und die MeeriDEX-Version melden. Bei einer konkreten Virenerkennung nicht nach dieser Anleitung fortfahren. Smart App Control oder verwaltete Geräte können andere Sperren anzeigen. Windows-Schutzfunktionen müssen für diese Anleitung nicht abgeschaltet werden.

[Microsoft: Wie SmartScreen die Bekanntheit von Anwendungen bewertet](https://learn.microsoft.com/en-us/windows/apps/package-and-deploy/smartscreen-reputation)

### Probleme am PC

| Problem | Was du prüfen kannst |
| --- | --- |
| **Meldung zu fehlendem .NET Framework / Programm startet nicht** | Windows aktualisieren und die passende **.NET Framework 4.x-Laufzeit** von Microsoft prüfen/installieren, beispielsweise 4.8 oder 4.8.1 passend zur Windows-Version. Neuere Windows-Versionen enthalten sie bereits. Das ist ein anderes Produkt als die moderne „.NET Desktop Runtime“. [Microsoft-Anleitung](https://learn.microsoft.com/de-de/dotnet/framework/install/on-windows-10). |
| **`winsqlite3.dll` fehlt** | Ab **1.7.2** enthält die EXE ihre eigene SQLite-Bibliothek; `winsqlite3.dll` muss nicht mehr vorhanden sein. Eine ältere MeeriDEX-Version mit dem aktuellen Installer aktualisieren und eine bisherige portable Kartei gezielt übernehmen. Keine einzelnen DLLs von fremden Downloadseiten beziehen. Bei weiterem Fehler den vollständigen Meldungstext melden. |
| **Muss ich Java, Office oder Datenbankwerkzeuge nachinstallieren?** | Nein. Java, Python, Android Studio und ein separater SQLite-/SQL-Server werden für die Nutzung nicht benötigt. Excel muss für Import und Export nicht installiert sein; zum Ansehen einer XLSX-Datei ist ein kompatibles Tabellenprogramm nötig. |
| **Windows oder Virenschutz warnt vor dem Download** | Eine unbekannte oder wenig verbreitete EXE kann einen Hinweis auslösen. Das allein sagt nicht, dass sie schädlich ist. Herkunft und genaue Meldung prüfen; eine konkrete Virenerkennung nicht pauschal ignorieren und den Virenschutz nicht für MeeriDEX abschalten. Mit Meldung und Version ein Problem melden. |
| **Speichern oder Sicherung schlägt fehl** | Freien Speicherplatz und Schreibrechte im Programmordner prüfen. Einen eigenen beschreibbaren Ordner verwenden; das Programm nicht innerhalb einer ZIP betreiben. Eine fehlgeschlagene Sicherung verhindert die automatische Updateinstallation. |
| **Nach einem manuellen Update fehlen Tiere oder Bilder** | Prüfen, ob die EXE versehentlich in einem neuen leeren Ordner gestartet wurde. Den ursprünglichen Ordner mit Datenbank und `Profil` verwenden. Nicht vorschnell Daten überschreiben oder eine leere Kartei über vorhandene Daten importieren. |
| **Update kann EXE nicht ersetzen** | Alle MeeriDEX-Fenster schließen und prüfen, ob eine zweite Instanz läuft. Schreibrechte und Virenschutzmeldung kontrollieren. Bei einer Fehlermeldung den genauen Text melden. |
| **Excel-Import wird abgewiesen** | Eine von MeeriDEX exportierte Arbeitsmappe verwenden. Tabellen-/Spaltennamen und Tier-IDs beibehalten; Formeln vor einem Import in feste Werte umwandeln. Ein beliebiges fremdes Tabellenformat wird nicht automatisch zugeordnet. |
| **Sync läuft in ein Zeitlimit / „Failed to connect“** | Den [WLAN-Sync-Abschnitt](#pc-und-app-synchronisieren) prüfen: offenes PC-Sync-Fenster, richtiges privates Netz, aktuelle IP und passende Firewallfreigabe sind erforderlich. |

### Hinweis zu Windows 7

> **Windows 7: ausschließlich mit Service Pack 1 und .NET Framework 4.8 verwenden. Ältere .NET-Versionen (z. B. 4.6.1 oder 4.7.x) werden für Windows 7 nicht unterstützt. Zusätzlich müssen Datum/Uhrzeit stimmen und die Windows-Stammzertifikate aktuell sein. Ohne diese Voraussetzungen können Installation, Online-Aktivierung und Updates scheitern. .NET 4.8.1 ist für Windows 7 nicht geeignet.**

MeeriDEX wird regulär unter Windows 10/11 geprüft. Der Fehler zur fehlenden `winsqlite3.dll` unter Windows 7 wird ab **1.7.2** durch eine eingebettete SQLite-Bibliothek vermieden. Das ist keine Zusage vollständiger Windows-7-Kompatibilität. Voraussetzung für Windows 7 ist Windows 7 SP1 mit [.NET Framework 4.8](https://support.microsoft.com/en-us/servicing/dotnetframework/2019/10/microsoft-net-framework-4-8-offline-installer-for-windows) verwenden; Aktivierung, Updates und Handy-Sync müssen auf dem tatsächlichen Rechner geprüft werden. Die produktive Kartei vorher sichern. Bei Fehlern Windows-Version, MeeriDEX-Version und den vollständigen Meldungstext angeben.

### Direkte Hilfe bei Laufzeitfehlern

Ab 1.7.3 zeigt MeeriDEX bei erkannten SQLite-Ladefehlern einen Hilfedialog mit Update-Verweis und kopierbaren technischen Details. Bei Hinweisen auf fehlende Framework-Funktionen oder Framework-Dateien und einer zu alten erkannten .NET-Laufzeit bietet er den offiziellen Microsoft-Download an. Eine fehlende `winsqlite3.dll` wird nicht pauschal als .NET-Problem eingeordnet; dafür MeeriDEX ab 1.7.2 verwenden. Fehlt .NET vollständig und Windows kann die EXE gar nicht starten, ist ein appinterner Dialog nicht möglich; dafür die Microsoft-Verknüpfung im ZIP-Paket oder den Download in dieser Anleitung verwenden.

Ab 1.7.4 öffnet eine fehlgeschlagene Online-Aktivierung einen Diagnose-Dialog mit Fehlerkategorie (Zertifikat, TLS, DNS, Timeout oder HTTP), ursprünglicher technischer Ursache, PC-Zeit und .NET-Version. Über „Details kopieren“ lassen sich diese zur Prüfung weitergeben. Der Bericht enthält keinen Lizenzcode, keine Namen und keine Tierdaten. Ein erfolgreicher Browsertest allein bestätigt nicht den Zertifikatszugriff von Windows/.NET.

## Android · Die Bande für unterwegs

### Android installieren – Schritt für Schritt

1. Diese GitHub-Seite **auf dem Android-Handy** öffnen und zum [Companion-Release](https://github.com/Coupe5E/MerriDex/releases/tag/companion-v0.8.13) wechseln.
2. **Assets** aufklappen und die Datei **`MeeriDex-Companion-0.8.5-test.apk`** laden. Nicht die `.sha256`-Datei und nicht „Source code“ wählen.
3. Die heruntergeladene APK über die Downloadmeldung oder die Dateien-App im Ordner **Downloads** öffnen.
4. Meldet Android, dass diese Quelle keine Apps installieren darf, über die angezeigten **Einstellungen** die Installation für genau den verwendeten Browser oder die Dateien-App erlauben. Die Einstellung heißt je nach Gerät **Unbekannte Apps installieren** oder **Aus dieser Quelle zulassen**; häufig unter **Einstellungen → Apps → Spezieller App-Zugriff**. Nur für eine bewusst gewählte vertrauenswürdige Quelle freigeben. Hersteller und Android-Version können andere Bezeichnungen verwenden.
5. Zur APK zurückkehren und **Installieren** wählen. Eine angebotene Sicherheitsprüfung abwarten. Beachte bei weiteren Meldungen den folgenden Abschnitt.
6. **MeeriDex Companion** öffnen. Für den QR-Scanner die Kameraberechtigung erteilen, wenn du ihn verwenden möchtest. Für den späteren Abgleich am PC das Sync-Fenster öffnen.
7. Die Installationsfreigabe für Browser/Dateien-App nach der Installation wieder entfernen, wenn sie nicht mehr benötigt wird.

**Spätere Updates:** Im App-Menü die Updateprüfung verwenden oder die neuere offizielle APK über die bestehende App installieren. Für die Installation eines aus Companion geladenen Updates kann Android die Quellenfreigabe für **MeeriDex Companion** selbst anfordern. Sie ersetzt nicht die Installationsbestätigung. **Die vorhandene App nicht vorher deinstallieren:** Deinstallation und „App-Daten löschen“ entfernen lokale Tiere, Fotos und interne Sicherungen. Vor einem Update möglichst erfolgreich mit dem PC synchronisieren und dort zusätzlich sichern.

### Android-Warnungen richtig einordnen

Die APK wird außerhalb des Google Play Stores angeboten und ist weiterhin eine lokal signierte Testversion. Ab 0.4.4 wird sie ohne Debuggerfreigabe gebaut; der bisherige App-Signierschlüssel bleibt für Updates erhalten. Je nach Browser, Hersteller und Sicherheitsprüfung können unterschiedliche Hinweise erscheinen. **Android stuft nicht jede APK außerhalb des Play Stores automatisch als gefährlich ein; eine solche Meldung lässt sich für diese App auch nicht allgemein ausschließen.**

| Meldung / Situation | Bedeutung und nächster Schritt |
| --- | --- |
| **Browser warnt, dass dieser Dateityp schädlich sein könnte** | Allgemeiner Hinweis für installierbare Dateien. Vor dem Herunterladen prüfen, dass du bei `github.com/Coupe5E/MerriDex` bist und die richtige APK gewählt hast. |
| **Installation aus dieser Quelle nicht erlaubt** | Die Quelle hat noch keine Installationsfreigabe. Das ist eine Berechtigung und keine Virendiagnose. Die gezielte Freigabe ist oben beschrieben. |
| **Unbekannte App / Prüfung empfohlen / App an Google senden** | Play Protect kann eine zusätzliche Prüfung einer bislang unbekannten App anbieten. Prüfung abwarten und Ergebnis beachten. Das ist etwas anderes als eine konkrete Schadsoftware-Erkennung. |
| **App als schädlich erkannt oder durch Play Protect blockiert** | Installation abbrechen und den genauen Meldungstext mit App-Version und Gerät melden. Play Protect nicht abschalten und die Warnung nicht pauschal umgehen. Nur die offizielle Datei verwenden; eine Prüfsumme bestätigt eine Dateiübereinstimmung, keine Schadsoftwarefreiheit. |
| **Installation durch Geräteverwaltung oder Hersteller blockiert** | Firmen-/Familiengeräte oder zusätzliche Geräteschutzfunktionen können APK-Installationen beschränken. Die zuständige Verwaltung bzw. Herstellerhilfe kontaktieren; ihre Vorgaben lassen sich durch die App nicht aufheben. |

Offizielle Hinweise: [Apps aus anderen Quellen herunterladen](https://support.google.com/android/answer/9457058?hl=de) und [Google Play Protect](https://support.google.com/googleplay/answer/2812853?hl=de). Zusätzliche [Android-Entwicklerbestätigungen](https://developer.android.com/developer-verification) können je nach Region und Systemstand weitere Schritte oder Einschränkungen bewirken; die einfache Quellenfreigabe löst nicht jede Installationssperre.

### Probleme in der App

| Problem | Was du prüfen kannst |
| --- | --- |
| **APK wird nicht geöffnet / „Paket konnte nicht analysiert werden“** | Android-Version prüfen: mindestens 8.0. Die APK vollständig erneut von der offiziellen Release-Seite laden und als APK öffnen; keine ZIP-/Prüfsummendatei auswählen. |
| **„App wurde nicht installiert“ / Update nicht möglich** | Freien Speicher und erlaubte Installationsquelle prüfen. Updates benötigen eine passende neuere Version mit derselben App-Signatur. Bei Signaturkonflikten nicht zur schnellen Lösung deinstallieren – erst Daten sichern bzw. synchronisieren und den Fehler melden. |
| **QR-Scanner bleibt ohne Bild** | Unter Android-Einstellungen → Apps → MeeriDex Companion → Berechtigungen die Kamera prüfen. Am PC einen frischen QR-Code im Sync-Fenster anzeigen; alternativ den Kopplungscode verwenden. |
| **Fotografieren funktioniert nicht** | Prüfen, ob eine Kamera-App vorhanden und nutzbar ist. Als Alternative ein bestehendes Bild über die Bildauswahl hinzufügen. Bei einem Fehler Gerätemodell und Meldung angeben. |
| **Handy-Abschluss fehlt / Dieselbe Revision enthält unterschiedliche Tierdaten** | Bei alten Profilen ohne RFID-Feld konnte Companion 0.4.1 den leeren PC-Standardwert fälschlich als Änderung ansehen. Auf Companion 0.4.2 aktualisieren und erneut synchronisieren; MeeriDEX 1.3.6 bleibt nutzbar. Die App nicht deinstallieren oder ihre Daten löschen. Echte Datenunterschiede werden weiterhin zurückgewiesen. |
| **Keine Verbindung zum PC** | Beide Geräte müssen sich lokal erreichen können. PC-Sync-Fenster offen lassen und die unten aufgeführten Netzwerkpunkte prüfen. Mobiles Internet allein verbindet nicht mit dem PC. |
| **Züchterprofil/Vorgaben sind veraltet** | Mindestens Desktop 1.3.3 und Companion 0.3.1 verwenden und erfolgreich synchronisieren. Eigene App-Vorgaben sind von der PC-Profilansicht getrennt; bereits gespeicherte Tiere werden durch neue Vorgaben nicht nachträglich geändert. |
| **Ein Tier fehlt in der Elternauswahl / Speichern wird abgewiesen** | Geschlecht und Geburtsdaten der Eltern prüfen. Unbekanntes Geschlecht wird nicht als Vater/Mutter vorgeschlagen. Bekannte Elterngeburtstage müssen vor dem Kind liegen. Bereits fehlerhafte Zuordnungen ausdrücklich korrigieren. |
| **Updateprüfung schlägt fehl** | Internetverbindung und GitHub-Erreichbarkeit prüfen; später erneut versuchen. Die lokale Tierverwaltung bleibt offline nutzbar. WLAN-Sync und Internet-Update sind unterschiedliche Verbindungen. |
| **Daten nach Deinstallation fehlen** | Android-Cloud-Backups sind für diese Testversion deaktiviert. Interne App-Sicherungen überstehen eine Deinstallation ebenfalls nicht. Nur ein zuvor synchronisierter PC-Bestand bzw. eine vorhandene eigene Sicherung kann noch helfen. |

## PC und App synchronisieren

1. PC und Handy mit demselben **privaten lokalen Netzwerk** verbinden; ein per LAN angeschlossener PC im selben Heimnetz ist ebenfalls möglich.
2. Am PC **Sync** öffnen. Falls nötig die passende lokale IP-Adresse auswählen und die angebotene **Netzwerkfreigabe** bestätigen. Windows fragt für die Einrichtung nach Administratorrechten; die normale Tierverwaltung benötigt sie nicht.
3. In der App oben links das Menü öffnen und **PC verbinden / QR-Code scannen** wählen. Den PC-QR-Code scannen oder den angezeigten Kopplungscode verwenden. Er gilt fünf Minuten.
4. Die neue Handy-Anfrage am PC bestätigen. Bei Konflikten oder Löschungen die Auswahl am PC sorgfältig prüfen: Es wird jeweils das vollständige Tierprofil ausgewählt, nicht jedes Feld einzeln gemischt.
5. Beide Abschlussmeldungen abwarten. Später am PC erneut **Sync** öffnen und in der App **Mit PC synchronisieren** wählen. Bei einem Abbruch erneut synchronisieren und mögliche Rückfragen beachten.

**Wenn keine Verbindung zustande kommt:**

- Das PC-Sync-Fenster muss während des Abgleichs geöffnet bleiben.
- Das vertrauenswürdige Heimnetz muss in Windows als **privat** eingestuft sein. MeeriDEX stellt dies nicht automatisch um.
- Die angebotene Firewallregel erlaubt nur die aktuelle EXE, **TCP-Port 47843**, private Netze und Geräte im lokalen Subnetz. Nach einem Umzug der EXE die Freigabe erneut prüfen.
- Kein Gast-WLAN mit Geräteisolation verwenden. VPNs und getrennte Netze können die direkte Verbindung verhindern; gegebenenfalls das normale gemeinsame Heimnetz verwenden.
- Bei geänderter PC-IP neu koppeln bzw. den frischen QR-Code scannen. Den QR-/Kopplungscode nur dem eigenen Handy zeigen.
- **Keine Router-Portweiterleitung einrichten:** Dieser Abgleich ist für das lokale Netz gedacht und benötigt keine Freigabe ins Internet.

Der Abgleich überträgt Tierprofile und Fotos in beide Richtungen verschlüsselt. Das Züchterprofil wird vom PC zur App übertragen; Verpaarungslisten und Programmeinstellungen werden nicht abgeglichen. Vor dem Speichern eines Abgleichs erstellt der PC ZIP- und Excel-Sicherungen. Trotzdem ersetzen Synchronisierung und interne Sicherungen keine zusätzliche Kopie auf einem anderen Datenträger.

## Eigene Tiere und Stammbaum richtig anlegen

**Deine eigenen Meeris gehören immer unter „Meine Meeris“ in den aktuellen Bestand.** Dort im Tierprofil über „Bearbeiten“ Mutter und Vater zuordnen. **Aus diesen Verknüpfungen entsteht der Stammbaum automatisch.** Unter „Stammbäume“ wird er angezeigt.

**„Tiere für den Stammbaum“ ist nur für Vorfahren und andere Tiere außerhalb deines aktuellen Bestands vorgesehen.** Eigene Tiere versehentlich dort angelegt? Unter „Stammbäume → Tiere für den Stammbaum“ das Tier auswählen und **„In Bestand übernehmen“** anklicken. Profil, Fotos und Familienverknüpfungen bleiben erhalten; das Tier muss nicht neu angelegt werden.

## Stammbaum als A4-PDF exportieren und drucken

Ab **1.9.19** stehen Rassengenetik und Farbcodes grundsätzlich in einer eigenen **Übersicht ab Seite 2**. Jedes bekannte Tier aus dem gewählten Stammbaum erhält einen Eintrag mit seinem Namen als Überschrift und beiden Angaben darunter. G-Nummern und entsprechende Kartenverweise entfallen. Wiederkehrende Tiere erscheinen einmal; unterschiedliche Tiere mit gleichem Namen bleiben getrennte Einträge. Fehlende Codes stehen als „nicht erfasst“ da. Die gespeicherten Profile werden beim Druck nicht verändert.

Die Reihenfolge lautet: Hauptblatt, Genetikübersicht(en), weitere Familienblätter. Alle Seitenzahlen und Anschlussverweise werden automatisch angepasst. Mit kurzen Codes passen 15 Tiere vollständig auf eine zweite Seite. Bei vielen Tieren oder langen Texten kommen zusätzliche Übersichtsseiten hinzu. Auch die kompakte Fünf-Generationen-Ausgabe erhält vollständige Einträge für alle bekannten Tiere. Lange Farbnamen nutzen auf dem Hauptblatt und den Vorfahrenkarten bis zu zwei Zeilen.

Links sind **„Blatt & Ahnen“** und **„Foto & Zucht“** getrennt. Der erste Bereich enthält Generationen und Ausgabeart, der zweite Fotoauswahl, Zuchtlogo und zusätzliche Adresszeile. Die Werkzeugleiste passt ihre Höhe an die Fensterbreite an, damit die Seitenauswahl erreichbar bleibt.

Andere nicht darstellbare Angaben nennen Tier, Tierkennung, Feld, Ahnenposition, einen Inhaltsauszug und die Zeichenanzahl oben in Rot. Der normale Bildschirm-Stammbaum verwendet jetzt dieselben rassen- und farbabhängigen Pixelbilder wie die Tierliste.


Ab **1.9.17** gibt es zusätzlich **5 Generationen kompakt** mit bis zu 31 Tieren auf einem Blatt. Entfernte Vorfahren haben kurze Karten mit Name, Geschlecht, Geburtstag, Rasse und Farbe. Alternativ stehen **5 oder 6 Generationen mit Folgeseiten** bereit: bei vollständigen Ahnen drei bzw. sieben Familienblätter mit Seitenzahlen und Anschlussverweisen, zusätzlich zu den Genetikübersichten. Die Anschlussseiten zeigen Vater- und Mutterlinien mit ihren zugehörigen Tieren; unbekannte Ahnen erzeugen keine leeren Zusatzseiten.

Die Seitenauswahl neben den Zoomknöpfen zeigt jedes Blatt einzeln. PDF und Druck geben alle Blätter aus. Auf der Hauptseite gilt die gewählte Foto-Option, auf Anschlussseiten steht das passende Pixel-Meeri beim jeweiligen Tier.

Fehler erscheinen oben in roter Schrift auf einem hellroten Hinweisfeld. Statt einer weißen Vorschau steht ein Hinweis auf den nächsten Schritt. Meldungen erklären zu lange Angaben, unlesbare Tierfotos und Logos, doppelte Geburtsgewichte und Tierkennungen sowie Kreise in der Abstammung. Fehlende normale Angaben und unbekannte Vorfahren bleiben erlaubt. Nach einer Korrektur die Vorschau aktualisieren; bei einem Foto-Problem gegebenenfalls „Foto auf diesem Blatt ausblenden“ wählen. Technische Details bleiben lokal unter `Diagnose/A4-Stammbaum-letzter-Fehler.txt`.


Ab **MeeriDEX 1.9.0** am Windows-PC unter **Stammbäume** ein Tier auswählen und **A4-Stammbaum / PDF** öffnen. Standard sind **vier Generationen inklusive des gewählten Tiers**: Tier, Eltern, Großeltern und Urgroßeltern. Für größere Schrift ist auch eine Dreigenerationen-Ausgabe möglich.

Oben stehen Zuchtname, Name, Ort, Telefon, E-Mail und Website aus dem Züchterprofil. Eine zusätzliche Adresszeile kann für den jeweiligen Export ergänzt werden. Der Kopf verwendet dein Züchterprofil; der Herkunftszüchter jedes Tiers steht separat bei dessen Daten. Abgabe-Empfänger werden nicht in den Stammbaum übernommen.

Beim gewählten Tier ein **hinterlegtes echtes Profilfoto auswählen** oder ein Foto aus einer Datei wählen. Das Foto wird vollständig eingepasst und nicht abgeschnitten; eine nur für den Export gewählte Datei verändert die Tierkartei nicht. Fehlt ein Foto, wird dies ausdrücklich angezeigt. Die Vorfahren verwenden die passenden Pixelbilder.

Enthalten sind Name, Geschlecht, Geburtstag, Rasse, Farbe, Herkunftszüchter, Geburtsgewicht, Wurfquote, Genetik-/Rassencode und Farbcode, soweit eingetragen. **Geburtsgewicht** wird nur aus einer Gewichtsmessung am tatsächlichen Geburtstag übernommen. Die **Wurfquote M/W/T** bezeichnet den Geburtswurf des jeweiligen Tiers, nicht dessen eigene späteren Würfe. Bei automatisch abgeleiteten Würfen bleiben unbekannte Totgeburten als **?** erkennbar; fehlendes Geschlecht ergibt **unvollständig**. Fehlende Angaben und Vorfahren werden nicht geraten.

**Als PDF speichern** erzeugt je nach Auswahl eine oder mehrere A4-Seiten im Hochformat als verlustfreies Bild-PDF mit **300 dpi**. Es benötigt keinen installierten PDF-Drucker und keine zusätzliche Laufzeit. Der Text ist im Bild-PDF nicht separat markierbar. Alternativ öffnet **Drucken** die Windows-Druckerauswahl. Für das PDF beim Ausdruck **A4 und tatsächliche Größe / 100 %** wählen. Eine Vorschau ist direkt im Exportfenster sichtbar.

Außergewöhnlich lange Angaben werden nicht still abgeschnitten: Bei zu umfangreichen Daten erscheint eine Meldung. Dann gegebenenfalls drei Generationen wählen oder die Angaben prüfen. Der Export verändert keine Tierdaten und ist auch im Lesemodus möglich. Die Druckfunktion ist zunächst in Windows verfügbar.

## Würfe auf PC und Android

Ab **MeeriDEX 1.8.0 / Companion 0.8.0** gibt es eine Wurfliste im gewohnten Pixelstil: am PC unter **Verpaarungen → Würfe**, auf Android im Menü **Würfe**.

- Eigene Würfe erscheinen automatisch aus **gleicher Mutter, gleichem Vater, gleichem Geburtsdatum und gleichem Geburtsort**, wenn der Ort zum **Züchterprofil / Zuchtort** passt. Groß-/Kleinschreibung und zusätzliche Leerzeichen spielen dabei keine Rolle. Beide Eltern müssen verknüpft sein. Auf Android gelten die eigenen beziehungsweise vom PC übernommenen Geburtsort-Vorgaben.
- Automatische Einträge werden aus den vorhandenen Tierprofilen abgeleitet und als **[Auto]** gekennzeichnet. Beim Bearbeiten und Speichern entsteht ein eigener Wurfeintrag. Fehlendes Geschlecht wird nicht geraten; entsprechende Tiere sind in den Notizen genannt und noch nicht als M/W zugeordnet.
- Die Quote **0/0/0** bedeutet **Männlich / Weiblich / Totgeburten**. Totgeburten sind aus den Profilen nicht ableitbar und müssen ergänzt werden. Ein später verstorbenes Jungtier bleibt in der ursprünglichen M/W-Geburtsbilanz.
- Würfe lassen sich auch manuell mit Mutter, optionalem Vater, Wurfdatum, Geburtsort und Notizen anlegen. Vorhandene Jungtiere können zugeordnet werden. Auf Wunsch werden fehlende lebend geborene Profile aus der Quote mit vorläufigen Namen und Elternverknüpfung angelegt. Anschließend die normalen Tierprofile öffnen und Namen, Fotos, Farbe usw. ergänzen. Totgeburten erzeugen keine automatischen Tierprofile.
- **Wurf aus Verpaarung** übernimmt den Bezug zur Gruppe. Bei mehreren Weibchen pro Gruppe jeden Wurf mit seiner tatsächlichen Mutter erfassen. Den wirklichen Trenntermin getrennt vom Geburtsdatum angeben. Auf Android stehen die PC-Verpaarungen nach einem Sync zur Verfügung; ohne vorherigen Sync ist eine manuelle Erfassung möglich.
- Gespeicherte Würfe gehören zur Historie der Mutter. SQLite, ZIP, Excel und WLAN übertragen die Daten und Jungtierzuordnungen. Konflikte betreffen das vollständige Tierprofil; unterschiedliche Trenntermine werden nicht still überschrieben. Für den Abgleich beide Programme aktualisieren. Das Löschen eines Wurfeintrags löscht keine Tierprofile und öffnet keine beendete Verpaarung erneut. Aus vorhandenen Profilen kann weiterhin ein automatischer Eintrag erscheinen.

## Abgabe: übernehmende Personen und Zuchten

Ab **MeeriDEX 1.8.1 / Companion 0.8.1** lassen sich bei einer Abgabe **Name, optionaler Zuchtname, Anschrift, Telefon, E-Mail und eine Notiz zur Abgabe** eintragen. Alle Angaben sind freiwillig; ältere Abgaben ohne Kontakt bleiben gültig. Der Zuchtname der übernehmenden Person ist von der Herkunftszucht des Tiers getrennt.

Am PC unter **Abgabe → Abgabedaten bearbeiten** erfassen oder beim Abgeben direkt ergänzen. Person und Zuchtname stehen in der Abgabeliste und können über **Tier / Person / Zucht** gesucht werden. Die vollständigen Angaben stehen im Tierprofil. **Zurück in Hauptliste** nimmt die Abgabe zurück und entfernt auch die zugehörigen Empfängerangaben.

Auf Android das Profil eines abgegebenen Tiers öffnen und **Übernehmende Person bearbeiten** wählen. Dort können die Kontaktdaten ergänzt oder geändert werden. Abgabedatum, Gewicht und Preis werden weiterhin am PC erfasst. Beim Drehen des Handys bleibt das offene Kontaktformular erhalten.

Die Angaben werden pro Tier gespeichert und über SQLite, ZIP, Excel und WLAN mitgenommen. Normale Profiländerungen erhalten sie. Beim Abgleich werden unterschiedliche Kontaktangaben als Profilkonflikt angezeigt. **Windows und Android gemeinsam aktualisieren**; ältere Versionen werden zum Update aufgefordert, bevor sie neue Kontaktangaben verlieren könnten.

## MeeriHimmel

Verstorbene Tiere können mit Todestag und optionaler Todesursache in MeeriHimmel aufgenommen werden. Profile, Fotos und Familienverknüpfungen bleiben erhalten. Windows und Android synchronisieren diese Angaben; dafür bitte beide Geräte auf Windows 1.6.0 und Companion 0.7.0 aktualisieren. Die Android-App bewahrt ungespeicherte Eingaben im MeeriHimmel-Dialog auch beim Drehen des Handys.

## Eigenes Zuchtlogo

Ab **MeeriDEX 1.9.1 / Companion 0.8.2** unter **Züchterprofil → Logo auswählen** ein eigenes Logo hinterlegen. **Am besten eine freigestellte PNG-Datei mit transparentem Hintergrund verwenden.** JPG und BMP werden ebenfalls angenommen, deren Hintergrund bleibt sichtbar. Das Programm stellt Bilder nicht automatisch frei.

Das Logo wird proportional auf höchstens 768 Pixel verkleinert und als PNG direkt im Profil gespeichert. Transparenz bleibt erhalten. Es erscheint in einer Ecke der Tierprofile und oben auf dem **A4-Stammbaum in PDF und Ausdruck**. Der Kopf zeigt das Logo deines Züchterprofils; es bezeichnet nicht automatisch den Herkunftszüchter des jeweiligen Tiers.

Mit **Profil speichern** werden Auswahl und Entfernung übernommen; **Abbrechen** verwirft die Änderung. Das Logo ist in der normalen ZIP-Sicherung enthalten. Nach einem erfolgreichen **WLAN-Sync** zeigt Android es im PC-Züchterprofil und auf den Tierprofilen. Auch das Entfernen wird übertragen. Das Logo wird am PC gepflegt; ältere Companion-Versionen zeigen es noch nicht an. Es wird nicht an den Lizenzdienst geschickt.

## Chipnummer prüfen und bei TASSO registrieren

Ab **MeeriDEX 1.9.2 / Companion 0.8.3** im Tierprofil **TASSO · Chip prüfen / registrieren** öffnen. Dort kannst du die **Chipnummer kopieren**, die [offizielle TASSO-Transponderabfrage](https://www.tasso.net/Tierregister/Transponderabfrage) öffnen und die Nummer im Browser einfügen. Auch ein Link zur [Registrierung](https://www.tasso.net/Tierregister/Tier-registrieren) und **Tierdaten für Anmeldung kopieren** sind vorhanden. Führende Nullen bleiben erhalten. Ungewöhnliche Nummernformate werden nur als Hinweis angezeigt; vorhandene Einträge werden nicht verändert.

Auch Meerschweinchen können bei TASSO registriert werden. Die Registrierung ist kostenlos; Chippen allein ersetzt sie nicht. TASSO nennt 15 Ziffern, selten 10 oder 12, für die Transpondernummer. Das Formular und das Abfrageergebnis bleiben auf TASSOs Webseite. MeeriDEX liest keinen Registrierungsstatus aus und behauptet nach einem Linkaufruf nicht, dass ein Tier registriert sei. Öffnen und Kopieren erfolgen jeweils erst nach dem zugehörigen Klick; Tier- und Halterdaten werden nicht automatisch übertragen.

**Keine automatische Registrierung und kein TASSO-Login in MeeriDEX:** Anmeldung und Passwort werden direkt bei TASSO eingegeben. TASSO bietet [TASSO.Connect](https://www.tasso.net/Tierregister/Fuer-Tieraerzte-Vereine-und-mehr/Fuer-Tieraerzte/TASSO-Connect) für angebundene Praxis- und Tierheimsoftware an. Für eine echte MeeriDEX-Anbindung müssten die Zulassung, die Schnittstellendokumentation und der benötigte aktivierte Registrierungsschlüssel mit TASSO geklärt werden. Ein gewöhnliches MeinTASSO-Konto ist hier noch keine aktivierte Schnittstelle.

## MeeriPro3-Datei oder ZIP übernehmen

Ab Windows 1.7.0 gibt es unter „Meine Meeris“ den eigenen Knopf „MeeriPro3 importieren“. Ab Windows 1.9.20 direkt die `.back3up`-Datei auswählen. Der zugehörige Bildordner muss daneben liegen, zum Beispiel `MeineZucht.back3up` und `MeineZucht._bilder`; die Fotos werden automatisch erkannt. Alternativ bleibt eine ZIP mit genau einer `.back3up` und ihrem Bildordner möglich. Fehlt der Bildordner, erscheint ein Hinweis vor der Übernahme; die Tierdaten lassen sich auch ohne Fotos importieren. Die Vorschau zeigt neue Tiere und mögliche Dubletten. Je Tier kann man neu anlegen, vorhandene Angaben behalten, bekannte Importwerte übernehmen oder den Eintrag auslassen. Elternverweise werden entsprechend zugeordnet; mehrdeutige Zuordnungen und Familienkreise müssen vor dem Speichern gelöst werden.

Bestehende Tiere und Verpaarungen bleiben erhalten. Vor dem Speichern werden automatisch Sicherungen angelegt. Unter `Importberichte` bleiben die Originalsicherung mit Bildern, vollständige Originaltabellen und die Importentscheidungen lokal erhalten. Beim Dateiimport werden die `.back3up` und zusätzlich ein ZIP-Archiv der Quelldateien aufbewahrt. Änderungen an Quelldateien während der Vorschau erfordern einen erneuten Importstart. Nicht automatisch abgebildete Zusatzdaten werden vor dem Übernehmen ausdrücklich genannt. Der MeeriPro3-Import benötigt kein Python. Namenlose Tiere erhalten einen eindeutigen Platzhalter wie „Unbenannt (MeeriPro3 u422)“ und einen Prüfhinweis. Fotos, Originalangaben und Abstammungsverknüpfungen bleiben erhalten; der tatsächliche Name kann anschließend ergänzt werden. Beim Übernehmen von Importwerten werden Farb-Bildzuordnung und strukturierte Genpaar-Auswahl mit dem neuen Eintrag abgeglichen; unveränderte Originalcodes bleiben erhalten. Companion prüft auch über WLAN empfangene Gewichtseinträge vor dem Speichern.

## Problem melden

Bitte ein [GitHub-Issue](https://github.com/Coupe5E/MerriDex/issues) mit diesen Angaben erstellen:

- **Anwendung und Version:** Desktop oder Companion, genaue Versionsnummer.
- **System:** Windows-/Android-Version; bei Android auch Hersteller und Modell.
- **Ablauf:** Welche Schritte führen zum Problem, was wurde erwartet und was passiert tatsächlich?
- **Meldung:** Genauen Fehlertext oder bereinigten Screenshot anfügen. Bei Installation angeben, ob Browser, Android-Installer, Play Protect oder ein Herstellerschutz die Meldung zeigt.
- **Beim Sync:** Beide Programmversionen und die Information, ob die Handy-Anfrage am PC erscheint.

Keine persönlichen Tierkarteien, Datenbanken, Kontaktdaten, Zugriffsschlüssel oder QR-/Kopplungscodes öffentlich posten. Falls ein Beispiel nötig ist, zunächst einen bereinigten Testfall beschreiben.

---


**Gewichte aus MeeriPro3:** Einzelne unplausible Messungen verhindern nicht die Übernahme der übrigen Tiere. Fehlende oder ungültige Datumsangaben, Messungen vor Geburt oder in der Zukunft, Gewichte außerhalb von über 0 bis 10000 g und zusätzliche Messungen am selben Tag werden mit Hinweis zur Nachprüfung erhalten. Die Originalwerte stehen in den Tiernotizen und im Importbericht; gültige Messungen werden ins Gewichtsarchiv übernommen. Es werden keine Datums- oder Gewichtswerte geraten.

*Stand: 04.11.2026 · MeeriDEX 1.9.34 / Companion 0.8.13.*


## Genetik verstehen und WurfOrakel

Ab **Windows 1.9.21 / Companion 0.8.7** ist eine gemeinsame Genetik-Hilfe enthalten. Am PC im WurfOrakel den Reiter **Genetik verstehen** öffnen oder im Rassengen-Editor den gleichnamigen Knopf verwenden. In Android steht der Knopf im Tierformular neben den Fell-/Farbangaben. Die Hilfe erläutert Allele, Trägergene, Genotyp/Phänotyp und Wahrscheinlichkeiten in eigenen Worten.

Das PC-WurfOrakel berechnet **Rn** zusätzlich als gesonderten Genort. Bei `Rnrn × Rnrn` ergibt das vereinfachte Modell 25 % `RnRn`; das ist keine feste Totgeburtenquote und keine sichere Aussage zum Überleben. Schimmel/Dalmatiner nicht miteinander verpaaren. Fehlende Rn-Angaben bleiben unbekannt; weiße Tiere werden nicht automatisch als `RnRn` eingestuft. Auch gespeicherte Vorlagen sind kein Genotypnachweis.

**Rh und M** werden zusätzlich gemeinsam ausgewertet. Die Modellgruppen zeigen mögliche Ausprägungen und bei unbekannten Eltern Unter-/Obergrenzen. Exakte Rosettenzahl, Lage und vollständige Rasse werden nicht vorhergesagt. Für `arat` erscheint eine differenzierte Erklärung zur Solidagouti-/Loh-Kombination. California, Dapple und weitere Zusatzfaktoren bleiben ausdrücklich unberechnet.

Fachlicher Abgleich: Andreas Reinert, *Meerschweinchen – Haltung – Zucht – Ausstellung*, vorliegendes Exemplar mit Copyright 2014, ISBN 978-3-88627-321-8, fotografierte Seiten 50–65 und 94–95; ergänzend [British Cavy Council: Cavy Genetics: An Exploration](https://www.britishcavycouncil.org.uk/Resources/Cavy%20Genetics%20Article%20October%202008%20rev%20A.pdf). Eine Auflagennummer wurde im vorliegenden Impressum nicht festgestellt. Buchseiten und Buchbilder werden nicht mitgeliefert. Bestehende Tierangaben bleiben erhalten.


## Rassen und Farben aus dem Standardabgleich

Ab Windows 1.9.22 / Companion 0.8.8 stehen Angora und Mohair sowie Tan/Loh Blau, Lux Blau, Otter Blau, Fox Blau und drei Brindle-Dalmatiner zur Auswahl. Angora nutzt vorläufig ein Peruanerbild und Mohair ein Alpakabild als Platzhalter; das Bild bestimmt keine Rasse. M und Satin bleiben in den neuen Rassevorlagen unbekannt.

Die Farbtabelle nennt ergänzende Quellenhinweise zum [EE-Standard 2024](https://entente-ee.eu/wp-content/uploads/EE-standard-D-2024.pdf) und [MCB-Standard](https://meerschweinchenclubbayern-mcb.de/infos/rassestandards/mcb-standard). Die Standards werden getrennt betrachtet. Zusätzliche Katalogmodelle sind keine automatische Anerkennung oder Bewertung eines einzelnen Tiers.

487 Farbauswahlen; die bisherigen Definitionen bleiben erhalten. Neue Vorlagen werden nur bei ausdrücklicher Auswahl übernommen. Eigene Gene bleiben individuell erfassbar. Schimmel/Dalmatiner nicht miteinander verpaaren.


## MeeriPro3-Farben und Pixelbilder

Ab Windows 1.9.23 / Companion 0.8.9 werden eindeutige importierte Farbnamen für die Katalog- und Bildauswahl verknüpft. Beispiele: Gold d.e., Weiß r.e., Schoko/Schokolade und Weiß/Weiss. Neue Importe speichern die erkannte Farb-ID; bereits importierte Tiere brauchen keinen erneuten Import, um die Anzeige zu nutzen. Beim normalen Bearbeiten und Speichern wird die Verknüpfung ebenfalls übernommen.

Die Originalfarbe und die Originalgenformel bleiben unverändert. Im Editor steht die erkannte Katalogfarbe für das Bild. Das ist kein Abgleich der Gene gegen eine allgemeine Vorlage. Eigene Genangaben bleiben geschützt; eine Farbvorlage ersetzt sie erst nach ausdrücklicher Auswahl und Bestätigung.

Unbekannte oder mehrdeutige Angaben wie bloß „Creme“ oder „Silber“ werden nicht automatisch geraten. Bei Bedarf die Farbtabelle öffnen und selbst wählen. Eine passende Katalogzuordnung garantiert noch kein besonderes Farbbild: Ohne vorhandenes Einzel- oder Gruppenbild bleibt das allgemeine Rassenbild.


## Wurfzeitraum nach dem Beenden einer Verpaarung

Ab Windows 1.9.24 bleibt die Geburtsschätzung bei beendeten Verpaarungen sichtbar. Käfigzeile und Tooltip zeigen das Fenster; nach Auswahl des Zeitraums steht es zusätzlich im Detailbereich. Der Beginn der Verpaarung und der tatsächliche Trenntermin bestimmen weiterhin das bestehende Schätzfenster. Beendet bezeichnet das Ende des Zusammensitzens, nicht das Ende einer möglichen Trächtigkeit. Die Anzeige bestätigt keine Trächtigkeit. Bei Kastratengruppen wird weiterhin keine automatische Geburtsschätzung ausgegeben.


## A4-Stammbaum anpassen

Im A4-Stammbaumfenster links **Blatt & Ahnen → Anpassungen** öffnen. Die Bereiche **Haupttier** und **Vorfahren** lassen sich unabhängig einstellen. **Blatt & Zucht** enthält die gemeinsamen Dokumentoptionen. Auf Familien-Folgeseiten verwendet auch die große obere Ahnenkarte die Vorfahren-Auswahl. Dort anhaken, was erscheinen soll: Geburtsgewicht, Gen-Code (Rassengenetik), Farb-Code (Farbgenetik), Wurfquote, Farbe, Rasse, Geschlecht, Geburtsdatum, Herkunftszucht, Züchterkopf, Kontaktdaten, Zuchtlogo, Hauptbild, Pixelbilder der Vorfahren und Legende/Fußzeile. Namen bleiben immer sichtbar.

**Übernehmen** aktualisiert die Vorschau und speichert die Auswahl lokal für den nächsten Ausdruck. **Abbrechen** lässt die bisherige Auswahl unverändert. **Alles anzeigen** setzt die Haken auf den vollständigen Umfang; anschließend Übernehmen wählen. Tierprofile und Züchterdaten werden dabei nicht verändert.

Die Auswahl gilt für PDF und Druck, für Vorfahren und für Folgeseiten. In kompakten Ansichten bleiben entfernte Vorfahren Kurzprofile. Wird nur ein Gen-Code gewählt, enthält das Beiblatt nur diesen. Sind beide Codes aus, entfallen die Beiblätter und die Seitenwahl wird angepasst. Ausgeblendete Bilder werden nicht geladen; ohne Hauptbild steht der Text über die gesamte Kartenbreite. Die konkrete Fotoauswahl bleibt unter **Foto & Zucht** erreichbar.

## Genstatus, Herkunft und Zucht-Favoriten

Ab Windows 1.9.26 / Companion 0.8.10 im Tierformular **Genstatus & Herkunft** öffnen. Je Genort erscheint „reinerbig laut Eintrag“, „mischerbig laut Eintrag“ oder „unbekannt“. Ein offenes Allel oder mehrere alternative Genotypen bleiben unbekannt. Das ist eine Einordnung gespeicherter Angaben und kein Nachweis aus dem Aussehen. K und Wd werden angezeigt, aber im WurfOrakel weiterhin nicht berechnet.

Optional je Genort eine Herkunft eintragen, etwa Züchterangabe oder Ableitung aus Nachkommen. Sie gilt für den damals eingetragenen Genotyp. Nach einer Änderung steht beim bisherigen Beleg „neu prüfen“; er wird nicht automatisch auf die neuen Gene übertragen. **Übernehmen** schließt den Dialog, **Tier speichern** speichert das Profil. Die Angaben bleiben in Sicherungen, Excel und im WLAN-Abgleich erhalten. Für ihren Abgleich beide Geräte aktualisieren; ältere Gegenstellen werden bei vorhandenen Herkunftsangaben abgehalten, damit nichts verloren geht.

Unter **Als Favorit speichern** eine Kombination aus Rasse, Farbe und Genangaben benennen. **Schnellauswahl** bietet die eigenen Vorlagen zum Übernehmen oder Entfernen an. Gleiche Namen können nach Rückfrage ersetzt werden. Maximal 100 Favoriten, jeweils auf dem verwendeten Gerät gespeichert. Sie werden nicht zwischen PC und Handy synchronisiert. Favoriten übertragen keine Namen, Eltern, Fotos oder individuellen Herkunftsbelege und gelten selbst nicht als Genotypnachweis.

Alle 40 bisherigen Formellücken im Katalog sind behandelt: 31 ergänzte Modellvorlagen, fünf Teilvorlagen und vier genetisch offene Weiß-Varianten. Unklare Gene werden als `__` geführt. Vorhandene Tiercodes werden nicht nachträglich verändert; neue Vorlagen werden ausdrücklich in der Farbtabelle gewählt.


## Weiß-Vorlagen und Stammbaum-Hinweise (1.9.27 / 0.8.11)

Die vier Weiß-Farben besitzen jetzt nutzbare **Modellvorlagen** statt ausschließlich unbekannter Gene:

| Farbe | Vorlage |
| --- | --- |
| Weiß, dunkle Augen | `__ bb crcr/crca ee P_ S_` |
| Weiß mit Pigment, dunkle Augen | `__ B_ crcr/crca ee P_ S_` |
| Weiß, rote Augen | `__ bb caca ee P_ S_` |
| Weiß mit Pigment, rote Augen | `__ B_ caca ee P_ S_` |

Basis ist das vereinfachte Zuchtmodell im [MCB-Standard](https://meerschweinchenclubbayern-mcb.de/infos/rassestandards/mcb-standard); die pigmentierten Varianten sind daraus abgeleitet. Die abweichenden C-Angaben für dunkeläugiges Weiß bleiben als Alternativen sichtbar. Rotäugig wird nicht automatisch mit `pp` gleichgesetzt. Das Modell erfasst nicht alle genetischen Weißursachen. A, D, Rn und unbekannte Trägergene bleiben offen. Insbesondere wird ein weißes Tier nicht automatisch als frei von verdecktem Schimmel eingestuft.

Vorhandene Tiercodes werden nicht überschrieben. Zum Übernehmen im Tierformular **Farbtabelle öffnen**, die gewünschte Weiß-Variante wählen, gegebenenfalls Ersetzen bestätigen und **Tier speichern**. Eigene abweichende Genangaben können beibehalten werden.

**Genstatus & Herkunft → Einfach erklärt** (Android: **Hilfe**) bietet Beispiele und eine Erklärung aller Eingaben. Herkunft bedeutet **Quelle der Genangabe**, etwa eine Züchterangabe. Das Feld ist freiwillig und hat nichts mit dem Geburtsort zu tun. `BB`/`bb` ist laut Eintrag reinerbig; `Bb` mischerbig; `B_`, `__` oder mehrere Alternativen bleiben unbestimmt. Dies gilt je Genort, nicht als pauschale Bestätigung für das ganze Tier. Gene werden im Tierformular bearbeitet; hier werden nur Quellennotizen ergänzt.

**Stammbaum-Hinweise:** Aus vorhandenen Genangaben der Eltern und weiterer Ahnen (bis zwölf Ebenen) werden mögliche Kombinationen im bestehenden Mendel-Modell berechnet. Beispiel: `BB × bb` lässt `Bb` zu. Unbekannte Angaben begrenzen nichts zusätzlich. Reine Rasse-, Farb- oder Favoritenvorlagen der Ahnen gelten ohne passende Quellennotiz nicht als individuelle Angabe. Eine passende Quellennotiz macht die Angabe verwendbar, bestätigt sie aber nicht automatisch fachlich.

Ein Widerspruch fordert zum Prüfen der Codes und Elternzuordnung auf; er beweist keine falsche Abstammung. Die Hinweise ändern weder Gene noch Quellen automatisch und berechnen keine Wahrscheinlichkeit. K/Wd bleiben außerhalb des WurfOrakels. „Übernehmen“ übernimmt Quellennotizen ins Formular; erst „Tier speichern“ speichert das Profil. Die Hilfe verwirft auf Android keine bereits eingegebenen Quellennotizen.


Die gemeinsame Bildsammlung enthält 169 zugeordnete Farbvarianten, darunter 35 neu eingebundene Motive vom 01.–04.11.2026. Windows und Android verwenden dieselben PNGs und Zuordnungen. Das Bild zum freien Namen „Brindle Blau-Creme“ ergänzt keine Katalogfarbe und keine Genformel.

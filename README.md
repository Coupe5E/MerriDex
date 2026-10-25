# MeeriDEX & MeeriDex Companion

Deine Meerschweinchenverwaltung im Pixel-Look: **MeeriDEX für Windows** für die vollständige Kartei und **MeeriDex Companion für Android** für Tierprofile und Fotos unterwegs. Beide speichern Tierdaten lokal und gleichen Tierprofile und Fotos im selben privaten WLAN ab. Windows ab 1.4.0 benötigt eine personalisierte Lizenz mit Online-Aktivierung; Android bleibt kostenlos. Der Lizenzdienst erhält keine Tierprofile oder Tierfotos.

> Aktuell: **MeeriDEX 1.9.2** und **Companion 0.8.3**. Companion ist eine **Android-Testversion** und steht deshalb als „Pre-release“ bei GitHub.

**Update-Hinweis für ältere Companion-Versionen:** APKs ab 0.5.2 überschreiten deren bisherige 100-MiB-Grenze und werden eventuell nicht angeboten. Die aktuelle Companion-Version einmalig über den APK-Download installieren, ohne die vorhandene App zu deinstallieren. Danach berücksichtigt die Updatesuche größere Bildpakete.

## Erweiterte Farben und Farbcodes

Ab **MeeriDEX 1.9.2 / Companion 0.8.3** enthält der gemeinsame Katalog **444 Einträge** (217 zusätzliche Auswahlen). Darunter **48 Brindle, 113 Schimmel/Buntschimmel, 65 Dalmatiner, 38 California und 10 Dapple**. Dalmatiner- und California-Einträge haben jetzt ebenfalls hinterlegte Modellformeln.

Neu sind unter anderem **Brindle Blau-Amber, Blau-Mandarine, Blau-Champagner und Blau-Weiß**, dazu weitere D-Verdünnungen und ihre Buntschimmel-Varianten. Blau mit **dd** bleibt von **Slate Blue** mit der P-Serie getrennt. Dalmatiner/Schimmel verwenden **Rnrn**, California **K_**, Dapple **wdwd**. Die Formeln sind Zuchtmodell-Vorlagen, kein Nachweis individueller Trägergene oder einer Vereinsanerkennung. Die zusätzlichen Faktoren bleiben im Tierprofil erhalten, werden im WurfOrakel aber ausdrücklich als **nicht berechnet** gekennzeichnet.

Dapple ist eine eigene Gruppe mit Schokoladenbasis, Weiß-, Gold-, Brindle- und Agoutikombinationen. Dapple wird nicht mit jeder Versilberung oder mit Schimmel gleichgesetzt. Mangels eindeutiger Grundlage sind blaue Dapple hier noch nicht als gesicherte Modellvorlage hinterlegt.

Bestehende Tierprofile werden durch das Update nicht überschrieben. Um einen neuen Katalogcode in ein vorhandenes Tier zu übernehmen, **Bearbeiten → Farbtabelle öffnen → passende Farbe auswählen → übernehmen → Tier speichern**. Eigene Farb- und Genangaben bleiben erhalten, solange sie nicht ausdrücklich ersetzt werden. Windows und Android verwenden denselben exportierten Katalog.

Für alle neuen Farben sind erweiterbare Bildgruppen hinterlegt. Vorhandene passende Gruppenbilder werden wiederverwendet; für noch nicht bebilderte Gruppen bleibt das allgemeine Rassenbild. Es wurden für dieses Update keine neuen Einzelbilder erzeugt. Die vollständigen Listen zusammengefasster Farben und fehlender Bilder wurden aktualisiert.

## Chipnummer prüfen und bei TASSO registrieren

Ab **MeeriDEX 1.9.2 / Companion 0.8.3** im Tierprofil **TASSO · Chip prüfen / registrieren** öffnen. Dort kannst du die **Chipnummer kopieren**, die [offizielle TASSO-Transponderabfrage](https://www.tasso.net/Tierregister/Transponderabfrage) öffnen und die Nummer im Browser einfügen. Auch ein Link zur [Registrierung](https://www.tasso.net/Tierregister/Tier-registrieren) und **Tierdaten für Anmeldung kopieren** sind vorhanden. Führende Nullen bleiben erhalten. Ungewöhnliche Nummernformate werden nur als Hinweis angezeigt; vorhandene Einträge werden nicht verändert.

Auch Meerschweinchen können bei TASSO registriert werden. Die Registrierung ist kostenlos; Chippen allein ersetzt sie nicht. TASSO nennt 15 Ziffern, selten 10 oder 12, für die Transpondernummer. Das Formular und das Abfrageergebnis bleiben auf TASSOs Webseite. MeeriDEX liest keinen Registrierungsstatus aus und behauptet nach einem Linkaufruf nicht, dass ein Tier registriert sei. Öffnen und Kopieren erfolgen jeweils erst nach dem zugehörigen Klick; Tier- und Halterdaten werden nicht automatisch übertragen.

**Keine automatische Registrierung und kein TASSO-Login in MeeriDEX:** Anmeldung und Passwort werden direkt bei TASSO eingegeben. TASSO bietet [TASSO.Connect](https://www.tasso.net/Tierregister/Fuer-Tieraerzte-Vereine-und-mehr/Fuer-Tieraerzte/TASSO-Connect) für angebundene Praxis- und Tierheimsoftware an. Für eine echte MeeriDEX-Anbindung müssten die Zulassung, die Schnittstellendokumentation und der benötigte aktivierte Registrierungsschlüssel mit TASSO geklärt werden. Ein gewöhnliches MeinTASSO-Konto ist hier noch keine aktivierte Schnittstelle.

## Eigenes Zuchtlogo

Ab **MeeriDEX 1.9.1 / Companion 0.8.2** unter **Züchterprofil → Logo auswählen** ein eigenes Logo hinterlegen. **Am besten eine freigestellte PNG-Datei mit transparentem Hintergrund verwenden.** JPG und BMP werden ebenfalls angenommen, deren Hintergrund bleibt sichtbar. Das Programm stellt Bilder nicht automatisch frei.

Das Logo wird proportional auf höchstens 768 Pixel verkleinert und als PNG direkt im Profil gespeichert. Transparenz bleibt erhalten. Es erscheint in einer Ecke der Tierprofile und oben auf dem **A4-Stammbaum in PDF und Ausdruck**. Der Kopf zeigt das Logo deines Züchterprofils; es bezeichnet nicht automatisch den Herkunftszüchter des jeweiligen Tiers.

Mit **Profil speichern** werden Auswahl und Entfernung übernommen; **Abbrechen** verwirft die Änderung. Das Logo ist in der normalen ZIP-Sicherung enthalten. Nach einem erfolgreichen **WLAN-Sync** zeigt Android es im PC-Züchterprofil und auf den Tierprofilen. Auch das Entfernen wird übertragen. Das Logo wird am PC gepflegt; ältere Companion-Versionen zeigen es noch nicht an. Es wird nicht an den Lizenzdienst geschickt.

## Stammbaum als A4-PDF exportieren und drucken

Ab **MeeriDEX 1.9.0** am Windows-PC unter **Stammbäume** ein Tier auswählen und **A4-Stammbaum / PDF** öffnen. Standard sind **vier Generationen inklusive des gewählten Tiers**: Tier, Eltern, Großeltern und Urgroßeltern. Für größere Schrift ist auch eine Dreigenerationen-Ausgabe möglich.

Oben stehen Zuchtname, Name, Ort, Telefon, E-Mail und Website aus dem Züchterprofil. Eine zusätzliche Adresszeile kann für den jeweiligen Export ergänzt werden. Der Kopf verwendet dein Züchterprofil; der Herkunftszüchter jedes Tiers steht separat bei dessen Daten. Abgabe-Empfänger werden nicht in den Stammbaum übernommen.

Beim gewählten Tier ein **hinterlegtes echtes Profilfoto auswählen** oder ein Foto aus einer Datei wählen. Das Foto wird vollständig eingepasst und nicht abgeschnitten; eine nur für den Export gewählte Datei verändert die Tierkartei nicht. Fehlt ein Foto, wird dies ausdrücklich angezeigt. Die Vorfahren verwenden die passenden Pixelbilder.

Enthalten sind Name, Geschlecht, Geburtstag, Rasse, Farbe, Herkunftszüchter, Geburtsgewicht, Wurfquote, Genetik-/Rassencode und Farbcode, soweit eingetragen. **Geburtsgewicht** wird nur aus einer Gewichtsmessung am tatsächlichen Geburtstag übernommen. Die **Wurfquote M/W/T** bezeichnet den Geburtswurf des jeweiligen Tiers, nicht dessen eigene späteren Würfe. Bei automatisch abgeleiteten Würfen bleiben unbekannte Totgeburten als **?** erkennbar; fehlendes Geschlecht ergibt **unvollständig**. Fehlende Angaben und Vorfahren werden nicht geraten.

**Als PDF speichern** erzeugt eine einzelne A4-Seite im Hochformat als verlustfreies Bild-PDF mit **300 dpi**. Es benötigt keinen installierten PDF-Drucker und keine zusätzliche Laufzeit. Der Text ist im Bild-PDF nicht separat markierbar. Alternativ öffnet **Drucken** die Windows-Druckerauswahl. Für das PDF beim Ausdruck **A4 und tatsächliche Größe / 100 %** wählen. Eine Vorschau ist direkt im Exportfenster sichtbar.

Außergewöhnlich lange Angaben werden nicht still abgeschnitten: Bei zu umfangreichen Daten erscheint eine Meldung. Dann gegebenenfalls drei Generationen wählen oder die Angaben prüfen. Der Export verändert keine Tierdaten und ist auch im Lesemodus möglich. Die Druckfunktion ist zunächst in Windows verfügbar.

## Eigene Tiere und Stammbaum richtig anlegen

**Deine eigenen Meeris gehören immer unter „Meine Meeris“ in den aktuellen Bestand.** Dort im Tierprofil über „Bearbeiten“ Mutter und Vater zuordnen. **Aus diesen Verknüpfungen entsteht der Stammbaum automatisch.** Unter „Stammbäume“ wird er angezeigt.

**„Tiere für den Stammbaum“ ist nur für Vorfahren und andere Tiere außerhalb deines aktuellen Bestands vorgesehen.** Eigene Tiere versehentlich dort angelegt? Unter „Stammbäume → Tiere für den Stammbaum“ das Tier auswählen und **„In Bestand übernehmen“** anklicken. Profil, Fotos und Familienverknüpfungen bleiben erhalten; das Tier muss nicht neu angelegt werden.

## Abgabe: übernehmende Personen und Zuchten

Ab **MeeriDEX 1.8.1 / Companion 0.8.1** lassen sich bei einer Abgabe **Name, optionaler Zuchtname, Anschrift, Telefon, E-Mail und eine Notiz zur Abgabe** eintragen. Alle Angaben sind freiwillig; ältere Abgaben ohne Kontakt bleiben gültig. Der Zuchtname der übernehmenden Person ist von der Herkunftszucht des Tiers getrennt.

Am PC unter **Abgabe → Abgabedaten bearbeiten** erfassen oder beim Abgeben direkt ergänzen. Person und Zuchtname stehen in der Abgabeliste und können über **Tier / Person / Zucht** gesucht werden. Die vollständigen Angaben stehen im Tierprofil. **Zurück in Hauptliste** nimmt die Abgabe zurück und entfernt auch die zugehörigen Empfängerangaben.

Auf Android das Profil eines abgegebenen Tiers öffnen und **Übernehmende Person bearbeiten** wählen. Dort können die Kontaktdaten ergänzt oder geändert werden. Abgabedatum, Gewicht und Preis werden weiterhin am PC erfasst. Beim Drehen des Handys bleibt das offene Kontaktformular erhalten.

Die Angaben werden pro Tier gespeichert und über SQLite, ZIP, Excel und WLAN mitgenommen. Normale Profiländerungen erhalten sie. Beim Abgleich werden unterschiedliche Kontaktangaben als Profilkonflikt angezeigt. **Windows und Android gemeinsam aktualisieren**; ältere Versionen werden zum Update aufgefordert, bevor sie neue Kontaktangaben verlieren könnten.

## Würfe auf PC und Android

Ab **MeeriDEX 1.8.0 / Companion 0.8.0** gibt es eine Wurfliste im gewohnten Pixelstil: am PC unter **Verpaarungen → Würfe**, auf Android im Menü **Würfe**.

- Eigene Würfe erscheinen automatisch aus **gleicher Mutter, gleichem Vater, gleichem Geburtsdatum und gleichem Geburtsort**, wenn der Ort zum **Züchterprofil / Zuchtort** passt. Groß-/Kleinschreibung und zusätzliche Leerzeichen spielen dabei keine Rolle. Beide Eltern müssen verknüpft sein. Auf Android gelten die eigenen beziehungsweise vom PC übernommenen Geburtsort-Vorgaben.
- Automatische Einträge werden aus den vorhandenen Tierprofilen abgeleitet und als **[Auto]** gekennzeichnet. Beim Bearbeiten und Speichern entsteht ein eigener Wurfeintrag. Fehlendes Geschlecht wird nicht geraten; entsprechende Tiere sind in den Notizen genannt und noch nicht als M/W zugeordnet.
- Die Quote **0/0/0** bedeutet **Männlich / Weiblich / Totgeburten**. Totgeburten sind aus den Profilen nicht ableitbar und müssen ergänzt werden. Ein später verstorbenes Jungtier bleibt in der ursprünglichen M/W-Geburtsbilanz.
- Würfe lassen sich auch manuell mit Mutter, optionalem Vater, Wurfdatum, Geburtsort und Notizen anlegen. Vorhandene Jungtiere können zugeordnet werden. Auf Wunsch werden fehlende lebend geborene Profile aus der Quote mit vorläufigen Namen und Elternverknüpfung angelegt. Anschließend die normalen Tierprofile öffnen und Namen, Fotos, Farbe usw. ergänzen. Totgeburten erzeugen keine automatischen Tierprofile.
- **Wurf aus Verpaarung** übernimmt den Bezug zur Gruppe. Bei mehreren Weibchen pro Gruppe jeden Wurf mit seiner tatsächlichen Mutter erfassen. Den wirklichen Trenntermin getrennt vom Geburtsdatum angeben. Auf Android stehen die PC-Verpaarungen nach einem Sync zur Verfügung; ohne vorherigen Sync ist eine manuelle Erfassung möglich.
- Gespeicherte Würfe gehören zur Historie der Mutter. SQLite, ZIP, Excel und WLAN übertragen die Daten und Jungtierzuordnungen. Konflikte betreffen das vollständige Tierprofil; unterschiedliche Trenntermine werden nicht still überschrieben. Für den Abgleich beide Programme aktualisieren. Das Löschen eines Wurfeintrags löscht keine Tierprofile und öffnet keine beendete Verpaarung erneut. Aus vorhandenen Profilen kann weiterhin ein automatischer Eintrag erscheinen.

## Downloads und Schnellstart

> **Windows 7: ausschließlich mit Service Pack 1 und .NET Framework 4.8 verwenden. Ältere .NET-Versionen (z. B. 4.6.1 oder 4.7.x) werden für Windows 7 nicht unterstützt. Zusätzlich müssen Datum/Uhrzeit stimmen und die Windows-Stammzertifikate aktuell sein. Ohne diese Voraussetzungen können Installation, Online-Aktivierung und Updates scheitern. .NET 4.8.1 ist für Windows 7 nicht geeignet.**

| Anwendung | Download | Voraussetzung |
| --- | --- | --- |
| Windows-PC | [Aktuelle Desktop-Version](https://github.com/Coupe5E/MerriDex/releases/latest) – `MeeriDEX.exe` oder `MeeriDEX-Testversion.zip` | Windows 10/11; Windows 7 nur mit SP1, .NET Framework 4.8 und aktuellen Stammzertifikaten (siehe Hinweis); SQLite ist enthalten |
| Android | [Aktuelle Companion-Testversion](https://github.com/Coupe5E/MerriDex/releases/tag/companion-v0.8.3) – `MeeriDex-Companion-0.8.3-test.apk` unter **Assets** | Android 8.0 oder neuer |

Die Datei `.sha256` enthält eine Prüfsumme und ist kein Installationsprogramm. GitHubs „Source code“-ZIPs enthalten nur die öffentlichen Repository-Hinweise und sind ebenfalls keine Programmpakete.

**Direkt zur Hilfe:** [.NET installieren](#net-framework-kostenlos-nachinstallieren) · [Desktop installieren](#desktop-installieren-und-aktualisieren) · [Windows-SmartScreen](#windows-smartscreen-beim-download-oder-start) · [Desktop-Probleme](#probleme-am-pc) · [Android installieren](#android-installieren--schritt-für-schritt) · [Android-Warnungen](#android-warnungen-richtig-einordnen) · [App-Probleme](#probleme-in-der-app) · [WLAN-Sync](#pc-und-app-synchronisieren) · [Problem melden](#problem-melden)

## MeeriDEX für Windows

### Funktionen

| Bereich | Was du damit machen kannst |
| --- | --- |
| **Meine Meeris** | Tiere anlegen, suchen, bearbeiten und mit Name, Geschlecht, Geburtstag, Geburtsort, Züchter, Notizen und Kastrationsangaben verwalten. |
| **Lizenz & Aktivierung** | Windows ab 1.4.0: manuell vergebene Dauerlizenz oder 15-Tage-Testlizenz, gebunden an Vorname, Nachname und Zuchtname. Zwei PCs sind gleichzeitig nutzbar. Testtage beginnen mit der ersten Aktivierung und gelten gemeinsam für beide PCs. Online aktivieren und spätestens alle 30 Tage erneut prüfen; Tests höchstens bis Testende. Ohne gültige Bestätigung bleiben Lesen und ZIP-/Excel-Export möglich. Android bleibt kostenlos. |
| **Pixel-Meeris** | 16 Rassenbilder einschließlich Skinny und 72 zusätzliche Farbvarianten. Neu sind je vier Brindle-/Schimmelbilder für English Crested, CH-Teddy, Coronet, Peruaner und Lunkarya. PC und App nutzen dieselben Zuordnungen für exakte Farben und 103 Farbgruppen; ein exaktes Bild hat Vorrang, ähnliche Farben können ein Gruppenbild derselben Rasse verwenden. Ohne passende Variante bleibt das Rassenbild, ohne bekannte Rasse Ryo. Die Illustration ist ein Beispiel und kein exakt rekonstruiertes Tierfoto. |
| **RFID-Chipnummer** | Eine optionale Chipkennung als Text speichern, im Profil nachlesen und danach suchen. Führende Nullen bleiben erhalten. Der Abgleich mit Companion und Excel enthalten das Feld; zum Sync von Chipnummern Desktop ab 1.3.6 und Companion ab 0.4.1 verwenden. Das Feld erfasst die Kennung und liest keinen Chip mit dem Handy aus. |
| **Fotos und Tierprofile** | Mehrere Bilder hinterlegen und im Profil Stammdaten, Familie, Gewicht und Krankenverlauf ansehen. Fotos werden für die Kartei verkleinert; ausgewählte Originaldateien bleiben unverändert. |
| **Rassen, Farben und Gene** | Rassen- und Farbvorlagen auswählen, Farbcodes erklären lassen sowie eigene Angaben und bekannte Trägergene erfassen. Vorlagen sind kein Nachweis des individuellen Genotyps. |
| **Familie und Stammbäume** | Mutter, Vater und Geschwister verknüpfen. Stammbäume über drei bis sechs Generationen anzeigen, verschieben und zoomen; Tierprofile direkt daraus öffnen. |
| **Ryo denkt mit · Erinnerungen** | Merkzettel für Wiegen, Medikamente, Kontrollen und eigene Aufgaben mit Termin, Wiederholung und Notizen anlegen, abhaken und auf morgen verschieben. Mit Companion ab 0.5.0 synchronisieren; ZIP und Excel sichern die Einträge mit. Hinweise erscheinen tageweise im geöffneten Erinnerungsbereich, ohne Hintergrundalarme bei geschlossener Anwendung. |
| **Gewichtsverlauf** | Messdatum und Gewicht erfassen, frühere Messungen bearbeiten und den Verlauf als Diagramm betrachten. |
| **Pixel-Käfige** | Käfige aufklappen und Tierkarten mit Namen sowie Pixelbildern passend zu Rasse und Farbe ansehen. Geschlecht und Kastration stehen direkt auf den Tierkarten. Filter lassen sich einklappen; Details erscheinen bei Auswahl. |
| **Verpaarungen** | Gruppen mit Käfig, Tieren, Start- und Enddatum planen und verwalten. Geplante, laufende und beendete Gruppen filtern; geschätzte Geburtstermine aus den Zeiträumen ansehen. |
| **Abgabe** | Ausgezogene Tiere mit Abgabedatum, optionalem Gewicht und Verkaufspreis erfassen. Monatliche eingetragene Verkaufssummen ansehen; Familienbeziehungen bleiben erhalten. Die Summe stellt Einnahmen und keinen Gewinn dar. |
| **WurfOrakel** | Mögliche Genpaare des Nachwuchses anhand gespeicherter Farb- und Fellgene betrachten. Unvollständige Angaben führen zu Spannen; nicht alle genetischen Faktoren werden berechnet. Das Ergebnis bestätigt weder eine Gesamtfarbe noch die gesundheitliche Eignung einer Verpaarung. |
| **Krankenstation** | Befunde, Verdachtsfälle, Diagnosestand, Praxis, Behandlung und Krankheitsverlauf dokumentieren. Familienübersicht und Befundsuche unterstützen den Vergleich; sie stellen keine Diagnose und keinen Nachweis einer Erbkrankheit dar. |
| **Züchterprofil** | Zuchtname, Ort, Kontaktangaben und soziale Links pflegen. Zuchtname und Ort werden für neue Tiere vorbelegt; das Profil wird beim Sync zur Ansicht an die App übertragen. |
| **Sicherung und Excel** | Sicherungen exportieren/importieren und Tierdaten einschließlich Fotos, Gewichten, Familien, Genen und Verpaarungen als Excel-Datei austauschen. Ein Import ersetzt die Kartei nach Vorschau und Bestätigung. Züchterprofil und Einstellungen sind separat zu sichern. |
| **Updates und Datenübernahme** | Updates über GitHub prüfen. Vor einem installierten Programmupdate entstehen eine ZIP-Sicherung und ein Excel-Export. Alte JSON-Tierdaten werden beim ersten Start der SQLite-Version automatisch übernommen. |
| **So geht’s** | Kurze Anleitungen für alle sechs Hauptbereiche in einer pixeligen Sprechblase mit Ryo, eingebetteter Pixelschrift und scrollbar lesbaren Absätzen. |
| **Companion-Sync** | Tierprofile und Fotos mit Android abgleichen; Konflikte und Löschungen am PC bestätigen. |

Das X in der Lizenzabfrage beendet den Programmstart. Über **Nur lesen / Sicherungen exportieren** lässt sich die Kartei ausdrücklich im Lesemodus öffnen; Speichern, Import und WLAN-Abgleich benötigen eine gültige Lizenz.

### Desktop installieren und aktualisieren

1. Auf der [Desktop-Release-Seite](https://github.com/Coupe5E/MerriDex/releases/latest) unter **Assets** die EXE oder das Programmpaket herunterladen.
2. Bei der ZIP-Datei zuerst **alles entpacken**. Einen eigenen beschreibbaren Ordner nutzen, zum Beispiel im Benutzerordner. Das Programm legt seine Daten neben der EXE ab; nicht direkt aus der ZIP starten.
3. `MeeriDEX.exe` öffnen. Ab Version 1.4.0 unter **Lizenz / Aktivierung** Vorname, Nachname, Zuchtname und den erhaltenen Lizenzschlüssel eintragen und online aktivieren; anschließend das Züchterprofil vervollständigen. Die aktivierte Tierverwaltung funktioniert bis zum angezeigten Prüftermin offline. Internet wird zur Aktivierung, spätestens nach 30 Tagen zur erneuten Lizenzprüfung und für GitHub-Updates benötigt; der Handyabgleich benötigt das lokale Netz.
4. Für spätere Updates **Updates prüfen** im Programm verwenden. Beim manuellen Austausch MeeriDEX zuerst schließen und den gesamten bisherigen Programmordner zusätzlich sichern. Die EXE am bisherigen Ort ersetzen, damit die vorhandenen Daten dort gefunden werden.

**Daten aufbewahren:** `meeridex.sqlite` enthält die Tierkartei; `Profil` enthält unter anderem Züchterangaben und Tierfotos. Im Ordner `Sicherungen` liegen zusätzliche Backups. Für einen Umzug den gesamten Programmordner bei geschlossenem Programm kopieren. Die EXE allein enthält keine Tierkartei.

### .NET Framework kostenlos nachinstallieren

Falls MeeriDEX wegen einer fehlenden .NET-Laufzeit nicht startet: **[Offiziellen .NET Framework 4.8 Offline-Installer bei Microsoft herunterladen](https://dotnet.microsoft.com/en-us/download/dotnet-framework/thank-you/net48-offline-installer)**.

1. Den Microsoft-Installer herunterladen und MeeriDEX schließen.
2. Den Installer starten und die Windows-Abfrage nach Administratorrechten bestätigen. Benötigt wird die **Runtime**, kein Developer Pack und keine moderne „.NET Desktop Runtime“.
3. Nach der Installation neu starten, falls der Installer dazu auffordert, und anschließend `MeeriDEX.exe` öffnen.

Auf Windows 10/11 ist eine passende Laufzeit häufig bereits vorhanden. Wenn bereits eine neuere passende .NET-Framework-4.x-Version vorhanden ist, muss sie nicht ersetzt werden. Für **Windows 7 SP1** ist **4.8** vorgesehen, **nicht 4.8.1**. Die frühere `winsqlite3.dll`-Meldung wird durch MeeriDEX ab **1.7.2** behoben; eine .NET-Installation allein ersetzt diese Korrektur nicht.

Programmpakete ab 1.7.3 enthalten zusätzlich `NET-Framework-4.8-herunterladen.url` und `NET-Framework-Hilfe.txt`. Der Verweis führt direkt zum Microsoft-Download; der Installer wird nicht automatisch gestartet.

### Windows-SmartScreen beim Download oder Start

Die aktuelle Windows-Version von MeeriDEX ist **noch nicht digital signiert**. Bei einer neuen oder wenig verbreiteten Datei können Microsoft Edge und Windows deshalb eine Warnung zu einer unbekannten Anwendung anzeigen. Eine Signatur-/Reputationswarnung ist von einer konkreten Schadsoftware-Erkennung zu unterscheiden.

1. MeeriDEX ausschließlich von den [offiziellen GitHub-Releases dieses Projekts](https://github.com/Coupe5E/MerriDex/releases/latest) herunterladen. Unter **Assets** für die Erstinstallation `MeeriDEX-Testversion.zip` auswählen; `Source code` und `.sha256` sind keine Installationspakete.
2. Falls Edge den Download als selten heruntergeladen meldet: Im Downloadmenü bei der Datei **…** öffnen. Wenn angeboten, **Beibehalten** und anschließend **Mehr anzeigen → Trotzdem beibehalten** wählen – erst nachdem Herkunft und genaue Warnung geprüft wurden. Die Bezeichnungen können je nach Edge-Version abweichen.
3. Die ZIP mit Rechtsklick → **Alle extrahieren** in einen eigenen beschreibbaren Ordner, zum Beispiel unter **Dokumente**, entpacken. Dort `MeeriDEX.exe` starten.
4. Erscheint beim Start die SmartScreen-Meldung **„Der Computer wurde durch Windows geschützt“** wegen einer unbekannten App, auf **Weitere Informationen** klicken. Wenn du dem Download aus diesem Projekt vertraust und die Option angeboten wird, **Trotzdem ausführen** wählen.
5. Beim ersten Start unter **Lizenz / Aktivierung** Vorname, Nachname, Zuchtname und Lizenzcode eingeben. Alle Angaben müssen zur ausgestellten Lizenz passen; zur Aktivierung ist Internet erforderlich.

**Andere Sicherheitsmeldung oder keine Fortsetzungsoption?** Den genauen Meldungstext beziehungsweise einen Screenshot und die MeeriDEX-Version melden. Bei einer konkreten Virenerkennung nicht nach dieser Anleitung fortfahren. Smart App Control oder verwaltete Geräte können andere Sperren anzeigen. Windows-Schutzfunktionen müssen für diese Anleitung nicht abgeschaltet werden.

[Microsoft: Wie SmartScreen die Bekanntheit von Anwendungen bewertet](https://learn.microsoft.com/en-us/windows/apps/package-and-deploy/smartscreen-reputation)

### Probleme am PC

| Problem | Was du prüfen kannst |
| --- | --- |
| **Meldung zu fehlendem .NET Framework / Programm startet nicht** | Windows aktualisieren und die passende **.NET Framework 4.x-Laufzeit** von Microsoft prüfen/installieren, beispielsweise 4.8 oder 4.8.1 passend zur Windows-Version. Neuere Windows-Versionen enthalten sie bereits. Das ist ein anderes Produkt als die moderne „.NET Desktop Runtime“. [Microsoft-Anleitung](https://learn.microsoft.com/de-de/dotnet/framework/install/on-windows-10). |
| **`winsqlite3.dll` fehlt** | Ab **1.7.2** enthält die EXE ihre eigene SQLite-Bibliothek; `winsqlite3.dll` muss nicht mehr vorhanden sein. Eine ältere MeeriDEX-Version durch die aktuelle EXE ersetzen, dabei den Datenordner behalten. Keine einzelnen DLLs von fremden Downloadseiten beziehen. Bei weiterem Fehler den vollständigen Meldungstext melden. |
| **Muss ich Java, Office oder Datenbankwerkzeuge nachinstallieren?** | Nein. Java, Python, Android Studio und ein separater SQLite-/SQL-Server werden für die Nutzung nicht benötigt. Excel muss für Import und Export nicht installiert sein; zum Ansehen einer XLSX-Datei ist ein kompatibles Tabellenprogramm nötig. |
| **Windows oder Virenschutz warnt vor dem Download** | Eine unbekannte oder wenig verbreitete EXE kann einen Hinweis auslösen. Das allein sagt nicht, dass sie schädlich ist. Herkunft und genaue Meldung prüfen; eine konkrete Virenerkennung nicht pauschal ignorieren und den Virenschutz nicht für MeeriDEX abschalten. Mit Meldung und Version ein Problem melden. |
| **Speichern oder Sicherung schlägt fehl** | Freien Speicherplatz und Schreibrechte im Programmordner prüfen. Einen eigenen beschreibbaren Ordner verwenden; das Programm nicht innerhalb einer ZIP betreiben. Eine fehlgeschlagene Sicherung verhindert die automatische Updateinstallation. |
| **Nach einem manuellen Update fehlen Tiere oder Bilder** | Prüfen, ob die EXE versehentlich in einem neuen leeren Ordner gestartet wurde. Den ursprünglichen Ordner mit Datenbank und `Profil` verwenden. Nicht vorschnell Daten überschreiben oder eine leere Kartei über vorhandene Daten importieren. |
| **Update kann EXE nicht ersetzen** | Alle MeeriDEX-Fenster schließen und prüfen, ob eine zweite Instanz läuft. Schreibrechte und Virenschutzmeldung kontrollieren. Bei einer Fehlermeldung den genauen Text melden. |
| **Excel-Import wird abgewiesen** | Eine von MeeriDEX exportierte Arbeitsmappe verwenden. Tabellen-/Spaltennamen und Tier-IDs beibehalten; Formeln vor einem Import in feste Werte umwandeln. Ein beliebiges fremdes Tabellenformat wird nicht automatisch zugeordnet. |
| **Sync läuft in ein Zeitlimit / „Failed to connect“** | Den [WLAN-Sync-Abschnitt](#pc-und-app-synchronisieren) prüfen: offenes PC-Sync-Fenster, richtiges privates Netz, aktuelle IP und passende Firewallfreigabe sind erforderlich. |

## MeeriDex Companion für Android

### Funktionen

| Bereich | Was du damit machen kannst |
| --- | --- |
| **Tierliste im Pixel-Look** | Deine Tiere mit Pixel-Meeri passend zu Rasse und unterstützter Farbkombination, Name und Geschlecht sehen. Über das Menü oben links neue Tiere anlegen, suchen, synchronisieren und Updates prüfen. |
| **Schnell wiegen** | Direkt aus der Liste oder dem Profil Messtag und Gramm speichern, letzte Messung und Unterschied sehen. Der Geburtstag wird für die Altersberechnung benötigt. |
| **Filter und Favoriten** | Bestand, Stammbaumtiere oder abgegebene Tiere anzeigen und mit Rasse, Farbe, Geschlecht, Suche und Favoriten kombinieren. Favoriten stehen oben und bleiben als persönliche Auswahl auf dem Handy. |
| **Mobiler Stammbaum** | Drei Generationen mit Eltern und Großeltern im Profil ansehen; antippen öffnet das jeweilige Tierprofil. |
| **Sync-Übersicht** | Vor dem Speichern den Übernahmeplan bestätigen oder abbrechen. Mit Desktop 1.5.5 zeigt er Profile, Löschungen und neue Fotos für beide Geräte. Abschluss und letzter bestätigter Sync sind nachlesbar. |
| **Tierprofile** | Stammdaten, RFID-Chipnummer, Geburtstag, Geburtsort, Züchter, Rasse, Farbe, Codes, Eltern, Kastration und Notizen anlegen oder bearbeiten. |
| **Gewicht & Alter** | Aktuelles Gewicht und kleine Verlaufsgrafik ansehen. Messdatum und Gramm erfassen, Messungen korrigieren oder entfernen. Änderungen erst mit Verlauf speichern übernehmen. Gewichte werden mit dem PC synchronisiert. |
| **Familie und weitere Profildaten** | Eltern, Geschwister und Kinder mit direkt aufrufbaren Profilen ansehen. Vorhandene Abgabedaten und Krankenverläufe vom PC nachlesen; deren Bearbeitung bleibt am PC. |
| **Kamera und Fotos** | Direkt im Profil mit der Handykamera ein Foto aufnehmen und zuordnen oder im Bearbeiten-Modus ein Profilfoto aufnehmen oder vorhandene Bilder auswählen; mehrere Bilder pro Tier verwalten. Für das Fotografieren wird die Kamera-App verwendet, der QR-Scanner hat eine eigene Kameraansicht. |
| **Farbtabelle und Rassengene** | Dieselben Rassen- und Farbvorgaben wie am PC nutzen. Große Farbmuster, Suche und Gruppenfilter erleichtern die Auswahl; erst „Übernehmen“ trägt die Farbe ein. Eigene Angaben bleiben möglich. |
| **Prüfung der Eingaben** | Nur Weibchen als Mutter und Böcke als Vater auswählen. Kastration erscheint nur bei Böcken. Datumsangaben, Familienkreise und die Konsistenz von Vorlagen und Codes werden beim Speichern geprüft. Historisch kastrierte Väter bleiben möglich. Das ist keine vollständige genetische Vererbungsberechnung. |
| **Züchterprofil und Vorgaben** | Das aktuelle PC-Züchterprofil nach dem Sync ansehen. Zuchtname und Geburtsort für neue Tiere vom PC übernehmen oder eigene App-Vorgaben nutzen. Änderungen am vollständigen Züchterprofil erfolgen am PC. |
| **Offline und WLAN** | Tiere und Fotos lokal auf dem Handy speichern und später im selben privaten WLAN mit dem PC abgleichen. |
| **GitHub-Updates** | Neue Companion-APKs über die App finden und laden. Android fragt vor der eigentlichen Installation nochmals nach. |

**Umfang der Testversion:** Grafische Stammbäume und Verpaarungsverwaltung werden weiterhin am Desktop bedient. Abgabedaten und Krankenverläufe sind in der App zur Ansicht verfügbar; ihre Bearbeitung erfolgt am PC. Gewichtserfassung und Verlauf sind ab Companion 0.4.0 auch auf dem Handy möglich. Vorhandene zusätzliche PC-Felder im Tierprofil bleiben beim Bearbeiten in Companion erhalten. Die App ist derzeit weder eine iPhone-App noch eine Play-Store-Veröffentlichung.

### Android installieren – Schritt für Schritt

1. Diese GitHub-Seite **auf dem Android-Handy** öffnen und zum [Companion-Release](https://github.com/Coupe5E/MerriDex/releases/tag/companion-v0.8.3) wechseln.
2. **Assets** aufklappen und die Datei **`MeeriDex-Companion-0.8.3-test.apk`** laden. Nicht die `.sha256`-Datei und nicht „Source code“ wählen.
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

## Problem melden

Bitte ein [GitHub-Issue](https://github.com/Coupe5E/MerriDex/issues) mit diesen Angaben erstellen:

- **Anwendung und Version:** Desktop oder Companion, genaue Versionsnummer.
- **System:** Windows-/Android-Version; bei Android auch Hersteller und Modell.
- **Ablauf:** Welche Schritte führen zum Problem, was wurde erwartet und was passiert tatsächlich?
- **Meldung:** Genauen Fehlertext oder bereinigten Screenshot anfügen. Bei Installation angeben, ob Browser, Android-Installer, Play Protect oder ein Herstellerschutz die Meldung zeigt.
- **Beim Sync:** Beide Programmversionen und die Information, ob die Handy-Anfrage am PC erscheint.

Keine persönlichen Tierkarteien, Datenbanken, Kontaktdaten, Zugriffsschlüssel oder QR-/Kopplungscodes öffentlich posten. Falls ein Beispiel nötig ist, zunächst einen bereinigten Testfall beschreiben.

## Ein Gürkchen für MeeriDex

MeeriDex gefällt dir? Über **Gürkchen spendieren** kannst du die Weiterentwicklung freiwillig mit [PayPal](https://paypal.me/SaschaGau) unterstützen. Den Knopf findest du am PC in der Knopfleiste und in Companion im Seitenmenü direkt unter **Updates prüfen**. Betrag und Zahlung bestätigst du selbst bei PayPal.

## Closed Source

MeeriDEX und MeeriDex Companion werden als **Closed Source** veröffentlicht. Dieses öffentliche Repository dient Downloads, Updates und Hinweisen; die eigenen Programmquellen bleiben privat. Alte Releases und die veröffentlichten Quellcode-ZIPs wurden entfernt.

Copyright (c) 2026 Coupe5E. Alle Rechte vorbehalten. MeeriDEX für Windows ab 1.4.0 benötigt eine gültige personalisierte Lizenz; MeeriDex Companion für Android bleibt kostenlos. Es wird keine Open-Source-Lizenz für die eigenen Programmquellen oder Grafiken erteilt. Zwingende gesetzliche Rechte bleiben unberührt. Siehe `LIZENZ.txt` in den aktuellen Releases; Lizenzen enthaltener Komponenten Dritter gelten weiterhin.

Die GitHub-Adresse enthält aus Gründen der Update-Kompatibilität weiterhin die frühere Schreibweise. Die Anwendungen heißen **MeeriDEX** und **MeeriDex Companion**.

*Dokumentationsstand: 25.10.2026 · Desktop 1.9.2 / Companion 0.8.3.*

## MeeriHimmel

Verstorbene Tiere können mit Todestag und optionaler Todesursache in MeeriHimmel aufgenommen werden. Profile, Fotos und Familienverknüpfungen bleiben erhalten. Windows und Android synchronisieren diese Angaben; dafür bitte beide Geräte auf Windows 1.6.0 und Companion 0.7.0 aktualisieren. Die Android-App bewahrt ungespeicherte Eingaben im MeeriHimmel-Dialog auch beim Drehen des Handys.

Ab Windows 1.6.2 werden auch Zwei-Monats-Lizenzen unterstützt: zwei Kalendermonate ab erster Aktivierung, gemeinsamer Endtermin für beide PCs. Das WurfOrakel besitzt getrennte Eltern-/Ergebnisreiter, gesperrte widersprüchliche Genorte und Hinweise zu Genherkunft und Verwandtschaft.

## MeeriPro3-ZIP übernehmen

Ab Windows 1.7.0 gibt es unter „Meine Meeris“ den eigenen Knopf „MeeriPro3 importieren“. Eine Original-ZIP mit genau einer `.back3up`-Datei und zugehörigen Fotos auswählen. Die Vorschau zeigt neue Tiere und mögliche Dubletten. Je Tier kann man neu anlegen, vorhandene Angaben behalten, bekannte Importwerte übernehmen oder den Eintrag auslassen. Elternverweise werden entsprechend zugeordnet; mehrdeutige Zuordnungen und Familienkreise müssen vor dem Speichern gelöst werden.

Bestehende Tiere und Verpaarungen bleiben erhalten. Vor dem Speichern werden automatisch Sicherungen angelegt. Unter `Importberichte` bleiben Original-ZIP, vollständige Originaltabellen und die Importentscheidungen lokal erhalten. Nicht automatisch abgebildete Zusatzdaten werden vor dem Übernehmen ausdrücklich genannt. Der MeeriPro3-Import benötigt kein Python.

### Hinweis zu Windows 7

> **Windows 7: ausschließlich mit Service Pack 1 und .NET Framework 4.8 verwenden. Ältere .NET-Versionen (z. B. 4.6.1 oder 4.7.x) werden für Windows 7 nicht unterstützt. Zusätzlich müssen Datum/Uhrzeit stimmen und die Windows-Stammzertifikate aktuell sein. Ohne diese Voraussetzungen können Installation, Online-Aktivierung und Updates scheitern. .NET 4.8.1 ist für Windows 7 nicht geeignet.**

MeeriDEX wird regulär unter Windows 10/11 geprüft. Der Fehler zur fehlenden `winsqlite3.dll` unter Windows 7 wird ab **1.7.2** durch eine eingebettete SQLite-Bibliothek vermieden. Das ist keine Zusage vollständiger Windows-7-Kompatibilität. Voraussetzung für Windows 7 ist Windows 7 SP1 mit [.NET Framework 4.8](https://support.microsoft.com/en-us/servicing/dotnetframework/2019/10/microsoft-net-framework-4-8-offline-installer-for-windows) verwenden; Aktivierung, Updates und Handy-Sync müssen auf dem tatsächlichen Rechner geprüft werden. Die produktive Kartei vorher sichern. Bei Fehlern Windows-Version, MeeriDEX-Version und den vollständigen Meldungstext angeben.

### Direkte Hilfe bei Laufzeitfehlern

Ab 1.7.3 zeigt MeeriDEX bei erkannten SQLite-Ladefehlern einen Hilfedialog mit Update-Verweis und kopierbaren technischen Details. Bei Hinweisen auf fehlende Framework-Funktionen oder Framework-Dateien und einer zu alten erkannten .NET-Laufzeit bietet er den offiziellen Microsoft-Download an. Eine fehlende `winsqlite3.dll` wird nicht pauschal als .NET-Problem eingeordnet; dafür MeeriDEX ab 1.7.2 verwenden. Fehlt .NET vollständig und Windows kann die EXE gar nicht starten, ist ein appinterner Dialog nicht möglich; dafür die Microsoft-Verknüpfung im ZIP-Paket oder den Download in dieser Anleitung verwenden.

Ab 1.7.4 öffnet eine fehlgeschlagene Online-Aktivierung einen Diagnose-Dialog mit Fehlerkategorie (Zertifikat, TLS, DNS, Timeout oder HTTP), ursprünglicher technischer Ursache, PC-Zeit und .NET-Version. Über „Details kopieren“ lassen sich diese zur Prüfung weitergeben. Der Bericht enthält keinen Lizenzcode, keine Namen und keine Tierdaten. Ein erfolgreicher Browsertest allein bestätigt nicht den Zertifikatszugriff von Windows/.NET.

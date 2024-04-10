# D04 DAVINCI Administration

**in Bearbeitung**

Dieses Handout gibt Ihnen einen Kurzüberblick über die Schulungsinhalte der DAVINCI Administrationschulung und noch einiges Wissenswertes mehr. Zu allen angesprochenen Themen wird hier das Wesentliche anhand einer Bildschirmabbildung und eines entsprechenden Textes erläutert. Eine umfangreichere Dokumentation zu DAVINCI bietet Ihnen das  [Benutzerhandbuch](https://doc.davinci6.stueber.de).

## Installation

!!! info "Hinweis"

     Bitte beachten Sie die ausführliche Beschreibung der [Installation](https://doc.davinci6.stueber.de/00.allgemein/installation/). 

### Systemvoraussetzungen

Unsere Systemanforderungen finden Sie [hier](https://doc.davinci6.stueber.de/00.allgemein/requirements/).

### Installation Client

### Installation Server

## Lizenz

### Manuell eingeben

Um Ihre Lizenzdaten von Hand einzugeben, gehen Sie bitte folgendermaßen vor

1. Starten Sie die jeweiligen DAVINCI Module und führen Sie den Menüpunkt `Hilfe > Lizenz` aus.
2. Betätigen Sie im erscheinenden Dialogfenster `Lizenz` die Schaltfläche `Neue Lizenz`.
3. Tragen Sie im erscheinenden Dialogfenster `Lizenz ändern` Ihre Lizenzdaten ein. Diese umfassen den Namen, den Standort und den Schlüssel des Lizenznehmers.
4. Bestätigen Sie Ihre Eingaben abschließend mit `OK`.

Im Dialogfenster `Lizenz` werden anschließend neue Module bei den aktiven Modulen angezeigt und stehen Ihnen zur Verfügung.

!!! info "Hinweis"

     Bitte beachten Sie, dass Sie die Lizenz nicht nur im Modul DAVINCI, sondern je nach Nutzung auch im Modul DAVINCI LOOK, DAVINCI SERVER und DAVINCI INFOSERVER eingeben müssen.

### Importieren

Alternativ können Sie Ihre Lizenzdatei auch importieren. Eine Lizenzdatei erhalten Sie entweder von STÜBER SYSTEMS als Anhang per E-Mail zugeschickt oder sie wird von DAVINCI automatisch bei der Eingabe Ihrer Lizenzdaten erzeugt. Wenn z.B. an einem anderen Rechner Ihrer Schule bereits eine ausreichende Lizenzierung vorliegt, können Sie einfach die Lizenzdatei dieses Rechners importieren. Die erzeugte bzw. importierte Lizenzdatei wird unter dem Namen `DAVINCI.lic` standardmäßig in folgenden Windows-Verzeichnissen abgelegt:

Betriebssystem | Pfad
-------------- | ----
Windows Vista | `C:\ProgramData\Stueber System\daVinci 6`
Windows XP | `C:\Dokumente und Einstellungen\All Users\Anwendungsdaten\Stueber System\daVinci 6`
Windows 2000 | `C:\Dokumente und Einstellungen\All Users\Anwendungsdaten\Stueber System\daVinci 6`

Um eine `DAVINCI.lic`-Datei zu importieren, führen Sie bitte folgende Schritte aus:

1. Starten Sie die jeweiligen DAVINCI Module und führen Sie den Menüpunkt `Hilfe > Lizenz` aus..
2. Betätigen Sie im erscheinenden Dialogfenster `Lizenz` die Schaltfläche `Lizenzdatei importieren`.
3. Markieren Sie im Windows-Explorer des erscheinenden Dialogfensters die gewünschte Lizenzdatei
4. Bestätigen Sie Ihre Auswahl mit `Öffnen`.

Im Dialogfenster `Lizenz` werden anschließend neue Module bei den aktiven Modulen angezeigt und stehen Ihnen zur Verfügung.

## Deinstallation

Die Deinstallation der DAVINCI Module starten Sie über den entsprechenden Aufruf unter `Systemsteuerung > Programme und Features`. Sie können die Module DAVINCI, DAVINCI LOOK, DAVINCI Server und DAVINCI Infoserver deinstallieren.

## Updates einspielen 

Wir veröffentlichen neue Funktionen per Serviceupdates. Diese Updates müssen auf den Rechnern in Ihrem Netzwerk eingespielt werden. Nachstehend werden die Schritte dazu beschrieben.

Bitte aktualisieren Sie immer als erstes Ihren Serverrechner, anschließend alle Arbeitsplatzrechner! Sie können die aktuellen [msi-Pakete](https://davinci.stueber.de/download.php) von unserer Webseite herunterladen und direkt per Doppelklick starten oder dazu ein Tool zur Softwareverteilung nutzen.

### Die Update-Infodatei

Jedes Installationspaket eines DAVINCI Moduls besitzt eine korrespondierende Update-Infodatei. Dies ist eine kleine XML-Datei, die es DAVINCI ermöglicht, eine neuere Version automatisch zu erkennen, herunterzuladen und zu installieren. Update-Infodateien besitzen die Dateiendung `.UPDATEINFO`.

Die Update-Infodateien für DAVINCI finden Sie hier: [Update-Infodatei für DAVINCI](https://download.stueber.de/bin/de/davinci/v6/davinci6.updateinfo)<br>
[Update-Infodatei für DAVINCI LOOK](https://download.stueber.de/bin/de/davinci/v6/davinci6look.updateinfo)<br>
[Update-Infodatei für DAVINCI SERVER](https://download.stueber.de/bin/de/davinci/v6/davinci6server.updateinfo)<br>
[Update-Infodatei für DAVINCI INFOSERVER](https://download.stueber.de/bin/de/davinci/v6/davinci6infoserver.updateinfo)

Sie können DAVINCI so anpassen, dass aktuelle Updates nicht von unseren Internetseiten, sondern von einem Netzwerkpfad Ihres Netzwerks bezogen werden.

### Lokales Ablegen des Setups

Laden Sie dazu die Installationspakete von unseren Internetseiten herunter, und legen Sie dieses zentral in einem für jeden Nutzer erreichbaren Ordner des Netzwerks ab. Laden Sie anschließend die zur Verfügung stehenden Update-Infodateien von unserer Internetseite und legen diese in den selben Ordner. Öffnen Sie die Datei mit einem einfachen Textbearbeitungsprogramm (z.B. Windows Notepad) und passen Sie den Pfad des Installationspaketes an, indem Sie den FTP-Pfad gegen Ihren Netzwerkpfad austauschen.

### Anpassen der Clients

Damit DAVINCI weiß, dass es nicht auf unseren Internetseiten sondern in Ihrem Netzwerk nach neuen Updates suchen soll, müssen Sie bei allen Clients in DAVINCI unter `Extras > Optionen > Auto-Update` den Pfad zu Ihrer Update-Infodatei eintragen.

## Client Server Einrichtung

## Benutzerverwaltung

Benutzernamen in DAVINCI festlegen Stammdaten > Lehrer rechte Maustaste und dort den Menüpunkt Benutzernamen vorbesetzen

Benutzernamen exportieren aus DAVINCI Plan > Importieren und Exportieren > DAVINCI-Benutzerdaten exportieren

Benutzer importieren im DAVINCI Explorer Registerkarte Benutzer Start > Benutzer > Importieren

Kennwörter erzeugen im DAVINCI Explorer und exportieren aus dem DAVINCI Explorer Registerkarte Benutzer Start > Kennung erzeugen Start > Exportieren

Benutzergruppe einzelne Mitglieder zuweisen im DAVINCI Explorer Registerkarte Benutzergruppen Start > hinzufügen

### Mandanten

## Plandateien

Planordner anlegen im DAVINCI Explorer Registerkarte Plandateien Planordner > Hinzufügen

Plan hinzufügen im DAVINCI Explorer Registerkarte Plandateien Plandateien > Hinzufügen

Plan hochladen im DAVINCI Explorer Registerkarte Plandateien Plandateien > Hochladen

## DAVINCI Servercontrol

Registerkarte "Backups"

Hier können Sie angeben, ob eine tägliche Sicherungskoprie der aktuellen Plandatei erstellt werden soll. Mit jeder Neuinstallation des DAVINCI Server ist diese Option aktiviert.

## PathDatei

## Schuljahreswechsel



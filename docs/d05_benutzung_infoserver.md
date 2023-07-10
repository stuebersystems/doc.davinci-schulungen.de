# D05 Benutzerverwaltung für DAVINCI INFOSERVER

in Bearbeitung

Inhalte: Übersicht über die Funktionsweise, Einstellungen in DAVINCI, Export und Import der Benutzer, Kennungen, Benutzergruppen, Plandateienstruktur, Rechtevergabe, 

## Schritte beim Stundenplanwechsel 

Die Plandatei für das neue Schuljahr muss im `DAVINCI EXPLORER > Plandateien` für die Bearbeitung und Pubbklikation zur Verfügung gestellt werden. Dafür gibt es zwei Wege:

## Gleichen Platzhalter im DAVINCI EXPLORER weiternutzen

Öffnen Sie das Modul `DAVINCI Explorer > Plandateien`. 

Laden Sie die neue Plandatei über die Schaltfläche **Hochladen** auf den Platzhalter hoch.

Beenden Sie den DAVINCI Explorer und stoppen und starten den DAVINCI Serverdienst in der Systemsteuerung einmal neu. 

## Neuen Platzhalter im DAVINCI EXPLORER anlegen

Öffnen Sie das Modul `DAVINCI Explorer > Plandateien`.

Erzeugen Sie über `Hinzufügen` einen neuen Platzhalter mit Namen  und verweisen auf Ihre zu ladende Datei.

Klicken Sie anschließend mit rechter Maustaste auf den neuen Platzhalter und wählen Eigenschaften. GUID kopieren
    Kopieren Sie die GUID, öffnen in der Systemsteuerung das DAVINCI INFOSERVER-Control und fügen die GUID und den Namen des Platzhalters ein. GUID einfügen
    Beenden Sie den DAVINCI Explorer und stoppen und starten den DAVINCI Serverdienst einmal neu. DAVINCI Serverdienst stoppen und neu starten
    Starten Sie Ihren Webserver neu.
    Sollten Sie die Rechte auf Höhe des Platzhalters vergeben haben, müssen Sie die Rechte noch für den neuen Platzhalter ergänzen.

Wichtig!

Bitte prüfen Sie in der neuen Stundenplandatei, ob die Benutzernamen in den Stammdaten der Lehrer und Klassen, ggfs. Schüler, vorbelegt sind und auch als Benutzer im DAVINCI Explorer angelegt sind. Hinweise zum Anlegen von Benutzern finden Sie im Abschnitt Benutzerverwaltung.

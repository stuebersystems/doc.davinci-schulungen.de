# D02 DaVinci Vertretungsplan Schulung

Dieses Handout gibt Ihnen einen Kurzüberblick über die Schulungsinhalte der DaVinci Vertretungsplanschulung und noch einiges Wissenswertes mehr. Zu allen angesprochenen Themen wird hier das Wesentliche anhand einer Bildschirmabbildung und eines entsprechenden Textes erläutert. Eine umfangreichere Dokumentation zu DaVinci bietet Ihnen das [Benutzerhandbuch](https://doc.davinci6.stueber.de).

## Allgemein

### Das Willkommen-Fenster

Versammelt zentrale Funktionen und Informationen, die Ihnen den Einstieg in das Programm erleichtern.
Allgemein gilt: Die Voraussetzung, um mit DaVinci Vertretungsplan arbeiten zu können, ist immer ein bereits gesetzter Stundenplan.

![Willkommensfenster](/assets/images/willk.png)

### Die DaVinci Optionen

Über den Menüpunkt `Extras > Verwalten > Optionen` gelangen Sie zu den Optionen für die Plandateien.

![DaVinci-Optionen](/assets/images/vp01.png)

1. **Startdatei:** Wenn Sie eine Startdatei eintragen, wird diese bei einem erneuten Programmaufruf geladen.
2. **Einstellung für lokalen Betrieb**
   1. Die Option Sicherungskopie der Datei anlegen ist standardmäßig markiert. Es wird von der aktuell geladenen Datei eine Kopie angelegt.
   2. Wenn Sie eine automatische Sicherung nach einem bestimmten Zeitintervall wählen, müssen Sie nicht manuell speichern, sondern DaVinci führt jeweils nach Ablauf des Zeitintervalls eine Speicherung durch.

## Bereich „Fehlzeiten“

### Fehlzeiten Ansicht

Im Bereich „Fehlzeiten“, Register „Start“ können Sie über die Menügruppe „Fehlzeiten Ansicht“ weitere Ansichten für das Erfassen der Fehlzeiten aufrufen.

![Bereich "Fehlzeiten", Register "Start"](/assets/images/images VP/vp_fehlzeitenansicht.png)

### Fehlzeiten erfassen

* Hier erfassen Sie fehlende Lehrer, Klassen und Räume
* Entsprechend der Markierung im rechten Fenster, wird links der jeweilige Plan angezeigt
* Die Symbole entsprechen den Symbolen in DaVinci Stundenplan

![Bereich "Fehlzeiten", Ansicht "Plan und Zeitplan" ](/assets/images/images VP/vp_fehlzeiten_erfassen.png)

### Lehrerfehlgründe definieren

`Extras > Schlüsselverzeichnisse > Lehrerfehlgründe`

Vor dem Erfassen fehlender Lehrern müssen unter `Extras > Schlüsselverzeichnisse > Lehrerfehlgründe` die entsprechenden Fehlgründe definiert werden. Diese stehen beim Erfassen einer Fehlzeit zur Auswahl und werden statistisch im Programm gezählt.

!!! info "Hinweis"

    Farben für Fehlgründe, werden im Plan farblich ausgegeben

![Schlüsselverzeichnis "Lehrerfehlgründe" ](/assets/images/vp02.png)

### Klassenfehlgründe definieren

`Extras > Schlüsselverzeichnisse > Klassenfehlgründe`

Definieren Sie vor dem Erfassen fehlender Klassen unter `Extras > Schlüsselverzeichnisse > Klassenfehlgründe` die entsprechenden Fehlgründe, die beim Eintragen der Fehlzeiträume erfasst und statistisch im Programm gezählt werden.

!!! info "Hinweis"

    Farben für Fehlgründe, werden im Plan farblich ausgegeben

![Schlüsselverzeichnis "Klassenfehlgründe"](/assets/images/vp03.png)

### Raumfehlgründe definieren

`Extras > Schlüsselverzeichnisse > Raumfehlgründe`

Definieren Sie vor dem Erfassen fehlender Räume unter `Extras > Schlüsselverzeichnisse > Raumfehlgründe` die entsprechenden Fehlgründe, die beim Eintragen der Fehlzeiträume erfasst und statistisch im Programm gezählt werden.

!!! info "Hinweis"

    Farben für Fehlgründe, werden im Plan farblich ausgegeben

![Schlüsselverzeichnis "Raumfehlgründe" ](/assets/images/images VP/vp_raumfehlgründe.png)

### Klassenfehlzeiten erfassen

Beginnen Sie mit dem Eintragen der fehlenden Klassen, da dadurch Lehrer frei werden, die als Vertretung eingesetzt werden können

* Markieren Sie im Vertretungsstundenplan die entsprechenden Fehlzeiträume und klicken Sie anschließend auf `Fehlzeiten > Neue Fehlzeit` oder wählen Sie die `F2-Taste`
* **Fehlgrund:** hier können Sie aus den zuvor eingegebenen „Klassenfehlgründen“ auswählen
* Option "Nicht öffentlich“ kann erfasst werden, um diesen ggf. nicht zu veröffentlichen (im Ausdruck und in LOOK)
* **Bemerkung:** hier kann ein Kommentar zu der Fehlzeit hinterlegt werden – diese erscheint später auch im Bereich „Anrechnungen“ in der Spalte „Bemerkungen“

![Fehlzeiten-Erfassen-Fenster](/assets/images/images VP/vp_klassenfehlzeit.png)

#### Ausfallstunden verrechnen

  Nach Erfassung der Klassenfehlzeit öffnet sich automatisch das Fenster `Klasse fehlt`.

![Klasse ... fehlt-Fenster](/assets/images/images VP/vp_klasse_fehlt_lehrer.png)

Dort erscheinen negativen Anrechenstunden, die ein Lehrer erhält, da seine planmäßige Klasse fehlt. Diese Stunden müssen für gewöhnlich vom Lehrer nachgeholt werden. Die vorbelegten Werte in der Spalte „Anrechnen“ können individuell angepasst werden.

* Mit dem Haken bei **Fährt mit** veranlassen Sie, dass bei diesem Lehrer eine Fehlzeit eingetragen wird.
* Über `Hinzufügen` können Sie Lehrer auswählen, welche die fehlende Klasse zur erfassten Klassenfehltzeit nicht unterrichten, dennoch Anrechenstunden verbucht bekommen sollen.

### Lehrerfehlzeiten erfassen

* Markieren Sie im Vertretungsstundenplan  die entsprechenden Fehlzeiträume und klicken Sie anschließend auf `Fehlzeiten > Neue Fehlzeit` oder wählen Sie die `F2-Taste`

![Fehlzeiten-Erfassen-Fenster](/assets/images/images VP/vp_lehrerfehlzeit.png)

* **Fehlgrund:** hier können Sie aus den zuvor eingegebenen „Klassenfehlgründen“ auswählen
* Im Feld **Bemerkung** kann ein Kommentar zu der Fehlzeit hinterlegt werden
* Setzt man ein Häkchen bei **Anrechnen,** so werden die ausfallenden Unterrichtsstunden als negative Anrechenstunden erfasst
* Option **Nicht öffentlich** kann erfasst werden, um diesen ggf. nicht zu veröffentlichen (im Ausdruck und in LOOK)
* Der Wert der anfallenden Anrechenstunden kann im Feld **Anrechenstd.** individuell angepasst werden

Die eingetragene Fehlzeit erscheint im Teilfenster „Zeitplan“ als farbiger Balken

Die eingetragene Fehlzeit wird im Teilfenster „Stundenplan“ bei den entsprechenden Terminfeldern durch einen farbigen Querbalken markiert.

![Anzeige Lehrerfehlzeit in Planfester und Zeitplan](/assets/images/images VP/vp_anzeige_lehrerfehlzeit_planfenster.png)

### Raumfehlzeiten erfassen

* Markieren Sie im Vertretungsstundenplan  die entsprechenden Fehlzeiträume und klicken Sie anschließend auf `Fehlzeiten > Neue Fehlzeit` der wählen Sie die `F2-Taste`

![Fehlzeiten-Erfassen-Fenster](/assets/images/images VP/vp_raumfehlzeit.png)

* **Fehlgrund:** hier können Sie aus den zuvor eingegebenen „Raumfehlgründen“ auswählen
* Im Feld **Bemerkung** kann ein Kommentar zu der Fehlzeit hinterlegt werden
* Unter **Ersatzraum** können Sie direkt einen Raum als Vertretungsraum auswählen, Hinweis: hier wird nicht geprüft, ob der Raum zu diesem Zeitpunkt verfügbar ist oder nicht, Sie erhalten im Aufklappbereich eine Liste aller Räume
* Option **Nicht öffentlich** kann erfasst werden, um diesen ggf. nicht zu veröffentlichen (im Ausdruck und in LOOK)
* Option **gesperrt:** Gesperrte Räume werden nicht mehr zur Vertretung angeboten.

## Bereich „Vertretungen“

### Vertretungserstellung

* oben links erscheinen fehlende Lehrer/Räume in Abhängigkeit des oben eingestellten Zeitraumes
* links unten erscheinen die möglichen direkten und indirekten Vertreter
* auf der rechten Seite erscheinen alle Stundenpläne, die zur Vertretungserstellung von Bedeutung sind

![Ansicht Bereich "Vertretungen" ](/assets/images/images VP/vp_bereich_vertretungen_ansicht.png)

In der Liste der möglichen Vertreter finden Sie zahlreiche Informationen über die zur Verfügung stehenden Lehrer.

![Direkte/Indirekte Vertreter](/assets/images/images VP/vp_liste_moeglicher_vertreter.png)

Die Liste ist gemäß verschiedener Kriterien sortiert, die Sie zuvor in den Vertretungseinstellungen gewichten können.

Mit Mausklick auf einen Spaltenkopf werden die Daten der Liste nach dieser Spalte aufsteigend sortiert. Ein nochmaliger Klick auf den Spaltenkopf bewirkt eine absteigende Sortierung.

Sie können entscheiden, ob Sie einen direkten Lehrer (dieser hat zum Vertretungszeitpunkt unterrichtsfrei) oder einen indirekten Lehrer (dieser hat zum Vertretungszeitpunkt Unterricht oder ist gesperrt) als Vertretungslehrer einsetzen möchten.

### Vertretungseinstellungen

`Start > Einstellungen`

![Vertretungseinstellungen](/assets/images/images VP/vp_vertretungseinstellungen01.png)

![Vertretungseinstellungen - Eignungsfaktoren](/assets/images/images VP/vp_vertretungseinstellungen02.png)

* In den Vertretungseinstellungen legen Sie fest, welches Gewicht verschiedene Faktoren für die Eignung eines Vertreters erhalten sollen.
* Aus dieser Gewichtung ermittelt DaVinci einen Eignungsfaktor für jeden möglichen Vertreter.
* Nach der Höhe des Eignungsfaktors ist die Liste der möglichen Vertreter standardmäßig sortiert.

### Direkte Vertreter

![ ](/assets/images/images VP/vp_vregelung.png)

* Markieren Sie den gewünschten Vertretungslehrer und klicken Sie anschließend auf `Einsetzen`.
* Über `Wie Woche zuvor` können Sie ggf. die Vertretungslösung der Vorwoche kopieren.
* Mit `Teilen` können Sie einen Doppelstundentermin in zwei Einzelstunden zerlegen.
* Mit `Zusammenfassen` werden geteilte Termine wieder zusammengefügt.
* Mit `Entfällt` können Sie eine Vertretung ausfallen lassen

#### Vertretung „Einsetzen“

![ ](/assets/images/images VP/vp_einsetzen.png)

* An dieser Stelle können Sie entscheiden, wie die Vertretungsstunde beim Lehrer verbucht werden soll.
* Eine erstellte Vertretung erkennt man an dem Feld „Status“ (nun: geändert) und dem Hinweis in Spalte „Art“ **(Zusätzlich,** **Geändert** oder **Verschoben)**

![ ](/assets/images/images VP/vp_geaendert.png)

* Die zugewiesenen Vertretungslehrer werden mit einem Pluszeichen in der Spalte **Lehrer** eingetragen.
* Der fehlende Lehrer wird in Klammern gesetzt.
* Anschließend kann man auch einen (Vertretungs-) Raum oder ein (Vertretungs-) Fach zuweisen.

![ ](/assets/images/images VP/vp_raum_aendern.png)

#### Vorziehen

* Zieht man einen Lehrer vor, so kann man auswählen, aus welcher Woche die Veranstaltung vorgezogen werden soll. Es werden Stunden zum Vorziehen angeboten, die zeitlich vor und nach dem betroffenen Termin liegen.
* Der Raum wird dabei automatisch mit vorgezogen

![ ](/assets/images/images VP/vp_vorziehen.png)

#### Ringtausch durchführen / Fehlstellen erzeugen

* Beim Vorziehen können Sie entscheiden, ob am ursprünglichen Ort des vorgezogenen Unterrichts eine Fehlstelle erzeugt werden soll.

![ ](/assets/images/images VP/vp_vertreter_vorziehen.png)

* Einer Fehlstelle kann dann wie bei einer Fehlzeit ein Vertretungslehrer zugewiesen werden. Auf diese Weise können Sie einen sogenannten Ringtausch durchführen

![Anzeige Fehlstelle](/assets/images/images VP/vp_fehlstelle.png)

#### Vertretungsentfallgründe definieren

`Extras > Schlüsselverzeichnisse > Vertretungsentfallgründe`

* Definieren Sie vor dem Vertretungsentfall unter `Extras > Schlüsselverzeichnisse > Vertretungsentfallgründe` die entsprechenden Gründe, die beim Ausfall einer Vertretung hinterlegt werden sollen.

![Schlüsselverzeichnis "Vertretungesentfallgründe" ](/assets/images/images VP/vp_vertretungsentfallgründe.png)

#### Vertretung entfällt

* Mit `Entfällt` können Sie eine Vertretung ausfallen lassen
* Wählen Sie den Grund für das Entfallen aus
* Zusätzlich können Sie in den Feldern **Info** und **Mitteilung** eine Info oder Mitteilung erfassen, die Sie später im Ausdruck mit ausgeben können.

![Vertretung entfällt-Fenster](/assets/images/images VP/vp_vertretung_entfaellt.png)

#### Vertretungsautomatik

* Über `Vertretungen > Start > Automatik` starten können Sie die offenen Lehrervertretungen automatisch von DaVinci erstellen lassen.
* Die Automatik weist dabei jeweils den Vertreter zu, der gemäß den aktuellen Vertretungseinstellungen den höchsten Eignungsfaktor aufweist.

![Vertretungsautomatik](/assets/images/images VP/vp_automatik.png)

### Indirekte Vertreter

* Wählt man einen indirekten Vertretungslehrer aus, so kann man wählen, ob dieser zwei Klassen gleichzeitig unterrichten oder freigestellt werden soll.
* Setzt man den Haken bei **Vertreter freistellen** muss die ursprüngliche Stunde des freigestellten Lehrers ggf. wiederum vertreten werden.

![Indirekten Vertreter einsetzen ](/assets/images/images VP/vp_indirekte_vertretung.png)

#### Lehrer im Plan freistellen

* Lehrer können alternativ auch über Ihr Planungsfenster (`Bearbeiten > Lehrer freistellen`) freigestellt werden

![Freistellen](/assets/images/images VP/vp_lehrer_freistellen.png)

* Sie erhalten dann ebenfalls das Symbol eines freigestellten Lehrers in der Vertretungserstellung und die betroffene Veranstaltung kann vertreten werden.

![Freistellen - Anzeige in Liste offene Vertretungen und Lehrerplan](/assets/images/images VP/vp_anzeige_freistellung_lehrer.png)

* Der freigestellte Lehrer steht dafür nun für andere Veranstaltungen als Vertreter zur Verfügung.

#### Vertretungserstellung Aufsichten

* Steht in der Spalte **Fach** bei den zu vertretenden Veranstaltungen eines Lehrers **Aufsicht**, so muss eine Pausenaufsicht des Lehrers vertreten werden

![Aufsichtslehrer fehlt](/assets/images/images VP/vp_aufsicht_fehlt.png)

* In der Liste der möglichen Vertreter werden Ihnen mögliche Vertretungen für die Pausenaufsicht angeboten
* Weisen Sie die Vertreter für die Aufsicht über `Einsetzen` zu

#### Vertretungserstellung Räume

* Markieren Sie in der Fehlzeiten-Liste eine Raumfehlzeit
* In der Liste der möglichen Vertreter (Räume) wird Ihnen angezeigt, ob der Vertretungsraum frei (Bsp. Raum „100“) oder belegt (Bsp. Raum „–101“) ist
* Weisen Sie die Vertretungsräume über `Einsetzen` zu

![Raumvertretung](/assets/images/images VP/vp_vertretung.raeume.png)

#### Verschieben und Vertauschen

In den Lehrer-, Klassen- und Raumplänen können Sie Stunden verschieben oder vertauschen.

* Markieren Sie die Zielposition über `RechteMaustatste > Markieren`.
* Klicken Sie anschließend auf die Zielposition und führen Sie den Befehl `RechteMaustaste > Termin verschieben oder vertauschen` aus.

![Termine vertauschen](/assets/images/images VP/vp_termine.vertauschen.png)

![Termine verschieben](/assets/images/images VP/vp_termine.verschieben.png)

* Sie können auch die Lehrer und/ oder Räume zwischen zwei Terminen tauschen.
* Markieren Sie die Zielposition über `RechteMaustaste > Markieren`.
* Klicken Sie anschließend auf die Position des gewünschten Tauschpartners und führen Sie den Befehl `RechteMaustaste > Lehrer/Raum vertauschen` aus.
* Entscheiden Sie im Dialogfenster **Lehrer/Raum vertauschen ob** nur Lehrer oder Raum oder beides getauscht werden soll.

![Lehrer/Raum vertauschen](/assets/images/images VP/vp_lehrer.raum.vertauschen.png)

#### Mitteilung einfügen

* Über `RechteMaustaste > Neue Mitteilung` können Sie Mitteilungen in den Bildschirmplan, die Änderungsliste und den Ausdruck einfügen.
* Mitteilungen kann man für mehrere Klassen und Lehrer einfügen

![Mitteilung einfügen](/assets/images/images VP/vp_mitteilung.einfügen.png)

![Mitteilung, Anzeige im Planfenster](/assets/images/images VP/vp_mitteilung.anzeige.png)

#### Zusatzunterricht einfügen

* Über `RechteMaustaste > NeuerZusatzunterricht` können Sie in der Änderungsliste oder in den Plänen selbst, zusätzlichen Unterricht einfügen und später mit ausdrucken.
* Zusatzunterricht können Sie mit mehreren Lehrer, Klassen und Räumen anlegen.
* Über Blitzsymbole wird Ihnen angezeigt, welche Klasse, Lehrer oder Räume zu diesem Zeitpunkt bereits belegt sind
* In Register **Räume** hat man die Filtermöglichkeit nach freien Räumen, Raumart, Kapazität und Teams

![Neuer Zusatzunterricht](/assets/images/vp04.png)

#### Unterrichtsfach/Raum im Plan ändern

* Über den `RechteMaustaste > Fach/Raum ändern`(bzw. `Start > Änderungen > Fach/Raum ändern`) können Sie das Unterrichtsfach bzw. den Raum eines Termins ändern.

![Raum ändern](/assets/images/vp06.png)

![Fach ändern](/assets/images/vp07.png)

## Bereich „Änderungen“

* In der Änderungsliste erscheinen alle erstellten Vertretungen
* Sie bildet die Grundlage für den späteren Ausdruck
* Über `Exportieren` kann die Liste nach Excel, TXT, HTML und XML exportiert werden
* Die Liste kann nach Spalten sortiert und nach einzelnen Spaltenwerten gefiltert werden

![Bereich "Änderungen"](/assets/images/images VP/vp_aenderungen.png)

## Bereich „Anrechnungen“

* In der Liste der Anrechnungsstunden werden alle Fehlzeiten und Vertretungen mit den vergebenen Anrechnungsstunden erfasst.
* Diese Liste können Sie wieder sortieren, gruppieren
* Über `Exportieren` kann die Liste nach Excel, TXT, HTML und XML exportiert werden

![Bereich "Anrechnungen"](/assets/images/images VP/vp_anrechnungen.png)

## Vertretungsstatistik

* In der Übersicht „Statistik“ finden Sie für jeden Lehrer eine monatsweise Aufstellung der Anrechenstunden, Fehlgründe, Vertretungen und Ausfallstunden. Bitte achten Sie darauf, dass Sie sich im Bereich "Vertretungen" oder "Anrechnungen" befinden.

`Start > Statistik`

![Statistik](/assets/images/images VP/vp_statistik.png)

### Vertretungsstatistik - Anrechenstunden

* Registerkarten **Positive Anrechenstunden** und  **Negative Anrechenstunden:** hier findet man für jeden Lehrer eine monatsweise Aufstellung der positiven und negativen Anrechenstunden

![Vertretungsstatistik, Anrechenstunden](/assets/images/images VP/vp_vertretungsstatistik.anrechenstunden.png)

### Vertretungsstatistik - Fehlgründe

* Auf der Registerkarte **Fehlgründe** des Dialogfensters **Statistik** werden die Fehlgründe je Lehrer gezählt. Die Liste kann nach Excel, Txt, HTML und XML exportiert werden.

![Vertretungsstatistik, Fehlgründe](/assets/images/images VP/vp_vertretungsstatistik.fehlgruende.png)

## Ausdruck

* Über `Publizieren > Drucken` können Sie nun Ihre Vertretungspläne drucken. Wählen Sie unter Auswahl aus, welchen Vertretungsplan Sie drucken wollen.
* Entsprechend dieser Auswahl wählen Sie Lehrer, Klasse oder Räume, einen entsprechenden Zeitraum und ein Druckformat aus.

![Ausdruck](/assets/images/images VP/vp_ausdruck.png)

### Druckvorschau

* In der Druckvorschau können Sie das zu erwartende Druckergebnis ansehen.
* Über die Schaltfläche `Design` können Sie das Dialogfenster zur Bearbeitung des aktuellen Druckformats aufrufen.
* Über die Schaltfläche `Seite einrichten` können Sie z.B. Ränder ändern, Kopf- und Fußzeile einfügen.

### Druckformat Design - Register „Liste“

* Unter „Tabelle“ können Sie verschiedene Format- Einstellungen bearbeiten

![Druckformat|Design|Register "Liste"](/assets/images/images VP/vp_design.liste.png)

### DruckformatDesign - Register „Spalten“

* Auf der Registerkarte „Spalten“ legen Sie Anzahl und Reihenfolge der auszugebenen Spalten fest

![Druckformat|Design|Register "Spalten"](/assets/images/images VP/vp_design.spalten.png)

### Druckformat Design - Register „Überschrift“

* Auf der Registerkarte „Überschrift“ legen Sie Schriftarten fest und ob im Infobereich Fehlende Klassen/Lehrer angezeigt werden sollen

![Druckformat|Design|Register "Überschrift"](/assets/images/images VP/vp_design.ueberschrift.01.png)

![Druckformat|Design|Register "Überschrift", Fehlende Klassen/Lehrer anzeigen](/assets/images/images VP/vp_design.ueberschrift.png)

### Druckformat Design - Register „Seite“

* Auf der Registerkarte „Seite“ legen Sie fest, wie die Bezeichnung der Lehrer in den Überschriften und Zellen ausgegeben werden soll.
* Weiterhin können Sie wählen, ob jede Tabelle auf neuer Seite beginnen soll.

![Druckformat|Design|Register "Seite"](/assets/images/images VP/vp_design.seite.01.png)

![Druckformat|Design|Register "Seite", Schaltflächen "Bearbeiten"](/assets/images/images VP/vp_design.seite.png)

## Was Sie noch wissen sollten

### Änderungen freigeben

* Unter `Plan > Eigenschaften > Datenschutz` kann die Option **Änderungen freigeben** aktiviert werden. Für DaVinci und für LOOK kann ebenfalls eingestellt werden, ob die Fehlgründe für Abwesenheiten gezeigt werden sollen.

![Plan-Eigenschaften, Datenschutz](/assets/images/images VP/vp_eigenschaften.datenschutz.png)

Dadurch kann nun das explizite Freigeben von Änderungen im lokalen wie im Servermodus gewählt werden. Wird der Haken vor **Änderungen freigeben** gesetzt, müssen die Änderungen im Vertretungsplan über `Änderungen freigeben` freigegeben werden, damit Sie auch für alle sichtbar sind.

![Publizieren, Änderungen freigeben](/assets/images/images VP/vp_publizieren.aenderungen.freigeben.png)

![Änderungen freigeben](/assets/images/images VP/vp_aenderungen.freigeben.png)

### Bezeichnungen anpassen

* Sie können in den Plan-Eigenschaften `Plan > Eigenschaften > Bezeichnungen` zahlreiche Bezeichnungen individuell anpassen.
* Diese Umbenennung wird im Ausdruck sichtbar.

![Plan-Eigenschaften, Bezeichnungen](/assets/images/images VP/vp_eigenschaften.bezeichnungen.png)

### Anzeige der Vertretungsinformationen im Stundenplan

* In DaVinci Stundenplan können Sie unter `Extras > Optionen > Stundenplan` einstellen, dass die Vertretungsinfos im Stundenplan angezeigt werden sollen.

![DaVinci-Optionen, Stundenplan](/assets/images/images VP/vp_opt_stundenplan.png)

* Die Vertretungsinformationen werden nun in der aktuellen Woche im Stundenplanbereich angezeigt. Sie erscheinen auch in DaVinci LOOK.

### Weitere Vertretungseinstellungen

![Start > Einstellungen](/assets/images/images VP/vp_start.vertretungseinstellungen.png)

![Vertretungseinstellungen, Register "Anzeigen"](/assets/images/images VP/vp_vertretungseinstellungen.anzeigen.png)

### Weitere DaVinci Optionen

in den DaVinci Optionen `Extras > Optionen|Vertretungsplan`

* Möglichkeit, für das Eintragen von Fehlzeiten **Infos,** **Mitteilungen** und **Bemerkungen** vorzudefinieren, aus denen man später auswählen kann

![DaVinci-Optionen, Vertretungsplan](/assets/images/images VP/vp_opt_vertretungsplan.png)

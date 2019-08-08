# D01 DAVINCI Intensivkurs

Dieses Handout gibt Ihnen einen Kurzüberblick über die Schulungsinhalte des DAVINCI Intensivkurs und noch einiges Wissenswertes mehr. Zu allen angesprochenen Themen wird hier das Wesentliche anhand einer Bildschirmabbildung und eines entsprechenden Textes erläutert. Eine umfangreichere Dokumentation zu DAVINCI bietet Ihnen das  [Benutzerhandbuch](https://doc.davinci6.stueber.de).

Hinweis|Bemerkung
--|--
**Dauer:**|12 x 45 min
**Themen:**|- Neuen Plan erstellen: Planvorbereitungsmanager, Stammdaten eingeben,- Unterrichtsverteilung erstellen: Perioden zuweisen, Blöcke erstellen, Lehrereinsatz,Raumverplanung,- Stundenplan setzen: manuelles und automatisches Planen, Übersichten, Druckformate editieren
**Zielgruppe:** |Stundenplaner

## Das Willkommen-Fenster

* Zugriff auf die verschiedenen Programmbereiche: Stammdaten, Kalender, Stundenplan
* Schnellstartfläche zum Öffnen der Beispieldatei (öffnet den Windows-Explorer …\Documents\Stueber Systems\DAVINCI 6\Beispiele)

![Willkommensfenster](/assets/images/willk.png)

## Neuen Plan erstellen mit dem Planvorbereitungsassistenten

Der Planvorbereitungsassistent gibt Ihnen Unterstützung bei der Neuerstellung eines Planes.
Über den Menüpunkt  ``Plan|Neu``gelangen Sie zum Planvorbereitungsassistenten.

### Neuen leeren Plan erstellen (für Neueinsteiger)

Markieren Sie ``Neuen leeren Plan`` wenn Sie auf keine Vorjahresplandatei, die Sie mit DAVINCI erstellt haben, zurückgreifen können und klicken Sie auf ``Weiter``.
Wenn Sie auf ``Fertig`` klicken, öffnet sich automatisch das Stammdatenfenster.

![Der Planvorbereitungsassistent ](/assets/images/planvorb.png)

### Neuen Plan erstellen und Daten übernehmen

Markieren Sie ``Neuen Plan erstellen und Daten übernehmen`` wenn Sie auf eine Vorjahresplandatei zurückgreifen und Daten übernehmen möchten. Geben Sie an, aus welchem Plan Sie die Daten übernehmen möchten und klicken Sie auf ``Weiter``.

![Planvorbereitungsassistent](/assets/images/Planvorb.01.png)

Wählen Sie zwischen ``Neues Schuljahr`` oder ``Planwechsel innerhalb des Schuljahres`` und klicken Sie auf ``Weiter``.

![Planvorbereitungsassistent](/assets/images/Planvorb.02.png)

Wählen Sie zwischen ``Unterrichtsverteilung und Aufsichten löschen`` oder ``Alles übernehmen`` und klicken Sie auf ``Weiter``.

![Planvorbereitungsassistent](/assets/images/Planvorb.03.png)

Anschließend gelangen Sie zu den wesentlichen Schritten der Planneuerstellung.

![Schritte der Planneuerstellung](/assets/images/planvorb1.png)

### Der erste Schritt – Der Planungszeitraum

#### Schritt 1 - Zeitraum eingeben

Geben Sie den Zeitraum an, für den Ihr Plan gelten soll.

![Zeitraum ](/assets/images/planvorb2.png)

#### Registerkarte „Statistik“

* _Zeitdauerangaben:_ Tragen Sie die zur Berechnung der Stundenangaben für die Statistik entsprechende Zeitdauer ein.
* _Wochenbezogene Summen:_ Hier können Sie die Kalenderwochen kennzeichnen, in denen kein Unterricht stattfindet. Entfernen Sie im unteren Fenster den Haken bei den Wochen, in denen kein Unterricht stattfindet. Bitte den Haken nur vor ganzen Ferienwochen entfernen!
Wichtig ist diese Angabe insbesondere, wenn Sie mit Perioden arbeiten oder eine wochenbezogene Berechnung der Unterrichtsstunden wünschen.
* _Verrechnungsart:_ Wenn man im Zeitrahmen den Haken vor "Termin-Ende beim Verplanen automatisch an Zeitrahmen anpassen" gesetzt hat, kann man über die Option „Mit „Minuten pro Einheit“ laut Zeitrahmen anstatt realer Dauer laut Plan rechnen“ entscheiden, ob in der Summenbildung die Unterrichtsstunde als 45 min gewertet werden soll, oder die Dauer lt. Positionen (die ja abweichen, 40 min, 45 min) einfließen sollen.
* Die Option ``Mit Wertfaktoren (aus Stundentafel, Fach, Klasse, Veranstaltung)`` benötigen Sie, wenn Sie mit dem Hamburger Lehrerarbeitszeitmodell rechnen wollen.
Nachträglich gelangen Sie über ``Plan|Eigenschaften|Statistik`` in dieses Menü.

![Plan-Eigenschaften, Register "Statistik" ](/assets/images/plan_eigenschaften_statistik.png)

### Schritt 2 - Kalenderdaten importieren

Laden Sie den Kalender für Ihr Bundesland, um die Ferien- und Feiertage einzutragen

* …:\Users\Public\Documents\Stueber Systems\daVinci 6\Kalender

![Kalender importieren ](/assets/images/kalender.png)

### Schritt 3 - Zeitrahmen einstellen

![Zeitrahmen ](/assets/images/zeitrahmen.png)

DAVINCI bietet Ihnen standardmäßig zwei Zeitrahmen an: Standard und Aufsichten.

#### Standard-Zeitrahmen

##### **Registerkarte "Allgemein"**

Hier können Sie vorgeben, aus wie viel Positionen Ihr Tag besteht und welche Dauer eine Position hat.

![Zeitrahmen, Register "Allgemein" ](/assets/images/zeitrahmen_standard.png)

##### **Registerkarte "Positionen"**

Spalte | Bedeutung
-|-
Bezeichnung | Standardmäßig so voreingestellt, können auch gerändert werden
Beginn/Ende |geben Sie hier Beginn und Ende der einzelnen Stunden an
Differenz | Wert errechnet sich automatisch aufgrund der eingetragenen Uhrzeiten bei „Beginn“ und „Ende“
Trennlinie |zwischen den einzelnen Positionen können Sie Trennlinien einfügen, diese können auch im Ausdruck verwendet werden
Doppelstunde | gesetzter Haken heißt für die Automatik, wann eine Doppelstunde beginnen darf, also von der Automatik verplant werden soll

![Zeitrahmen, Register "Positionen" ](/assets/images/zeitrahmen_standard_pos.png)

#### Aufsichten-Zeitrahmen

##### **Registerkarte"Allgemein"**

Spalte | Bedeutung
 -|-
Positionen | Anzahl der zu beaufsichtigenden Pausenzeiten

![Aufsichten-Zeitrahmen ](/assets/images/zeitrahmen_aufsichten.png)

!!! info "Hinweis"
    Das Zeitrahmen-Fenster können Sie jederzeit über den Menüpunkt ``Extras|Zeitrahmen`` öffnen. Bitte beachten Sie, den Zeitrahmen am gesetzten Plan nicht mehr zu verändern.

## STAMMDATEN

### Ressourcen

Erfassen Sie hier alle Hilfs- und Lehrmittel, die Sie im Rahmen der Unterrichtsplanung zuweisen möchten. Diese stehen Ihnen im Bereich "Stundenplan" zur Verfügung. Im Bereich Kalender wird außerdem für jede Ressource ein Teilnehmerkalender angelegt.

![Stammdaten Ressourcen](/assets/Stammdaten_Ressourcen.png)

### Teams

Erfassen Sie hier verschiedene organisatorische Gliederungen an der Schule. Sie können die angelegten Teams in den Stammdaten der Klassen, Lehrer und Räume hinterlegen und diese später als Filterkriterium nutzen.

![Stammdaten Teams](/assets/Stammdaten_Teams.png)

### Gebäude

Geben Sie hier die unterschiedlichen Standorte und die Wegzeiten zwischen Hauptgebäude und den Standorten ein.
Die Automatik versucht die Veranstaltungen so zu verplanen, dass keine Probleme mit den Wegzeiten bestehen. Sollte dennoch eine Wegzeit eine Pausenzeit überschreiten, weil Sie die Veranstaltungen beispielsweise manuell gesetzt haben, wird im Plan bei den entsprechenden Elementen ein Warnsymbol angezeigt.

![Wegzeitkonflikte-Symbol im Planfenster ](/assets/images/Warnsymbol.png)

![Stammdaten Gebäude](/assets/images/Stammdaten_Gebäude.png)

### Perioden

Geben Sie hier alle Periodenschemata (Wochenbezüge) ein, die Sie später einer Klasse oder einer Veranstaltung zuweisen möchten.

![Stammdaten Perioden](/assets/images/Stammdaten_Perioden.png)

### Räume

Erfassen Sie hier alle Räume, die für die Unterrichtsplanung zur Verfügung stehen sollen.

Spalte | Bedeutung
-|-
Lehrer | Eingabe des Raumbetreuers, kann in den Ausdruck übergeben werden und wird in DAVINCI LOOK angezeigt
Kapazität | diese kann bei der Raumzuweisung als Filterkriterium genutzt werden

![Stammdaten Räume](/assets/images/Stammdaten_Räume.png)

### Aufsichtsbereiche

Tragen Sie hier die Aufsichtsbereiche ein, denen zu bestimmten Zeiten ein Aufsichtslehrer zugeordnet werden soll.

Spalte | Bedeutung
-|-
Zeitrahmen | hier wählen Sie den für den Aufsichtsbereich definierten Zeitrahmen aus
Räume | hier wählen Sie Räume aus, die in der Nähe des Aufsichtsbereiches liegen, Ihnen wird später bei der Zuweisung eines Lehrers für eine Aufsicht angezeigt, wer sich in Bereichsnähe aufhält

![Stammdaten Aufsichten](/assets/images/Stammdaten_Aufsichtsbereiche.png)

### Fächer

Erfassen Sie hier die Unterrichtsfächer Ihrer Lehrveranstaltungen. Weisen Sie hier bestimmten Fächern Fachräume zu. Diese Eintragung dient als Filterkriterium bei der Raumzuweisung. Ein Fachraum ist auch ein möglicher Raum für die Planung per Raumautomatik.

![Stammdaten Fächer](/assets/images/Stammdaten_Fächer.png)

### Stundentafeln

Stundentafeln bilden die Grundlage für die spätere Unterrichtsverteilung. Geben Sie hier alle Stundentafeln ein.

![Stammdaten Stundentafel](/assets/images/Stammdaten_Stundentafeln.png)

![Anlegen einer Stundentafel](/assets/images/Stammdaten_Stundentafeln01.png)

Spalte | Bedeutung
-|-
Soll | dieser Wert wird in Spalte „Dauer“ der Unterrichtsverteilung übernommen.
Angleichung | Feld wird derzeit nur für Berufsbildende Schulen in Rheinland-Pfalz benötigt.
Wertfaktor | muss eingetragen werden, wenn Sie mit dem Hamburger Lehrerarbeitszeitmodell oder mit einer anderen Verrechnung arbeiten möchten
Termine | Terminfolge vorbelegen
Doppelstunde | Automatikvorgaben, Einträge wie 1-2 möglich

Die Stundentafeln können über das Symbol ``Exportieren`` in die Formate Excel, TXT, HTML und XML exportiert werden.

### Lehrer

Erfassen Sie hier alle Lehrkräfte, die an der Schule unterrichten. Geben Sie die Fächer der Lehrer ein. Bei der Lehrerzuordnung dient das Kriterium „Fachlehrer“ als Filter.

Spalte | Bedeutung
-|-
Raum | Wenn Sie dem Lehrer einen Raum zuordnen und dann einer Veranstaltung diesen Lehrer zuordnen, wird der Raum bei der Lehrerzuordnung direkt mit eingetragen, vorausgesetzt die Veranstaltung hatte noch keine Raumzuweisung

![Stammdaten Lehrer](/assets/images/Stammdaten_Lehrer.png)

#### Zeitkonto der Lehrer

``rechte Maustaste auf Lehrerkürzel|Zeitkonto bearbeiten``

Richten Sie hier die Arbeitszeitkonten der einzelnen Lehrer ein.
Ein „Grundkonto“ mit den Soll-Stunden, den Ist-Stunden laut Unterrichtsverteilung und der Differenz ist grundsätzlich vorhanden.

Spalte | Bedeutung
-|-
Anrechnungen | Wert ergibt sich aus der Summe der Mehr- und Minderstunden, die je Arbeitszeitkonto der Lehrer erfasst werden können
Ist | verplante Stunden (die im Plan gesetzt sind)

![Lehrer-Arbeits-Zeitkonto](/assets/images/zeitkonto_lehrer.png)

Bsp. Lehrer hat 10 Std. Ermäßigung aufgrund seiner Tätigkeit als Schulleiter und 1 Std. Mehrarbeit aus Vorjahr (+1 Std)ergibt einen Wert unter Anrechnungen von 9 (-10+1=9)

![Lehrer-Arbeits-Zeitkonto bearbeitet](/assets/images/zeitkonto_bearbeitet.png)

#### Schlüsselverzeichnis Lehrer-Soll-Schlüssel

Über `Start|Schlüsselverzeichnisse` können Sie das Verzeichnis der Lehrer-Soll-Schlüssel bearbeiten. Für einige Bundesländer können Sie auch Schlüssel importieren.

>Start|Schlüsselverzeichnisse

![![Lehrer-Soll-Schlüssel](/assets/images/images/lehrer_soll_schluessel.png)](/assets/Lehrer_Soll_Schlüssel.png)

### Klassen

Erfassen Sie hier alle Klassen, die Sie an der Schule unterrichten.

![Stammdaten Klassen](/assets/images/Stammdaten_Klassen.png)

### Anzeige der Stammdaten

Über `Extras|Optionen` gelangen Sie zu den DAVINCI Optionen.

>Extras|Optionen|Einstellungen

![DAVINCI Optionen|Einstellungen](/assets/images/opt_einstellungen.png)

* _Einstellungen:_ hier können Sie für das Stammdatenfenster die Option „Im Bearbeiten-Modus“ ausschalten, dann befindet sich das Stammdatenfenster beim Öffnen nicht im Editiermodus und versehentliches Überschreiben von Einträgen wird verhindert

>Extras>Optionen>Ansicht

![DAVINCI Optionen|Ansicht](/assets/images/opt_ansicht.png)

* _Ansicht:_ hier können Sie durch Markieren auswählen, welche Stammdaten-Register im Stammdatenfenster angezeigt werden

Im jeweiligen Stammdatenfenster können Sie über den Menüaufruf „Start|Spalten ein-/ausblenden“ oder den „*“ im Spaltenkopf einzelne Spalten ein- und ausblenden.
Dies gilt für alle Stammdatenregister.

![Spalten ein-/ausblenden](/assets/images/spalten_ein_ausblenden.png)

## STUNDENPLAN

Wählen Sie im Dialogfenster `Auswahl` welchen Plan Sie öffnen möchten. Je nachdem, welchen Reiter Sie aktivieren, erhalten Sie die zugehörige Planart.
Mit dem Auswahlfeld „Nur Team“ können Sie die Planauswahl entsprechend der Teamzugehörigkeit filtern. Wenn Sie die Einstellung „Alle Teams“ wählen, werden immer alle Teams angezeigt.
Mit dem Auswahlfeld „Unverplante Termine“ oder „N.N.-Angaben“ können Sie die Planauswahl nach dem Planungsfortschritt filtern

Sie können auch Plangruppen (Sammlungen von Plänen) definieren und für die spätere Auswahl speichern

Führen Sie den Befehl `Aus Stundentafel erzeugen` durch, um die Fachinformationen aus den in den Stammdaten angelegten Stundentafeln in die Veranstaltungslisten der zugehörigen Klassen zu übertragen – diese bilden die Grundlage für die spätere Unterrichtsverteilung.

Im Dialogfenster `Aus Stundentafel erzeugen` legen Sie fest, ob Veranstaltungen für alle Klassen gemäß der in den Stammdaten zugewiesenen Stundentafeln oder nur für eine bestimmte Klasse entsprechend einer frei wählbaren Stundentafel erzeugt werden sollen.

![Aus Stundentafel erzeugen](/assets/images/aus_stundentafel_erzeugen.png)

### Die Veranstaltungsliste

![Spalten der Veranstaltungsliste](/assets/images/Veranstaltungsliste.png)

Spalte | Bedeutung
-|-
Unverplant |
Block |
Schiene |
Fach |
Dauer |
Periode |
Soll (W) |
Ist (W) |
Lehrer |
Klassen |
Räume |
Schüler |
Wochen |
Bemerkung |
Nr |

### Veranstaltung bearbeiten | Veranstaltung

![Veranstaltung bearbeiten-Fenster | Veranstaltung](/assets/images/veranstaltungsdetails.png)

### Veranstaltung bearbeiten | Teilnehmer Termine

![Veranstaltung bearbeiten-Fenster - Teilnehmer Termine](/assets/images/veranstaltungsdetails_termine.png)

* „Nur Fachlehrer“
* „Nur ausreichende Soll-Differenz“
* „Nur Lehrer des Teams“

### Sperrung eintragen

Tragen Sie im Planungsfenster `Sperrungen` in vier unterschiedlichen Gewichtungstufen ein. Diese Entragungen werden von der Setzautomatik entsprechend der vorgegeben Abstufung berücksichtigt.
Dabei gilt 1 gilt als am stärksten und 4 als am schwächsten gewichtete Sperrung.

![Zeitpräferenz - Klasse](/assets/images/zeitpraeferenz_klasse.png)

Anzeige im Plan:

### Kernzeit eintragen

Tragen Sie im Planungsfenster `Kernzeiten` in vier unterschiedlichen Gewichtungstufen ein. Diese Entragungen werden von der Setzautomatik entsprechend der vorgegeben Abstufung berücksichtigt.
Dabei gilt 1 gilt als am stärksten und 4 als am schwächsten gewichtete Kernzeit.

![Zeitpräferenz - Lehrer](/assets/images/zeitpraeferenz_lehrer.png)

Anzeige im Plan:

![Anzeige Kernzeit im Plan ](/assets/images/kernzeit.png)

### Unverplante Termine setzen

Setzen Sie Unterrichtstermine aus dem Zusatzfenster „Unverplant“ in das Planungsfenster des aufgerufenen Einzelplans. Dies können Sie komfortabel per Drag & Drop erledigen

![Zusatzfenster "Unverplant" ](/assets/images/planfenster_unverplant.png)

Über den Menüaufruf ``Start>Planansicht`` können Sie zwei Überschneidungsprüfungen aktivieren.
Die Option „Positionskonflikte anzeigen“ hebt alle unpassenden Positionen im Planungsfenster farbig und textlich hervor.
Die Option „Passende Termine hervorheben“ hebt alle unpassenden Termine im Zusatzfenster „Unverplant“ farbig hervor.

![Planfenster ](/assets/images/planansicht_01.png)

### Termine fixieren

Fixieren Sie Stunden, um zu verhindern, dass diese von der Setzautomatik verschoben werden.

![Planfenster](/assets/images/planansicht_01.png)

### Planlayout

In den Datei-Eigenschaften unter ``Eigenschaften|Stundenplan`` geben Sie an, in welcher Form die Positionen im Bildschirmplan angezeigt werden.
Sie legen außerdem fest, welche Teilnehmerfarbe ggf. im Terminfeld angezeigt wird.
Hier entscheiden Sie ebenfalls, ob Lehrersymbole, Pausenaufsichten, Uhrzeiten und die Kalenderwochen der Perioden im Planungsfenster angezeigt werden

>Plan>Eigenschaften>Stundenplan

![Plan-Eigenschaften|Stundenplan](/assets/images/plan_eigenschaften_stundenplan.png)

### Die Zeitdetails

In den Zeitdetails einer Veranstaltung legen Sie verschiedene veranstaltungsspezifische Automatikvorgaben fest

![Veranstaltung bearbeiten-Fenster | Zeitdetails](/assets/images/veranstaltungsdetails_zeitdetails.png)

## Die Automatik

Geben Sie hier die Prioritäten für Ihren Automatikdurchlauf ein

![Automatikvorgaben|Allgemein](/assets/images/automatikvorgaben_allgemein.png)

### Klassenvorgaben

Verändern Sie hier die Anzahl der Tage und Stunden, wenn die Klasse nicht die ganze Woche bzw. den ganzen Tag anwesend ist. Wenn Sie jedoch beispielsweise von vorneherein festlegen wollen, an welchen Tagen die Klasse anwesend ist, sollten Sie die Tage sperren, die für die Klasse nicht zur Verfügung stehe

![Automatikvorgaben|Klassenvorgaben](/assets/images/automatikvorgaben_klassenvorgaben.png)

### Lehrervorgaben

Verändern Sie hier die Anzahl der Tage und Stunden, wenn der Lehrer nicht die ganze Woche bzw. den ganzen Tag anwesend ist. Wenn Sie jedoch beispielsweise von vorneherein festlegen wollen, an welchen Tagen der Lehrer anwesend ist, sollten Sie die Tage sperren, an denen der Lehrer nicht zur Verfügung steht.
Außerdem können Sie hier festlegen, wie viele Springstunden die einzelnen Lehrer maximal aufweisen dürfen.

![Automatikvorgaben|Lehrervorgaben](/assets/images/automatikvorgaben_lehrervorgaben.png)

### Fächervorgaben

In der Spalte „Fachfolge“ können Sie festlegen, welche Fächer in Klassenplänen aufeinanderfolgend und welche nicht aufeinanderfolgend verplant werden.

Spalte | Bedeutung
-|-
1 bis 9 | Fächer mit gleicher Zahl sollen am selben Tag unmittelbar hintereinander gesetzt werden.
-1 bis -9 | Fächer mit gleicher Zahl dürfen am selben Tag nicht unmittelbar hintereinander  verplant werden
 _-10 bis -19 | Fächer mit gleicher Zahl dürfen nicht am gleichen Tag verplant werden

![Automatikvorgaben|Fächervorgaben](/assets/images/automatikvorgaben_faechervorgaben.png)

![Automatik starten](/assets/images/automatik_starten.png)

Hier können Sie über den Filter und die Auswahl bestimmen, was von der Automatik verplant werden soll. Sie können erst die Setz- und dann die Raumautomatik starten oder direkt beide zusammen.
Mit der Lehrerzuordnungsautomatik können den Veranstaltungen Lehrer aufgrund der Lehrbefähigung, der Sollstundenanzahl und der Abteilungszugehörigkeit zugewiesen werden.

### Korrespondierende Pläne

Das Arbeiten mit korrespondierenden Plänen hilft Ihnen, die Übersicht über die Stundenverteilung in mehreren Klassen-, Raum- oder Lehrerplänen gleichzeitig zu bewahren. Sie arbeiten in einem ausgezeichneten Plan und die anderen Pläne richten sich danach, das heißt, die aktuelle Cursorposition wird Ihnen in den korrespondierenden Plänen angezeigt.

Mit der "X"-Schaltfläche in den Plänen links oben können Sie den betreffenden Plan aus der Synchronisation ausschließen

![Korrespondierende Pläne](/assets/images/korrespondierende_plaene.png)

### Symbole im Planfenster

Symbol|Bedeutung
--|--
![Block](/assets/images/sshot-2.png)| geblockter Unterricht
![geblockte Elemente](/assets/images/sshot-4.png)| geblockte Elemente, können hier aus platztechnischen Gründen nicht nebeneinander dargestellt werden, über `strg + linke Maus` können die geplockten Elemente aufgerufen werden
![Lehrersymbol](/assets/images/sshot-3.png)|Lehrersymbol (siehe Stammdatenfenster "Lehrer", Spalte "Symbol")
![Periodensymbol](/assets/images/sshot-5.png)|Periodensymbol, kenntzeichnet wochenbezogenen Unterricht, hier wurde der Veranstaltung eine Periode zugewiesen
![Tauschelemente](/assets/images/sshot-6.png)| mögliche Tauschelemente des im Planfenster markierten Elementes, der Tausch wird mit gedrückter  ``Shift + linke Maustaste``auf den Tauschpartner ausgeführt.
![Positionskonflikte](/assets/images/sshot-8.png)| "Positionskonflikte anzeigen" - GELB heißt, die markierte Veranstaltungen (im Planfenster oder Veranstaltungsliste) kann auf diese Position gesetzt werden
![![Positionskonflikte](/assets/sshot-8.png)](/assets/images/sshot-9.png)| "Positionskonflikte anzeigen" - BLAU heißt, die markierte Veranstaltungen (im Planfenster oder Veranstaltungsliste) führt zu einem Konflikt, wenn auf diese Position gesetzt wird

## KALENDER

![Bereich Kalender](/assets/images/sshot-10.png)

Im Bereich Kalender importieren Sie die offiziellen Ferien- und Feiertagstermine Ihres Bundeslandes.

![Kalender](/assets/images/kalender.png)

Außerdem können Sie hier Ereignisse und Aufgaben selbst definieren.
Bei Bedarf können Sie in der Kalenderansicht auch Ihre Unterrichtstermine anzeigen und diese sogar bearbeiten.

Im Dialogfenster `Ereignis` geben Sie die Termin- und Teilnehmerdaten eines Kalendereignisses an.

![Kalender](/assets/images/kalender_kalender.png)

## Die Unterrichtsmatrix

![Unterrichtsmatrix](/assets/U-Matrix.png)

In der Unterrichtsmatrix wird die Gesamt-Unterrichtsverteilung in drei unterschiedlichen Matrixansichten dargestellt.
Hier können Sie die erstellten Veranstaltungen sowohl erzeugen, als auch bearbeiten. Entweder über die Menüleiste "Start" oder über ``rechte Maustaste``.

![Veranstaltungseinträge bearbeiten](/assets/U-Matrix01.png)

## Der Aufsichtsplan

Im Programmbereich „Aufsichten können Sie für die im Aufsichtszeitrahmen erstellten Aufsichtspositionen in jedem Bereich Aufsichtslehrer zuweisen. Den Aufsichtsbereichsplan können Sie entweder für alle Wochen oder für jede Woche einzeln erstellen

![!Aufsichtsplan](/assets/images/Aufsichtsplan.png)

## ÜBERSICHTEN

Im Bereich der Übersichten finden Sie eine Vielzahl von Übersichten für weitere Auswertungen.

### Übersicht „Lehrer-Soll-Ist“

Die Übersicht „Lehrer-Soll-Ist“ zeigt für jeden Lehrer die Pflicht- und Änderungsstunden an.

### Übersicht „Fach-Soll-Ist“

Die Übersicht „Fach-Soll-Ist“ zeigt Ihnen eine Liste der Fach-Soll- und Ist-Stunden pro Klasse. Die Liste kann nach Klassen,Fächern und Schlüsseln gefiltert werden

### Übersicht „Veranstaltungen“

Die Übersicht „Veranstaltungen“ zeigt eine Liste aller Veranstaltungen und Termine des Plans.

## AUSDRUCK

Im Dialogfenster „Drucken“ wählen Sie die Planart, die Einzelpläne, den Zeitraum und das Druckformat fest, für die der Ausdruck erfolgen soll.

![Drucken-Fenster](/assets/images/drucken_fenster.png)

Für den Ausdruck in DAVINCI-Stundenplan stehen folgende Planarten zur Verfügung:

* Klassenpläne
* Lehrerpläne
* Raumpläne
* Fachpläne
* Aufsichtspläne etc

![Drucken-Fenster](/assets/images/drucken_auswahl_druckformat.png)

Für jede Planart stehen jeweils zwei Standard-Druckformate zur Auswahl:

* *Einzelplan* – hier wird das Stundenraster eines einzelnen Vertreters der Planart dargestellt.

* *Gesamtplan* – hier werden die Termine mehrerer Vertreter einer Planart in einem gemeinsamen Stundenraster dargestellt.
Aus den Standard-Druckformaten können Sie Ihre eigenen individuellen Druckformate generieren.

### Register „Stundenplan“

Für jedes individuelle Druckformat können Sie die Anzahl und die Darstellung der Wochentage im Ausdruck festlegen.

![Design|Stundenplan](/assets/images/drucken_design_stundenplan.png)

### Register „Termine“

Hier stellen Sie ein, welche Termininformationen im Ausdruck zu sehen sind.

![Design|Termine](/assets/images/drucken_design_termine.png)

### Register „Schriftarten“

Die im Planausdruck verwendeten Schriftarten können ebenfalls individuell angepasst werden

![Design|Schriftarten](/assets/images/Klassenplan.Schriftarten.png)

### Druckvorschau

In der Druckvorschau finden Sie vielfältige Optionen, das Druckergebnis zu überprüfen und an individuelle Vorgaben anzupassen

### Ansicht „Druckvorschau“|Seite einrichten

Im Dialogfenster ``Seite einrichten`` können Sie das Format der Druckseite anpassen.

![Druckvorschau - Seite einrichten](/assets/images/drucken_druckvorschau_seite_einrichten.png)

## SONSTIGES

### Bezeichnungen anpassen

Sie können Bezeichnungen umbenennen. Diese Umbenennung wird an verschiedenen Stellen in den Stammdaten, der Veranstaltungsliste dem Planungsfenster und im Ausdruck sichtbar.

>Plan|Eigenschaften|Bezeichnungen

![Plan-Eigenschaften|Bezeichnungen](/assets/images/plan_eigenschaften_bezeichnungen.png)

### DAVINCI Optionen

Über `Extras|Optionen` gelangen Sie zu den DAVINCI Optionen.

`Extras|Optionen|Meine Daten`

![Meine Daten](/assets/images/Opt_MeineDaten.png)

`Extras|Optionen|Plandatei`

![Plandatei](/assets/images/Opt_Plandatei.png)

`Extras|Optionen|Einstellungen`

![Einstellungen](/assets/images/Opt_Einstellungen.png)

`Extras|Optionen|Ansicht`

![Ansicht](/assets/images/Opt_Ansicht.png)

`Extras|Optionen|Plananzeige`

![Allgemeine Plananzeige](/assets/images/Opt_Plananzeige.png)

`Extras|Optionen|Stundenplan`

An dieser Stelle können Sie einstellen, ob verschiedene Ereignisse, z. B. Vertretungsinfos und Zeitkonflikte im Plan angezeigt werden.

![Anzeige von Planeinträgen](/assets/images/Opt_Stundenplan.png)

`Extras|Optionen|Termine`

![Einstellungen für Termine](/assets/images/Opt_Termine.png)

`Extras|Optionen|Farben`

Die Farbgebung verschiedener Ereignisse im Planeditor kann nahezu beliebig verändert werden.

![Farbgebung verändern](/assets/images/Opt_Farben.png)

`Extras|Optionen|Bezeichnungen`

![Bezeichnungen anpassen](/assets/images/Opt_Bezeichnungen_plus.png)

`Extras|Optionen|Auto-Update`

![Autoupdate aktivieren](/assets/images/Opt_AutoUpdate.png)

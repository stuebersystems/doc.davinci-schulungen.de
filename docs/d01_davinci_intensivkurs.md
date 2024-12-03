# D01 DaVinci Stundenplan

Dieses Handout gibt Ihnen einen Kurzüberblick über die Schulungsinhalte der DaVinci Stundenplanschulung und noch einiges Wissenswertes mehr. Zu allen angesprochenen Themen wird hier das Wesentliche anhand einer Bildschirmabbildung und eines entsprechenden Textes erläutert. Eine umfangreichere Dokumentation zu DaVinci bietet Ihnen das  [Benutzerhandbuch](https://doc.davinci6.stueber.de).

## Allgemein - Willkommen-Fenster

* Zugriff auf die verschiedenen Programmbereiche: Stammdaten, Kalender, Stundenplan (Navigationsleiste links)
* Beispieldateien: Schnellstartfläche zum Öffnen der Beispieldateien (öffnet den Windows-Explorer …\Documents\Stueber Systems\DaVinci 6\Beispiele)
* Nachrichten: Neuigkeiten zu DaVinci

![Willkommensfenster](/assets/images/willk.png)

## Neues Schuljahr planen

Um eine Stundenplandatei für das neue Schuljahr anzulegen, gehen Sie über den Menüpunkt `Plan > Neu`. Über diesen Aufruf wird der sogenannte Planvorbereitungsassistent geöffnet. Dieser führt Sie durch die wesentlichen Schritte der Planneuerstellung.

Hier stehen Ihnen drei Wege zur Auswahl:

![Planvorbereitungsassistent](/assets/images/SP.002.png)

### Neuen leeren Plan erstellen (für Neueinsteiger)

Wenn Sie zum ersten Mal mit DaVinci einen Plan erstellen bzw. keine Plandaten zum übernehmen haben, wählen Sie `Neuen leeren Plan erstellen` aus. Klicken Sie auf `Weiter`.
Ein weiteres Fenster mit einer Liste öffnet sich, nach diesen Punkten bereiten Sie Ihre neue Stundenplandatei vor:

![Planvorbereitungsassistent ](/assets/images/SP.001.png)

### Neuen Plan erstellen und Daten übernehmen

Schulen, die bereits auf eine Vorjahresdatei von DaVinci zurückgreifen können und daraus Daten übernehmen möchten, wählen `Neuen Plan erstellen und Daten übernehmen`. Geben Sie an, aus welchem Plan Sie die Daten übernehmen möchten und klicken Sie auf `Weiter`. Folgendes Fenster wird geöffnet:

![Planvorbereitungsassistent](/assets/images/SP.003.png)

* `Neues Schuljahr`, Klassenkürzel werden von 8a auf 9a umbenannt, die Klassenstufe wird erhöht, die Klassen-IDs werden gelöscht, alle weiteren Stammdaten bleiben unverändert
* `Planwechsel innerhalb des Schuljahres`, es werden keine Änderungen an den Stammdaten vorgenommen
  
Klicken Sie auf `Weiter`.

![Planvorbereitungsassistent](/assets/images/Planvorb.02.png)

* `Unterrichtsverteilung und Aufsichten löschen`, der gesetzte Stunden- und Aufsichtsplan aus dem Vorjahr werden gelöscht 
* `Alles übernehmen`, alle Pläne, Veranstaltungen und Aufsichtspläne werden aus dem Vorjahr übernommen
* 
Klicken Sie auf `Weiter`.

Ein weiteres Fenster mit einer Liste öffnet sich, nach diesen Punkten bereiten Sie Ihre neue Stundenplandatei vor:

![Planvorbereitungsassistent ](/assets/images/SP.001.png)

### 1. Zeitraum eingeben

Wählen Sie `Zeitraum eingeben`. Sie gelangen zum `Plan-Eigenschaften`-Fenster. Geben Sie an, für welchen Zeitraum Sie planen möchten.

![Zeitraum ](/assets/images/SP.005.png)

Planungszeitraum und Hauptzeitraum werden i.d.R. mit dem selben Start- und Enddatum vorbegelt.

Innerhalb des `Plan-Eigenschaften`-Fensters wechseln Sie bitte auf die Registerkarte "Statistik".

![Plan-Eigenschaften, Register "Statistik" ](/assets/images/SP.006.png)

Bereich | Bedeutung
--|--
Zeitdauerangaben | Tragen Sie die zur Berechnung der Stundenangaben für die Statistik entsprechende Zeitdauer ein.
Verrechnungsart | Wenn man im Zeitrahmen den Haken vor "Termin-Ende beim Verplanen automatisch an Zeitrahmen anpassen" gesetzt hat, kann man über die Option „Mit „Minuten pro Einheit“ laut Zeitrahmen anstatt realer Dauer laut Plan rechnen“ entscheiden, ob in der Summenbildung die Unterrichtsstunde als 45 min gewertet werden soll, oder die Dauer lt. Positionen (die ja abweichen, 40 min, 45 min) einfließen sollen.
Wochen | Hier können Sie die Kalenderwochen kennzeichnen, in denen kein Unterricht stattfindet. Entfernen Sie im unteren Fenster den Haken bei den Wochen, in denen kein Unterricht stattfindet. **Bitte den Haken nur vor ganzen Ferienwochen entfernen.** Wichtig ist diese Angabe insbesondere, wenn Sie mit Perioden arbeiten oder eine wochenbezogene Berechnung der Unterrichtsstunden wünschen.

Die Option `Mit Wertfaktoren (aus Stundentafel, Fach, Klasse, Veranstaltung)` benötigen Sie, wenn Sie mit dem Hamburger Lehrerarbeitszeitmodell rechnen wollen.

!!! info "Hinweis"

    Sie gelangen jederzeit nachträglich über den Aufruf `Plan > Eigenschaften > Statistik` in dieses Eingabefenster.

### 2. Kalenderdaten importieren

Importieren Sie Ferien- und Feiertage in Ihre DaVinci Datei. Laden Sie dazu den mit der Installation mitgelieferten Kalender für Ihr Bundesland:
`…:\Users\Public\Documents\Stueber Systems\daVinci 6\Kalender`

![Kalender importieren ](/assets/images/SP.007.png)

!!! info "Hinweis"

    Sie können diesen Schritt auch überspringen. Die Kalenderdatei kann jederzeit über den Bereich `KALENDER` zu einem späteren Zeitpunkt importiert werden.

### 3. Zeitrahmen einstellen

Sie gelangen in das `Zeitrahmen`-Fenster. DaVinci bietet Ihnen standardmäßig zwei Zeitrahmen an: `Standard` (Hauptzeitrahmen) und `Aufsichten` (Zeitrahmen für Ihre Aufsichtspläne).

![Zeitrahmen ](/assets/images/SP.008.png)

#### Standard-Zeitrahmen

![Standard-Zeitrahmen ](/assets/images/SP.009.png)

##### Registerkarte Allgemein

Eingaben | erforderlich für:
--|--
Tag besteht aus X Positionen | aus wie vielen Positionen maximal besteht Ihr Tag besteht
Dauer einer Position X Minuten | welche Dauer hat eine Position
Einheiten je Position X Einheiten | eine Unterrichtseinheit kann in mehrere Einheiten unterteilt werden, Trennlinien werden pro Einheit eingefügt
Vormittag bis X Position | bis zu welcher Einheit geht der Vormittag, Einstellung für die Vorschlagsautomatik, diese kann zunächst die Vormittagsstunden verplanen
Standardmäßig sichtbare Positionen X |  bis zu welcher Position sollen Stunden später fest im Planfenster gezeigt werden, alles was höher ist, ist nur durch einen Scrollbutton in der Oberfläche zu sehen

##### Registerkarte Positionen

Spalte | Bedeutung
-|-
Bezeichnung | Standardmäßig so voreingestellt, kann auch geändert werden (1.Std, 2. Std.)
Beginn/Ende |geben Sie hier Beginn und Ende der einzelnen Stunden an
Differenz | Wert errechnet sich automatisch aufgrund der eingetragenen Uhrzeiten bei „Beginn“ und „Ende“
Trennlinie | zwischen den einzelnen Positionen können Sie Trennlinien einfügen, diese können auch im Ausdruck verwendet werden, Trennlinien wird nach der Position farblich im Plan gezeigt
Doppelstunde | gesetzter Haken heißt für die Automatik, wann eine Doppelstunde beginnen darf, also von der Automatik verplant werden soll

!!! info "Hinweis"

    Haben Sie Doppelstunden, die später von der Automatik verplant werden sollen, ist es zwingend notwendig hier Haken zu setzen. Nur so erlauben Sie der Automatik Stunden beginnen, also auch verplanen zu lassen!

![Zeitrahmen, Register "Positionen" ](/assets/images/SP.010.png)

#### Aufsichten-Zeitrahmen

##### Registerkarte Allgemein

Spalte | Bedeutung
 -|-
Tag besteht aus X Positionen | Anzahl der zu beaufsichtigenden Pausenzeiten, hier zählt auch die Frühaufsicht vor Unterrichtsbeginn mit
Standardmäßig sichtbare Positionen | Wir empfehlen die selbe Zahl einzutragen, die Sie unter Tag besteht aus X Positionen eingetragen haben

Die restlichen Eingabefelder brauchen Sie nicht zu befüllen.

Entscheidend sind die Eingaben, die Sie unter der Registerkarte "Positionen" einplegen.

##### Registerkarte Positionen

Spalte | Bedeutung
-|-
Bezeichnung | Standardmäßig so voreingestellt, kann auch geändert werden (1.Pause, 2. Pause, Frühaufsicht etc.)
Beginn/Ende |geben Sie hier Beginn und Ende der zu beaufsichtigenden Pausenzeiten ein
Differenz | Wert errechnet sich automatisch aufgrund der eingetragenen Uhrzeiten bei „Beginn“ und „Ende“
Trennlinie | zwischen den einzelnen Positionen können Sie Trennlinien einfügen, diese können auch im Ausdruck verwendet werden, Trennlinien wird nach der Position farblich im Plan gezeigt
Doppelstunde | spielt bei den Aufsichten keine Rolle

![Aufsichten-Zeitrahmen ](/assets/images/zeitrahmen_aufsichten.png)

!!! info "Hinweis"
    Das Zeitrahmen-Fenster können Sie jederzeit über den Menüpunkt `Extras > Zeitrahmen` öffnen. Bitte beachten Sie, den Zeitrahmen am gesetzten Plan nicht mehr zu verändern.

#### Neue Zeitrahmen hinzufügen

Neben dem Standard- und Aufsichtenzeitrahmen können Sie weitere Zeitrahmen anlegen. In der Regel dann, wenn Sie zwei Schulteile haben, an denen die Unterrichtszeiten voneinander abweichen. (Schulteil 1 - Unterrichtsbeginn 7.55 Uhr, Schulteil 2 - Unterrichtsbeging 8.00 Uhr)

![Zeitrahmen,`Neu`](/assets/images/SP.011.png)

## Stammdaten

![Planvorbereitungsassistent,`Neu`](/assets/images/SP.012.png)

Haben Sie Schritt 1-3 umgesetzt, klicken Sie auf `Fertig`, um das Stammdatenfenster aufzurufen.

DaVinci schließt den Planvorbereitungsassistent und öffnet automatisch den Bereich "Stammdaten".

Im Stammdatenfenster geben Sie Ihre Stammdaten wie Räume, Lehrer, Klassen, Stundentafeln usw. ein. 

![Stammdaten Fenster](/assets/images/SP.013.png)

### Ressourcen

Erfassen Sie hier alle Hilfs- und Lehrmittel, die Sie im Rahmen der Unterrichtsplanung zuweisen möchten. Diese stehen Ihnen im Bereich "Stundenplan" zur Verfügung. Im Bereich Kalender wird außerdem für jede Ressource ein Teilnehmerkalender angelegt.

![Stammdaten Ressourcen](/assets/images/Stammdaten_Ressourcen.png)

### Teams

Erfassen Sie hier verschiedene organisatorische Gliederungen an der Schule. Sie können die angelegten Teams in den Stammdaten der Klassen, Lehrer und Räume hinterlegen und diese später als Filterkriterium nutzen.

![Stammdaten Teams](/assets/images/Stammdaten_Teams.png)

### Gebäude

Geben Sie hier die unterschiedlichen Standorte und die Wegzeiten zwischen Hauptgebäude und den Standorten ein.
Die Automatik versucht die Veranstaltungen so zu verplanen, dass keine Probleme mit den Wegzeiten bestehen. Sollte dennoch eine Wegzeit eine Pausenzeit überschreiten, weil Sie die Veranstaltungen beispielsweise manuell gesetzt haben, wird im Plan bei den entsprechenden Elementen ein Warnsymbol angezeigt.

![Wegzeitkonflikte-Symbol im Planfenster ](/assets/images/Warnsymbol.png)

![Stammdaten Gebäude](/assets/images/image69.png)

### Perioden

Geben Sie hier alle Periodenschemata (Wochenbezüge) ein, die Sie später einer Klasse oder einer Veranstaltung zuweisen möchten.

![Stammdaten Perioden](/assets/images/Stammdaten_Perioden.png)

### Räume

Erfassen Sie hier alle Räume, die für die Unterrichtsplanung zur Verfügung stehen sollen.

Spalte | Bedeutung
-|-
Lehrer | Eingabe des Raumbetreuers, kann in den Ausdruck übergeben werden und wird in DaVinci LOOK angezeigt
Kapazität | kann bei der Raumzuweisung als Filterkriterium genutzt werden

![Stammdaten Räume](/assets/images/image70.png)

### Aufsichtsbereiche

Tragen Sie hier die Aufsichtsbereiche ein, denen zu bestimmten Zeiten ein Aufsichtslehrer zugeordnet werden soll.

Spalte | Bedeutung
-|-
Zeitrahmen | hier wählen Sie den für den Aufsichtsbereich definierten Zeitrahmen aus
Räume | hier wählen Sie Räume aus, die in der Nähe des Aufsichtsbereiches liegen, Ihnen wird später bei der Zuweisung eines Lehrers für eine Aufsicht angezeigt, wer sich in Bereichsnähe aufhält

![Stammdaten Aufsichten](/assets/images/Stammdaten_Aufsichtsbereiche.png)

### Fächer

Erfassen Sie hier die Unterrichtsfächer Ihrer Lehrveranstaltungen. Weisen Sie hier bestimmten Fächern Fachräume zu. Diese Eintragung dient als Filterkriterium bei der Raumzuweisung. Ein Fachraum ist auch ein möglicher Raum für die Planung per Raumautomatik.

![Stammdaten Fächer](/assets/images/stamm_faecher.png)

### Stundentafeln

Stundentafeln bilden die Grundlage für die spätere Unterrichtsverteilung. Geben Sie hier alle Stundentafeln ein.

![Stammdaten Stundentafel](/assets/images/Stammdaten_Stundentafeln.png)

![Anlegen einer Stundentafel](/assets/images/Stammdaten_Stundentafeln01.png)

Spalte | Bedeutung
-|-
Soll | Wert wird in Spalte „Dauer“ der Unterrichtsverteilung übernommen
Angleichung | Feld wird derzeit nur für Berufsbildende Schulen in Rheinland-Pfalz benötigt.
Wertfaktor | muss eingetragen werden, wenn Sie mit dem Hamburger Lehrerarbeitszeitmodell oder mit einer anderen Verrechnung arbeiten möchten
Termine | Terminfolge vorbelegen
Doppelstunde | Automatikvorgaben, Einträge wie 1-2 möglich

Die Stundentafeln können über das Symbol `Exportieren` in die Formate Excel, TXT, HTML und XML exportiert werden.

### Lehrer

Erfassen Sie hier alle Lehrkräfte, die an der Schule unterrichten. Geben Sie die Fächer der Lehrer ein. Bei der Lehrerzuordnung dient das Kriterium „Fachlehrer“ als Filter.

Spalte | Bedeutung
-|-
Raum | Wenn Sie hier dem Lehrer einen Raum zuordnen und später einer Veranstaltung diesen Lehrer zuordnen, wird der Raum bei der Lehrerzuordnung direkt mit eingetragen, vorausgesetzt die Veranstaltung hatte noch keine Raumzuweisung

#### Zeitkonto der Lehrer

`rechte Maustaste auf Lehrerkürzel > Zeitkonto bearbeiten`

Richten Sie hier die Arbeitszeitkonten der einzelnen Lehrer ein. Ein „Grundkonto“ mit den Soll-Stunden, den Ist-Stunden laut Unterrichtsverteilung und der Differenz ist grundsätzlich vorhanden.

Spalte | Bedeutung
-|-
Anrechnungen | Wert ergibt sich aus der Summe der Mehr- und Minderstunden, die je Arbeitszeitkonto der Lehrer erfasst werden können
Ist | verplante Stunden (die im Plan gesetzt sind)

![Lehrer-Arbeits-Zeitkonto](/assets/images/zeitkonto_lehrer.png)

Bsp. Lehrer hat 10 Std. Ermäßigung aufgrund seiner Tätigkeit als Schulleiter und 1 Std. Mehrarbeit aus Vorjahr (+1 Std)ergibt einen Wert unter Anrechnungen von 9 (-10+1=9)

![Lehrer-Arbeits-Zeitkonto bearbeitet](/assets/images/zeitkonto_bearbeitet.png)

#### Schlüsselverzeichnis Lehrer-Soll-Schlüssel

Über `Start > Schlüsselverzeichnisse` können Sie das Verzeichnis der Lehrer-Soll-Schlüssel bearbeiten. Für einige Bundesländer können Sie auch Schlüssel importieren.

>Start|Schlüsselverzeichnisse

![Lehrer-Soll-Schlüssel](/assets/images/lehrer_soll_schluessel.png)

### Klassen

Erfassen Sie hier alle Klassen, die Sie an der Schule unterrichten.

![Stammdaten Klassen](/assets/images/Stammdaten_Klassen.png)

#### Einstellungsmöglichkeiten für die Anzeige der Stammdaten

Über `Extras > Optionen` gelangen Sie zu den DaVinci Optionen.

![`DaVinci Optionen > Einstellungen`](/assets/images/opt_einstellungen.png)

`Extras > Optionen > Einstellungen`

Hier können Sie für das Stammdatenfenster die Option „Im Bearbeiten-Modus“ ausschalten, dann befindet sich das Stammdatenfenster beim Öffnen nicht im Editiermodus und versehentliches Überschreiben von Einträgen wird verhindert

![DaVinci Optionen|Ansicht](/assets/images/opt_ansicht.png)

`Extras > Optionen > Ansicht`

Hier können Sie durch Markieren auswählen, welche Stammdaten-Register im Stammdatenfenster angezeigt werden.

Im jeweiligen Stammdatenfenster können Sie über den Menüaufruf `Start > Spalten ein-/ausblenden` oder den „*“ im Spaltenkopf einzelne Spalten ein- und ausblenden.
Dies gilt für alle Stammdatenregister.

![Spalten ein-/ausblenden](/assets/images/SP.015.png)

## Stundenplan

Nachdem alle Stammdaten erfasst sind, wechseln Sie links in der Navigation in den Bereich "Stundenplan".

![Aufruf "Stundenplan"](/assets/images/SP.016.png)

### Stundenplan öffnen

In der Registerkarte "Start" wählen Sie über das Dialogfenster `Auswahl` welchen Plan Sie öffnen möchten. Je nachdem, welchen Reiter Sie aktivieren, erhalten Sie die zugehörige Planart.

![Auswahl](/assets/images/SP.017.png)

Es öffnet sich das gewählte Auswahlfenster für Klassen, Lehrer, Raum oder Fach.

![Auswahl](/assets/images/SP.018.png)

Mit dem Auswahlfeld `Nur Team` können Sie die Planauswahl entsprechend der Teamzugehörigkeit filtern. Wenn Sie die Einstellung `Alle Teams` wählen, werden immer alle Teams angezeigt.

Mit dem Auswahlfeld `Unverplante Termine` oder `N.N.-Angaben` können Sie die Planauswahl nach dem Planungsfortschritt filtern

Sie können auch Plangruppen (Sammlungen von Plänen) definieren und für die spätere Auswahl speichern.

### Stundenplanansicht wählen

In der Registerkarte "Ansicht" wählen Sie, wie der Plan angezeigt werden soll. Soll "Plan und Liste", nur der "Plan", nur die "Liste" usw. geöffnet werden.

![Ansicht](/assets/images/SP.019.png)

Führen Sie den Befehl `Aus Stundentafel erzeugen` durch, um die Fachinformationen aus den in den Stammdaten angelegten Stundentafeln in die Veranstaltungslisten der zugehörigen Klassen zu übertragen – diese bilden die Grundlage für die spätere Unterrichtsverteilung.

### Veranstaltungsliste gemäß der Stundentafel im Stammdatenfenster befüllen

Standardmäßig finden Sie in der Veranstaltungsliste keine Einträge. Stellen Sie sicher, dass Ihre Planansicht mindestens die "Liste" (Veranstaltungsliste) zeigt. 

Klicken Sie in den Bereich "Liste" `rechte Maustaste > Aus Stundentafel erzeugen`.

![Ansicht](/assets/images/SP.020.png)

Im Dialogfenster `Aus Stundentafel erzeugen` legen Sie fest, ob Veranstaltungen für alle Klassen gemäß der in den Stammdaten zugewiesenen Stundentafeln oder nur für eine bestimmte Klasse entsprechend einer frei wählbaren Stundentafel erzeugt werden sollen.

![Aus Stundentafel erzeugen](/assets/images/SP.021.png)

### Die Veranstaltungsliste

![Spalten der Veranstaltungsliste](/assets/images/SP.022.png)

Die Veranstaltungsliste führt eine Vielzahl von Spalten auf:

* Unverplant:
* Fach
* Block:
* Dauer:
* Periode:
* Soll (W):
* Ist (W):
* Lehrer:
* Klassen:
* Räume:
* Schüler:
* Wochen:
* Bemerkung:
* Nr:
* Schiene:
* usw.

### Veranstaltung bearbeiten > Veranstaltung

![Veranstaltung bearbeiten-Fenster | Veranstaltung](/assets/images/veranstaltungsdetails.png)

### Veranstaltung bearbeiten > Teilnehmer Termine

![Veranstaltung bearbeiten-Fenster - Teilnehmer Termine](/assets/images/veranstaltungsdetails_termine.png)

* `Nur Fachlehrer`
* `Nur ausreichende Soll-Differenz`
* `Nur Lehrer des Teams`

### Sperrung > wann soll kein Unterricht stattfinden

Gewünschten Plan öffnen:

![Planansicht](/assets/images/SP.023.png)

Klicken Sie in den Bereich "Plan" `rechte Maustaste > Neue Sperrung`.

![Neue Sperrung](/assets/images/SP.024.png)

Tragen Sie im Planungsfenster `Sperrungen` in vier unterschiedlichen Gewichtungstufen ein. Diese Entragungen werden von der Setzautomatik entsprechend der vorgegeben Abstufung berücksichtigt.
Dabei gilt "1" als am stärksten und "4" als am schwächsten gewichtete Sperrung.

![Zeitpräferenz - Klasse](/assets/images/SP.025.png)

Anzeige einer Sperrung im Plan:

![Sperrzeit im Plan](/assets/images/SP.026.png)

### Kernzeit > wann soll Unterricht stattfinden

Gewünschten Plan öffnen:

![Planansicht](/assets/images/SP.023.png)

Klicken Sie in den Bereich "Plan" `rechte Maustaste > Neue Kernzeit`.

![Neue Sperrung](/assets/images/SP.027.png)

Tragen Sie im Planungsfenster `Kernzeiten` in vier unterschiedlichen Gewichtungstufen ein. Diese Entragungen werden von der Setzautomatik entsprechend der vorgegeben Abstufung berücksichtigt.
Dabei gilt "1" als am stärksten und "4" als am schwächsten gewichtete Kernzeit.

Anzeige im Plan:

![Anzeige Kernzeit im Plan ](/assets/images/SP.028.png)

### Unverplante Termine setzen

Setzen Sie Unterrichtstermine aus dem Zusatzfenster „Unverplant“ in das Planungsfenster des aufgerufenen Einzelplans. Dies können Sie komfortabel per Drag & Drop erledigen.

![Zusatzfenster "Unverplant" ](/assets/images/planfenster_unverplant.png)

Über den Menüaufruf `Start > Planansicht` können Sie zwei Überschneidungsprüfungen aktivieren.
Die Option `Positionskonflikte anzeigen` hebt alle unpassenden Positionen im Planungsfenster farbig und textlich hervor.
Die Option `Passende Termine hervorheben` hebt alle unpassenden Termine im Zusatzfenster „Unverplant“ farbig hervor.

![Planfenster ](/assets/images/planansicht_01.png)

### Termine fixieren

Fixieren Sie Stunden, um zu verhindern, dass diese von der Setzautomatik verschoben werden.

![Planfenster](/assets/images/planansicht_01.png)

### Planlayout

In den Datei-Eigenschaften unter `Eigenschaften > Stundenplan` geben Sie an, in welcher Form die Positionen im Bildschirmplan angezeigt werden.
Sie legen außerdem fest, welche Teilnehmerfarbe ggf. im Terminfeld angezeigt wird.
Hier entscheiden Sie ebenfalls, ob Lehrersymbole, Pausenaufsichten, Uhrzeiten und die Kalenderwochen der Perioden im Planungsfenster angezeigt werden

`Plan > Eigenschaften > Stundenplan`

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
 -10 bis -19 | Fächer mit gleicher Zahl dürfen nicht am gleichen Tag verplant werden

![Automatikvorgaben > Fächervorgaben](/assets/images/automatikvorgabeb_faechervorgabe.png)

![Automatik starten](/assets/images/automatik_starten.png)

Hier können Sie über den Filter und die Auswahl bestimmen, was von der Automatik verplant werden soll. Sie können erst die Setz- und dann die Raumautomatik starten oder direkt beide zusammen.
Mit der Lehrerzuordnungsautomatik können den Veranstaltungen Lehrer aufgrund der Lehrbefähigung, der Sollstundenanzahl und der Abteilungszugehörigkeit zugewiesen werden.

### Korrespondierende Pläne

Das Arbeiten mit korrespondierenden Plänen hilft Ihnen, die Übersicht über die Stundenverteilung in mehreren Klassen-, Raum- oder Lehrerplänen gleichzeitig zu bewahren. Sie arbeiten in einem ausgezeichneten Plan und die anderen Pläne richten sich danach, das heißt, die aktuelle Cursorposition wird Ihnen in den korrespondierenden Plänen angezeigt.

Mit der "X"-Schaltfläche in den Plänen links oben können Sie den betreffenden Plan aus der Synchronisation ausschließen

![Korrespondierende Pläne](/assets/images/korrespondierende_plaene.png)

### Symbole im Planfenster

| Symbol                                  | Bedeutung                           |
| --------------------------------------- | ----------------------------------- |
| <img src="/assets/images/sshot-2.png"> | geblockter Unterricht |
| <img src="/assets/images/sshot-4.png"> | geblockte Elemente, können hier aus platztechnischen Gründen nicht nebeneinander dargestellt werden, über `strg + linke Maus` können die geplockten Elemente aufgerufen werden |
| <img src="/assets/images/sshot-3.png"> | Lehrersymbol (siehe Stammdatenfenster "Lehrer", Spalte "Symbol") |
| <img src="/assets/images/sshot-5.png"> | Periodensymbol, kenntzeichnet wochenbezogenen Unterricht, hier wurde der Veranstaltung eine Periode zugewiesen |
| <img src="/assets/images/sshot-6.png"> | mögliche Tauschelemente des im Planfenster markierten Elementes, der Tausch wird mit gedrückter  `Shift + linke Maustaste`auf den Tauschpartner ausgeführt. |
| <img src="/assets/images/sshot-8.png"> | "Positionskonflikte anzeigen" - GELB heißt, die markierte Veranstaltungen (im Planfenster oder Veranstaltungsliste) kann auf diese Position gesetzt werden<br>"Positionskonflikte anzeigen" - BLAU heißt, die markierte Veranstaltungen (im Planfenster oder Veranstaltungsliste) führt zu einem Konflikt, wenn auf diese Position gesetzt wird|

## Kalender

![Bereich Kalender](/assets/images/sshot-10.png)

Im Bereich Kalender importieren Sie die offiziellen Ferien- und Feiertagstermine Ihres Bundeslandes.

![Kalender](/assets/images/kalender.png)

Außerdem können Sie hier Ereignisse und Aufgaben selbst definieren.
Bei Bedarf können Sie in der Kalenderansicht auch Ihre Unterrichtstermine anzeigen und diese sogar bearbeiten.

Im Dialogfenster `Ereignis` geben Sie die Termin- und Teilnehmerdaten eines Kalendereignisses an.

![Kalender](/assets/images/kalender_kalender.png)

## Die Unterrichtsmatrix

![Unterrichtsmatrix](/assets/images/U-Matrix.png)

In der Unterrichtsmatrix wird die Gesamt-Unterrichtsverteilung in drei unterschiedlichen Matrixansichten dargestellt.
Hier können Sie die erstellten Veranstaltungen sowohl erzeugen, als auch bearbeiten. Entweder über die Menüleiste "Start" oder über `rechte Maustaste`.

![Veranstaltungseinträge bearbeiten](/assets/images/U-Matrix01.png)

## Der Aufsichtsplan

Im Programmbereich „Aufsichten können Sie für die im Aufsichtszeitrahmen erstellten Aufsichtspositionen in jedem Bereich Aufsichtslehrer zuweisen. Den Aufsichtsbereichsplan können Sie entweder für alle Wochen oder für jede Woche einzeln erstellen

![!Aufsichtsplan](/assets/images/aufsichtsplan.png)

## Übersichten

Im Bereich der Übersichten finden Sie eine Vielzahl von Übersichten für weitere Auswertungen.

### Übersicht „Lehrer-Soll-Ist“

Die Übersicht „Lehrer-Soll-Ist“ zeigt für jeden Lehrer die Pflicht- und Änderungsstunden an.

### Übersicht „Fach-Soll-Ist“

Die Übersicht „Fach-Soll-Ist“ zeigt Ihnen eine Liste der Fach-Soll- und Ist-Stunden pro Klasse. Die Liste kann nach Klassen,Fächern und Schlüsseln gefiltert werden

### Übersicht „Veranstaltungen“

Die Übersicht „Veranstaltungen“ zeigt eine Liste aller Veranstaltungen und Termine des Plans.

## Ausdruck

Im Dialogfenster „Drucken“ wählen Sie die Planart, die Einzelpläne, den Zeitraum und das Druckformat fest, für die der Ausdruck erfolgen soll.

![Drucken-Fenster](/assets/images/SP.029.png)

Für den Ausdruck in DaVinci stehen folgende Planarten zur Verfügung:

* Klassenpläne
* Lehrerpläne
* Raumpläne
* Fachpläne
* Aufsichtspläne usw.

![Drucken-Fenster](/assets/images/SP.030.png)

Für jede Planart stehen jeweils Standard-Druckformate zur Auswahl:

Plan | Anzeige
--|--
Einzelplan | hier wird das Stundenraster eines einzelnen Vertreters der Planart dargestellt
Gesamtplan | hier werden die Termine mehrerer Vertreter einer Planart in einem gemeinsamen Stundenraster dargestellt

![Drucken-Fenster](/assets/images/SP.031.png)

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

### Ansicht „Druckvorschau“ > Seite einrichten

Im Dialogfenster `Seite einrichten` können Sie das Format der Druckseite anpassen.

![Druckvorschau - Seite einrichten](/assets/images/drucken_druckvorschau_seite_einrichten.png)

## SONSTIGES

### Bezeichnungen anpassen

Sie können Bezeichnungen umbenennen. Diese Umbenennung wird an verschiedenen Stellen in den Stammdaten, der Veranstaltungsliste dem Planungsfenster und im Ausdruck sichtbar.

`Plan > Eigenschaften > Bezeichnungen`

![Plan-Eigenschaften|Bezeichnungen](/assets/images/SP.032.png)

### DaVinci Optionen

Über `Extras > Optionen` gelangen Sie zu den DaVinci Optionen.

`Extras > Optionen > Meine Daten`

![Meine Daten](/assets/images/Opt_MeineDaten.png)

`Extras > Optionen > Plandatei`

![Plandatei](/assets/images/opt_plandatei.png)

`Extras > Optionen > Einstellungen`

![Einstellungen](/assets/images/opt_einstellungen.png)

`Extras > Optionen > Ansicht`

![Ansicht](/assets/images/opt_ansicht.png)

`Extras > Optionen > Plananzeige`

![Allgemeine Plananzeige](/assets/images/Opt_Plananzeige.png)

`Extras > Optionen > Stundenplan`

An dieser Stelle können Sie einstellen, ob verschiedene Ereignisse, z. B. Vertretungsinfos und Zeitkonflikte im Plan angezeigt werden.

![Anzeige von Planeinträgen](/assets/images/opt_stundenplan.png)

`Extras > Optionen > Termine`

![Einstellungen für Termine](/assets/images/Opt_Termine.png)

`Extras > Optionen > Farben`

Die Farbgebung verschiedener Ereignisse im Planeditor kann nahezu beliebig verändert werden.

![Farbgebung verändern](/assets/images/opt_farben.png)

`Extras > Optionen > Bezeichnungen`

![Bezeichnungen anpassen](/assets/images/Opt_Bezeichnungen_plus.png)

`Extras > Optionen > Auto-Update`

![Autoupdate aktivieren](/assets/images/Opt_AutoUpdate.png)

# Einstellungen und Schlüsselverzeichnisse

MAGELLAN richtet sich nicht an eine bestimmte Region oder Schulart. Um MAGELLAN für Ihre Region und Ihre Schulform vorzubereiten, müssen Verzeichnisse gefüllt werden oder bestimmte Felder vorbelegt werden. Für Zeugnisberichte finden Sie pro Bericht eine Liste der vorzubereitenden Punkte im Modul MAGELLAN Berichte. Pro Abiturverordnung finden Sie eine Anleitung in der Dokumentation ["MAGELLAN Landesanpassungen"](https://doc.la.stueber.de/), für die Fachwahl ist die Anleitung in der Dokumentation [MAGELLAN Handbuch](https://doc.magellan6.stueber.de/). Nachstehend finden Sie eine Liste der grundsätzlichen Eintragungen für Ihre Datenbank. Wenn Sie diese Punkte einpflegen, haben Sie Ihre Datenbank für grundsätzliche Zeugnisdaten, die Verwendung der Fachwahlkarte und die Abiturqualifikationsberechnung vorbereitet.


Stelle | Hinweis
--|--
Verzeichnisse > **Abschlussjahrgang **| Bitte legen Sie unter `Verzeichnisse > Verordnungen` die Abschlussjahrgänge an. Es genügt dabei die Angabe des Kürzels, der Bezeichnung und der Kategorie (Abitur). Legen Sie bitte die Abschlussjahrgänge soweit für die Zukunft an, dass beim Synchronisieren der Schüler der Klasse 10 bereits deren Abschlussjahrgang zugewiesen werden kann.
Verzeichnisse > **Verordnungen**| Bitte folgen Sie der Anleitung in der [Dokumentation](https://doc.la.stueber.de/de-diap-2015.html)<br/>Beispiel: ![Beispiel](images/verordnungen.png)
Verzeichnisse > **Zeiträume**|Bitte legen Sie unter `Verzeichnisse > Zeiträume` bereits die Zeiträume soweit in der Zukunft an, dass das Schuljahr existiert, indem Ihre 10er Schüler das Abitur ablegen werden.
Verzeichnisse > Zeiträume > **Art**| Der Wert 1. oder 2. Halbjahr muss gefüllt sein
Verzeichnisse > Fächer > **Kategorie**|Bitte folgen Sie der Anleitung in der [Dokumentation](https://doc.la.stueber.de/de-diap-2015.html)
Verzeichnisse > Fächer > **Aufgabenbereich**|Bitte folgen Sie der Anleitung in der [Dokumentation](https://doc.la.stueber.de/de-diap-2015.html)
Verzeichnisse > Fächer > **Fachmerkmale**|Bitte folgen Sie der Anleitung in der [Dokumentation](https://doc.la.stueber.de/de-diap-2015.html#fachmerkmale)
Verzeichnisse > weitere Schlüsselverzeichnisse > **Fachstatus**|Bitte folgen Sie der Anleitung in der [Dokumentation](https://doc.la.stueber.de/de-diap-2015.html)<br/>Beispiel: ![Beispiel](images/fs.png)
Verzeichnisse > weitere Schlüsselverzeichnisse > **Sprachreferenzen**|(zeugnisrelevant)<br/>Die Sprachreferenzen werden beim Schüler unter `Schüler > Daten 3 > Fremdsprachenfolge` im Feld `Referenz` eingetragen. Sie können dazu auch die Sammelzuweisung unter `Schüler > Bearbeiten > Sammelzuweisung` verwenden. Beispiel: ![Beispiel](images/sprachreferenzen.png)
Verzeichnisse > weitere Schlüsselverzeichnisse > **Kurssprachen**|(zeugnisrelevant)<br/>Für vollständig in einer Fremdsprache unterrichtete Fächer lassen Sie den Schlüssel bitte frei, für bilingual unterrichtete Fächer tragen Sie im Schlüssel bitte `bi` ein. Die Kurssprachen können an folgenden Stellen eingegeben werden:<br/>- `Verzeichnisse > Fachtafeln > für Fachwahltafeln (Q1-Q4 Sprache)`<br/>- `Schüler > Zeugnis > Fächer > Sprache` <br/>- `Abitur > Fachwahl > Q1-Q4 Sprache`<br/>- `Abitur > Qualifikation > Q1-Q4 Sprache`<br/>Beispiel: ![Beispiel](images/kurssprachen.png)
Verzeichnisse > weitere Schlüsselverzeichnisse > **Unterrichtsarten**|Bitte folgen Sie der Anleitung in der [Dokumentation](https://doc.la.stueber.de/de-diap-2015.html)<br/>Beispiel: ![Beispiel](images/ua.png)
Mandanten > Daten > **Schulleiter**| (zeugnisrelevant)<br/>Weisen Sie bitte im Feld Schulleiter den entsprechenden Kollegen aus dem Lehrermenü zu
Klassen > Zeiträume > Zeitraum > **Klassenleiter**|(zeugnisrelevant)<br/>Wählen Sie bitte den Klassenleiter aus
Lehrer > Daten > **Geschlecht**|(zeugnisrelevant) <br/>Füllen Sie bitte für die Kollegen das Feld Geschlecht. <br/> Beispiel: <br/>Schulleiter oder Schulleiterin<br/>Klassenleiter oder Klassenleiterin
Klassen > Daten > **Klassenart**|Klassen 11, 12 oder 13: <br/>Wählen Sie bitte `Oberstufenjahrgang (nur Kurse)`oder `Oberstufenjahrgang (Grund- und Leistungskurse)`<br/>Für Schüler in Klassen, denen diese Klassenart zugewiesen wurde, werden beim Synchronisieren die Schüler mit Fach- und Notendaten in den Bereich "Abitur" synchronisiert.<br/>Klasse 10: <br/>Unter `Klasse > Daten` muss im Feld „Klassenart“ die Auswahl "Standardklasse mit Oberstufensynchronisation" wählen, hierbei werden aber lediglich die Schüler für den Punkt `Abitur > Fachwahl` übertragen, also keine Schülerfachdaten oder Leistungsdaten.
Klassen > Zeiträume > Zeitraum > **Jahrgang**|Tragen Sie pro Klassenzeitraum bitte den Jahrgang ein (10, 11, 12 oder 13)


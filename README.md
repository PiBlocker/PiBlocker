
Inhalt
1.	Zielsetzung und Hintergrund	
2.	Systemarchitektur	
3.	Funktionale Spezifikationen	
4.	Datenmodell	
5.	Benutzeroberfläche	
6.	Technische Anforderungen	
7.	Leistungsanforderungen	
8.	Qualitätsanforderungen	
9.	Test- und Validierungsstrategie	
10. Lieferumfang und Zeitplan	
11. Quellen	
12. Ergebnisse/Zwischenstand und Umgang mit Problemen	
13. Aufgabenverteilung im Projekt	

1.	 Zielsetzung und Hintergrund
•	Bau eines Adblockers für das gesamte Netzwerk.
•	Die nötige Software existiert bereits fast vollständig.
2.	 Systemarchitektur
•	Raspberry Pi 4b, basierend auf einer ARM-CPU
•	Display per dsiDP
•	230V Netzteil


3.	 Funktionale Spezifikationen
Das Gerät soll jegliche Werbung im ganzen Netzwerk blockieren, bevor sie uns angezeigt wird. Dabei soll der interne Ping nicht groß beeinträchtigt werden.
Die Bedienung sollte über ein Webinterface bzw. einem Touchdisplay passieren.
4.	 Datenmodell
Homepage mit Weiterleitung auf: 
1.	PiHole
2.	Speedtest
3.	Impressum
4.	Erklärvideo
5.	 Benutzeroberfläche
•	Touchdisplay zur einfachen Bedienung des Ad-Blockers. 
•	Weboberfläche über IP erreichbar.
	Homepage zur Weiterleitung an die Wunschpage
	Tutorial zur Bedienung
6.	 Technische Anforderungen
•	Genug Rechenleistung um die Aufgabe auszuführen.
•	Genug Speicherplatz um die Software zu speichern.
•	Niedriger Stromverbrauch, da das Gerät die ganze Zeit eingeschaltet ist.
•	Netzwerkzugang zum konfigurieren und nutzen
7.	 Leistungsanforderungen
•	Blockierung von allen Werbungen.
•	Betreibung eines Displays.

8.	 Qualitätsanforderungen
•	Ansprechendes Gehäuse mit guter Verarbeitung.
•	Schnelle und zuverlässige Funktion des Displays.
9.	 Test- und Validierungsstrategie
Nachdem der PiBlocker eingeschaltet wurde, gibt es zwei Dinge, die überprüft werden müssen:
1.	Funktion der Internetverbindung (Test via Speedtest)
2.	Blockierung der Werbeadressen (Check via mit Client 
 10.  Lieferumfang und Zeitplan
Im Lieferumfang des Gerätes wäre natürlich: 
o	PiBlocker (installiert)
o	CAT. 5 RJ 45 Kabel
o	Powerkabel
o	Installierte Software
Zeitplan:
o	Software bis zur Meilensteinsitzung fertig
o	Hardware bis Ende Mai fertig







 11.  Quellen
Software:
GitHub:
  -PiHole
  -LibreSpeed
  Hardware:
 

Notiz: Das Gehäuse wird von Max gedruckt. Die Kosten übernimmt er.






 12.  Ergebnisse/Zwischenstand und Umgang mit Problemen
- Das Gehäuse des PiBlockers wird noch modelliert
-Elektronik fertig
-Software bereitet Probleme, Website fast fertig

Probleme:
1.DNS vergabe von Ngix
	leider hat Ngix eine Fehlermeldung ausgegeben, die auf die Ports    zurückzuführen war. Behoben wurde dies mittels eines Stackoverflow Beitrags. 
 13.   Aufgabenverteilung im Projekt
	Max: Design und Herstellung des Gehäuses
	Ioannis: Programmierung und Scripting der Software, Bauen der Elektrokomponenten, Auswahl und Einkauf der Komponenten
	Colin: Erstellung des Handouts, Vorbereitung der Vorführung (Praxistest)
	Linus: Erstellung des Handouts, Überprüfung der Ziel/Zeit-einhaltung
	Jannes: Erstellung der Schaltpläne, Abnahme des Produktes

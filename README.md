# Algorythmus Sozialauswahl
Hallo liebe Kollegen,
hier ist ein kleines Projekt zu unserem Fit-Recovery-Unsinn.

Meine Frage war, ob es möglich ist, ein Algorythmus zu schreiben, der automatisch die Punkte aller wichtigen Parameter unserer Sozialauswahl berechnet und in einer Tabelle zusammen mit einer Entlassungsempfehlung speichert.

Als ersten Schritt habe ich einen mitarbeiter_generator gebaut, denn es ging ja darum, erst einmal herauszufinden, ob das Konzept überhaupt funktioniert. 
Dazu wird ein Betrieb mit 40 MA angenommen, der mit einer Personalreduzierung von 10 Stellen (bzw 10 FTE) plant.

Die generierten Kollegen habe ich dann in vier verschiedene Modelle eingelesen.
Im ersten Modell geht es um eine allgemeine Entlassungsempfehlung nach unserer Methodik: Konstruktion verschieder Instanzvariablen mit einem Punktesystem, eine Einteilung der MA in Altersgruppen und eine symmetrische Erstellung von Kündigungsempfehlungen nach diesem Punktesystem.

Im zweiten Modell habe ich die Variable Arbeitsvertrag hinzugefügt, die verschiedene Stundenverträge einberechnet. Ich bin dann nicht von einer Stellenreduzierung ausgeangen, sondern von einem Gesamtstundenumfang, der eingespart werden soll.
Das gleiche Ergebnis mit der prozentualen Übersetzung der Teilzeitstellen nimmt sich das dritte Modell vor.

Und im vierten Modell fallen einige MA aus dem Modell, die entweder im BR engagiert sind oder Spezialaufgaben ausführen. 





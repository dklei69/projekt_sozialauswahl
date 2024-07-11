# Algorythmus Sozialauswahl
Hallo liebe Kollegen,
ich habe ein bisschen herumprobiert.

Meine Frage war, ob es möglich ist, ein Algorythmus zu schreiben, der automatisch die Punkte aller wichtigen Parameter unserer Sozialauswahl berechnet und in einer Tabelle zusammen mit einer Entlassungsempfehlung speichert.

Als ersten Schritt habe ich einen mitarbeiter_generator gebaut, denn es ging ja darum, erst einmal herauszufinden, ob das Konzept überhaupt funktioniert. 
Dazu wird ein Betrieb mit 40 MA angenommen, der mit einer Personalreduzierung von 10 Stellen (bzw 10 FTE) plant.

Die generierten Kollegen habe ich dann in zwei verschiedene Modelle eingelesen.
Im ersten Modell geht es um eine allgemeine Entlassungsempfehlung nach unserer Methodik: Konstruktion verschieder Instanzvariablen mit einem Punktesystem, eine Einteilung der MA in Altersgruppen und eine symmetrische Erstellung von Kündigungsempfehlungen nach diesem Punktesystem. Die Altersgruppierung lässt sich mit dem konkreten Alter, aber auch mit dem Geburtsdatum ermitteln. (Und es war, entgegen meiner Erwartung auch nicht zu kompliziert.

Im zweiten Modell habe ich die Variable Arbeitsvertrag hinzugefügt, die verschiedene Stundenverträge einberechnet. Ich bin dann nicht von einer Stellenreduzierung ausgeangen, sondern von einem Gesamtstundenumfang, der eingespart werden soll. (Wie sich herausstellt, brauchen wir das Modell jedoch nicht.)

Es sind zu diesem Projekt noch die eine oder andere Frage offen, an die ich mich später setze. (Wenn ich mal gaaaaaanz viel Zeit und Lust hab.) 
Kann man zum Beispiel einen eleganten Automatismus einführen,  wenn Kollegen freiwillig aussteigen, auf die das Programm dann selbstständig reagiert.

Hier findet ihr jedoch erst einmal nur den Code für die synthetischen Daten (wer weiß, wofür man das noch gebrauchen kann) und die beiden Modelle. 








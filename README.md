![github-header-image (2)](https://user-images.githubusercontent.com/111282979/232119853-52dee20b-6259-493a-8a52-3e239aeb1b82.png)



|[Blogeintrag-16.01.23](#blogeintrag---16012023)|[Blogeintrag-14.02.23](#blogeintrag---14022023)|[Blogeintrag-28.02.23](#blogeintrag---28022023)|[Blogeintrag-14.03.23](#blogeintrag---14032023)|[Blogeintrag-21.03.23](#blogeintrag---21032023)|[Blogeintrag-14.04.23](#blogeintrag---14042023)|
:-------------------:|:-------------------:|:-------------------:|:-------------------:|:-------------------:|:-------------------:|

## Blogeintrag - 16.01.2023

Am heutigen Tag gab es Unschlüssigkeiten bzgl. des Stundenplans, weshalb nur die Hälfte der Klasse anwesend war. Da es sich nicht lohnte, die Projekte vorzustellen, fingen wir an, uns neue Projekte zu überlegen. Leider war nur Laurenz anwesend, sodass er sich über verschiedene mögliche Projektideen Gedanken machte und dazu recherchierte.

## Blogeintrag - 14.02.2023

Nachdem wir uns letztes Mal mit der Desktop-Anwendungsentwicklung auseinandergesetzt hatten, und eine Simulation programmierten, welche die Evolutionstheorie nach Charles Darwin repräsentierte, entschieden wir uns nun dazu, dieses Halbjahr in das "Physical Computing" einzusteigen. Zufälligerweise entdeckten wir auf Social Media Teslaspulen, welche durch einen AUX-Anschluss die eingehende Spannung insofern anpassten, dass die Audio den erzeugten Frequenzen entsprach und die Teslaspule wie ein Lautsprecher fungierte. Dieses Konzept wollten wir uns als Vorbild nehmen. Die Kabelgebundenheit war uns jedoch ein Dorn im Auge. Deshalb war unser Plan, das Ganze per Bluetooth zu betreiben. Getauft haben wir unser Projekt mit dem Titel "Tesla Beats". Mithilfe eines Arduinos sollte die eingehende Spannung der Teslaspule gesteuert werden. Falls diese Aspekte erfüllt sein sollten, wollten wir noch zusätzlich, mithilfe einer Kamera Bewegungen erfassen können, um mithilfe von festgelegten Bewegungen die Spannung zu steuern. Vom Design her orientierten wir uns an den kabelgebundenen Teslaspulen:

[![20230411_203427](https://user-images.githubusercontent.com/111282979/231257475-f5c9ac69-5901-435d-827c-68555571c453.jpg)](https://www.youtube.com/shorts/9_NoVwdvP4I)


## Blogeintrag - 28.02.2023

Seit der letzten Stunde hatten wir bereits begonnen, im Baumarkt alle nõtigen Bauteile zu beschaffen, die wir benötigten, um mit
dem Bau der Teslaspule zu beginnen. Unter anderem benötigten wir Kupferdraht, einen Transformator und weitere Bauteile.
Leider war bis heute nicht alles auffindbar, was wir brauchten. Somit hofften wir darauf, aus den Physikräumen der Schule die restlichen Materialien beschaffen zu können. Da Laurenz in dieser Doppelstunde leider nicht anwesend war, begann Daniel damit, die Primärspule zu konstruieren. Glücklicherweise verfügte unsere Schule über Kupferdrahtvorräte, die uns zur Verfügung gestellt wurden. Die Herausforderung bei der Herstellung der ersten Spule bestand darin, den Kupferdraht ohne eine Drehbank zu wickeln. 
Zufälligerweise hatte die Schule wegen des Tages der offenen Tür eine Teslaspule von einer anderen Schule geliehen, sodass an dieser der Aufbau veranschaulicht werden konnte und das Verhalten dieser Spule bereits kennengelernt werden konnte.

![Bild Blogeintrag 2](https://user-images.githubusercontent.com/111282979/231255524-049d1a20-d767-4e27-bc09-1def42fc7f3a.jpg)



## Blogeintrag - 14.03.2023

Nachdem wir uns eine ausgeliehene Teslaspule angeschaut hatten, sind wir nach einigen Überlegungen zum Entschluss gekommen, dass die Teslaspule insofern keinen Mehrwert hätte, da dieses Projekt nur etwas zum Betrachten wäre und keine sinnvolle Funktion für den Anwender hat. 
Deshalb wollten wir uns nicht weiter dem Physical Computing widmen, sondern dieses Mal in die moderne Full-Stack Web-Entwicklung einsteigen.
Da Laurenz bereits neben dem Informatikunterricht privat angefangen hatte, einen Passwort Manager mit React zu entwickeln, nahmen wir dies als Projekt.
Unsere Idee war ein Passwort Manager namens VergissMeinNicht, der die Passwörter der Nutzer besser und transparenter schützen kann als andere Anbieter sowie automatisch starke Passwörter erstellt. Bei den ganzen heutigen Standards, die Passwörter auf allen möglichen Seiten erfüllen müssen, stoßen auch wir häufig auf das Problem, dass man sich einfach nicht mehr an sein Passwort erinnert.
Wir wollen den Nutzern im Internet nun das Leben erleichtern und sie vor den Gefahren des Zugriffs durch Fremde so gut wie möglich schützen. 
Ähnlich wie bei einer 2-Faktor-Authentifizierung schützt ein Nutzer seine Passwörter neben seinem Account-Passwort noch zusätzlich durch ein Masterpasswort.
Bevor wir unsere Idee in die Praxis umsetzen wollen, wollten wir uns unbedingt einen guten Plan machen. Bei der Entwicklung einer kompletten Full-Stack Anwendung ist die Planung das A und O. Wir erstellten über ein kostenloses Designerprogram mit dem Namen Figma Grafiken, um unsere Ideen und die Funktionen, die wir uns für unser Projekt überlegten, zu visualisieren. Um uns auch später noch genauestens an das zu erinnern, was wir uns zu den Grafiken in dem Moment dachten, verfassten wir zu jeder Skizze einen Text, der nun auch auf der Projektseite zu sehen ist. Nachdem unser klarer Plan fertiggestellt war, begannen wir mit der Umsetzung des Projekts.
Die Entwicklung des Frontends als React-Anwendung ist praktisch, da diese, durch ihre Komponenten-Struktur zu einem sehr klaren und gut zu überarbeitenden Code führt. 
Schnell hatten wir das Projekt von Laurenz migriert und eine Grundstruktur geschaffen, auf der wir bis zur nächsten Woche die nächsten die Accounteinstellungen programmieren werden.

![Bild Blogeintrag 1](https://user-images.githubusercontent.com/111282979/231255651-992358e6-2d29-4e10-a0fa-18cfabd53903.jpg)


## Blogeintrag - 21.03.2023

Nachdem wir nach vielem Trial und Error ein funktionierendes Frontend geschaffen haben, müssen wir nun die Funktionalität (das Backend) hinzufügen.
Die Anfragen müssen von einem Server empfangen und verarbeitet werden. Zuerst machten wir uns auf die Suche nach einer Möglichkeit, diesen Server zu hosten.
Nach kurzer Recherche stießen wir auf die Google Cloud Functions. Dadurch lässt sich unser Backend/Server als RESTful-API mit Node.js und Express ohne eigenen Server hosten.

Node.js ist eine serverseitige JavaScript-Plattform, die es Entwicklern ermöglicht, leistungsstarke, skalierbare und schnelle Netzwerkanwendungen zu erstellen. Node.js wurde 2009 von Ryan Dahl entwickelt und seitdem kontinuierlich erweitert und verbessert. Die Plattform verwendet Googles V8 JavaScript Engine, um schnellen, effizienten und leistungsstarken JavaScript-Code auszuführen.
Eine der Hauptfunktionen von Node.js ist die asynchrone Verarbeitung von Daten, die durch das sogenannte Event-Loop-Modell ermöglicht wird. Im Gegensatz zu traditionellen serverseitigen Technologien wie PHP, die auf synchroner Verarbeitung basieren, verwendet Node.js eine asynchrone Architektur, die es Entwicklern ermöglicht, eine große Anzahl von Anfragen gleichzeitig zu verarbeiten, ohne den Server zu überlasten. Node.js ist auch in der Lage, Datenübertragungen in Echtzeit über WebSockets zu unterstützen, wodurch Entwickler schnelle und reaktionsfähige Webanwendungen erstellen können.
Node.js ist auch für seine große Auswahl an Modulen und Paketen bekannt, die über den Node Package Manager (NPM) zur Verfügung stehen. Dieser ermöglicht es Entwicklern, eine Vielzahl von Modulen und Paketen zu installieren und zu verwenden, die speziell für Node.js entwickelt wurden. Diese Module und Pakete können für eine Vielzahl von Aufgaben verwendet werden, wie z.B. die Verarbeitung von Daten, die Anbindung an Datenbanken, die Erstellung von APIs und vieles mehr.
Eine weitere Stärke von Node.js ist seine Fähigkeit, mit verschiedenen Datenbanken zu interagieren, einschließlich der populären NoSQL-Datenbank MongoDB und der relationalen Datenbank MySQL. Mit Node.js können Entwickler Datenbankabfragen asynchron ausführen, was die Leistung und Skalierbarkeit der Anwendung verbessert.
Node.js eignet sich auch hervorragend für die Entwicklung von Microservices, einer modernen Architektur, bei der eine Anwendung in mehrere unabhängige Dienste aufgeteilt wird, von denen jeder eine bestimmte Funktion ausführt. Diese Dienste können unabhängig voneinander bereitgestellt und skaliert werden, was eine höhere Flexibilität und Skalierbarkeit ermöglicht. Insgesamt ist Node.js eine leistungsfähige und flexible Plattform, die es Entwicklern ermöglicht, schnelle und skalierbare Anwendungen auf Basis einer asynchronen Architektur zu erstellen. Durch die Verwendung von NPM und die große Auswahl an Modulen und Paketen ist Node.js zudem sehr erweiterbar und kann für eine Vielzahl von Anwendungsfällen eingesetzt werden.


[![Node JS-pic-12](https://user-images.githubusercontent.com/111282979/231259269-c62c838c-c022-4310-b007-b0a92fe424ca.png)](https://kinglearn.ir/wp-content/uploads/2021/03/Node.JS-pic-12.png)

## Blogeintrag - 7.04.2023

Mittlerweile waren wir mit der Programmierung unseres Projekts "VergissMeinNicht" fertig geworden, sodass wir uns nun voll und ganz unserer Projektseite widmen können. Wir fertigten, wie beim letzten Mal, eine Logo-Animation und ein Inhaltsverzeichnis an. Neben den Planskizzen haben wir die Projektseite in drei weitere, aufklappbare Überschriften aufgeteilt: Frontend, Backend, Reflexion. Wir gingen den gesamten Code durch und kommentierten diesen.
Zusätzlich ist es nun unser Ziel, jedes Detail im Code auf der Projektseite zu erklären.
Zur Darstellung des Codes nutzten wir teilweise wieder Carbon, um unsere Code-Abschnitte als Fotographie in die Projektseite einzufügen.
Da das Projekt so umfangreich ist, haben wir uns überlegt bei manchen Aspekten einen kurzen, verständlichen Erklärtext zu verfassen und daraufhin auch einen aufklappbaren, längeren, in dem alle Details erklärt werden. Auch wenn nur der kurze Text gelesen wird, versteht man bereits ein wenig, wie das Ganze funktioniert.

![Bild Blogeintrag 4](https://user-images.githubusercontent.com/111282979/231255825-5ecd0cb1-b44e-4bc1-b583-2aa800c034a8.jpg)

## Blogeintrag - 14.04.2023

Nach sehr vielen verfassten Texten zu den einzelnen Bereichen des Projekts, haben wir unsere Texte noch überarbeitet und verbessert.
Für eine noch bessere Verständlichkeit, sodass keine Fragen offen bleiben, haben wir noch Grafiken hinzugefügt. 
Damit wir uns juristisch gegen Raubkopie des Codes absichern, haben wir eine Lizenz hinzugefügt, wodurch wir im Ernstfall im Recht wären.
Wir sind stolz auf das, was wir geschafft haben und freuen uns auf das nächste Projekt.




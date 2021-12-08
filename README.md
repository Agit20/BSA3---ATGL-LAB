# ATGL - LAB Protokoll
#
## Use Case - Sandra
#
#
### Aufgabenstellung
# TEXT
### Klientin Kurzbeschreibung
Die Klientin Sandra möchte sich ihren körperlichen Einschränkungen mit Hilfe der modernen Technologie, die wir zur Verfügung haben, widersetzen. Da sie abgesehen von ihren physischen Barrieren, auch eine signifikante Sehschwäche hat, ist die Klientin in ihrer Selbstständigkeit stark limitiert. Das Ziel ist es, ihr eine gewisse Autonomie zurückzugewinnen.  

 

Frau Sandra besitzt bereits einen Rollstuhl, einen Laptop und ein Smartphone. Da sie Buchstaben nur stark vergrößert wahrnehmen kann (binocular acuity of distant vision: b21000), müssen digitale Geräte auch dementsprechend konfiguriert werden. Außerdem sollte man ihre Protanopie (colour vision: b21021) und die Notwendigkeit nach hohem Kontrast (contrast sensitivity: b21022), in Betracht ziehen.  

 

Dass sie dennoch über gewisse körperliche Funktionen verfügt, ermöglicht einen größeren Spielraum bei der Verwendung von Hilfsmittel. Abgesehen davon, dass sie ihren Kopf bewegen kann, sind auch Daumen und Zeigefinger am linken Arm vollkommen funktionstüchtig. Die Tatsache, dass sie ihren Mund bzw. ihre Lippen bewegen kann, ermöglicht die Verwendung einer FlipMouse.  

 

Die Klientin Sandra wünscht sich, Licht, Temperatur, Jalousien und etliche Elektrogeräte wie Fernseher, Musikanlage und ihre Spielzeuge, selbstständig steuern zu können. Außerdem möchte sie den Computer insofern steuern können, sodass sie im Internet surfen und E-Mails schreiben bzw. auf diese antworten kann. Zusätzlich würde sie gerne Klänge erzeugen, Computerspiele adaptieren und Visuals mit Hilfe von Phillips Hue Go oder Infrarot Lampen kreieren. Als letzten Wunsch formulierte sie, ihr SmartPhone für kommunikative Funktionen wie Anrufe tätigen und SMS schreiben, ohne jegliche Hilfe verwenden zu wollen.  
#

## AsTeRICs Grid
# Raumauswahl Grid

![](Images_Grid_Kitchen/01_Main_Grid.jpg)

Das Hauptmenü umfasst die eine Auswahl der 3 verschiedenen Räume.

![](Images_Grid_Kitchen/02_MainKüche_Grid.jpg)

Dies ist das Speziele Grid für die Küche mann kann Licht allgemein ein/ausschalten zudem kann man über eine weitere Schaltfläche in ein untermenü navigiert werden, um die Leds zu dimmen. Um die Temperatur einzustellen, öffnet sich wiederum ein neues Grid. Im Grid Beamer kann der Beamer im Wohnzimmer gesteuert werden. Die Jalousien werden nach Druck auf "Jalousie HOCH" / "Jalousie RUNTER" vollständig herunter/hinauf bewegt, es sei denn es wird "Jalousien STOPP" gedrückt. Zudem verfügt das Grid über ein Radio untergrid.

![](Images_Grid_Kitchen/03_TemperaturMain_Grid.jpg)

Im Temperaturgrid kann die Temperatur auf 20°C, 22°C, 24°C eingestellt werden. Weitere befehle erlauben es die Heizung EIN oder AUS zuschalten sowie Abzusenken.

![](Images_Grid_Kitchen/04_LichtDimmenMain_Grid.jpg)

# TEXT

![](Images_Grid_Kitchen/05_Küche_Beamer_Grid.jpg)

# TEXT

![](Images_Grid_Kitchen/06_Radiosteuerung_Grid.jpg)

# TEXT

## Eingabegeräte
# was das

### FABI - Eingabegerät
- Text?

![](Images_Kitchen/FabiConfig_Mainpage.jpg)

- Text?

![](Images_Kitchen/FabiConfig_Acceleratebutton.jpg)

- Text?

![](Images_Kitchen/FabiConfig_Breakbutton.jpg)

- Text?

![](Images_Kitchen/HillClimbRaceGame01.jpg)

- Text?

![](Images_Kitchen/HillClimbRaceGame02.jpg)

- Text?

https://user-images.githubusercontent.com/95447783/144845615-9a4815f1-15b3-4475-b079-d19f37f21ede.mp4

- Text?

### IR-Trans - Eingabegerät

Der erste Schritt mit dem IR Trans war es die Applikation zu installieren und die IR zu starten.

![](Images_Kitchen/IR_running.PNG)

Danach wurde zur ersten Probe ein IR Signal eingelesen und wieder ausgegeben.

Beim eingeben musste zuerst oben ein „remote name“ festgelegt werden und danach ein Signalname eingestellt werden. Beim ausgeben wurde die Fernbedienung ausgewählt und dazu das zugehörige Signal.

![](Images_Kitchen/IR_ein.PNG)

![](Images_Kitchen/Ir_einst.PNG)

![](Images_Kitchen/IR_aus.PNG)

Um dies nun mit der ARE (Asterics runtime) zu verknüpfen musste zuerst der Funktionsblock eingestellt werden. Dazu wurde zunächst beim „hostname“ der „localhost“ eingestellt. Dann musste der PORT auf 21000 eingestellt werden. Beim schicken des Signals ist es dann sinnvoll beim „prestring “(Der Teil der vor jedem anderen Signal geschickt wird) den Namen der oben erstellten Fernbedienung zu nehmen und bei den „sends“ nur noch den Namen der Signale einzustellen. Aufpassen sollte man jedoch sehr, da bei einem Leerzeichen zu viel das Programm nicht mehr funktioniert. 

![](Images_Kitchen/IR_ast.PNG)

Um dies nun auszuführen kann man in der Asterics-Grid eine „Action“ einstellen. Dazu musste nur noch die Komponente ausgewählt werden und das Signal 1 geschickt werden.

![](Images_Kitchen/IR_grid.PNG)

## Accesibility (iOS)

Das iOS-Betriebssystem enthält Barrierefreiheitsfunktionen, von denen Sie in vielerlei Hinsicht profitieren können – körperliche Aktivität und motorische Fähigkeiten, Zuhören und Lernen sowie viele Interaktionen. Wir erklären Ihnen, wie Sie diese Funktionen konfigurieren und Shortcuts einrichten, um gezielt auf jede Funktion zuzugreifen.

### Farbkorrektur - Einstellungen
Eine Anleitung (Betriebssystem: MacOS) zur Farbkorrektur / Kontrasterhöhung entsprechend den Bedürfnissen der Klientin Sandra:

1. Unter Systemeinstellungen den Unterpunkt „Bedienungshilfen“ anklicken
![](Images_Kitchen/MAC_Settings1.jpeg)

2. „Anzeige“ im Unterreiter „Sehen“ anklicken und den Filtertyp auswählen, nachdem man den Navigationspunkt „Farbfilter“ ausgewählt hat

![](Images_Kitchen/MAC_Settings2.jpeg)
![](Images_Kitchen/MAC_Settings3.jpeg)

3. Kontrasteinstellungen unter dem Navigationspunkt „Display“ modifizieren.
![](Images_Kitchen/MAC_Settings4.jpeg)

(Auch die Kontrasteinstellungen wurden ihren Bedürfnissen gerecht gemacht, da sie wie in der Beschreibung bereits vermerkt, nur Texte und Bilder, die unter einem starken Kontrast stehen, warnehmen kann)

https://user-images.githubusercontent.com/95447783/145011435-095a7594-e634-46a9-83b1-e51f39a477a6.mp4

### Bildschirmlupe - Einstellungen

![](Images_Kitchen/Lupe_MAC.jpeg)
![](Images_Kitchen/Lupe_MAC2.jpeg)

(Hier sieht man die Einstellungen, welche die Bildschirmlupe aktivieren. Die Bildschirmlupe folgt der Maus in einem angemessenen Tempo. Sie wird benötigt, um der Sehschwäche der Klientin entgegenzuwirken)

### Siri - Anwendung (Nachricht)

https://user-images.githubusercontent.com/95447783/145010899-61f14d02-ce41-41c3-a699-3b0ea9cd9658.mp4

### Siri - Anwendung (Anruf)

https://user-images.githubusercontent.com/95447783/145011288-497be48a-d371-412f-82ae-c16f9ab96462.mp4




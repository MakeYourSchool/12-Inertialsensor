Inerstialsensor
----
*(Seeed Studio Grove – IMU 9 DOF v2.0)*

<img src=https://www.makeyourschool.de/wp-content/uploads/2018/10/12_inertialsensor-1024x1024.jpg width=400px>

Bildquelle: *Wissenschaft im Dialog*

Der Grove-IMU ist ein sogenannter neunachsiger Inertialsensor. Inertialsensoren kombinieren mehrere Sensortypen, um jegliche dreidimensionale Bewegung (Verschiebungen und Neigungen in allen Raumrichtungen) zu bestimmen.

Das Gyroskop (siehe Link am Ende der Seite) misst zu jedem Zeitpunkt die Drehraten (Drehgeschwindigkeiten) in allen drei Raumrichtungen. Der Beschleunigungssensor misst die axialen Beschleunigungen in allen drei Raumrichtungen. Theoretisch ist es bereits mit diesen sechs Messwerten möglich, die Bewegung (Verschiebungen und Neigungen in allen Raumrichtungen) nachzuvollziehen. Da insbesondere das Gyroskop oftmals driftet (mit der Zeit verschieben sich die Messwerte), kommt bei diesem IMU zusätzlich ein Magnetometer zum Einsatz. Dieses misst die Magnetfeldstärke in allen drei Raumrichtungen. Dies dient insbesondere dazu, das Erdmagnetfeld als Orientierungsreferenz zu nutzen und die Gesamtmessung immer wieder zu referenzieren. Werden diese Informationen allesamt kombiniert, ist es möglich, die genaue Bewegung des Sensors nachzuvollziehen und so beispielsweise immer dreidimensional die aktuelle Position sowie die Orientierung (Neigung) des Sensors relativ zu einer Startposition zu ermitteln.

Mit diesem Sensor kann beispielsweise ein Handschuh realisiert werden, der die genaue Bewegung der Hand nachvollziehen kann. Damit wäre es zum Beispiel möglich eine Roboterhand zu steuern, welche die gleichen Bewegungen ausführt.

Der Sensor kann direkt oder mithilfe des Grove Shields an einen Arduino angeschlossen werden. Der Sensor kommuniziert hierbei über die seriellen Schnittstellen I2C oder SPI.

----

Im Rahmen von [*Make Your School*](https://www.makeyourschool.de/) finden an Schulen Hackdays statt. Dabei überlegen sich Schülerinnen und Schüler, wie sie ihre Schule mitgestalten und mit technischen und digitalen Tools noch besser machen können. Unterstützt werden sie dabei von Mentorinnen und Mentoren, die die Veranstaltung begleiten und fachliche Impulse geben. *Make Your School* ist ein Projekt von *Wissenschaft im Dialog*. Die Klaus Tschira Stiftung ist bundesweiter Förderer.

Mit diesen **Bibliotheken und Beispiel-Codes** kann der euch vorliegende Sensor/Aktor getestet werden. Den **Mentorinnen und Mentoren von *Make Your School*** steht es frei, die hier zusammengestellten Codes **nach Bedarf und den individuell gemachten Erfahrungen anzupassen**. Beispiele können einfach im Ordner „examples“ hinzugefügt oder bearbeitet werden. Wir werden eure Beiträge regelmäßig prüfen und das Repository mithilfe eurer Änderungsvorschläge aktualisieren.

Das Repository basiert grundlegend auf den veröffentlichten Informationen und Codes von Seeed Studio. Die deutsche Übersetzung stammt von *Make Your School*, Fehlinterpretationen und Änderungen vorbehalten. Die Informationen dürfen frei genutzt, angepasst und verbreitet werden, solange die Lizenzrechte (siehe License.txt) beachtet werden.


**Weitere Informationen:**

[Repository von Seeed Studio](https://github.com/Seeed-Studio/Grove_IMU_9DOF)

[Offizielles Wiki von Seeed Studio](http://wiki.seeedstudio.com/Grove-IMU_9DOF_v2.0/)

[Materialkoffer von *Make Your School*](https://www.makeyourschool.de/material/intertialsensor/)

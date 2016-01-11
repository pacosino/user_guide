# xDrip App

Die xDrip-App ist eine Anwendung (eine App), die auf einem Android-Handy läuft.

Position im Prozessablauf: 
* Ein Dexcom-Sensor liegt auf/unter der Haut und misst den Zucker. 
* Ein Dexcom G4 Transmitter ist auf den Sensor eingelickt und sendet die Zucker-Werte über ein Funk-Protokoll weg. 
* Im regulären Prozess würde die Meldung des Transmitters vom Dexcom-Receiver empfangen und angezeigt. 
* In dem Fall, in dem die xDrip-Ap relevant ist, kann der Dexcom-Receiver entfallen. Die vom Transmitter gesendeten Werte werden von einer selbst gebauten Hardware (xDrip) empfangen und via Bluetooth an ein Android-Handy gesendet.  Auf dem Handy wird die xDrip-App installiert.

Die xDrip-App hat folgende Funktionen:
* 	Empfang von BZ-Messwerten
*	Anzeige (ggf. ansagen) von BZ-Werten 
*	Weiterleiten der Werte an nachgelagerte Systeme (Pebble-Watch, Nightscout)
*	Alarm bei (zuvor individuell definierten) meldewürdigen Werten / Verlauf
*	Export der Werte zur Auswertung in anderen Systemen (zB. SiDiary, Excel)
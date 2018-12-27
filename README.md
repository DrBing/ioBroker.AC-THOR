# Einbindung des MyPV AC•THOR in ioBroker über den ioBroker Modbus-Adapter. #

<img src="https://user-images.githubusercontent.com/819464/50426039-99c46100-0884-11e9-80e0-0c48ba5f803a.jpg"></img>

## my-PV AC•THOR ##

AC•THOR ist ein 0 - 3 kW (6 kW) stufenlos geregelter PV/BHKW Power-Manager für
Warmwasser, elektrische Wärmequellen und optional Heizung.

Durch vielfältige Konfigurationsmöglichkeiten sind mehrere Anwendungsszenarien denkbar.

Ausgiebige Informationen findet man auf https://www.my-pv.com/de/produkte/ac-thor sowie im Handbuch.

So ist es stufenlos möglich bis zu 6 kW über 2 Heizstäbe (zB. je 1 im Warmwasserpuffer und 1 im Brauchwasserpuffer) überschüssige Energie für die Warmwasser-Bereitung und Heizung
zur Verfügug zu stellen.

Durch die stufenlose Regelung kann die Einspeiseleistung theoretisch bis gegen Null ausgeregelt werden.

Sie kann mit Heizstäben in Warmwasser- und oder Pufferspeicher oder auch direkt mit zB. Infrarotheizpanelen verwendet werden.


Die Anbindung an ioBroker erfolgt dabei über den Modbus Adapter
(Dank an Bluefox für den tollen Adapter!)

# 1. Schritt

  Installation des Modbus Adapter.

  Jeder der an diesem Punkt nicht weiß wie man in ioBroker einen Adapter installiert
  sollte sich bitte erst einmal grundsätzlich mit der Installation und Einrichtung
  von ioBroker vertraut machen. ;-)

  Bitte im ioBroker Admin unter Adapter den Modbusadapter auswählen und mit einem Klick auf das "+" Symbol hinzufügen.

# 2. Schritt

  Grundparameter Modbus einstellen

  Nach der Installation des Adapters landen wir automatisch im Konfigurationsmenue.
  Hier bitte die IP-Adresse des AC•THOR eingeben und die anderen Werte wie im Bild ersichtlich einstellen.

  <img src="https://user-images.githubusercontent.com/819464/50450841-b4541400-0930-11e9-9384-e9076f846303.jpg"></img>

# 3. Schritt

   Kopieren und Einfügen der Registereinstellungen
   ...

# 4. Inbetriebnahme und Regelung

<img src="https://user-images.githubusercontent.com/819464/50450514-e6fd0d00-092e-11e9-8232-76c392d5bdfd.jpg"></img>

  ...





## Changelog

  ### 0.1.0 (25.12.2018)
* First (Initial) Version.


## License
The MIT License (MIT)

Copyright (c) 2018 Jedo <nospam@biglinux.de>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

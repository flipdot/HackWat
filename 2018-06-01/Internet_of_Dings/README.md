Der Talk beschreibt die Schritte zur Entwicklung der Hardware, mit der der
Ruhestrombedarf eines batteriebetriebenen Sensors mit einem ESP8266 von 300µA
im Sleep Mode durch den Einsatz eines separaten Mikrocontrollers auf 120 nA
gesenkt werden konnte.Der ESP wird dabei komplett abgeschaltet, und der
Controller Attiny45 durch einen Interrupt bei Betätigung eines Schalters aus
seinem Sleep Mode geweckt.

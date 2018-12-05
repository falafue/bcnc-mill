# Fräse FabLab Fürth

## Vor Inbetriebnahme:

* Bevor die Maschine gestartet wird, muss eine Sichtprüfung erfolgen. Hierbei muss geprüft werden, ob:

  * der Fräsraum frei von Verschmutzung ist. (Keine Späne bzw. Frästeile von Vorgängern.)
  * welcher Fräser in der Maschine eingespannt ist.
  * die richtige Überwurfmutter für den eigenen Fräser vorhanden ist.
  * die Endkontaktschalter nicht betätigt sind. (In diesem Fall muss die Achse händisch bewegt werden.)
  * der Frästisch die benötigte Form (Alu-Profil Konfiguration) hat, um sein Werkstück einzuspannen.

## Inbetriebnahme:

* Als erstes muss der Rechner eingeschaltet werden. (Kleines schwarzes Kästchen hinter dem Monitor. Beim Start wird **kein** Passwort benötigt.)
* bCNC mit einem Doppelklick starten.
* Den Notausknopf im Uhrzeigersinn lösen. (Wenn er sich nicht bewegt, dann ist er schon lose.)
* Die Maschine mit einem Druck auf den grünen Eintaster einschalten. (Die Maschine macht einen kurzen Ruck sobald das Netzteil läuft.)
* Im bCNC auf die Schaltfläche "Referenzfahrt" klicken. (Vorher geht nichts.)

## Wichtiges zu bCNC:

* Verändern der Software und Einbauen von Plugins darf nur durch Rainer Roscher geschehen.
* Die Maschine fährt die Referenzpunkte bei X und Y ins Minus und bei Z ins Plus. Die absolute Mschinenposition wird in der Zeile MPos angezeigt.
* Der Nullpunkt unseres Werkstücks wird in der Zeile WPos angezeigt.
* Ein vollständiges Handbuch für die Software findet Ihr unter 
  [https://github.com/vlachoudis/bCNC/wiki](https://github.com/vlachoudis/bCNC/wiki)


## Eckdaten:

* Bauraum bis Mittelpunkt Frässpindel: X 400mm / Y 398mm / Z 170mm
* Maximale Drehzahl Frässpindel 29000 U/min.
* Maximale Vorschubgeschwindigkeit: X und Y 500 mm/min, Z 400 mm/min
* Betrieb mit 24V Schutzkleinspannung.
* Vorhandene Überwurfmuttern: 2mm, 2.35mm, 3mm, 3.175mm, 4mm, 6mm, 8mm.
* Absaugung der Späne. (Saugkraft manuell einstellbar.)


## Hinweise

#### Alarm
* Alarm auslesen: Klick auf den Alarm.
* Alarm löschen: Reset + Freigabe anklicken.

#### Antasten elektrisch / mechanisch
* Der mechanische Tastkopf benötigt invertiertes Signal: 
  Werkzeuge -> Controller ->  Einstellungen -> Antasten Signal umkehren [x] (Häkchen gesetzt!)
* Elektrisches Antasten benötigt normales Signal: 
  Werkzeuge -> Controller ->  Einstellungen -> Antasten Signal umkehren [ ] (Häkchen nicht gesetzt!)
* Nach dem Umschalten einer Einstellung: Werkzeuge -> Controller ... Feld mit Zahnrad anklicken, grüner Fortschrittsbalken fährt. Evtl. 2x, 3x machen.

#### Schnellstopp
Empfehlung: Bei "Angstfahrten" immer eine Hand an der Tür.

* Tür öffnen pausiert sofort alle Antriebe. Nach Türschliessen und grünem Taster kann mit Klick auf das Rechtsdreieck fortgefahren werden.
* Notaustaster geht auch immer. Danach kann aber nicht fortgefahren werden.
* Funktionstaste F12: STOP. (Erreicht gleichen Zustand wie Tür auf)

#### Bildschirmschoner
* Passwort: odroid
* Tastatur geht nicht mehr, wenn der Bildschirmschoner zuschlägt.



Uglybox
========

In a Daily Greens system, Uglybox is responsible for control tasks
hosting all of the necessary electronics in a single waterproof
container.

The end user or system installer is not expected to open an Uglybox,
as there are 240VAC parts inside. The whole idea is that of a black
box.


Parts for an Uglybox
--------------------

Daily Greens team internal information:

   Part name   | part function |     size   |  price  | ref.
---------------|---------------|------------|---------|------
Raspberry Pi   | controller    |    85x56   |  39,99  | partco RASPBERRY PIB+
Wi-Fi          | communication |     10     |  14,90  | partco DK USB WLAN 2
Relay 1        | control pump  |    74x44   |   5,95  | partco RELAYMOD 1
Relay 2        | control light |    74x44   |   5,95  | partco RELAYMOD 1
Sugarpiece (!) | power         |     nvm    |   2,06  | partco RUUVIKLS 2,5
Holkkitiiviste | power pump    |  Ø3-6,5mm  |   0,99  | partco MG12
Holkkitiiviste | power lamp    |  Ø6-12mm   |   1,18  | partco MG20 
Holkkitiiviste | power input   |  Ø6-12mm   |   1,18  | partco MG20 
Suko jatko     | power input   |    klunk   |   2,36  | partco SUKO JATKO VAL
USB brick      | power input   |    klunk   |  10,42  | partco PCC NOK LAT 6
Box            | box           | 56x180x125 |  15,13  | partco KOT 11-26T
Avahi-Daemon   | discovery     |     nvm    |   0,00  | ELL-i
uglybox.sh     | software      |     nvm    |   0,00  | ELL-i
---------------|---------------|------------|---------|--------
                                              100,11

box layout:



  56       74    30    = 160 mm

 WW                    10
+-----++-------+ XX
|R    || Relay | XX
|a    ||   1   | XX
|s    |+-------+ XX    88
|p    |+-------+ XX
|     || Relay | XX
|     ||   2   | XX
+-----++-------+ XX
                       = 98 mm

thickness with insulator 30 mm


so the box should measure internally at least
1) 160 x 98 x 80
2) 200 x 98 x 35

 component  |  dimension 1
------------|-------------
raspi b+    | 85
Wi-Fi       | 10


component   | dimension 2
------------|------------
raspi b+    | 56
relay 1&2   | 74


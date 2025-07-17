# Connectors

## Power

5v-12v power in to the connector box and keyboard (via the keyboard/host port).

3 Pin Mini Din female on the connector box.

* 1: 0v
* 2: +12v
* 3: +12v
* Shell: --

0v is connected to the host shell, and all USB shells, but not the serial/keyboard/misc shells

## Host

Data and power connection between the keyboard and connector box.

Half-pitch centronics 36 (HPCN36) female on both devices, using a HPCN36 male cable.

* A 01: 0v
* B 02: 
* A 03: 
* B 04: 
* A 05: 12v
* B 06: 
* A 07: 
* B 08: 
* A 09: 
* B 10: 
* A 11: 0v
* B 12: 
* A 13: 
* B 14: 
* A 15: 
* B 16: 
* A 17: 
* B 18: 12v
* C 19: 0v
* D 20: 
* C 21: 
* D 22: 
* C 23: 
* D 24: 
* C 25: 
* D 26: 
* C 27: 
* D 28: 
* C 29: 
* D 30: 
* C 31: 
* D 32: 
* C 33: 
* D 34: 
* C 35: 
* D 36: 12v
* Shell: 0v

## "keyboard interface"

15-pin d-sub DA15 male

* 01: 
* 02: 0v
* 03: 0v
* 04: 0v
* 05: 12v
* 06: 12v
* 07: 12v
* 08: 
* 09: 
* 10: Hostport A Tx - keyboard slave/master
* 11: Hostport A Rx - keyboard slave/master
* 12: 
* 13: Hostport B Tx - keyboard slave/master
* 14: Hostport B Rx - keyboard slave/master
* 15: 
* Shell: --

## PS/2 keyboard/mouse port 1/2

6-pin mini DIN female.

* 1: Data
* 2: --
* 3: 0v
* 4: +5v
* 5: Clock
* 6: --
* Shell: 0v

## Sun port 3

8-pin mini DIN female.

* 1: 0v
* 2: 0v
* 3: +5v
* 4: Mouse from
* 5: Keyboard to
* 6: Keyboard from
* 7: --
* 8: +5v
* Shell: 0v

## Serial keyboard/mouse port 4/5

9-pin d-sub DE9 male.

* 1: Data carrier detect (DCD)
* 2: Rx - keyboard slave/master
* 3: Tx - keyboard slave/master
* 4: Data terminal ready (DTR)
* 5: 0v
* 6: Data set ready (DSR)
* 7: Request to send (RTS)
* 8: Clear to send (CTS)
* 9: Ring indicator
* Shell: --

## Misc port 6

15-pin d-sub DA15 female

* 01: 
* 02: 
* 03: 
* 04: 
* 05: Tx or Rx
* 06: 
* 07: 
* 08: 
* 09: 
* 10: 
* 11: 
* 12: 
* 13: 
* 14: Tx or Rx
* 15: 0v
* Shell: --

## USB

* 1: V+ 5v
* 2: D-
* 3: D+
* 4: V- 0v
* Shell: 0v

## Jumpers

* J1
* J4
* J5

* J18
* J19

* J20
* J23
* J24
* J25 Y

* J34
* J35 Y

* J40 Y
* J41 Y
* J42
* J43
* J44
* J45
* J47
* J48
* J49
* J50 Y

* J46 (jtag?)

* J16 (3pin)
* J17 (3pin)

# Beverage Flow Meters Board #

These are the hardware design files for the project "Beverage Flow Meters", a drinks dispensing flow meter control for Beer, Wines and Spirits

### Summary ###
The board is designed specifically as a flow-measurement solution for the drink dispensing industries including beer, wines and spirits.

### How do I get set up? ###

    $ git clone https://github.com/blackbliss/beverage-flow-meters-board.git

### What's included ###

* **Datasheets** — Datasheets for the various components.
* **EAGLE** — Schematic and board files
* **Gerber** — Complete set of Gerber files for the current version of the project.

### Hardware connections ###

    +-----------------+
    |          D0 [16]| ---> Status LED
    |          D1 [05]| ---> I2C SDA (to PCF8574)
    |          D2 [04]| ---> I2C SCL (to PCF8574)
    |          D4 [02]| <--- Ball sensor (water presence)
    |              3V3| ----
    |              GND| ----
    |          D5 [14]| <--- Distance sensor TRIG
    |          D6 [12]| <--- Distance sensor ECHO
    |          D7 [13]| ----
    |          D8 [15]| ----
    |          D9 [03]| ----
    |          D10[01]| ----
    |              GND| ----
    |              3V3| ----
    +-----------------+

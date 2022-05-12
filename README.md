# ESP32-C3 custom minimal Dev board
<img src="/PCB.png">

This board based on ESP32-C3-MINI-1. To reduce power consumption for battery operations and PCB dimension, dedicated USB to UART converter not used. The USB directly connected to Serial/JTAG controller of ESP32-C3 (GPIO18 and GPIO19). This can be used as CDC-ACM virtual serial port, programming embedded/external flash, CPU debugging with compact JTAG instructions.

### The power jumper should shorted with a shunt for normal operations. This pins are helpful for measuring current consumption (fast switching currents) using power analyzers(PPK2, Otii Arc etc).

# mSD-Breakout
Breakout with microSD socket and level shifter.

[![mSD-Breakout](https://raw.github.com/watterott/mSD-Breakout/master/pcb/mSD-Breakout_v10.jpg)](http://www.watterott.com/en/mSD-Breakout)


## Shop
* [mSD-Breakout](http://www.watterott.com/en/mSD-Breakout)


## Features
* microSD socket (SPI) support SD and SDHC cards (up to 32GB)
* 5V tolerant inputs (level shifter)
* on-board 3.3V voltage regulator


## Hardware and Software
* [Schematics + Layout](https://github.com/watterott/mSD-Breakout/tree/master/pcb)

* Arduino Uno Connection (Example Sketch: ```File->Examples->SD->CardInfo```):
    ```
    Uno -> Breakout
    ---------------
    5V  -> 5V
    GND -> GND
    D13 -> CLK
    D12 -> DO (MISO)
    D11 -> DI (MOSI)
    D4  -> CS
    ```

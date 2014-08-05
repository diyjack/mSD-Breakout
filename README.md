# mSD-Breakout
Breakout with microSD socket and level shifter.

Shop: [mSD-Breakout](http://www.watterott.com/en/mSD-Breakout)

![mSD-Breakout](https://raw.github.com/watterott/mSD-Breakout/master/img/msd-breakout.jpg)


## Features
* microSD socket
* 5V tolerant inputs (level shifter)
* on-board 3.3V voltage regulator


## Hardware
* [Schematics + Layout](https://github.com/watterott/mSD-Breakout/tree/master/pcb)

* Arduino Uno Connection (Example Sketch: File->Examples->SD->CardInfo):
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

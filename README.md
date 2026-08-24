# SevenSegmentTM1637

Library for using a 4 digit seven segment display with TM1636 or TM1637 driver IC. Extensive library for controlling a 4 digit seven segment display. This library inherent the Print class and uses the LCDAPI 1.0. For example you can use all normal Print methods like: print() and println(). From the LCDAPI among others begin(), clear(), home(), setCursor() and setBacklight() are implementend. On top of these regular functionality a segerate fun class which adds more features can be used. For example a bombtimer(), nightrider() and bouncingBall() method can be used when using the fun class. Original author: Bram Harmsen <bramharmsen@gmail.com>. This is Dave Robinson's working copy from the Arduino `libraries` tree. Version recorded in `library.properties`: 1.1.0. Upstream: <https://github.com/bremme/arduino-tm1637>.

**Source last updated:** 2020-07-04  
**Language:** C++ / Arduino  
**Target:** Arduino (avr)  
**Output:** Arduino library

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `SevenSegmentTM1637` | C++ / Arduino | library | Library for using a 4 digit seven segment display with TM1636 or TM1637 driver IC |
| `Basic` | C++ / Arduino | example sketch | `examples/Basic/Basic.ino` |
| `ExtClock` | C++ / Arduino | example sketch | `examples/ExtClock/ExtClock.ino` |
| `ExtScoreboard` | C++ / Arduino | example sketch | `examples/ExtScoreboard/ExtScoreboard.ino` |
| `FunPrintAll` | C++ / Arduino | example sketch | `examples/FunPrintAll/FunPrintAll.ino` |
| `FunPrintLevel` | C++ / Arduino | example sketch | `examples/FunPrintLevel/FunPrintLevel.ino` |
| `LowLevel` | C++ / Arduino | example sketch | `examples/LowLevel/LowLevel.ino` |
| `PrintNumber` | C++ / Arduino | example sketch | `examples/PrintNumber/PrintNumber.ino` |
| `SerialPrint` | C++ / Arduino | example sketch | `examples/SerialPrint/SerialPrint.ino` |

## How to open

Install this folder as an Arduino library (Sketch → Include Library → Add .ZIP Library, or copy into `libraries/SevenSegmentTM1637`). Open any `examples/*.ino` from the Arduino IDE.

## Attribution and provenance

- **Original author / maintainer:** Bram Harmsen <bramharmsen@gmail.com>
- **library.properties name:** SevenSegmentTM1637
- **Version:** 1.1.0
- **Upstream URL:** <https://github.com/bremme/arduino-tm1637>
- **Category:** Display
- This repository is Dave Robinson's working copy for catalogue/reference; authorship stays with the original authors.

## License

Original upstream license terms in this tree (where recorded). This repository does not claim authorship of the upstream library. See `THIRD_PARTY_NOTICES.md`. The `LICENSE` file added at import is a VaderConsulting MIT wrapper and does not replace upstream terms.

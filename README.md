# edgy_board number b152
This design is part of the [edgy board project](https://github.com/skunkforce/edgy_boards). It provides a step-down DCDC sourcing 5V from pin 10 and converting it to 3.3V on pin 9 using the [TPS564201](https://datasheet.lcsc.com/lcsc/2010141804_Texas-Instruments-TPS564201DDCR_C464812.pdf). Due to the high current capability pin headers are also provided.


![](/board/board.png)

# getting started
This repository uses submodules. After cloning use the command 

```$ git submodule update --init --recursive```

to pull the submodules before opening the project with kicad. 

# Tests
Tests can be found in [TESTS.md](TESTS.md)


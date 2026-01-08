# HodgePodge

A keyboard, using things I had lying around, for example a NRF52840-DK devcard, ec11 encoder, some weird display from Ali express.

---;

## Display, Pin, Cable color

VCC,VDD (3.3V)            - Green
GND,GND                   - Brown
SCL (Clock),P0.27         - Blue
SDA (MOSI),P0.26          - Yellow
RES (Reset),P0.05         - Orange
DC (Data/Cmd),P0.06       - Red
CS (Chip Select),P0.08    - Black
BLK (Backlight),P0.07     - White

___;

## Wiring

Row 0 - Black
Row 1 - Red
Row 2 - White
Row 3 - Gray

### Right half

Col 12   - Purple
Col 11   - Green
Col 10   - Brown
Col 9    - Yellow
Col 8    - Blue
Col 7    - Orange

### Left half

Col 1   - Purple
Col 2   - Green
Col 3   - Brown
Col 4   - Yellow
Col 5   - Blue
Col 6   - Orange

---;

### Temporary wiring to NRF52845 while I wait on the pro micros

Row 0 - Black - P1.12
Row 1 - Red   - P1.13
Row 2 - White - P1.14
Row 3 - Gray  - P1.15

## Right half pins

Col 12 - Purple - P1.08
Col 11 - Green  - P1.07
Col 10 - Brown  - P1.06
Col 9  - Yellow - P1.05
Col 8  - Blue   - P1.04
Col 7  - Orange - P1.03


## Left half pins

Col 1 - Purple - P0.03
Col 2 - Green  - P0.04
Col 3 - Brown  - P0.28
Col 4 - Yellow - P0.29
Col 5 - Blue   - P0.30
Col 6 - Orange - P0.31

---;

## Notes

nrfutil device program --firmware hodgepodge-nrf52840dk_nrf52840-zmk.bin --traits jlink --options chip_erase_mode=ERASE_ALL

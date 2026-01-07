# NOTES, WILL FLESH OUT

## flashing

nrfutil device program --firmware ~/Downloads/hodgepodge-nrf52840dk_nrf52840-zmk.bin --traits jlink --options chip_erase_mode=ERASE_ALL



### Display, Pin, Cable color

VCC,VDD (3.3V)            - Grön
GND,GND                   - Brun
SCL (Clock),P0.27         - Blå
SDA (MOSI),P0.26          - Gul
RES (Reset),P0.05         - Orange
DC (Data/Cmd),P0.06       - Röd
CS (Chip Select),P0.08    - Svart
BLK (Backlight),P0.07     - Vit



set up a custom binding so we can try SPI mode 3
add a hard test screen (solid color) to remove LVGL from the equation.

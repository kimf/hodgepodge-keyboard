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

Col 12 - Purple - P1.03
Col 11 - Green  - P1.04
Col 10 - Brown  - P1.05
Col 9  - Yellow - P1.06
Col 8  - Blue   - P1.07
Col 7  - Orange - P1.08


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

---;

<details>
<summary>
Shield Wizard Debug Information
</summary>

In case of broken configuration, here is the Shield Wizard internal data used to generate this configuration:

Commit: b1abd5f84e8910e1c18c5f4957144f832c09b2b6

```json
{"name":"HodgePodge","shield":"hodgepodge","dongle":false,"layout":[{"id":"01KEFV0TPH2PFNKCWVVR3XKK7T","part":0,"row":0,"col":0,"w":1,"h":1,"x":0,"y":0.37,"r":0,"rx":0,"ry":0},{"id":"01KEFV0TPH77E8QDV247AYEN5D","part":0,"row":0,"col":1,"w":1,"h":1,"x":1,"y":0.37,"r":0,"rx":0,"ry":0},{"id":"01KEFV0TPHPXZ22BZCCNNYANDH","part":0,"row":0,"col":2,"w":1,"h":1,"x":2,"y":0.12,"r":0,"rx":0,"ry":0},{"id":"01KEFV0TPH402JTVW7GT3KHTDJ","part":0,"row":0,"col":3,"w":1,"h":1,"x":3,"y":0,"r":0,"rx":0,"ry":0},{"id":"01KEFV0TPH139PP7Y6S6A9SPAG","part":0,"row":0,"col":4,"w":1,"h":1,"x":4,"y":0.12,"r":0,"rx":0,"ry":0},{"id":"01KEFV0TPHAZBZTH6WTWJ78MC9","part":0,"row":0,"col":5,"w":1,"h":1,"x":5,"y":0.24,"r":0,"rx":0,"ry":0},{"id":"01KEFV0TPHZTAXPX7T7MQWG9EY","part":0,"row":0,"col":6,"w":1,"h":1,"x":8,"y":0.24,"r":0,"rx":0,"ry":0},{"id":"01KEFV0TPH77KPE1Z6C2F4ZS1B","part":0,"row":0,"col":7,"w":1,"h":1,"x":9,"y":0.12,"r":0,"rx":0,"ry":0},{"id":"01KEFV0TPHTA15TFJXZ37HMX1R","part":0,"row":0,"col":8,"w":1,"h":1,"x":10,"y":0,"r":0,"rx":0,"ry":0},{"id":"01KEFV0TPH1H2QDFFP5J9XCDC2","part":0,"row":0,"col":9,"w":1,"h":1,"x":11,"y":0.12,"r":0,"rx":0,"ry":0},{"id":"01KEFV0TPHFKJSZ6EPPVQRFE1K","part":0,"row":0,"col":10,"w":1,"h":1,"x":12,"y":0.37,"r":0,"rx":0,"ry":0},{"id":"01KEFV0TPHFRDCS3WAKYZ3A96F","part":0,"row":0,"col":11,"w":1,"h":1,"x":13,"y":0.37,"r":0,"rx":0,"ry":0},{"id":"01KEFV0TPHSYGDXW6B3N2YPN0G","part":0,"row":1,"col":0,"w":1,"h":1,"x":0,"y":1.37,"r":0,"rx":0,"ry":0},{"id":"01KEFV0TPHRTXTEYBKVX2G7RHF","part":0,"row":1,"col":1,"w":1,"h":1,"x":1,"y":1.37,"r":0,"rx":0,"ry":0},{"id":"01KEFV0TPH2F5SAGHV2GNJ6VC6","part":0,"row":1,"col":2,"w":1,"h":1,"x":2,"y":1.12,"r":0,"rx":0,"ry":0},{"id":"01KEFV0TPH9FWTD05WXCR718EY","part":0,"row":1,"col":3,"w":1,"h":1,"x":3,"y":1,"r":0,"rx":0,"ry":0},{"id":"01KEFV0TPHPRGKPMCP7378R26E","part":0,"row":1,"col":4,"w":1,"h":1,"x":4,"y":1.12,"r":0,"rx":0,"ry":0},{"id":"01KEFV0TPH9WGXY6EPX7A8P23X","part":0,"row":1,"col":5,"w":1,"h":1,"x":5,"y":1.24,"r":0,"rx":0,"ry":0},{"id":"01KEFV0TPHJJSMN5W29WCSVDAE","part":0,"row":1,"col":6,"w":1,"h":1,"x":8,"y":1.24,"r":0,"rx":0,"ry":0},{"id":"01KEFV0TPH78JBNBFA8QVDH1DP","part":0,"row":1,"col":7,"w":1,"h":1,"x":9,"y":1.12,"r":0,"rx":0,"ry":0},{"id":"01KEFV0TPHD4NX0QP1NQAK0SKB","part":0,"row":1,"col":8,"w":1,"h":1,"x":10,"y":1,"r":0,"rx":0,"ry":0},{"id":"01KEFV0TPH167QCAYXPAF5EC96","part":0,"row":1,"col":9,"w":1,"h":1,"x":11,"y":1.12,"r":0,"rx":0,"ry":0},{"id":"01KEFV0TPHPF803WF1P0MCTXE8","part":0,"row":1,"col":10,"w":1,"h":1,"x":12,"y":1.37,"r":0,"rx":0,"ry":0},{"id":"01KEFV0TPH23JXWG7VNJYFY5FB","part":0,"row":1,"col":11,"w":1,"h":1,"x":13,"y":1.37,"r":0,"rx":0,"ry":0},{"id":"01KEFV0TPHWB2QH40AV5C62P50","part":0,"row":2,"col":0,"w":1,"h":1,"x":0,"y":2.37,"r":0,"rx":0,"ry":0},{"id":"01KEFV0TPHJS79PW7XJGT17FFB","part":0,"row":2,"col":1,"w":1,"h":1,"x":1,"y":2.37,"r":0,"rx":0,"ry":0},{"id":"01KEFV0TPH2XBSP1P8JHVAJG86","part":0,"row":2,"col":2,"w":1,"h":1,"x":2,"y":2.12,"r":0,"rx":0,"ry":0},{"id":"01KEFV0TPHNFJC3VQVJVGHAHF2","part":0,"row":2,"col":3,"w":1,"h":1,"x":3,"y":2,"r":0,"rx":0,"ry":0},{"id":"01KEFV0TPH22JNV4QKH40FQ755","part":0,"row":2,"col":4,"w":1,"h":1,"x":4,"y":2.12,"r":0,"rx":0,"ry":0},{"id":"01KEFV0TPHS5N2RQF8HQD2A0SG","part":0,"row":2,"col":5,"w":1,"h":1,"x":5,"y":2.24,"r":0,"rx":0,"ry":0},{"id":"01KEFV0TPH7VXRV6YXVQ1YJ8KC","part":0,"row":2,"col":6,"w":1,"h":1,"x":8,"y":2.24,"r":0,"rx":0,"ry":0},{"id":"01KEFV0TPHQX8S211V151BQV2S","part":0,"row":2,"col":7,"w":1,"h":1,"x":9,"y":2.12,"r":0,"rx":0,"ry":0},{"id":"01KEFV0TPHBEXP2Y0C0K4X1EEE","part":0,"row":2,"col":8,"w":1,"h":1,"x":10,"y":2,"r":0,"rx":0,"ry":0},{"id":"01KEFV0TPHTRZAHZ350E2NBWD8","part":0,"row":2,"col":9,"w":1,"h":1,"x":11,"y":2.12,"r":0,"rx":0,"ry":0},{"id":"01KEFV0TPHRN23HDMFFMYAKABF","part":0,"row":2,"col":10,"w":1,"h":1,"x":12,"y":2.37,"r":0,"rx":0,"ry":0},{"id":"01KEFV0TPHTW09CY7NADEKBN36","part":0,"row":2,"col":11,"w":1,"h":1,"x":13,"y":2.37,"r":0,"rx":0,"ry":0},{"id":"01KEFV0TPHDRSS0TPWQJHGJS7Z","part":0,"row":3,"col":3,"w":1,"h":1,"x":3.5,"y":3.12,"r":0,"rx":0,"ry":0},{"id":"01KEFV0TPH774VBT6XTPBG9M8F","part":0,"row":3,"col":4,"w":1,"h":1.5,"x":4.5,"y":3.12,"r":12,"rx":4.5,"ry":4.12},{"id":"01KEFV0TPH6YVBMA14S3VTRV7K","part":0,"row":3,"col":5,"w":1,"h":1,"x":5.23,"y":3.33,"r":24,"rx":5.23,"ry":4.83},{"id":"01KEFV0TPH7ZCHTNE3QHPNZFR8","part":0,"row":3,"col":6,"w":1,"h":1,"x":7.77,"y":3.33,"r":-24,"rx":8.77,"ry":4.83},{"id":"01KEFV0TPHCQTDMETSNB09MF6B","part":0,"row":3,"col":7,"w":1,"h":1.5,"x":8.5,"y":3.12,"r":-12,"rx":9.5,"ry":4.12},{"id":"01KEFV0TPHSMJGZPBB9WE9ZMD9","part":0,"row":3,"col":8,"w":1,"h":1,"x":9.5,"y":3.12,"r":0,"rx":0,"ry":0}],"parts":[{"name":"unibody","controller":"xiao_ble_plus","wiring":"matrix_diode","keys":{"01KEFV0TPH2PFNKCWVVR3XKK7T":{"input":"d10","output":"d1"},"01KEFV0TPH77E8QDV247AYEN5D":{"input":"d10","output":"d2"},"01KEFV0TPHPXZ22BZCCNNYANDH":{"input":"d10","output":"d3"},"01KEFV0TPH402JTVW7GT3KHTDJ":{"input":"d10","output":"d4"},"01KEFV0TPH139PP7Y6S6A9SPAG":{"input":"d10","output":"d5"},"01KEFV0TPHAZBZTH6WTWJ78MC9":{"input":"d10","output":"d6"},"01KEFV0TPHZTAXPX7T7MQWG9EY":{"input":"d10","output":"d11"},"01KEFV0TPH77KPE1Z6C2F4ZS1B":{"input":"d10","output":"d12"},"01KEFV0TPHTA15TFJXZ37HMX1R":{"input":"d10","output":"d13"},"01KEFV0TPH1H2QDFFP5J9XCDC2":{"input":"d10","output":"d14"},"01KEFV0TPHFKJSZ6EPPVQRFE1K":{"input":"d10","output":"d15"},"01KEFV0TPHFRDCS3WAKYZ3A96F":{"input":"d10","output":"d17"},"01KEFV0TPHSYGDXW6B3N2YPN0G":{"input":"d9","output":"d1"},"01KEFV0TPHRTXTEYBKVX2G7RHF":{"input":"d9","output":"d2"},"01KEFV0TPH2F5SAGHV2GNJ6VC6":{"input":"d9","output":"d3"},"01KEFV0TPH9FWTD05WXCR718EY":{"input":"d9","output":"d4"},"01KEFV0TPHPRGKPMCP7378R26E":{"input":"d9","output":"d5"},"01KEFV0TPH9WGXY6EPX7A8P23X":{"input":"d9","output":"d6"},"01KEFV0TPHJJSMN5W29WCSVDAE":{"input":"d9","output":"d11"},"01KEFV0TPHD4NX0QP1NQAK0SKB":{"input":"d9","output":"d13"},"01KEFV0TPH78JBNBFA8QVDH1DP":{"input":"d9","output":"d12"},"01KEFV0TPH167QCAYXPAF5EC96":{"input":"d9","output":"d14"},"01KEFV0TPHPF803WF1P0MCTXE8":{"input":"d9","output":"d15"},"01KEFV0TPH23JXWG7VNJYFY5FB":{"input":"d9","output":"d17"},"01KEFV0TPHWB2QH40AV5C62P50":{"input":"d8","output":"d1"},"01KEFV0TPHJS79PW7XJGT17FFB":{"input":"d8","output":"d2"},"01KEFV0TPH2XBSP1P8JHVAJG86":{"input":"d8","output":"d3"},"01KEFV0TPHNFJC3VQVJVGHAHF2":{"input":"d8","output":"d4"},"01KEFV0TPH22JNV4QKH40FQ755":{"input":"d8","output":"d5"},"01KEFV0TPHS5N2RQF8HQD2A0SG":{"input":"d8","output":"d6"},"01KEFV0TPH7VXRV6YXVQ1YJ8KC":{"input":"d8","output":"d11"},"01KEFV0TPHQX8S211V151BQV2S":{"input":"d8","output":"d12"},"01KEFV0TPHTRZAHZ350E2NBWD8":{"input":"d8","output":"d14"},"01KEFV0TPHBEXP2Y0C0K4X1EEE":{"input":"d8","output":"d13"},"01KEFV0TPHRN23HDMFFMYAKABF":{"input":"d8","output":"d15"},"01KEFV0TPHTW09CY7NADEKBN36":{"input":"d8","output":"d17"},"01KEFV0TPHDRSS0TPWQJHGJS7Z":{"input":"d7","output":"d4"},"01KEFV0TPH774VBT6XTPBG9M8F":{"input":"d7","output":"d5"},"01KEFV0TPH6YVBMA14S3VTRV7K":{"input":"d7","output":"d6"},"01KEFV0TPH7ZCHTNE3QHPNZFR8":{"input":"d7","output":"d11"},"01KEFV0TPHCQTDMETSNB09MF6B":{"input":"d7","output":"d12"},"01KEFV0TPHSMJGZPBB9WE9ZMD9":{"input":"d7","output":"d13"}},"pins":{"d7":"input","d8":"input","d9":"input","d10":"input","d1":"output","d2":"output","d3":"output","d4":"output","d5":"output","d6":"output","d11":"output","d12":"output","d13":"output","d14":"output","d15":"output","d17":"output"},"buses":[{"type":"spi","name":"spi0","devices":[]},{"type":"spi","name":"spi1","devices":[]},{"type":"spi","name":"spi2","devices":[]},{"type":"spi","name":"spi3","devices":[]},{"type":"i2c","name":"i2c0","devices":[]},{"type":"i2c","name":"i2c1","devices":[]}]}]}
```

</details>

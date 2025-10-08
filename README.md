# foc-hw
My foc driver board

3 shunt, 12V 50A max.

## power

buck & motor share the 12V supply

- [x] buck chip - tps62130, output 3.3v
- [x] protect - rc snubber, 10Ω, 10nF
- [x] protect - bidirectional tvs, smbj15ca


## bridge

- [x] 3-phase bridge driver - drv8323rsrgzr
- [x] mos - iauc100n04s6n022
- [x] gate protect - 500mΩ, smbj15ca
- [x] gate pulldown - 100kΩ


## MCU

- [x] protect - lr supply, 1uh 500mΩ
- [x] sdram - is42s32800j-6bli
- [x] qspi flash - mx25l25645gz2i-08g
- [x] emmc - klmag2gend-b031


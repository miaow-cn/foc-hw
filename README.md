# foc-hw
My foc driver board

3 shunt, 12V 50A max.

## power

buck & motor share the 12V supply

- [x] buck chip - tps62130, output 3.3v
- [x] protect - rc snubber, 10Ohm, 10nF
- [x] protect - bidirectional tvs, smbj15ca


## bridge

- [x] 3-phase bridge driver - drv8323rsrgzr
- [x] mos - iauc100n04s6n022
- [x] gate protect - rc, 1Ohm, smbj15ca
- [x] gate pulldown - 47KOhm


## MCU

- [x] protect - lr supply, 1uh 1Ohm

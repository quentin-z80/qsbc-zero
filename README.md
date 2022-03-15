# qsbc-zero

## About

Specs:

- i.MX6ULL ARM Cortex-A7
- 512MB DDR3L
- 64MB QSPI Flash
- MicroSD card slot
- USB Type-C DRP and USB Type-A port
- 10/100M Ethernet
- Dual 36 pin GPIO headers
- PF1510 PMIC
- USB Type-C Power in

![](img/qsbc-zero_top.png)
![](img/qsbc-zero_bottom.png)


## TODO

### Rev 1.1
- R2 and R5 PN is wrong
- Some Ratings do not match PNs
- Move USB Type-A connector, so lip does not hit board

### Rev 2
- Use interrupt for ETH PHY
- Fix LED order on PCB
- Swap USB-A and USB-C data port

### Linux
- Port PF1510 Driver
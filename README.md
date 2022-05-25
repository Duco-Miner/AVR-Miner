# AVR-Miner

The AVR-Miner Board forms the Slave Device controlled by the [ESP32-Miner](https://github.com/Duco-Miner/ESP32-Miner) in the DUCO-Miner Rack. The [Common Miner Baseboard](https://github.com/Duco-Miner/Common-Miner-Baseboard) uses multiple AVR-Miner Boards for Mining the Duno Coin.

These are the KiCAD Project files for the AVR-Miner Board PCB.

Please feel free to modify the design files as per your requirements. Improvements are always appreciated !!!

---
### Preview:

1) PCB View 1:

![AVR-Miner](https://github.com/Duco-Miner/AVR-Miner/blob/18e8f97630ff8491f35998306b474113af62d5f5/IMAGES/AVR-MINER-PCB-1.png)

2) PCB View 2:

![AVR-Miner](https://github.com/Duco-Miner/AVR-Miner/blob/18e8f97630ff8491f35998306b474113af62d5f5/IMAGES/AVR-MINER-PCB-2.png)

3) PCB Front View:

![AVR-Miner](https://github.com/Duco-Miner/AVR-Miner/blob/18e8f97630ff8491f35998306b474113af62d5f5/IMAGES/AVR-MINER-PCB-3.png)

4) PCB Back View:

![AVR-Miner](https://github.com/Duco-Miner/AVR-Miner/blob/18e8f97630ff8491f35998306b474113af62d5f5/IMAGES/AVR-MINER-PCB-4.png)
---

### PCB Specifications:

- Layers: 2
- Size: 20mm x 30mm

---

### Components:

| Sr. No. | Component                               | Package | Quantity | Marking on PCB |
| :-----: | :-------------------------------------- | :-----: | :------: | :------------: |
|    1    | Atmega328P-AU or Atmega8-AU             | TQFP-32 |    1     |       U1       |
|    2    | 16MHz Crystal                           | HC49US  |    1     |       Y1       |
|    3    | 3x6x2.5mm SMD Tactile Switch            |    -    |    1     |      SW1       |
|    4    | 10uF 16V Capacitor                      |  0805   |    1     |       C5       |
|    5    | 22pF 16V Capacitor                      |  0805   |    2     |     C3,C4      |
|    6    | 0.1uF 16V Capacitor                     |  0805   |    2     |     C1,C2      |
|    7    | 10k Resistor                            |  0805   |    1     |       R1       |
|    8    | 1k Resistor                             |  0805   |    1     |       R2       |
|    9    | 1x5 2.5mm Pin Header Male - Right Angle |    -    |    1     |       J2       |
|   10    | LED (Blue Color)                        |  0805   |    1     |       D1       |

---

### Supported Controllers:

|  Controller   | Supported | Hash Rate (H/s) |
| :-----------: | :-------: | :-------------: |
| Atmega328P-AU |    ✔️     |     250-270     |
|  Atmega8-AU   |    ✔️     |     220-230     |

---

### Program/Code:

Please find the Code to be uploaded to AVR Miner here: [https://github.com/Duco-Miner/AVR-Miner-Code](https://github.com/Duco-Miner/AVR-Miner-Code)

---

### Additional Links:

- Check out the awesome Duino Coin Project at: [https://duinocoin.com](https://duinocoin.com)
- Duino Coin Wallet: [https://wallet.duinocoin.com](https://wallet.duinocoin.com)

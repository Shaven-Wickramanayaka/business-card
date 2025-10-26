# PCB Business Card With NFC 🛜
- A business card that that is able to transmit information to an nfc ready device while simultaneously harvesting energy to power an led. Based on a tutorial by [Maggie Liu](https://jams.hackclub.com/jam/hacker-card) for Hackclub.
<img width="1275" height="707" alt="image" src="https://github.com/user-attachments/assets/29af9c76-8ae3-4a5c-b8d0-004a1fe6c62f" />
<img width="1286" height="714" alt="image" src="https://github.com/user-attachments/assets/f59373c4-8d3e-48e6-8fb1-7da39d370981" />

- My intial inspiration for the project came from the Stylophone business card by [mitxela](https://www.youtube.com/watch?v=zHVrY_xLM3c) on youtube . Afterwards I came across a ping pong business card by [Electronics Guy](https://youtu.be/x8Cdz36BOXc?si=Xfb_3ctz9GYAQnGA) and a business card that plays flappy bird by [StuckAtPrototype](https://youtu.be/y-lWarLUhfg?si=4j23PVfSiszfBYDo). However all of these were beyond my skill level to even attempt at recreating given I had never worked with hardware before, let alone PCBs. I would like to use this project as a taster in to the world of hardware design and hopefully have a nice project to show off since my current work is very software oriented.

## Technical Specs
| ID | Name                  | Designator | Footprint                                         | Quantity | Manufacturer Part | Manufacturer     | Supplier | Supplier Part | Price  | Pins | 3DModel                    | Contributor    | JLCPCB Part Class | link                                                                                     |
|----|-----------------------|------------|---------------------------------------------------|----------|-------------------|------------------|----------|---------------|--------|------|----------------------------|----------------|-------------------|------------------------------------------------------------------------------------------|
| 1  | 25X48MM\_NFC\_ANTENNA | 2          | 25X48MM\_NFC\_ANTENNA                             | 1        |                   |                  |          |               |        | 2    |                            | LoneWalkerWolf |                   |                                                                                          |
| 2  | 220nF                 | C1         | C0603                                             | 1        | CL10B224KA8NNNC   | SAMSUNG\(三星\)    | LCSC     | C21120        | 0\.006 | 2    | C0603\_L1\.6\-W0\.8\-H0\.8 | lcsc           | Basic Part        | https://item\.szlcsc\.com/362304\.html                                                   |
| 3  | 17\-21SUYC/TR8        | LED1       | LED0805\-R\-RD                                    | 1        | KT\-0805黄灯        | KENTO            | LCSC     | C2296         | 0\.012 | 2    | LED0805\-RD                | lcsc           | Basic Part        | https://item\.szlcsc\.com/88042\.html                                                    |
| 4  | 47Ω                   | R1         | R0603                                             | 1        | 0603WAF470JT5E    | UNI\-ROYAL\(厚声\) | LCSC     | C23182        | 0\.001 | 2    | R0603                      | lcsc           | Basic Part        | https://www\.mouser\.in/datasheet/2/447/PYu\_RT\_1\_to\_0\_01\_RoHS\_L\_11\-1669912\.pdf |
| 5  | NT3H2111W0FHKH        | U1         | XQFN\-8\_L1\.6\-W1\.6\-P0\.50\-BL\_NT3H2111W0FHKH | 1        | NT3H2111W0FHKH    | NXP\(恩智浦\)       | LCSC     | C710403       | 0\.695 | 8    |                            | LCSC           | Extended Part     | https://www\.nxp\.com/docs/en/data\-sheet/NT3H2111\_2211\.pdf                            |

Build of Materials 

| Item                | Description                            | Unit Price | Quantity | Total Price | Running Total |
|---------------------|----------------------------------------|------------|----------|-------------|---------------|
| 25X48MM_NFC_ANTENNA | NFC Antenna made with a coil of copper | 0          | 5        | 0           | 0             |
| 220nF               | Resistor of 220 nF                     | 0.006      | 5        | 0.03        | 0.03          |
| 17-21SUYC/TR8       | Yellow LED                             | 0.012      | 5        | 0.06        | 0.09          |
| 47?                 | 47 ohm resistor                        | 0.001      | 5        | 0.005       | 0.095         |
| NT3H2111W0FHKH      | NFC Chip                               | 0.695      | 5        | 3.475       | 3.57          |


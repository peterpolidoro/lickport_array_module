- [Repository Information](#orged3fbc5)
  - [Description](#org94845ee)
- [Images](#orga411631)
- [Schematic](#org5dc6ad9)
- [Gerbers](#org11bbb00)
- [Bill of Materials](#org9bf6c4f)
  - [PCB Parts](#org560011a)
  - [Supplemental Parts](#org4f9a332)
  - [Vendor Parts Lists](#org20988d1)
- [Supplemental Documentation](#org6d85958)
  - [Assembly Instructions](#orgdbef0a5)
- [Manufacturing Archive](#orge789f8e)

g# Created 2021-06-18 Fri 10:19


<a id="orged3fbc5"></a>

# Repository Information

-   **Name:** lickport\_array\_module
-   **Version:** 1.0
-   **License:** Open-Source Hardware
-   **URL:** <https://github.com/janelia-kicad/lickport_array_module>
-   **Author:** Peter Polidoro
-   **Email:** peterpolidoro@gmail.com


<a id="org94845ee"></a>

## Description

This module board connects lick sensors and dispense actuators to an array of lickports. A set of these module boards will be assembled into a larger array.


<a id="orga411631"></a>

# Images


<a id="org5dc6ad9"></a>

# Schematic

[./schematic/lickport\_array\_module.pdf](./schematic/lickport_array_module.pdf)

![img](./schematic/images/schematic00.png)

![img](./schematic/images/schematic01.png)

![img](./schematic/images/schematic02.png)

![img](./schematic/images/schematic03.png)

![img](./schematic/images/schematic04.png)

![img](./schematic/images/schematic05.png)

![img](./schematic/images/schematic06.png)

![img](./schematic/images/schematic07.png)

![img](./schematic/images/schematic08.png)

![img](./schematic/images/schematic09.png)

![img](./schematic/images/schematic10.png)

![img](./schematic/images/schematic11.png)

![img](./schematic/images/schematic12.png)


<a id="org11bbb00"></a>

# Gerbers

![img](./gerbers/images/gerbers00.png)

![img](./gerbers/images/gerbers01.png)


<a id="org9bf6c4f"></a>

# Bill of Materials


<a id="org560011a"></a>

## PCB Parts

| Item | Reference(s)                                                                                                                                                                 | Quantity | Manufacturer                    | Manufacturer Part Number | Vendor   | Vendor Part Number   | Description                                 | Package            |
|---- |---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |-------- |------------------------------- |------------------------ |-------- |-------------------- |------------------------------------------- |------------------ |
| 1    | C1                                                                                                                                                                           | 1        | TDK Corporation                 | C2012X5R1V106K085AC      | Digi-Key | 445-14417-1-ND       | CAP CER 10UF 35V X5R                        | 0805 (2012 Metric) |
| 2    | C10 C12 C14 C16 C18 C20 C22 C24 C26 C4 C6 C8 C2                                                                                                                              | 13       | Vishay Sprague                  | 298D105X0016K2T          | Digi-Key | 718-1618-1-ND        | CAP TANT 1UF 20% 16V                        | 0402               |
| 3    | C11 C13 C15 C17 C19 C21 C23 C25 C27 C5 C7 C9                                                                                                                                 | 12       | Murata Electronics              | GRM155R71H473KE14D       | Digi-Key | 490-10702-1-ND       | CAP CER 0.047UF 50V X7R 0402                | 0402               |
| 4    | D1                                                                                                                                                                           | 1        | Nexperia USA Inc.               | PMEG045V100EPDZ          | Digi-Key | 1727-1904-1-ND       | DIODE SCHOTTKY 45V 10A                      | CFP15              |
| 5    | D10 D12 D14 D16 D18 D20 D22 D24 D26 D4 D6 D8 D2                                                                                                                              | 13       | Diodes Incorporated             | BAS116LPH4-7B            | Digi-Key | BAS116LPH4-7BDICT-ND | DIODE GEN PURP 85V 215MA 2DFN               | 0402               |
| 6    | D11 D13 D15 D17 D19 D21 D23 D25 D3 D5 D7 D9                                                                                                                                  | 12       | Comchip Technology              | CDBQR0230L               | Digi-Key | 641-1275-1-ND        | DIODE SCHOTTKY 30V 200MA                    | 0402               |
| 7    | L1 L10 L11 L12 L13 L2 L3 L4 L5 L6 L7 L8 L9                                                                                                                                   | 13       | Lite-On Inc.                    | LTST-C170GKT             | Digi-Key | 160-1179-1-ND        | LED GREEN CLEAR SMD                         | 0805 (2012 Metric) |
| 8    | P10 P11 P12 P13 P14 P3 P4 P5 P6 P7 P8 P9                                                                                                                                     | 12       | Mill-Max Manufacturing Corp.    | 9837-0-15-80-14-27-10-0  | Digi-Key | ED10170-ND           | Pin Receptacle Connector 0.065in to 0.082in |                    |
| 9    | P2                                                                                                                                                                           | 1        | Amphenol RF                     | 031-5633-1010            | Digi-Key | ARF2116-ND           | CONN BNC JACK STR 50 OHM PCB                |                    |
| 10   | R1 R2 R3 R12 R16 R20 R24 R28 R32 R36 R40 R44 R48 R52 R8                                                                                                                      | 15       | Panasonic Electronic Components | ERJ-PA2F2201X            | Digi-Key | P17226CT-ND          | RES SMD 2.2K OHM 1% 1/5W                    | 0402               |
| 11   | R11 R15 R19 R23 R27 R31 R35 R39 R43 R47 R51 R7                                                                                                                               | 12       | Panasonic Electronic Components | ERJ-2RKF2053X            | Digi-Key | P205KLCT-ND          | RES SMD 205K OHM 1% 1/10W 0402              | 0402               |
| 12   | R13 R17 R21 R25 R29 R33 R37 R41 R45 R49 R53 R9                                                                                                                               | 12       | Panasonic Electronic Components | ERJ-PA2F2002X            | Digi-Key | P124454CT-ND         |                                             | 0402               |
| 13   | R4 R5                                                                                                                                                                        | 2        | Panasonic Electronic Components | ERJ-PA2F4702X            | Digi-Key | P17234CT-ND          | RES SMD 47K OHM 1% 1/5W                     | 0402               |
| 14   | T1 T10 T11 T12 T2 T3 T4 T5 T6 T7 T8 T9                                                                                                                                       | 12       | Phoenix Contact                 | 1988956                  | Digi-Key | 277-1779-ND          |                                             |                    |
| 15   | TEENSY1                                                                                                                                                                      | 2        | Sullins Connector Solutions     | PPPC141LFBN-RC           | Digi-Key | S7047-ND             | CONN HDR 14POS 0.1 GOLD PCB                 |                    |
| 16   | U1                                                                                                                                                                           | 1        | Microchip Technology            | AT42QT2120-MMHR          | Digi-Key | AT42QT2120-MMHRCT-ND | IC TOUCH SENSOR 12CH                        | 20-VFQFN           |
| 17   | U10 U11 U12 U13 U2 U3 U4 U5 U6 U7 U8 U9                                                                                                                                      | 12       | Texas Instruments               | DRV103U                  | Digi-Key | 296-11622-ND         | IC LO-SIDE DRIVER PWM 8SOIC                 | 8SOIC              |
|      | C3 FID1 FID2 FID3 FID4 MH1 MH10 MH11 MH12 MH13 MH14 MH2 MH3 MH4 MH5 MH6 MH7 MH8 MH9 P1 R10 R14 R18 R22 R26 R30 R34 R38 R42 R46 R50 R6 S1 S10 S11 S12 S2 S3 S4 S5 S6 S7 S8 S9 | 44       |                                 |                          | Digi-Key | 1276-1739-1-ND       | CAP CER 0.1UF 25V Y5V                       | 0402               |


<a id="org4f9a332"></a>

## Supplemental Parts

| Item | Quantity | Manufacturer         | Manufacturer Part Number | Vendor   | Vendor Part Number | Description                      |
|---- |-------- |-------------------- |------------------------ |-------- |------------------ |-------------------------------- |
| 1    | 1        | SparkFun Electronics | DEV-16997                | Digi-Key | 1568-DEV-16997-ND  | TEENSY 4.0 (HEADERS)             |
| 2    | 1        | Qualtek              | 3021077-10               | Digi-Key | Q1225-ND           | USB 2.0 A MALE TO USB 2.0 MICRO  |
| 3    | 1        | CUI Inc.             | SDI65-24-UDC-P6          | Digi-Key | 102-4891-ND        | AC/DC DESKTOP ADAPTER 24V 65W    |
| 4    | 1        | Amphenol RF          | 115101-19-120            | Digi-Key | ACX1790-ND         | CBL ASSY BNC PLUG-PLUG RG58 10FT |
| 5    | 24       | Panduit Corp         | FSD73-8-D                | Digi-Key | 298-10557-ND       | CONN FERRULE DIN 24AWG YELLOW    |


<a id="org20988d1"></a>

## Vendor Parts Lists

[./bom/Digi-Key\_parts.csv](./bom/Digi-Key_parts.csv)


<a id="org6d85958"></a>

# Supplemental Documentation


<a id="orgdbef0a5"></a>

## Assembly Instructions

-   Solder surface mount and through hole components onto the pcb.


<a id="orge789f8e"></a>

# Manufacturing Archive

Send manufacturing zip file to your favorite PCB manufacturer for fabrication.

[./manufacturing/lickport\_array\_module\_v1.0.zip](./manufacturing/lickport_array_module_v1.0.zip)
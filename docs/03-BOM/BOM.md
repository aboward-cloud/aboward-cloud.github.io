---
title: Bill of Materials — Revision J Through-Hole
---

# Bill of Materials — Revision J Through-Hole

Alexander Boward | Team 202 Weather Gadget | November 3, 2026

**Final DigiKey purchase-request estimate:** $55.47 ($33.84 merchandise + $4.64 estimated tariffs + $16.99 shipping). This is the order estimate after excluding parts already available; it is separate from the full assembly replacement cost below. The request includes two of each fuse and ten 47 kOhm resistors; assembly quantities below are one of each fuse and five 47 kOhm resistors.

**Priced assembly/accessory subtotal: $86.86, plus unpriced stock parts and any additional LCD wiring hardware.**


| Supplier / source | Priced assembly subtotal |
|---|---:|
| DigiKey | $67.96 |
| Mouser reference pricing for already-available UART cables | $18.90 |
| PCB features | $0.00 |
| **Known-price subtotal** | **$86.86** |
| JWCO capacitor and stock contrast resistor | Unpriced |

## DigiKey

| Part / description | Qty per assembly | Prototype unit | Prototype total | Production unit | Production total | References / use |
|---|---:|---:|---:|---:|---:|---|
| [0251.250MXL](https://www.digikey.com/en/products/detail/littelfuse-inc/0251-250MXL/700699)<br>250mA,125VAC/DC fast axial solder-in fuse | 1 | $1.5 | $1.50 | $1.5 | $1.50 | F1 |
| [0251.500MXL](https://www.digikey.com/en/products/detail/littelfuse-inc/0251-500MXL/700707)<br>500mA,125VAC/DC fast axial solder-in fuse | 1 | $1.37 | $1.37 | $1.37 | $1.37 | F2 |
| [1N5819-E3/54](https://www.digikey.com/en/products/detail/vishay-general-semiconductor-diodes-division/1N5819-E3-54/1023531)<br>1N5819, 1 A, 40 V Schottky, DO-41 | 1 | $0.71 | $0.71 | $0.71 | $0.71 | D1 |
| [3811/16 100](https://www.digikey.com/en/products/detail/3m/3811-16-100/22532483)<br>26 AWG stranded color-coded ribbon, purchase unit = one foot | 1 | $2.32 | $2.32 | $2.32 | $2.32 | LCD harness wire; one foot purchase unit |
| [B3F-1000](https://www.digikey.com/en/products/detail/omron-electronics-inc-emc-div/B3F-1000/33150)<br>B3F-1000, SPST-NO tactile switch, 6x6 mm | 1 | $0.35 | $0.35 | $0.35 | $0.35 | SW1 |
| [C315C104K5R5TA](https://www.digikey.com/en/products/detail/kemet/C315C104K5R5TA/12701330)<br>100nF,50V,X7R,10%,radial2.54mm | 3 | $0.79 | $2.37 | $0.79 | $2.37 | C3, C5, C7 |
| [C330C334K1R5TA](https://www.digikey.com/en/products/detail/kemet/C330C334K1R5TA/818183)<br>330nF,100V,X7R,10%,radial5.08mm | 1 | $1.86 | $1.86 | $1.86 | $1.86 | C1 |
| [DM164150](https://www.digikey.com/en/products/detail/microchip-technology/DM164150/11586705)<br>PIC18F57Q43 Curiosity Nano development board | 1 | $10.61 | $10.61 | $10.61 | $10.61 | U1 |
| [M20-1060800](https://www.digikey.com/en/products/detail/harwin-inc/M20-1060800/3728198)<br>8-position single-row female cable housing, 2.54 mm pitch | 4 | $0.37 | $1.48 | $0.37 | $1.48 | J6/J7 to DS1: both ends of two groups |
| [M20-1180046](https://www.digikey.com/en/products/detail/harwin-inc/M20-1180046/3728125)<br>Loose tin crimp socket contacts, 22-30 AWG | 26 | $0.1092 | $2.84 | $0.1092 | $2.84 | LCD harness: 13 conductors, both ends |
| [M20-9990845](https://www.digikey.com/en/products/detail/harwin-inc/M20-9990845/3727965)<br>1x8 male header, 2.54 mm pitch | 3 | $0.37 | $1.11 | $0.37 | $1.11 | J5, J6, J7 |
| [M20-9991645](https://www.digikey.com/en/products/detail/harwin-inc/M20-9991645/3921260)<br>16-position male LCD header, 2.54 mm pitch | 1 | $0.69 | $0.69 | $0.69 | $0.69 | DS1 LCD header |
| [MFR-25FBF52-10K](https://www.digikey.com/en/products/detail/yageo/MFR-25FBF52-10K/13219)<br>10K resistor,1%,0.25W axial metal film | 1 | $0.1 | $0.10 | $0.1 | $0.10 | R6 |
| [MFR-25FBF52-1K](https://www.digikey.com/en/products/detail/yageo/MFR-25FBF52-1K/13011)<br>1K resistor,1%,0.25W axial metal film | 1 | $0.1 | $0.10 | $0.1 | $0.10 | R10 |
| [MFR-25FBF52-470R](https://www.digikey.com/en/products/detail/yageo/MFR-25FBF52-470R/9138172)<br>470R resistor,1%,0.25W axial metal film | 1 | $0.11 | $0.11 | $0.11 | $0.11 | R4 |
| [MFR-25FRF52-2K2](https://www.digikey.com/en/products/detail/yageo/MFR-25FRF52-2K2/9138953)<br>2K2 resistor,1%,0.25W axial metal film | 1 | $0.1 | $0.10 | $0.1 | $0.10 | R9 |
| [MFR-25FRF52-47K](https://www.digikey.com/en/products/detail/yageo/MFR-25FRF52-47K/9139054)<br>47K resistor,1%,0.25W axial metal film | 5 | $0.1 | $0.50 | $0.1 | $0.50 | R1, R2, R3, R5, R7 |
| [MFR-25FRF52-4K7](https://www.digikey.com/en/products/detail/yageo/MFR-25FRF52-4K7/9139057)<br>4K7 resistor,1%,0.25W axial metal film | 1 | $0.1 | $0.10 | $0.1 | $0.10 | R8 |
| [PJ-002A](https://www.digikey.com/en/products/detail/same-sky-formerly-cui-devices/PJ-002A/96962)<br>DC barrel jack, PJ-002A, 2.0 mm center pin | 1 | $0.66 | $0.66 | $0.66 | $0.66 | J4 |
| [PPTC281LFBN-RC](https://www.digikey.com/en/products/detail/sullins-connector-solutions/PPTC281LFBN-RC/810166)<br>Nano female socket strip, 1x28, 2.54 mm pitch | 2 | $1.7 | $3.40 | $1.7 | $3.40 | U1: both Nano socket strips |
| [SN74AHC14N](https://www.digikey.com/en/products/detail/texas-instruments/SN74AHC14N/375979)<br>Hex Schmitt inverter,DIP14; two gates cascaded | 1 | $0.88 | $0.88 | $0.88 | $0.88 | U3 |
| [T350F226K016AT](https://www.digikey.com/en/products/detail/kemet/T350F226K016AT/818435)<br>22 uF, 16 V tantalum, 10%, case F, 2.54 mm pitch | 1 | $4.76 | $4.76 | $4.76 | $4.76 | C4 |
| [TST-104-01-G-D](https://www.digikey.com/en/products/detail/samtec-inc/TST-104-01-G-D/9497049)<br>Keyed shrouded 2x4 PCB header, 2.54 mm pitch | 3 | $3.21 | $9.63 | $3.21 | $9.63 | J1, J2, J3 |
| [WP710A10ID](https://www.digikey.com/en/products/detail/kingbright/WP710A10ID/2769809)<br>Red diffused3mm LED,2.54mm pitch | 3 | $0.24 | $0.72 | $0.24 | $0.72 | D2, D3, D4 |
| [WSU090-1300](https://www.digikey.com/en/products/detail/triad-magnetics/WSU090-1300/3094977)<br>9 V, 1.3 A regulated adapter, center-positive 5.5x2.1 mm | 1 | $8.65 | $8.65 | $8.65 | $8.65 | J4: operating power adapter |
| [ZOR-25-R-52-0R](https://www.digikey.com/en/products/detail/yageo/ZOR-25-R-52-0R/14670488)<br>0 ohm axial jumper,10A at70C,<=10mOhm | 2 | $0.12 | $0.24 | $0.12 | $0.24 | R11, R12 |
| [NHD-0216K1Z-FSW-FBW-L](https://www.digikey.com/en/products/detail/newhaven-display-intl/NHD-0216K1Z-FSW-FBW-L/1701185)<br>16x2 parallel LCD, 5 V logic, white backlight; external contrast/backlight wiring | 1 | $8.11 | $8.11 | $8.11 | $8.11 | DS1 |
| [LM1086CT-5.0/NOPB](https://www.digikey.com/en/products/detail/texas-instruments/LM1086CT-5-0-NOPB/363572)<br>5 V, 1.5 A LDO, TO-220-3, commercial temperature grade | 1 | $2.44 | $2.44 | $2.44 | $2.44 | U2 |
| [ECA-1EM470](https://www.digikey.com/en/products/detail/panasonic-industry/ECA-1EM470/245010)<br>47 uF, 25 V, 20%, aluminum electrolytic, 85 C, 5 mm diameter, 2 mm pitch | 1 | $0.25 | $0.25 | $0.25 | $0.25 | C2 |

**Subtotal: $67.96**

## Already-available UART cables — replacement pricing

| Part / description | Qty per assembly | Prototype unit | Prototype total | Production unit | Production total | References / use |
|---|---:|---:|---:|---:|---:|---|
| [IDSD-04-D-08.00-G](https://www.mouser.com/ProductDetail/Samtec/IDSD-04-D-08.00-G?qs=0lQeLiL1qyZIFjM6oRjn%252BA%3D%3D)<br>8-contact 2x4 socket-to-socket IDC cable, 8 inch, gray, 2.54 mm connector pitch | 3 | $6.3 | $18.90 | $6.3 | $18.90 | J1-J3 UART interfaces |

**Subtotal: $18.90. No separate Mouser purchase request is planned.**

## On-hand components without verified replacement prices

| Part / description | Qty per assembly | Prototype unit | Prototype total | Production unit | Production total | References / use |
|---|---:|---:|---:|---:|---:|---|
| JWCO CH, body markings: -40/+105 C, 1706, 2.2 uF 50 V<br>Radial aluminum electrolytic; exact orderable MPN, tolerance and leakage unverified | 1 | TBD | TBD | TBD | TBD | C6; user-selected lab component |
| 1 kOhm axial resistor from existing stock<br>Initial LCD contrast trial; exact manufacturer/tolerance unrecorded | 1 | TBD | TBD | TBD | TBD | LCD V0 (pin 3) to GND; no potentiometer |

## PCB features

| Part / description | Qty per assembly | Prototype unit | Prototype total | Production unit | Production total | References / use |
|---|---:|---:|---:|---:|---:|---|
| N/A - fabricated PCB feature<br>Bare copper test pads, 1.5 mm diameter; included in PCB fabrication | 30 | $0 | $0.00 | $0 | $0.00 | TP1, TP10, TP11, TP12, TP13, TP14, TP15, TP16, TP17, TP18, TP19, TP2, TP20, TP21, TP22, TP23, TP24, TP25, TP26, TP27, TP28, TP29, TP3, TP30, TP4, TP5, TP6, TP7, TP8, TP9 |

## Assembly and selection notes

- DS1 is now **NHD-0216K1Z-FSW-FBW-L**, replacing the fixed-contrast FB1 display. It needs a contrast connection on pin 3 and backlight connections on pins 15/16. The old instruction to leave these pins unconnected no longer applies. The 1 kOhm contrast resistor is a bench-test starting value; readability must be checked. Backlight current limiting and the final harness pinout/contact count still require confirmation. The 26-contact harness line is the earlier allowance, not a verified final count for the new display.
- U2 is **LM1086CT-5.0/NOPB**, replacing LM1086IT-5.0/NOPB; C2 is **ECA-1EM470**, replacing EEUFR1E470. These are the parts on the final DigiKey request.
- C6 uses the chosen **JWCO 2.2 uF 50 V** capacitor instead of the KEMET tantalum. Earlier calculated debounce timing for the KEMET part does not qualify the JWCO part; check button operation on the assembled board.
- F1/F2 remain the specified 250 mA / 500 mA fast axial fuses. The found T500mAL250V slow-blow fuses and loose fuse holders are inventory, not approved substitutes for these selections.
- D2-D4 retain the specified red LED replacement pricing; five red LEDs were found in the lab. Other collected components are not automatic substitutions. C3/C5/C7 and C4 retain the exact parts still present on the final purchase request.
- The Nano, available connectors, cables and adapter remain in the full BOM even when omitted from the purchase request because already available. U3 is one SN74AHC14N DIP14 IC, using two cascaded inverters.
- This update changes the website BOM only. The schematic and downloadable workbook/PDF may still contain the earlier LCD, regulator, C2 and C6 selections. Export the published webpage to PDF for the Canvas submission after reviewing it.

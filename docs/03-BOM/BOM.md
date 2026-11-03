---
title: Bill of Materials — Revision J
---

# Bill of Materials — Revision J

Zander Boward | Team 202 Weather Gadget | November 3, 2026

**Component cost: $90.91**

Revision J basis: 67 schematic references (37 purchased items and 30 bare PCB pads), plus listed operating accessories. One assembly; no inventory credits, breadboard quantities or spares. Nano and LCD included at replacement cost.

Pricing: published supplier USD listings checked November 3, 2026, at one-assembly quantities. Same prices in prototype and production columns. Round each extension to cents before summing. Tax, shipping and separately assessed tariffs are excluded; vendor-inclusive duties remain in published prices.

Delivery: target ZIP 85212 within 10 calendar days after vendor order placement. Stock is a listing snapshot; 2-business-day transit after dispatch is an estimate, not a confirmed arrival. Newark lists 4-6 business days from UK stock. Confirm every dated ETA at checkout.

Revision J: exact fixed-contrast FB1 LCD, LM1086IT-5.0/NOPB regulator, 22 uF output capacitor and 2.2 uF tantalum debounce capacitor. No trimmer, 3.3 V regulator, jumper headers or removable shunts. Reference numbering follows Revision J.

Accessories: two 1x28 Nano sockets; one 1x16 LCD male header; four 1x8 female housings and 26 tin contacts; one foot of 26 AWG ribbon for 13 LCD conductors <=150 mm; three approved gray UART cables; one 9 V adapter. No J5 cable is required by the Revision J accessory list.

LCD pins 3, 15, 16 stay unconnected. Supply path drop, live regulator tab/thermal performance, stability, debounce, fit and fault clearing remain hardware qualifications. Mouser marks exact LCD NRND. Ordered/date/received/surplus fields remain blank.

30 bare copper test pads carry no separate component cost. PCB fabrication, enclosure, mounting hardware and assembly tooling/labor are excluded. Website/PDF are local previews; export published website for final rubric submission. See Sourcing-review.md and packaged source records.

| Supplier | Subtotal |
|---|---:|
| DigiKey | $60.35 |
| Mouser | $30.07 |
| Newark | $0.49 |
| PCB features | $0.00 |
| **Total** | **$90.91** |

## DigiKey

| Part / description | Qty | Prototype unit | Prototype total | Production unit | Production total | References / accessory use |
|---|---:|---:|---:|---:|---:|---|
| [0154.250DR](https://www.digikey.com/en/products/detail/littelfuse-inc/0154-250DR/183349)<br>250 mA fast removable fuse + holder assembly | 1 | $4.84 | $4.84 | $4.84 | $4.84 | F1 |
| [0154.500DR](https://www.digikey.com/en/products/detail/littelfuse-inc/0154-500DR/183350)<br>500 mA fast removable fuse + holder assembly | 1 | $4.84 | $4.84 | $4.84 | $4.84 | F2 |
| [1N5819-E3/54](https://www.digikey.com/en/products/detail/vishay-general-semiconductor-diodes-division/1N5819-E3-54/1023531)<br>1N5819, 1 A, 40 V Schottky, DO-41 | 1 | $0.71 | $0.71 | $0.71 | $0.71 | D1 |
| [3811/16 100](https://www.digikey.com/en/products/detail/3m/3811-16-100/22532483)<br>26 AWG stranded color-coded ribbon, purchase unit = one foot | 1 | $2.32 | $2.32 | $2.32 | $2.32 | LCD harness wire; one foot purchase unit (accessory) |
| [B3F-1000](https://www.digikey.com/en/products/detail/omron-electronics-inc-emc-div/B3F-1000/33150)<br>B3F-1000, SPST-NO tactile switch, 6x6 mm | 1 | $0.35 | $0.35 | $0.35 | $0.35 | SW1 |
| [C0805C104K5RACTU](https://www.digikey.com/en/products/detail/kemet/C0805C104K5RACTU/411169)<br>100 nF, 50 V, X7R, 10%, 0805 | 3 | $0.18 | $0.54 | $0.18 | $0.54 | C3, C5, C7 |
| [C0805C334K3RACTU](https://www.digikey.com/en/products/detail/kemet/C0805C334K3RACTU/2212617)<br>330 nF, 25 V, X7R, 10%, 0805 | 1 | $0.4 | $0.40 | $0.4 | $0.40 | C1 |
| [DM164150](https://www.digikey.com/en/products/detail/microchip-technology/DM164150/11586705)<br>PIC18F57Q43 Curiosity Nano development board | 1 | $10.61 | $10.61 | $10.61 | $10.61 | U1 |
| [LTST-C170KRKT](https://www.digikey.com/en/products/detail/liteon/LTST-C170KRKT/386779)<br>Red LED, 0805 | 3 | $0.18 | $0.54 | $0.18 | $0.54 | D2, D3, D4 |
| [M20-1060800](https://www.digikey.com/en/products/detail/harwin-inc/M20-1060800/3728198)<br>8-position single-row female cable housing, 2.54 mm pitch | 4 | $0.37 | $1.48 | $0.37 | $1.48 | J6/J7 to DS1: both ends of two groups (accessory) |
| [M20-1180046](https://www.digikey.com/en/products/detail/harwin-inc/M20-1180046/3728125)<br>Loose tin crimp socket contacts, 22-30 AWG | 26 | $0.1092 | $2.84 | $0.1092 | $2.84 | LCD harness: 13 conductors, both ends (accessory) |
| [M20-9990845](https://www.digikey.com/en/products/detail/harwin-inc/M20-9990845/3727965)<br>1x8 male header, 2.54 mm pitch | 3 | $0.37 | $1.11 | $0.37 | $1.11 | J5, J6, J7 |
| [M20-9991645](https://www.digikey.com/en/products/detail/harwin-inc/M20-9991645/3921260)<br>16-position male LCD header, 2.54 mm pitch | 1 | $0.69 | $0.69 | $0.69 | $0.69 | DS1 LCD header (accessory) |
| [PJ-002A](https://www.digikey.com/en/products/detail/same-sky-formerly-cui-devices/PJ-002A/96962)<br>DC barrel jack, PJ-002A, 2.0 mm center pin | 1 | $0.66 | $0.66 | $0.66 | $0.66 | J4 |
| [PPTC281LFBN-RC](https://www.digikey.com/en/products/detail/sullins-connector-solutions/PPTC281LFBN-RC/810166)<br>Nano female socket strip, 1x28, 2.54 mm pitch | 2 | $1.7 | $3.40 | $1.7 | $3.40 | U1: both Nano socket strips (accessory) |
| [RC1206FR-0710KL](https://www.digikey.com/en/products/detail/yageo/RC1206FR-0710KL/728483)<br>10k ohm resistor, +/-1%, 0.25 W, 1206 | 1 | $0.1 | $0.10 | $0.1 | $0.10 | R6 |
| [RC1206FR-071KL](https://www.digikey.com/en/products/detail/yageo/RC1206FR-071KL/728387)<br>1k ohm resistor, +/-1%, 0.25 W, 1206 | 1 | $0.1 | $0.10 | $0.1 | $0.10 | R10 |
| [RC1206FR-072K2L](https://www.digikey.com/en/products/detail/yageo/RC1206FR-072K2L/728624)<br>2.2k ohm resistor, +/-1%, 0.25 W, 1206 | 1 | $0.1 | $0.10 | $0.1 | $0.10 | R9 |
| [RC1206FR-07470RL](https://www.digikey.com/en/products/detail/yageo/RC1206FR-07470RL/728934)<br>470 ohm resistor, +/-1%, 0.25 W, 1206 | 1 | $0.1 | $0.10 | $0.1 | $0.10 | R4 |
| [RC1206FR-0747KL](https://www.digikey.com/en/products/detail/yageo/RC1206FR-0747KL/731878)<br>47k ohm resistor, +/-1%, 0.25 W, 1206 | 5 | $0.1 | $0.50 | $0.1 | $0.50 | R1, R2, R3, R5, R7 |
| [RC1206FR-074K7L](https://www.digikey.com/en/products/detail/yageo/RC1206FR-074K7L/728887)<br>4.7k resistor, 1206, 0.25 W, 1% | 1 | $0.1 | $0.10 | $0.1 | $0.10 | R8 |
| [RC1206JR-070RL](https://www.digikey.com/en/products/detail/yageo/RC1206JR-070RL/732131)<br>0 ohm resistor, 1206, 0.25 W, 2 A jumper | 2 | $0.1 | $0.20 | $0.1 | $0.20 | R11, R12 |
| [SN74LVC1G17DBVR](https://www.digikey.com/en/products/detail/texas-instruments/SN74LVC1G17DBVR/389051)<br>Schmitt buffer, SOT-23-5, SN74LVC1G17 | 1 | $0.15 | $0.15 | $0.15 | $0.15 | U3 |
| [T350F226K016AT](https://www.digikey.com/en/products/detail/kemet/T350F226K016AT/818435)<br>22 uF, 16 V tantalum, 10%, case F, 2.54 mm pitch | 1 | $4.76 | $4.76 | $4.76 | $4.76 | C4 |
| [T491A225K025AT](https://www.digikey.com/en/products/detail/kemet/T491A225K025AT/3759239)<br>2.2 uF, 25 V, +/-10% polarized tantalum, A/3216 case | 1 | $0.63 | $0.63 | $0.63 | $0.63 | C6 |
| [TST-104-01-G-D](https://www.digikey.com/en/products/detail/samtec-inc/TST-104-01-G-D/9497049)<br>Keyed shrouded 2x4 PCB header, 2.54 mm pitch | 3 | $3.21 | $9.63 | $3.21 | $9.63 | J1, J2, J3 |
| [WSU090-1300](https://www.digikey.com/en/products/detail/triad-magnetics/WSU090-1300/3094977)<br>9 V, 1.3 A regulated adapter, center-positive 5.5x2.1 mm | 1 | $8.65 | $8.65 | $8.65 | $8.65 | J4: operating power adapter (accessory) |

**Subtotal: $60.35**

## Mouser

| Part / description | Qty | Prototype unit | Prototype total | Production unit | Production total | References / accessory use |
|---|---:|---:|---:|---:|---:|---|
| [IDSD-04-D-08.00-G](https://www.mouser.com/ProductDetail/Samtec/IDSD-04-D-08.00-G?qs=0lQeLiL1qyZIFjM6oRjn%252BA%3D%3D)<br>8-contact 2x4 socket-to-socket IDC cable, 8 inch, gray, 2.54 mm connector pitch | 3 | $6.3 | $18.90 | $6.3 | $18.90 | J1-J3 UART interfaces (accessory) |
| [LM1086IT-5.0/NOPB](https://www.mouser.com/ProductDetail/Texas-Instruments/LM1086IT-5.0-NOPB?qs=sGAEpiMZZMug9GoBKXZ759%2FWxdjGb5obqWlryGQJdV0%3D)<br>5 V, 1.5 A LDO regulator, TO-220-3 | 1 | $2.37 | $2.37 | $2.37 | $2.37 | U2 |
| [NHD-0216K1Z-FSW-FTW-FB1](https://www.mouser.com/ProductDetail/Newhaven-Display/NHD-0216K1Z-FSW-FTW-FB1?qs=sGAEpiMZZMt7dcPGmvnkBpdHgMVhq5cu2av6HIr5mGo%3D)<br>16x2 parallel LCD, 5 V, fixed contrast and always-on white backlight | 1 | $8.8 | $8.80 | $8.8 | $8.80 | DS1 |

**Subtotal: $30.07**

## Newark

| Part / description | Qty | Prototype unit | Prototype total | Production unit | Production total | References / accessory use |
|---|---:|---:|---:|---:|---:|---|
| [EEUFR1E470](https://www.newark.com/panasonic/eeufr1e470/cap-alu-elec-47uf-25v-20/dp/92Y6310)<br>47 uF, 25 V radial, 5 mm diameter, 2 mm pitch | 1 | $0.488 | $0.49 | $0.488 | $0.49 | C2 |

**Subtotal: $0.49**

## PCB features

| Part / description | Qty | Prototype unit | Prototype total | Production unit | Production total | References / accessory use |
|---|---:|---:|---:|---:|---:|---|
| N/A - fabricated PCB feature<br>Bare copper test pads, 1.5 mm diameter; included in PCB fabrication | 30 | $0 | $0.00 | $0 | $0.00 | TP1, TP2, TP3, TP4, TP5, TP6, TP7, TP8, TP9, TP10, TP11, TP12, TP13, TP14, TP15, TP16, TP17, TP18, TP19, TP20, TP21, TP22, TP23, TP24, TP25, TP26, TP27, TP28, TP29, TP30 |

**Subtotal: $0.00**

## Sourcing and assembly notes

### 0154.250DR

[DigiKey / F1219CT-ND](https://www.digikey.com/en/products/detail/littelfuse-inc/0154-250DR/183349) | [Local manufacturer documentation](datasheets/Littelfuse-154.pdf)

Checked 2026-11-03: 8,787 listed. Stocked listing screening only. Estimate: select 2-business-day service after vendor dispatch for ZIP 85212; confirm dated checkout arrival within 10 calendar days after order. No confirmed delivery date.

Complete fuse-and-holder assembly; included holder 01550900M must not be purchased again. Exact specified 250 mA provision retained. Fuse coordination and clearing remain bench checks.

### 0154.500DR

[DigiKey / F1220CT-ND](https://www.digikey.com/en/products/detail/littelfuse-inc/0154-500DR/183350) | [Local manufacturer documentation](datasheets/Littelfuse-154.pdf)

Checked 2026-11-03: 10,437 listed. Stocked listing screening only. Estimate: select 2-business-day service after vendor dispatch for ZIP 85212; confirm dated checkout arrival within 10 calendar days after order. No confirmed delivery date.

One complete F2 fuse-and-holder assembly; included holder must not be bought again. F1/F2 are intentionally nonselective in Revision J; actual fault clearing remains pending.

### 1N5819-E3/54

[DigiKey / 1N5819-E3/54GICT-ND](https://www.digikey.com/en/products/detail/vishay-general-semiconductor-diodes-division/1N5819-E3-54/1023531) | [Local manufacturer documentation](datasheets/1N5819.pdf)

Checked 2026-11-03: 17,842 listed. Stocked listing screening only. Estimate: select 2-business-day service after vendor dispatch for ZIP 85212; confirm dated checkout arrival within 10 calendar days after order. No confirmed delivery date.

### 3811/16 100

[DigiKey / 19-3811/16100-DS-ND](https://www.digikey.com/en/products/detail/3m/3811-16-100/22532483) | [Documentation link — local exact PDF unavailable](https://multimedia.3m.com/mws/media/22071O/3m-tm-color-coded-flat-cbl-050-26-awg-stranded-pvc-3811-ts0122.pdf)

Checked 2026-11-03: 79 listed. Stocked listing screening only. Estimate: select 2-business-day service after vendor dispatch for ZIP 85212; confirm dated checkout arrival within 10 calendar days after order. No confirmed delivery date.

Purchase one foot (304.8 mm) of 16-conductor ribbon, not the 100-foot spool. Separate 13 conductors and cut each <=150 mm; terminate both ends with the listed contacts. Remaining cable is unavoidable cut-length remainder, no spares allowance. Stranded tinned copper, 7/34, 26 AWG, 1.07 mm nominal insulation thickness/diameter. Verify crimp insulation grip and finished continuity.

Manufacturer PDF verified through online reader; server denied local download. Local copy missing; use the linked manufacturer datasheet.

### B3F-1000

[DigiKey / SW400-ND](https://www.digikey.com/en/products/detail/omron-electronics-inc-emc-div/B3F-1000/33150) | [Local manufacturer documentation](datasheets/B3F.pdf)

Checked 2026-11-03: 21,365 listed. Stocked listing screening only. Estimate: select 2-business-day service after vendor dispatch for ZIP 85212; confirm dated checkout arrival within 10 calendar days after order. No confirmed delivery date.

### C0805C104K5RACTU

[DigiKey / 399-C0805C104K5RACTUCT-ND](https://www.digikey.com/en/products/detail/kemet/C0805C104K5RACTU/411169) | [Local manufacturer documentation](datasheets/KEMET-X7R.pdf)

Checked 2026-11-03: 7,280,270 listed. Stocked listing screening only. Estimate: select 2-business-day service after vendor dispatch for ZIP 85212; confirm dated checkout arrival within 10 calendar days after order. No confirmed delivery date.

### C0805C334K3RACTU

[DigiKey / 399-C0805C334K3RACTUCT-ND](https://www.digikey.com/en/products/detail/kemet/C0805C334K3RACTU/2212617) | [Local manufacturer documentation](datasheets/KEMET-X7R.pdf)

Checked 2026-11-03: 61,407 listed. Stocked listing screening only. Estimate: select 2-business-day service after vendor dispatch for ZIP 85212; confirm dated checkout arrival within 10 calendar days after order. No confirmed delivery date.

### DM164150

[DigiKey / 150-DM164150-ND](https://www.digikey.com/en/products/detail/microchip-technology/DM164150/11586705) | [Local manufacturer documentation](datasheets/Nano-user-guide.pdf)

Checked 2026-11-03: 114 listed. Stocked listing screening only. Estimate: select 2-business-day service after vendor dispatch for ZIP 85212; confirm dated checkout arrival within 10 calendar days after order. No confirmed delivery date.

Include the complete development board at replacement cost. The course Nano setup guide describes two male-header strips included with the board; trim each to the 28 populated contacts required by this design. No extra male-header purchase is counted. USB programming cable is lab equipment and excluded.

### LTST-C170KRKT

[DigiKey / 160-1415-1-ND](https://www.digikey.com/en/products/detail/liteon/LTST-C170KRKT/386779) | [Documentation link — local exact PDF unavailable](https://optoelectronics.liteon.com/upload/download/DS-22-99-0150/LTST-C170KRKT.pdf)

Checked 2026-11-03: 382,575 listed. Stocked listing screening only. Estimate: select 2-business-day service after vendor dispatch for ZIP 85212; confirm dated checkout arrival within 10 calendar days after order. No confirmed delivery date.

Red 0805 LED. Exact manufacturer datasheet was verified online, but its download endpoint did not yield a usable local PDF. The local Lite-On LED catalog provides the part and package data; retain the exact datasheet link for later download.

### M20-1060800

[DigiKey / 952-2234-ND](https://www.digikey.com/en/products/detail/harwin-inc/M20-1060800/3728198) | [Local manufacturer documentation](datasheets/Harwin-M20-106.pdf)

Checked 2026-11-03: 4,866 listed. Stocked listing screening only. Estimate: select 2-business-day service after vendor dispatch for ZIP 85212; confirm dated checkout arrival within 10 calendar days after order. No confirmed delivery date.

Four empty 8-position housings for both ends of J6/J7 LCD groups. Contacts purchased separately. 13 conductors only; omit LCD positions 3/15/16. J5 has no attached accessory harness or allocated external power load in Revision J. Mark pin 1 and verify wiring.

### M20-1180046

[DigiKey / 952-2159-ND](https://www.digikey.com/en/products/detail/harwin-inc/M20-1180046/3728125) | [Local manufacturer documentation](datasheets/Harwin-M20-118.pdf)

Checked 2026-11-03: 61,171 listed. Stocked listing screening only. Estimate: select 2-business-day service after vendor dispatch for ZIP 85212; confirm dated checkout arrival within 10 calendar days after order. No confirmed delivery date.

26 contacts: both ends of 13 LCD conductors, housed in four M20-1060800 housings. The 25-piece price tier applies to 26; contacts are each, not packs. No contacts in LCD positions 3, 15, 16.

### M20-9990845

[DigiKey / 952-2000-ND](https://www.digikey.com/en/products/detail/harwin-inc/M20-9990845/3727965) | [Local manufacturer documentation](datasheets/Harwin-M20-999.pdf)

Checked 2026-11-03: 5,157 listed. Stocked listing screening only. Estimate: select 2-business-day service after vendor dispatch for ZIP 85212; confirm dated checkout arrival within 10 calendar days after order. No confirmed delivery date.

Three 1x8 male board headers J5-J7. Four female LCD housings are listed separately for J6/J7 and LCD ends. J5 is spare GPIO, with no external power budget or attached cable required.

### M20-9991645

[DigiKey / 952-3304-ND](https://www.digikey.com/en/products/detail/harwin-inc/M20-9991645/3921260) | [Local manufacturer documentation](datasheets/Harwin-M20-999.pdf)

Checked 2026-11-03: 1,383 listed. Stocked listing screening only. Estimate: select 2-business-day service after vendor dispatch for ZIP 85212; confirm dated checkout arrival within 10 calendar days after order. No confirmed delivery date.

One separately purchased 1x16 header fitted to DS1. Verify soldering orientation and pin 1.

### PJ-002A

[DigiKey / CP-002A-ND](https://www.digikey.com/en/products/detail/same-sky-formerly-cui-devices/PJ-002A/96962) | [Local manufacturer documentation](datasheets/PJ-002A.pdf)

Checked 2026-11-03: 83,214 listed. Stocked listing screening only. Estimate: select 2-business-day service after vendor dispatch for ZIP 85212; confirm dated checkout arrival within 10 calendar days after order. No confirmed delivery date.

Same Sky 2.0 mm center-pin PCB jack. Footprint requires plated slots. Confirm fabricator capability and physical fit; the selected adapter has a 5.5 x 2.1 mm center-positive plug.

### PPTC281LFBN-RC

[DigiKey / S7026-ND](https://www.digikey.com/en/products/detail/sullins-connector-solutions/PPTC281LFBN-RC/810166) | [Local manufacturer documentation](datasheets/Sullins-Sockets.pdf)

Checked 2026-11-03: 1,046 listed. Stocked listing screening only. Estimate: select 2-business-day service after vendor dispatch for ZIP 85212; confirm dated checkout arrival within 10 calendar days after order. No confirmed delivery date.

Two 1x28 female socket strips retained, 2.54 mm pitch, matching U1 15.24 mm row separation. Verify drill/tail fit, mating height and USB clearance.

### RC1206FR-0710KL

[DigiKey / 311-10.0KFRCT-ND](https://www.digikey.com/en/products/detail/yageo/RC1206FR-0710KL/728483) | [Local manufacturer documentation](datasheets/Yageo-RC.pdf)

Checked 2026-11-03: 1,568,116 listed. Stocked listing screening only. Estimate: select 2-business-day service after vendor dispatch for ZIP 85212; confirm dated checkout arrival within 10 calendar days after order. No confirmed delivery date.

### RC1206FR-071KL

[DigiKey / 311-1.00KFRCT-ND](https://www.digikey.com/en/products/detail/yageo/RC1206FR-071KL/728387) | [Local manufacturer documentation](datasheets/Yageo-RC.pdf)

Checked 2026-11-03: 624,451 listed. Stocked listing screening only. Estimate: select 2-business-day service after vendor dispatch for ZIP 85212; confirm dated checkout arrival within 10 calendar days after order. No confirmed delivery date.

### RC1206FR-072K2L

[DigiKey / 311-2.20KFRCT-ND](https://www.digikey.com/en/products/detail/yageo/RC1206FR-072K2L/728624) | [Local manufacturer documentation](datasheets/Yageo-RC.pdf)

Checked 2026-11-03: 5 listed. Stocked listing screening only. Estimate: select 2-business-day service after vendor dispatch for ZIP 85212; confirm dated checkout arrival within 10 calendar days after order. No confirmed delivery date.

Exact 2.2k, 1%, 0.25 W, 1206 retained. Prior stock snapshot was low; recheck available quantity and fulfillment before ordering.

### RC1206FR-07470RL

[DigiKey / 311-470FRCT-ND](https://www.digikey.com/en/products/detail/yageo/RC1206FR-07470RL/728934) | [Local manufacturer documentation](datasheets/Yageo-RC.pdf)

Checked 2026-11-03: 36,612 listed. Stocked listing screening only. Estimate: select 2-business-day service after vendor dispatch for ZIP 85212; confirm dated checkout arrival within 10 calendar days after order. No confirmed delivery date.

R4 is the shared LCD R/W and DB0-DB3 pull-down in Revision J.

### RC1206FR-0747KL

[DigiKey / 311-47.0KFRCT-ND](https://www.digikey.com/en/products/detail/yageo/RC1206FR-0747KL/731878) | [Local manufacturer documentation](datasheets/Yageo-RC.pdf)

Checked 2026-11-03: 193,220 listed. Stocked listing screening only. Estimate: select 2-business-day service after vendor dispatch for ZIP 85212; confirm dated checkout arrival within 10 calendar days after order. No confirmed delivery date.

### RC1206FR-074K7L

[DigiKey / 311-4.70KFRCT-ND](https://www.digikey.com/en/products/detail/yageo/RC1206FR-074K7L/728887) | [Local manufacturer documentation](datasheets/Yageo-RC.pdf)

Checked 2026-11-03: 21,581 listed. Stocked listing screening only. Estimate: select 2-business-day service after vendor dispatch for ZIP 85212; confirm dated checkout arrival within 10 calendar days after order. No confirmed delivery date.

### RC1206JR-070RL

[DigiKey / 311-0.0ERCT-ND](https://www.digikey.com/en/products/detail/yageo/RC1206JR-070RL/732131) | [Local manufacturer documentation](datasheets/Yageo-RC.pdf)

Checked 2026-11-03: 2,009,135 listed. Stocked listing screening only. Estimate: select 2-business-day service after vendor dispatch for ZIP 85212; confirm dated checkout arrival within 10 calendar days after order. No confirmed delivery date.

Exact specified 0-ohm link retained, 1206, 0.25 W, 2 A. Export also says 1% tolerance; that is not a meaningful percentage for a zero-ohm jumper. Use the manufacturer maximum resistance/current specification rather than claim 1% accuracy.

### SN74LVC1G17DBVR

[DigiKey / 296-11933-1-ND](https://www.digikey.com/en/products/detail/texas-instruments/SN74LVC1G17DBVR/389051) | [Local manufacturer documentation](datasheets/SN74LVC1G17.pdf)

Checked 2026-11-03: 195,878 listed. Stocked listing screening only. Estimate: select 2-business-day service after vendor dispatch for ZIP 85212; confirm dated checkout arrival within 10 calendar days after order. No confirmed delivery date.

### T350F226K016AT

[DigiKey / 399-3574-ND](https://www.digikey.com/en/products/detail/kemet/T350F226K016AT/818435) | [Local manufacturer documentation](datasheets/KEMET-T350.pdf)

Checked 2026-11-03: 95 listed. Stocked listing screening only. Estimate: select 2-business-day service after vendor dispatch for ZIP 85212; confirm dated checkout arrival within 10 calendar days after order. No confirmed delivery date.

C4 regulator output: 22 uF/16 V, +/-10%, 2.54 mm pitch. Observe polarity and verify installed LM1086 loop stability with the actual parallel capacitors and LCD harness.

### T491A225K025AT

[DigiKey / 399-10122-1-ND](https://www.digikey.com/en/products/detail/kemet/T491A225K025AT/3759239) | [Local manufacturer documentation](datasheets/KEMET-T491.pdf)

Checked 2026-11-03: 17,891 listed. Stocked listing screening only. Estimate: select 2-business-day service after vendor dispatch for ZIP 85212; confirm dated checkout arrival within 10 calendar days after order. No confirmed delivery date.

C6: positive pad 1 to BUTTON_FILTERED. 3.2 x 1.6 mm, height <=1.8 mm. Exact Revision J capacitor replaces former 1 uF X7R candidate; former C12 purchase hold is superseded. Revision J debounce/capacitance/leakage bench checks remain pending.

### TST-104-01-G-D

[DigiKey / TST-104-01-G-D-ND](https://www.digikey.com/en/products/detail/samtec-inc/TST-104-01-G-D/9497049) | [Local manufacturer documentation](datasheets/Samtec-TST.pdf)

Checked 2026-11-03: 37 listed. Stocked listing screening only. Estimate: select 2-business-day service after vendor dispatch for ZIP 85212; confirm dated checkout arrival within 10 calendar days after order. No confirmed delivery date.

Three 2x4 shrouded headers for the peer UART interfaces; three double-ended cables are listed separately. The peer boards supply their own corresponding headers.

### WSU090-1300

[DigiKey / 237-1451-ND](https://www.digikey.com/en/products/detail/triad-magnetics/WSU090-1300/3094977) | [Local manufacturer documentation](datasheets/WSU090-1300.pdf)

Checked 2026-11-03: 2,121 listed. Stocked listing screening only. Estimate: select 2-business-day service after vendor dispatch for ZIP 85212; confirm dated checkout arrival within 10 calendar days after order. No confirmed delivery date.

Regulated 9 V, 1.3 A wall adapter, center-positive 5.5 x 2.1 mm plug. Compatible nominal mating size for PJ-002A; verify polarity and plug insertion fit physically.

### IDSD-04-D-08.00-G

[Mouser / 200-IDSD04D0800G](https://www.mouser.com/ProductDetail/Samtec/IDSD-04-D-08.00-G?qs=0lQeLiL1qyZIFjM6oRjn%252BA%3D%3D) | [Local manufacturer documentation](datasheets/Samtec-IDSD.pdf)

Checked 2026-11-03: 35 listed. Stocked listing screening only. Estimate: select 2-business-day service after vendor dispatch for ZIP 85212; confirm dated checkout arrival within 10 calendar days after order. No confirmed delivery date.

User approved the -G gray-cable version on November 2, 2026. Samtec identifies -G as gray cable; same 8-inch length, connector geometry and standard wiring as IDSD-04-D-08.00. Verify pin-1 orientation and end-to-end continuity before connection.

### LM1086IT-5.0/NOPB

[Mouser / 926-LM1086IT50NOPB](https://www.mouser.com/ProductDetail/Texas-Instruments/LM1086IT-5.0-NOPB?qs=sGAEpiMZZMug9GoBKXZ759%2FWxdjGb5obqWlryGQJdV0%3D) | [Local manufacturer documentation](datasheets/TI-LM1086.pdf)

Checked 2026-11-03: 83 listed. Stocked listing screening only. Estimate: select 2-business-day service after vendor dispatch for ZIP 85212; confirm dated checkout arrival within 10 calendar days after order. No confirmed delivery date.

Exact TI part retained. DigiKey direct stock was zero, 45 expected November 10, 2026, so Mouser selected. Pins 1 GND, 2 OUT, 3 IN; live tab is OUT. Installed thermal resistance <=60 C/W or heatsink qualification required; no heatsink assumed until layout testing.

### NHD-0216K1Z-FSW-FTW-FB1

[Mouser / 763-0216K1Z-FSWFTWFB](https://www.mouser.com/ProductDetail/Newhaven-Display/NHD-0216K1Z-FSW-FTW-FB1?qs=sGAEpiMZZMt7dcPGmvnkBpdHgMVhq5cu2av6HIr5mGo%3D) | [Local manufacturer documentation](datasheets/Newhaven-FB1.pdf)

Checked 2026-11-03: 95 listed. Stocked listing screening only. Estimate: select 2-business-day service after vendor dispatch for ZIP 85212; confirm dated checkout arrival within 10 calendar days after order. No confirmed delivery date.

Exact Revision J LCD retained. Mouser marks NRND; stock snapshot is 95 in the USD listing, other regional listings differ. Recheck before ordering. Pins 3/15/16 must remain unconnected; power and automatic backlight use pins 1/2. Header purchased separately; no package inclusion credited.

### EEUFR1E470

[Newark / 92Y6310](https://www.newark.com/panasonic/eeufr1e470/cap-alu-elec-47uf-25v-20/dp/92Y6310) | [Local manufacturer documentation](datasheets/Panasonic-FR.pdf)

Checked 2026-11-03: 2,294 listed. Published 4-6 business days from UK stock; normal-week estimate can fit 10 calendar days, but checkout arrival to 85212 is unconfirmed.

Manufacturer writes EEUFR1E470; distributor aliases include EEU-FR1E470. Exact 47 uF, 25 V, 5 mm diameter, 2 mm pitch part retained. Newark lists UK stock with 4-6 business-day delivery; confirm ZIP-specific checkout ETA.

## Documentation and release checks

Exact local PDFs unavailable for: 3811/16 100, LTST-C170KRKT. The Lite-On catalog is included for the LED. Online manufacturer links remain available. Local 3M download was denied by its server.

[Lite-On LED catalog](datasheets/LiteOn-LED-Catalog.pdf)

Hardware checks remain pending as recorded in the packaged Revision J qualification checklist. The PDF is a local preview; export the published website again for final submission.

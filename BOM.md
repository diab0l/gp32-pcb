# GP32 Bottomside
| Component | Marking | Measured value | Notes |
| --- | --- | --- | --- |
| C7 | GFT 10 16V || (elco) |
| C38 | 227A M121T || (ta) |
| C39 | 227A M121T || (ta) |
| C41 | 106A M22 1P || (ta) |
| C42 | 106A M22 1P || (ta) |
| C45 | 106A M22 1P || (ta) |
| C49 | GCZ 100 6V || (elco) |
| C52 | GCZ 100 6V || (elco) |
| C57 | 106A M22 1P || (ta) |
| C60 | GEY 22 16V || (elco) |
| C62 | GEF 22 35V || (elco) |
| C70 | GBP 4.7 50V || (elco) |
| C72 | GEF 2.2 50V || (elco) |
| C73 | GEF 2.2 50V || (elco) |
| C76 | 225C M3507 || (ta) |
| C77 | GFT 10 16V || (elco) |
| C79 | 106A M22 1P || (ta) |
| C81 | GFT 10 16V || (elco) |
| C89 | GFT 10 16V || (elco) |
| C90 | 227A M121T || (ta) |

CON1 - ext connector (18pin)
CON2 - weird usb connector

J1 - SMC connector
J3 - volume wheel (5pin)
J4 - AC power (center negative ffs)

LS1 - right speaker
LS2 - left speaker

R4 - 470
R5 - 472
R6 - 103 (9.5kOhm)
R8 - 470
R10 - 103
R11 - 103
R12 - 101
R13 - (11.3 kOhm)
R14 - 122
R15 - 391
R16 - 122
R17 - (670 Ohm)
R18 - 115
R19 - (354 Ohm)
R20 - 391
R21 - 221
R22 - 222
R23 - 101 (103 Ohm)
R24 - 334 (330 kOhm)
R25 - 0
R26 - 102
R27 - 122
R29 - 1R0 (1 Ohm)
R31 - 122
R32 - 102
R33 - 423?
R34 - 152
R35 - 220
R36 - 220
R37 - 640
R38 - 823
R39 - 153
R40 - 913
R41 - 563
R42 - 303
R43 - 103
R44 - 123 (12 kOhm)
R45 - 103 (9.5 kOhm)
R46 - 103
R47 - 153
R48 - 300
R49 - 124
R50 - 105
R51 - 303 (19 kOhm)
R52 - 640
R53 - 512
R54 - 563
R55 - 303 (20 kOhm)
R56 - 273
R57 - 363
R58 - 123 (9 kOhm)
R59 - 303 (20 kOhm)
R60 - (20 kOhm)
R61 - 123
R63 - 220
R64 - 220
R65 - 220
R66 - 220
R67 - 220
R72 - 473 (47 kOhm)
R73 - 473
SW1 - SPDT power switch

S1 - 90 degree smd microswitch
S2 - 90 degree smd microswitch
S3 - dpad left microswitch
S4 - dpad down microswitch
S5 - dpad right microswitch
S6 - dpad up microswitch

T1 - VCC? (FLU red wire connects here)
T7 - GND? (FLU black wire connects here)

U2 - SL74HC14D 0144 (DIP-14 hex inverter, datasheet found)
U3 - Hynix HY57V641620HG 0148AA T-H (SDRAM, datasheet found)
U5 - L91SC S102 (DIP-8)
U7 - 11TI ACH (DIP-8)
U8 - 1330A 06480 H0062 (DIP-16)
U9 - LTPG (DIP-10, power management ic?)
U10 - LTKS (2/3 pin dip, maybe a transistor?)
U11 - A6CN (3/2 pin dip)
U12 - LTKG (3/2 pin dip)
U13 - MM17AH LMV324M (DIP-14)

Y1 - ? (crystal, value unknown)
Y2 - 12.000 (12 Mhz crystal)

# GP32 Topside
J2 - 50pin FPC (display)
U1 - Samsung S3C2400X01-EER0 (LQFP208, datasheet found)
U4 - Atmel AT49BV040 90VC 0141 (DIP-32, flash rom)
U6 - Samsung 143 LPC3600 (QFP-32)
R1 - 103
R2 - 103
R3 - 103
R7 - 103 (9.6 kOhm)
R9 - 103
R62 - 471 (480 Ohm)
R76 - 220
R77 - 220
R78 - 220
R79 - 220
R80 - 220
R81 - 220
S7 - start button pad
S8 - B button pad
S9 - A button pad
S10 - select button pad

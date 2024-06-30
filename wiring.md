# Wiring reference

The following applies to PDIP package.

| EEPROM part | pin count |
|-------------|-----------|
| AT28C16     | 24        |
| AT28C32     | 28        |
| AT28C256    | 28        |

Pin ID is the reference in the datasheet.

There are two Shift Registers (74HC595), SR1 and SR2.

| pin ID | function    | AT28C16 pin# | AT28C32 pin# | AT28C256 pin# | wire to |
|--------|-------------|---------|--------------|--------------|---------------|
| A0     | address bus | 8 | | | 
| A1   | address bus | 7 | | | 
| A2   | address bus | 6 | | | 
| A3    | address bus | 5 | | | 
| A4   | address bus | 4 | | | 
| A5    | address bus | 3 | | | 
| A6    | address bus | 2 | | | 
| A7    | address bus | 1 | | | 
| A8    | address bus | 23 | | | 
| A9    | address bus | 22 | | | 
| A10   | address bus | 19 | | | 
| A11    | address bus | - | | | 
| CEn | chip enable | 18 | | | 
| OEn | output enable | 20 | | | 
| WEn | write enable | 21 | | | 
| IO0 | data bus | 9 | | | 
| IO1 | data bus | 10 | | | 
| IO2 | data bus | 11 | | | 
| IO3 | data bus | 13 | | | 
| IO4 | data bus | 14 | | | 
| IO5 | data bus | 15 | | | 
| IO6 | data bus | 16 | | | 
| IO7 | data bus | 17 | | | 
| GND | power | 12 | | | 
| Vcc | power | 24 | | | 

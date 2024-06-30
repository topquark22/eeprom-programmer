# Wiring reference

The following applies to PDIP package.

| EEPROM part | pin count |
|-------------|-----------|
| AT28C16     | 24        |
| AT28C32     | 28        |
| AT28C256    | 28        |

Pin ID is the reference in the EEPROM datasheet.

There are two Shift Registers (74HC595), SR1 and SR2.

D# are Arduino pins.

| EEPROM pin ID | function    | AT28C16 pin# | AT28C32 pin# | AT28C256 pin# | wire to |
|--------|-------------|---------|--------------|--------------|---------------|
| A0     | address bus | 8 | | | SR1 15 | 
| A1   | address bus | 7 | | | SR1 1 | 
| A2   | address bus | 6 | | SR1 2 | 
| A3    | address bus | 5 | | | SR1 3 | 
| A4   | address bus | 4 | | | SR1 4 | 
| A5    | address bus | 3 | | | SR1 5 | 
| A6    | address bus | 2 | | | SR1 6 | 
| A7    | address bus | 1 | | | SR1 7 | 
| A8    | address bus | 23 | | | SR2 15  | 
| A9    | address bus | 22 | | | SR2 1 | 
| A10   | address bus | 19 | | | SR2 2 | 
| A11    | address bus | - | | | SR2 3 | 
| CEn | chip enable | 18 | | | GND | 
| OEn | output enable | 20 | | | SR2 7|
| WEn | write enable | 21 | | | D13 |
| I/O0 | data bus | 9 | | | D5 | 
| I/O1 | data bus | 10 | | | D6 | 
| I/O2 | data bus | 11 | | | D7 | 
| I/O3 | data bus | 13 | | | D8 | 
| I/O4 | data bus | 14 | | | D9 | 
| I/O5 | data bus | 15 | | | D10 | 
| I/O6 | data bus | 16 | | | D11 | 
| I/O7 | data bus | 17 | | | D12 | 
| GND | power | 12 | | | GND | 
| Vcc | power | 24 | | |  +5V | 

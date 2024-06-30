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

| EEPROM pin ID | function    | AT28C16 pin | AT28C32 pin | AT28C256 pin | wire to |
|--------|-------------|---------|--------------|--------------|---------------|
| A0     | address bus | 8 | | 10 | SR1 15 | 
| A1   | address bus | 7 | | 9 | SR1 1 | 
| A2   | address bus | 6 | | 8 | SR1 2 | 
| A3    | address bus | 5 | | 7| SR1 3 | 
| A4   | address bus | 4 | | |6 SR1 4 | 
| A5    | address bus | 3 | | 5 | SR1 5 | 
| A6    | address bus | 2 | | 4 | SR1 6 | 
| A7    | address bus | 1 | | 3 | SR1 7 | 
| A8    | address bus | 23 | | 25 | SR2 15  | 
| A9    | address bus | 22 | | 24 | SR2 1 | 
| A10   | address bus | 19 | | 21 | SR2 2 | 
| A11   | address bus | - | | 23 | SR2 3 |
| A12   | address bus | - | | 2 | SR2 4 |
| A13 | address bus | - | | 26 | SR2 5 |
| A14 | address bus | - | | 1 | SR2 6 |
| CEN | chip enable | 18 | | 20 | GND | 
| OEN | output enable | 20 | | 22 | SR2 7|
| WEN | write enable | 21 | | 27| D13 |
| I/O0 | data bus | 9 | | 11 | D5 | 
| I/O1 | data bus | 10 | | 12 | D6 | 
| I/O2 | data bus | 11 | | 13 | D7 | 
| I/O3 | data bus | 13 | | 15 | D8 | 
| I/O4 | data bus | 14 | | 16 | D9 | 
| I/O5 | data bus | 15 | | 17 | D10 | 
| I/O6 | data bus | 16 | | 18 | D11 | 
| I/O7 | data bus | 17 | | 19 | D12 | 
| GND | power | 12 | | 14 | GND | 
| Vcc | power | 24 | | 28 |  +5V | 

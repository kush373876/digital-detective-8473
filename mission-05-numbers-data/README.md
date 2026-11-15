
# Mission 5 – Numbers and Data

## 1. Task / Objective

To understand decimal, binary and hexadecimal number systems, perform manual conversions, verify conversions using Python, build a number converter and understand text encoding.

## 2. Work Completed

- Completed all seven manual number conversions.
- Verified conversions using Python built-in functions.
- Created `number_converter.py`.
- Tested the converter with 10, 25 and 100.
- Studied ASCII and text encoding.

### Manual Conversions

| Question | Answer |
|---|---|
| Decimal 13 to Binary | 1101 |
| Decimal 25 to Binary | 11001 |
| Binary 1010 to Decimal | 10 |
| Binary 1101 to Decimal | 13 |
| Hexadecimal A to Decimal | 10 |
| Hexadecimal 1F to Decimal | 31 |
| Binary 1111 to Hexadecimal | F |

### Python Verification

| Python Expression | Result |
|---|---|
| bin(13) | 0b1101 |
| bin(25) | 0b11001 |
| int('1010', 2) | 10 |
| int('1101', 2) | 13 |
| hex(13) | 0xd |
| hex(25) | 0x19 |
| int('A', 16) | 10 |
| int('1F', 16) | 31 |

All Python results matched the manual calculations.

### Number Converter Test Results

| Input | Binary | Hexadecimal |
|---|---|---|
| 10 | 0b1010 | 0xa |
| 25 | 0b11001 | 0x19 |
| 100 | 0b1100100 | 0x64 |

### Text Encoding

- Uppercase A ASCII decimal value: 65
- Lowercase a ASCII decimal value: 97
- Example of a character outside basic ASCII: ₹

A computer needs an encoding standard to represent characters as numerical codes. This allows computers to store, transmit and display text consistently.

UTF-8 supports characters from many languages and symbols beyond basic ASCII.

## 3. Commands / Tools Used

- `cd` – Navigate between directories.
- `touch` – Create files.
- `python3` – Run Python programs and interactive mode.
- `bin()` – Convert decimal to binary.
- `hex()` – Convert decimal to hexadecimal.
- `int(value, 2)` – Convert binary to decimal.
- `int(value, 16)` – Convert hexadecimal to decimal.
- `input()` – Accept user input.
- `print()` – Display output.

## 4. My Understanding

Decimal uses base 10, binary uses base 2 and hexadecimal uses base 16.

I learned how to convert numbers manually using place values and repeated division. I also learned how Python can perform these conversions using built-in functions.

The number converter accepts a decimal number and displays its binary and hexadecimal representations.

## 5. Difficulties Faced

Write about the actual difficulties you faced while completing this mission.

## 6. How I Resolved Them

I practised the conversion methods and used Python to verify my answers.

## 7. Evidence / Files

- `number_converter.py` – Python number converter.
- `README.md` – Mission documentation.
- Terminal outputs – Conversion and program testing evidence.

## 8. Commit Details

Commit message: `Build number converter and practise data representation`

Changes pushed to the GitHub repository after verification.

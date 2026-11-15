TASK 5.1:
-->Conversion	|Working	|Answer
1. Decimal 13 to binary	|13 = 8 + 4 + 1	|1101
2. Decimal 25 to binary	|25 = 16 + 8 + 1	|11001
3. Binary 1010 to decimal	|8 + 2	|10
4. Binary 1101 to decimal	|8 + 4 + 1	|13
5. Hexadecimal A to decimal	|A = 10	|10
6. Hexadecimal 1F to decimal	|1 × 16 + 15	|31
7. Binary 1111 to hexadecimal	|1111 = 15	|F

TASK 5.2:
-->Used Python's built-in conversion functions to verify the manual calculations.
-->Expression	|Result
1. bin(13)	|0b1101
2. bin(25)	|0b11001
3. int('1010', 2)	|10
4. int('1101', 2)	|13
5. int('A', 16)	|10
6. int('1F', 16)	|31
7. hex(15)	|0xf
The Python results matched the manual calculations.

TASK 5.3:
Created a Python program named number_converter.py.

The program:
- Accepts a decimal number from the user.
- Converts the number into binary.
- Converts the number into hexadecimal.
- Displays both results.

Python functions used:
- input() – Accepts input from the user.
- int() – Converts input into an integer.
- bin() – Converts an integer into binary representation.
- hex() – Converts an integer into hexadecimal representation.

Sample test cases:
-->Decimal input	|Binary output	|Hexadecimal output
1. 10	|0b1010	|0xa
2. 13	|0b1101	|0xd
3. 25	|0b11001	|0x19

TASK 5.4:
- ASCII code of uppercase A = 65.
- ASCII code of lowercase a = 97.
- UTF-8 supports a much wider range of characters than basic ASCII.
Why is encoding necessary?

Computers store information in binary form. Character encoding provides a standard way to represent letters, numbers and symbols using bytes so that computers can store and interpret text correctly.

Example of a character outside basic ASCII: ₹

3. Commands / tools used
- python3 – Opened the Python environment and executed the program.
- bin() – Converted decimal integers into binary.
- hex() – Converted decimal integers into hexadecimal.
- int() – Converted binary and hexadecimal strings into decimal.
- input() – Accepted user input.
- print() – Displayed conversion results.
- python3 number_converter.py – Executed the converter program.

4. My understanding
Computers use binary because their electronic circuits represent information using two states, 0 and 1. Decimal, binary and hexadecimal are different number systems. Python provides built-in functions to convert between these number systems. Character encoding allows computers to represent and store text in binary form.

5. Difficulties Faced

One thing I needed to understand was how binary and hexadecimal values are represented in Python. The prefixes 0b and 0x initially looked like part of the converted number.

6. How I Resolved Them

I checked the output of Python's built-in conversion functions and learned that 0b identifies a binary value and 0x identifies a hexadecimal value. I also used the manual calculations to cross-check the results.

7. Evidence / files
- Manual conversion calculations
- Python verification results
- number_converter.py
- Three or more converter test cases
- Text encoding notes
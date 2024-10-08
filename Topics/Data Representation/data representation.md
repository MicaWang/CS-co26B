# Summary of Data Representation

Oct.8th 2024, Mica Wang

## Summary Poster

![Computer Science FA - Daisy Mica James](https://github.com/user-attachments/assets/4f52b37d-e53d-4dc6-bb33-fa11e62e9810)

If the picture doesn't display, click [here](https://keystoneacademy-my.sharepoint.com/:i:/g/personal/xuanyi_wang_student_keystoneacademy_cn/ETN0YR1zLbFLmp5TNoHWxO4BX2HYDn5-vuUS2G5pAK9uvg?e=7ylgDZ)

## Intro

Computers are multimedia devices that deal with a vast array of information categories
It *stores, presents, and modifies*:
- Numbers, and
- Text, Audio, Images and graphics, Video

Clarification in definitions([1](https://www.baeldung.com/cs/data-vs-information)):
- **Data**: raw, unprocessed facts that need context to become useful
  - In forms of numbers, characters,ect.
- **Information**: processed data (supports with context, and interprets with meanings)
  - In forms of data + information
  - In forms of words, numbers, and pictures that we can understand
- Computer convert data to information
  - IPO: input - process - output
 
Two ways to represent information
- **Analog data**: continuous representation
  - Applied in sensors (robots)
  - Used voltage: fluctuate: set a threshold + time
- **Digital data**: a discrete representation, breaking the information up into separate elements
  - Digitize: Mimic the continuous data in a digital way
  - Has only high or low states —> correspond to the two binary digits
- Both electric signals degrade as they move down a line
  - The signal is re-clocked periodically to regain its original shape
![analog-signal-5874227_6408591759982719198857](https://github.com/user-attachments/assets/34f4a0ca-a5dd-409b-9fc9-7a245a792724)


## Number Systems

***Decimal/Denary Number System***
A **base 10** number system which uses digits from **0 to 9**
- Unique digits: 0, 1, 2, 3, 4, 5, 6, 7, 8, 9
- Positional notation: 10^0, 10^1, 10^2, etc.

***Binary Number System***
A **base 2** number system which uses two digits: 0 and 1
- Use electric pulses to represent digits: operating in two states:
  - On/off - storage
  - True/false - logic
- Positional notation: 2^0, 2^1, 2^2, etc.
- e.g. 45 = 101101 (32+8+4+1 —> turn on 32, 8, 4, 1; turn off 16, 2)

**Bit** (位数 unit of binary digits)
- *Basic and smallest* unit of computer system: also storage unit
  - Can hold one of two values: 0 or 1
  - Can be grouped together
  - e.g. largest number to be represented by 5 bits: 31 = 1+2+4+8+16, looks like: 11111
- *Word Length*: number of bits in a word

**Byte**
- 1 byte = 8 bits
  - Can represent 256 things

- 1 MB (Megabyte) = 1,000,000B (bytes)

***Hexadecimal Number System***
A Base-16 number system using digits: 
- 0,1,2,3,4,5,6,7,8,9,A(10),B(11),C(12),D(13),E(14),F(15)
  - Can use 4 bits to represent all digits
- Commonly used to represent color code

***Conversion***

*Check the poster**

- How to convert from binary to hexadecimal:
  - Group the binary numbers by 4
  - E.g. 01101101 = 6D
  - Split it into 0110 & 1101, 0110 = 6, 1101 = 13 = D
- How to convert from hexadecimal to decimal
  - e.g. 6D = 6*16^1+D*16^0 = 96 + 13 = 109
  - But it’s easier to convert to binary first, than the decimal

# X7000-Reference
Wavetek 7000 inspired voltage reference on the cheap.
![Refpic1](/img/a.jpg) ![Refpicé](/img/b.jpg) ![Refpic3](/img/c.jpg)

## As any FOSS thing operation and specs not guaranteed
## BOM list
-  The * denounces that these parts were used in development and there is probably a better alternative.
-  **(G)** denotes this is a generic part and nearly any alternative will do.
-  Socket and current setting resistor not included for the moment.

| Part name          | Manufacturer      | Quantity   | Price per (eur) | Notes                                                                   |
|:-------------------|:-----------------:|:----------:|:---------------:|------------------------------------------------------------------------:|
| NOMCT16031003AT1   | Vishay            |     1      |      3,64       |                                                                         |
| NOMCT16032001AT1   | Vishay            |     1      |      3,42       |                                                                         |
| NOMCT16031001AT1   | Vishay            |     1      |      3,29       |                                                                         |
|--------------------|-------------------|------------|-----------------|                                                                         |
| Y0785100R000T9L    | Vishay            |     1      |      21,53      | Can also be 120 for less drift with more noise, but TComp needs changed |
| PTF5621R000BYEK    | Vishay            |     1      |      5,11       | (or better more satble resistor) TComp                                  |
| TNPW0402137RBEED   | Vishay            |     1      |      0,67       | TComp trim to 18,18 Ohm                                                 |
|--------------------|-------------------|------------|-----------------|                                                                         |
| ADA4523-1BRZ       | Analog Devices    |     4      |      2,65       |                                                                         |
| LTZ1000CH#PBF      | Analog Devices    |     1      |      68,9       | Or LTZ1000ACH#PBF or ADR (untested)                                     |
| 1N4148UR-1         | Microchip         |     2(G)   |      0,81       |                                                                         |
| CRT1206-DY-1004ELF | Bourns            |     1(G)   |      0,35       |                                                                         |
| CRT1206-BY-1002EST | Bourns            |     1(G)   |      0,35       |                                                                         |
| CRT1206-BY-1001ELF | Bourns            |     1(G)   |      0,52       |                                                                         |
| CRT1206-BY-1002EST | Bourns            |     1(G)   |      0,35       |                                                                         |
| ERA-8AED302V       | Panasonic         |     1(G)   |      0,46       |                                                                         |
| ERA-8AEB4223V      | Panasonic         |     1(G)   |      0,58       |                                                                         |
| C1206C104K5RAC7867 | Kemet             |      4     |      0,12       |                                                                         |
| C1206X103K5RECAUT  | Kemet             |      1     |      0,44       |                                                                         |         
| 1206YC223MAT2A     | Kyocera           |      1     |      0,26       |                                                                         |
| SPZT3904T1G        | Onsemi            |      1     |      0,64       |                                                                         |
| **TOTAL**          |-------------------|------------|      1--,28     |                                                                         |


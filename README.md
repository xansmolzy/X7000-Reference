# X7000-Reference
Wavetek 7000 inspired voltage reference on the cheap.
![Refpic1](/img/a.jpg) ![Refpicé](/img/b.jpg) ![Refpic3](/img/c.jpg)

## As any FOSS thing operation and specs not guaranteed
## BOM list
-  The * denounces that these parts were used in development and there is probably a better alternative.
-  **(G)** denotes this is a generic part and nearly any alternative will do.

**⚠️For V0.1 and V0.2 RCur 124Ohm and 31.2Ohm were used, based on [work](https://xdevs.com/article/b7000/) 100Ohm and 18.2Ohm are encouraged but not tested⚠️**
**⚠️LTZ-A has oscillations in the order of 10uV⚠️**

If you like to stick to tested use 124 and 31.2Ohm respectively, when V0.3 gets assembled 100 and 18.2Ohm resistors will be used and data will be provided.


| Part name          | Manufacturer      | Quantity   | Price per (eur) | Notes                                                                   |
|:-------------------|:-----------------:|:----------:|:---------------:|------------------------------------------------------------------------:|
| NOMCT16031003AT1   | Vishay            |     1      |      3,64       |                                                                         |
| NOMCT16032001AT1   | Vishay            |     2      |      3,42       |                                                                         |
|--------------------|-------------------|------------|-----------------|                                                                         |
| Y0785100R000T9L    | Vishay            |     1      |      21,53      | RCur, can be 120 for less drift with more noise, RComp needs changed    |
| PTF5621R000BYEK    | Vishay            |     1*     |      5,11       | (or better more satble resistor) RComp                                  |
| TNPW0402137RBEED   | Vishay            |     1*     |      0,67       | RComp trim to 18,18 Ohm for 100Ohms RCur                                |
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


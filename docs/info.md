<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

This project drives a 7-segment common-cathode display to count from 0 to 9, incrementing with each pulse of an external clock signal. Once it reaches 9, the counter automatically resets and the sequence repeats continuously.s

## How to test

Connect the circuit to an external clock source and observe the 7-segment display. The digits should increment from 0 to 9 at the rate determined by the clock frequency, then restart from 0 once the cycle is complete.
N	State							Next State						
10	0	0	0	0	0	0	0	0	1	1	1	1	1	1
0	0	1	1	1	1	1	1	0	0	0	0	1	1	0
1	0	0	0	0	1	1	0	1	0	1	1	0	1	1
2	1	0	1	1	0	1	1	1	0	0	1	1	1	1
3	1	0	0	1	1	1	1	1	1	0	0	1	1	0
4	1	1	0	0	1	1	0	1	1	0	1	1	0	1
5	1	1	0	1	1	0	1	1	1	1	1	1	0	1
6	1	1	1	1	1	0	1	0	0	0	0	1	1	1
7	0	0	0	0	1	1	1	1	1	1	1	1	1	1
8	1	1	1	1	1	1	1	1	1	0	0	1	1	1
9	1	1	0	0	1	1	1	0	1	1	1	1	1	1
<img width="826" height="289" alt="image" src="https://github.com/user-attachments/assets/e1a01806-39f7-433b-baa4-abd1abe0d8e0" />


## External hardware

- 7-segment common-cathode display
- External clock signal source

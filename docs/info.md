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

<img width="1106" height="352" alt="image" src="https://github.com/user-attachments/assets/3458c679-47f1-403c-b006-b29dd375a55e" />

## External hardware

- 7-segment common-cathode display
- External clock signal source

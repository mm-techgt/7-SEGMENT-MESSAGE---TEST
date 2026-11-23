<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

The logic to light the characters appears in the bottom half of the simulation window. The top half of the simulation window implements a modulo-12 counter. In other words, the counter increments up to 11 then resets. This counter is used to determine which character we should output to the 7-segment display. The truth table for the design can be found in the Design Spreadsheet.

## How to test

Turn all pins OFF, keep the clock running and watch the rolling text on the 7-segment display. Or turn pin 3 ON and manually select a letter using pins 4 to 7.

## External hardware

none

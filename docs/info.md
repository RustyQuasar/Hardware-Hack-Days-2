<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

Uses an OR gate, AND gate, Inverted gate, and a MUX gate.

An Inverted gate is connected to ui[0] and is recieved by uo[0], any input will be inverted.
An AND gate is connected to ui[1] and ui[2], but is received by uo[2]. Unless both inputs are 1, uo[2] will recieve 0.
A MUX gate is connected to ui[5] and ui[6] for interchangeable inputs, with ui[7] acting as the the switch. 
An OR gate is connected to the output of the MUX gate and ui[4], with uo[6] recieving 1 if either the MUX gate or ui[4] is 1.

## How to test

Use switches attached to see if the above behaviour is occuring. 

## External hardware

N/A



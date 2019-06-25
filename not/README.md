# Not Gate

This folder contains an implementation of a not gate using `nmos` and `pmos` transistors.

The `not.v` folder contains the module, wheras the `not_tb.v` contains the test bench to test the module.


## Truth Tables

Here is the truth table for the gate. Given the input, the output is as expected.

 Input | Output 
 ----- | ------
   0   |   1
   1   |   0

## Schematic

The KiCad schematic is contained in /* TODO fill in here */

The circuit for this particular gate is shown below:

![Image of Not Gate Schematic](https://github.com/abhishekpratapa/computer/not/assets/not.png)

## To Build

```
iverilog -o not not.v not_tb.v 
```

## To run in the terminal

```
vvp not
```

## To run in GTKWave

```
gtkwave not.vcd
```
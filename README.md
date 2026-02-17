# Lab 05 - Combinatorial Logic

In this lab, you’ve learned real world applications of digital logic, as well
as how to assemble your own Verilog modules. In addition, you’ve learned how
the constraints file maps your inputs and outputs to real pins on the FPGA.

## Rubric

|Item|Description|Value|
|-|-|-|
|Summary Answers|Your writings about what you learned in this lab.|25%|
|Question 1|Your answers to the question|25%|
|Question 2|Your answers to the question|25%|
|Question 3|Your answers to the question|25%|

## Name

## Lab Summary

In this lab, we had practice mapping circuits to other circuits with wires. We also had a more in depth understanding of the constraints file and used it to identify the Basys 3 switches and leds that are going to be used in our simulation (output and input pins). We created our own top file, which took the functions from our A and B circuits and mapped them onto the circuit board.

## Lab Questions

### 1 - Explain the role of the Top Level file.

The top level file connects our coded circuit to the hardware/circuit board.

### 2 - Explain the function of the Constraints file.

We used the file to identify the parameters implemented in our circuit, seven switches and two leds, by “uncommenting” them on the file so that Vivado would recognize them and assign them accordingly to the project.

3 - Was the selection of Minterm and Maxterm correct for each circuit? What would you have chosen?
The selection we chose for both circuits was an accurate demonstration of its actual inputs/outputs. The SOP and POS for Circuit A would have been represented exactly the same way (~A\&D). We would’ve chosen SOP for circuit A, since there’s a convenient group of four rather than two groups of 8. An SOP for Circuit B would have been the most effective way to represent the function due to larger group sizes.


# Lab 05 - Combinatorial Logic

In this lab, you’ve learned real world applications of digital logic, as well
as how to assemble your own Verilog modules. In addition, you’ve learned how
the constraints file maps your inputs and outputs to real pins on the FPGA.

## Rubric

| Item | Description | Value |
| ---- | ----------- | ----- |
| Summary Answers | Your writings about what you learned in this lab. | 25% |
| Question 1 | Your answers to the question | 25% |
| Question 2 | Your answers to the question | 25% |
| Question 3 | Your answers to the question | 25% |

## Lab Questions

Summary:

In this lab, we learned how to implement combinational logic circuits in Verilog using minterms and maxterms. We created a file for circuit a using maxterms and another file for circuit b using minterms. We then combined them into the top.v file connecting the output from circuit a as an input for circuit b. We also learned how to read constraints files, which assign logical signals in Verilog to physical pins on the FPGA so that inputs from switches and outputs to LEDs function properly.


### 1 - Explain the role of the Top Level file.
The top.v file made it so we could connect circuit a and circuit b together by assigning the switches and LED’s to each input and output. The output for circuit a was led[0] so we used led[0] as an input for circuit b to connect them.

### 2 - Explain the function of the Constraints file.
The constraints file allows us to program our board in the way we want to. By activating which switching and LED’s we want to use, we have to go into the file and uncomment all the switches and LED’s we want to use on the board. This essentially is just a background file for the board, so that it knows which LED’s and Switches we are using.

### 3 - Was the selection of Minterm and Maxterm correct for each circuit? What would you have chosen?
I think the selection for minterm and maxterm were sufficient, as we were able to program the board with the equations with no problems. I think we successfully did it with no problems calculating the maxterms and minterms.

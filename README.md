# Introduction

In this lab, we are designing and building a bit-serial logic operation processor with the use of several logic gates, multiplexers, and a counter. The lab consists of two parts. In the first, we designed and built a 4-bit physical circuit. In the second, we extended the design on Vivado using SystemVerilog to an 8-bit processor. The processor has four main units: register, computation, routing, and control. The register unit stores the loaded or computed result of inputs A and B. The computation unit can compute the result of the eight logic operations AND, OR, XOR, 1, NAND, NOR, XNOR, and 0. The result then goes to the routing unit, where you can control if the result should be stored in either A or B, keep A and B the same, or swap A with B. This whole process is controlled through the Finite State Machine (FSM) of the control unit.

*Please check out the project's brief report.*

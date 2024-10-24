java c
Sequential logic elements
1. Circuits with feedback loop
This question pertains to the following circuit:

a.  Complete the table below; the entries in the first row have been provided for you. Hint: Fill in the w and x values first.  Express the next (stable) y and z values in terms of their current values.

b.  To determine that the circuit implements a D latch,  verify each of the following conditions:
1. Specify the input combinations which will force z to become 0.
2. Specify the input combinations which will force z to become 1.
3. Specify the input combinations which will let y hold its value.
4. Specify the input combinations which will let z hold its value.
2. Dual-Latch Flip Flop
Review the two dual-latch flip flop designs below. They both are implemented with gated D latches. (NOTE: WE stands for write enable.)
1. Express next state output Q+ of the first gated D latch (i.e. left latch) as a function of inputs DF, CLOCK, and its current state Q for the circuit, figure (a).
2. Express next state output Q+ of the second gated D latch (i.e. right latch) as a function of inputs Ds, CLOCK, and its current state Q for the circuit, figure (a).
3. Express next state output Q+ of the first gated D latch (i.e. left latch) as a function of inputs DF, CLOCK, and its current state Q for the circuit, figure (b).
4. Express next state output Q+ of the second gated D latch (i.e. right latch) as a function of inputs Ds, CLOCK, and its current state Q for the circuit, figure (b).
5. Compare the behavior. of the two circuits, and explain the major difference in their functionality.

3. Register Operations
1. Draw the timing diagrams for Q0, Q1, Q2, and Q3 for the two circuits below (for the 4 clock cycles shown below). Assume all the Qi outputs are at a low state at the beginning.

2. Complete the design of a 4-bit register (drawn below) that performs the operations listed in the following table.  To complete the register, you need only supply 代 写Sequential logic elementsProlog
代做程序编程语言the MUX inputs.  You may use Qi inputs to the MUXes without drawing the wires from the flip-flop outputs: just write the appropriate Qi labels.
Usage:
· When arithmetic operations are performed, assume that the numbers are in 2's complement representation.
· M2M1M0 denotes function (mode) selection.
· Parallel load inputs should be labeled as Pi.
· Use LSI for a (serial) left shift input.M2M1M0
Operation000
No Change001
Clear (load 0000)010
Arithmetic shift right011
Shift left (use LSI for load input)100
Circular shift left101
logical shift right110
Parallel load (load P3P2P1P0)111
Bitwise complement

4. Analyzing a sequential circuit
Below is an implementation of a sequential circuit with input x and output z.  Your task is to analyze this circuit in order to try to understand what it does.

Derive Boolean expressions for Q1+ (the D1 input to the top flip-flop), Q0+ (the D0 input to the bottom flip-flop) and output Z as a function of the outputs of the flip-flops, and input X.
5. Programming.
Download, compile, and execute the program latch.c Download latch.c.  The program finds and prints all stable states for an R'-S'-latch.  Read the program and examine its output to make sure that you understand how it works.
1. Modify the program to compute stable states for two cross-coupled AND gates.  In other words, replace the two NAND calculations with AND.  Execute the program to find the stable states of such a circuit.  For this part, you may turn in either a printed or a handwritten copy of the output (the list of states).
2. For which combination of inputs  R' and S' does the “latch” that you simulated in part (1) have two stable states?
3. Since the “latch” simulated in part (1) has two stable states, one can use it to store a bit.  Give two reasons that such a design (using two AND gates) is inferior to the R'-S'-latch (using two NAND gates) in CMOS technology.  Explain your answers.



         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com

# QOSFTasks2021
## Task 1 Solution

### Problem - <br>
Design a quantum circuit that considers as input the following vector of integers numbers: [1,5,7,10]
returns a quantum state which is a superposition of indices of the target solution, obtaining in the output the indices of the inputs where two adjacent bits will always have different values. In this case the output should be: 1/sqrt(2) * (|01> + |11>) , as the correct indices are 1 and 3.

### My approach - <br>
<ol>
    <li> Take Input vector of any length 2^n. </li>
    <li> Convert the vector into binary numbers of equal length </li>
    <li> Find all the indices of the binary numbers whose adjacent bits are always different i.e. alternative bits pattern </li>
    <li> Create a statevector of superposition of the indices </li>
    <li> Initialize the circuit with statevector </li>
    <li> Draw the circuit </li>
</ol>

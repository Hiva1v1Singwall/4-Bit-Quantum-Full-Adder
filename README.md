# Quantum Full adder
4-Bit Quantum Full Adder implemented using only C-NOT &amp; Tofolli gates in Python/Qiskit for certain test cases:
The circuit implemented is as follows:  
![](https://upload.wikimedia.org/wikipedia/commons/0/0a/Quantum_Full_Adder.png?20210806154655)
this circuit is a single-bit quantum Full Adder & in my implementation, it is constructed 4 times to augment 4-bit functionality & barriers have been created to separate  & at last measurements of the obtained sum & final carry bit have been taken.  
![](https://hackmd.io/_uploads/SysoIv7Dn.png)  
Some more gate combinations (X[NOT], H[Hadamard] & CX[CNOT]) were also appended before the full adder circuit to initialize the qubit states (A and B) to that of the test cases (some were superimposed, some were pure)

![](https://hackmd.io/_uploads/SyfDb1Xvn.png)  
![](https://hackmd.io/_uploads/SyfDb1Xvn.png)  
![](https://hackmd.io/_uploads/SyfDb1Xvn.png)  
![](https://hackmd.io/_uploads/SyfDb1Xvn.png)  

Measurements were taken, and the probability of output states was measured as well a histogram plot was drawn for the measurements using Quantum Simulator (QASM)

Credits:  
https://www.researchgate.net/publication/346508632/figure/fig1/AS:963729009156096@1606782309965/Circuit-model-of-a-quantum-full-adder.png  
https://qiskit.org/documentation/  
https://www.geeksforgeeks.org/full-adder-in-digital-logic/  

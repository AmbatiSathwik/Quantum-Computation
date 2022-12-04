# Quantum-Computation

## How to run:
1. Download the latest version of python kernel from https://www.python.org/downloads/ .
2. Download the current repositary's zip file and extract the file.
3. Now open the extracted file in either jupyter notebook or any code editor that supports .ipynb files.
4. Now you can use Run All command to run all cells, and you can check output of every cell below them.

## Overall Implementation 
1. Every code file startes with importing all required libraries for the code.
2. Once all imports are sucessfull then we written some required function and input values.
3. After reading the input, implementing the required algorithm is the next step. We referred many online resourses and official page of Qiskit to implement the required circuit.
4. We can check the circuit design using .draw() function. If there is no errors in the circuit we can start executing this circuit both in our local machine simulator and online IBMQ machines.
5. Qiskit has a option to simulate our local computer as a quantum computer to run the designed circuit. In the code you can see the AER simulator, which simulates our computer as quantum computer.
6. Another option is to request for one of the IBMQ machine, which is a quantum computer developed by IBM, for this you need to wait in queue to get assigned a backend.
7. Once we received our backend, we can run our circuit in the quantum computer.
8. You can see the resultant output of the IBMQ machine is not consistent, this can be either quantum noise or quantum decoherence. But most probable output is our required solution.

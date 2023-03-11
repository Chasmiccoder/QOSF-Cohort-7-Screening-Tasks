# QOSF-Cohort-7-Screening-Tasks
Submission for the Screening Tasks

### Setup
```
conda create --name qosf-task python=3.10
conda activate qosf-task

pip install --upgrade pip
pip install qiskit
conda install jupyter  
jupyter notebook
conda install ipykernel
ipython kernel install --user --name=qosf-task
pip install 'qiskit-terra[visualization]'

conda list -e > requirements.txt
```

### Task 4 - Random Circuits
Design a function that generates a random quantum circuit by considering as parameters the number of qubits, the number of depths, and the base of gates to be used. You can only use the quantum gates of 1 and 2 qubits. Bonus: use the described order between qubits of a quantum computer.

Key Feature: Using probability theory to generate useful random circuits. We can choose the probability distribution with which to choose a qubit (or qubits) and to choose gates.

# Job-Shop-Scheduling-IBM
The Job Shop Scheduling Problem is considered one of the most complex problems affecting various sectors of society. Currently, solving this problem in the ideal form mainly involves significant computational power. However, with the emergence of quantum computing, there is a possibility to deal with these challenges that traditional computing faces more efficiently. This study explored the applicability of Quantum Approximate Optimization Algorithm (QAOA) in JSSP using circuit-based quantum computers. To this end, the problem was formulated in terms of binary optimization, adapted for the quantum algorithm, and computational experiments were performed to evaluate the performance of QAOA on JSSP. The goal of the study is to demonstrate the feasibility of this approach on NIQS quantum computers. This project was my implementation created in my Undergraduate thesis, application of JSSP using IBM's Qiskit.

To run the code, simply execute each cell of the JSSP-IBM.ipynb file and change the test instance. The example below was given by:

Jobs = {'job_1': [('machine_2', 2), ('machine_1', 1)],
        'job_2': [('machine_1', 1), ('machine_2', 1)]}

max_time = 4

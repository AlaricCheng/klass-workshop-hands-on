
## Prerequisite

- Linear algebra
- Python

## Preparation

- Install `qiskit` following the steps in (https://docs.quantum.ibm.com/start/install)
- Install Jupyter notebook:
  ```python
  pip install notebook
  ```



## Outline

- Quantum states, quantum gates, parameterized gates
- Quantum circuits
  - Bell state generation
  - teleportation
  - variational quantum circuits 
- Measurement
  - retrieve statistics
  - obtain expectation values
- Application 1: Grover
  - background
  - quantum oracle, circuit
  - demo
- Application 2: QAOA
  - Max Cut
  - framework (analog to neural network)
  - circuit 
  - loss function
  - optimization: gradient descent
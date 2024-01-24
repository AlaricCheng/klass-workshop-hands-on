
## Prerequisite

- Linear algebra
- Python

## Preparation

- Install `qiskit` following the steps in (https://docs.quantum.ibm.com/start/install)
- Install `qiskit-aer`: `pip install qiskit-aer`
- Install Jupyter notebook:
  ```python
  pip install notebook
  ```
- basics.ipynb Colab [link](https://colab.research.google.com/drive/1eyrndDbtiAg3-ycgWnJ0mDxcG8URDRDa?usp=sharing) (need Google account).


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
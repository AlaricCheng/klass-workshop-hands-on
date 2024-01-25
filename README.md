
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


## Notebooks

You would need a Google account to access the following notebooks.

- [basics](https://colab.research.google.com/drive/1eyrndDbtiAg3-ycgWnJ0mDxcG8URDRDa?usp=sharing) 
- [grover](https://colab.research.google.com/drive/1PdyYZCTpik4MSfYlPIJayAnWtnIt_eOI?usp=sharing)
- [qaoa](https://colab.research.google.com/drive/1QKjQ3JTbbZ7CqUv69dxElLMH0hAYv_aF)


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
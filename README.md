# Getting started with the IonQ Backend for Qiskit

> :information_source: **NOTE:** An IonQ API token is required!
>
> Please reach out to [sales@ionq.com](mailto:sales@ionq.com) to request access, or provision access directly via [Google Cloud](https://ionq.com/docs/get-started-with-google-cloud).


## Install dependencies

First, make sure you follow the Qiskit installation steps for your OS first, found [here](https://qiskit.org/documentation/getting_started.html).

Also, make sure your python interpreter / environment has the `qiskit-ionq` provider installed, e.g. using: `pip install qiskit-ionq`.

## Run the samples

| Notebook       | Description      |
| ------------- | ---------- |
| bv/bernstein-vazirani-3q.ipynb | A three-qubit [Bernstein-Vazirani](https://en.wikipedia.org/wiki/Bernstein%E2%80%93Vazirani_algorithm) example |
| bell-cat-states.ipynb | Creates [Bell](https://en.wikipedia.org/wiki/Bell_state) and [Cat](https://en.wikipedia.org/wiki/Cat_state) states |
| deutsch-jozsa.ipynb   | Performs the [Deutsch-Jozsa](https://en.wikipedia.org/wiki/Deutsch%E2%80%93Jozsa_algorithm) algorithm |
| rabi-flopping.ipynb | Simulates [Rabi flopping](https://en.wikipedia.org/wiki/Rabi_cycle) | 
| circuit-training.ipynb | Demonstrates [Data-driven quantum circuit learning](https://advances.sciencemag.org/content/5/10/eaaw9918) | 
| entangling-gates.ipynb | Demonstrates entangling gates | 
| qft-adder.ipynb	| Implements a [QFT adder](https://en.wikipedia.org/wiki/Adder_(electronics)#Quantum_full_adder) | 
| ipea/iterative-phase-estimation-algorithm.ipynb | Demonstrates the quantum [iterative phase estimation algorithm](https://medium.com/quantum-untangled/iterative-quantum-phase-estimation-qpe-algorithms-ced794341487) | 
| vqe/noisy-vqe.ipynb | Demonstrates the impact of noise on the simulation of H2 via a [variational quantum eigensolver](https://en.wikipedia.org/wiki/Quantum_algorithm#Variational_quantum_eigensolver) |


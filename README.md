# IBM's Qiskit Global Summer School 2023:
## Theory to Implementation

### Content of IBM's Qiskit Global Summer School 2023 - Theory to Implementation:

* #### Lab 1: Qiskit 101 ✅
  * In the first lab, we will explore different ways of representing and manipulating quantum states using IBM's Qiskit, based on the quantum theory you learned in the first three lectures. We will cover important IBM's Qiskit classes, including Operator, Statevector, and QuantumCircuit, and learn how to use them to perform deterministic, probabilistic, and unitary operations. Lastly, we'll cover different ways of measuring quantum states using IBM's Qiskit.
  * Check it here: [Jupyter Notebook]() | [HTML]()

* #### Lab 2: Creating Entanglement with Qiskit ✅
  * In this lab, we explore interesting properties of entangled qubits. However, we first will explore the Sampler and Estimator primitives to measure quasi-probability distributions (related to counts) and expectations of an observable, respectively. We then use the Estimator to measure one observable that violates the CHSH inequality, thereby disproving local hidden variable theories. Next, we build a quantum state and teleport it by entangling it with a shared resource, using the Sampler to show that we obtain the same quasi-probabilities by measuring both the prepared state and the teleported state.
  * Check it here: [Jupyter Notebook](https://github.com/rubenandrebarreiro/ibm-qiskit-global-summer-school-2023/blob/main/labs/jupyter-notebooks/lab-2-creating-entanglement-with-qiskit.ipynb) | [HTML](https://github.com/rubenandrebarreiro/ibm-qiskit-global-summer-school-2023/blob/main/labs/htmls/lab-2-creating-entanglement-with-qiskit.html)
    
* #### Lab 3: Diving in Quantum Algorithms ✅
  * In this lab, we will be applying what we've learned so far about quantum algorithms to implement our own version of Quantum Phase Estimation as well as Shor's factoring algorithm. We will explore how increasing the number of qubits used to store the phase estimation changes the accuracy, as well as examine how this algorithm performs on real hardware. Afterward, we will use your implementation of QPE to execute Shor's algorithm to find the prime factors of a small number. Each step will be walked through, and by the end, we will have created a complete generalized function that can be run on the QasmSimulator.
  * Check it here: [Jupyter Notebook](https://github.com/rubenandrebarreiro/ibm-qiskit-global-summer-school-2023/blob/main/labs/jupyter-notebooks/lab-3-diving-in-quantum-algorithms.ipynb) | [HTML](https://github.com/rubenandrebarreiro/ibm-qiskit-global-summer-school-2023/blob/main/labs/htmls/lab-3-diving-in-quantum-algorithms.html)

* #### Lab 4: Iterative Phase Estimation ✅
  * In this lab, you'll implement a simple version of the iterative phase estimation algorithm. Using the recently introduced dynamic circuit capabilities, you'll be able to run the algorithm on an IBM quantum processor.
  * Check it here: [Jupyter Notebook](https://github.com/rubenandrebarreiro/ibm-qiskit-global-summer-school-2023/blob/main/labs/jupyter-notebooks/lab-4-iterative-phase-estimation.ipynb) | [HTML](https://github.com/rubenandrebarreiro/ibm-qiskit-global-summer-school-2023/blob/main/labs/htmls/lab-4-iterative-phase-estimation.html)

* #### Lab 5: Error Mitigation with Qiskit Runtime ✅
  * In this lab, we'll explore a few of the error mitigation options available through IBM's Qiskit Runtime. Specifically, we'll define a simple observable and initial state and use the Estimator primitive to measure the expectation value. Using noisy simulations, we'll explore the effect of different error mitigation strategies.
  * Check it here: [Jupyter Notebook](https://github.com/rubenandrebarreiro/ibm-qiskit-global-summer-school-2023/blob/main/labs/jupyter-notebooks/lab-5-error-mitigation-with-qiskit-runtime.ipynb) | [HTML](https://github.com/rubenandrebarreiro/ibm-qiskit-global-summer-school-2023/blob/main/labs/htmls/lab-5-error-mitigation-with-qiskit-runtime.html)

# Quantum Fourier Transform

The [Quantum Fourier Transform](https://en.wikipedia.org/wiki/Quantum_Fourier_transform) \(QFT\) is sometimes referred to as the workhorse of quantum algorithms, as it is an important part of several of them. The QFT is based upon the [Fourier transform](https://en.wikipedia.org/wiki/Fourier_transform), illustrated by the following animation:

![By Lucas V. Barbosa - Own work, Public Domain, commons.wikimedia.org](https://upload.wikimedia.org/wikipedia/commons/5/50/Fourier_transform_time_and_frequency_domains.gif)

As shown in the previous animation, the Fourier transform decomposes waves \(e.g. sound waves from your favorite song\) into their individual frequencies. The ability of QFT to decompose waves into frequencies is incredibly useful in quantum computing for tasks such as finding the _period_ of a series of numbers; a technique use in Shor's algorithm. For example, a wave that represents the repeating number series from the decimal expansion of $$1/7$$ has a wavelength \(or period\) of 6 \(the digits 1, 4, 2, 8, 5, 7\). In that case, the resultant quantum state after a QFT would have 6 evenly spaced basis states containing high probabilities, with the rest of the basis states having low or 0 probabilities. Remarkably, after setting up the quantum states and gates for $$n$$ qubits, nature's firmware \(quantum mechanics\) remarkably computes the Fourier transform involving $$2^n$$ states.

To get a working understanding of QFTs, experiment with this Quantum Fourier Transform notebook in the Qiskit tutorials:

{% embed url="https://nbviewer.jupyter.org/github/Qiskit/qiskit-tutorial/blob/master/community/terra/qis\_adv/fourier\_transform.ipynb" caption="Quantum Fourier Transform notebook in the Qiskit tutorials" %}


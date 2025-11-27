**Note: This readme is still under construction**

# Supersymmetric Quantum Mechanics with Qiskit
The 0+1 supersymmetric quantum mechanics spontaneous supersymmetry breaking is investigated by calculating the ground state energy of the system (i.e zero preserved, non-zero breaking.), for three different superpontetials:

- Harmonic Oscillator
- Double Well
- Anharmonic Oscillator

The groud state energy is determined using the Variational Quantum Eigensolver [`(VQE)`](https://www.nature.com/articles/ncomms5213) algorithm implemented in [`QISKIT`](https://www.qiskit.org). For a comprehensive introduction to designing a VQE in QISKIT, please visit the IBM [`Variational Algorithm Design`](https://learning.quantum.ibm.com/course/variational-algorithm-design).



Results from quantum simulations, both with and without shot noise, are presented in the [`proceeding`](https://arxiv.org/abs/2411.15083). If you find this work useful, please refer to [How to cite](#How_to_cite).

# Code

** **


# How_to_cite
If you find this code (or parts of it) useful, please cite the proceeding as well as the code:
```bibtex
@article{Mendicelli:2024ryt,
    author = "Mendicelli, Emanuele and Schaich, David",
    title = "{Towards quantum simulation of lower-dimensional supersymmetric lattice models}",
    eprint = "2411.15083",
    archivePrefix = "arXiv",
    primaryClass = "hep-lat",
    month = "11",
    year = "2024"
}
```

# Requirements

The following python packages are installed:

| Package             | Version      |
|---------------------|--------------|
| asttokens           | 2.0.5        |
| certifi             | 2025.1.31    |
| charset-normalizer  | 3.4.1        |
| colorama            | 0.4.6        |
| comm                | 0.2.1        |
| contourpy           | 1.3.1        |
| cycler              | 0.12.1       |
| debugpy             | 1.8.11       |
| decorator           | 5.1.1        |
| dill                | 0.3.9        |
| executing           | 0.8.3        |
| fonttools           | 4.55.8       |
| idna                | 3.10         |
| ipykernel           | 6.29.5       |
| ipython             | 8.30.0       |
| jedi                | 0.19.2       |
| joblib              | 1.4.2        |
| jupyter_client      | 8.6.3        |
| jupyter_core        | 5.7.2        |
| kiwisolver          | 1.4.8        |
| matplotlib          | 3.10.0       |
| matplotlib-inline   | 0.1.6        |
| mpmath              | 1.3.0        |
| nest_asyncio        | 1.6.0        |
| numpy               | 2.2.2        |
| packaging           | 24.2         |
| pandas              | 2.2.3        |
| parso               | 0.8.4        |
| pbr                 | 6.1.1        |
| pillow              | 11.1.0       |
| pip                 | 24.2         |
| platformdirs        | 3.10.0       |
| prompt_toolkit      | 3.0.43       |
| psutil              | 5.9.0        |
| pure-eval           | 0.2.2        |
| Pygments            | 2.15.1       |
| pylatexenc          | 2.10         |
| pyparsing           | 3.2.1        |
| python-dateutil     | 2.9.0.post0  |
| pytz                | 2025.1       |
| pywin32             | 308          |
| pyzmq               | 26.2.0       |
| qiskit              | 1.3.2        |
| qiskit-aer          | 0.16.0       |
| qiskit-algorithms   | 0.3.1        |
| requests            | 2.32.3       |
| rustworkx           | 0.16.0       |
| scikit-learn        | 1.6.1        |
| scipy               | 1.15.1       |
| setuptools          | 75.8.0       |
| six                 | 1.16.0       |
| stack-data          | 0.2.0        |
| stevedore           | 5.4.0        |
| symengine           | 0.13.0       |
| sympy               | 1.13.3       |
| threadpoolctl       | 3.5.0        |
| tornado             | 6.4.2        |
| traitlets           | 5.14.3       |
| typing_extensions   | 4.12.2       |
| tzdata              | 2025.1       |
| urllib3             | 2.3.0        |
| wcwidth             | 0.2.5        |
| wheel               | 0.44.0       |


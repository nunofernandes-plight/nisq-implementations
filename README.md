# NISQ Implementations

A curated list of algorithm implementations on noisy, intermediate-scale quantum (NISQ) computers. Implemented algorithms are ordered chronologically and include architecture (e.g., superconducting), number of qubits, and references.

# Contributions

Please submit pull requests (or email rlarose (at) umich (dot) edu) with algorithm implementations not included below. Any and all corrections are welcome. References to open-access journals or the arXiv are preferred in all cases, if available. Markdown table generators such as https://www.tablesgenerator.com may be useful.

# Chronological ordering

| Year | Month | Algorithm          | Description                                                                                              | Qubit type           | Computer                             | Number of Qubits |                                                                Reference                                                               |
|------|-------|--------------------|----------------------------------------------------------------------------------------------------------|----------------------|--------------------------------------|:----------------:|:--------------------------------------------------------------------------------------------------------------------------------------:|
| 1997 | Aug   | ----               | Implemented gates (XOR, Toffoli), prepared entangled state                                               | NMR                  | ----                                 |        1-3       |                                                 https://arxiv.org/abs/quant-ph/9709001                                                 |
| 1997 | Oct   | ----               | Implemented gates (Rotation, CNOT), prepared entangled state                                             | NMR                  | ----                                 |        1-2       |                                                                                                                                        |
| 1997 | Nov   | Grover             | Executed Grover's algorithm on two qubits.                                                               | NMR                  | ----                                 |         2        |                         [Paper](https://pdfs.semanticscholar.org/6c05/5053f4f1605fdc0bd474c7a350dcd01f627d.pdf)                        |
| 1998 | Jan   | DJ                 | Executed DJ algorithm on NMR quantum computer                                                            | NMR                  | ----                                 |         2        |                                                 https://arxiv.org/abs/quant-ph/9801027                                                 |
| 1998 | Feb   | QEC                | Implemented 3-bit code for phase errors in liquid state NMR                                              | NMR                  |                                      |         3        |                                                 https://arxiv.org/abs/quant-ph/9802018                                                 |
| 1998 | Aug   | DJ                 | Executed DJ algorithm on NMR quantum computer                                                            | NMR                  | ----                                 |         3        |                                                 https://arxiv.org/abs/quant-ph/9808039                                                 |
| 2000 | Mar   | DJ                 | Executed DJ algorithm on NMR quantum computer                                                            | NMR                  | ----                                 |        2-3       |                                    https://journals.aps.org/pra/abstract/10.1103/PhysRevA.61.042306                                    |
| 2000 | Mar   | Entanglement       | Experimental entanglement of four particles                                                              | Trapped ion (9Be+)   | ----                                 |        2-4       |                               [PDF](https://qudev.phys.ethz.ch/content/courses/QSIT08/pdfs/Sackett00.pdf)                              |
| 2000 | Apr   | Benchmark          | Coherent manipulations of seven qubits                                                                   | NMR                  | ----                                 |         7        |          [PDF](https://www.researchgate.net/publication/12569058_An_algorithmic_benchmark_for_quantum_information_processing)          |
| 2000 | June  | DJ                 | Executed DJ algorithm on NMR quantum computer                                                            | NMR                  | ----                                 |        ??        |                                             https://aip.scitation.org/doi/10.1063/1.482015                                             |
| 2000 | June  | DJ                 | Executed DJ algorithm on NMR quantum computer                                                            | NMR                  | ----                                 |         4        |                                    https://journals.aps.org/pra/abstract/10.1103/PhysRevA.62.012310                                    |
| 2000 | July  | Order finding      | Experimental realization of order finding                                                                | NMR                  | ----                                 |         5        |                                                 https://arxiv.org/abs/quant-ph/0007017                                                 |
| 2000 | Dec   | BV                 | Executed BV algorithm on an ensemble quantum computer                                                    | NMR                  | ----                                 |         2        |                                                 https://arxiv.org/abs/quant-ph/0012114                                                 |
| 2001 | June  | QEC                | Experimental demonstration of five qubit code                                                            | NMR                  | ----                                 |         5        |                                    https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.86.5811                                   |
| 2001 | Sep   | BV                 | Executed BV algorithm                                                                                    | NMR                  | ----                                 |         2        |                                                 https://arxiv.org/abs/quant-ph/0012114                                                 |
| 2001 | Dec   | Shor               | Factor 15                                                                                                | NMR                  |                                      |         7        |                                                 https://arxiv.org/abs/quant-ph/0112176                                                 |
| 2003 | Jan   | DJ/BV              | Implement DJ and BV on                                                                                   | Linear optics        | ----                                 |         3        |                         [Paper](https://pdfs.semanticscholar.org/0c3c/e11ac2926ad8974732958d98b10e9a7434ee.pdf)                        |
| 2003 | Feb   | DJ                 | Executed DJ on ion-trap quantum computer                                                                 | Trapped ion (40Ca+)  | ----                                 |         1        | [Paper](https://www.researchgate.net/publication/10964594_Implemention_of_the_Deutsch-Jozsa_algorithm_on_an_ion-trap_quantum_computer) |
| 2004 | Dec   | QEC                | Demonstrates 3 qubit code for spin flip errors                                                           | Trapped ion (9Be+)   | ----                                 |         3        |                     [PDF](https://www.researchgate.net/publication/8149695_Realization_of_quantum_error_correction)                    |
| 2005 | May   | QFT                | Semi-classical QFT                                                                                       | Trapped ion (9Be+)   | ----                                 |         3        |                                           https://science.sciencemag.org/content/308/5724/997                                          |
| 2005 | Sep   | DJ/Grover          | Implemented multiple algorithms on NMR quantum computer                                                  | NMR                  | ----                                 |        ??        |                                                 https://arxiv.org/abs/quant-ph/0509046                                                 |
| 2005 | Oct   | Grover             | Executed Grover's algorithm on two trapped ion qubits                                                    | Trapped ion (111Cd+) |                                      |                  |                                                                                                                                        |
| 2007 | May   | Shor               | Factor 15                                                                                                | Photonic             | ----                                 |         4        |                                                                                                                                        |
| 2007 | Apr   | Shor               | Factor 15                                                                                                | Photonic             | ----                                 |         4        |                          [PDF](https://pdfs.semanticscholar.org/ba6a/9461d97efffca821d681fb9cde4f1d9e9d9e.pdf)                         |
| 2009 | Mar   | DJ/Grover          | Executed Grover and DJ algorithm on superconducting processor                                            | Superconducting      | ----                                 |         2        |                                                     https://arxiv.org/abs/0903.2030                                                    |
| 2009 | Nov   | Shor               | Factor 15                                                                                                | Photonic             | ----                                 |         4        |                                                     https://arxiv.org/abs/0911.1242                                                    |
| 2010 | Feb   | DJ                 | Implemented DJ algorithm with single electronic spin in diamond                                          | NV Center            | ----                                 |         1        |                                                     https://arxiv.org/abs/1002.2465                                                    |
| 2011 | May   | QEC                | Implements multiple QEC codes                                                                            | Trapped ion          | ----                                 | ??               |                                        [Abstract](https://www.ncbi.nlm.nih.gov/pubmed/21617070)                                        |
| 2011 | Sep   | QEC                | Realization of 3 qubit bit (phase) flip code                                                             | Superconducting      | ----                                 |         3        |                                                     https://arxiv.org/abs/1109.4948                                                    |
| 2011 | Nov   | Shor               | Factor 21                                                                                                | Photonic             | ----                                 |         2        |                                                     https://arxiv.org/abs/1111.4147                                                    |
| 2012 | Feb   | Benchmark          | Perform quantum process tomography on universal gate set                                                 | Superconducting      | ----                                 |         2        |                                                     https://arxiv.org/abs/1202.5344                                                    |
| 2013 | Apr   | VQE                | Compute ground state energy of He-H+                                                                     | Photonic             | ----                                 |         2        |                                                     https://arxiv.org/abs/1304.3061                                                    |
| 2014 | Jan   | ----               | Gate implementations and entangled state preparation                                                     | Trapped ion (171Yb+) | ----                                 |         5        |                                                     https://arxiv.org/abs/1401.1575                                                    |
| 2015 | Jan   | Benchmark          | Randomized benchmarking of single qubit gates                                                            | Neutral atom         | ----                                 | 49               | https://arxiv.org/abs/1501.02041                                                                                                       |
| 2015 | Feb   | Sim                | Quantum simulation of Heisenberg and Ising models.                                                       | Superconducting      | ----                                 | 2                | https://arxiv.org/abs/1502.06778                                                                                                       |
| 2015 | Apr   | QEC                | Demonstration of quantum error detection protocol                                                        | Superconducting      | ----                                 |         4        |                                               https://www.nature.com/articles/ncomms7979                                               |
| 2015 | July  | Shor               | Factor 15                                                                                                | Trapped ion (40Ca+)  | ----                                 |         5        |                                                    https://arxiv.org/abs/1507.08852                                                    |
| 2015 | Dec   | VQE/QPE            | Compute energy surface of molecular Hydrogen                                                             | Superconducting      | ----                                 |        2/3       |                                                    https://arxiv.org/abs/1512.06860                                                    |
| 2016 | Mar   | Benchmark          | Executes single and two-qubit gates                                                                      | Trapped ion (9Be+)   | ----                                 | 1-2 (?)          | https://arxiv.org/abs/1604.00032                                                                                                       |
| 2016 | Mar   | DJ/BV/QFT          | Execute DJ, BV, and QFT algorithms                                                                       | Trapped ion (171Yb+) | ----                                 |        3-5       |                                                    https://arxiv.org/abs/1603.04512                                                    |
| 2016 | Mar   | BV                 | Implements BV algorithm                                                                                  | Trapped ion (171Yb+) | ----                                 | 2-3              |                                                    https://arxiv.org/abs/1603.05672                                                    |
| 2016 | May   | Mermin inequalties | Experimental test of Mermin inequalities                                                                 | Superconducting      | IBM Q Experience                     |        1-5       |                                                    https://arxiv.org/abs/1605.04220                                                    |
| 2016 | May   | Multiple           | Executes QEC, arithmetic, etc.                                                                           | Superconducting      | IBM Q Experience                     |        1-5       |                                                    https://arxiv.org/abs/1605.05709                                                    |
| 2016 | Aug   | QEC                | Demonstrates a method to optimize encoding procedure for small error correction code                     | Ion trap (40Ca+)     | ----                                 |         7        |                                                    https://arxiv.org/abs/1603.00402                                                    |
| 2017 | May   | QEC                | Sampling from states prepared with the [[4, 2, 2]] code                                                  | Superconducting      | IBMQX4                               |         5        |                                                    https://arxiv.org/abs/1705.08957                                                    |
| 2017 | May   | QEC                | Demonstrates fault-tolerant state preparation                                                            | Superconducting      |                                      |         5        |                                                    https://arxiv.org/abs/1705.09259                                                    |
| 2017 | June  | Benchmark          | Multiple benchmarking circuits                                                                           | Superconducting      | IBMQX3                               |         5        |                                                    https://arxiv.org/abs/1706.04341                                                    |
| 2017 | Aug   | QEC                | Experimental realization of error correction for Bell and GHZ states                                     | Superconducting      | ??                                   |        5?        |                                                    https://arxiv.org/abs/1708.02297                                                    |
| 2017 | Sep   | QEC                | Repetition code of 15 qubits.                                                                            | Superconducting      | IBMQX3                               |        15        |                                                    https://arxiv.org/abs/1709.00990                                                    |
| 2018 | Jan   | Benchmark          | Demonstrates graph states on 8-16 qubits are fully entangled                                             | Superconducting      | IBMQX5                               | 8-16             |                                                    https://arxiv.org/abs/1801.03782                                                    |
| 2018 | Jan   | VQE                | Computes energy landscapes of deuteron                                                                   | Superconducting      | IBMQX5/Rigetti 19Q-Acorn             | 2-3              |                                                    https://arxiv.org/abs/1801.03897                                                    |
| 2018 | Feb   | VQE/QSE            | Compute ground/excited states of H2                                                                      | Superconducting      | ----                                 |         2        |                            [PRX PDF](https://physics.aps.org/featured-article-pdf/10.1103/PhysRevX.8.011021)                           |
| 2018 | Mar   | S.O.               | Compute state overlap for one-qubit states                                                               | Superconducting      | IBMQX4, Rigetti 19Q-Acorn            |         2        |                                                    https://arxiv.org/abs/1803.04114                                                    |
| 2018 | Apr   | Multiple           | Grover, BV, Shor, HHL, persistent homology, ... (cont. below)                                            | Superconducting      | IBMQX4/5                             |        1-5       |                                                    https://arxiv.org/abs/1804.03719                                                    |
| 2018 | Apr   | Multiple           | Min. spanning tree, QAOA, qPCA, qSVM, Schrodinger's eqn. simulation, state preparation, state tomography | Superconducting      | IBMQX4/5                             |        1-5       |                                                    https://arxiv.org/abs/1804.03719                                                    |
| 2018 | Apr   | SVM                | Classify two-dimensional data                                                                            | Superconducting      | ----                                 |         2        |                                                    https://arxiv.org/abs/1804.11326                                                    |
| 2018 | June  | Benchmark          | Randomized benchmarking                                                                                  | Superconducting      | IBMQX4/5, Rigetti 8Q-Agave/19Q-Acorn |       5-19       |                                                    https://arxiv.org/abs/1806.02736                                                    |
| 2018 | June  | Scrambling         | Application of quantum scrambling in Rydberg atom                                                        | Superconducting      | IBMQX4                               |        5?        |                                                    https://arxiv.org/abs/1806.00781                                                    |
| 2018 | June  | QEC                | Randomized benchmarking on [4, 2, 2] code                                                                | Superconducting      | IBMQX5                               | 4                |                                                    https://arxiv.org/abs/1806.02359                                                    |
| 2018 | July  | QAQC               | Compile quantum algorithms                                                                               | Superconducting      | Rigetti 8Q-Agave, IBMQX1/2           |         2        |                                                    https://arxiv.org/abs/1807.00800                                                    |
| 2018 | July  | QEC                | Quantum error detection for (2n + 1)-qubit entangled states                                              | Superconducting      | IBMQX5                               |        13        |                                                    https://arxiv.org/abs/1807.02883                                                    |
| 2018 | July  | Sim                | Simulates spin-boson model                                                                               | Superconducting      | IBMQX4                               | 5                |                                                    https://arxiv.org/abs/1807.00323                                                    |
| 2018 | Sep   | DJ/BV/QFT          | Implemented DJ, BV, QFT, and Grover on three qubits                                                      | Superconducting      | Trimon                               |         3        |                                                    https://arxiv.org/abs/1809.00668                                                    |
| 2018 | Oct   | VQSD               | Diagonalize a 2x2 matrix                                                                                 | Superconducting      | Rigetti 8Q-Agave                     |         1        |                                                    https://arxiv.org/abs/1810.10506                                                    |
| 2018 | Nov   | Benchmark          | Introduces and computes quantum volume on several computers                                              | Superconducting      | IBMQ                                 | 4-16?            |                                                    https://arxiv.org/abs/1811.12926                                                    |
| 2019 | Jan   | QITE/QLanczos      | Compute ground state energy of TFIM using two novel algorithms                                           | Superconducting      | Rigetti Aspen QPU                    |         2        |                                                    https://arxiv.org/abs/1901.07653                                                    |
| 2019 | Feb   | VQE                | Compute ground state energy of H20                                                                       | Trapped ion (171Yb+) | IonQ                                 |       10-11      |                                                    https://arxiv.org/abs/1902.10171                                                    |
| 2019 | Mar   | BV/HS              | Execute BV and HS algorithms                                                                             | Ion trap (171Yb+)    | ----                                 |        11        |                                                    https://arxiv.org/abs/1905.09294                                                    |
| 2019 | Mar   | Benchmark          | Executes randomized benchmarking with "error-aware" compiling                                            | Superconducting      | IBMQ16                               | 16               |                                                   https://arxiv.org/abs/1903.10963v1                                                   |
| 2019 | May   | ----               | Demonstrates protocol for simultaneous entanglement generation of arbitrary qubit pairs                  | Ion trap (171Yb+)    | IonQ                                 | 11               |                                                    https://arxiv.org/abs/1905.09294                                                    |
| 2019 | June  | Sim.               | Hamiltonian simulation for many-body dynamics                                                            | Superconducting      | IBM 20Q                              |       6-10       |                                                    https://arxiv.org/abs/1906.06343                                                    |
| 2019 | Aug   | ----               | Entanglement generation in two-dimensional neutral atom qubit array; benchmark                           | Neutral atom         | ----                                 | ??               | https://arxiv.org/abs/1908.06103                                                                                                       |
| 2019 | Aug   | ----               | Parallel implementation of multi-qubit gates; benchmark                                                  | Neutral atom         | ----                                 | 10?              | https://arxiv.org/abs/1908.06101                                                                                                       |
| 2019 | Aug   | Sim.               | Simulates SU(2) non-abelian gauge field theory in one dimension                                          | Superconducting      | IBM 20Q                              | 4                | https://arxiv.org/abs/1908.06935                                                                                                       |
| 2019 | Aug   | QML                | Solves small optimization problems                                                                       | Superconducting      | Rigetti Aspen QPU                    | <= 10            | https://arxiv.org/abs/1908.08054                                                                                                       |

## Algorithm keys (Alphabetical)

* BV: Bernstein-Vazirani.
* DJ: Deustch-Jozsa.
* HS: Hidden shift.
* QAQC: Quantum-assisted quantum compiling.
* QFT: Quantum Fourier Transform.
* QPE: Quantum phase estimation.
* QSE: Quantum subspace expansion.
* Sim: (Quantum) simulation.
* S.O.: State overlap.
* VQE: Variational quantum eigensolver.
* VQSD: Variational quantum state diagonalization.


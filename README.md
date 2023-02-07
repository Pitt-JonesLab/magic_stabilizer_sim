# magic_stabilizer_sim

What is stabilizer rank of GATE (e.g. sqiswap) but primarily care about non-CX gates that appear directly in algorithms?

What is robustness of magic of GATE?

Does the current decomp have room for improvement according to the robustness?

---

https://qiskit.org/documentation/tutorials/simulators/6_extended_stabilizer_tutorial.html

#### Paper Dump

- https://www.youtube.com/watch?v=uMGaXEx5p3I
- https://research.ibm.com/publications/simulation-of-quantum-circuits-by-low-rank-stabilizer-decompositions

- https://journals.aps.org/prxquantum/abstract/10.1103/PRXQuantum.2.010345

- https://iopscience.iop.org/article/10.1088/1367-2630/16/1/013009

"Two methods are known for producing [stabilizer] decompositions. The first method relies onconstructing an equivalent circuit to U in which every non-Clifford gate is replaced by a Clifford gate and an ancilla qubit initialized in a magic state. This is the same state-injection gadget from fault-tolerant quantum computing, where non-Clifford gates are applied byconsuming ancilla qubits prepared using some magic state distillation routine [30]. The upshot is that this method allows us to convert compressed stabilizer decompositions of copies of a magic state into stabilizer decompositions of the output state of the circuit. The second method, known as the sum-over-Cliffords method, is more direct, but produces only approximate stabilizer decompositions. It relies on decomposing each nonClifford gate in the circuit as a linear combination of Cliffords and then using randomizedsparsification to find a sparse approximation. Below we give a more detailed descriptionof the two methods." - https://uwspace.uwaterloo.ca/bitstream/handle/10012/16814/Qassim_Hammam.pdf?sequence=3&isAllowed=y

- https://quantum-journal.org/papers/q-2019-09-02-181/

- https://arxiv.org/pdf/1905.06903.pdf

- https://arxiv.org/pdf/1609.07488.pdf

![image](https://user-images.githubusercontent.com/47376937/212824221-aa7b8195-2028-4314-ba86-2a7b38e103e3.png)

- https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.116.250501

"gadgets are useful is that they allow to effectively implement a gate from the k-th level of the Clifford hierarchy using a special resource state and gates from the (k−1)-th level only"

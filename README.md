# Enhancing Bandwidth Incentive Simulation for Swarm: Recreating a Python-based Tool in Go

**GoSwarmSim — a high-performance Go rewrite of a Swarm bandwidth incentive simulation tool**

Bachelor's Thesis · Computer Science · May 2023
Department of Electrical Engineering and Computer Science

**Authors:** Filip B. Gotten, Rasmus Øglænd, and Torjus J. Knudsen
**Grade:** A

---

## 📄 Read the thesis

**[Download / read the full thesis (PDF)](thesis.pdf)**

## 💻 View the code

The simulation tool (GoSwarmSim) is implemented in a separate repository:

**[Swarm-Bachelor/go-incentive-simulation](https://github.com/Swarm-Bachelor/go-incentive-simulation)** — implementation of the Swarm bandwidth incentive simulation written in Go, including build and run instructions.

---

## Abstract

This thesis builds upon an existing Python simulation tool that models the
behavior of bandwidth incentives in Swarm, forming the basis for our research.
Recognizing the potential for improvements, we undertook the challenge of
recreating the existing tool in Go, aiming to enhance its performance and overall
functionality. This thesis details the original design of the Python-based tool,
the subsequent advancements made in our adjusted design, and specific
implementation differences involved when developing the Go-based tool.

The primary focus of our work was to utilize the inherent advantages of Go,
particularly its support for **concurrency**, to achieve enhanced performance in
simulating bandwidth incentives. We also addressed various shortcomings of the
original tool, incorporating implementation enhancements to better simulate Swarm
and improve upon the overall quality and usability of the simulation tool.

In the evaluation phase of our study, we compare the execution times of the
original Python-based simulation tool with the newly developed Go-based tool.
Our findings reveal a significant improvement in performance, with the Go
implementation **outperforming the Python version by a factor of up to 10,000**.

This paper contributes to the field of decentralized storage systems by
highlighting the benefits of employing Go for simulation tasks, especially in
scenarios that demand high performance. Our work provides valuable insights into
the design considerations, implementation choices, and performance gains
associated with recreating a simulation tool in Go for bandwidth incentives in
Swarm.

---

## Key contributions

- **Python-to-Go rewrite** — GoSwarmSim recreates the existing Python-based PySwarmSim tool in Go, improving both design and implementation.
- **Concurrency for performance** — a workers-based approach leveraging Go's concurrency yields execution times up to **10,000× faster** than the Python version.
- **Better Swarm fidelity** — implementation enhancements make the simulation more reflective of Swarm's real behavior.
- **Improved usability** — a separate `config.yaml` for simulation settings and more user-friendly output make the tool easier to use and adapt.
- **Design insights for decentralized storage** — documents design considerations and trade-offs for high-performance simulation of bandwidth incentives.

## Research context

| | |
|---|---|
| **Field** | Computer Science |
| **Topic** | Decentralized storage systems · Swarm · bandwidth incentives |
| **Language** | Go (rewrite of a Python/cadCAD tool) |
| **Department** | Electrical Engineering and Computer Science |
| **Date** | May 2023 |
| **Grade** | A |

---

## Citation

If you reference this work, please cite:

> Gotten, F. B., Øglænd, R., & Knudsen, T. J. (2023). *Enhancing Bandwidth
> Incentive Simulation for Swarm: Recreating a Python-based Tool in Go*
> (Bachelor's thesis, Computer Science). Department of Electrical Engineering
> and Computer Science.

## Contact

- **GitHub:** [@torsaft](https://github.com/torsaft)

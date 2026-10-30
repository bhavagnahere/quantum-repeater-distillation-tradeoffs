# Architectural Trade-Offs in Distributed Quantum Repeaters


This repository contains the simulation code, analytical models, and paper manuscript for:
> **Architectural Trade-Offs in Distributed Quantum Repeaters: Distillation Scheduling Under Memory Coherence Constraints**  
> *Author: Bhavagna Bathula*

---

## 📌 Abstract & Key Findings
Long-distance quantum communication relies on quantum repeaters using entanglement swapping and distillation. This project investigates the architectural trade-off between:
* **Strategy A (Purify-then-Swap):** Distilling elementary links locally before swapping.
* **Strategy B (Swap-then-Purify):** Swapping raw elementary links immediately and distilling end-to-end.

### Core Discoveries:
1. **The Crossover Point ($\tau_{\text{RTT}}/T_2 \approx 0.018$):** When classical signaling takes $>1.8\%$ of memory coherence time, **Strategy B strictly outperforms Strategy A**.
2. **Destructive Local Purification ($\tau_{\text{RTT}}/T_2 \ge 0.070$):** In high-latency regimes, attempting to purify locally yields fidelities worse than raw unpurified swapping.
3. **Minimum QKD Hardware Threshold ($F_{\text{init}} \ge 0.880$):** Elementary links must have raw fidelity $\ge 0.88$ for single-round distillation to support secure Quantum Key Distribution ($F > 0.81$).

---

## 🚀 How to Run the Code
You can run the full simulation directly in your browser with zero installation:
1. Open the `.ipynb` notebook in [Google Colab](https://colab.research.google.com/).
2. Run all cells to reproduce the fidelity sweeps, tipping point annotations, and resource overhead curves.

---

## 📄 Manuscript
The complete 4-page IEEE-format research paper is available in this repository:
* [Download Paper PDF](./Architectural_Trade_Offs_in_Distributed_Quantum_Repeaters__Distillation_Scheduling_Under_Memory_Coherence_Constraints.pdf)

---

## 📚 Citation
```bibtex
@article{bathula2026architectural,
  title={Architectural Trade-Offs in Distributed Quantum Repeaters: Distillation Scheduling Under Memory Coherence Constraints},
  author={Bathula, Bhavagna},
  year={2026},
  publisher={Zenodo},
  doi={10.5281/zenodo.xxxxxxx}
}

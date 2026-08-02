# Adaptive Hybrid Quantum-Classical Optimization Framework for Distributed Order Management

## WISER × Nestlé Quantum Challenge 2026

This repository presents a Hybrid Quantum-Classical Optimization Framework developed for solving the Distributed Order Management (DOM) problem using the WISER × Nestlé challenge dataset.

The proposed framework integrates classical preprocessing, adaptive candidate reduction, Quadratic Unconstrained Binary Optimization (QUBO), the Quantum Approximate Optimization Algorithm (QAOA), and a business repair layer to generate feasible order assignment recommendations under operational constraints.

---

## Project Objectives

- Optimize customer order assignments across multiple distribution centers.
- Minimize shipping costs and fulfillment penalties.
- Maximize business value while satisfying operational constraints.
- Demonstrate the application of hybrid quantum-classical optimization for supply chain management.

---

## Proposed Workflow

1. Data Preprocessing
2. Feasible Candidate Generation
3. Adaptive Priority Score Calculation
4. Candidate Space Reduction
5. QUBO Formulation
6. Exact QUBO Solver
7. QAOA Optimization
8. Business Repair Layer
9. Performance Evaluation

---

## Repository Structure

```
WISER-DOM-Hybrid-Quantum-Optimization/

├── notebooks/
├── figures/
├── report/
├── presentation/
└── results/
```

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Qiskit
- Qiskit Optimization
- SciPy
- Jupyter Notebook

---

## Results Summary

| Metric | Value |
|---------|------:|
| Candidate Reduction | 50.67% |
| Final Business Assignments | 12 |
| Constraint Violations After Repair | 0 |
| Optimization Framework | Hybrid Quantum-Classical |

---

## Repository Contents

### Report
- Technical Report (PDF & DOCX)
- Planner View (PDF & DOCX)

### Presentation
- WISER Presentation

### Notebook
- Complete implementation in Jupyter Notebook

### Figures
- Framework Diagram
- Candidate Space Reduction
- Quantum Business Repair
- Business Constraint Validation
- Distribution Center Allocation

### Results
- Benchmark Table
- Candidate Reduction Statistics
- Business Repair Statistics
- Distribution Center Allocation
- Final Business Assignments
- QAOA Results

---

## How to Run

1. Install the required Python packages listed in `requirements.txt`.
2. Open the Jupyter Notebook in the `notebooks/` folder.
3. Execute the notebook sequentially from top to bottom.
4. Review the generated figures and result files.

---

## Data Privacy

The original WISER × Nestlé challenge dataset is **not included** in this repository due to challenge data privacy requirements. Only aggregated results, figures, and derived outputs are provided.

---

## Future Work

- Evaluate larger Distributed Order Management datasets.
- Execute on larger quantum hardware.
- Explore advanced QAOA parameter tuning.
- Extend to multi-objective supply chain optimization.
- Integrate real-time inventory and demand updates.

---

## Author

**Kadiyam Nava Kasturi Teja**

Department of Computer Science and Engineering (Data Science)

R.V.R. & J.C. College of Engineering

---

## Acknowledgement

This project was developed as part of the **WISER × Nestlé Quantum Challenge 2026**.

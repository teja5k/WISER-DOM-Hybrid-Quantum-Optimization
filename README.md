                 Adaptive Hybrid Quantum–Classical Optimization Framework for Distributed Order Management

This repository presents a hybrid quantum–classical optimization framework developed for the WISER × Nestlé Quantum Challenge 2026. The project addresses the Distributed Order Management (DOM) problem by determining the optimal distribution center for customer order fulfillment while considering inventory availability, throughput capacity, dock capacity, shipping costs, fulfillment value, and penalty costs.

The proposed framework combines classical preprocessing with quantum optimization to improve decision-making. Feasible order-to-distribution-center assignments are generated and ranked using an Adaptive Priority Score. The optimization search space is reduced through an adaptive candidate reduction strategy before formulating the problem as a Quadratic Unconstrained Binary Optimization (QUBO) model. The reduced problem is solved using both an Exact QUBO Solver and the Quantum Approximate Optimization Algorithm (QAOA). A classical Business Repair Layer ensures that the final recommendations satisfy business constraints by removing duplicate assignments and validating solution feasibility.

The implementation demonstrates how hybrid quantum–classical optimization can address complex combinatorial supply chain problems while remaining compatible with current quantum computing capabilities.

Project Highlights:
Hybrid Quantum–Classical Optimization Framework
Distributed Order Management (DOM)
Adaptive Candidate Reduction
Adaptive Priority Score
QUBO Formulation
Exact QUBO Optimization
Quantum Approximate Optimization Algorithm (QAOA)
Business Repair Layer
Benchmark Comparison with Classical Baseline
Scalability Analysis

Key Results:
Metric	Result
Total Feasible Assignments	133,495
Reduced Candidate Assignments	65,857
Candidate Reduction	50.67%
Raw Quantum Assignments	15
Final Business Assignments	12
Constraint Violations After Repair	0

Benchmark Summary:
Method	                             Revenue	    Shipping Cost	              Penalty
Greedy Baseline	                     76,691,433	     32,027,721	                  461.746
Exact QUBO	                         4,744,085	     22,405	                      0.000
QAOA	                             2,490,693	     12,477	                      0.040


Technologies Used:
Python
Pandas
NumPy
Qiskit
QAOA
QUBO
Google Colab
Jupyter Notebook 

Repository Structure:
├── data/                    # Challenge datasets (not publicly shared)
├── notebooks/               # Jupyter notebooks
├── src/                     # Source code
├── figures/                 # Graphs and framework diagrams
├── report/                  # Technical report
├── presentation/            # WISER presentation
├── planner_view/            # Business planner summary
├── README.md
└── requirements.txt
Note on Data Privacy

This repository follows the WISER × Nestlé challenge data privacy guidelines. The original challenge datasets contain anonymized operational information and are not included in this repository. Users should obtain the approved dataset through the official WISER challenge workspace.

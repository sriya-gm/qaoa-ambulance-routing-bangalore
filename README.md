# qaoa-ambulance-routing-bangalore
Implementation of QUBO and QAOA for ambulance routing, with corridor construction and classical comparisons
# qaoa-ambulance-routing-bangalore

Implementation of QUBO and QAOA for ambulance routing, with corridor construction and classical comparisons.  

This repository contains the code and Jupyter notebooks for my research project on applying the **Quantum Approximate Optimization Algorithm (QAOA)** to an ambulance routing problem in Bangalore, India. The project compares quantum solutions to the classical shortest path solver (Dijkstra’s algorithm) on small, congestion-weighted road networks.  


## Contents
- `notebooks/` – Jupyter notebooks for corridor construction, QUBO formulation, and QAOA runs  
- `data/` – sample OSMnx road network extractions (if included)  
- `results/` – plots of classical vs quantum paths  

## Requirements
- Python 3.10  
- Qiskit 0.44.1  
- qiskit-optimization 0.6.0  
- qiskit-algorithms  
- qiskit-aer  
- osmnx, networkx, matplotlib, numpy  

Install everything with:  
```bash
pip install -r requirements.txt
## How to Run
1. Clone the repo:  
   ```bash
   git clone https://github.com/sriya-gm/qaoa-ambulance-routing-bangalore.git
   cd qaoa-ambulance-routing-bangalore
pip install -r requirements.txt

```
Acknowledgements:
This work was carried out as part of the Pioneer Research Program, with guidance from Prof. Brenda Rubenstein. Thanks also to IBM Quantum and the Qiskit community for their open-source tools.

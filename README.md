# oae-supply-chain-model

This repository contains the optimization model and analysis framework developed in the SeaO2-CDR project (2023–2027). The model is implemented in Python using Gurobi and Jupyter Notebooks and is designed to assess supply chain networks for Ocean Alkalinity Enhancement applications. The optimization model has the objective of minimizing the investment and operational costs for a determined supply chain under a given net uptake target. 

> This repository is currently private and under development. The code and data will be made public after the end of the project (planned: mid 2027).

The code, sample data, and documentation will be published after the official end of the project (estimated: June 2027).

If you have questions or are interested in collaboration, please contact:
Mail: lisa.herlicka@bwl.uni-kiel.de
or via GitHub LHerlicka
---

## 🔧 Requirements

- Python ≥ 3.9
- Gurobi ≥ 10.x (academic license required)
- Jupyter Notebook
- Core packages:
  - `gurobipy`
  - `pandas`, `numpy`
  - `matplotlib`, `folium`
  - `openpyxl`, `pickle`

> Gurobi requires a valid academic or commercial license.  
> Students and researchers can obtain a free license at: https://www.gurobi.com/academia/academic-program-and-licenses/


## Repository Structure (Planned)

```bash
OAE-supply-chain/
│
├── notebooks/               # Jupyter Notebooks for modeling and results
├── data/                    # Input data (to be added)
├── figures/                 # Maps and visualizations
├── README.md                # This file
├── LICENSE                  # License information
└── requirements.txt         # (Optional) Python dependencies

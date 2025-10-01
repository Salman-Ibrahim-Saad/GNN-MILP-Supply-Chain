# GNN-MILP Supply Chain Optimization

This repository contains research code and data for integrating **Graph Neural Networks (GNNs)** with **Mixed Integer Linear Programming (MILP)** to solve supply chain optimization problems.  
The project explores demand forecasting, network optimization, and end-to-end decision-making for resilient and efficient supply chains.

---

## 📂 Repository Structure
scg_project/
│
├── GNN_MILP.ipynb # Main Jupyter notebook (GNN + MILP integration)
├── training_and_coverage.png # Visualization of training/coverage
│
├── data/ # Data folder
│ ├── raw/ # Raw input datasets (plants, sales orders, flows, etc.)
│ ├── processed/ # Processed datasets (graph topology, forecasts, etc.)
│ └── figures/ # Figures and CSVs for plots
│
├── LICENSE
├── .gitignore
└── README.md

---

## ⚡ Objectives
- Apply **Graph Neural Networks (GNNs)** for demand forecasting and graph representation of the supply chain.  
- Develop **MILP models** for production, distribution, and routing optimization.  
- Integrate GNN forecasts into MILP formulations for **data-driven decision-making**.  
- Demonstrate use cases such as **EV Routing (EVRP, SDEVRP)** and **Disaster-Resilient Network Design (INDP)**.

---

## 🔧 Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/Salman-Ibrahim-Saad/GNN-MILP-Supply-Chain.git
   cd GNN-MILP-Supply-Chain/scg_project

2. Install required dependencies:
   pip install -r requirements.txt
   (Create a requirements.txt with PyTorch, Pyomo/Gurobi, NetworkX, Pandas, Numpy, Matplotlib, etc.)


**Usage**
Open the Jupyter notebook: jupyter notebook GNN_MILP.ipynb
Run experiments for: Forecasting with GNNs
MILP optimization on supply chain data
GNN + MILP integration workflow

**Results & Visualizations**
  Forecasting performance (accuracy metrics on demand predictions)
  Optimization results (production, inventory, distribution flows)
  Graph visualizations of supply chain networks
  Resilience analysis under disruptions

**License**
This project is licensed under the MIT License – see the LICENSE file for details.

Author
Salman Ibrahim Saad
Lecturer, Industrial & Production Engineering, MIST (Dhaka, Bangladesh)
Research: Operations Research, Machine Learning, Supply Chain Optimization
📧 salman.2000.bd@gmail.com | https://www.linkedin.com/in/salman-ibrahim-saad/

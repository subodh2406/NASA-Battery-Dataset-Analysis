# NASA Battery Dataset Analysis with Plotly

## Project Overview
This project explores the NASA Battery Dataset to analyze how battery parameters, such as **Battery Impedance (Re)** and **Charge Transfer Resistance (Rct)**, evolve over repeated charge and discharge cycles. These parameters provide insights into battery aging and degradation. Interactive plots are created using Plotly to visualize these trends.

---

## Dataset Description
The dataset includes data from lithium-ion batteries tested under various operational conditions, including charge, discharge, and impedance measurements. Experiments were terminated when the batteries reached end-of-life (EOL) criteria.

- **Key Parameters**:
  - **Cycle**: Indicates the charge/discharge cycle number.
  - **Re (Battery Impedance)**: Estimated electrolyte resistance in ohms (Ω).
  - **Rct (Charge Transfer Resistance)**: Estimated charge transfer resistance in ohms (Ω).
  - **Capacity**: Remaining capacity of the battery during each cycle.

### Source
The dataset can be found on Kaggle: [NASA Battery Dataset](https://www.kaggle.com/datasets/patrickfleith/nasa-battery-dataset/data)

---

## Features
- **Interactive Plots**:
  - **Battery Impedance (Re) vs. Cycle**: Visualizes how electrolyte resistance changes with cycles.
  - **Charge Transfer Resistance (Rct) vs. Cycle**: Tracks the progression of charge transfer resistance over cycles.


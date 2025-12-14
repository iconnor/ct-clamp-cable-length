# ct-clamp-cable-length
Simple calculator for determining CT accuracy based on cable resistance

## Resistance vs Error Analysis

This repository includes a Jupyter notebook that visualizes the relationship between cable resistance and measurement error for CT clamps at different power levels (10W to 10kW).

### Installation

Install the required dependencies:

```bash
pip install -r requirements.txt
```

### Running the Notebook

Start Jupyter Notebook:

```bash
jupyter notebook resistance_vs_error.ipynb
```

The notebook will display a plot showing how measurement error varies with power level for different cable resistances (1Ω, 2Ω, and 3Ω extra burden).

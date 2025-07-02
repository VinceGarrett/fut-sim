# Fractal Unification Theory Simulations
This repository hosts open-source simulation models for the Fractal Unification Theory (FUT), validating predictions for redshift, CMB, fifth force, and FTL travel as described in [Fractal Unification Theory, 2025]. 

## Setup
1. Clone the repository: `git clone https://github.com/<your-username>/fut-sim`
2. Install dependencies: `pip install -r requirements.txt`
3. Run example: `python examples/example_redshift.py`

## Citation
Garrett, V. M. (2025). Fractal Unification Theory. *Physical Review Letters* (submitted).
fut-sim/
├── README.md
├── LICENSE
├── src/
│   ├── simulate_deff.py       # Simulates effective dimensionality
│   ├── simulate_rho_psi.py    # Simulates vacuum energy density
│   ├── simulate_ftl.py        # Simulates FTL travel parameters
│   └── utils.py               # Helper functions
├── tests/
│   ├── test_deff.py           # Unit tests for D_eff
│   ├── test_rho_psi.py        # Unit tests for rho_psi
│   └── test_ftl.py            # Unit tests for FTL
├── data/
│   ├── cmb_data.csv           # CMB data for validation
│   └── bao_data.csv           # BAO data for validation
├── docs/
│   ├── getting-started.md     # Setup and usage guide
│   └── api-reference.md       # Code documentation
├── examples/
│   ├── example_redshift.py    # Example script for redshift
│   └── example_ftl.py         # Example script for FTL travel
└── requirements.txt           # Python dependencies

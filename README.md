# BeaversTank
Welcome to beaversTank - Our playground for building cities that stay dry and happy. We’re Marcos, Lena, Yashashvi & Samarth four students from the Masters in AI for Architecture & Built Environment (IAAC, Barcelona), and we’ve teamed up to tackle floods the way real beavers do: with brains and a bit of cheeky engineering.

Inside this repo you’ll find two AI sidekicks working together. One (NSGA optimizer) sketches out smart layouts - think ponds, ridges and green sponge zones - while the other (a reinforcement-learning agent) learns when to open gates or fire up pumps as storms roll in. Grab the notebooks, run the demo, and help us keep the water where it belongs: out of the living room and in the scenery. 🦫

## 📦 Project Structure

```bash
BeaversTank/
├── 01_optimization/            # GEE data fetch, MCDA, NSGA-II patch optimization
├── 02_simulation/              # Mesa-based flood simulation with/without NBS
├── 03_frontend/                # Interactive maps, charts, UI (Leaflet, Streamlit, etc.)
├── 04_data/                    # Input data: DEM, rivers, GEE layers, etc.
├── 05_results/                 # Output patches, plots, and exported analysis
├── 06_reports/                 # Final compiled reports
├── 07_scripts/                 # CLI tools to run pipeline or launch dashboard
├── 08_notebooks/               # Jupyter exploration & testing (if so)
├── config.yaml              # Central config for weights, parameters, paths
├── requirements.txt         # Project dependencies
├── .gitignore               # Files/folders to exclude from Git
└── README.md                # You're here!
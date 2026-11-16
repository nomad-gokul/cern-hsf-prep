# HEP software & fast-ML work

Hands-on projects in high-energy-physics (HEP) software and machine learning for particle physics, built while preparing for CERN-HSF open-source work.

Each folder is a self-contained piece of work with its own README: what it does, how to reproduce it in a few commands, and the results.

## Completed work

*(added as each part is finished)*

## Setup

Developed on Ubuntu 24.04 (WSL2) with a Miniforge conda environment:

```bash
conda create -n hep -c conda-forge python=3.11 root numpy pandas matplotlib scipy jupyterlab -y
conda activate hep
pip install uproot awkward vector hist scikit-hep-testdata
```

Folder-specific requirements are listed in each folder's README.

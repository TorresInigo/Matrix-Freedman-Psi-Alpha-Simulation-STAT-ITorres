# Matrix Freedman ψ<sub>α</sub> Simulations

This repo contains the code used in:
> **Matrix Freedman Inequality for Sub-Weibull Martingales** (Torres, 2025).

## What’s here
- Bandits: OFUL with **Freedman–ψα** vs **K&S (Ber)** radii  
- Covariance: trimmed estimator + radii and coverage

## Reproduce (Colab CPU-only)
1. Open `colab_cpu_sim.py` (or notebook).  
2. Run; the code falls back to NumPy when CUDA isn’t available.

## GPU (optional)
- On Colab: Runtime → Change runtime type → GPU, then `pip install cupy-cuda12x`.

## Exact version for the paper
See the **Releases** tab; use tag **v1.0.0**.

## License
MIT.


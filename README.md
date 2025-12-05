# Ultra-Minimal Predictive Models for Riemann Zeta Zeros

This repository contains code for the paper:
**"Two Independent Ultra-Minimal Predictive Models for the First 10^8 Nontrivial Zeros of the Riemann Zeta Function"**

## Models:
1. **Hybrid 11-zero extrapolation model**
   - Formula: γ̂ₙ = 0.62⋅γₙᵃˢʸ + 0.27⋅γₙᵖᵒˡʸ⁵ + 0.11⋅γₙᵗʳᵉⁿᵈ
   - Calibrated on first 11 zeros only

2. **Stochastic feedback model**
   - φ ≈ 0.8714
   - γₖ = φγₖ₋₁ + δlog(2π(k+10)) + εₖ

## Requirements:
- Python 3.8+
- NumPy
- SciPy

## Usage:
```bash
python hybrid_model.py

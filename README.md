# Geometry-Arithmetic-emergence

Three-layer geometry: sphere, hyperbolic, Euclidean.

## Files

| File | Description |
|---|---|
| `index.html` | Interactive 3D visualization (Three.js) |
| `three_layer_verification.py` | Numerical checks |
| `README.md` | This file |

## The three layers

$$S^2 \xrightarrow{\;R \mapsto iR\;} \mathbb{H}^2 \xrightarrow{\;\text{cusp}\;} E^2\ \text{algebra}$$

| Layer | Geometry | $K$ | $h$ | Role |
|---|---|---|---|---|
| 1 | $S^2$ sphere | $+1/4$ | $0$ | real phase |
| 2 | $\mathbb{H}^2$ hyperboloid | $-1/4$ | $\sqrt{\lvert K \rvert}$ | imaginary phase |
| 3 | $E^2$ Euclidean | $0$ | $0$ | critical phase |

Invariant across the first two: $K_{\mathbb{C}} \cdot \rho^2 = 1$.

Invariant across the last two: spectral–object duality

$$\{t_j\},\ \{\rho\} \;\longleftrightarrow\; \{\ell(\gamma)\},\ \{\log p\}$$

## Quick start

**Visualization.** Open `index.html` in a browser. No build step.

**Numerical checks.**

```bash
pip install mpmath numpy matplotlib
python three_layer_verification.py
```

Output: three consistency checks (Li scaling, $\chi$ decomposition, Pesin entropy) and a figure.

## License

Code: MIT. Text: CC BY 4.0.

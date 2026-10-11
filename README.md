# thesis-learnable-methods
Reproducible code for my PhD thesis chapters on learnable discontinuous Galerkin methods for parametric PDEs (JAX, Scimba).

🚧 **This repository is under construction. The full code will be available soon.**

Code accompanying the last two chapters of my PhD thesis
*Hybrid finite element and neural network methods for parametric PDEs*
(Frédérique Lecourtier, Mimesis, Inria, 2026).

- **Chapter 4**: numerical validations of the differentiable JAX library for DG schemes.
- **Chapter 5**: numerical results using learnable Galerking solver for (parametric) PDEs.

The enriched FEM chapter (**Chapter 3**), built with FEniCS, has its own repository: https://github.com/flecourtier/EnrichedFEMUsingPINNs.

<!--
## Requirements

Results were obtained with Scimba [version / commit hash] and JAX [version].

## Installation

### Docker (recommended)
```sh
docker build -t thesis-learnable .
docker run --rm -it [--gpus all] thesis-learnable
```

### Local
```sh
pip install -r requirements.txt
```

## Repository structure

| Folder | Content | Thesis reference |
|---|---|---|
| `[...]` | [...] | Section [X], Figure [Y] |

## Reproducing the results

```sh
python [script].py [options]
```
Expected runtime and hardware: [...]. Outputs are written to `[...]`.

## Citation

```bibtex
@phdthesis{lecourtier2026thesis,
  author = {Lecourtier, Fr{\'e}d{\'e}rique},
  title  = {Finite Element Methods and Neural Networks for parametric {PDE}s},
  school = {[...]},
  year   = {2026}
}
```
If you use this code, please also cite Scimba: [reference].
-->

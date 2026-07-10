# Observation-Driven Scientific Discovery (ODSD)

## A Variational Framework for Certified Learning from Operando Dynamics

This repository contains the **official companion implementation** of
the paper:

> **Observation-Driven Scientific Discovery (ODSD): A Variational
> Framework for Certified Learning from Operando Dynamics, with
> Electrolyte Design as a First Application**

The repository provides a fully reproducible demonstration of
**Observation-Driven Scientific Discovery (ODSD)**, a framework in which
dynamic operando observations become the primary learning signal for
autonomous scientific discovery.

## Highlights

-   Dynamic operando imaging as the learning signal
-   Physics-residual Gaussian Process surrogate
-   Observation equilibrium through variational learning
-   Scientific uncertainty and κ-certification
-   Decision identifiability and defer-and-image strategy
-   Scientific information gain for experiment selection
-   End-to-end reproducible synthetic operando benchmark

## Repository contents

-   `operando_in_the_loop_demo_v3.ipynb` --- complete executable
    notebook
-   Synthetic phase-field electrodeposition simulator
-   Operando imaging model
-   Physics-informed surrogate learning
-   Certified acquisition strategy
-   Reproducible figures and benchmark results

## Requirements

-   Python 3.10+
-   NumPy
-   SciPy
-   scikit-learn
-   Matplotlib

## Running

``` bash
jupyter notebook operando_in_the_loop_demo_v3.ipynb
```

Run all cells to reproduce every figure and numerical result reported in
the manuscript.

## Citation

If you use this repository, please cite the associated paper.

## License

MIT License (or your preferred license).

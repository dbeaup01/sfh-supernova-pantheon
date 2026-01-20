[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18217479.svg)](https://doi.org/10.5281/zenodo.18217479)

# sfh-supernova-pantheon

Reproducible analysis code for Type Ia supernova time-dilation and luminosity-distance
tests within the Spacetime Flow Hypothesis (SFH).

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dbeaup01/sfh-supernova-pantheon/blob/main/SuperNova_Luminosity_Notebook.ipynb)

## Overview

This repository contains a fully reproducible Jupyter / Google Colab notebook used to
compute Type Ia supernova luminosity distances and time-dilation effects within the
Spacetime Flow Hypothesis.

The analysis reproduces the results presented in the associated Zenodo preprint using
the Pantheon+ SH0ES supernova compilation, without invoking dark energy or metric
expansion.

## Contents

- **SuperNova_Luminosity_Notebook.ipynb**  
  Main reproducible analysis notebook (Google Colab compatible).

## Data Availability & Reproducibility

This repository includes an unmodified copy of the **Pantheon+ SH0ES** Type Ia supernova compilation used in the analysis.

- **Dataset:** Pantheon+ SH0ES  
- **File:** `Pantheon_SH0ES_v1.0.dat`  
- **Number of supernovae:** 1701  
- **Source:** Pantheon+ Collaboration (Brout et al., 2022)  
- **Retrieval date:** 2025-09-06  

The dataset is provided **unchanged** to ensure full reproducibility and eliminate ambiguity regarding preprocessing.  
All calculations, transformations, and modeling steps are performed explicitly in  
`SuperNova_Luminosity_Notebook.ipynb`.

No external data downloads are required to reproduce the results presented in the
associated Zenodo preprint.

## How to run

Click the **Open in Colab** badge above and follow the instructions provided at the top
of the notebook.

The notebook is fully self-contained once the public data files are supplied.

## Related work

- *Supernova Distances Without Dark Energy: A First-Principles Result from Spacetime Flow*  
  (Zenodo, 2026)

## License

MIT License

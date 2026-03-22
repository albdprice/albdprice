<div align="center">

# Alastair J. A. Price

**Computational Chemist & Postdoctoral Fellow** · University of Toronto / Acceleration Consortium

[![Google Scholar](https://img.shields.io/badge/Google_Scholar-720+_citations-4285F4?style=flat-square&logo=google-scholar&logoColor=white)](https://scholar.google.com/citations?user=4zGRuLQAAAAJ)
[![ORCID](https://img.shields.io/badge/ORCID-0000--0003--3239--8319-A6CE39?style=flat-square&logo=orcid&logoColor=white)](https://orcid.org/0000-0003-3239-8319)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Alastair_Price-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alastair-price-6bba6611b/)
[![Website](https://img.shields.io/badge/Website-albdprice.github.io-222222?style=flat-square&logo=github-pages&logoColor=white)](https://albdprice.github.io)
[![CV](https://img.shields.io/badge/CV-Download_PDF-red?style=flat-square&logo=adobe-acrobat-reader&logoColor=white)](https://github.com/albdprice/cv)

[![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)](#)
[![Fortran](https://img.shields.io/badge/-Fortran-734F96?style=flat-square&logo=fortran&logoColor=white)](#)
[![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)](#)
[![LaTeX](https://img.shields.io/badge/-LaTeX-008080?style=flat-square&logo=latex&logoColor=white)](#)
[![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)](#)
[![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)](#)

</div>

---

### About

I am a computational chemist who develops and applies quantum mechanical methods for molecular science. My work spans density functional theory, dispersion interactions, and machine learning for molecular property prediction. Named developer for [FHI-aims](https://fhi-aims.org/). Currently working with Prof. O. Anatole von Lilienfeld at the University of Toronto.

**720+ citations** · **h-index 14** · **18 publications** · **10 invited talks** · **$10M+ grant funding**

### Research

My research is rooted in the fundamental physics of molecular interactions and building better computational tools for chemistry.

**Dispersion & Density Functional Theory** — I develop and implement methods for accurately treating London dispersion interactions in DFT. This includes the exchange-hole dipole moment ([XDM](https://github.com/albdprice/psi4_xdm)) model in [Psi4](https://psicode.org/), adaptive hybrid functionals ([aPBE0](https://www.science.org/doi/10.1126/sciadv.adt7769)), non-local adiabatic connection methods (nLanE), and double-hybrid functionals (DH24) in [FHI-aims](https://fhi-aims.org/). I am currently generating training data for a machine-learned version of XDM dispersion following [Tu et al.](https://doi.org/10.1039/d2dd00150k).

**Machine Learning Interatomic Potentials** — I develop [physics-constrained approaches](https://github.com/albdprice/adaptive-ml-potentials) to learning interatomic potentials, where the model learns universal scaling parameters for known functional forms rather than fitting the potential surface directly. I also fine-tune [MACE](https://github.com/ACEsuit/mace) neural network potentials for targeted chemical domains, including a pipeline for 1,445 pesticide molecules trained on wB97M-D3BJ/def2-TZVPPD data.

### Selected Publications

> D. Khan, **A. J. A. Price**, M. L. Ach, O. A. von Lilienfeld. *Adaptive hybrid density functionals.* **Science Advances** 2025, 11(5), eadt7769.

> **A. J. A. Price**, A. Otero de la Roza, E. R. Johnson. *XDM-corrected hybrid DFT with numerical atomic orbitals predicts molecular crystal energetics with unprecedented accuracy.* **Chem. Sci.** 2023, 14, 1252.

> **A. J. A. Price**, K. R. Bryenton, E. R. Johnson. *Requirements for an accurate dispersion-corrected density functional.* **J. Chem. Phys.** 2021, 154, 230902. (**Top 10% Altmetric**)

> M. DeJong, **A. J. A. Price** et al. *Small molecule binding to surface-supported single-site transition-metal reaction centres.* **Nat. Commun.** 2022, 13, 1-10.

[Full publication list →](https://albdprice.github.io)

### Active Projects

| Repository | Description |
|:---|:---|
| [`psi4_xdm`](https://github.com/albdprice/psi4_xdm) | XDM dispersion + aPBE0 + nLanE adaptive DFT in Psi4 (C++/Python) |
| [`adaptive-ml-potentials`](https://github.com/albdprice/adaptive-ml-potentials) | Physics-constrained parameter learning for interatomic potentials ([Price & von Lilienfeld, 2026](https://github.com/albdprice/adaptive-ml-potentials)) |
| [`molecular-ml-pipeline`](https://github.com/albdprice/molecular-ml-pipeline) | MACE fine-tuning pipeline: 28K pesticide structures, MLflow tracking, GPU training |
| [`agentic-ai-demos`](https://github.com/albdprice/agentic-ai-demos) | Agentic AI for drug discovery: LangGraph agents, molecular RAG, PubChem integration |
| [`teaching`](https://github.com/albdprice/teaching) | DFT lectures for CHM328 at UofT (Beamer slides + companion notes) |
| [`cv`](https://github.com/albdprice/cv) | Academic CV with GitHub Actions auto-build |

### Teaching

| Course | Role | Institution |
|:---|:---|:---|
| [CHM328: Modern Physical Chemistry](https://github.com/albdprice/teaching) | Guest Lecturer (DFT & Computational Chemistry) | University of Toronto, Winter 2026 |

### Tools & Expertise

| Domain | |
|:---|:---|
| **Quantum Chemistry** | Psi4 (developer), FHI-aims (named developer), Gaussian, critic2, postg, ASE |
| **Theory** | DFT, XDM dispersion, CCSD(T), adiabatic connection, double hybrids, perturbation theory |
| **Machine Learning** | PyTorch, MACE, scikit-learn, KRR, cMBDF molecular descriptors |
| **Scientific Computing** | Fortran, C++, Python, MPI/OpenMP, SLURM, Alliance Canada HPC, Globus |
| **Infrastructure** | Proxmox, Docker, Ansible, Tailscale, Prometheus/Grafana, ZFS, MLflow |

### Recent Highlights

- **2026** — ML-XDM dispersion model: large-scale DFT data generation for machine-learned dispersion corrections
- **2026** — Collaborator on **$10M NRF Singapore-UofT grant** for ML design of complex materials
- **2025** — Invited seminars at **Seoul National University**, **Fritz-Haber-Institut (Max Planck)**, **University of Cambridge**, **National University of Singapore**
- **2025** — *Science Advances* publication on adaptive hybrid density functionals
- **2022** — Best graduate student poster, Canadian Symposium on Theoretical & Computational Chemistry

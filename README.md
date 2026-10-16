# Ali Aouf

Machine learning engineer and researcher in generative AI. PhD at UCLouvain, carried out at SCK CEN, Belgium's nuclear research centre. Based in Mol, Belgium.

[aliaouf.com](https://aliaouf.com) · [LinkedIn](https://www.linkedin.com/in/40uf411) · [Google Scholar](https://scholar.google.com/citations?user=eYEOHRAAAAAJ&hl=en) · ali.aouf.ab@gmail.com

[![StandWithPalestine](https://raw.githubusercontent.com/Safouene1/support-palestine-banner/master/StandWithPalestine.svg)](https://techforpalestine.org/learn-more)

I build generative models for scientific data, and the software around them. My PhD work synthesises 3D material microstructures from 2D images with diffusion, flow-matching and adversarial methods, and checks the results with physics simulation. Before the PhD I built SmartWells, an operations platform used at drilling rigs, ran it in production and led its team.

Open to machine learning engineer and research engineer roles in Belgium.

## Selected repositories

**[ControlledSliceFlow](https://github.com/40uf411/ControlledSliceFlow)**: flow matching for 3D microstructures learned from 2D images only. A 3D generator is trained through a 2D slice discriminator; a decomposed noise prior gives diversity across volumes and control over porosity; two-stage reflow reaches reference quality in 8 sampling steps; guided inpainting extends volumes beyond the training size.

**[DimExDAM](https://github.com/40uf411/DimExDAM)**: diffusion with an adversarial loss. A 3D U-Net generator learns a volume distribution from 2D slices, with no 3D ground truth.

**[credit-review](https://github.com/40uf411/credit-review)**: checks a mortgage file against a bank's credit policy. An LLM reads the documents, every rule runs as deterministic code with its evidence, and the policy is a validated YAML file the bank owns. Hosted or fully local models, a Streamlit review page, 81 offline tests.

**[condebase-infra](https://github.com/40uf411/condebase-infra)**: production-style authentication platform. Keycloak (OAuth 2.0 with PKCE), a FastAPI backend-for-frontend with server-side sessions, a React app behind Caddy, Redis for sessions, rate limits and job queues, PostgreSQL with activity logs, and runbooks for deploy, rollback, restore and incidents.

**[autocode](https://github.com/40uf411/autocode)**: FastAPI template in clean architecture. Users, roles and privileges checked per endpoint, JWT with a blocklist, PostgreSQL and SQLite adapters, caching, tests and Docker.

**[microstructure_toolkit](https://github.com/40uf411/microstructure_toolkit)**: config-driven 2D and 3D microstructure analysis. Segmentation, filter pipelines and descriptors (two-point correlation, chord length, lineal path, pore-size distribution, Minkowski measures), with CSV and VTK output and tests.

## Selected publications

- Aouf A, Laloy E, Rogiers B, De Vleeschouwer C. [Reconstruction of 3D multiphase microstructures using denoising diffusion models](https://link.springer.com/article/10.1007/s10596-026-10437-2). *Computational Geosciences*, 2026.
- Aouf A, Laloy E, Rogiers B, De Vleeschouwer C. 3D clay microstructure synthesis using denoising diffusion probabilistic models. *Applied Computing and Geosciences*, 2025.
- Amara K, Aouf A, et al. COVIR: O-Net for COVID-19 CT-scan lung lesion segmentation. *Computers & Graphics*, 2022. Code: [O-Net](https://github.com/40uf411/O-Net-Medical-Images-Segmentation).

Full list on [Google Scholar](https://scholar.google.com/citations?user=eYEOHRAAAAAJ&hl=en).

## Tools I work with

- **Generative models and LLMs:** PyTorch, Hugging Face, diffusion, flow matching, GANs, vLLM, structured extraction, RAG
- **Backend and data:** Python, FastAPI, PostgreSQL, Redis, Docker, React
- **Practice:** Git and code review, GitHub Actions, pytest, Slurm GPU clusters, Weights & Biases

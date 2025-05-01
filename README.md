Protein Generative ML Design

This repository explores machine learning and deep learning methods for generative protein design, with a focus on immunoglobulin-like scaffolds (e.g., antibodies, NANOBODIES®). It is inspired by recent advancements in self-supervised learning, large language models (LLMs), and diffusion models applied to protein structures.

Project Goals
- Develop and benchmark machine learning models for de novo protein design.
- Apply and fine-tune foundation models for protein structure generation and optimization.
- Integrate docking and structure prediction workflows (e.g., LightDock, HADDOCK, Rosetta).
- Curate and preprocess large biological datasets for model training and evaluation.

Key Tools and Libraries
- Python (NumPy, pandas, PyTorch, JAX)
- RFdiffusion, proteinMPNN, Rosetta, pyRosetta
- BioPython, BioPandas
- Scikit-learn, Hugging Face Transformers
- LightDock, HADDOCK

Custom data engineering pipelines for large protein datasets

Repository Structure
protein_generativeML_design/
├── data/                 # Datasets (curated biological data, PDB files, etc.)
├── notebooks/            # Jupyter notebooks for experiments and workflows
├── src/                  # Source code (modeling, training scripts, utilities)
├── results/              # Output of experiments (predictions, designed sequences)
├── README.md             # Project overview
├── requirements.txt      # Python environment requirements
└── LICENSE               # License for reuse (optional)

Example Workflows
- Protein Structure Preprocessing
- Self-Supervised Pretraining on Protein Sequences
- Training Diffusion Models on 3D Protein Coordinates
- Fine-Tuning Protein Language Models for Scaffold Design
- Docking Designed Proteins to Target Antigens

Future Directions
- Implement flow matching methods for protein generation.
- Benchmark custom-designed antibodies/NANOBODIES® against experimental datasets.
- Explore multimodal models (sequence + structure).

Disclaimer
All datasets used in this repository are publicly available or simulated. No confidential or proprietary data is included.

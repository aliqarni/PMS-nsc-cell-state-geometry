# Geometric Organization of Neural Stem Cell States in Progressive Multiple Sclerosis

## Overview

This repository contains a geometry-based analysis of single-cell RNA-sequencing (scRNA-seq) data from neural stem cells (NSCs) in progressive multiple sclerosis (PMS).

Rather than focusing on clustering or marker genes alone, the analysis examines how disease and treatment reshape the geometry of cell-state space using representation learning and cell–cell distance structure.

A central goal of this project is to assess whether observed biological conclusions are *robust across different representation learning methods*, or whether they depend on a specific embedding choice.

---

## Data

- System: Neural stem cells (NSCs)
- Disease context: Progressive Multiple Sclerosis (PMS)
- Conditions:
  - DMSO (disease / untreated)
  - ABT (treatment)
- Source: Public scRNA-seq data from NCBI GEO  
  - Accession: GSE297365

---

## Methods

- Gene filtering and alignment across conditions
- Shared highly variable gene (HVG) selection
- Representation learning approaches:
  - Principal Component Analysis (PCA)
  - Autoencoder-based latent representations
  - scVI (single-cell Variational Inference)
- Euclidean distance–based Representational Dissimilarity Matrices (RDMs)
- Geometry metrics:
  - Local compactness
  - Global dispersion
  - Cell–cell distance distributions

---

## Key Findings

- Disease is associated with *uneven and extreme distortion* of neural stem cell state space.
- Treatment induces *global compression* of cell-state geometry and reduces pathological extremes.
- Across multiple representation learning methods, *no evidence is observed for the emergence of new discrete cell states*, suggesting that treatment reshapes existing geometry rather than creating novel states.

---

## Repository Contents

- 01_raw_loading_and_QC.ipynb  
  Data loading, quality control, and preprocessing

- PMS_NSC_cell_state_geometry.ipynb  
  Geometry analysis using PCA-based representations

- cell_state_geometry_across_representations.ipynb  
  Comparative geometry analysis across PCA, autoencoder, and scVI embeddings

---

## Status

This repository represents an ongoing computational research project intended for:

- transparent analysis
- preprint preparation
- discussion with collaborators or prospective supervisors

Further extensions may include additional datasets or alternative representation learning frameworks.

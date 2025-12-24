# Geometric Organization of Neural Stem Cell States in Progressive Multiple Sclerosis

## Overview

This repository contains a geometry-based analysis of single-cell RNA-sequencing (scRNA-seq) data from neural stem cells (NSCs) in progressive multiple sclerosis (PMS).

Rather than focusing on clustering or marker genes alone, the analysis examines how disease and treatment reshape the geometry of cell-state space using representation learning and cell–cell distance structure.

---

## Data

- System: Neural stem cells
- Disease context: Progressive Multiple Sclerosis (PMS)
- Conditions:
  - DMSO (disease / untreated)
  - ABT (treatment)
- Source: Public scRNA-seq data from NCBI GEO (accession: *GSE297365*)

---

## Methods

- Gene filtering and alignment across conditions
- Shared highly variable gene selection
- PCA-based representation learning
- Euclidean distance–based Representational Dissimilarity Matrices (RDMs)
- Geometry metrics:
  - Local compactness
  - Global dispersion
  - Distance distributions

---

## Key Finding

Disease is associated with extreme and uneven distortion of neural stem cell state space, while treatment induces global compression and reduces pathological extremes without introducing new discrete cell states.

---

## Contents

- PMS_NSC_Geometry_RDM_PCA.ipynb — main analysis notebook

---

## Status

This is an ongoing research analysis intended for transparency, preprint preparation, and discussion with collaborators or supervisors.

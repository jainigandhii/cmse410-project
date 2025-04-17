# CMSE410 Final Project: Machine Learning in Neuronal Modeling: A Comparative Analysis and Implementation

This repository contains the complete pipeline for my CMSE410 final project at Michigan State University. The goal of this project was to explore and model the relationship between electrophysiological stimuli and neuronal spike responses using human neuron data from the Allen Brain Atlas.

---

## Project Overview

The project was divided into several key components:
- **Data Acquisition & Cleaning** (`background.ipynb`, `data_prep.ipynb`)
- **Feature Engineering** (`preprocessing.ipynb`)
- **ANN Modeling** (`ann.ipynb`)
- **CNN Modeling** (attempted but not used; `cnn.ipynb`)
- **Final Report** (`report.docx`)

---

## Files

| File | Description |
|------|-------------|
| `background.ipynb` | Exploratory analysis of the neuron dataset and source overview |
| `data_prep.ipynb` | Processes all human neuron sweep files and extracts biologically relevant features |
| `preprocessing.ipynb` | Cleans the dataset, handles missing values, and performs basic transformations |
| `ann.ipynb` | Implements and evaluates an artificial neural network to predict spike counts |
| `cnn.ipynb` | Prototype of CNN-based model (not used in final analysis due to size and performance) |
| `cnn_input.npy`, `cnn_target.npy`, `cnn_metadata.csv` | Intermediate data files (DO NOT TRACK on GitHub) |
| `report.docx` | Final report for the project, including figures, citations, and narrative |
| `project_report.ipynb` | Optional Jupyter version of the report for reproducibility |
| `.gitattributes`, `.gitignore` | Git configuration files for proper repo handling and LFS exclusions |

---

## Key Insights

- ANN models showed poor generalization on spike count prediction due to high variability and signal sparsity.
- CNN architectures were attempted but not included due to excessive training time and data imbalance.
- Biological feature engineering was essential to create meaningful predictors.

---

## Code & Reproducibility

To run this project locally:

```bash
git clone https://github.com/jainigandhii/cmse410-project.git
cd cmse410-project
# Open notebooks in Jupyter Lab or VSCode

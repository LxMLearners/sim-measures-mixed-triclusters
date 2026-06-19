# Similarity Measures for Comparing Mixed-Type Triclusters

This repository contains the official code, experiments, and visualizations for the paper: **"Similarity Measures for Comparing Mixed-Type Triclusters"**.

## Overview
This repository provides an evaluation framework for symmetric similarity measures (Horizontal, Vertical, and Combined) applied to 3D temporal patterns. The provided Jupyter Notebook allows users to reproduce the sanity checks, sensitivity tests, and computational profiling, comparing the proposed metrics against baseline approaches (Virtual Pattern and Hyper-box).

## Repository Structure
* `Experiments.ipynb`: The main notebook containing the full codebase for the 9 sanity check scenarios, Noise Sensitivity Tests, Mixed-Type Composition tests, structural overlap tests, and runtime scalability profiling.
* `visualize_patterns.py`: Auxiliary helper functions required for virtual pattern representation.
* `heterogeneity_test/`: Output directory containing visual results and tables for the variable heterogeneity sensitivity experiments.
* `noise_sensitivity_test/`: Output directory containing visual results for the data corruption/noise tests.
* `scalability_test/`: Output directory containing the execution time scaling profile grids.
* `output_tricluster_tables_compact/`: Output directory containing the highly optimized vector/raster graphical representations of the tested triclusters.
*(Note: The Structural Overlap Sensitivity test outputs its analysis directly within the notebook execution).*

## How to Run
1. Clone this repository:
   ```sh
   git clone [https://github.com/LxMLearners/sim-measures-mixed-triclusters.git](https://github.com/LxMLearners/sim-measures-mixed-triclusters.git)
    ```
2. Install the required dependencies:
   ```py
    pip install -r requirements.txt
   ```
3. Open Experiments.ipynb using Jupyter Notebook or JupyterLab to run the cells and interact with the data.

## Citation
If you use this code or the similarity measures in your research, please cite our paper:
   ```sh
   @article{similarity_triclusters_2026,
     title={Similarity Measures for Comparing Mixed-Type Triclusters},
     author={[Your Name and Co-authors]},
     journal={[Journal/Conference Name]},
     year={2026}
   }
   ```

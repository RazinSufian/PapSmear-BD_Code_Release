# PapSmear-BD classification benchmark

This repository contains the executed reference benchmark for PapSmear-BD v1. The notebook
evaluates the primary three-class task and the five-class Bethesda task using a majority-class
reference, HOG–RBF-SVM, ResNet18 and Swin-T.

The dataset is distributed separately through Zenodo
(`https://doi.org/10.5281/zenodo.23017652`). Place the extracted
`PapSmear-BD_Zenodo_v1.0.0` directory beside this repository. It must contain
`metadata.csv` and the `images/` hierarchy referenced by its `relative_path` column.

Open `01_PapSmear_BD_Classification_Benchmark.ipynb` to inspect the code and recorded outputs or
to reproduce the benchmark.

Code is released under the MIT License.

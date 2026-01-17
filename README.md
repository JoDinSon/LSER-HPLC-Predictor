# LSER-HPLC-Predictor

This project is a reproduction of research into **Linear Solvation Energy Relationships (LSER)** by Marchetto *et al.* (2025). The goal is to predict how chemicals behave in an HPLC column based purely on their molecular structure.

By using the **Abraham Solvation Parameter Model**, this tool estimates molecular descriptors (*E,S,A,B,V*) and translates them into real-world retention times for chromatography.
## 🧪 Project Goals

+ **Reproduce Research:** Rebuild the machine learning architecture described in the original paper using open-source tools.

+ **Open Source Stack:** Using RDKit for molecular processing and Scikit-learn for the predictive modeling.

+ **Validation:** Testing the model against real-world lab data (e.g., Caffeine method validation from Pharmacognosy Research).

## 🏗️ Status: Under Construction

This repository is currently a work in progress. I am currently:

+ Cleaning and refactoring code.

+ Validating the predicted retention times.

## 🚀 How it Works 

The software takes a **SMILES** string, runs it through a trained pipeline, and outputs a predicted Retention Time (tR​).

## References

This project reproduces the machine learning workflow for HPLC method development as described in:
> **Marchetto, A., et al.** (2025). *Analytical Chemistry*, 97(13). 
> DOI: [10.1021/acs.analchem.4c03466](https://doi.org/10.1021/acs.analchem.4c03466)

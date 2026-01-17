# LSER-HPLC-Predictor

This project is a reproduction of research into **Linear Solvation Energy Relationships (LSER)**. The goal is to predict how chemicals behave in an HPLC column based purely on their molecular structure.

By using the **Abraham Solvation Parameter Model**, this tool estimates molecular descriptors (*E,S,A,B,V*) and translates them into real-world retention times for chromatography.
## 🧪 Project Goals

+ **Reproduce Research:** Rebuild the machine learning architecture described in the original paper using open-source tools.

+ **Open Source Stack:** Using RDKit for molecular processing and Scikit-learn for the predictive modeling.

+ **Validation:** Testing the model against real-world lab data (e.g., Caffeine method validation from Pharmacognosy Research).

## 🏗️ Status: Under Construction

This repository is currently a work in progress. I am currently:

+ Cleaning and refactoring code.

+ Validating the predicted retention times.

## 🚀 How it Works (Quick View)

The software takes a **SMILES** string, runs it through a trained pipeline, and outputs a predicted Retention Time (tR​).
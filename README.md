# 3D_Pharmacophore-Caffeine
Python project for generating 3D pharmacophore features of caffeine using RDKit.

This project uses **RDKit** to generate 3D pharmacophore features of Caffeine.

## Files
- `Caffeine_Pharmacophore.ipynb` – Colab notebook with code and explanations
- `pharmacophore.json` – JSON file containing extracted pharmacophore features

## Steps
1. Load molecule (.sdf)
2. Generate 3D conformers
3. Energy minimization (MMFF + UFF)
4. Extract pharmacophore features
5. Compute feature coordinates
6. Build consensus pharmacophore
7. Export to JSON

# Protein Structure Validation

## Objective

This project aims to learn structural bioinformatics by analyzing experimentally determined protein structures from the Protein Data Bank (PDB).

## Protein Used

| Property | Details |
|----------|----------|
| Protein | Human Insulin |
| Initial PDB ID | 4EYD |
| Structure Source | Protein Data Bank (PDB) |
| Experimental Method | X-ray Crystallography |
| Organism | Homo sapiens |
| Resolution | (Add from PDB page) |

During structural validation, the original PDB structure (4EYD) was processed using MolProbity. Hydrogen atoms were added and structural optimization was performed, generating the corrected structure (4EYDH). All subsequent analyses were carried out using the optimized structure.

## Workflow

This project follows a complete structural bioinformatics workflow beginning with retrieval of an experimentally determined protein structure and ending with structural visualization and electrostatic surface analysis.

Workflow:

Protein Data Bank
        ↓
Download Human Insulin (4EYD)
        ↓
MolProbity Validation
        ↓
Generate Corrected Structure (4EYDH)
        ↓
Quality Assessment
        ↓
Structural Visualization (PyMOL)
        ↓
Hydrogen Bond Analysis
        ↓
Salt Bridge Analysis
        ↓
Hydrophobic Residue Mapping
        ↓
Electrostatic Surface Analysis (ChimeraX)

## Skills

- Structural Biology
- Structural Bioinformatics
- Protein Data Bank (PDB)
- Protein Validation
- GitHub Documentation

## Software Used

| Software | Purpose |
|-----------|----------|
| Protein Data Bank (PDB) | Download experimental structure |
| MolProbity | Structural validation and hydrogen optimization |
| PyMOL | Molecular visualization and interaction analysis |
| UCSF ChimeraX | Electrostatic surface visualization |
| GitHub | Documentation and portfolio |

## Structural Analysis

The following analyses have been completed.

- Protein structure validation
- MolProbity quality assessment
- Clashscore evaluation
- Ramachandran plot assessment
- Rotamer validation
- Addition of hydrogen atoms
- Hydrogen bond visualization
- Salt bridge identification
- Hydrophobic residue mapping
- Electrostatic surface potential visualization

## Workflow Summary

### Step 1
Retrieve experimental protein structure from the Protein Data Bank.

### Step 2
Inspect protein metadata.

### Step 3
Validate the structure using MolProbity.

### Step 4
Interpret validation statistics.

### Step 5
Download the corrected MolProbity structure (4EYDH).

### Step 6
Visualize the optimized protein in PyMOL.

### Step 7
Generate molecular representations.

### Step 8
Analyze structural interactions:

- Hydrogen bonds
- Salt bridges
- Hydrophobic residues

### Step 9
Calculate electrostatic surface potential using UCSF ChimeraX.

(Current stage)


## Repository Structure

data/
results/
figures/
notes/
references/

## Status

🟡 In Progress

Started: July 2026

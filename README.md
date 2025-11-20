# PROTEIN-STRUCTURE-SWISS-MODELLING-2ZNS-Structure-of-ligand-binding-core-of-human-glutamate-receptor
PROTEIN-STRUCTURE-MODELLING [SWISS MODELLING] = 2ZNS = Crystal structure of the ligand-binding core of the human ionotropic glutamate receptor, GluR5, in complex with glutamate 
# Homology Modeling: Human Glutamate Receptor (GRIK1) Ligand Binding Core 🧬💻

## Overview

This repository contains the results of a **Homology Modeling** project performed using the **SWISS-MODEL Server**. The goal was to generate a high-quality 3D structural model of the ligand-binding core of the **Human Glutamate receptor, ionotropic kainate 1 (GRIK1)**, specifically based on the sequence identified by the tag `>2ZNS_1|Chain A...mutated.fasta`.

The prediction successfully generated a model, identified highly similar templates (like PDB ID **4mf3**), and provided comprehensive quality assessment reports.

---

## Target System and Methodology

* **Target Protein:** Glutamate receptor, ionotropic kainate 1 (GRIK1), *Homo sapiens* (9606), mutated sequence.
* **Target Domain:** Ligand Binding Domain (LBD) core.
* **Modeling Tool:** SWISS-MODEL Server.
* **Key Template Used:** The top template, **4mf3.1.A**, shows an exceptional sequence identity of **99.61%**, ensuring high confidence in the predicted structure.
* **Predicted Oligo-State:** Homo-dimer.

---

## Quality Assessment Summary

The model's quality metrics indicate a high-fidelity prediction, owing to the extremely high sequence identity with the template structure.

| Metric | Value | Interpretation |
| :--- | :--- | :--- |
| **Global Model Quality Estimate (GMQE)** | **0.88** | Excellent score (closer to 1.0 is better), suggesting high reliability of the overall fold. |
| **QMEAN DisCo Global** | $\mathbf{0.82 \pm 0.05}$ | High score, confirming the global model quality is comparable to high-resolution experimental structures. |
| **Template Identity** | **99.61%** | Near-perfect sequence match to the top template (PDB ID 4mf3), guaranteeing high structural accuracy. |

* **Local Quality Estimate (p-value):** The plot (`Local_quality_estimate.png`) shows that most residues have scores near 1.0, indicating high confidence across the entire structure.
* **QMEAN Z-Score:** The Z-scores are within the range of high-quality experimental structures, confirming the model's overall correctness.

---

## Repository Files

| File Name | Description | Category |
| :--- | :--- | :--- |
| **model\_01.pdb** | **The final predicted 3D structure** of the protein domain, in standard PDB format. | Output |
| `report.html` | The full interactive SWISS-MODEL report, containing all visualizations and template alignment data. | Output |
| `_2ZNS_1..._Summary.pdf` | Detailed summary including sequence, template filtering results, and global quality metrics. | Report |
| `_2ZNS_1..._Models.pdf` | Report containing residue-by-residue local quality estimates and alignment details. | Report |
| `_2ZNS_1..._Templates.pdf` | Full list of all templates identified and their quality scores. | Report |
| `Local_quality_estimate.png` | Graphical representation of the residue-by-residue local quality score (QMEANDisCo). | Visualization |
| `Quality_comparison.png` | Graph comparing the model's quality against the quality distribution of similar experimental structures. | Visualization |

---

## Setup and Usage

1.  **Clone the repository:**
    ```bash
    git clone [Your Repository URL]
    cd [Your Repository Name]
    ```

2.  **View the Model:**
    Load the `model_01.pdb` file into any molecular visualization software (e.g., **PyMOL**, **ChimeraX**, or **VMD**) to inspect the 3D structure.

3.  **Analyze the Report:**
    Open the **`report.html`** file in a web browser to view the interactive quality assessment and detailed alignments. The PDF summaries offer static, organized views of the same information.

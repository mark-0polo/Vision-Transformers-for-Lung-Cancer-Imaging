# Supplementary Materials: Vision Transformers for Lung Cancer Imaging

Supplementary data tables and reference screening audit accompanying the review paper:

> **Vision Transformers for Lung Cancer Imaging: Task-Specific Evidence, Validation, and Clinical Translation**  
> *Artificial Intelligence in Medicine*

---

## Authors

* **Mark Protik Mondol** ([ORCID](https://orcid.org/0009-0002-2140-6731)) – `markprotik12@gmail.com`  
* **Parishmita Sinha** ([ORCID](https://orcid.org/0009-0009-3465-2203)) – `parishmitasinha02@gmail.com`  
* **Mohammad Sakib Mahmood** ([ORCID](https://orcid.org/0000-0002-9198-9488)) – `sakib.mahmood@elitelab.ai`  
* **Md Kishor Morol** (*Corresponding Author*) ([ORCID](https://orcid.org/0000-0002-4468-8260)) – `kishor@elitelab.ai`  

**Affiliation:**  
ELITELab.AI, Queens, NY, USA

---

## Overview

This repository provides open access to the study-level extracted evidence and literature-selection audit supporting the comparative synthesis of pure Vision Transformers (ViTs), hybrid architectures, and convolutional neural networks (CNNs) across clinical lung cancer imaging workflows.

---

## Repository Contents

The repository contains two structured Excel workbooks:

### 1. `Supplementary_Data_S1.xlsx`
A comprehensive evidence matrix containing **165 extracted benchmark records** directly cross-referenced to original publication sources:
* **Reference & Study:** Citation numbering, primary author, and publication year.
* **Model & Architecture:** Model variant, architectural role (e.g., pure transformer, hybrid, backbone/encoder), and comparative baseline.
* **Input & Modality:** Datasets evaluated (e.g., LIDC-IDRI, NLST, OpenM3Chest, in-house clinical cohorts) and imaging modalities (CT, low-dose CT, PET/CT, CXR, histopathology).
* **Performance Metrics:** Quantitative outcomes (AUC, sensitivity, specificity, accuracy, Dice score, Concordance index, volume counts) alongside standardized units.
* **Evaluation Context:** Specific task scope (screening, nodule detection, malignancy risk, segmentation, staging, prognosis, or response assessment).
* **Traceability & Validation:** Direct DOI links, exact source locations (specific Table, Figure, or Page in the cited manuscript), and individual audit verification timestamps.

### 2. `Reference_Audit_Included_vs_Not_Included.xlsx`
A reference-level literature screening and bibliographic audit organized across 4 sheets:
* **`Summary`:** Reconciles total citation counts and bibliographic checks (zero missing DOIs, zero orphaned BibTeX keys, zero duplicate entries).
* **`Reference_Audit` & `Included_in_Review` (79 Included Studies):**
  * **57 Core Studies:** Retained for direct narrative synthesis, task-specific architectural comparison, and clinical validation analysis.
  * **9 Benchmark & Context References:** Foundational models, baseline methodologies, and clinical background papers.
  * **13 Supplementary-Update References:** Recent literature identified during supplementary updates.
  * *Metadata captured:* BibTeX citation keys, complete title/venue/DOI, citation frequency in the manuscript, and local full-text archive tracking.
* **`Not_Included` (24 Screened Studies):**
  * Documents candidate studies screened but excluded from the comparative synthesis (including 6 core transformer/hybrid papers and 15 context/comparator papers).
  * Records detailed rationale for non-retention (e.g., cohort size, missing baseline rigor, older single-dataset evaluations, or reporting inconsistencies) and quantitative evidence notes.

---

## Purpose & Scope

* **Transparency & Reproducibility:** Allows readers and reviewers to trace every synthesized metric, claim, and architecture comparison directly back to the exact table, figure, or section of the original published paper.
* **Reporting Scope:** All data points reflect the values reported in the original published studies. These workbooks serve as an evidentiary synthesis audit and do not represent re-execution of original model weights or codebases.

---

## Citation

If you use these supplementary materials, evidence tables, or audit logs in your research, please cite the review article:

```bibtex
@article{mondol2026vision,
  title   = {Vision Transformers for Lung Cancer Imaging: Task-Specific Evidence, Validation, and Clinical Translation},
  author  = {Mondol, Mark Protik and Sinha, Parishmita and Mahmood, Mohammad Sakib and Morol, Md Kishor},
  journal = {Artificial Intelligence in Medicine},
  year    = {2026}
}

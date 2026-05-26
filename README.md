# Quantitative Time-Lapse Imaging & scRNA-seq Analysis Pipeline (GSE167317)

Data downloaded from GSE167317 - PMID: 35820055

This pipeline was adjusted and modified based on our objectives. 

The code necessary to reproduce all findings described in the paper is available at https://bsse.ethz.ch/csd/software/trackSeq.html
------------------------------------------------------------

## Main Report

The primary deliverable is a rendered R Markdown report:

GSE167317_code.html – rendered analysis report (recommended starting point)
GSE167317_code.Rmd – R Markdown source containing all code and narrative
Please open the GSE167317_code.html file in a web browser to view the full analysis.

All data and repositories are stored in "Z:\home\common\Data\NM\Analysis_GSE167317"

------------------------------------------------------------

## Repository Structure

- `paper-info/` – input data objects
  *(Not included in this repository due to dataset size)*
- `csv/` – CSV files generated during analysis
- `gencode/` – files related to GENCODE annotation
- `plots/` – figures and plots generated during the analysis  
- `rda/` – saved `.rda` objects  
  *(Not included in this repository due to file size)*

All code used in the analysis is contained directly in the R Markdown document.

Large data files were not added to their respective repository.

------------------------------------------------------------

## Notes on data files

A large serialized R workspace object (workspace.rda) generated during analysis
is not included in the repository to keep it lightweight. All figures and results
are fully reproducible from the provided R Markdown document.

- Paths in scripts may need to be adjusted to your system
- Make sure all required software is installed before running

------------------------------------------------------------

## Required Files

Download required files from: https://www.gencodegenes.org/mouse/release_M21.html

------------------------------------------------------------

## Author

Prepared by: **Silva Morosini, Natalia**  
Date: **May 26, 2026**
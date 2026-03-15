# Bioinformatics
Bioinformatics Case
# Mini Bioinformatics Pipeline

This project implements a small reproducible bioinformatics pipeline for analyzing long-read sequencing data.

## Features

- FASTQ quality control
- GC content analysis
- Read length analysis
- Mean quality score calculation
- Visualization of sequencing statistics

## Tools Used

- Python
- Snakemake
- Conda
- Pandas
- Matplotlib

## How to Run

1. Create the environment

conda env create -f env/environment.yml

2. Activate environment

conda activate bio_pipeline

3. Run the pipeline

snakemake --cores 1

## Output

The pipeline generates:

- CSV file containing read statistics
- Distribution plots for:
  - GC content
  - Read length
  - Mean quality scores
  - 

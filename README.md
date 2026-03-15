# Bioinformatics
Bioinformatics Case
Dear Professor Kılıç,

    I have performed an initial quality control analysis of the provided long-read sequencing data. The pipeline calculated several key metrics including GC content, read length distribution, and mean read quality scores. Visualizations were generated to better understand the distribution of these metrics across all reads. The read length distribution appears consistent with long-read sequencing technology. GC content values fall within the expected biological range, suggesting no obvious bias in the sequencing process. Quality scores are generally within an acceptable range for long-read sequencing platforms, indicating that the data should be suitable for downstream analysis. Based on these results, I recommend proceeding with the alignment and further genomic analysis.
Best regards, 

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

# GATK4 Germline Variant Calling Pipeline

This project demonstrates a germline variant calling workflow using human whole-genome sequencing (WGS) data from the 1000 Genomes Project (HG00096, SRR062634).

## Dataset
-**Sample:** HG00096
- **Sequencing data:** SRR062634 (paired-end reads)
- **Source:** 1000 Genomes Project
- **Reference genome:** Human hg38

## Tools Used

- **FastQC:** Quality control
- **BWA-MEM:** Read alignment
- **SAMtools:** Reference genome indexing
- **GATK4:** Duplicate marking, base quality score recalibration (BQSR), variant calling, and filtering
- **Funcotator:** Functional annotation of SNPs and INDELs
- **Bash & AWK:** Workflow execution and variant record filtering

## Reference Genome
Human hg38

**Note:** This pipeline was developed for educational purposes.

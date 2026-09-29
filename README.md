# Ipomoea batatas Chloroplast Genome Annotation Analysis

## Student & Course Information
* **Student Name:** Ray Gee J. Lisondra
* **Course and Section:** Cell and Molecular Biology - A

## Organism & Accession Details
* **Chosen Genus & Species:** *Ipomoea batatas* 
* **NCBI Accession / Version:** NC_026703.1
* **NCBI Reference Link:** (https://www.ncbi.nlm.nih.gov/nuccore/NC_026703)
* **Retrieval Date:** September 29, 2026

## Plastome Overview & Size
* **Genome Size:** 161,303 base pairs (bp)
* **Plastome Summary:** The chloroplast genome shows a quadripartite plant structure containing Large Single Copy (LSC), Small Single Copy (SSC), and two Inverted Repeat (IR) regions, characterized by duplicated gene sets and standard plastid functional groups (photosystem subunits, ATP synthases, ribosomal proteins, rRNAs, and tRNAs).

## Methodology & Workflow
* **Acquisition:** The annotation file (GFF3/GenBank format) was retrieved directly from NCBI RefSeq and uploaded into the Galaxy.
* **Galaxy History & Tools Used:**
  * **History:** Plastid_Ipomoea_Lisondra
  * **Tool used:** FASTA statistics wass utilized to compute basic sequence length, nucleotide composition, and summary metrics.
    
## Gene Content Summary and Observations
* **Total Gene Count:** 141 genes.
* **Functional Group Breakdown:**
  * **Protein-Coding & Other Genes:** 93 (including psa, psb, pet, rpo, rpl, rps, and ycf).
  * **tRNA Genes:** 40 .
  * **Ribosomal RNA (rRNA) Genes:** 8 
* **Notable Features:** Structural regions (LSC, SSC, IR) are defined by coordinate boundaries and duplicated gene blocks rather than explicit layout rows. Introns and exons are identifiable via associated exon and Parent tags.

## Data Sources & References
* NCBI GenBank Database: Accession NC_026703 (https://www.ncbi.nlm.nih.gov/nuccore/NC_026703.1).
* Galaxy Platform for genomic data analysis and filtering workflows.

## Reproducibility Guide
To replicate this analysis in Galaxy:
1. Import the *Ipomoea batatas* chloroplast annotation file (`NC_026703` in FASTA format) into your Galaxy history.
2. Run the **Fasta Statisitics** tool with the condition to check sequence proprties.

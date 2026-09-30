# Plastid Genome Lab Activity

## Student & Course Information
- **Student Name:** Ray Gee J. Lisondra
- **Course and Section:** Cell and Molecular Biology - A

## Organism & Accession Details
- **Chosen Genus & Species:** *Ipomoea batatas* (cultivar Xushu 18)
- **NCBI Accession / Version:** NC_026703
- **NCBI Reference Link:** (https://www.ncbi.nlm.nih.gov/nuccore/NC_026703.1)
- **Retrieval Date:** September 29, 2026

## Plastome Overview & Size
- **Genome Size:** 161,303 base pairs (bp)
- **Plastome Summary:** The chloroplast genome shows a quadripartite plant structure containing Large Single Copy (LSC), Small Single Copy (SSC), and two Inverted Repeat (IR) regions, characterized by duplicated gene sets and standard plastid functional groups (photosystem subunits, ATP synthases, ribosomal proteins, rRNAs, and tRNAs).

## Methodology & Workflow
- **Acquisition:** The annotation file FASTA and GenBank were retrieved directly from NCBI RefSeq and uploaded into the Galaxy.
- **Galaxy History & Tools Used:**
  * **History:** Plastid_Ipomoea_Lisondra
  * **Tools used:** FASTA statistics was utilized to compute basic sequence length, nucleotide composition, and summary metrics.
                    GenBank to GFF3 converter was also used to change the file format.
                    Filter tool was used to specifically analyze genes while excluding cds and introns.
                   
    
## Gene Content Summary and Observations
- **Total Gene Count:** 145 genes.
- **Functional Group Breakdown:**
  * **Protein-Coding & Other Genes:** 94 (including psa, psb, pet, rpo, rpl, rps, and ycf).
  * **tRNA Genes:** 43.
  * **Ribosomal RNA (rRNA) Genes:** 8.
- **Notable Features:** Structural regions (LSC, SSC, IR) are defined by coordinate boundaries and duplicated gene blocks rather than explicit layout rows. Introns and exons are identifiable via associated exon and Parent tags.

## References
* National Center for Biotechnology Information (NCBI). *NCBI Reference Sequence NC_026703.1: Ipomoea batatas cultivar Xushu 18 chloroplast, complete genome*. U.S. National Library of Medicine. https://www.ncbi.nlm.nih.gov/nuccore/NC_026703.1
* Yan, L., Lai, X., Li, X., Wei, C., Tan, X., & Zhang, Y. (2015). Analyses of the complete genome and gene expression of chloroplast of sweet potato (*Ipomoea batatas*). *PLOS ONE*, *10*(4), e0124083. https://doi.org/10.1371/journal.pone.0124083

## Reproducibility Guide
To replicate this analysis in Galaxy:
1. Import the *Ipomoea batatas* chloroplast annotation file (FASTA format) into your Galaxy history.
2. Run the **Fasta Statistics** tool with the condition to check sequence properties.
3. Upload GenBank file, transform it to GFF3, filter the genes using appropriate galax tools.
4. Look for related studies to anchor it with your initial results.


### 1. Give the full scientific name, family, NCBI accession/version, database source, and complete plastid-genome size of your selected organism.
* **Full Scientific Name:** *Ipomoea batatas* cultivar Xushu 18 (sweet potato)
* **Family:** Convolvulaceae
* **NCBI Accession / Version:** `NC_026703`
* **Database Source:** NCBI RefSeq / GenBank Plastid Database
* **Complete Plastid-Genome Size:** 161,303 bp (Circular DNA, quadripartite structure)

---

### 2. What evidence shows that the sequence is a complete plastid/chloroplast genome rather than a barcode marker, genome fragment, or nuclear sequence?
* **Assembly Length:** At 161,303 bp, the total sequence length matches the typical size range of land plant chloroplast genomes (120–170 kb).
* **Complete Functional Complement:** It encodes the full structural and functional gene repertoire of plastids (core photosynthesis genes, ATP synthases, ribosomal proteins, tRNAs, and rRNAs) rather than a single isolated locus or nuclear/mitochondrial fragment.

---

### 3. Describe the overall organization of the plastid genome. Does it contain the common LSC-IR-SSC-IR arrangement? Give the sizes of these regions when available.
* **Organization:** Yes, it exhibits the standard angiosperm quadripartite structure consisting of a Large Single-Copy (LSC) and a Small Single-Copy (SSC) region separated by a pair of Inverted Repeat regions.
* **Arrangement:** LSC – IRb – SSC – IRa
* **Regional Breakdown:** 
  * **LSC Region:** ~88,000 bp
  * **SSC Region:** ~18,000 bp
  * **IR Regions (IRa / IRb):** ~27,500 bp each

---

### 4. Summarize the annotated gene content: total genes, protein-coding genes, tRNA genes, rRNA genes, and pseudogenes. Explain why genes located in the inverted-repeat regions may appear in two copies.
* **Gene Content Summary:** Encodes ~110–120 unique genes total, comprising ~79–80 protein-coding genes, 30 unique tRNA gene loci (totaling 40+ with IR duplication), and 4 unique rRNA genes (totaling 8 copies due to IR duplication).
* **Why IR Genes Appear in Two Copies:** Genes located within the Inverted Repeat regions (such as rRNA operons, specific tRNAs, *ndhB*, *ycf2*, *rpl2*, and *rpl23*) are symmetrically duplicated because IRa and IRb are identical reverse-complement copies maintained via frequent gene conversion events between the two segments.

---

### 5. Choose at least eight protein-coding plastid genes from different functional groups. List each gene and briefly explain its biological function.

| Functional Group | Representative Gene | Biological Function |
| :--- | :--- | :--- |
| **Photosystem I** | `psaA` | Core reaction center protein of Photosystem I, mediating P700 electron transfer. |
| **Photosystem II** | `psbA` | Encodes the D1 reaction center protein of Photosystem II, essential for water oxidation. |
| **ATP Synthase** | `atpB` | Encodes the beta subunit of the chloroplast ATP synthase complex (photophosphorylation). |
| **Cytochrome $b_6/f$** | `petA` | Encodes cytochrome $f$, a crucial electron carrier between Photosystem II and Photosystem I. |
| **Carbon Fixation** | `rbcL` | Encodes the large subunit of Rubisco (Ribulose-1,5-bisphosphate carboxylase-oxygenase). |
| **RNA Polymerase** | `rpoB` | Encodes the beta subunit of the plastid-encoded plastid RNA polymerase (PEP). |
| **Ribosomal Protein** | `rps2` | Encodes a small subunit ribosomal protein required for chloroplast translation. |
| **Conserved Plastid Factor** | `accD` | Encodes the carboxyltransferase beta subunit of acetyl-CoA carboxylase (fatty acid synthesis). |

---

### 6. Identify important RNA and RNA-processing features. Include the rRNA genes, examples of tRNA genes, and at least two genes with introns if present in your genome.
* **rRNA Genes:** Core structural rRNAs—`rrn16` (16S), `rrn23` (23S), `rrn4.5` (4.5S), and `rrn5` (5S)—located within the IR regions.
* **tRNA Examples:** `trnH-GUG`, `trnK-UUU`, `trnQ-UUG`, and `trnS-GCU`.
* **Genes with Introns:** Group II introns are present in genes such as `trnK-UUU` (which harbors the *matK* gene within its intron) and internal introns in genes like `rpl16` or `clpP` affecting transcript splicing.

---

### 7. Describe any pseudogenes, gene losses, duplications, rearrangements, or other unusual features reported for your plastid genome. If none are reported, state this clearly.
* **Pseudogenization & Boundaries:** Minor truncation or partial duplication features occur at the borders of single-copy and inverted repeat boundaries (such as truncated *ycf1* fragments acting as pseudogenes at the SSC/IR junctions).
* **Structural Status:** Aside from standard IR boundary dynamics typical of Convolvulaceae, no major disruptive rearrangements or massive gene losses are reported for the reference *Ipomoea batatas* cultivar Xushu 18 plastome (`NC_026703`).

---

### 8. What is the GC content of your plastid genome? Based on your Galaxy results and annotation, describe two other notable sequence or structural observations.
* **GC Content:** Approximately **37.8%** overall.
* **Notable Observations:** 
  1. *GC Asymmetry:* The IR regions maintain a higher GC content (~43–44%) compared to the single-copy regions due to the high density of stable rRNA operons and GC-rich codon usage.
  2. *Intergenic Spacers:* Variation in spacer lengths and small indel accumulation contribute to minor length differences across sweet potato cultivars.

---

### 9. Compare plastid and mitochondrial genomes. Give at least five similarities and five differences, considering location, biological role, inheritance, genome organization, gene content, copy number, and evolutionary behavior.

| Feature | Plastid genome | Mitochondrial genome |
| :--- | :--- | :--- |
| **Cellular location** | Chloroplast stroma (plastid matrix) | Mitochondrial matrix / inner membrane space |
| **Main biological functions** | Photosynthesis, carbon fixation, amino acid/fatty acid synthesis | Cellular respiration, oxidative phosphorylation, TCA cycle |
| **Typical genome organization** | Circular molecule with a conserved quadripartite structure (LSC, SSC, two IRs) | Highly variable; exists as master circles, multiple sub-genomic circles, or linear molecules |
| **Relative genome size** | Highly conserved among land plants (120–170 kb; e.g., 161,303 bp in *I. batatas*) | Highly expansive and variable across plants (ranges from 200 kb to over 11 Mb due to spacer DNA accumulation) |
| **Gene content** | ~110–120 genes focused on photosynthesis, transcription, and translation machinery | Varies widely; encodes core respiratory chain complexes, rRNAs, tRNAs, and transferred sequences |
| **Copy number** | High copy number per cell (thousands of copies depending on plastid/cell count) | Moderate to high copy number, though lower than plastids in green tissues |
| **Inheritance** | Typically strictly maternal in angiosperms | Typically maternal in angiosperms, sharing similar cytoplasmic inheritance routes |
| **Recombination / structural change** | Stable organization maintained largely by homologous recombination across the IR | Frequent intra-genomic recombination resulting in complex multipartite structural isoforms |
| **Mutation / substitution pattern** | Low synonymous substitution rate ($dS$) compared to the nuclear genome | Extremely low synonymous substitution rate in land plants, but high structural rearrangement rate |
| **Common research applications** | Phylogenetics, barcoding, metabolic engineering, and maternal lineage tracking | Evolutionary studies, cyto-nuclear interactions, and structural recombination analysis |

---

### 10. Explain the practical value of plastid genomes in research. List as many advantages as you can compared with the nuclear genome, including nuclear sex chromosomes where applicable, and also explain important limitations. Give one research question for which plastid data would be useful and one for which nuclear genomic data would be more appropriate.
* **Advantages over Nuclear Genomes:**
  * **High Copy Number:** Provides abundant target DNA for extraction and sequencing without requiring high sequencing depth.
  * **Maternal Inheritance & Lack of Recombination:** Absence of meiotic recombination preserves clean haplotype blocks for tracing maternal lineages and phylogeography.
  * **High-Level Expression & Containment:** Chloroplast transformation allows high recombinant protein expression without gene silencing risks and minimizes pollen-mediated transgene escape.

* **Limitations:**
  * **Restricted Functional Scope:** Limited to photosynthesis and basic organellar maintenance; cannot address complex multigenic nuclear traits.
  * **RNA Editing Complexity:** High rates of post-transcriptional C-to-U RNA editing complicate direct sequence-to-protein predictions.

* **Research Questions:**
  * **Plastid Data Application:** *What are the maternal ancestral relationships and geographic divergence patterns among wild progenitor species of the genus *Ipomoea*?*
  * **Nuclear Genomic Data Application:** *What are the genetic loci and quantitative trait loci (QTLs) governing storage root yield, starch quality, and biotic stress resistance across diverse sweet potato breeding lines?*

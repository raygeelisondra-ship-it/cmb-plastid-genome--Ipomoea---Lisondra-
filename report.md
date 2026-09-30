### 1. Give the full scientific name, family, NCBI accession/version, database source, and complete plastid-genome size of your selected organism.
* **Full Scientific Name:** *Ipomoea batatas* (cultivar Xushu 18)
* **Family:** Convolvulaceae[cite: 3]
* **NCBI Accession / Version:** `KP212149`
* **Database Source:** National Center for Biotechnology Information (NCBI) [https://www.ncbi.nlm.nih.gov/nuccore/NC_026703.1]
* **Complete Plastid Genome Size:** 161,303 bp

---

### 2. What evidence shows that the sequence is a complete plastid/chloroplast genome rather than a barcode marker, genome fragment, or nuclear sequence?
* The sequence forms a continuous circular molecule spanning 161,303 bp featuring the characteristic angiosperm quadripartite structure.
* It contains a fully annotated complement of 145 complete genes partitioned across single-copy and inverted repeat regions, rather than an isolated gene fragment, short barcode marker (such as *rbcL* or *matK* alone), or nuclear DNA contaminant.

---

### 3. Describe the overall organization of the plastid genome. Does it contain the common LSC-IR-SSC-IR arrangement? Give the sizes of these regions when available.
* **Arrangement:** Yes, it features the typical angiosperm quadripartite structure consisting of a Large Single-Copy (LSC) region and a Small Single-Copy (SSC) region separated by a pair of Inverted Repeat regions ($\text{IR}_A$ and $\text{IR}_B$) in the arrangement $\text{LSC} – \text{IR}_B – \text{SSC} – \text{IR}_A$.
* **Sizes / GC Statistics:** While exact region kilobase lengths are not detailed in the text excerpt, the total circular genome size is 161,303 bp with specific regional GC contents: LSC is 36.13%, SSC is 33.78%, and the IR regions are 41.25%.

---

### 4. Summarize the annotated gene content: total genes, protein-coding genes, tRNA genes, rRNA genes, and pseudogenes. Explain why genes located in the inverted-repeat regions may appear in two copies.
* **Total Genes:** 145 genes (103 single-copy and 21 duplicated).
* **Protein-Coding Genes:** 94 total genes (72 single-copy located in LSC/SSC regions and 11 two-copy genes in the IRs).
* **tRNA Genes:** 43 total (31 single-copy and 6 two-copy genes).
* **rRNA Genes:** 8 total (all duplicated in the IR regions: *rrn23*, *rrn16*, *rrn5*, and *rrn4.5*).
* **Pseudogenes:** 7 pseudogenes/unknown functions.
* **Duplication Explanation:** Genes located in the inverted-repeat ($\text{IR}$) regions appear in two copies because $\text{IR}_A$ and $\text{IR}_B$ are identical reverse-complement duplicate segments situated on opposite sides of the circular genome.

---

### 5. Choose at least eight protein-coding plastid genes from different functional groups. List each gene and briefly explain its biological function.
1. ***psaA* (Photosystem I):** Encodes a core reaction center protein for Photosystem I, mediating light-driven electron transport.
2. ***psbA* (Photosystem II):** Encodes the D1 reaction center protein of Photosystem II, essential for splitting water during photosynthesis.
3. ***atpA* (ATP Synthase):** Encodes the alpha subunit of the chloroplast ATP synthase complex, which synthesizes ATP[cite: 1].
4. ***petA* (Cytochrome $b_6/f$ complex):** Encodes cytochrome $f$, an essential electron carrier component bridging Photosystem II and I.
5. ***rbcL* (Calvin Cycle):** Encodes the large subunit of Rubisco, which catalyzes carbon fixation during the Calvin cycle.
6. ***ndhB* (Chlororespiration / NADH dehydrogenase):** Part of the chloroplast NADH dehydrogenase complex involved in cyclic electron flow and chlororespiration.
7. ***rpoA* (RNA Polymerase):** Encodes the alpha subunit of the plastid-encoded RNA polymerase responsible for gene transcription.
8. ***matK* (Gene Expression Machinery):** Encodes a maturase-like protein involved in the splicing of group II introns from transcripts.

---

### 6. Identify important RNA and RNA-processing features. Include the rRNA genes, examples of tRNA genes, and at least two genes with introns if present in your genome.
* **rRNA Genes:** Four distinct rRNA species, all duplicated in the IR regions (*rrn23*, *rrn16*, *rrn5*, and *rrn4.5*).
* **tRNA Gene Examples:** *trnH-GUG*, *trnK-UUU*, *trnQ-UUG*, and *trnS-GCU*.
* **Genes with Introns:** Examples from the dataset containing introns include *ndhA*, *ndhB*, *rpoC1*, and *atpF*.

---

### 7. Describe any pseudogenes, gene losses, duplications, rearrangements, or other unusual features reported for your plastid genome. If none are reported, state this clearly.
* **Pseudogenes & Unique Features:** The genome contains 7 pseudogenes/unknown functions (*ycf2*, *ycf15*, *ycf68*, *ihbA*, *orf42*, *orf56*, and *orf188*). Notably, *ihbA* is identified as a unique gene relative to other *Ipomoea* plants[cite: 3].
* **Duplications:** 21 genes are duplicated via the Inverted Repeat regions. No major structural rearrangements or unusual genome losses are reported.

---

### 8. What is the GC content of your plastid genome? Based on your Galaxy results and annotation, describe two other notable sequence or structural observations.
* **Overall GC Content:** 38.45% overall (LSC: 36.13%, SSC: 33.78%, IR regions: 41.25%).
* **Notable Observations:** 
  1. The distinct elevation of GC content in the Inverted Repeat regions (41.25%) compared to single-copy regions, which is typical due to the high base composition stability of ribosomal RNAs residing there.
  2. The presence of the unique *ihbA* pseudogene element distinguishing the sweet potato plastid genome structurally from related *Ipomoea* species.

---

### 9. Compare plastid and mitochondrial genomes. Give at least five similarities and five differences, considering location, biological role, inheritance, genome organization, gene content, copy number, and evolutionary behavior.
* **Similarities:**
  1. Both are extranuclear organellar genomes possessing circular DNA molecules.
  2. Both replicate independently of the host cell nuclear cycle.
  3. Both share endosymbiotic evolutionary origins derived from bacterial ancestors (cyanobacteria and proteobacteria).
  4. Both encode critical components essential for cellular energy metabolism and ATP synthesis.
  5. Both possess their own specialized internal transcription and translation machinery (ribosomal RNAs and tRNAs).
* **Differences:**
  1. **Primary Metabolic Role:** Plastids handle photosynthesis, carbon fixation, and lipid/amino acid synthesis; mitochondria handle cellular respiration and oxidative phosphorylation.
  2. **Inheritance Pattern:** Chloroplasts are typically maternally inherited, whereas plant mitochondrial inheritance can vary (maternally, biparentally, or paternally).
  3. **Genome Architecture:** Plastids exhibit a strict, conserved quadripartite structure (LSC-IR-SSC-IR)plant mitochondria frequently have fluid, multipartite, or subgenomic structures.
  4. **Genome Size:** Plant chloroplast genomes are moderate and uniform (120–170 kb); plant mitochondria vary vastly in size, often expanding massively due to non-coding sequence accumulation.
  5. **Gene Content:** Chloroplasts retain a high count of photosynthetic and chlororespiratory genes; mitochondria focus on TCA cycle enzymes and oxidative phosphorylation chains.

---

### 10. Explain the practical value of plastid genomes in research. List as many advantages as you can compared with the nuclear genome, including nuclear sex chromosomes where applicable, and also explain important limitations. Give one research question for which plastid data would be useful and one for which nuclear genomic data would be more appropriate.
- **Advantages over Nuclear Genome:** 
  * **High Production Volume:** Because there are thousands of copies of chloroplast DNA in a single plant cell, scientists can use them to produce very large amounts of a desired protein.
  * **Better Environmental Safety:** In most crops, chloroplasts are passed down only through the mother plant's eggs (not pollen), which greatly reduces the risk of genetically modified genes spreading to wild plants via wind-blown pollen.
  * **Precise Gene Insertion:** New genes can be placed into exact, targeted spots rather than landing randomly in the DNA, which prevents accidental damage to other important genes.
  * **Stable Expression:** The inserted genes are much less likely to be accidentally turned off or disrupted by neighboring DNA compared to genes in the nucleus.

- **Important Limitations:** 
  * **Technical Difficulty:** It is technically challenging and often has low success rates when trying to modify chloroplasts in certain crop species.
  * **Limited Protein Processing:** Chloroplasts cannot handle complex protein modifications (like adding specific sugar chains) as well as the main cell nucleus can.
  * **Pollen Restriction:** Because chloroplast DNA is only passed through the mother plant, you cannot use this method to pass traits through pollen if that is your breeding goal.

- **Research Question (Plastid Data Useful):** "Can chloroplast DNA sequences be used to trace the maternal ancestry and geographic origin of different sweet potato varieties?"

- **Research Question (Nuclear Genomic Data):** "Which nuclear genes control the inheritance of storage root skin and flesh color in sweet potato?"

`Note`: The sizes of LSC,SSC, andIR were supported by the studies of Yan et al., (2015).

### 9. Plastid vs. Mitochondrial Genome Comparison

| Feature | Plastid genome | Mitochondrial genome |
| :--- | :--- | :--- |
| **Cellular location** | Located inside the chloroplasts within the plant cell cytoplasm. | Located inside the mitochondria within the plant cell cytoplasm. |
| **Main biological functions** | Photosynthesis, carbon fixation (Calvin cycle), and synthesis of amino acids, fatty acids, and pigments. | Cellular respiration, oxidative phosphorylation, and the tricarboxylic acid (TCA) cycle for ATP generation. |
| **Typical genome organization** | Conserved circular molecule with a quadripartite structure (Large Single-Copy, Small Single-Copy, and two Inverted Repeats). | Highly variable, complex, and multipartite structures, often consisting of multiple subgenomic circles or linear/branched molecules. |
| **Relative genome size** | Moderate and uniform across angiosperms, typically ranging from 120 kb to 170 kb (specifically **161,303 bp** in *Ipomoea batatas*). | Highly variable and exceptionally large in plants, ranging from 200 kb to over 11 Mb due to non-coding sequence expansions. |
| **Gene content** | Encodes around 110–145 total genes focused on photosynthesis, chlororespiration (`ndh`), ribosomal proteins, tRNAs, and rRNAs. | Encodes core components of the electron transport chain, ribosomal proteins, tRNAs, and rRNAs (fewer photosynthetic genes, higher focus on respiration and intron splicing). |
| **Copy number** | High copy number per cell (thousands of copies distributed across multiple plastids). | Moderate to high copy number per cell, though often lower than chloroplasts depending on tissue metabolic demand. |
| **Inheritance** | Strictly maternal inheritance in the vast majority of angiosperm crop species. | Varies by lineage; predominantly maternal in most angiosperms, but can be biparental or paternal in certain plant groups. |
| **Recombination / structural change** | Relatively stable structure, though structural rearrangements and expansions/contractions at the Inverted Repeat boundaries occur. | Highly dynamic with frequent homologous recombination across repeated sequences, leading to complex subgenomic molecule shifts. |
| **Mutation / substitution pattern** | Generally low nucleotide substitution rates compared to nuclear and mitochondrial genomes. | Extremely low point-mutation/substitution rate, but prone to structural rearrangements and foreign DNA insertions. |
| **Common research applications** | Studying plant evolution, tracking maternal ancestry, and engineering crops to produce higher yields. | Studying plant evolution, investigating how cell organelles communicate, and breeding crops for hybrid seed production. |

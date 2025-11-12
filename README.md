# Genomics
**Informative markers of wheat productivity, quality and sustainability based on open genomic data**

The project aims to identify and functionally annotate informative genetic markers (SNPs, candidate genes) associated with productivity, grain quality, and resistance to major diseases in wheat. Open GWAS and sequencing data will be integrated, phenotypes will be harmonized using unified ontologies, and coordinates will be transferred to the current reference assembly. Association analysis with population structure control will be supplemented by meta-analysis across studies, colocalization with candidate genes, and prioritization based on composite criteria (significance, effect size, biological plausibility). Based on consensus loci, a compact, high-priority list of approximately 150–300 SNP candidates with available flanking sequences will be compiled. SNPs with multiple mappings and potential A/B/D homologues (2 x 250 bp flanks) are excluded, preventing artificially inflated LD in hexaploids and confounding subgenome signals. The results will be implemented through a reproducible analytical pipeline and an interactive web dashboard with genome maps, Manhattan plots, and network visualizations. Expected benefits include increased accuracy and speed of selection, shorter decision-making cycles, personnel training, and the creation of a national marker database for a sustainable grain industry.

Objective of the project

To create a scientifically validated and independently validated marker-assisted selection system for wheat, taking into account regional relevance for breeding programs in Kazakhstan: identify and functionally annotate loci and SNPs consistently associated with productivity, grain quality, and rust resistance, develop a reproducible analysis pipeline and interactive dashboard, and, based on these, generate and in silico verify a compact, high-priority list of approximately 150–300 informative SNPs.

Project objectives
*	Data Collection and Harmonization: Collect and conduct legal and quality control analysis of open GWAS and phenotypic data. Unify phenotypes using Crop Ontology and transfer genomic data coordinates to a single reference assembly.
*	Functional Annotation and Candidate Prioritization: Colocalize GWAS signals with candidate genes and functional data. Develop and implement a composite scoring system for SNP ranking.
*	Formation and in silico validation of the final tag-SNP registry: Form a preliminary list of tag-SNPs and conduct its rigorous validation using the "leave-one-study-out" and "leave-one-country-out" methods. Calculate Genomic Prediction Accuracy and calibrate models.
*	Tool Development and Implementation: Implement a containerized, reproducible pipeline (Nextflow/Snakemake) and deploy a prototype interactive web dashboard (Django/FastAPI).
*	Documentation, Publication, and Dissemination: Prepare scientific publications, and conduct training workshops for breeders.

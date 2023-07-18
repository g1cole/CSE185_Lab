# CSE185 Labwork
Advanced Bioinformatics Lab Class Spring 2023 at UC San Diego

## Index Material
*Introductory Material with Exercises*  

Lab 1: [Next Generation Sequencing and Mutation Hunting](https://github.com/g1cole/CSE185_Lab/blob/main/Lab%201%20-%20Next%20Generation%20Sequencing%20and%20Mutation%20Hunting/CSE185-LAB1-PART1%20(1).pdf) | [Part 2](https://github.com/g1cole/CSE185_Lab/blob/main/Lab%201%20-%20Next%20Generation%20Sequencing%20and%20Mutation%20Hunting/CSE185-LAB1-PART2.pdf)  
- Learned and applied sequence alignment, variant calling, and standard file formats (FASTQ/BAM/VCF) to process NGS data and performed whole genome sequencing to discover potential disease-causing mutations
  - Skills covered: basic UNIX navigation, NGS, sequence alignment and variant calling, python plotting, python scripting and error sources
  
Lab 2: [Sequence Assembly](https://github.com/g1cole/CSE185_Lab/blob/main/Lab%202%20-%20Sequence%20Assembly/CSE185-LAB2-PART1.pdf) | [Part 2](https://github.com/g1cole/CSE185_Lab/blob/main/Lab%202%20-%20Sequence%20Assembly/CSE185-LAB2-PART2.pdf)
- Estimated size of a sequenced E. coli strain from an Illumina whole genome sequencing dataset using kmer count histograms and assembled the sequencing reads into a genome of E. coli using short reads from Illumina and long reads from PacBio and compared the quality of the resulting sequences
  - Skills covered: genome size estimation, sequence assembly, command line one-liners, and managing computational resource
  
Lab 3: [Population Genetics & GWAS](https://github.com/g1cole/CSE185_Lab/blob/main/Lab%203%20-%20Population%20Genetics%20%26%20GWAS/CSE185-LAB3-PART1.pdf) | [Part 2](https://github.com/g1cole/CSE185_Lab/blob/main/Lab%203%20-%20Population%20Genetics%20%26%20GWAS/CSE185-LAB3-PART2.pdf)
- Used population genetics datasets (mainly VCF files), analysis tools (bcftools) and principal component analysis (PCA) to perform ancestry analysis and also performed a genome-wide association study of a quantitative trait (LDL cholesterol) and explored effects of confounding by ancestry.
  - Skills covered: GWAS, genotype data, principal components analysis, ancestry analysis, plink, p-values, and plotting
  
*Lab Material with Applications*

Lab 4: [RNA-seq | Transcriptomics](https://github.com/g1cole/CSE185_Lab/blob/main/Lab%204%20-%20RNA-seq/CSE185-LAB4-REPORT.pdf) | [code](https://github.com/g1cole/CSE185_Lab/blob/main/Lab%204%20-%20RNA-seq/CSE185-LAB4-README.pdf)  
- Performed RNA-sequencing on mice samples and analyzed the RNA-seq results to determine which genes changed their expression and what their function is by using Gene Expresssion Omnibus, IGV, DESeq2, PANTHER, STAR, and RSEM
  - Pipeline: Alignment of RNA-seq data and quantifying expression levels -> Differential Expression Analysis -> "GO" Enrichment analysis to characterize differentially expressed genes -> Visualizing expression data with IGV
  - Skills covered: differential expression, R, and enrichment analysis

Lab 5: [ChIP-seq | Epigenomics](https://github.com/g1cole/CSE185_Lab/blob/main/Lab%205%20-%20ChIP-seq/CSE185-LAB5-REPORT.pdf) | [code](https://github.com/g1cole/CSE185_Lab/blob/main/Lab%205%20-%20ChIP-seq/CSE185-LAB5-README.pdf)  
- Analyzed ChIP-sequencing of three transcription factors and two histone modifications from mouse embryonic stem cells to determine where these factors and modifications are binding and performed motif analysis to determine which specific motifs they are binding to using the tools BWA MEM, IGV, and HOMER
  - Pipeline: Aligning ChIP-seq reads to reference genome -> Visualizing ChIP-seq data in IGV -> Identifying binding sites from ChIP-seq data ("peak calling") -> Visualizing patterns of transcription factor and histone modification binding -> Motif finding to identify the sequence a transcription factor binds to
  - Skills covered: ChIP-seq, genome browssers, peak calling, and motif finding
  
Lab 6: [scRNA-seq](https://github.com/g1cole/CSE185_Lab/blob/main/Lab%206%20-%20scRNA-seq/CSE185-LAB6-REPORT.pdf) | [code](https://github.com/g1cole/CSE185_Lab/blob/main/Lab%206%20-%20scRNA-seq/CSE185-LAB6-README.pdf)
- Used human pancreatic cells samples from stem cells to analyze scRNA-seq data from multiple stafes across the differentiation process to learn more about the genes that go up and down across the different stages of development using the python library "scanpy" and the r tool "Seurat"
  - Pipeline: Loading single-cell data into Scanpy -> Basic filtering and QC -> Correcting for batch effects -> Using dimensionality reduction techniques (PCA), clustering (Leiden) and visualizations (UMAP, t-SNE) to visualize and identify cell type clusters
  - Skills covered: scRNA-seq, dimensionality reduction, and using Python analysis packages
  
Lab 7: [COVID Phylogenetics](https://github.com/g1cole/CSE185_Lab/blob/main/Lab%207%20-%20COVID%20Phylogenetics/CSE185-LAB7-REPORT.pdf) | [code](https://github.com/g1cole/CSE185_Lab/blob/main/Lab%207%20-%20COVID%20Phylogenetics/CSE185-LAB7-README.pdf)
- Analyed the genome multiple straings of the novel coronavirus (SARS-CoV-2) and used comparative genomics techniques to explore how the virus relates to the other types of coronaviruses of different virus specifics using the tools mafft and RaxML
  - Pipeline: Obtaining genome assemblies from NCBI and raw reads from SRA -> Performing multiple sequence alignment -> Building a phylogenetic tree to explore the evolutionary relationship between virus strains -> Visualizing phylogenetic trees
  - Skills covered: Multiple sequence alignment, Phylogenetics, Installing tools, and finding data

![Erill Lab Logo](https://github.com/ErillLab/.github/blob/main/profile/ErillLab_Logo.svg)

As Robert Robbins[^1] put it, the DNA sequence of an organism is “the result of literally millions of maintenance revisions performed by the worst possible set of kludge–using, spaghetti–coding, opportunistic hackers (i.e. evolution) who delight in clever tricks like writing self–modifying code and relying upon undocumented system quirks”. As a result, deciphering molecular biology is the ultimate dream of a computer scientist.

[^1]: Robbins, R. J., 1992. Challenges in the human genome project. IEEE Engineering in Biology and Medicine, (March 1992):25–34.

## Research Lines
### Evolutionary simulation of transcription factor-binding site interaction principles
Modeling transcription factor-binding site interactions is of vital importance to enhancing the quality of regulatory network inference algorithms and to improving our understanding transcriptional regulation. In spite of this, the most frequently used model for transcription factor binding (the position-specific weight/scoring matrix, or PSSM) has remained virtually unchanged for over 30 years. Furthermore, given the difficulty of generating large and accurate datasets for multiple transcription factors, it is not obvious what assumptions of this basic model should be relaxed or how. We propose to use explicit simulations of the co-evolution of a transcription factor with its target sites in a genomic context to test the validity of different assumptions, such as positional independence, by comparing the evolutionary outcomes obtained with relaxed and constrained models.

### Enhanced motif discovery tools
Conventional motif discovery algorithms rely on the position-specific scoring matrices (PSSM) to model transcription factor-binding motifs. While the binding specificity of well-studied transcription factors can be effectively modeled by assuming positional independence (as in a PSSM), many transcription factors have binding requirements that break this assumption. These include flexible spacer regions between the primary DNA contact dyads and the recognition of structural features of DNA. Research in our lab leverages the power of genetic programming techniques to extract flexible models of co-regulated promoters.

### Comparative genomics of transcriptional regulatory networks
Comparative genomics is a powerful tool to make inferences on the wiring and evolution of transcriptional regulatory networks, but its application to bacterial regulatory networks is still not well standardized and has been only sparingly used in the analysis of bacterial transcription networks. By leveraging a rapidly-growing amount of experimental data on transcription factor-binding sites, here we seek to standardize comparative genomics analyses of regulatory networks in bacteria and to test their effectiveness for the study of network evolution.

### CollecTF
In bacteria, data on transcription factor-binding sites is mostly scattered in model organism-centered databases using different standards and methods. We have developed CollecTF as an open database for transcription-factor binding sites across bacteria. [CollecTF](http://www.collectf.org) compiles data on experimentally validated, naturally occurring TF-binding sites across the Bacteria domain, placing a strong emphasis on the transparency of the curation process, the quality and availability of the stored data and fully customizable access to its records.  Furthermore, CollecTF entries are periodically submitted to NCBI for integration into RefSeq complete genome records as db_xref link-out features embedded in genome annotations, to the EBI as regulon information for UniProtKB entries, and as GO annotations through the Gene Ontology Annotation program of the EBI.

### Metagenomic analysis of regulatory networks
Next-generation sequencing technologies have made it possible to analyze comprehensively the metagenome of microbial communities. Metagenomes provide an extraordinary amount of sequence data on the genetic composition of a bacterial population. Conventional approaches to the analysis of metagenomes have relied on mapping predicted genes onto known pathways. We have shown that known regulatory data and in silico search methods can be leveraged to reconstruct meta-regulons, and we are currently optimizing the bioinformatics pipeline to allow comparing regulatory networks across metagenomes.

### Phage genomics
As part of the [SEA-PHAGES program](https://seaphages.org/), we routinely work with UMBC Phage Hunters to isolate bacteriophages infecting Bacillus and Streptomyces species. Genome analyses of these phages reveal fundamental features about their evolution and their potential use in biocontrol applications.

### Self-adjustable codon bias indices
Codon usage bias (CUB) is a widespread phenomenon in natural organisms, which depart from a uniform usage of codons (triplets of mRNA letters that designate an amino acid in the genetic code). The genes of many organisms show highly biased codon usages that correlate well with their expression levels. Thus, indices that measure CUB are important tools for prediction of gene expression, optimization of gene sequences or assessment of lateral gene transfer (LGT).


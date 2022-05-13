# Functional Classification and Sequence Homology Across Primate Genomes
**Emily M. Liau**  
DSC 3334 Final Project  
*Fendt, Spring 2022*

### Overview

The divergence of human (Homo sapiens) and chimpanzee (Pan troglodytes) ancestors dates back to at least 6.5-7.5 million years ago. Due to their homology, humans and chimpanzees share a large number of conserved sequences. Although recent technologies have improved, it remains difficult to quantify the exact differences between human and chimpanzee genomes based on protein-coding sequences alone. Therefore, comparing the major structural and regulatory genetic alterations that have shaped the biological function of specific DNA sequences could provide insight into human and chimpanzee speciation over time.

In this analysis, our objective is to classify DNA sequences across primate genomes based on their apparent biological function. More specifically, we will analyze DNA sequences from humans and chimpanzees, and attempt to classify these sequences into seven main gene families: 
- **G-protein Coupled Receptors:** membrane proteins used by eukaryotic cells to convert extracellular signals into intracellular responses, such as responses to hormones, neurotransmitters, and external signals
- **Tyrosine Kinase:** enzymes that catalyze the phosphorylation of specific tyrosine residues in target proteins
- **Tyrosine Phosphatase:** enzymes that utilize ATP to regulate signal transduction pathways by catalyzing the dephosphorylation of tyrosine-phosphorylated proteins to reverse the phosphorylation of tyrosine residues
- **Synthetase:** enzymes that catalyze the linking of two molecules using the energy derived from the separation of a pyrophosphate group from a triphosphate
- **Synthase:** enzymes that catalyze the synthesis of new compounds in the body, regardless of energy source
- **Ion Channel:** integral membrane proteins in mammaliam cells that form pores to allow the transport of specific ions by passive diffusion
- **Transcription Factor:** proteins involved in the process of transcribing DNA into RNA

The original dataset contains sequences from both human and chimpanzee genomes, as well as class values that correspond to the functions of the sequences. DNA sequence data is usually stored in FASTA file format, which is a text-based format used to represent nucleotide sequences or amino acid sequences. In FASTA files, nucleotides or amino acids are represented using single-letter codes. Therefore, sequencing data is text-based data, and it is best to use algorithms such as Naive Bayes, in order to perform classification on the DNA sequences.

In this analysis, we apply a Multinomial Naive Bayes Classifier to predict the gene family that characterizes each sequence across both primate species. Comparing the resulting classifications across both primate species of interest will provide an additional perspective into the impact of evolution on sequence homology between humans and chimpanzees over time.

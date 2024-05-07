Background: Protein structure comparative analysis and similarity searches play essential roles in structural bioinformatics. A couple of algorithms for protein structure alignments have been developed in recent years. However, facing the rapid growth of protein structure data, improving overall comparison performance and running efficiency with massive sequences is still challenging. Results: Here, we propose MADOKA, an ultra-fast approach for massive structural neighbor searching using a novel two-phase algorithm. Initially, we apply a fast alignment between pairwise structures. Then, we employ a score to select pairs with more similarity to carry out a more accurate fragment-based residue-level alignment. MADOKA performs about 6–100 times faster than existing methods, including TM-align and SAL, in massive alignments. Moreover, the quality of structural alignment of MADOKA is better than the existing algorithms in terms of TM-score and number of aligned residues. We also develop a web server to search structural neighbors in PDB database (About 360,000 protein chains in total), as well as additional features such as 3D structure alignment visualization. The MADOKA web server is freely available at: http://madoka.denglab.org/ Conclusions: MADOKA is an efficient approach to search for protein structure similarity. In addition, we provide a
parallel implementation of MADOKA which exploits massive power of multi-core CPUs.

This is the implementation of MADOKA protein structure similarity search algorithm. Please refer Paper "MADOKA: an ultra-fast approach for large-scale protein structure similarity searching" for more details.

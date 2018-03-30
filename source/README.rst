survey - k-mer analysis for genomic characteristics
================================================================================

**Survey**, is the estimation of genome features, including genome sizes, repeat content, and heterozygosity, by analyzing k-mer frequency from sequencing reads. The minimal requirement of sequencing depth is **50x**, which can help us correctly calculate the heterozygosity rate.  

Besides, this survey pipeline also do the initial assembly with illumina paired-end reads. On one hand, we can adjust the genome sizes estimated from k-mer analysis since the contig coverage is more stable. On the other hand, the indicators of genome assembly can roughly reflect the complexity of the genome. For example, it will be considered as a simple genome if the initial contig N50 is larger than 1kbp, or a highly repetitive genome if the total size of assembled scaffolds is much less than the estimated genome size. Moreover, we can know whether there is any other contamination in the data of this genome based on the coverage vs GC content curve of contigs.

Comparing to the old pipeline, the **advantages** of our new survey package are as follows:

	(a) Replacing soapKF with jellyfish to count the kmer frequency, greatly save the runtime;
	(b) Optimizing the input mode with a single configuration file and adding more parameters;
	(c) Increasing the program's potability by changing absolute path to relative path;
	(d) Adding necessary notes and help information, as well as a simple run log file;


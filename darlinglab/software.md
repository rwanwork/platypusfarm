---
layout: page
title: Software
permalink: /software/
---

###Current software projects
Our group is currently involved in the following software development projects

[**PhyloSift** - phylogenetic analysis of genomes and metagenomes](http://phylosift.wordpress.org)<br/>
PhyloSift is a re-implementation and extension of the original amphora approach to reconstructing metagenome phylogeny and taxonomy. PhyloSift has several new capabilities, including an ability to quickly process reads generated by next-generation sequencers, an expanded set of phylogenetic marker genes that includes the Archaea, Eukarya, and Viruses, and Bayesian phylogenetic placement of reads using the [pplacer software](http://matsen.fhcrc.org/pplacer).

[**Mauve** - multiple genome alignment](http://darlinglab.org/mauve)<br/>
Mauve is a software tool to compute whole genome multiple alignments among bacteria and small eukaryotic genomes (usually no bigger than Drosophila). The software includes a Java-based visualization module and a set of alignment programs written in C++, available for Linux, Mac, and Windows. Source code is currently available on [sourceforge.net](http://sf.net/p/mauve).

[**A5-miseq** - Andrew and AAron's Awesome Assembly Pipeline (miseq enabled)](http://sf.net/p/ngopt)<br/>
A5-miseq is an updated software pipeline for de novo assembly of microbial isolate genomes from Illumina HiSeq or MiSeq data. It automates all of the usual steps in genome assembly with an easy-to-use interface.

[**STS** - the Sequential Tree Sampler](https://github.com/metatangle/sts)<br/>
Software to update a posterior probability distribution over phylogenies with new sequence data. A collaboration with the [Matsen group](http://matsen.fhcrc.org) at the Fred Hutchinson Cancer Research Center.

###Past software projects
Darling lab members have contributed to the following software projects in the past but are no longer actively participating in these projects.

[**mpiBLAST** - open source parallel BLAST](http://mpiblast.org/)<br/>
mpiBLAST is a parallelization of the popular NCBI BLAST for MPI-based compute clusters. When searching large databases, it can yield super-linear speedups. It is extremely flexible, accommodating cluster architectures with and without shared storage and parallel filesystems. It integrates well with most job scheduling systems and has also been extended to grid architectures.

[**The beagle library** - a library for phylogenetic likelihood calculation on the CPU and GPU](https://code.google.com/p/beagle-lib/)<br/>
libhmsbeagle, also known as the beagle library, is a software development library for calculating phylogenetic likelihoods using a variety of compute hardware types. Currently supported hardware types and features include graphics processing units (GPUs) via CUDA and OpenCL, standard CPUs using SSE for fine-scale parallelism and OpenMP for coarse parallelism, and others. The library works on Linux, Mac, and Windows. Further development on this software is being led by [Daniel Ayres].

[**Repeatoire** – alignment of interspersed genomic repeats](http://wwwabi.snv.jussieu.fr/public/Repeatoire/)<br/>
Software to construct multiple sequence alignments of interspersed repeats directly from raw genomic sequence. This project is led by [Dr. Todd Treangen](http://www.cbcb.umd.edu/~treangen/).

[**ClonalOrigin** – inference of homologous recombination in bacteria using whole genome sequences](http://code.google.com/p/clonalorigin)<br/>
This software implements a Bayesian model of recombination among bacteria. Starting with whole genome sequences aligned with progressiveMauve, this software can reconstruct the probability distribution over historical recombination events among each lineage. From that probability distribution one can compute quantities of interest, such as the rate of gene flow between particular lineages, which parts of the genome have undergone recombination, and more. We have applied this software to investigate speciation in archaea, the chromosomal structure of recombination in Bacillus, and rates of gene flow between pathogenic and commensal E. coli. This software is being maintained by [Xavier Didelot](http://www.xavierdidelot.xtreemhost.com/).

[**barphlye** – Bayesian rearrangement phylogeny in Yersinia](http://bioinformatics.org.au/barphlye)<br/>
barphlye supplements the [BADGER software](http://badger.duq.edu/) to analyze patterns present in ancient genome arrangements. A modified version of BADGER samples reconstructions of inversion phylogeny among a set of related organisms, and barphlye can then detect bias in the reconstructed ancestral genome arrangements. Using barphlye, I was able to discover rearrangement hotspots near the origin of replication in bacterial chromosomes. I was also able to confirm the bias towards “symmetric” inversion in circular bacterial chromosomes. Although Yersinia is in the title, the software can be applied to any bacteria with circular chromosomes, and can even operate on individual linear chromosomes.

[**GenoPlast** – Bayesian inference of genomic plasticity](http://www.xavierdidelot.xtreemhost.com/genoplast.htm)<br/>
Given a Mauve genome alignment, GenoPlast uses a statistical model to infer the baseline rates of gene gain and loss among a group of organisms, along with lineage-specific changes to those rates. Gain and loss are modeled independently. Thus it is possible to detect, for example, a lineage-specific accelerated loss with a constant rate of acquisition that may be characteristic of a recent lifestyle change in bacteria. This project was led by [Xavier Didelot](http://www.xavierdidelot.xtreemhost.com/).

[**Seevolution** – a time machine for evolution](http://seevolution.org/)<br/>
Seevolution is an interactive viewer for mutations occurring during genome evolution. The program is written in Java and uses Java3D. This project was developed by Andres Esteban-Marcos, who was a student I supervised at The Institute for Molecular Bioscience at The University of Queensland.

[**ASAP and the ERIC BRC**](http://asap.ahabs.wisc.edu/asap/home.php)<br/>
ASAP is A Systematic Annotation Package for microbial genomes which is part of the larger Enteropathogen Resource Integration Center project. Together, ERIC and ASAP provide a centralized, web based means to annotate the genomes of enteropathogens and serve as a clearinghouse for all types of annotation and experimental data. ASAP supports a wealth of automated annotation strategies, and its evolution has been described in a series of Nucleic Acids Research papers. ASAP is led by [Nicole Perna](http://genetics.wisc.edu/Perna.htm) and continues to grow at the Genome Evolution Laboratory since my departure.

[**libClustalW** – a C library for Clustal-W 1.83](http://asap.ahabs.wisc.edu/software/software-development-libraries/libclustalw.html)<br/>
The 1.83 release of Clustal-W has been refactored as a C library. It builds in Visual Studio on Windows and on Linux, BSD, and other unices with gcc and automake. Note that the Clustal-W authors have since [made a 2.0 release](http://www.clustal.org/) which represents a complete rewrite of the aligner and which renders this library obsolete.

[**libGenome** – a C++ development library](http://sourceforge.net/projects/libgenome)<br/>
libGenome is an open-source C++ library for reading and writing genome sequence data from common file formats, and also provides functions for basic manipulation of genome sequences. It was designed from the ground-up for speed and efficiency. It is available on sourceforge and also as part of the debian linux distribution.



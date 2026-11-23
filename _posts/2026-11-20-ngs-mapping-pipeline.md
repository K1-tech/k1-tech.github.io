---
title: "[Log #00] From Wet-Lab to Dry-Lab: Why I Started This Archive"
date: 2026-11-19 00:30:00 +0800
categories: Bioinformatics, Study-Log
tags: bioinformatics, computational-biology, learning-log, wet-to-dry
---
 *"Tell me and I forget, teach me and I may remember, involve me and I learn."* - Benjamin Franklin -

Until recently, my world in my major was strictly **wet-lab**: pipettes, agar plates, molecular biology, and microbiology, which I learned mainly in Biotechnology Core Techniques(生物技術核心實驗) 2025 [juang.bst.ntu.edu.tw/BCT/Miscell/introduction.htm](http://juang.bst.ntu.edu.tw/BCT/Miscell/introduction.htm)

Coding and command-line interfaces felt like an entirely different universe. That changed in the **Fall 2026 semester** when I took an **Bioinformatics** course. Processing gigabytes of genomic sequences instead of microliters of reagents opened up a completely new perspective and made me realize I want to dive much deeper into **Computational Biology**. However, biological data pipelines are dense, and human memory is notably leaky. I am launching this blog series as an external hard drive for my brain: a personal reference log to review, break down, and eventually master what I learn.

 What This Series Will Cover I won't be posting on a designative schedule just whenever I have time to dissect a new concept or run an experiment. The rough roadmap covers five core pillars: 

* **Environment & Data Formats:** WSL2/Linux setups, CLI survival tricks, and decoding raw file structures `FASTA`, `FASTQ`, `SAM/BAM`, `VCF`). 

* **Sequence Alignment & Search:** The math and heuristics behind Needleman-Wunsch, Smith-Waterman, BLOSUM matrices, BLAST, and modern high-speed alternatives like MMseqs2. 

* **NGS Read Mapping & Variant Calling:** Quality control `fastp`), Burrows-Wheeler Transform `BWA`), `Samtools`, and identifying SNPs/Indels `GATK`). 

* **De Novo Genome Assembly:** Overcoming repetitive regions with long-read sequencing, k-mer genome size estimation, and De Bruijn graphs. 

* **Phylogenetics & Functional Annotation:** Multiple sequence alignment, evolutionary trees, and tapping into databases like NCBI and UniProt.

 ---

Ground Rules for This Archive To keep this log practical, ethical, and honest, I am setting three ground rules: 

1. **Public Raw Data Only (Zero Copyright Issues):** The lecture materials I studied from were massive, but copying slides or proprietary datasets is off-limits. Instead, every workflow documented here will be rebuilt from scratch using publicly available raw datasets from **NCBI SRA**, **UniProt**, or **ENA**. 

2. **AI-Assisted Coding:** Transitioning into computational biology requires writing Python, R, and Bash scripts. Although I learned some basic coding during high school but still remain limited, So I will actively leverage AI tools as a pair-programmer to debug syntax and accelerate pipeline building, focusing my energy on understanding the underlying biological logic and algorithms. 

3. **A Living Undergraduate Draft:** I am still an undergraduate student, not a tenured bioinformatician or graduate degree student. My current understanding isn't 100% bulletproof. Think of these posts as version `0.1` drafts, I will continuously update and patch them as my background knowledge grows. 

Time to start with **Log #01** on next post.
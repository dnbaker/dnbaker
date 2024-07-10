### Hi, I'm Daniel 👋

Software Engineer at Roche. Previously, I was a Senior Scientist at Pacific Biosciences (PacBio) after earning my PhD at [Johns Hopkins University](https://jhu.edu) in the department of [Computer Science](https://cs.jhu.edu).
Before that I was a Bioinformatics Scientist at ARUP Laboratories, where I worked on
cell-free circulating tumor DNA (_ctDNA_) analysis and clinical genomics after my training
in Physics [BS] and Biophysics/Computational Biology [MS].
I've worked with biological data (sequence, molecular modeling, metabolomics, transcriptomics, metagenomics), telecommunications data, as well as graph algorithms, machine learning, and numerical optimization.

🔭 I've worked on similarity search, and clustering, and indexing for large-scale biological data, simd/gpu-accelerated and randomized algorithms.
   Most recently, I've been developing methods for human genetics, including long RNA-seq, VNTRs, and haplotype phasing.

😄 Pronouns: He/Him/His

#### A quick tour of my interests

1. Practical randomized algorithms

This ranges from libraries providing [sketch data structures](https://github.com/dnbaker/sketch) and [coresets](https://github.com/dnbaker/minicore),
as well as projects using [random projections](https://github.com/dnbaker/frp) and [DCI](https://github.com/dnbaker/DCI).

My work on coresets and clustering is primarily part of the [minicore](https://github.com/dnbaker/minicore) project, with the aims
of providing a standard utility for coreset construction and weighted clustering, especially for exponential family models and shortest-paths metrics.

2. Computational Biology

The [bonsai](https://github.com/dnbaker/bonsai) project provides methods for __metagenomic__ analysis,
along with k-mer encoding/decoding and I/O, while the [Dashing](https://github.com/dnbaker/dashing2) performs scalable
sketching and comparison of sequence data.

[BMFtools](https://github.com/dnbaker/bmftools) performs molecular demultiplication over sequencing barcoded data, reducing error rates while eliminating redundant information.
Designed for ctDNA, this method can reduce error rates by orders of magnitude, allowing confident detection of very rare events.

[scavenger](https://github.com/dnbaker/scavenger) has rust implementations using tch-rs for VAEs for count-based data, applied to single-cell transcriptomics.

I also co-developed [pbfusion](https://github.com/PacificBiosciences/pbfusion), a fast tool for characterizing transcriptional abnormalities.

3. General C++

Most of my projects fall into this category, serving as tools I can reuse in various projects.

Some of my favorites:

- [vec](https://github.com/dnbaker/vec) provides type-generic abstractions over x86-64 vectorization, making it easy to write fast, portable code.
- [kspp](https://github.com/dnbaker/kspp) is an RAII-based variant of kstring from [klib](https://github.com/attractivechaos/klib) with extra niceties making appending printf-style formatting easy.
- [aesctr](https://github.com/dnbaker/aesctr) provides STL-style random number generators built on fast aes-ctr and wyhash
- [circularqueue](https://github.com/dnbaker/circularqueue) provides a range-based circular queue container that uses power-of-two sizes
  

<!--
**dnbaker/dnbaker** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

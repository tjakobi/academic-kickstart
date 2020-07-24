---
title: "Large-scale compression of genomic sequence databases with the Burrows-Wheeler transform"
date: 2012-05-01
publishDate: 2020-07-24T16:41:43.908808Z
authors: ["Anthony J. Cox", "Markus J. Bauer", "Tobias Jakobi", "Giovanna Rosone"]
publication_types: ["2"]
abstract: "MOTIVATION: The Burrows-Wheeler transform (BWT) is the foundation of many algorithms for compression and indexing of text data, but the cost of computing the BWT of very large string collections has prevented these techniques from being widely applied to the large sets of sequences often encountered as the outcome of DNA sequencing experiments. In previous work, we presented a novel algorithm that allows the BWT of human genome scale data to be computed on very moderate hardware, thus enabling us to investigate the BWT as a tool for the compression of such datasets.  RESULTS: We first used simulated reads to explore the relationship between the level of compression and the error rate, the length of the reads and the level of sampling of the underlying genome and compare choices of second-stage compression algorithm. We demonstrate that compression may be greatly improved by a particular reordering of the sequences in the collection and give a novel 'implicit sorting' strategy that enables these benefits to be realized without the overhead of sorting the reads. With these techniques, a 45× coverage of real human genome sequence data compresses losslessly to under 0.5 bits per base, allowing the 135.3 Gb of sequence to fit into only 8.2 GB of space (trimming a small proportion of low-quality bases from the reads improves the compression still further). This is textgreater4 times smaller than the size achieved by a standard BWT-based compressor (bzip2) on the untrimmed reads, but an important further advantage of our approach is that it facilitates the building of compressed full text indexes such as the FM-index on large-scale DNA sequence collections.  AVAILABILITY: Code to construct the BWT and SAP-array on large genomic datasets is part of the BEETL library, available as a github repository at https://github.com/BEETL/BEETL."
featured: false
publication: "*Bioinformatics*"
tags: ["DNA", "Genome", "Humans", "Algorithms", "Genomics", "Genomics: methods", "Computer Simulation", "Sequence Analysis", "Nucleic Acid", "Databases", "Human", "Data Compression", "Data Compression: methods", "Escherichia coli", "Escherichia coli: genetics"]
url_pdf: "http://www.ncbi.nlm.nih.gov/pubmed/22556365"
doi: "10.1093/bioinformatics/bts173"
---


---
title: "Comparing DNA Sequence Collections by Direct Comparison of Compressed Text Indexes"
date: 2012-01-01
publishDate: 2020-07-25T22:13:13.726264Z
authors: ["Anthony J. Cox", "Tobias Jakobi", "Giovanna Rosone", "Ole B. Schulz-Trieglaff"]
publication_types: ["1"]
abstract: "Popular sequence alignment tools such as BWA convert a reference genome to an indexing data structure based on the Burrows-Wheeler Transform (BWT), from which matches to individual query sequences can be rapidly determined. However the utility of also indexing the query sequences themselves remains relatively unexplored.Here we show that an all-against-all comparison of two sequence collections can be computed from the BWT of each collection with the BWTs held entirely in external memory, i.e. on disk and not in RAM. As an application of this technique, we show that BWTs of transcriptomic and genomic reads can be compared to obtain reference-free predictions of splice junctions that have high overlap with results from more standard reference-based methods.Code to construct and compare the BWT of large genomic data sets is available at http://beetl.github.com/BEETL/ as part of the BEETL library."
featured: false
publication: "*Algorithms in Bioinformatics*"
tags: ["External Memory", "Junction Site", "Short Read Alignment", "Splice Junction", "Tasmanian Devil"]
url_pdf: "https://doi.org/10.1007/978-3-642-33122-0_17"
doi: "10.1007/978-3-642-33122-0_17"
---


# Oyster Pathogen WRI Project
Analysis of oyster microbiomes for the WRI Oyster Pathogen project. Reads were generated by Oxford Nanopore MinIon. Long read amplicons stretch the entire ribosomal RNA operon. Quality control and filtering done with [Nanoplot](https://github.com/wdecoster/NanoPlot) and [Nanofilt](https://github.com/wdecoster/nanofilt). Annotation made with [MIrROR](https://github.com/seoldh/MIrROR). Further exploratory analyses done with [phyloseq](https://github.com/joey711/phyloseq) and [vegan](https://cran.r-project.org/web/packages/vegan/vegan.pdf).

[DNA_extraction_protocol.Rmd](https://lizsuter.github.io/files/DNA_extraction_protocol.nb.html) is a notebook that walks through the DNA extraction steps.
[OysterPathogenWRI.html](https://lizsuter.github.io/files/OysterPathogenWRI.html) is a Jupyter notebook that does the read quality filtering and annotation with MIrROR.
[OysterPathogenWRI.nb.html](https://lizsuter.github.io/files/OysterPathogenWRI.nb.html) is an R markdown notebook that goes through the exploratory analysis (diversity, plotting, etc).
# hoodscanR: Cellular neighborhoods scanning from spatial transcriptomics data in R <img src="man/figures/hoodscanR_sticker.png" align="right" alt="" width="120" />

[![R-CMD-check](https://github.com/DavisLaboratory/hoodscanR/workflows/R-CMD-check-bioc/badge.svg)](https://github.com/DavisLaboratory/hoodscanR/actions)
[![Coverage status](https://codecov.io/gh/DavisLaboratory/hoodscanR/branch/devel/graph/badge.svg)](https://app.codecov.io/gh/DavisLaboratory/hoodscanR?branch=devel)



Install released version from Bioconductor

```
if (!require("BiocManager", quietly = TRUE))
    install.packages("BiocManager")

BiocManager::install("hoodscanR")
```


Install development version from GitHub

```
library(devtools)
devtools::install_github("DavisLaboratory/hoodscanR")
```

## Citation

If you use hoodscanR in your research, please cite:

Liu N, Martin J, Bhuva DD, et al. (2026). hoodscanR: profiling single-cell
neighborhoods in spatial transcriptomics data. *Bioinformatics*, 42(8), btag609.
[doi:10.1093/bioinformatics/btag609](https://doi.org/10.1093/bioinformatics/btag609).

To obtain the citation and BibTeX entry in R, run:

```r
citation("hoodscanR")
```


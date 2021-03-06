# NN FLUXNET

[![DOI](https://zenodo.org/badge/95237025.svg)](https://zenodo.org/badge/latestdoi/95237025)

This repository contains all R code to reproduce the analysis used for the paper *Quantifying soil moisture control on light use efficiency across biomes*.

A detailed description of the scope, method, and algorithms is given by the RMarkdown file `knit_nn_fluxnet2015.Rmd`. 

To get this repository, change into a suitable directory and clone by
```bash
cd <suitable-working-direcotry>
git clone https://github.com/stineb/nn_fluxnet2015.git .
```

To render the RMarkdown file, execute all code, and thereby fully reproduce all analysis, simply enter the following command in RStudio (after making sure the 'rmarkdown' package is installed):
```r
install.packages("rmarkdown", type = "source")
rmarkdown::render_site()
```

Please also note the data use policy, described in `./knit_nn_fluxnet2015.Rmd` and `./LICENSE`. When using this code, please cite the paper Stocker et al. (2018) *New Phytologist*.
This code is also available on [Zenodo](https://zenodo.org/record/1181691#.WrN9xJPwbUI), where the latest version corresponds to tag `submission_3 `.

beni stocker, 27.6.2017
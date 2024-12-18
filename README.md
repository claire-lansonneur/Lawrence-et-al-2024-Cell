# Lawrence-et-al-2024-Cell

This repository contains the code needed to reproduce bioinformatics results and plots in the paper from

## [Microglia maintain structural integrity during fetal brain morphogenesis (*Cell*)](https://doi.org/10.1016/j.cell.2024.01.012)

> Akindé René Lawrence, Alice Canzi, Cécile Bridlance, Nicolas Olivié, Claire Lansonneur, et al. Microglia maintain structural integrity during fetal brain morphogenesis. *Cell*, 2024, 187(4), pp.962-980.e19. 10.1016/j.cell.2024.01.012.

Available at: <https://doi.org/10.1016/j.cell.2024.01.012>

## Code

Analysis was performed in the paper as described, in R.

- Figure 1A-D
- Figure S1
- Figure S4
- Table S1

## Public datasets

scRNA-seq microglia data analyses contain public available data from:

| **Publication**                                                | **Accession**                                      | **Sequencing technology** | **Number of cells** | **Microglia state reported**      |
| -------------------------------------------------------------- | -------------------------------------------------- | ------------------------- | ------------------- | --------------------------------- |
| [Hammond et al. 2019 *Immunity*](https://doi.org/10.1016/j.immuni.2018.11.004) | GEO: GSE121654 & authors                           | 10X 3’ Chromium v1, v2    | 76,149              | ATM: 2,517                        |
| [Li et al. 2019 *Neuron*](https://doi.org/10.1016/j.neuron.2018.12.006)        | GEO: GSE123025 & authors                           | Smart-seq2                | 1,816               | PAM: 228                          |
| [La Manno et al. 2021 *Nature*](https://doi.org/10.1038/s41586-021-03775-x)    | <http://mousebrain.org/development> (“dev_all.loom”) | 10X Chromium v2           | 1,711               | ATM-like: 510     Cycling MG: 415 |
-------------------------------------------------------------------------------------------------

<sup>Metadata was requested from Hammond et al. (2019) and Li et al. (2019).</sup>
<sup>A repository is now available for the pseudo-object from [Hammond et al. (2019)](https://github.com/samuel-marsh/Hammond-et-al_2019_Microglia_scRNAseq).</sup>

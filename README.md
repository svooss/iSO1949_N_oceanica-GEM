## iSO1949_N_oceanica-GEM: Genome-scale metabolic model of an industrial oleagionous microalga.

[![Zenodo](https://zenodo.org/badge/1065827.svg)](https://zenodo.org/records/10658527)  

#### Description

Genome-scale constraint-based metabolic model (GEM) of the oleaginous microalga Nannochloropsis oceanica. Build through orthology-based reconstruction with AuReMe, using the scaffold GEMs iCre1355 (Chlamyomonas reinhardtii), iLB1027_lipid (Phaeodactylum tricornutum), iRJ1321 (Microchloropsis gaditana) and iNS934 (Microchloropsis salina). Specifically curated on the lipid metabolism of N. oceanica. Contains two 'light acclimation modes', based on continuous steady state cultures acclimated to low light and high light. We used the biomass compositions and oxygen-based photosynthesis-irradiance (PI) curves to set the biomass equation and the non-growth associated maintenance rates. The GEM can predict the effect of light acclimation on CO2-based PI-curves.

Developed by the Bioprocess Engineering (BPE) department and the laboratory of Systems and Synthetic Biology (SSB) of the Wageningen University and Research. Additional information available upon request.

#### Citation

{{ provide the citation once available, for example:
  > Lu, H., Li, F., Sánchez, B.J. et al (2019). A consensus S. cerevisiae metabolic model Yeast8 and its ecosystem for comprehensively probing cellular metabolism. Nat Commun 10, 3586 [doi:10.1038/s41467-019-11581-3](https://doi.org/10.1038/s41467-019-11581-3)

}}


#### Keywords

> Keywords are be separated by semicolons.
> The `Model source` field contains the source(s) of the current model, eg existing GEMs. If possible, use the Markdown format to add the URL with the DOI. The (NCBI) taxonomy ID should be provided in the [format from identifiers.org](https://registry.identifiers.org/registry/taxonomy). For the genome identifier, please provide the ENA/GenBank/RefSeq identifier via *identifiers.org*, or from other sources such as PATRIC or KBase.  

**Utilisation:** Experimental data reconstruction; _in silico_ strain design; model template  
**Field:** Metabolic-network reconstruction, Microalgal biotechnology  
**Type of model:** Reconstruction; curated  
**Model source:** [iNS934](http://doi.org/10.1186/s12918-017-0441-1); [iRJ1321](http://doi.org/10.1016/j.algal.2017.08.014); [iLB1027_lipid](http://doi.org/10.1371/journal.pone.0155038); [iCre1355](http://doi.org/10.1111/tpj.13059)  
**Omic source:** Genomics ; lipidomics  
**Taxonomic name:** _Nannochloropsis oceanica_  
**Taxonomy ID:** [taxonomy:1333499](https://identifiers.org/taxonomy:1333499)  
**Genome ID:** [NoIMET1v2]([http://nandesyn.single-cell.cn/analysis/7)  
**Metabolic system:** General metabolism ; lipid metabolism; photosynthesis mechanisms; photoacclimation; pigment metabolism.  
**Bioreactor:**   Photobioreactors in steady state cyclostat (no dilution during night (8h), constant dilution during the day (16h))
**Strain:** IMET1  
**Condition:** High light acclimated (I_ph,0 of 600 µmol/m2/s); Low light acclimated (I_ph,0 of 200 µmol/m2/s), artificial seawater (ASW).  


### Installation

You can obtained the model by any of the following methods:

If you have a Git client installed on your computer, you can clone the main branch of the iSO1949_N_oceanica-GEM repository.
You can directly download the latest release as a ZIP file.
If you want to contribute to the development of iSO1949_N_oceanica-GEM (see below), it is best to fork the iSO1949_N_oceanica-GEM repository to your own Github account.

Model can be used with any GEM reading tool, such as COBRA or COBRApy.

## Obtain model

You can obtained the model by any of the following methods:
1. If you have a Git client installed on your computer, you can clone the [`main`](https://github.com/svooss/iSO1949_N_oceanica-GEM) branch of the yeast-GEM repository.
2. You can directly download [the latest release](https://github.com/svooss/iSO1949_N_oceanica-GEM/releases) as a ZIP file.
3. If you want to contribute to the development of yeast-GEM (see [below](#below)), it is best to [fork](https://github.com/svooss/iSO1949_N_oceanica-GEM/fork) the iSO1949_N_oceanica repository to your own Github account.

## Required software

### Basic user

If you want to use the model for your own model simulations, you can use **any software** that accepts SBML L3V1 FBCv3 formatted model files. This includes any of the following:
* MATLAB-based
  * [RAVEN Toolbox](https://github.com/SysBioChalmers/RAVEN) version 2.8.3 or later (recommended)  
  * [COBRA Toolbox](https://github.com/opencobra/cobratoolbox)

* Python-based
  * [cobrapy](https://github.com/opencobra/cobrapy)  

Please see the installation instructions for each software package.

### Contributing

Contributions are always welcome! Please read the [contributing guideline](.github/CONTRIBUTING.md) to get started.


### Contributors

Code contributors are reported automatically by GitHub under [Contributors](https://github.com/svooss/iSO1949_N_oceanica-GEM/graphs/contributors), while other contributions come in as [Issues](https://github.com/iSO1949_N_oceanica-GEM/issues).

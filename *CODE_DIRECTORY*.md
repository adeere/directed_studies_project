---
jupytext:
  text_representation:
    extension: .md
    format_name: myst
    format_version: 0.13
    jupytext_version: 1.11.1
kernelspec:
  display_name: Python 3
  language: python
  name: python3
---

# Code Directory

+++

* All of my final code is in `/data_share/alison_448`
* Intermediate work/files is located in `/data_share/alison_448/intermediate_work`
* Figures are located in `/data_share/alison_448/figures`

+++

## Polar Plots

Polar plot code is in the following files: 
* `polar_plots_cccma.ipynb`: code creates 5 by 8 plot of all ensembles CanESM5 model polar plots, and 3 by 6 plots of each decade for one ensemble.
* `polar_plots_mohc-hadgem3-gc31-ll.ipynb`: code creates 4 by 1 plot of HadGEM3-GC31-LL model polar plots
* `polar_plots_mohc-hadgem3-gc31-mm.ipynb`: code creates 4 by 1 plot of HadGRM3-GC31-MM model polar plots
    * Note: Not used in this project. Code is an older version, not finalized for the report. 
* `polar_plots_UKESM1-0-LL.ipynb`: code creates 4 by 2 plot of UKESM historic model polar plots
    * Note: Not used in this project. Code is an older version, not finalized for the report.

+++

## Animations 
* The animations were created for the presentation and were not used for the report.

Animation code is in the following files: 
* `animation_cccma_historic.ipynb`: Create animation for historic CanESM5 model simulation
* `animation_cccma-ssp45.ipynb`: Create animation for CanESM5 model scenario SSP2-45
* `animation_cccma-ssp85.ipynb`: Create animation for CanESM5 model scenario SSP5-85
* `animation_hadgem-ll_historic.ipynb`: Create animation for historic CHadGEM3-GC3.1-LL model simulation
* `animation_hadgem_LL-ssp45.ipynb`: Create animation for HadGEM3-GC3.1-LL model scenario SSP2-45
* `animation_hadgem_LL-ssp85.ipynb`: Create animation for HadGEM3-GC3.1-LL model scenario SSP5-85

+++

## Estimating Natural Variability

Estimating natural variability code is in the folowing files: 
* `estimating_natural_variability_cccma_historical.ipynb`: create figures of ensemble means and area-weighted yearly mean of sea-ice thickness (historical model CanESM5)
* `estimating_natural_variability_HadGEM3-GC31-LL_historical.ipynb`: create figures of ensemble mean and area-weighted yearly mean of sea-ice thickness (histoircal model Hadgem3-gc31-LL)
* `estimating_natural_variability_HadGEM3-GC31-MM_historical.ipynb`: create figures of ensemble mean and area-weighted yearly mean of sea-ice thickness (histoircal model Hadgem3-gc31-MM)
    * Note: Not used in this project. Code is an older version, not finalized for the report   

* `comparing_hadgem_canesm5.ipynb`: create figure of a qualitative comparison of CanESM5 and HadGEM3-GC3.1-LL models
* `comparing_ssp45_ssp85.ipynb`: create figure to compare the two emissions scnearios (SSP2-45 and SSP5-85 scenarios) for the CanESM5 model

+++

## Taylor Diagrams

Taylor Diagram code is in the following files: 
* `sm_taylor_diagram_cccma_historical.ipynb`: create taylor diagram of CanESM5 ensemble members, compare with one ensemble member from HadGEM3-GC3.1-LL
    * Note:  `sm_taylor_diagram_hadgem3-gc31-ll_historical.ipynb` must be run first
    
    <br>
    
* `sm_taylor_diagram_hadgem3-gc31-ll_historical.ipynb`: create taylor diagram of HadGEM3-GC3.1-LL ensemble members
    * Note: run`sm_taylor_diagram_cccma_historical.ipynb` can be run afterwards to compare one ensemble member from the HadGEM3-GC3.1-LL with Canadian model
    
     <br>
     
* `sm_taylor_diagram_cccma-ssp45.ipynb`: create taylor diagram for the SSP2-45 scenario of CanESM5 ensemble members, compare with one ensemble member from HadGEM3-GC3.1-LL.
    * Note: `sm_taylor_diagram_mohc_hadgem3-gc31-ll-spp45.ipynb` must be run first
        
     <br>
     
* `sm_taylor_diagram_mohc_hadgem3-gc31-ll-ssp45.ipynb`: set up HadGEM3-GC3.1-LL so that it can be run with the CanESM5 taylor diagram to compare the output from the future scenario SSP5-45.
    * Note: run`sm_taylor_diagram_cccma-ssp45.ipynb` can be run afterwards to compare one ensemble member from the HadGEM3-GC3.1-LL with Canadian model (SSP2-45 scenario)
    
    <br>
    
* `sm_taylor_diagram_mohc_hadgem3-gc31-ll-ssp85.ipynb`: set up HadGEM3-GC3.1-LL so that it can be run with the CanESM5 taylor diagram to compare the output from the future scenario SSP5-85.
    * Note: run`sm_taylor_diagram_cccma-ssp85.ipynb` can be run afterwards to compare one ensemble member from the HadGEM3-GC3.1-LL with Canadian model (SSP5-85 scenario)
    
    <br>

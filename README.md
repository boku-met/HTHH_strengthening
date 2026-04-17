[![Python 3.7](https://img.shields.io/badge/python-3.6-blue.svg)](https://www.python.org/downloads/release/python-369/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

# Was the strengthening of the Northern polar vortex in 2024/2025 associated with the Hunga Tonga eruption? 

 **[Ales Kuchar](https://github.com/kuchaale), Matthias Stocker, Alistair Bell, [Bruno Lehner](https://github.com/brunolehner), [Jessica Kult-Herdin](https://github.com/Jevare), Gabriel Chiodo, Timofei Sukhodolov, Eugene Rozanov, Gunter Stober, and Harald E. Rieder**

Submitted to [ACP](https://egusphere.copernicus.org/preprints/2026/egusphere-2026-406/).

Code used to process and visualise the model and other data outputs in order to reproduce figures in the manuscript.
Model data are available [here](?). All datasets already preprocessed can be found [here](?).

Notebooks for each individual figure as well as for two data tables are in the [`code/` directory](code), while the figures themselves are in the [`plots/` directory](plots).

### Figures
|  #  | Figure                                                                                                                                                                                                    | Notebook                                                                              | Dependencies                                                                                                                                                             |
|:---:|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:--------------------------------------------------------------------------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|  1 | [Composites documenting vortex morphology](plots/PVmoments_lagA_composite_20days_poster.pdf)                                                                              | [moment_calculation_distribution_in_CMAM30-sd_composites.ipynb](code/moment_calculation_distribution_in_CMAM30-sd_composites.ipynb)                       |   [uref_calculation_CMAM.ipynb](code/uref_calculation_CMAM.ipynb), [uref_ration_validation.ipynb](code/uref_ration_validation.ipynb), [moments_fast_example.py](code/moments_fast_example.py), [vor_fast_setup.py](https://github.com/wseviour/vortex-moments/blob/master/vor_fast_setup.py), [vor_fast.py](https://github.com/wseviour/vortex-moments/blob/master/vor_fast.py)                                                                                                                               |
|  2 | [Composite anomalies of NAM](plots/NAM_lagA_composite_HIonly_FDR.pdf)                                                      | [NAM_lagA.ipynb](code/NAM_lagA.ipynb)                 |                                                                                                                           |
|  3 | [Conditional probabilities that NAM is less or equal -1](plots/NAM_lagA_probability_10hPa_CI.pdf)                | [NAM_lagA.ipynb](code/NAM_lagA.ipynb)|                                                                                              |
|  4 | [Composite anomalies of Eliassen-Palm flux](plots/EPflux-analysis_Himalayas_anomalies_20days_zm_wEPFDsignificancetropopause_DJFonly_pvalue005_lags0357_FDR.pdf)                                               | [GRL_reproduce_Fig1_Himalayas_lagA.ipynb](code/GRL_reproduce_Fig1_Himalayas_lagA.ipynb)                     |                                                                        |
|  5 | [LWA composite at 18 km](plots/LWA_anomalies_lagA_FDR.pdf)                                                                                      | [LWA_anomalies_CMAM.ipynb](code/LWA_anomalies_CMAM.ipynb)                           |                                                                                                                    |
|  6 | [Composites of anomalies documenting evolution total column ozone for CMAM](plots/TO3_anomalies_lagA_FDR.pdf) | [toz_anomalies_CMAM.ipynb](code/toz_anomalies_CMAM.ipynb)                     |       [composite_example_ERA5.py](code/composite_example_ERA5.py)                                                                                                                     |
|  7 | [Effective_diffusivity composite at 450 K](plots/effective_diffusivity_HI-composite@450K_pv_FDR-xcontour.pdf)                                                                                      | [effective_diffusivity_HI_composite-pv-xcontour.ipynb](code/effective_diffusivity_HI_composite-pv-xcontour.ipynb)                           |                 [xcontour_isoentropic_CMAM-script.py](code/xcontour_isoentropic_CMAM-script.py)                                                                                                       |
|  8 | [Composite anomalies of refractive index and zonally averaged OGWD](plots/OGWDzm+refr_lagA_composite_CI_daily.pdf)                                                  | [OGWD+refr_index_himalayas_composite_lagA.ipynb](code/OGWD+refr_index_himalayas_composite_lagA.ipynb)               |   [refraction_index_calc.py](code/refraction_index_calc.py)                                                                                                                        |


#### Appendix figures
|  #  | Figure                                                                                                                                                                                                    | Notebook                                                                              | Dependencies                                                                                                                                                             |
|:---:|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:--------------------------------------------------------------------------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|  A1 | [Explained variance of NAM time series.](plots/NAM_explained_variance.pdf)                                               | [NAM_CMAM_variance.ipynb](code/NAM_CMAM_variance.ipynb)                     | |
                                                                                                                             
                                                  



    
    
### Auxiliar notebooks:
- [?.ipynb](code/?.ipynb) + ?



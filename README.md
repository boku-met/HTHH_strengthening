[![Python 3.7](https://img.shields.io/badge/python-3.6-blue.svg)](https://www.python.org/downloads/release/python-369/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

# Was the strengthening of the Northern polar vortex in 2024/2025 associated with the Hunga Tonga eruption? 

 **[Ales Kuchar](https://github.com/kuchaale), Matthias Stocker, Alistair Bell, [Bruno Lehner](https://github.com/brunolehner), [Jessica Kult-Herdin](https://github.com/Jevare), Gabriel Chiodo, Timofei Sukhodolov, Eugene Rozanov, Gunter Stober, and Harald E. Rieder**

Submitted to [ACP](https://egusphere.copernicus.org/preprints/2026/egusphere-2026-406/).

Code used to process and visualise the model and other data outputs in order to reproduce figures in the manuscript.
Any direct access to full simulation data can be arranged by contacting the authors. All datasets already preprocessed can be found [here](https://data.mendeley.com/preview/hb3whw3nfr).

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
|  A1 | [Globally averaged water vapour anomalies](plots/Fig_A1_h2o_anom_socol_MLS_SWOOSH.pdf)                                               | [NAM_CMAM_variance.ipynb](code/NAM_CMAM_variance.ipynb)                     | |
|  A2 | [Monthly zonal-mean anomalies of polar chemistry for the period 2023/2024](plots/polar-chemistry_2023-2024.pdf)                                               | [NAM_CMAM_variance.ipynb](code/NAM_CMAM_variance.ipynb)                     | |
|  A3 | [As Fig. 2 but for the extended winter 2025/2026](plots/TE+WV+O3_time-evolution_2025-09-2026-03_MLSv6_anom-int_significance.pdf)                                               | [NAM_CMAM_variance.ipynb](code/NAM_CMAM_variance.ipynb)                     | |
|  A4 | [As Fig. 2 but for the extended winter 2023/2024](plots/TE+WV+O3_time-evolution_2023-09-2024-03_MLSv6_anom-int_significance.pdf)                                               | [NAM_CMAM_variance.ipynb](code/NAM_CMAM_variance.ipynb)                     | |
|  A5 | [RRTMG radiative heating rates (longwave, shortwave and their sum) for prescribed WV and O3](plots/MLS_RRTMG_2024-09--2025-03.pdf)                                               | [NAM_CMAM_variance.ipynb](code/NAM_CMAM_variance.ipynb)                     | |
|  A6 | [Weighted zonally-average over 60◦–90◦N of clear-sky (offline) longwave heating rate anomalies](plots/2xHR+WV_time-evolution_2023-2024.pdf)                                               | [NAM_CMAM_variance.ipynb](code/NAM_CMAM_variance.ipynb)                     | |
|  A7 | [Scatter plot of equatorial zonal wind at 10 hPa as a proxy for QBO](plots/QBO@10hPa_vs_SOI_SOCOLw-only_colored_seaborn.pdf)                                               | [NAM_CMAM_variance.ipynb](code/NAM_CMAM_variance.ipynb)                     | |
|  A8 | [Daily zonal-mean zonal wind at 10 hPa and 60◦N based on SOCOLv4 for the period 2024/2025](plots/ZW_cluster_202410-202502.pdf)                                               | [NAM_CMAM_variance.ipynb](code/NAM_CMAM_variance.ipynb)                     | |
|  A9 | [Monthly anomaly of sea level pressure (in hPa) in February 2025 ](plots/SLP_map_cluster_2025_Feb.pdf)                                               | [NAM_CMAM_variance.ipynb](code/NAM_CMAM_variance.ipynb)                     | |
|  A10 | [Weighthed zonally-average over 60◦–90◦N of age of air](plots/AoA_time-evolution_2023-2024.pdf)                                               | [NAM_CMAM_variance.ipynb](code/NAM_CMAM_variance.ipynb)                     | |

                                                                                                                             
                                                  



    
    
### Auxiliar notebooks:
- [?.ipynb](code/?.ipynb) + ?



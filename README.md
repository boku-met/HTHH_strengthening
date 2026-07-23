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
|  1 | [ZMZW at 10 hPa 60N and EHF at 100 hPa for the extended winter 2024/2025](plots/Fig1_ZW+EHF_MERRA2.pdf)                                               | [Fig1_reproduction.ipynb](code/Fig1_reproduction.ipynb)                     | |
|  2 | [Globally averaged water vapour anomalies](plots/Fig_A1_h2o_anom_socol_MLS_SWOOSH.pdf)                                               | [260416_Fig_A1_SWV.ipynb](code/260416_Fig_A1_SWV.ipynb)                     | |
|  3 | [Polar-cap average for WV, O3 and temperature for the extended winter 2024/2025 (MLS)](plots/TE+WV+O3_time-evolution_2024-09-2025-03_MLSv6_anom-int_significance.pdf)                                               | [MLS_significance_visualization.ipynb](code/MLS_significance_visualization.ipynb)                     | |
|  4 | [As Fig. 3 but for the extended winter 2023/2024](plots/TE+WV+O3_time-evolution_2023-09-2024-03_MLSv6_anom-int_significance.pdf)                                               | [MLS_significance_visualization.ipynb](code/MLS_significance_visualization.ipynb)                     | |
|  5 | [Polar-cap average for WV, O3, temperature and ZMZW for the extended winter 2023/2024 (SOCOL)](plots/TE+U+WV+O3_time-evolution_2023-2024.pdf)                                               | [HT_ta_WV_SOCOL.ipynb](code/HT_ta_WV_SOCOL.ipynb)                     | |
|  6 | [As Fig. 5 but for the extended winter 2024/2025 (SOCOL)](plots/TE+U+WV+O3_time-evolution_2024-2025.pdf)                                               | [HT_ta_WV_SOCOL_2024-2025.ipynb](code/HT_ta_WV_SOCOL_2024-2025.ipynb)             
|  7 | [Monthly zonal-mean anomalies of polar chemistry for the period 2023/2024](plots/polar-chemistry_2023-2024.pdf)                                               | [NOx_HOx_Clx_23-24.ipynb](code/NOx_HOx_Clx_23-24.ipynb)                     | |
|  8 | [Weighted zonally-average over 60◦–90◦N of age of air](plots/AoA_time-evolution_2023-2024.pdf)                                               | [NAM_all-winters.ipynb](code/NAM_all-winters.ipynb)                     | |
|  9 | [RRTMG radiative heating rates (longwave, shortwave and their sum) for prescribed WV and O3](plots/MLS_RRTMG_2024-09--2025-03.pdf)                                               | [konrad_RRTMG_MLS_SOCOL-final.ipynb](code/konrad_RRTMG_MLS_SOCOL-final.ipynb)                     | |
|  10 | [Weighted zonally-average over 60◦–90◦N of clear-sky (offline) longwave heating rate anomalies](plots/2xHR+WV_time-evolution_2023-2024.pdf)                                               | [heating_rates+WV_plotting.ipynb](code/heating_rates+WV_plotting.ipynb)                     | |
|  11 | [Daily zonal-mean zonal wind at 10 hPa and 60◦N based on SOCOLv4 for the period 2024/2025](plots/ZW_cluster_202410-202502.pdf)                                               | [HT_ta_WV_SOCOL_2024-2025_clustered.ipynb](code/HT_ta_WV_SOCOL_2024-2025_clustered.ipynb)                     | |
|  12 | [Scatter plot of equatorial zonal wind at 10 hPa as a proxy for QBO](plots/QBO@10hPa_vs_SOI_SOCOLw-only_colored_seaborn.pdf)                                               | [SOI_SOCOL.ipynb](code/SOI_SOCOL.ipynb)                     | |
|  13 | [Monthly anomaly of sea level pressure (in hPa) in February 2025 ](plots/SLP_map_cluster_2025_Feb.pdf)                                               | [HT_ta_WV_SOCOL_2024-2025_clustered.ipynb](code/ HT_ta_WV_SOCOL_2024-2025_clustered.ipynb)                     | |
|  14 | [As Fig. 5, but daily anomalies of the weighted meridional temperature gradient](plots/temp-gradient_SOCOL_2023-2024.pdf)                                               | [SOCOL_temp_gradient-final.ipynb](code/SOCOL_temp_gradient-final.ipynb)                     | |
|  15 | [As Fig. 3 but for the extended winter 2025/2026](plots/TE+WV+O3_time-evolution_2025-09-2026-03_MLSv6_anom-int_significance.pdf)                                               | [MLS_significance_visualization.ipynb](code/MLS_significance_visualization.ipynb)                     | |


                                                                                                                             
                                                  
#### Supplementary figures
|  #  | Figure                                                                                                                                                                                                    | Notebook                                                                              | Dependencies                                                                                                                                                             |
|:---:|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:--------------------------------------------------------------------------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|  S1 | [Daily Eliassen-Palm flux diagnostics for the extended winter 2023/2024 (SOCOL)](plots/EPFD_plot_2023-2024.pdf)                                               | [NAM_all-winters.ipynb](code/NAM_all-winters.ipynb)                     | |

    
    




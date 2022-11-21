# Awesome-earth-system-ml [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
**Awesome-earth-system-ml** is a curated list of datasets from dynamic Earth system models for the climate-interested machine learning community. The list targets data from climate, weather, atmosphere, ocean, flood, cryosphere, or other models and sciences. 

Getting started with data science in Earth system modeling. The lack of organized datasets is one reason why. So, this list of datasets intends to get you started with building machine learning models for analysing dynamical Earth systems.

This is a wide open and inclusive community. We would very much appreciate if you add your favorite datasets via a pull request or (emailing lutjens at mit [dot] edu).

<img src="figures/race-climate-change-climate-activists-small.jpg" alt="LONDON/ENGLAND – FEBRUARY 22 2020: Black Extinction Rebellion protester holding a 'THERE IS NO PLANET B' sign at the February 2020 March in collaboration with Parents 4 Future by JessicaGirvan on Shutterstock" width="50%">
Photo of climate activists holding a 'THERE IS NO PLANET B' sign by [**Jessica Girvan**](https://www.dreamstime.com/Jessicagirvan94_info) on [Shutterstock](https://www.shutterstock.com/image-photo/londonengland-february-22-2020-black-extinction-1654798531)

## Content
- [**Atmosphere**](#atmosphere)
- [**Climate**](#climate)
- [**Climate risk**](#climate-risk)
- [**Cryosphere**](#cryosphere)
- [**Land surface, forest, and biodiversity**](#land-surface,-forest,-and-biodiversity)
- [**Flooding**](#flooding)
- [**Ocean**](#ocean)
- [**Renewables wind and solar**](#renewables-wind-and-solar)
- [**Weather**](#weather)
- [**Wildfire**](#wildfire)
- [**Awesome-awesome**](#awesome-awesome)

## Atmosphere
- [**SEVIR : A Storm Event Imagery Dataset for Deep Learning Applications in Radar and Satellite Meteorology**](https://sevir.mit.edu/nowcasting) *(Veillette et al., 21)* \
ML-ready dataset for nowcasting storm events. US dataset of 10,000 weather events that each consist of 384 km x 384 km image sequences spanning 4 hours of time. Contains 5-bands: 3x GOES-16 advanced baseline imager, NEXRAD vertically integrated liquid, and GOES-16 Geostationary Lightning Mapper. Used in [1](https://proceedings.neurips.cc/paper/2020/hash/fa78a16157fed00d7a80515818432169-Abstract.html).

- [**CUMULO : A Dataset for Learning Cloud Classes**](https://github.com/FrontierDevelopmentLab/CUMULO) *(Zantedeschi et al., 19)* \
ML-ready dataset for cloud classification. Global dataset at 1km spatial and daily resolution for 2008, 2009 and 2016. Includes 300K annotated images with multispectral image (MODIS), radar (CloudSat), and lidar (CLDCLASS and CALIOP). Used in [1](https://arxiv.org/abs/1911.04227).

- [**SP-CAM**]

- [**NCAR CAM**]


## Climate
- [**ClimateBench**](https://doi.org/10.1029/2021MS002954) *(Watson-Parris et al., 22)* \
ML-ready dataset for learning climate response to aerosols. Global dataset at 2° spatial and yearly resolution creating images of size 96x144 videos, totaling approx 2GB storage. Includes carbon dioxide, methane, sulfur dioxide, and soot forcings and temperature, diurnal temperature range and precipitation predictors. Includes CMIP6's AerChemMIP, NorESM2, ScenarioMIP, and DAMIP data. Evaluates RMSE. Used in [1](https://arxiv.org/abs/2002.00469), [2](https://doi.org/10.1029/2020MS002109), [3](https://doi.org/10.1002/qj.4180), and [4](https://arxiv.org/abs/2008.08626).

- [**ClimART: A Benchmark Dataset for Emulating Atmospheric Radiative Transfer in Weather and Climate Models**](https://github.com/RolnickLab/climart) *(Cachay and Ramesh et al., 22)* \
ML-ready dataset for atmospheric radiative transfer parametrizations. Contains 10M samples from present, pre-industrial, and future climate conditions, based on the Canadian Earth System Model. Used in [1](https://arxiv.org/abs/2111.14671).

- [**CMIP6**](https://pangeo-data.github.io/pangeo-cmip6-cloud/accessing_data.html#preprocessing-the-cmip6-datasets) *(WCRP, 2019)* \ 
Raw comprehensive dataset of 100+ climate models under various emission scenarios.

## Climate Risk
- todo

## Cryosphere
- [**MAR**]

## Land surface, forest, and biodiversity
- [**Clima Land**]

## Flood
- [**NEMO: Digital Twin Earth xxx**](https://google.github.io/auto-arborist/) *(Beery et al., 2022)* \
A tree genus classification dataset from 23 cities in US, Canada with Google Street View imagery with 2M trees and >300 classes. 

## Ocean
- [**NEMO: Digital Twin Earth xxx**](https://google.github.io/auto-arborist/) *(Beery et al., 2022)* \
A tree genus classification dataset from 23 cities in US, Canada with Google Street View imagery with 2M trees and >300 classes. 

## Renewables wind and solar
- [**WiSoSuper: Benchmarking Super-Resolution Methods on Wind and Solar Data**](https://arxiv.org/abs/2109.08770) *(Kurinchi-Vendhan et al.,2022)* \
ML-ready dataset for superresolution of wind and solar data. Evaluates RMSE, kinetic energy spectrum, and solar semivariogram.

## Weather
- [**RainBench: Towards Data-Driven Global Precipitation Forecasting from Satellite Imagery**](https://github.com/FrontierDevelopmentLab/PyRain) *(Schroeder de Witt et al., 2021)* \
ML-ready dataset for data-driven precipitation forecasting. Global dataset at 1.4° and 5.625° spatial and hourly resolution creating images of size 32x64 with 3 vertical grid points from 2016-2019. Includes ERA5 reanalysis, SimSat simulated satellite data, and IMERG glocal precipitation estimates. Contains output variables (ERA5 total precipitation, IMERG precipitation), dynamic input variables (geopotential, temperature, humidity, cloud liquid water content, cloud ice water content, surface pressure, 2-meter temperature, and cloud-brightness temperatures), and static input variables (lat, lon, land-sea mask, orography, soil type). Evaluate RMSE. Used in [1](https://doi.org/10.1609/aaai.v35i17.17749).

- [**WeatherBench: A benchmark dataset for data-driven weather forecasting**](https://github.com/pangeo-data/WeatherBench) *(Rasp et al., 2020)* \
ML-ready dataset for data-driven weather forecasting. Global dataset at 1.4° and 5.625° spatial and hourly resolution creating images of size 128x256 - 32x64 with 13 vertical grid points, totaling 191GB storage. Includes geopotential, temperature, humidity, wind, potential vorticity, solar radiation, and others. Includes ERA5 and CMIP-MPI-ESM-HR data. Evaluate RMSE. Used in [1](https://arxiv.org/abs/2002.00469), [2](https://doi.org/10.1029/2020MS002109), [3](https://doi.org/10.1002/qj.4180), and [4](https://arxiv.org/abs/2008.08626).

- [**ERA5**](https://www.ecmwf.int/en/forecasts/datasets/reanalysis-datasets/era5) *(ECMWF, 2020)*\
Raw hourly reanalysis estimate of atmospheric, land and oceanic variables. Global, 30km grid, with 137 vertical nodes in the atmosphere, including uncertainties, 1959-present. Used in [FourCastNet](https://arxiv.org/abs/2202.11214) and [Keysler et al., 22](https://rkeisler.github.io/graph_weather/).

## Wildfire
- [**PYROCAST: Machine learning pipeline for pyrocumulonimbus (pyroCb) forecasting**](https://spaceml.org/repo/project/63691212f97150000d504d4d) *(Tazi et al., 2022)* \
Unclear. Code not yet public.

## Awesome-awesome
- [**Awesome Forests**](https://github.com/blutjens/awesome-forests) \
A curated list of ground-truth forest datasets for the machine learning and forestry community.

- [**Awesome Flood Datasets**](https://github.com/blutjens/awesome-flood-datasets) \
A curated list of ground-truth forest datasets for the machine learning and forestry community.

- [**Awesome satellite imagery datasets**](https://github.com/chrieke/awesome-satellite-imagery-datasets) \
A list of more satellite imagery datasets with annotations for deep learning and computer vision.

- [**Awesome GIS**](https://github.com/sshuair/awesome-gis) \
A list of GIS resources.

- todo: add link to dataset list on [conservationtech.directory](https://conservationtech.directory/)

## Acknowledgements
- This list has only been possible to assemble through the extensive input by Duncan Watson Parris.

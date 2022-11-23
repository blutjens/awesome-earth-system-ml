# Awesome-earth-system-ml [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
**Awesome-earth-system-ml** is a curated list of datasets from dynamic Earth system models for the climate-interested machine learning community. The list targets data from climate, weather, atmosphere, ocean, flood, cryosphere, or other models and sciences. 

Getting started with data science in Earth system modeling is challenging. The lack of accessible datasets and plethora of evaluation options is one reason why. So, this list of datasets and benchmarks intends to get you started with building machine learning models for analysing dynamical Earth systems.

This is list represents an inclusive community. We would very much appreciate if you add your favorite datasets via a pull request or (emailing lutjens at mit [dot] edu).

<img src="figures/race-climate-change-climate-activists-small.jpg" alt="LONDON/ENGLAND – FEBRUARY 22 2020: Black Extinction Rebellion protester holding a 'THERE IS NO PLANET B' sign at the February 2020 March in collaboration with Parents 4 Future by JessicaGirvan on Shutterstock" width="50%">

Photo of climate activists holding a THERE IS NO PLANET B sign by 
[**Jessica Girvan**](https://www.dreamstime.com/Jessicagirvan94_info)
on [Shutterstock](https://www.shutterstock.com/image-photo/londonengland-february-22-2020-black-extinction-1654798531)

## Content
- [**Atmosphere and Precipitation**](#atmosphere-and-precipitation)
- [**Climate**](#climate)
- [**Climate risk**](#climate-risk)
- [**Cryosphere**](#cryosphere)
- [**Flooding**](#flooding)
- [**Land surface, forest, and biodiversity**](#land-surface-forest-and-biodiversity)
- [**Ocean**](#ocean)
- [**Renewables wind and solar**](#renewables-wind-and-solar)
- [**Scientific machine learning and numerical methods**](#scientific-machine-learning-and-numerical-methods)
- [**Weather**](#weather)
- [**Wildfire**](#wildfire)
- [**Awesome-awesome**](#awesome-awesome)

## Atmosphere
- [**SEVIR : A Storm Event Imagery Dataset for Deep Learning Applications in Radar and Satellite Meteorology**](https://sevir.mit.edu/nowcasting) *(Veillette et al., 21)* \
ML-ready dataset for forecasting (nowcasting) storm events. US dataset of 10,000 weather events that each consist of 384 km x 384 km image sequences spanning 4 hours of time. Contains 5-bands: 3x GOES-16 advanced baseline imager, NEXRAD vertically integrated liquid, and GOES-16 Geostationary Lightning Mapper. Used in [1](https://proceedings.neurips.cc/paper/2020/hash/fa78a16157fed00d7a80515818432169-Abstract.html).

- [**CUMULO : A Dataset for Learning Cloud Classes**](https://github.com/FrontierDevelopmentLab/CUMULO) *(Zantedeschi et al., 19)* \
ML-ready dataset for classification of clouds. Global dataset at 1km spatial and daily resolution for 2008, 2009 and 2016. Includes 300K annotated images with multispectral image (MODIS), radar (CloudSat), and lidar (CLDCLASS and CALIOP). Used in [1](https://arxiv.org/abs/1911.04227).

- [**Fast and accurate learned multiresolution dynamical downscaling for precipitation**](https://github.com/lzhengchun/DSGAN) *(J. Wang et al., 20)* \
ML-ready dataset for superresolution of precipitation. US dataset at 50 and 12km spatial and 3-hourly resolution for 2005 creating ~3K snapshot images at 128x64 and 512x256. Includes WRF RCM simulation from NCEP-R2 climate model. Contains output variables (high-res. precipitation) and input variables (low-res. precipitation, vertically integrated water vapor, sea level pressure, 2m air temperature, and high-res. topography). Evaluates MSE, Jensen-Shannon distance of probability density functions, and extreme precipitation occurences on global and local scale. Used in [1](https://doi.org/10.5194/gmd-14-6355-2021).

- [**SP-CAM**]

- [**NCAR CAM**]

## Climate
- [**ClimateBench**](https://doi.org/10.1029/2021MS002954) *(Watson-Parris et al., 22)* \
ML-ready dataset for forecasting the climate response to aerosols. Global dataset at 2° spatial and yearly resolution creating images of size 96x144 videos, totaling approx 2GB storage. Includes carbon dioxide, methane, sulfur dioxide, and soot forcings and temperature, diurnal temperature range and precipitation predictors. Includes CMIP6's AerChemMIP, NorESM2, ScenarioMIP, and DAMIP data. Evaluates RMSE. Used in [1](https://arxiv.org/abs/2002.00469), [2](https://doi.org/10.1029/2020MS002109), [3](https://doi.org/10.1002/qj.4180), and [4](https://arxiv.org/abs/2008.08626).

- [**ClimART: A Benchmark Dataset for Emulating Atmospheric Radiative Transfer in Weather and Climate Models**](https://github.com/RolnickLab/climart) *(Cachay and Ramesh et al., 22)* \
ML-ready dataset for forecasting atmospheric radiative transfer parametrizations. Contains 10M samples from present, pre-industrial, and future climate conditions, based on the Canadian Earth System Model. Used in [1](https://arxiv.org/abs/2111.14671).

- [**PaleoJump: A database for abrupt transitions in past climates**](https://paleojump.github.io/) *(Bagniewski et al., 2022)* \
Raw dataset for forecasting climatic shocks and analyzing paleoclimate. Global dataset from 123 sites with point data from 4M years ago until present. Includes PANGAEA and NCEI/NOAA datasets. Contains 49 marine-sedient cores, 29 speleothems, 18 lake sediment cores, 16 terrestrial records, and 11 ice cores. Used in [1](https://arxiv.org/abs/2206.06832).

- [**CMIP6**](https://pangeo-data.github.io/pangeo-cmip6-cloud/accessing_data.html#preprocessing-the-cmip6-datasets) *(WCRP, 2019)* \ 
Raw comprehensive dataset of 100+ climate models under various emission scenarios.

## Climate Risk
- todo

## Cryosphere
- [**MAR**]\
todo

## Flooding
- [**NEMO: Digital Twin Earth**]\
todo

## Land surface, forest, and biodiversity
- [**CESM CLM**]\
todo

- see [Awesome-awesome](#awesome-awesome) for more forest data.

## Ocean
- todo

## Renewables wind and solar
- [**WiSoSuper: Benchmarking Super-Resolution Methods on Wind and Solar Data**](https://github.com/RupaKurinchiVendhan/WiSoSuper) *(Kurinchi-Vendhan et al.,2022)* \
ML-ready dataset for superresolution of wind and solar data. US dataset at 10 and 2km spatial and 4-hourly (wind) and 20 and 4km spatial and hourly resolution (solar) from 2007 to 2018. Includes NREL WIND and NSRDB solar data. Contains output variables (high-res. westward wind velocity, southward wind velocity, direct normal irradiance, diffused horizontal irradiance) and input variables (low-res. bilinearly interpolated version of HR variables). Evaluates RMSE, kinetic energy spectrum, and solar semivariogram. Used in [1](https://doi.org/10.1073/pnas.1918964117), [2](https://arxiv.org/abs/2109.08770).

## Scientific machine learning and numerical methods
- [**PDEBench: An Extensive Benchmark for Scientific Machine Learning**](https://github.com/pdebench/pdebench) *(Takamoto et al., 2022)* \
ML-ready dataset for forecasting various PDEs from hydromechanics. Includes 6 basic and 3 advanced problems. The basic PDEs are 1D advection, Burgers, Diffusion-Reaction, Diffusion-Sorption equations and 2D Diffusion-Reaction and Darcy Flow. The advanced PDEs are incompressible Navier-Stokes equations (NSE) and compressible NSE, and shallow-water equations. Evaluates RMSE, normalized RMSE, RMSE on boundary, RMSE of conserved value, RMSEs in low-, mid- or high-pass Fourier space. Used in [1](https://arxiv.org/abs/2210.07182).

## Weather
- [**RainBench: Towards Data-Driven Global Precipitation Forecasting from Satellite Imagery**](https://github.com/FrontierDevelopmentLab/PyRain) *(Schroeder de Witt et al., 2021)* \
ML-ready dataset for forecasting precipitation. Global dataset at 1.4° and 5.625° spatial and hourly resolution creating images of size 32x64 with 3 vertical grid points from 2016-2019. Includes ERA5 reanalysis, SimSat simulated satellite data, and IMERG glocal precipitation estimates. Contains output variables (ERA5 total precipitation, IMERG precipitation), dynamic input variables (geopotential, temperature, humidity, cloud liquid water content, cloud ice water content, surface pressure, 2-meter temperature, and cloud-brightness temperatures), and static input variables (lat, lon, land-sea mask, orography, soil type). Evaluate RMSE. Used in [1](https://doi.org/10.1609/aaai.v35i17.17749).

- [**WeatherBench: A benchmark dataset for data-driven weather forecasting**](https://github.com/pangeo-data/WeatherBench) *(Rasp et al., 2020)* \
ML-ready dataset for forecasting weather. Global dataset at 1.4° and 5.625° spatial and hourly resolution creating images of size 128x256 - 32x64 with 13 vertical grid points, totaling 191GB storage. Includes geopotential, temperature, humidity, wind, potential vorticity, solar radiation, and others. Includes ERA5 and CMIP-MPI-ESM-HR data. Evaluate RMSE. Used in [1](https://arxiv.org/abs/2002.00469), [2](https://doi.org/10.1029/2020MS002109), [3](https://doi.org/10.1002/qj.4180), and [4](https://arxiv.org/abs/2008.08626).

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
- This list has only been possible to assemble through the extensive input by Duncan Watson Parris, Paula Harder, and Fabrizio Falasca.

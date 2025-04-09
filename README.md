# Awesome Urban Datasets

This is a curated list of publicly available urban datasets, gathered over the years. The datasets are divided by their broad topic (natural phenomena, human-driven phenomena, build environment, others), using the same approach as the one used in our [survey of 3D urban analytics](https://urbantk.org/survey-3d/). In each topic, you will find datasets with different types (e.g., timeseries, images, audio) and sizes.

In **natural phenomena**, we list datasets that are primarily describing natural phenomena (e.g., sunlight access / shadow, wind & ventilation, climate). 
In **human-driven phenomena**, we list datasets that are primarily describing phenomena driven by human factors (e.g., traffic, energy modeling or energy potential assessment, noise & sound propagation, property cadastre). 
In **built & natural environment**, we list datasets that are primarily describing the built and natural environment (e.g., infrastructure, buildings, sidewalks, street networks, trees). 

The main goal of this list is to offer a straightforward way to discover urban datasets that can be of interest to users in multiple domains: computer science (e.g., data analytics, data mining, visualization, machine learning, computer vision), social science (e.g., urban planning, economics), climate science, public health, etc.

This list is constantly being updated. Contributions are greatly appreciated.

![Static Badge](https://img.shields.io/badge/No.%20datasets-53-brightgreen)

***
## Table of Contents

1. [Natural phenomena](#natural-phenomena)
   1. [Sunlight access & shadow](#sunlight-access--shadow)
   2. [Flooding](#flooding)
2. [Human-driven phenomena](#human-driven-phenomena)
   1. [Mobility](#mobility)
   2. [Noise & sound propagation](#noise--sound-propagation)
   3. [Pollution](#pollution)
   4. [Crime](#crime)
   5. [Sanitation](#sanitation)
   6. [Service requests](#service-requests)
3. [Built & natural environment](#built--natural-environment)
   1. [Roads & sidewalks](#roads--sidewalks)
   2. [Natural environment](#natural-environment)
   3. [Buildings & lots](#buildings--lots)
4. [Others](#others)
5. [Links](#links)


***

## Natural phenomena

### Sunlight access & shadow

- [Shadows Accrual Maps](https://github.com/ViDA-NYU/shadow-accrual-maps): Detailed shadow information in multiple cities.
- [Deep Umbra](https://urbantk.org/shadows/): Comprehensive dataset with the sunlight access information for more than 100 cities across six continents of the world.

### Flooding

- [European Flood 2013 Dataset](https://github.com/cvjena/eu-flood-dataset): This repository contains metadata and annotations of a flood dataset used in the context of interactive content-based image retrieval.
- [Flooding Complaints to 311](https://data.cityofchicago.org/Service-Requests/Flooding-Complaints-to-311/qrmr-m89j/about_data): 311 flooding complaints received by the City of Chicago.
- [Smart Green Infrastructure Monitoring Sensors - Historical](https://data.cityofchicago.org/Environment-Sustainable-Development/Smart-Green-Infrastructure-Monitoring-Sensors-Hist/ggws-77ih/about_data): Results from a 2017-2018 project of city-installed sensors measuring water runoff from streets and sidewalks.

## Human-driven phenomena

### Mobility

- [UTD19](https://utd19.ethz.ch/): Largest multi-city traffic dataset publicly available.
- [NYC Taxi](https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page): Trip records from all yellow and green taxis in New York City. It includes detailed information such as pickup and drop-off locations, dates, times, fares, and driver-reported passenger counts.
- [Chicago Taxi](https://data.cityofchicago.org/Transportation/Taxi-Trips-2013-2023-/wrvz-psew/about_data): Taxi trips in Chicago from 2013 to the present, including data on trip start and end times, locations, distance traveled, and fare details.
- [NYC Shared Bike](https://www.citibikenyc.com/system-data): Detailed records of bike-sharing activities in New York City, including information on station locations, trip durations, and user demographics.
- [Washington Shared Bike](https://www.capitalbikeshare.com/system-data): Bike-sharing usage in Washington, D.C., featuring data on trip origins and destinations, durations, and bike availability at docking stations.
- [Boston Shared Bike](https://s3.amazonaws.com/hubway-data/index.html): Detailed records of bike-sharing trips in Boston, including information on start and end times, trip durations, and the geographic distribution of bike docks.
- [Guangzhou, China Urban Traffic Speed](https://zenodo.org/record/1205229): Traffic speed data across the urban areas of Guangzhou, China
- [US Census Commuting Flow](https://www.census.gov/topics/employment/commuting/guidance/flows.html): Commuting flow data, showing the movement of workers between home and workplace locations across various geographic levels.
- [Sao Paulo Commuting Flow](https://transparencia.metrosp.com.br/dataset/pesquisa-origem-e-destino): Commuting patterns in Sao Paulo, Brazil.
- [COVID19USFlows](https://github.com/GeoDS/COVID19USFlows): Multiscale Dynamic Human Mobility Flow Dataset in the U.S. during the COVID-19 Epidemic.
- [StreetAware](https://ultraviolet.library.nyu.edu/records/q1byv-qc065): A high-resolution audio, video, and LiDAR dataset of three urban intersections in Brooklyn, New York, totaling approximately 8 unique hours.
- [CCTV Action Recognition Dataset](https://www.kaggle.com/datasets/jonathannield/cctv-action-recognition-dataset): This action recognition dataset contains short video clips sourced from CCTV footage from existing CCTV datasets as well as YouTube and Google.
- [Traffic Crashes - Crashes](https://data.cityofchicago.org/Transportation/Traffic-Crashes-Crashes/85ca-t3if/about_data): Crash data shows information about each traffic crash on city streets within the City of Chicago limits and under the jurisdiction of Chicago Police Department (CPD).
- [Traffic Crashes - People](https://data.cityofchicago.org/Transportation/Traffic-Crashes-People/u6pd-qa9d/about_data): This data contains information about people involved in a crash and if any injuries were sustained. This dataset should be used in combination with the traffic Crash and Vehicle dataset.
- [Traffic Crashes - Vehicle](https://data.cityofchicago.org/Transportation/Traffic-Crashes-Vehicles/68nd-jvt3/about_data): This dataset contains information about vehicles (or units as they are identified in crash reports) involved in a traffic crash. This dataset should be used in conjunction with the traffic Crash and People datasets.
- [Towed Vehicles](https://data.cityofchicago.org/Transportation/Towed-Vehicles/ygr5-vcbg/about_data): This dataset displays location for vehicles that have been towed and impounded by the City of Chicago within the last 90 days.
- [Red Light Camera Violations](https://data.cityofchicago.org/Transportation/Red-Light-Camera-Violations/spqx-js37/about_data): This dataset reflects the daily volume of violations created by the City of Chicago Red Light Program for each camera.
- [Speed Camera Violations](https://data.cityofchicago.org/Transportation/Speed-Camera-Violations/hhkd-xvj4/about_data): This dataset reflects the daily volume of violations that have occurred in Children's Safety Zones for each camera.
- [Chicago Traffic Tracker - Congestion Estimates by Segments](https://data.cityofchicago.org/Transportation/Chicago-Traffic-Tracker-Congestion-Estimates-by-Se/n4j6-wkkf/about_data): This dataset contains the current estimated speed for about 1250 segments covering 300 miles of arterial roads.
- [Traffic Crashes - Vision Zero Chicago Traffic Fatalities](https://data.cityofchicago.org/Transportation/Traffic-Crashes-Vision-Zero-Chicago-Traffic-Fatali/gzaz-isa6/about_data): Traffic fatalities within the City of Chicago that are included in Vision Zero Chicago (VZC) statistics.

### Noise & sound propagation

- [UrbanSound](https://urbansounddataset.weebly.com/urbansound.html): This dataset contains 1302 labeled sound recordings.
- [UrbanSound8K](https://urbansounddataset.weebly.com/urbansound8k.html): This dataset contains 8732 labeled sound excerpts (<=4s) of urban sounds from 10 classes.
- [SONYC UST](https://zenodo.org/record/2590742#.X1mVrmdKjOQ): SONYC Urban Sound Tagging (SONYC-UST), a multilabel dataset from an urban acoustic sensor network.

### Pollution

- [Global High Air Pollutants](https://weijing-rs.github.io/product.html): Global high-resolution (1km, daily) data on air pollution, derived from satellite data, ground data and models.

### Crime

- [Crime data in Brazil](https://www.kaggle.com/inquisitivecrow/crime-data-in-brazil): This dataset contains structured data about all crime occurrences that have been acted upon by the PM, the main police force in Sao Paulo.
- [Crimes - 2001 to Present](https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-Present/ijzp-q8t2/about_data): This dataset reflects reported incidents of crime (with the exception of murders where data exists for each victim) that occurred in the City of Chicago from 2001 to present, minus the most recent seven days.

### Sanitation

- [NY Monthly Tonnage Data](https://data.cityofnewyork.us/City-Government/DSNY-Monthly-Tonnage-Data/ebb7-mvp5/about_data): Monthly collection tonnages that the Department of Sanitation collects from NYC residences and institutions.

### Service requests
- [NYC 311 Service Requests](https://data.cityofnewyork.us/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9/about_data): Requests to the city's complaint service from 2010 to the present.
- [Chicago 311 Service Requests](https://data.cityofchicago.org/Service-Requests/311-Service-Requests/v6vf-nfxy): 311 Service Requests received by the City of Chicago.

## Built & natural environment

### Roads & sidewalks

- [Road networks](https://networkrepository.com/road.php): List of road networks from several cities.
- [Global Streetscapes](https://github.com/ualsg/global-streetscapes): Global Streetscapes is an open dataset made up of 10 million Street View Images (SVIs) spanning 688 cities from 212 countries and regions, crowdsourced from Mapillary and KartaView
- [Project Sidewalk](https://sidewalk-chicago.cs.washington.edu/api): Point-level information on what accessibility attributes exist and where, and value that indicates how (in)accessible a given street/area is.
- [A century of sprawl in the United States](https://datadryad.org/stash/dataset/doi:10.5061/dryad.3k502): High-resolution time series of urban sprawl, as measured through street network connectivity, in the United States from 1920 to 2012.
- [Project Sidewalk](https://sidewalk-chicago.cs.washington.edu/api): Point-level information on what accessibility attributes exist and where (latitude-longitude).

### Natural environment

- [NYC Street Tree Census](https://www.nycgovparks.org/trees/treescount): Spatially accurate digital inventory of NYC's street trees.

### Buildings & lots

- [Global Building Morphology Indicators](https://github.com/ualsg/global-building-morphology-indicators): GBMI is an open project on systematising, computing, and storing individual and aggregated building form metrics, which may be useful for researchers and practitioners across multiple domains.
- [NYC Pluto](https://www.nyc.gov/site/planning/data-maps/open-data/dwn-pluto-mappluto.page): Land use and geographic data at the tax lot level.
- [OpenStreetMap](http://www.geofabrik.de/data/download.html): Crowdsourced data for buildings, roads, etc.
- [CMP Facade](http://cmp.felk.cvut.cz/~tylecr1/facade/): Dataset focused on facade segmentation.
- [Toxic Release Inventory Facilities](https://www.epa.gov/toxics-release-inventory-tri-program/tri-data-and-tools): The Toxics Release Inventory (TRI) Program tracks the industrial management of toxic chemicals that may cause harm to human health and the environment.
- [CDPH Environmental Records Lookup Table](https://data.cityofchicago.org/Environment-Sustainable-Development/CDPH-Environmental-Records-Lookup-Table/a9u4-3dwb/about_data): This dataset serves as a lookup table to determine if environmental records exist in a Chicago Department of Public Health (CDPH) environmental dataset for a given address.
- [Building Violations](https://data.cityofchicago.org/Buildings/Building-Violations/22u3-xenr/about_data): Violations issued by the Department of Buildings from 2006 to the present.
- [Energy Usage 2010](https://data.cityofchicago.org/Environment-Sustainable-Development/Energy-Usage-2010/8yq3-m6wp/about_data): Displays several units of energy consumption for households, businesses, and industries in the City of Chicago during 2010.
- [Chicago Energy Benchmarking - 2020 Data Reported in 2021](https://data.cityofchicago.org/Environment-Sustainable-Development/Chicago-Energy-Benchmarking-2020-Data-Reported-in-/ydbk-8hi6/about_data): The Chicago Building Energy Use Benchmarking Ordinance calls on existing municipal, commercial, and residential buildings larger than 50,000 square feet to track whole-building energy use, report to the City annually, and verify data accuracy every three years.

## Others

- [Cityscapes](https://www.cityscapes-dataset.com/): Dataset for semantic urban scene understanding.
- [DroNet](https://rpg.ifi.uzh.ch/dronet.html): Dataset for drone navigation in urban environments.



## Links

This list includes datasets from other compilations, but it specifically focuses on urban data. Other lists include [Awesome Public Datasets](https://github.com/awesomedata/awesome-public-datasets), [Awesome Spatial Data](https://github.com/bchapuis/awesome-spatial-data), [Awesome Multimodal Urban Computing](https://github.com/yoshall/Awesome-Multimodal-Urban-Computing#taxonomy-and-summary-of-open-sourced-dataset), [Awesome Network Analysis](https://github.com/briatte/awesome-network-analysis?tab=readme-ov-file#datasets), [Free GIS Data](https://freegisdata.rtwilson.com/).



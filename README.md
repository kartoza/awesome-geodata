# Awesome Geodata [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome geospatial data sources and services

**ALPHA STATE NOTICE** - This is very much in an early WIP state.

## Navigation

This page relies on [GitHub Navigation Controls for Markdown](https://github.com/isaacs/github/issues/215#issuecomment-807688648) for in page navigation.

Other relevant sections include:

- [About](about.md)
- [The Bucket](bucket.md)
- [Contributing Guide](contributing.md)
- [Regional Commercial Data Vendors List](vendors.md)
- [Contributor Code of Conduct](code-of-conduct.md)

## About

This readme provides the root geodata service list in order to simplify navigation and search for return users. It is highly recommended that anyone visiting this page for the first time reads through the [about page](about.md) first.

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## Disclaimer

Use at your own risk. This is just a list.

## Legend

This list uses emoji to highlight some characteristic of a service or platform with the following keys used for reference:

### Access

* :unlock: - Authwalled (account is required)
* :gem: - Public/ Open
* :icecream: - Free (Gratis but proprietary)
* :money_with_wings: - Freemium (Pay nothing now but much later)
* :moneybag: - Commercial
* :alien: - The site acts strange, asks you to jump through hoops to get data, and may not be totally altruistic

### Licensing

* :zero: - Open Data/ Open Source/ Public Domain/ Commons
* :warning: - No license information given
* :copyright: - Various, depending on specific data
* :no_entry: -  Copyright and data limitations apply

### Validity

* {{YYYY}} :recycle: - Checked and verified to be working at date/ year
* {{YYYY}} :hourglass: - Service online but seems to be struggling with performance/ scale/ load etc
* {{YYYY}} :grey_exclamation: - Service online but seems to have maintenance issues (invalid ssl etc)
* {{YYYY}} :interrobang: - Service checked and seems to be unavailable
* :exclamation: - Service is deprecated and expected to go offline

An extended legend is provided at the bottom of the lsit to assist with additional categorisations and content discovery.

# Geodata Regions

Data services are primarily categorised by geographic region.

### Global

Global level data sets that provide worldwide data. This is primarily for global cartography, basemaps, and generic data services. Services that provide application specific data at global scale may be detailed in the [topics](#topics) section.

#### OpenStreetMap (OSM)

OpenStreetMap is a community world mapping project and the de facto Open Geographic Data collection

- :gem: :zero: https://wiki.openstreetmap.org/wiki/Downloading_data - Full article on accessing data from OSM

- :gem: :zero: https://download.geofabrik.de/ - Snapshots of OSM data in PBF and SHP formats

- :hammer_and_wrench: https://www.hotosm.org/tools-and-data - Humanitarian Open Streetmap Team tools and data

- https://github.com/kartoza/docker-osm - a docker project for running a local copy of OSM in sync and storing it in PostGIS

#### General

High level data services and sources that provide information at the global level.

- https://data.worldbank.org/ - Worldbank Data Catalogue

- https://www.naturalearthdata.com/ - High level world data useful for cartography

- https://www.copernicus.eu/en/access-data - European Space Agency Copernicus programme data

- https://scihub.copernicus.eu/dhus/#/home - Interactive Copernicus data browser

- https://earthdata.nasa.gov/ - Nasa Earth Data Open Access Portal

- https://wiki.earthdata.nasa.gov/display/GIBS/ - The NASA Earth Data Global Imagery Browse Services

- https://neo.sci.gsfc.nasa.gov/ - NASA Earth Observations

- :unlock: https://urs.earthdata.nasa.gov/ - NASA Earth Explorer

- :unlock: https://dwtkns.com/srtm30m/ - Simple web service for getting relevant SRTM data from the NASA Earth Explorer

#### Other

Private tools, commercial vendors and other useful Earth Science links.

- https://openaddresses.io/ - Open Data Address Information Project

- https://earthengine.google.com/ - Googles Earth Science Platform

- https://registry.opendata.aws/?search=tags:gis,earth%20observation,events,mapping,meteorological,environmental,transportation - Geodata from Amazon Web Services

https://store.usgs.gov/ - View, purchase, and download data and maps

### Continental

Data portals offered at continental, subcontinent or regional level

#### Africa

Data services for the African Continent
##### Civic Technology

Portals, datahubs and catalogues curated by civic technology agencies and community projects

- https://africaopendata.org/

### Countries

Data sources managed at the national level.

#### ZA

The Republic of South Africa

- http://www.sasdi.net/ - South African Spatial Data Infrastructure Catalogue
- http://cdngiportal.co.za/cdngiportal/ - Chief Directorate National Geo-Spatial Information (NGI) Portal from the Department of Rural Development and Land Reform (DRDLR)
- http://catalogue.sansa.org.za/search/ - Data catalogue for the South African National Space Agency
- https://egis.environment.gov.za/data_egis/data_download/current - The GIS data portal for the Department of Forestry, Fisheries and the Environment
- https://ccis.environment.gov.za/#/data-download - National Climate Change Information System
- http://www.dwa.gov.za/iwqs/gis_data/ - Department of Water and Sanitation inks to geographical data
- https://dataportal-mdb-sa.opendata.arcgis.com/ - Municipal Demarcation board Data
- https://bgis.sanbi.org/ - South African National Biodiversity Institute Spatial Data Portal

##### Metros and Municipalities

Data services provided by Municipalities, Local Governments and Metropolitan Areas

- https://web1.capetown.gov.za/web1/opendataportal/AllDatasets - City of Cape Town Data Portal
- https://edge.durban/ - eThekwini Data Portal
- http://gis.durban.gov.za/gis_website/internetsite/ - eThekwini Corporate GIS

##### Civic Technology

Portals, datahubs and catalogues curated by civic technology agencies and community projects

- https://africaopendata.org/
- https://wazimap.co.za/ - Media Monitoring and Census Reporting
- https://beta.youthexplorer.org.za/ - Wazimap-NG

## Topics

Data services that are relevant to a specific topic or scientific field.

These are typically expected to be at global or continental scale at least. Local or regional services should be categorised by region.

### Biodiversity Information

- https://www.gbif.org/ - Global Biodiversity Information Facility provides free and open access to biodiversity data and species observations
- https://geobon.org/ - Group on Earth Observations biodiversity observation network

### Climate

- http://chelsa-climate.org/ - CHELSA (Climatologies at high resolution for the earth’s land surface areas) is a very high resolution (30 arc sec, ~1km) global climate data set currently hosted by the Swiss Federal Institute for Forest, Snow and Landscape Research WSL.

### Disaster Risk Reduction (DRR)

- https://www.geonode-gfdrrlab.org/ - The Global Facility for Disaster Reduction and Recovery GeoNode instance

### Earth Observation

- :hammer_and_wrench: :gem: https://github.com/sentinelsat/sentinelsat - A python library for searching and retrieving sentinel imagery

### Energy

- https://energydata.info/ - Open data platform providing access to datasets and data analytics that are relevant to the energy sector.

### Health

- https://healthsites.io/ - An open data commons of health facility data project built with tight integration to the OpenStreetMap project.

### Humanitarian

- https://data.humdata.org/ - The Humanitarian Data Exchange

### Remote Sensing

- https://glovis.usgs.gov/ - USGS Global Visualization Viewer (GloVis)

### Non-Spatial

More information on non-spatial data sources is available on the [About Page](about.md), especially in the "Prior Art" section.

### Services

* https://neo.sci.gsfc.nasa.gov/wms/wms?version=1.3.0 - WMS for https://neo.sci.gsfc.nasa.gov/

## Software

Software and software plugins which provide effective data access and cataloguing services.

### Esri

Esri provide access to a large number of data services in many of their products across different platforms. Additional/ distinct data products (which may be accessed via other products) include:

- https://livingatlas.arcgis.com/en/home/
- https://hub.arcgis.com/ - The successor to Esri opendata
- https://www.arcgis.com/home/group.html?id=702026e41f6641fb85da88efe79dc166#! - ArcGIS Online Basemaps Collection

Additionally, public sample services for testing are available via the ArcGIS REST API:

- https://sampleserver3.arcgisonline.com/arcgis/rest/services
- https://sampleserver4.arcgisonline.com/arcgis/rest/services
- https://sampleserver5.arcgisonline.com/arcgis/rest/services
- https://sampleserver6.arcgisonline.com/arcgis/rest/services

### QGIS

QGIS Desktop does not provide much data by default, however there are some "Easter Eggs" which let you access data immediately by [typing keywords into the coordinates bar](https://qgis.org/en/site/forusers/visualchangelog316/index.html#add-user-groups-easter-egg). The most commonly used easter egg is probably "world", which loads the natural earth country boundaries, but because QGIS is an Open Source project you can dig around the[source code](https://github.com/qgis/QGIS/blob/2d1aa68f0d044f2aced7ebeca8d2fa6b754ac970/src/app/qgsstatusbarcoordinateswidget.cpp#L113) to get a full list of available easter eggs.

Modern versions of QGIS also include some data services OOTB, including access to the [nominatim geocoding service](https://nominatim.org/) and the Open Street Map XYZ Tile Service

#### QGIS Plugins

- [QuickMapServices](https://github.com/nextgis/quickmapservices), available from the [official plugin repository](https://plugins.qgis.org/plugins/quick_map_services/), provides easy access to a number of basemap collections as tile services.
- [QuickOSM](https://github.com/3liz/QuickOSM), available from the [official plugin repository](https://plugins.qgis.org/plugins/QuickOSM/), provides easy access to Open Street Map vector data via the overpass API.
- [Google Earth Engine Data Catalog](https://github.com/sandroklippel/qgis_gee_data_catalog), available from the [official plugin repository](https://plugins.qgis.org/plugins/qgis_gee_data_catalog/), provides easy access to GEE Data within QGIS.

## Other

Geodata resources which don't quite fit any of the above categories.

### Vendors

Private commercial data vendors which may supply data across various domains or regions may be found on the [commercial vendors page](vendors.md).

## Extended Legend

Many services may cater to a specific topic/ category or type of data. In order to suitably identify these data types visually the following emoji may be appended to an entry to outline the relevant characteristics.

### ISO 19115 Topic Category

* :blossom: Biota
* :world_map: Boundaries
* :sunny: Climatology Meteorology Atmosphere
* :receipt: Economy
* :mountain: Elevation
* :leaves: Environment
* :seedling: Farming
* :volcano: Geoscientific Information
* :hospital: Health
* :earth_africa: Imagery Base Maps Earth Cover
* :satellite: Intelligence Military
* :droplet: Inland Waters
* :compass: Location
* :ocean: Oceans
* :toolbox: Planning Cadastre
* :family: Society
* :bricks: Structure
* :bike: Transportation
* :telephone_receiver: Utilities Communication

### Service Type

* :hammer_and_wrench: Tools
* :globe_with_meridians: Web Service
* :world_map: Maps
* :compass: Navigation
* :artificial_satellite: Satellite
* :mountain: Geology
* :beach_umbrella: Tourism
* :briefcase: Business Intelligence
* :robot: AI/ ML
* :zap: Energy
* :handshake: Humanitarian
* :national_park: Conservation

# Awesome Geodata [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome geospatial data sources and services

**ALPHA STATE NOTICE** - This is very much in an early WIP state.

## Disclaimer

Use at your own risk. This is just a list.

## REQUEST FOR GOOD BEHAVIOUR

Please be responsible when consuming and utilising the services listed here. Many of these public data services are developed, maintain, and run by volunteers and have limited resources.

The majority of these services have their own terms and conditions, licensing requirements, usage policies, and rate limits.

Everyone who makes use of these services should endeavour to comply with them as much as possible. Failure to do so may result in penalties and/ or legal action.

If you are utilising a service for commercial purposes, please consider using a commercial provider or hosting the relevant data and services on your own infrastructure to prevent abuse of public resources. If using a public resource in a public or open source application, it is expected that you should implement some form of rate limiting in the client applications to prevent abuse by your users.

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

## Legend

This list uses emoji to highlight some characteristic of a service or platform.

The GeoMoji project [github.com/zacharlie/geomoji](https://github.com/zacharlie/geomoji) will serve as a reference for the emoji used in this list, along with the extended definitions as outlined below.

with the following keys used for reference:

### Access

- :muscle: - The site has reliable support (This includes funding or infrastructure provided by a large foundation, NGO, public agency, corporation, or significant corporate sponsorship and should be indicative that it is expected to have continued support for the medium to long term, or 5-10 years, without changes to it's terms of use even if it experiences a sudden rise in popularity, making it suitable for use in production. It should also indicate mature services with wide userbase which are unlikely to introduce breaking changes)
- :alien: - The site acts strange, asks you to jump through hoops to get data, and may not be totally altruistic

### Validity

- {{YYYY}} :recycle: - Checked and verified to be working at date/ year
- {{YYYY}} :hourglass: - Service online but seems to be struggling with performance/ scale/ load etc
- {{YYYY}} :grey_exclamation: - Service online but seems to have maintenance issues (invalid ssl etc)
- {{YYYY}} :interrobang: - Service checked and seems to be unavailable
- {{YYYY}} :exclamation: - Service is deprecated and expected to go offline at the date listed

An extended legend is provided at the bottom of the list to assist with additional categorisations and content discovery.

### Licensing

Licensing information is provided where possible, however it is subject to error and may change at any time.

## Other Lists

The following outline lists of spatial datasources similar to this list:

- A List of related but dissimilar community lists is available in the "Prior Art" section of the [About Page](about.md#prior-art)
- https://en.wikipedia.org/wiki/List_of_GIS_data_sources - Wikipedia equivalent of awesome-geodata

## Catalogues

This list is primarily for targeting legacy platforms, services, web interfaces, and data sources which cannot be automatically be traversed using some catalog software or platform. As the OGC APIs mature, and technologies such as OAFeat and STAC become more widely used, this would become redundant. If there is a better tool for discovering certain service types, such as stacindex.org, this list should rather link to that resource than individual endpoints available from those platforms.

## Geodata Regions

Data services are primarily categorised by geographic region.

### Global

Global level data sets that provide worldwide data. This is primarily for global cartography, basemaps, and generic data services. Services that provide application specific data at global scale may be detailed in the [topics](#topics) section.

#### General

High level data services and sources that provide information at the global level.

- :muscle: :gem: https://data.worldbank.org/ - Worldbank Data Catalogue
- :gem: https://www.naturalearthdata.com/ - High level world data useful for cartography
- :gem: https://www.geoboundaries.org/index.html#getdata - Global Database of Political Administrative Boundaries with custom attribution license
- :moneybag: https://gadm.org/ - Initiative to maintain high resolution administrative area boundaries for all countries globally. Free for academic and non-commercial use, however commercial use or redistribution requires special permission.
- :muscle: https://www.copernicus.eu/en/access-data - European Space Agency Copernicus programme data
- :muscle: https://scihub.copernicus.eu/dhus/#/home - Interactive Copernicus data browser
- :muscle: https://inspire-geoportal.ec.europa.eu/ - Infrastructure for Spatial Information in the European Community Geoportal
- :muscle: https://esa-worldcover.org/en/data-access - WorldCover is a freely accessible global land cover product at 10 m resolution for 2020, based on both Sentinel-1 and Sentinel-2 data initiative provided by the European Space Agency (ESA) initially released on 10/2021. This site includes access to WorldCover web services, data downloads, symbology files, and more.
- :muscle: https://earthdata.nasa.gov/ - Nasa Earth Data Open Access Portal
- :muscle: https://wiki.earthdata.nasa.gov/display/GIBS/ - The NASA Earth Data Global Imagery Browse Services
- :muscle: :gem: https://neo.sci.gsfc.nasa.gov/ - NASA Earth Observations
- :muscle: :unlock: https://sedac.ciesin.columbia.edu/ - NASA Socioeconomic Data and Applications Center (SEDAC)
- :muscle: :unlock: https://urs.earthdata.nasa.gov/ - NASA Earth Explorer
- :unlock: https://dwtkns.com/srtm30m/ - Simple web service for getting relevant SRTM data from the NASA Earth Explorer
- :muscle: https://www.usgs.gov/products/data-and-tools/overview - usgs has many resources
- :muscle: https://www.fao.org/geospatial/resources/data-portals/ - Spatial data portals from the Food and Agriculture Organization of the United Nations
- :gem: https://stacindex.org/ - An index site for known [STAC](https://stacspec.org/) catalogues

#### OpenStreetMap (OSM)

[OpenStreetMap](https://www.openstreetmap.org/about) is a community world mapping project and the de facto open collection of geographic vector data

- :gem: :zero: https://wiki.openstreetmap.org/wiki/Downloading_data - Full article on accessing data from OSM
- :gem: :zero: https://download.geofabrik.de/ - Snapshots of OSM data in PBF and SHP formats
- :hammer_and_wrench: :gem: :zero: https://www.hotosm.org/tools-and-data - Tools and data utilities from the Humanitarian Open Streetmap Team
- :zero: :unlock: https://www.hotosm.org/tools-and-data - HOTOSM export tool
- :hammer_and_wrench: :gem: :zero: https://github.com/kartoza/docker-osm - a docker project for running a local copy of OSM (optionally restricted to a specific target area) which is kept in sync with OSM updates, storing the resulting data (for configured tags) in a PostGIS database. Based on [imposm](https://imposm.org/)

#### Other

Private tools, commercial vendors and other useful Earth Science links.

- https://openaddresses.io/ - Open Data Address Information Project
- https://opentopography.org/ - High-Resolution Topography Data and Tools and data aggregation site, including LiDAR and DEM coverages
- https://map.openaerialmap.org - Openly licensed aerial imagery data from satellites, aircraft and UAV
- https://developers.google.com/earth-engine/datasets/catalog/ - Googles Earth Science Platform
- https://registry.opendata.aws/?search=tags:gis,earth%20observation,events,mapping,meteorological,environmental,transportation - Geodata from Amazon Web Services
- https://store.usgs.gov/ - View, purchase, and download data and maps, including access to historical topomap collections
- https://planetarycomputer.microsoft.com/catalog - Microsoft Earth Observation platform
- https://github.com/microsoft/GlobalMLBuildingFootprints - Global Building Footprints from Microsoft derived from machine learning

### Continental

Data portals offered at continental, subcontinent or regional level

#### Africa

Data services for the African Continent

- https://sites.research.google/open-buildings/ - AI derived building footprints for the African continent developed by Google

##### Earth Observation

- https://maps.digitalearth.africa - Map and interactive data browser for the [Digital Earth Africa](https://www.digitalearthafrica.org/) project
- https://docs.digitalearthafrica.org/en/latest/ - Docs, user guides, and links to data platforms such as the metadata catalogue for the [Digital Earth Africa](https://www.digitalearthafrica.org/) project

##### Civic Technology

Portals, data hubs, and catalogues curated by civic technology agencies and community projects

- https://africaopendata.org/ - A CKAN implementation for various civic technology groups and public agencies to share and catalogue data, maintained by [Code for Africa](https://github.com/CodeForAfrica/)

### Countries

Data sources managed at the national level.

#### CA

Canada

- https://open.canada.ca/en/open-maps - Government of Canada’s geospatial information portal
- http://cgrsc.ca/resources/geodetic-control-networks/provincial-networks/ - Control Networks Canadian Geodetic Reference System Committee

##### Provincial Portals

- https://openmaps.gov.bc.ca - British Columbia Map Services
- https://geodiscover.alberta.ca - Enhanced details on Alberta's geospatial data
- https://open.alberta.ca/opendata - Alberta Open Data Portal (includes spatial data)

#### FR

France

- https://cadastre.data.gouv.fr/ - French cadastral portal, including [data downloads](https://cadastre.data.gouv.fr/data/etalab-cadastre/) from the open [etalab cadstre project](https://github.com/etalab/cadastre)

#### KE

Kenya

- :blossom: https://tanaribbis.org/ - Biodiversity portal for Kenya

#### NZ

New Zealand

- https://www.linz.govt.nz/ - Toitū Te Whenua Land Information New Zealand
- https://lris.scinfo.org.nz/ - New Zealand Land Resource Information Systems Portal
- https://datafinder.stats.govt.nz/ - [Stats NZ](https://www.stats.govt.nz/) Geographic data service

#### US

The United States of America

- https://catalog.data.gov/dataset - US Government Data Portal based on the CKAN platform
- https://github.com/Microsoft/USBuildingFootprints - Microsoft Building Footprints for the US

##### Oklahoma

- https://gis-okdot.opendata.arcgis.com - Oklahoma Department of Transport Geodata

#### ZA

The Republic of South Africa

- http://www.sasdi.net/ - South African Spatial Data Infrastructure Catalogue
- http://cdngiportal.co.za/cdngiportal/ - Chief Directorate National Geo-Spatial Information (NGI) Portal from the Department of Rural Development and Land Reform (DRDLR)
- http://trignet.co.za/ - Access portal for the [TrigNet GNSS base stations](www.ngi.gov.za/index.php/what-we-do/geodetic-and-control-survey-services/37-trignet-continuously-operating-gnss-network) operated by the NGI
- ftp://ftp.trignet.co.za/ - Download TrigNet data using ftp. Supports anonymous login.
- http://catalogue.sansa.org.za/search/ - Data catalogue for the South African National Space Agency
- :leaves: https://egis.environment.gov.za/data_egis/data_download/current - The GIS data portal for the Department of Forestry, Fisheries and the Environment
- :sunny: https://ccis.environment.gov.za/#/data-download - National Climate Change Information System
- :droplet: http://www.dwa.gov.za/iwqs/gis_data/ - Department of Water and Sanitation inks to geographical data
- :world_map: https://dataportal-mdb-sa.opendata.arcgis.com/ - Municipal Demarcation board Data
- :blossom: https://bgis.sanbi.org/ - South African National Biodiversity Institute Spatial Data Portal
- :blossom: https://freshwaterbiodiversity.org/ - Freshwater Biodiversity Information System (FBIS)
- :bike: https://atns.com/products-services/aim/aeronautical-information-managementrsa-airspaces-in-3d/7423/ - 3D KMZ for South African Aviation data including airspace, routes, aerodromes and navigational facilities within South Africa compiled by Air Traffic and Navigation Services SOC Limited

##### Metros and Municipalities

Data services provided by Municipalities, Local Governments and Metropolitan Areas

- https://web1.capetown.gov.za/web1/opendataportal/AllDatasets - City of Cape Town Data Portal
- https://edge.durban/ - eThekwini Data Portal
- http://gis.durban.gov.za/gis_website/internetsite/ - eThekwini Corporate GIS

##### Civic Technology

Portals, datahubs and catalogues curated by third party agencies and community projects

- https://wazimap.co.za/ - Media Monitoring and Census Reporting, developed and maintained by [OpenUp](https://openup.org.za/)
- https://maps.sagta.org.za/ - The Southern African Geography Teachers Association map downloader allows the creation and download of print map layouts using the RSA imagery and 50k tile services

##### Non-Spatial Data

Non-spatial data that is typically used in conjunction with, or to enrich, spatial data.

The following resources should facilitate utilisation of census data from statssa:

- http://www.statssa.gov.za/?page_id=1417 - The "Interactive Data" page
- https://apps.statssa.gov.za/census01/html/Geography_Metadata.htm - Detail on design and implementation of geographic data structures and hierarchy for national census
- http://superweb.statssa.gov.za/webapi/jsf/login.xhtml - Web based version of SuperCROSS

##### Services

- http://apollo.cdngiportal.co.za/erdas-iws/ogc/wms/CDNGI_IMAGERY_MOSAICS?service=WMS&request=getcapabilities - Chief Directorate: National Geospatial Information WMS: Imagery Mosaics
- http://apollo.cdngiportal.co.za/erdas-iws/ogc/wms/CDNGI_MAP_MOSAICS?service=WMS&request=getcapabilities - Chief Directorate: National Geospatial Information WMS: Mapping Mosaics
- http://c.aerial.openstreetmap.org.za/ngi-aerial/{z}/{x}/{y}.jpg - XYZ Tile service for South African Imagery from the NGI
- https://htonl.dev.openstreetmap.org/ngi-tiles/tiles/50k/{z}/{x}/{-y}.png - XYZ Tile service for South African 50k Toposheets
- http://bgismaps.sanbi.org/arcgis/rest/services - ArGIS Server REST endpoint for SANBI BGIS

## Topics

Data services that are relevant to a specific topic or scientific field.

These are typically expected to be at global or continental scale at least. Local or regional services should be categorised by region.

### Biodiversity Information

- https://www.gbif.org/ - Global Biodiversity Information Facility provides free and open access to biodiversity data and species observations
- https://geobon.org/ - Group on Earth Observations biodiversity observation network
- https://www.genesys-pgr.org/ - Plant Genetic Resources for Food and Agriculture (PGRFA)
- https://obis.org/ - Ocean Biodiversity Information System

### Climate

- https://climateknowledgeportal.worldbank.org/ - Interactive knowledge portal for climate change data
- https://www.worldclim.org - Global climate and weather data
- https://www.globalclimatemonitor.org/ - Historical climate data web viewer and downloader
- http://www.climatologylab.org/terraclimate.html - Monthly climate and climatic water balance data for global terrestrial surfaces from 1958-2019
- http://chelsa-climate.org/ - CHELSA (Climatologies at high resolution for the earth’s land surface areas) is a very high resolution (30 arc sec, ~1km) global climate data set currently hosted by the Swiss Federal Institute for Forest, Snow and Landscape Research WSL.
- https://cds.climate.copernicus.eu/ - Copernicus Climate Data Store

#### Precipitation

- https://data.chc.ucsb.edu/products/CHIRPS-2.0/global_annual/tifs/ - University of California, Santa Barbara [Climate Hazards Group InfraRed Precipitation with Station](https://www.chc.ucsb.edu/data/chirps) data.

### Disaster Risk Reduction (DRR)

- https://www.geonode-gfdrrlab.org/ - The Global Facility for Disaster Reduction and Recovery GeoNode instance
- :volcano: https://earthquake.usgs.gov/earthquakes/search/ - USGS earthquake data portal, including a search for retrieving spatial data such as kml

### Earth Observation

- :hammer_and_wrench: :gem: https://github.com/sentinelsat/sentinelsat - A python library for searching and retrieving sentinel imagery
- https://landsatlook.usgs.gov/explore - Tool for online viewing and access to the USGS Landsat Collection 2 data. Also includes a stac API at https://landsatlook.usgs.gov/sat-api/

#### Atmospheric

- https://ads.atmosphere.copernicus.eu/ - Copernicus Atmospheric Data Store

### Energy

:zap:

- https://energydata.info/ - Open data platform providing access to datasets and data analytics that are relevant to the energy sector.
- https://globalsolaratlas.info/map - Maps and data for countries eligible for official development assistance [SolarGIS Catalogue](https://solargis.com/maps-and-gis-data/overview)

### Health

- https://healthsites.io/ - An open data commons of health facility data project built with tight integration to the OpenStreetMap project.

### Humanitarian

- https://data.humdata.org/ - The Humanitarian Data Exchange

### Hydrology

- https://ggis.un-igrac.org/ - International Groundwater Resources Assessment Centre (IGRAC) Global Groundwater Information System (GGIS)

### Landcover

https://livingatlas.arcgis.com/landcover/ - Global 10m Landcover developed by Impact Observatory using Sentinel-2 data and published by Esri

### Remote Sensing

- https://glovis.usgs.gov/ - USGS Global Visualization Viewer (GloVis)

### Non-Spatial

More information on non-spatial data sources is available on the [About Page](about.md), especially in the "Prior Art" section.

### Services

Service endpoints of international importance and utility

- :muscle: :gem: :zero: https://tile.openstreetmap.org/{z}/{x}/{y}.png - XYZ Tiles from the [OpenStreetMap Project](https://www.openstreetmap.org/)
- :muscle: :gem: :zero: https://neo.sci.gsfc.nasa.gov/wms/wms?version=1.3.0 - WMS for https://neo.sci.gsfc.nasa.gov/

## Other

Geodata and related resources which don't quite fit any of the above categories.

- https://data.giss.nasa.gov/ - Miscellaneous data from the NASA Goddard Institute for Space Studies

## Software

Software, platforms, and plugins which provide effective data access and cataloguing services.

### Esri

:copyright: :money_with_wings:

Esri provide access to a large number of data services in many of their products across different platforms. Additional/ distinct data products (which may be accessed via other products) include:

- https://livingatlas.arcgis.com/en/home/
- https://hub.arcgis.com/ - The successor to Esri opendata
- https://www.arcgis.com/home/group.html?id=702026e41f6641fb85da88efe79dc166#! - ArcGIS Online Basemaps Collection

Additionally, publicly available services using the ArcGIS REST API include:

- http://server.arcgisonline.com/ArcGIS/rest/
- https://sampleserver3.arcgisonline.com/arcgis/rest/services
- https://sampleserver4.arcgisonline.com/arcgis/rest/services
- https://sampleserver5.arcgisonline.com/arcgis/rest/services
- https://sampleserver6.arcgisonline.com/arcgis/rest/services

Some example ArcGIS service endpoints include:

- https://wi.maptiles.arcgis.com/arcgis/rest/services/World_Imagery/MapServer
- https://services.arcgisonline.com/ArcGIS/rest/services/World_Imagery/MapServer/
- https://server.arcgisonline.com/ArcGIS/rest/services/World_Topo_Map/MapServer/
- https://basemaps.arcgis.com/arcgis/rest/services/World_Basemap_v2/VectorTileServer
- https://server.arcgisonline.com/arcgis/rest/services/Polar/Arctic_Imagery/MapServer/tile/{z}/{y}/{x}
- https://server.arcgisonline.com/arcgis/rest/services/Polar/Antarctic_Imagery/MapServer/tile/{z}/{y}/{x}
- https://basemaps.arcgis.com/v1/arcgis/rest/services/World_Basemap/VectorTileServer/tile/{z}/{y}/{x}.pbf
- https://basemaps.arcgis.com/b2/arcgis/rest/services/World_Basemap/VectorTileServer/resources/styles/root.json

You can find similar services from the Esri catalogues:

- https://www.arcgis.com/home/group.html?owner=esri&title=ArcGIS%20Online%20Basemaps#!
- https://livingatlas.arcgis.com/en/browse/#d=1&q=basemaps&categories=Basemaps:11111
- https://www.esri.com/en-us/arcgis/products/data/data-portfolio/basemaps

> **Note:** Utilisation of Esri Services is subject to certain conditions and limitations. You are typically required to utilise these services in conjunction with other Esri products, services, or subscriptions.

More Information:

- https://developers.arcgis.com/documentation/mapping-apis-and-services/licensing/attribution/
- https://www.esri.com/en-us/legal/terms/full-master-agreement
- http://downloads2.esri.com/ArcGISOnline/docs/Information_Guide.pdf
- https://support.esri.com/en/technical-article/000012040

### QGIS

QGIS Desktop does not provide much data by default, however there are some "Easter Eggs" which let you access data immediately by [typing keywords into the coordinates bar](https://qgis.org/en/site/forusers/visualchangelog316/index.html#add-user-groups-easter-egg). The most commonly used easter egg is probably "world", which loads the natural earth country boundaries, but because QGIS is an Open Source project you can dig around the [source code](https://github.com/qgis/QGIS/blob/2d1aa68f0d044f2aced7ebeca8d2fa6b754ac970/src/app/qgsstatusbarcoordinateswidget.cpp#L113) to get a full list of available easter eggs.

Modern versions of QGIS also include some data services OOTB, including access to the [nominatim geocoding service](https://nominatim.org/) and the Open Street Map XYZ Tile Service

#### QGIS Hub

The QGIS plugin repository has been expanded to include the QGIS Hub. In addition to being able to find and share community styles and data processing models, the HUB allows users to access [community projects](https://plugins.qgis.org/geopackages/) which are end-to-end solutions including processing models, styles, data, and more.

#### QGIS Plugins

The [QGIS plugin repository](https://plugins.qgis.org/plugins/) provides community plugins to extend the default functionality of the QGIS Desktop and QGIS Server applications. There are a great deal of plugins related to various functionality, including data acquisition, collection, management, and advanced or application specific functions. Some of the plugins which are really awesome for general data acquisition, especially for providing basemaps and basedata, include:

- :gem: [QuickMapServices](https://github.com/nextgis/quickmapservices), available from the [official plugin repository](https://plugins.qgis.org/plugins/quick_map_services/), provides easy access to a number of basemap collections as tile services. Includes access to community map services which can be added and reviewed from https://qms.nextgis.com/
- :gem: [QuickOSM](https://github.com/3liz/QuickOSM), available from the [official plugin repository](https://plugins.qgis.org/plugins/QuickOSM/), provides easy access to Open Street Map vector data via the overpass API.
- :unlock: :money_with_wings: [Google Earth Engine Data Catalog](https://github.com/sandroklippel/qgis_gee_data_catalog), available from the [official plugin repository](https://plugins.qgis.org/plugins/qgis_gee_data_catalog/), provides easy access to GEE Data within QGIS.
- :unlock: :money_with_wings: [MapTiler Plugin](https://www.maptiler.com/qgis-plugin/)

### Vendors

Private commercial data vendors which may supply data across various domains or regions may be found on the [commercial vendors page](vendors.md).

## Exclusions

If you are the custodian of a listed service and wish for your services to not be listed please file a PR to add your agency, service name, or domain name to the [exclusion list](excludes.md). Note that it may be expected that some form of demonstration of ownership for a service is provided before the PR is merged.

## Thanks

Thank you to all users and contributors, but most of all thanks to all data providers that support the development, maintenance, and publication of these services and their associated data.

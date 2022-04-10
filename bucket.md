# The Bucket List

The less-curated, catch-all, less awesome list of geodata services.

Same format as the list. Things have probably just not been scoped out properly yet. :clock10: Indicates a legacy/ deprecated/ unmaintained service.

#### General

High level data services and sources that provide information at the global level.

- :alien: :unlock: https://www.igismap.com/download-free-shapefile-maps/ - igismap data collections
- :clock10: https://github.com/globalmaps

#### Other

- https://datasetsearch.research.google.com/ - Google, but for data

- https://cgiarcsi.community/category/data/ - CGIAR Consortium for Spatial Information (CGIAR-CSI)

### Continental

Data portals offered at continental, subcontinent or regional level

#### Africa

Data services for the African Continent

##### East Africa

- 2021 :recycle: http://geoportal.icpac.net - IGAD Climate Prediction and Applications Centre GeoNode instance

##### Southern Africa

- 2021 :recycle: https://sadc-gip.org/ - Southern African Development Community Groundwater Information Portal GeoNode Instance. Contains links and references to multiple related groundwater databases and platforms

#### The Caribbean

- 2021 :recycle: http://www.charim-geonode.net/ - Caribbean Handbook on Risk Information Management (CHaRIM)
- 2021 :recycle: http://146.185.160.86/geoserver/wms
- 2021 :recycle: http://146.185.160.86/geoserver/wfs
- 2021 :recycle: http://146.185.160.86/catalogue/csw
- https://cdema.org/cris/ - Caribbean Risk Information System (CRIS)
- https://geocris2.cdema.org/ - Geospatial component of the Caribbean Risk Information System

#### The Pacific

- 2021 :recycle: http://www.pacgeo.org/ - An open access geospatial data repository for the Pacific Region providing premier geophysical, geodetic, and marine spatial data sets.
- 2021 :recycle: http://pcrafi.spc.int/ - Pacific Risk Information System

### Countries

Data sources managed at the national level.

#### CA

- https://geohist.ca/ - Historical GIS project for Canada

#### NZ

New Zealand

- :unlock: https://www.linz.govt.nz/data/linz-data-service/guides-and-documentation/using-the-linz-data-importer-plugin-in-qgis - Includes links to services for LINZ, Environment, Stats, landcare, defence, and basemaps

#### ZA

The republic of South Africa

- https://waterresourceswr2012.co.za/about/

##### Civic Technology

Portals, datahubs and catalogues curated by third party agencies and community projects

- https://beta.youthexplorer.org.za/ - Wazimap-NG
- https://water-wazi.openup.org.za/ - Wazimap for water commons (beta)
- https://github.com/j-norwood-young/SA-Maps - [To a hammer, everything is a nail](https://en.wikipedia.org/wiki/Law_of_the_instrument). When a government fails to deliver suitable and reliable data services, community members will do what they must to facilitate data access...

### Services

Resources for discovering service endpoints of international importance and utility

- http://osgeo-org.1560.x6.nabble.com/Public-vector-tile-servers-td5453345.html - Discussion on public vector tiles services
- https://gis.stackexchange.com/questions/20191/adding-basemaps-from-google-or-bing-in-qgis - Community list of XYZ Tile services

#### Vector Tile Services

Very few [vector tile services](https://en.wikipedia.org/wiki/Vector_tiles) are operated in a manner that they are accessible to the public. Some useful links include:

- :money_with_wings: https://cloud.maptiler.com/maps/ - Fremium
- :no_entry: :icecream: https://www.qwant.com/maps/tiles/ozbasemap/{z}/{x}/{y}.pbf - Accessible free of charge and reserved exclusively for non-professional and non-commercial use
- https://raw.githubusercontent.com/QwantResearch/qwant-basic-gl-style/master/style.json - An example "style file" used to configure the design of vector tile maps
- https://github.com/klokantech/vector-tiles-sample -

> Note that a number of ArcGIS vector tile endpoints are available in the Esri section of the [Main List](readme.md#esri), however these are subject to Esri terms and conditions

## Other

Geodata and related resources which don't quite fit any of the above categories.

- http://maps.stamen.com/ - Maps and designs by Stamen. fancy enough that the [Smithsonian added it to their permanent collection](https://www.si.edu/newsdesk/releases/watercolor-maptiles-website-enters-permanent-collection-cooper-hewitt).
- https://wikitech.wikimedia.org/wiki/Maps - details on deploying Maps service on Wikimedia Foundation infrastructure
- :unlock: :money_with_wings: :copyright: https://www.maptiler.com/data/ - Various data solutions for vector and raster tiles, including downloading, serving, and API access
- https://openmaptiles.org/ - Project for storing and styling tile services, maintained by the maptiler team
- https://github.com/Qwant/qwantmaps - maps by https://www.qwant.com/
- http://map.wikimedia.ch/
- https://tile.synapta.io/styles/osm-bright/{z}/{x}/{y}.png
- https://gedi.umd.edu/data/download/ - Ecosystem LiDAR
- https://github.com/CS-SI/eodag - Earth Observation Data Access Gateway

## Protips

Some generic advice on how to more effectively discover and access spatial data

> You can use the [GitHub Navigation Controls for Markdown](https://github.com/isaacs/github/issues/215#issuecomment-807688648) to jump to relevant sections of the list you utilise frequently and create a bookmark in your browser to skip the noise.

> When using web mapping services you can usually find the endpoint addresses in the network tab of the developer tools (F12) in your browser which can then be used in another GIS system (dependant on service terms).

> When accessing [FTP](https://en.wikipedia.org/wiki/File_Transfer_Protocol) or [SCP](https://en.wikipedia.org/wiki/Secure_Copy_Protocol) services, you can typically just type the full address, with the protocol prefix, into the address bar using your standard file browser, such as windows explorer. Most modern operating systems support this, however you can also use external SCP/ FTP client software like [WinSCP](https://winscp.net), [Cyberduck](https://cyberduck.io/), or [FileZilla](https://portableapps.com/apps/internet/filezilla_portable) - Warning, YMMV and Filezilla has been known to contain bundleware in the past.

# Awesome Geodata [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A *curated* list of awesome geospatial data sources and services

This list is designed to adhere to the values outlined in the [awesome manifesto](https://github.com/sindresorhus/awesome/blob/main/awesome.md).

As such, there are specific *rules* governing the content that may be introduced into the list.

This project additionally attempts to address some of the shortcomings which typically affect awesome lists.

## Purpose

The purpose of this list is to create a central resource for linking to numerous SPATIAL data sources and save users the time it takes to trawl the web for them.

In addition, this list is designed to structure the elements into categories by geographic attributes, as outlined in the [Structure](#structure) section.

## The Bucket

The primary list is intentionally limited in scope in order to provide maximum value and promote the use of certifiably awesome services.

In many situations, community members wish to include any and all resources in a list, rather than simply providing an awesome subset of available services.

Whilst there is often some value in this "high-noise" "catch-all" approach, it does diminish the quality and value (or awesomeness) of the main list.

In an attempt to balance the needs of the community (we can't pretend to understand what data you need) with the desire for a low-noise, high value "awesome" list, the bucket has been provided as an alternative.

At this point submissions to the bucket will undergo significantly less scrutiny in order to be included, however the structure will be the same as the main list and low quality submissions (duplicate data/ spam etc) will still be excluded.

It's the not-so-awesome-awesome-list

## Naughty and Nice

Spam will not be tolerated. This is not an advertising platform. If you are making a submission, even if solely for community benefit, any affiliations or possible conflicts of interest should be submitted as commentary using the PR comments section (not buried in a commit somewhere either).

Failure to do so may end up with your name on the naughty list. Rogue submissions to the bucket list will get you landed on the naughty list too btw.

## Prior art

This list does not serve the same purpose as known existing lists of a similar nature. Many of these lists supply details for GIS platforms, software, or public data sources. This list is exclusively reserved for spatial data sources, or in some rare instances, toolkits for aiding in the discovery of spatial data.

What people do with the data thereafter is another story.

Non-spatial data which is relevant to geoscience, geodesy and spatial information may be included in the *Non-Spatial* topic, however external reference links to other upstream lists may be more useful than direct links to services where relevant.

Known lists to be related but distinct to this may include:

- https://github.com/sindresorhus/awesome
- https://github.com/onurakpolat/awesome-bigdata
- https://github.com/chrisleaman/awesome-coastal
- https://github.com/academic/awesome-datascience
- https://github.com/fasouto/awesome-dataviz
- https://github.com/acgeospatial/awesome-earthobservation-code
- https://github.com/tmcw/awesome-geojson
- https://github.com/sacridini/Awesome-Geospatial
- https://github.com/sshuair/awesome-gis
- https://github.com/pangeo-data/awesome-open-climate-science
- https://github.com/softwareunderground/awesome-open-geoscience
- https://github.com/awesomedata/awesome-public-datasets
- https://github.com/awesomedata/awesome-public-datasets#gis
- https://github.com/RadarCODE/awesome-sar
- https://github.com/chrieke/awesome-satellite-imagery-datasets
- https://github.com/RoboDonut/awesome-spatial

If you have another entry similar to these which you feel should be included, please feel free to submit a PR.

## Structure

ENTRIES MUST NOT BE DUPLICATED.

Wherever possible/ reasonable, items should be listed in order oof priority (where relevant) and then alphabetically. For example, national level infrastructure services, it is likely that priority is given to higher level projects (e.g. a national SDI), following which services may be listed in alphabetical order.

Items are structured hierarchically as should be apparent by increasing the increment of the header within each section.

If an entry is suitable for inclusion in more than one category, it must be listed in the category MOST suitable for it's discovery as outlined by the structure detailed below.

The majority of the services listed at global or regional level should be public entities, foundations, or similar services. Commercial data suppliers may be listed at the national level, however where the extents of their products extend beyond national or regional levels they may be more appropriately listed under the [Commercial Vendors page](vendors.md). Products that have global level coverage and no/ limited competition in the marketplace (e.g. Google Earth Engine) are also suitable for the main list, especially in instances where the service listed is an open data catalogue or similar.

**Regions**: If the data extent is regional, or the source is a regional entity, then the data should be classified by region, locale, or country.

Most spatial data of the highest quality is produced and managed at the national level. As such it makes sense to categorise data in this manner so that data sources with the highest integrity are discoverable.

**World**: This is most suitable for global datasets and projects that focus on a wide variety of data sources and types, such as basemaps and Open Street Map data.

Where the scope of the data/ service may be global but the primary purpose of the data store is for an application specific purpose, topics should be used.

**Topics**: Application specific projects, services, or data related to a particular field of interest. These should be at global or at least regional/ continental in scope, otherwise they should simply be listed within the relevant national section.

**Services**: A curated list of OGC services (WMS/ WFS/ CSW)/ OGC API, ArcGIS REST, or custom APIs and data endpoints which may be inherently useful. These are sometimes, but not always, published on the relevant sites and may require some effort to discover.

### Regional Hierarchy

Regional sections should be indented accordingly using the relevant header level.

Global (`<h3>`)
- Continental
  - Sub Continental/ Regional
  - Country Codes: These should follow the [ISO 3166-2](https://en.wikipedia.org/wiki/ISO_3166-2) naming convention
  - Other Countries: Where states/ entities or regions (or recognition of their sovereignty is under dispute) are not recognised by the ISO 3166-2 standard, they may be included at the bottom of the countries list with an `x-` prefix along with a unique identifier. Clarification on the entity should be provided in an excerpt.
    - Locality: As each country organises adminstrative abnd geographic regions differently into Parishes, Provinces, Counties, States or any other subdivisions, this may vary from entity to entity. This should have little impact as long as the indentation level remains consistent.

### Subsections

Each category may be further divided into arbitrary subsections to better support categorisation of services by using a header with an additional indentation.

## Metadata

Capturing metadata on available services is difficult especially in a simple list format. As such, distinct tags have been outlined according to a particular characteristic and may be associated with each entry using a simple emoji in accordance with the provided legend/ key.

## Legend

The legend for outlining core metadata characteristics for entries is listed in the readme. As additional categories and alternative methods of highlighting content may be desirable, and extended legend is provided at the bottom of the readme to assist with content discovery.

### Availability and consistency checks

Data services differ from many other data source types typically available in awesome lists, as with software projects and libraries, the source is typically static and consistently available.

Data services, by contrast, require resources and maintenance, and their services are subject to scale utilisation and load.

As such it is necessary to monitor and test these services, or at least identify services that become outdated or become unavailable. Provision for this process is made by utilising a date prefix (for listing last check) and an emoji identifier as outlined in the *Validity* section of the legend description of the readme.

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

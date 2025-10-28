# awesome-berlin-data [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![RSS](https://img.shields.io/badge/Subscribe-RSS-blue.svg)](https://github.com/tifa365/awesome-berlin-data/commits/main.atom)

##### Community list of open data sources, APIs, tools, applications, and resources for Berlin.

Berlin is one of Europe's leading cities in open data and digital innovation. This list brings together datasets, APIs, tools, and applications that help citizens, researchers, developers, and urban planners better understand and improve Germany's capital.

Have something to add or change? Open a [pull request](../../pulls) or [issue](../../issues)!

------------------------------

### Table of Contents

- [Art & Street Culture](#art--street-culture)
- [Education & Schools](#education--schools)
- [Environment & Nature](#environment--nature)
- [Government & Politics](#government--politics)
- [Maps & Visualizations](#maps--visualizations)
- [Open Data Tools & APIs](#open-data-tools--apis)
- [Transportation & Mobility](#transportation--mobility)
- [Urban Planning & Land Use](#urban-planning--land-use)

------------------------------

## Art & Street Culture

Data and projects documenting Berlin's vibrant street art and urban culture.

- 🎵 [Berlin Club History](https://github.com/tifa365/berlin_club_history) - Dataset of 106 closed/historic nightclubs and music venues in Berlin from the late 1960s through 2020. Includes GPS coordinates, addresses, years of operation, music genres, and historical context. Available in CSV and GeoJSON formats. Documents Berlin's legendary club culture including venues like Club ZMF and others.
- 🧘 [Korkmännchen Berlin](https://github.com/tifa365/korkmaennchen_berlin) - Comprehensive dataset of 220+ locations of Korkmännchen (cork figure street yogis) across Berlin. Includes GPS coordinates, street addresses, and 81 openly licensed photos from Wikimedia Commons of these tiny urban art pieces created by artist Josef Foos since 2006.

------------------------------

## Education & Schools

Data and tools related to schools and education in Berlin (and Germany).

- 🏫 [jedeschule-scraper](https://github.com/Datenschule/jedeschule-scraper) - Scrapers for German school data across all federal states (including Berlin), providing a unified data format. Includes school locations, types, and metadata. Data available via API at [jedeschule.codefor.de](https://jedeschule.codefor.de/).

------------------------------

## Environment & Nature

Environmental data and applications related to Berlin's natural spaces and sustainability.

- 🏊 [Badegewässer Berlin](https://www.berlin.de/lageso/gesundheit/gesundheitsschutz/badegewaesser/liste-der-badestellen/) - Official data from LAGeSo (State Office for Health and Social Affairs) providing daily updates on water quality at Berlin's public swimming locations. Includes information on water quality measurements, accessibility, and amenities at bathing spots across the city.
- ⛲ [Berliner Trinkbrunnen Analyse](https://github.com/tifa365/berliner_trinkbrunnen_analyse) - Interactive maps analyzing Berlin's drinking fountains. Compares data from Berliner Wasserbetriebe (BWB) with OpenStreetMap, providing detailed analysis and visualization of public water fountain locations across the city.
- ⚡ [Berliner EnergieCheckpoint](https://github.com/technologiestiftung/energiekarte) - Explorable map showing energy consumption of public buildings managed by BIM (Berliner Immobilienmanagement). Visualizes which buildings consume how much energy and potential savings through renovation, supporting Berlin's climate neutrality goal by 2045.
- 🌳 [Gieß den Kiez](https://github.com/technologiestiftung/giessdenkiez-de) - Interactive platform for citizen participation in watering Berlin's urban trees. Shows almost all street and park trees with water requirements, age, and species data. Users can adopt trees, mark them as watered, and track watering activities. Open-source project by Technologiestiftung Berlin, adapted by multiple cities.
- 🌬️ [ODIS Luftqualität](https://github.com/technologiestiftung/odis-luftqualitaet) - Interactive map exploring Berlin's air quality based on 2024 yearly averages. Click locations or enter addresses to view pollution levels with improvement recommendations rated from "Very Low" to "High". Based on Luftschadstoffprognose data.

------------------------------

## Government & Politics

Tools and data related to Berlin's government, parliament, and political processes.

- 🎭 [Fairgnügen](https://github.com/technologiestiftung/fairgnuegen) - Searchable database of free or reduced-price cultural, sports, educational, and leisure activities for Berlin residents receiving social benefits. Features map-based discovery with filters for event location, discount type, and target groups. Promotes social participation through voluntary Berlin state services.
- 🏛️ [Parla](https://github.com/technologiestiftung/parla-frontend) - AI-powered search tool for Berlin parliamentary documents. Makes 11,000+ written requests (Schriftliche Anfragen) and main committee procedures searchable using large language models. Provides answers with source references from the PARDOK parliamentary documentation system. Developed by CityLAB Berlin.

------------------------------

## Maps & Visualizations

Interactive maps and visual applications for exploring Berlin.

- 🎨 [Kiezcolors](https://github.com/technologiestiftung/kiezcolors) - Interactive map-based tool that generates postcards showing land-use distribution in any Berlin neighborhood. Select a location and see how space is divided between categories like traffic, nature, water, residential, and recreation using ALKIS open data.
- 📸 [Luftbilder Berlin](https://github.com/codeforberlin/luftbilder.berlin.codefor.de) - Web application displaying historical aerial photographs of Berlin from 2004-2022 (and 1928). Search by address to observe how the city has changed over time at any location. Data sourced from Berlin's FIS-Broker.
- 🗺️ [OSM Berlin & Verkehrswende](https://github.com/osmberlin) - Organization hosting OpenStreetMap projects for sustainable transport and Berlin/Brandenburg. Includes parking data processing, traffic sign tools, street space maps, and Mapillary street coverage analysis. Active community with monthly meetups.
- 🎄 [WeihnachtsmarktFinder](https://github.com/technologiestiftung/weihnachtsmarktkarte) - Interactive map of Christmas markets in Berlin with filters for opening times, entry fees, special attractions, and ÖPNV proximity. Includes [open dataset](https://daten.berlin.de/datensaetze/simple_search_wwwberlindesenwebservicemaerktefesteweihnachtsmaerkte) annually updated by Senate Department for Economics, Energy and Public Enterprises.

------------------------------

## Open Data Tools & APIs

Tools, APIs, and applications for accessing and visualizing Berlin's open data.

- 🗂️ [Berlin Open Data Portal](https://daten.berlin.de/) - Official open data portal of Berlin containing thousands of datasets from various governmental departments. Includes data on demographics, environment, transportation, urban planning, culture, and more. Datasets are available in multiple formats (CSV, JSON, XML, etc.) with APIs for programmatic access.
- ✅ [Berlin Open Data Metadata Quality Assessment](https://github.com/tifa365/berlin_opendata_assesment) - Python tool that evaluates metadata quality of Berlin's Open Data Portal using FAIR principles (Findable, Accessible, Interoperable, Reusable). Based on opendata.swiss methodology, adapted for Berlin's DCAT-AP.de schema. Generates quality scores and ratings across five dimensions.
- 🚀 [Berlin Open Data Starter Code](https://github.com/tifa365/starter-code-open_data_berlin) - Preconfigured Python Jupyter Notebooks and R Markdown files for all CSV datasets on Berlin Open Data Portal. Each file comes with metadata, descriptions, data links, and starter code. One-click opening in Google Colab supported.
- 📊 [Kerndatensätze Monitor](https://github.com/technologiestiftung/kerndatensaetze-monitor) - Creates access to ~100 core datasets identified as most valuable for Berlin's urban society across 10 categories. Documents openness status of datasets, tracks publication progress, and collaborates with administration to progressively open data. Official measure of Berlin's Open Data Strategy (adopted Nov 2023), based on North Rhine-Westphalia model catalog.
- 🤖 [DCAT-AP.de AI Analyzer](https://github.com/tifa365/dcat_ap_de_ai-analyzer) - AI-powered metadata quality analyzer for DCAT catalogs. Uses LLMs to assess semantic quality of titles and descriptions, checks DCAT conformity, detects hidden nulls, duplicates, and text issues. Adapted from Zurich's OGD analyzer for Berlin's DCAT-AP.de standard.
- 🔍 [ODIS GeoExplorer](https://github.com/technologiestiftung/odis-geoexplorer) - AI-powered search tool for Berlin's geodata. Uses vector embeddings to find relevant datasets from FIS-Broker and Berlin Open Data Portal based on natural language queries. Provides AI-generated explanations of dataset content. Prototype by Open Data Informationsstelle Berlin.
- 🏢 [Technologiestiftung Berlin](https://github.com/technologiestiftung) - Organization maintaining countless open-source projects for Berlin including interactive maps, data visualizations, APIs for trees, air quality, parliamentary data, neighborhood analysis tools, and WFS data explorers. All projects use Berlin's open data and are publicly available under open licenses.

------------------------------

## Transportation & Mobility

Data, maps, and tools related to Berlin's public transportation and mobility infrastructure.

- 🚇 [awesome-berlin-transit](https://github.com/tifa365/awesome-berlin-transit) - Comprehensive collection of 87+ open-source tools, APIs, and datasets for Berlin public transport (VBB/BVG). Includes REST APIs, GTFS datasets, real-time monitoring tools, transit map generators, and much more by @derhuerst and others.
- 🔄 [Berlin S-Bahn Ring GeoJSON](https://gist.github.com/derhuerst/9a3fca091cb1d48ad0b28743f86676c4) - GeoJSON data for the Berlin S-Bahn Ringbahn (circular railway line). Useful for mapping applications and geographic analysis of Berlin's iconic ring line.
- 🎫 [Berliner Tarifkarte](https://github.com/technologiestiftung/tarifkarte) - Interactive map visualizing Berlin's public transport fare zones (A, B, C). Shows exactly where fare zone boundaries run and which stations are reachable with different ticket types. Built with Next.js using open VBB (Verkehrsverbund Berlin-Brandenburg) GTFS data.

------------------------------

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors to this list have waived all copyright and related or neighboring rights to this work.

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

To add a new entry:
1. Fork this repository
2. Add your entry in the appropriate section
3. Ensure your link and description are clear and concise
4. Submit a pull request

## About

This list is maintained by the community and aims to be a comprehensive resource for anyone interested in Berlin's open data ecosystem. Listing of a project/resource does not imply endorsement.

Last updated: 2025-10-21

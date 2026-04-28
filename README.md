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
- [Housing & Social](#housing--social)
- [Maps & Visualizations](#maps--visualizations)
- [Open Data Tools & APIs](#open-data-tools--apis)
- [Transportation & Mobility](#transportation--mobility)
- [Urban Planning & Land Use](#urban-planning--land-use)

------------------------------

## Art & Street Culture

Data and projects documenting Berlin's vibrant street art and urban culture.

- 🎵 [Berlin Club History](https://github.com/tifa365/berlin_club_history) - Dataset of 106 closed nightclubs and music venues from late 1960s through 2020 with GPS coordinates and historical context in CSV/GeoJSON.
- 🗿 [Bildhauerei in Berlin](https://bildhauerei-in-berlin.de/) - Interactive platform documenting sculptures and plastic artworks across Berlin with map, search filters, and [JSON API](https://bildhauerei-in-berlin.de/wp-content/plugins/bitgilde-bib/dataprovider.php) providing GPS coordinates and metadata (verify usage rights before use).
- 📚 [Bücherschränke Berlin](https://github.com/tifa365/buecherschraenke_berlin) - Scraper and dataset of ~57 public bookshelves across Berlin with GPS coordinates and descriptions in GeoJSON format.
- 🧘 [Korkmännchen Berlin](https://github.com/tifa365/korkmaennchen_berlin) - Dataset of 220+ cork figure street yogi locations with GPS coordinates and 81 Wikimedia Commons photos.
- 🏓 [Tischtennisplatten Berlin](https://github.com/tifa365/tischtennisplatten_berlin) - Collection of 2,710 ping pong table locations across Berlin with geographic coordinates in JSON format.

------------------------------

## Education & Schools

Data and tools related to schools and education in Berlin (and Germany).

- 🏫 [jedeschule-scraper](https://github.com/Datenschule/jedeschule-scraper) - Scrapers for German school data across all federal states with unified format and API at jedeschule.codefor.de.
- 🎒 [Kita Navigator Berlin](https://kita-navigator.berlin.de/) - Official Berlin daycare search with 2,856 Kitas including availability status, coordinates, and [OpenAPI specification](https://github.com/tifa365/kitas_berlin).
- 📡 [Internet@Schule in Berlin](https://www.tursics.de/story/schule-breitband-2020/) - Interactive maps showing internet connection speeds at Berlin schools by district (2020, outdated), could be updated with [dataset](https://daten.berlin.de/datensaetze/breitband-ausbau-der-berliner-schulen-1430033).

------------------------------

## Environment & Nature

Environmental data and applications related to Berlin's natural spaces and sustainability.

- 🏊 [Badegewässer Berlin](https://www.berlin.de/lageso/gesundheit/gesundheitsschutz/badegewaesser/liste-der-badestellen/) - Official LAGeSo data with daily water quality updates at Berlin's public swimming locations.
- ⛲ [Berliner Trinkbrunnen Analyse](https://github.com/tifa365/berliner_trinkbrunnen_analyse) - Interactive maps analyzing Berlin's drinking fountains comparing Berliner Wasserbetriebe data with OpenStreetMap.
- ⚡ [Berliner EnergieCheckpoint](https://github.com/technologiestiftung/energiekarte) - Map showing energy consumption of BIM-managed public buildings with renovation savings potential.
- 🔋 [Energieatlas Berlin](https://energieatlas.berlin.de/) - Interactive energy map and 3D model of ~550,000 buildings with consumption data and renewable potential scenarios.
- 🌳 [Gieß den Kiez](https://github.com/technologiestiftung/giessdenkiez-de) - Platform for citizens to adopt and track watering of Berlin's street and park trees with species data.
- 🌬️ [ODIS Luftqualität](https://github.com/technologiestiftung/odis-luftqualitaet) - Interactive air quality map based on 2024 yearly averages with location-specific pollution levels and recommendations.

------------------------------

## Government & Politics

Tools and data related to Berlin's government, parliament, and political processes.

- 📰 [Amtsblatt Berlin Archiv](https://github.com/tifa365/amtsblatt-berlin-scraper) - PDF archive of Berlin's official gazette with Wayback Machine fallback (berlin.de only keeps last 6 issues).
- 🗳️ [awesome-berlinwahl-2026](https://github.com/tifa365/awesome-berlinwahl-2026) - Curated list of official datasets, maps, timelines, FAQs, and election-boundary resources for the Berlin 2026 Abgeordnetenhaus and BVV elections.
- 💰 [Berlin Haushaltskürzungen 2025](https://berlin-haushalt25.nand.io/) - Interactive visualization of Berlin's 2025 budget cuts showing ~3 billion € savings across departments.
- 🏙️ [Berlin Budget Skyline](https://tifa365.github.io/berlin-budget-skyline/) - Turns Berlin's public budget lines into a navigable 3D skyline where each building represents a budget item, with search, filtering, detail panels, and links back to the official budget visualization. [Source code](https://github.com/tifa365/berlin-budget-skyline).
- 💼 [Berlin Karriereportal](https://www.karriereportal-stellen.berlin.de/) - Official job portal for Berlin administration positions with unofficial [OpenAPI specification](https://github.com/tifa365/berlin-karriereportal-api-schema) documenting search, filter, and RSS endpoints.
- 📊 [Digitalisierungs-Dashboard](https://digitalisierungs-dashboard.berlin.de/) - Live dashboard tracking digitalization progress of 6,800+ Berlin administrative services with OZG maturity levels and [OpenAPI schema](https://github.com/tifa365/digitalisierungs-dashboard-berlin-scraper).
- 🎭 [Fairgnügen](https://github.com/technologiestiftung/fairgnuegen) - Searchable database of free/reduced-price cultural and leisure activities for Berlin social benefit recipients.
- ⚖️ [Gesetze Berlin API](https://github.com/tifa365/berliner-rechtsprechungsdatenbank-scraper) - Unofficial API documentation for Berlin's legal database with 78k+ laws and court decisions.
- 📜 [Parlamentsdokumentation Open Data](https://www.parlament-berlin.de/dokumente/open-data) - XML metadata of parliamentary documents (Drucksachen, Plenarprotokolle, Ausschussprotokolle, Schriftliche Anfragen) since 1989, updated daily, with [XML schema documentation](https://www.parlament-berlin.de/media/download/4322).
- 🏛️ [Parla](https://github.com/technologiestiftung/parla-frontend) - AI-powered search tool for 11,000+ Berlin parliamentary documents and committee procedures.

------------------------------

## Housing & Social

Data and tools analyzing Berlin's housing market, rental prices, and social issues.

- 🏘️ [AirBnb vs Berlin](https://airbnbvsberlin.de/) - Data visualization of Airbnb listings showing short-term rental clusters and their impact on Berlin's housing market.
- 📊 [Mietenwatch](https://www.mietenwatch.de/) - Analysis of ~80,000 rental listings showing affordable neighborhoods based on household income.

------------------------------

## Maps & Visualizations

Interactive maps and visual applications for exploring Berlin.

- 📊 [awesome-berlin-datenjournalismus](https://github.com/tifa365/awesome-berlin-datenjournalismus) - Curated list of data journalism projects about Berlin from Tagesspiegel, Morgenpost and others.
- 🕰️ [Berlin 1928](https://1928.tagesspiegel.de/) - Swipe map comparing 1928 aerial imagery with modern photos showing how Berlin changed over time.
- 🛣️ [Berliner Strassen](https://github.com/tifa365/Berliner_Strassen) - Scrollytelling data journalism project about Berlin street names, memory, and urban history built with MapLibre and Scrollama using processed street and address GeoJSON.
- 🎨 [Kiezcolors](https://github.com/technologiestiftung/kiezcolors) - Tool generating postcards showing land-use distribution in any Berlin neighborhood using ALKIS data.
- 🎪 [Kulturkataster Berlin](https://kulturkataster.berlin/) - Interactive map of roughly 2.5k cultural locations across Berlin with 15 categories and search filters (data available via email to info@kulturkataster.berlin, undocumented API endpoints exist).
- 📸 [Luftbilder Berlin](https://github.com/codeforberlin/luftbilder.berlin.codefor.de) - Web app displaying historical aerial photographs from 2004-2022 searchable by address.
- 🗺️ [OSM Berlin & Verkehrswende](https://github.com/osmberlin) - OpenStreetMap projects for sustainable transport including parking data, traffic signs, and street space maps.
- ⚔️ [Straßenkrieg](https://hanshack.com/strassenkrieg/) - Interactive map tagging Berlin street names with war and military references.
- 🎄 [WeihnachtsmarktFinder](https://github.com/technologiestiftung/weihnachtsmarktkarte) - Interactive map of Berlin Christmas markets with filters for times, fees, and attractions.

------------------------------

## Open Data Tools & APIs

Tools, APIs, and applications for accessing and visualizing Berlin's open data.

- 🗂️ [Berlin Open Data Portal](https://daten.berlin.de/) - Official portal with thousands of datasets from Berlin's governmental departments in CSV, JSON, XML formats with APIs.
- 📱 [Berlin Open Data Applications RSS](https://daten.berlin.de/anwendungen/rss.xml) - RSS feed of applications built with Berlin open data including TopoExport, Hallo Baum, Kiezcolors, and more (mostly outdated).
- ✅ [Berlin Open Data Metadata Quality Assessment](https://github.com/tifa365/berlin_opendata_assesment) - Python tool evaluating metadata quality using FAIR principles for Berlin's Open Data Portal.
- 🚀 [Berlin Open Data Starter Code](https://github.com/tifa365/starter-code-open_data_berlin) - Preconfigured Python/R notebooks for all CSV datasets with metadata and one-click Google Colab access.
- 📊 [Kerndatensätze Monitor](https://github.com/technologiestiftung/kerndatensaetze-monitor) - Tracks ~100 core datasets identified as most valuable for Berlin's Open Data Strategy.
- 🏙️ [Berlin Open Data MCP Server](https://github.com/tifa365/berlin-opendata-mcp) - MCP Server for accessing Berlin's open data with 6 tools for CKAN catalog search, analysis, and exploration of 2,500+ datasets across 25 categories.
- 🤖 [DCAT-AP.de AI Analyzer](https://github.com/tifa365/dcat_ap_de_ai-analyzer) - AI-powered metadata quality analyzer for DCAT catalogs using LLMs.
- 🔍 [ODIS GeoExplorer](https://github.com/technologiestiftung/odis-geoexplorer) - AI-powered search for Berlin's geodata using natural language queries.
- 🃏 [ODIS Open Data Card Game](https://github.com/technologiestiftung/odis-cardgame) - Top Trumps-style card game featuring Berlin's 58 administrative areas with open data categories.
- 📍 [POIs Berlin](https://github.com/tifa365/pois-berlin) - Curated collection of open datasets for Berlin points of interest covering education, environment, history, and street art with geographic coordinates.
- 🏢 [Technologiestiftung Berlin](https://github.com/technologiestiftung) - Organization maintaining open-source projects for Berlin including maps, visualizations, and APIs.

------------------------------

## Transportation & Mobility

Data, maps, and tools related to Berlin's public transportation and mobility infrastructure.

- 🚇 [awesome-berlin-transit](https://github.com/tifa365/awesome-berlin-transit) - Collection of 87+ open-source tools, APIs, and datasets for Berlin public transport (VBB/BVG).
- 📶 [WLAN an Berliner Bahnhöfen: Wenn Daten auf der Strecke bleiben](https://www.linkedin.com/pulse/wlan-berliner-bahnh%C3%B6fen-wenn-daten-auf-der-strecke-tim-fangmeyer-c0tpf/) - Article analyzing WiFi coverage at Berlin stations with scraped station data.

------------------------------

## Urban Planning & Land Use

Tools and data related to urban development, construction projects, and demographic changes.

- 🏗️ [Hier Baut Berlin](https://web.archive.org/web/20241208091442/https://hierbautberlin.de/) - (Outdated) Crowdsourced map scraping Berlin's planning announcements with email alerts for new projects.

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

Last updated: 2026-03-30

# Awesome Urban Mobility [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/brandonhimpfen/awesome-lists)

[![Support Open Work](https://img.shields.io/badge/Support-Open%20Work-0A0A0A?style=flat&logo=github)](https://github.com/brandonhimpfen/support) 
[![GitHub Sponsor](https://srv-cdn.himpfen.io/badges/github/github-flat.svg)](https://github.com/sponsors/brandonhimpfen) 
[![Buy Me a Coffee](https://srv-cdn.himpfen.io/badges/buymeacoffee/buymeacoffee-flat.svg)](https://buymeacoffee.com/brandonhimpfen) 
[![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com/brandonhimpfen) 
[![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://www.paypal.com/donate/?hosted_button_id=3LLKRXJU44EJJ) <br />
[![X](https://srv-cdn.himpfen.io/badges/twitter/twitter-flat.svg)](https://x.com/ListsAwesome) 
[![Facebook](https://srv-cdn.himpfen.io/badges/facebook-pages/facebook-pages-flat.svg)](https://www.facebook.com/awesomelists)

> A curated list of resources for urban mobility, public transit data standards, Mobility-as-a-Service (MaaS) frameworks, micromobility protocols, and multi-modal routing engines.

Urban mobility technology enables sustainable, efficient, and accessible transportation networks through open transit data standards, shared mobility data protocols, dynamic routing engines, and integrated MaaS solutions. This list is intended for transit data engineers, urban transport planners, mobility software developers, and municipal transportation leads.

_Support ongoing maintenance and curation via [GitHub Sponsors](https://github.com/sponsors/brandonhimpfen)._

## Contents

- [Public Transit Data Standards](#public-transit-data-standards)
- [Multimodal Routing & Journey Planning](#multimodal-routing--journey-planning)
- [Mobility-as-a-Service (MaaS) & Shared Mobility](#mobility-as-a-service-maas--shared-mobility)
- [Traffic Simulation & Demand Modeling](#traffic-simulation--demand-modeling)
  - [Microscopic & Macroscopic Simulators](#microscopic--macroscopic-simulators)
  - [Accessibility & Isochrone Analytics](#accessibility--isochrone-analytics)
- [Related Awesome Lists](#related-awesome-lists)

## Public Transit Data Standards

Open specifications, validation suites, and processing tools for public transit schedules, real-time alerts, and service disruptions.

- [GTFS Specification](https://github.com/google/transit) — The General Transit Feed Specification defining a common format for public transportation schedules and associated geographic information.
- [GTFS-Realtime Specification](https://github.com/MobilityData/gtfs-realtime-bindings) — Feed specification for public transit agencies to provide real-time updates about location, arrivals, and service alerts.
- [NeTEx (Network and Timetable Exchange)](https://github.com/NeTEx-CEN/NeTEx) — European general standard XML format for exchanging public transport schedule, network topology, and fare structures.
- [SIRI (Service Interface for Real Time Information)](https://github.com/SIRI-CEN/SIRI) — XML-based European standard interface for exchanging real-time information between public transport systems.

## Multimodal Routing & Journey Planning

Open-source routing engines and graph solvers for calculating itineraries across walking, cycling, driving, and public transit modes.

- [OpenTripPlanner (OTP)](https://github.com/opentripplanner/OpenTripPlanner) — Open-source multi-modal trip planner that relies on OpenStreetMap data and GTFS/GTFS-RT transit feeds.
- [R5 (Rapid Realistic Routing)](https://github.com/conveyal/r5) — High-performance multimodal routing engine developed by Conveyal for scenario planning and accessibility analytics.
- [Valhalla](https://github.com/valhalla/valhalla) — Open-source routing engine written in C++ providing turn-by-turn navigation, map matching, and isochrones.
- [MOTIS](https://github.com/motis-project/motis) — Multi-modal transport optimization and information system capable of routing across intercity and local transit data streams.

## Mobility-as-a-Service (MaaS) & Shared Mobility

Data standards, open engines, and protocol specifications for integrating bikeshare, e-scooters, ride-hailing, and micro-transit.

- [GBFS (General Bikeshare Feed Specification)](https://github.com/MobilityData/gbfs) — Open data standard for shared mobility feeds, delivering real-time status of bikeshare, scooters, and mopeds.
- [MDS (Mobility Data Specification)](https://github.com/openmobilityfoundation/mobility-data-specification) — Standardized digital APIs used by municipalities to manage micro-mobility service providers in public rights-of-way.
- [TOMP-API (Transport Operator to MaaS Provider API)](https://github.com/TOMP-WG/TOMP-API) — Standardized API specification facilitating booking, payment, and access control between MaaS providers and transport operators.
- [Open-MaaS Core Engine](https://github.com/maas-global) — Modular architecture for integrating multi-operator ticketing, multimodal search, and mobility subscription models.

## Traffic Simulation & Demand Modeling

Computational tools, network solvers, and agent-based frameworks for modeling vehicle flow, transit demand, and urban accessibility.

### Microscopic & Macroscopic Simulators

- [Eclipse SUMO (Simulation of Urban MObility)](https://github.com/eclipse-sumo/sumo) — Open-source microscopic traffic simulation package designed to handle large multi-modal transport networks.
- [MATSim (Multi-Agent Transport Simulation)](https://github.com/matsim-org/matsim) — Open-source framework for implementing large-scale agent-based transport simulations and travel demand models.

### Accessibility & Isochrone Analytics

- [r5r](https://github.com/ipeaGIT/r5r) — R package for rapid realistic routing and accessibility calculations using the R5 routing engine.
- [Peartree](https://github.com/kuanb/peartree) — Python library for converting GTFS transit data into network graph representations for accessibility analysis.

## Related Awesome Lists

- [Awesome GIS](https://github.com/brandonhimpfen/awesome-gis) — Geographic Information Systems, spatial data analysis, and web mapping libraries.
- [Awesome OpenStreetMap](https://github.com/brandonhimpfen/awesome-openstreetmap) — Routing engines, mapping tools, and spatial data extraction tools built on OSM data.
- [Awesome Fleet Management](https://github.com/brandonhimpfen/awesome-fleet-management) — Vehicle telematics, GPS tracking, and route optimization solvers.
- [Awesome Digital Twins for Cities](https://github.com/brandonhimpfen/awesome-digital-twins-cities) — Urban digital twins, 3D city modeling, and urban simulation engines.

## Contribute

Contributions are welcome. Please ensure your submission fully follows the requirements outlined in [`CONTRIBUTING.md`](CONTRIBUTING.md), including formatting, scope alignment, and category placement.

Pull requests that do not adhere to the contribution guidelines may be closed.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)

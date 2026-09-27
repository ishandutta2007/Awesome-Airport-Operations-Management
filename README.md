# Awesome-Airport-Operations-Management

## Top Airport Operations Management Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Airport Resource Optimization, Flight Information & Operational Intelligence*  

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Airport Operations Management**. These tools manage airport resource allocation, flight information display, baggage handling, passenger flow, turnaround management, and collaborative decision-making (A-CDM) for airports, ground handlers, and aviation authorities.



**Examples** include Veovo, Amadeus Airport Operational Database, SITA Airport Management, ADB Safegate, RESA Airport Suite, Inform Airport, GateKeeper Systems, Damarel FiNDnet, Amorph Systems, and AeroCloud (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom operational workflows, and transparent airport data management — ideal for airports, ground handlers, researchers, and developers building vendor-independent airport operations solutions.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Veovo](https://www.veovo.com/)**  

  Airport operations platform with passenger flow prediction, resource management, and real-time situational awareness for airports worldwide.



- **[Amadeus Airport Operational Database](https://amadeus.com/en/airports)**  

  Comprehensive airport operations suite covering flight information, resource allocation, and passenger processing.



- **[SITA Airport Management](https://www.sita.aero/solutions/sita-airport-management/)**  

  Integrated airport operations platform for flight information, resource management, and collaborative decision-making.



- **[ADB Safegate](https://www.adbsafegate.com/)**  

  Airport operations and airfield management solutions including apron management, docking systems, and visual guidance.



- **[RESA Airport Suite](https://www.resa.aero/)**  

  Airport management software covering resource planning, flight information, and billing for regional and international airports.



- **[Inform Airport](https://www.inform-software.com/)**  

  AI-powered airport operations optimization with resource allocation, turnaround management, and passenger flow analytics.



- **[GateKeeper Systems](https://www.gatekeepersystems.com/)**  

  Airport operations management platform with resource scheduling, work orders, and asset management capabilities.



- **[Damarel FiNDnet](https://www.damarel.com/)**  

  Airport resource management and billing system for ground handlers and airports, covering slots, counters, and infrastructure.



- **[Amorph Systems](https://www.amorph-systems.com/)**  

  Airport operations management with real-time resource allocation and turnaround monitoring.



- **[AeroCloud](https://www.aerocloud.aero/)**  

  Intelligent airport management platform with flight information, resource management, and passenger analytics.



## Open-Source GitHub Projects



- **[Airport Manager (Microservices)](https://gitlab.fi.muni.cz/xnadzam/airport-manager)**  

  Maven multi-module Spring Boot project modeling a small airport operations system as separate microservices for airports, planes, flights, and employees. Features CRUD operations, flight lifecycle management, crew assignment, and aircraft availability tracking. Built with Java 25, Spring Boot 4.0.4, and Docker Compose support.



- **[Airport Traffic Control Simulator](https://github.com/Henrique-Versiani/Airport-Traffic-Control)**  

  Simulation of an air traffic control system for a high-demand international airport, developed in C with PThreads. Implements multithreading, resource management (runways, gates, control towers), deadlock detection and treatment, starvation prevention via aging, and comprehensive logging. Models distinct rules for domestic and international flights.



- **[Airport Database Management System](https://github.com/Jana-Ahmed-20005/Airport-database-managment-system)**  

  Fully integrated platform designed to control and optimize major airport operations including flight scheduling, passenger check-in, baggage handling, and security monitoring. Supports multiple user types (Passengers, Airline Employees, Flight Crew) with role-based functionality for coordination across departments.



- **[Airport Database Management System (SQL)](https://github.com/poetabdullah/Airport-Database-Management-System)**  

  Comprehensive airport management system built with Microsoft SQL Server and Django backend. Covers passenger management, flight schedules, baggage tracking, security protocols, fueling, maintenance, and resource allocation. Features authorization roles, stored procedures, triggers, indexing, and backup/recovery procedures.



- **[SOCFAI (Secure Open Collaboration Framework powered by AI)](https://www.socfai.com/)**  

  ITEA project developing an open-source, AI-powered framework for airport operations optimization. Features operational dashboards, AI-powered message hub, authentication services, predictive baggage analytics, passenger flow intelligence, air quality monitoring, and dynamic energy management. Validated at Izmir Adnan Menderes Airport with documented efficiency gains.



- **[Mercury](https://www.mercury-project.eu/)**  

  Open-source platform for evaluating air transport mobility developed by University of Westminster. Agent-based model tracking individual flights and passengers, with multimodality and door-to-door estimation capabilities. Simulates one day of operations at ECAC level (27K flights, 3.4M passengers) for ATM research and policy evaluation.



- **[Flight Schedule Optimization](https://github.com/monu808/Flight-Schedule-Optimization)**  

  AI-powered airline operations management dashboard designed to optimize flight schedules at busy airports. Features intelligent data transformation, delay prediction using machine learning, schedule optimization, cascade impact analysis, runway utilization optimization, and NLP query interface. Built with Python and Streamlit.



- **[Système Multi-Agent de Contrôle Aérien](https://github.com/amine-sabbahi/Application-SMA-pour-le-controle-aerien)**  

  Multi-Agent System (MAS) for air traffic control developed with JADE and JavaFX. Simulates aircraft, pilot, traffic manager, airline, and flow director agents to optimize traffic management, reduce congestion, and improve safety. Includes runway allocation and landing/takeoff request handling.



- **[skies-adsb](https://github.com/machineinteractive/skies-adsb)**  

  Real-time 3D air traffic display using unfiltered ADS-B data from RTL-SDR receivers. Deployable on Raspberry Pi, features custom map layers, aircraft photos via Planespotters.net, and FlightAware AeroAPI integration. Built with JavaScript, Python, and WebGL (Three.js).



- **[RealtimeFlightDisplay](https://github.com/SathvikCookie/RealtimeFlightDisplay)**  

  Compact desktop display using ESP32 and 3.5" touchscreen showing live flight arrivals. Fetches real-time data from OpenSky Network API, displays airline logos and flight info, and cycles flights automatically. Python prototype serving as data pipeline before hardware implementation.



- **[Radar ATC](https://github.com/Luffy0805/radar_atc)**  

  Luanti (Minetest) mod for air traffic surveillance, airport management, and ATC communication. Features real-time radar monitoring, airport creation with runway configuration, ATC request handling, radio communication, and NOTAM publishing. Requires laptop and airutils mods.



### Additional Strong Open-Source Options



- **BDAD_airportManagement** — SQL database designed from scratch to manage data related to a specific airport. Basic database management system with entity relationships and operational data structures.

- **TheFlightWall** — LED wall displaying live flight information using ESP32 and LED panels. Apache 2.0 licensed with data service integration for visualizing nearby air traffic.

- **FlightScnr Pi** — Raspberry Pi-based flight radar showing live aircraft on a circular radar display with rich flight details. Combines FlightRadar24, adsb.fi data, and Tomorrow.io weather with local web portal management.

- **LoadWorkData GUIs** — Aviation processing, telemetry, and telematics client GUIs for database operations. Features XML-based data management for aircraft, airlines, airports, and routes with Qt Designer interfaces.



**Frameworks for building custom airport operations solutions**: Combine **Airport Manager** microservices for core operational data management, **SOCFAI** for AI-powered predictive analytics and multi-stakeholder collaboration, **Mercury** for ATM simulation and policy evaluation, and **skies-adsb** or **RealtimeFlightDisplay** for real-time flight tracking and visualization. For database-centric implementations, **Airport Database Management System** projects provide production-ready schemas with role-based access and stored procedures.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Airport operations tools must comply with aviation regulations (ICAO Annex 14, EASA, FAA) and security standards.

- Self-hosted open-source solutions require proper aviation-grade security, reliability, and regulatory validation before operational deployment.



---



**Made for airports, ground handlers, aviation authorities, and airport technologists.**  

Let's make airport operations management more open, data-driven, and efficient.

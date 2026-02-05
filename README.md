# A Data-Driven Carpooling Application for Sustainable Urban Mobility in London

## Project description
This project investigates a data-driven approach to identifying feasible carpooling opportunities in London to support more sustainable urban mobility. The aim is to improve vehicle occupancy by matching commuters based on geographic proximity, route similarity, and travel constraints, using realistic road network data rather than simple straight-line distance measures.

The project focuses on the use of open data and synthetic commuting patterns to avoid ethical and privacy concerns associated with real personal mobility data. A prototype application will be developed to visualise and evaluate potential carpool matches and assess their efficiency and sustainability impact.

## Tools and technologies
The project is planned to be implemented using the following tools and libraries:

- **Python** – core programming language
- **Pandas / NumPy** – data manipulation and analysis
- **GeoPandas / Shapely / PyProj** – geospatial data processing
- **OSMnx** – extraction and modelling of London road networks from OpenStreetMap
- **NetworkX** – graph-based routing and network analysis
- **Scikit-learn** – clustering and analytical techniques
- **Matplotlib / Folium** – visualisation of routes and results
- **Streamlit** – development of an interactive prototype interface
- **GitHub** – version control and project documentation

## Methodological overview
The planned analytical pipeline consists of the following stages:

1. Acquisition of London road network data using OpenStreetMap
2. Generation of synthetic origin–destination commuter journeys
3. Data preprocessing and validation
4. Clustering of similar travel patterns
5. Route compatibility and detour analysis
6. Carpool matching and scoring
7. Visualisation and evaluation of results

## Challenges and limitations
- **Urban complexity:** London’s dense and large road network increases computational complexity and requires careful scoping to remain feasible.
- **Data realism:** Synthetic commuting data cannot fully capture real human behaviour, although it avoids privacy risks.
- **Time constraints:** Implementation must be carefully prioritised to focus on core functionality within the available timeframe.
- **Scalability:** Advanced optimisation techniques may be limited by computational resources.

## Ethics and sustainability
No real personal or location-identifiable commuter data will be collected or processed. Synthetic data is used to simulate commuting behaviour, reducing privacy risks and ethical concerns. The project explicitly considers sustainability by evaluating potential reductions in single-occupancy vehicle journeys.

## Repository status
At the Interim Progress Demonstration (IPD) stage, this repository contains project documentation, planning artefacts, environment configuration, and methodological design. Algorithmic implementation and prototype development will follow.

## Credits
**Student:** Syed Hussnain Ali Wasti (w1978727)  
**Degree:** BSc (Hons) Data Science and Analytics  
**Supervisor:** Salma Chahed  
**Institution:** University of Westminster  

## Acknowledgements
This project makes use of open data from OpenStreetMap and open-source Python libraries. Generative AI tools were used to assist with brainstorming and refining academic writing, in accordance with university guidance.

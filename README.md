# Detecting oil spills in marine environments using Automatic Identification System (AIS) and satellite datasets

## Overview      
It focuses on real-time oil spill detection and monitoring in marine environments by combining AIS data and satellite imagery.
System enhances detection accuracy and maritime safety through a multi-faceted approach that includes anomaly detection, real-time ship rerouting, and predictive oil spill spread modeling.

## Key Features
**1. Integrated AIS and Satellite Fusion**
Combines real-time AIS data and satellite imagery to monitor marine traffic and oil spills.
Uses DBSCAN, Autoencoders, and Neural Networks for early detection of vessel behavior anomalies.


**2. Oil Spill Detection & Prediction**
FMNet architecture analyzes SAR images for precise oil spill detection.
GNOME and BAOAC models predict the spread of the spill, assisting in response planning.



**3. Real-Time Ship Rerouting**
Dynamically reroutes vessels using live traffic and spill data, minimizing delays and avoiding affected areas.
Proposed Solution Workflow
Anomaly Detection: Real-time monitoring of AIS data using ML algorithms (DBSCAN/Autoencoders).
Oil Spill Detection: Analysis of SAR images using FMNet for precise masking of ships, oil, land, and water.
Predictive Modeling: Forecasting oil spill spread every 15 minutes using GNOME, generating maps for priority response.
Real-Time Alerts: Sends immediate notifications to coast guards and port authorities.
Ship Rerouting: Reconstructs routes for vessels based on oil spill data using the A* algorithm.


## Tech Stack
Python Libraries: Scikit-Learn, TensorFlow, Geopandas
Web Interface: HTML, CSS, JavaScript, React.js, Node.js
Other Tools: NIC One-Way Gateway, Heroku, AIS Decoder, Apache Spark, SnapTool, Google Earth Encoder


## Impact
This project aligns with SDG Goal 14 (Life Below Water), promoting sustainable practices by enabling early oil spill detection and swift responses. The solution minimizes ecological damage and supports marine biodiversity, ensuring healthier oceans.

## Challenges & Solutions
High Computational Needs: Utilized scalable cloud services to handle real-time data processing.
Weather Interference: Integrated advanced SAR preprocessing techniques to improve imagery accuracy under challenging conditions.
Stakeholder Coordination: Established communication channels to ensure real-time collaboration between authorities.


## Research & References
AIS data: AISHub, VesselFinder
SAR imagery processing: ESA SNAP, GNOME suite
For more research details, check the Research & References.


## Documentation
**Study On AIS stream, marine traffic stream and SAR datasets:**


https://www.aishub.net/

https://www.vesselfinder.com/

https://www.marinetraffic.com/en/ais/home/centerx:73.5/centery:13.5/zoom:8

https://step.esa.int/main

https://dataspace.copernicus.eu/ 



**Review on different techniques for anomaly detection:**

https://www.sciencedirect.com/science/article/abs/pii/S0957417423010631

https://www.mdpi.com/2077-1312/10/1/112



**Methods for detecting OIL spills accurately and early:**

https://www.mdpi.com/2072-4292/13/16/3174

https://appliedsciences.nasa.gov/sites/default/files/2022-10/SAR_Disasters_Part3.pdf 

https://www.mdpi.com/2072-4292/12/24/4090

https://ieeexplore.ieee.org/abstract/document/868885/

https://www.mdpi.com/2072-4292/11/12/1402



**Spatio-Temporal Analysis of Spills:**

https://www.sciencedirect.com/science/article/abs/pii/S0034425719304407

https://www.bonnagreement.org/site/assets/files/1081/special_on_volume_calculation_20160607.docx

https://www.mdpi.com/2072-4292/12/7/1225

https://www.sciencedirect.com/science/article/abs/pii/S0964569120303173

https://response.restoration.noaa.gov/oil-and-chemical-spills/oil-spills/response-tools/gnome-suite-oil-spill-modeling.html



**Route Construction:**

https://www.sciencedirect.com/science/article/pii/S0952197624008546




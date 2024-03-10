# MCSs_Climatology_NwSA

Final processed data used to generate all figures in the submitted manuscript (2024JD041159) to Journal of Geophysical Research - Atmospheres.
This repository contains a 20-year database of mesoscale convective systems tracked over northwestern South America using the new ATRACKCS algorithm. If you want to learn more about ATRACKCS go to the repository [ATRACKCS Repository](https:**//github.com/alramirezca/ATRACKCS)


Here you can find the MCS_climatology.csv file which contains the detailed list of MCS and other NetCDF files already processed by the authors that will help you to do different types of analysis over the region.

## General description of MCS database
The MCS_Climatology_NwSA file contains all convective systems tracked from 2001 to 2021. Below is a brief description of its columns:

**- track_id:** Track identifier. Each track contains a list of polygons representing the convective system at different time steps.

**- polygon_id:** Identifier of the polygon that represents a convective system at a given time and location.

**- time:** Date and time of detection of the convective system.

**- geometry:** Geometry (and location) of the polygon representing the convective system at a given time step.

**- area_tb:** Area in km2.

**- centroid:** Location of the centroid of the convective system.

**- mean_tb:** Mean brightness temperature of the convective system.

**- mean_p:** Mean precipitation rates of the convective system.

**- max_p:** Max value of precipitation of the convecive system.

**- intersection_percentage:** Percentage of interception between a convective system at time i and the same convective system at time i+1. 

**- distance:** Distance between consecutive convective systems.

**- direction:** Direction of propagation of the convective system.

**- total_duration:** Duration of the entire track in hours.

**- total_distance:** Total distance  of the entire track in km.

**- mean_velocity:** mean velocity of the entire track in km/h.

## Acknowledgements

This research was funded by the Colombian Ministry of Science, Technology and Innovation (MINCIENCIAS) through the project: “Implementación de un sistema de investigación y pronóstico meteorológico de corto plazo con el modelo WRF, para apoyo a sistemas de comando y control de la Fuerza Aérea Colombiana” (code 1115-852-70955) with funds from “Patrimonio Autónomo Fondo Nacional de Financiamiento para la Ciencia, la Tecnología y la Innovación, Fondo Francisco José de Caldas”.

## Cite as

Robledo Vanessa, Henao Juan. J, Mejía John F, Ramírez-Cardona Álvaro, Hernández, K. Santiago, Gómez-Ríos Sebastián, &  Rendón Angela M. (2024). Final database used in JGR-Atmospheres manuscript 2024JD041159 [Data set]. In Climatological Characteristics of Mesoscale Convective Systems in Northwestern South America Using a Persistence Technique.(v1.0). Zenodo. https://doi.org/10.5281/zenodo.10443552. 


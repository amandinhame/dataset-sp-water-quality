# Dataset: São Paulo Beaches Water Quality

## Context

One criteria that can be used to measure the water quality of the beaches is the density of Enterococcus, which indicates the fecal pollution in water. High values of the density of this bacteria indicates that the water quality is compromised and it represents risks to the bathers health. The measurements are performed weekly in several beaches in the state of São Paulo and they are used to classify the beaches as 'Proper' or 'Improper' for bathing.

## Content

This data represents over 68k measurements of Enterococcus taken weekly between 2012 and 2020, from 16 cities and 168 beaches/collection points in the São Paulo state.

## Acknowledgements

The original source of the data was provided by [CETESB](https://cetesb.sp.gov.br/).

## Inspiration

Explore the data and check if we can see improvements in the sanitary sewer system over the years.
Does the weather, tidal variance and holidays/vacations impact in the water quality of the beaches? How?
What are other factors that can influence the water quality?
Can we cross this data with other environment/development/etc data sources and see what can be done to improve our beaches?

## Collection Methodology

The measure of the density of Enterococcus is made every Sunday by collecting a sample of water in each station (at a 1m deep-water spot) and then filtering the sample with a membrane. This membrane is used to make a microbiological culture for 24 hours, when finally the counting of the number of colony-forming unit is performed. 
Source: [https://cetesb.sp.gov.br/praias/programa-de-monitoramento/]().

The data is published weekly by CETESB in a pdf report. To get the data I've used the python libraries `pandas` end `tabula` and did some manual fixes.

## Date Coverage

Temporal coverage: 01-01-2012 to 15-03-2020
Spacial coverage: São Paulo, SP - Brazil

## Others

This dataser is also available in: [https://www.kaggle.com/amandalk/sp-beaches-water-quality]().
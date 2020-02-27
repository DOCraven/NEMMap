# Mapping the NEM (NEM stands for here)

<img align="left" width="50" height="50" src="./docs/icons/open-book.svg">

## Context

This is do do a thing with the other thing

<img align="left" width="50" height="50" src="./docs/icons/flag.svg">

## Scope

Contains:

- Transmission and sub transmission lines (ie, 66kV and above)
- ZSS
- TS
- Generators

for the NEM (ie, QLD, NSW, VIC, TAS, SA) as well as some data from WA and NT.

<img align="left" width="50" height="50" src="./docs/icons/tools.svg">

## How to use

1. `Git clone <executable goes here>`
1. `python <executable> --inputs`

<img align="left" width="50" height="50" src="./docs/icons/network.svg">

## How to Contribute

### How to install

- Step 1: `pip install`
- Step 2: `alt-f4`



### How to build

`python --build --all .`

### How to test

Run the command
`pytest --megahardcore`

<img align="left" width="50" height="50" src="./docs/icons/traffic-light.svg">

## Known Issues

Awaiting on Powercor to release their sub transmission lines via Rosetta/other GIS system. Expected release date late MAR early APR

<img align="left" width="50" height="50" src="./docs/icons/notes.svg">

## Data Sources

ALL data is from Data.gov.au, or scraped from the respective [TNSP](<url goes here>)/[DNSP](<url goes here>) [TAPR/DAPR](<url goes here>) website/pdf.

## SOURCES ##
#############

ALL data is from Data.gov.au, or scraped from the respective TNSP/DNSP TAPR/DAPR website/pdf. 
QLD forecast data is supplied by ERGON 

https://ausgrid.rosettaportal.com.au/ # requires login, unable to source as of 280220
https://tapr.transgrid.com.au/
https://dapr.essentialenergy.com.au/
https://dapr.endeavourenergy.com.au/
https://dapr.ausnetservices.com.au/
https://www.ergon.com.au/network/network-management/future-investment/distribution-annual-planning-report/dapr-map-2018
https://www.energex.com.au/about-us/company-information/company-policies-And-reports/distribution-annual-planning-report/dapr-map-2018
https://www.powercor.com.au/customers/electricity-connections/solar-and-other-generation/connecting-larger-embedded-generation-systems/ #POWERCOR are working on an offline version, to be released late MAR early APR


https://data.gov.au/dataset/ds-ga-1185c97c-c042-be90-e053-12a3070a969b/details?q=transmission
https://data.gov.au/dataset/ds-ga-13be62a4-4fe3-f812-e053-12a3070a22be/details?q=transmission
https://data.gov.au/dataset/ds-ga-04661f51-82ee-144e-e054-00144fdd4fa6/details?q=power%20stations

## MISSING DATA ##
##################
Jemena
United Energy
AUSGRID

## INFERRED DATA ##
###################
PowerLink
Electranet
SAPowerNetworks 
TasNetworks (Distribution)


<img align="left" width="50" height="50" src="./docs/icons/file.svg">

## License

Full public any one can use it.


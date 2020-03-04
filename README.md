
# Mapping the National Electricity Market (NEM) infrastructure
=======


<img align="left" width="50" height="50" src="./docs/icons/open-book.svg">

## Context
A visual map to assist with interpreting the NEM, SWIS and NT grids. 
=======

<img align="left" width="50" height="50" src="./docs/icons/flag.svg">

## Scope

Contains:

- Transmission and sub transmission lines (ie, 66kV and above)
- Zone Substations 
- Terminal Substations
- Generators

for the NEM (ie, QLD, NSW, VIC, TAS, SA), SWIS (WA) and NT grids. 
=======


<img align="left" width="50" height="50" src="./docs/icons/tools.svg">

## How to use

1. Install Google Earth Pro 
1. Open `AU Network Map.kmz`
1. State level `KMZ` are embedded with `AU Network Mark.kmz`
=======


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


Some overlap of data exists
Energex data is a single map of data


=======
<img align="left" width="50" height="50" src="./docs/icons/notes.svg">

## Data Sources


ALL data is from Data.gov.au, or scraped from the respective TNSP/DNSP TAPR/DAPR website/pdf. 


- [AusGrid - NSW Distributor](https://ausgrid.rosettaportal.com.au/) # requires login, unable to source as of 280220
- [TransGrid - NSW TNSP](https://tapr.transgrid.com.au/)
- [Essential Energy - NSW Distributor](https://dapr.essentialenergy.com.au/)
- [Endeavour Energy - NSW Distributor](https://dapr.endeavourenergy.com.au/)- [AusNet Services - VIC TSNP and Distributor](https://dapr.ausnetservices.com.au/)
- [Ergon Energy - QLD Distributor](https://www.ergon.com.au/network/network-management/future-investment/distribution-annual-planning-report/dapr-map-2018)
- [Energex - SEQ Distributor](https://www.energex.com.au/about-us/company-information/company-policies-And-reports/distribution-annual-planning-report/dapr-map-2018)
- [Powercor - VIC Distributor](https://www.powercor.com.au/customers/electricity-connections/solar-and-other-generation/connecting-larger-embedded-generation-systems/) #POWERCOR are working on an offline version, to be released late MAR early APR


- https://data.gov.au/dataset/ds-ga-1185c97c-c042-be90-e053-12a3070a969b/details?q=transmission
- https://data.gov.au/dataset/ds-ga-13be62a4-4fe3-f812-e053-12a3070a22be/details?q=transmission
- https://data.gov.au/dataset/ds-ga-04661f51-82ee-144e-e054-00144fdd4fa6/details?q=power%20stations

## MISSING DATA ##

- Jemena
- United Energy
- AUSGRID
- Others

## INFERRED DATA ##

- PowerLink
- Electranet
- SAPowerNetworks 
- TasNetworks (Distribution)
- EvoEnergy (ACT TSNP)

=======



<img align="left" width="50" height="50" src="./docs/icons/file.svg">

## License

Full public any one can use it.


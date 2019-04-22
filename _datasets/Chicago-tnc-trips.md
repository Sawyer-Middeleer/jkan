---
schema: default
title: Chicago Transportation Network Providers - Trips
organization: CDOT
notes: All trips, starting November 2018, reported by Transportation Network Providers (sometimes called rideshare companies) to the City of Chicago as part of routine reporting required by ordinance.
Census Tracts are suppressed in some cases, and times are rounded to the nearest 15 minutes. Fares are rounded to the nearest $2.50 and tips are rounded to the nearest $1.00.
For a discussion of the approach to privacy in this dataset, please see http://dev.cityofchicago.org/open%20data/data%20portal/2019/04/12/tnp-taxi-privacy.html.

resources:
  - name: TNC Trips CSV
    url: "https://data.cityofchicago.org/api/views/m6dm-c72p/rows.csv?accessType=DOWNLOAD&bom=true&format=true"
    format: csv
  - name: TNC Trips API
    url: 'https://data.cityofchicago.org/resource/m6dm-c72p.json'
    format: api
license: 'http://www.cityofchicago.org/'
category:
  - Transportation
---

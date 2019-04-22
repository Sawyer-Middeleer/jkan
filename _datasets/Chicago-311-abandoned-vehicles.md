---
schema: default
title: 311 Service Requests - Abandoned Vehicles - No Duplicates
organization: City of Chicago 311
notes: This filtered view shows only those service requests from the underlying dataset that are not marked as duplicates. -- All open abandoned vehicle complaints made to 311 and all requests completed since January 1, 2011. A vehicle can be classified as abandoned if it meets one or more of the following criteria: 1) On a public way in a state of disrepair as to be incapable of being driven in its present condition. 2) Has not been moved or used for more than seven consecutive days and is apparently deserted. 3) Has been left on the public way without state registration or a temporary state registration placard for two or more days. 4) Is a hazardous dilapidated vehicle left in full view of the general public, whether on public or private property.
For some Open service requests, the vehicle has been towed but further action is required before the request may be closed. 311 sometimes receives duplicate abandoned vehicle complaints.
If a vehicle is towed it remains as open, work in progress until it is redeemed, transferred or disposed of. The service request is not closed until there is a final disposition for the vehicle.
Requests that have been labeled as Duplicates are in the same geographic area and have been entered into 311 Customer Service Requests (CSR) system at around the same time as a previous request. Duplicate reports/requests are labeled as such in the Status field, as either "Open - Dup" or "Completed - Dup." Data is updated daily.
resources:
  - name: 311 Service Requests - Abandoned Vehicles - No Duplicates CSV
    url: 'https://data.cityofchicago.org/api/views/atid-bgws/rows.csv?accessType=DOWNLOAD&bom=true&format=true'
    format: csv
  - name: 311 Service Requests - Abandoned Vehicles - No Duplicates JSON
    url: 'https://data.cityofchicago.org/api/views/atid-bgws/rows.json?accessType=DOWNLOAD'
    format: json
  - name: 311 Service Requests - Abandoned Vehicles - No Duplicates API
    url: 'https://data.cityofchicago.org/resource/atid-bgws.json'
    format: api
license: 'http://www.cityofchicago.org/'
category:
  - Chicago 311
maintainer: Jonathan Levy
maintainer_email: .
---

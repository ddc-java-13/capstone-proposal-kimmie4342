## Summary

Critical Support is a software program that uses the GPS services that are already on most cars
today to identify where there is a great need for road infrastructure repairs. With the advancement
of internet of things, Critical Support monitors and measures how balanced the vehicles axles are as
they travel over our roads using a mounted cell phone inside the vehicle. Identifying extreme areas of the
roads that need repair or improvements.

The information will be identified and tracked using Heat Mapping to highlight infrastructure
improvement needs. This information will be available to Federal, State and City Governments as well
as contractors, so they have a quick reference of the extent of damaged road in need of repair.

## Intended users

* Contractors that bid for road repair jobs.

  > As a contractor that places bids for jobs, I want to be able to quickly visualize the area of need, so I can bid appropriately.

* Representatives of government agencies specialize in infrastructure.

  > As a representative of a government agency specializing in road infrastructure, I want to be able to keep track of repair needs, completed jobs and identify problem areas before they become critical, so that our roads are safe for travel.

## Client component

### Functionality

Using a search bar, the user will be able to directly input any specific road they are inquiring
about.

Otherwise, the user will have a drop down option to choose a state. The user will also have the
ability to save the preferred state within the device. A map of the selected stated will appear with
all roads and Heat mapping. The mapping will identify the roads and base the need for repair using
green, yellow and red areas of the road. The user will then have a drop down option to choose from
Interstate, State, County and City roads to choose from. The map will appear with the road option
chosen with the same identification of roads as previously.

### Persistent data

* State and county preferences.

### Device/external services

* GPS mapping and locations.
* Heat mapping
* Updated data from Department of Transportation for selected state.

## Server component

### Functionality

Bringing up maps of roads by user requests. Calculating the variations in the axle balance based on
how much the mounted cell phone vibrates to identify extreme areas in any given road that will need
attention and repairs. Calculating the data received and reporting it back in a Heat map for quick reference.

### Persistent data

* State and county roads via mapping services

### External services

* Data from sensor on mounted cell phone.
* Mapping and GPS services.
*

## Stretch goals/possible enhancements

TBD

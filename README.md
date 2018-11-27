# Boeing Hackathon - Brisbane 2018
## A data pipeline for an autonomous UAV navigation system

This is the repo for team Collision Division's project on autonomous unmanned aerial vehicle (UAV) navigation, which was done as part of the Brisbane 2018 Boeing Hackathon. The challenge was to take actual ADS-B flight data from a busy commercial route for over 200 aircraft and autonomously navigate an unmanned aerial navigation system safely through the airspace.

There were four steps involved in the process.
- Inspect and clean the ADS-B data and export it to an external database
- Plot the aircraft routes in 3D space using CesiumJS
- Create an autonomous UAV navigation to plot a route through the airspace with any given start location and time
- Create and export the route data for the UAV

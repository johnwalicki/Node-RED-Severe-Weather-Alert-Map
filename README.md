# Node-RED Severe Weather Alert Map
Build a Severe Weather Alert Map Node-RED Dashboard using The Weather Company APIs

Use [The Weather Company APIs](https://business.weather.com/products/weather-data-packages) to plot all of the current [Severe Weather Alerts](https://business.weather.com/resource/brochure-the-weather-company-data-package-severe-weather) issued by the [National Weather Service](https://www.weather.gov/alerts) on a [Node-RED](https://nodered.org) Dashboard

This example flow and Node-RED Dashboard might be useful as part of a [Call for Code](https://developer.ibm.com/callforcode/) solution. The Call for Code 2020 theme is to help reverse the impact of Climate Change.

Create additional Node-RED flows using the [node-red-contrib-twc-weather](https://flows.nodered.org/node/node-red-contrib-twc-weather) package.

### Prerequistes

- [Install Node-RED](https://nodered.org/docs/getting-started/) on your system or in the cloud
- This flow requires Node-RED v1.1 or higher
- [Add the following nodes](https://nodered.org/docs/user-guide/runtime/adding-nodes) to your Node-RED palette
  - [node-red-dashboard](https://flows.nodered.org/node/node-red-dashboard)
  - [node-red-node-ui-table](https://flows.nodered.org/node/node-red-node-ui-table)
  - [node-red-contrib-web-worldmap](https://flows.nodered.org/node/node-red-contrib-web-worldmap)
- If you are participating in the [2020 Call for Code](https://developer.ibm.com/callforcode/) you can [register](https://callforcode.weather.com/) for a time limited TWC API key.

## Node-RED flow in this repository:
---
### A flow that displays Severe Weather Alerts on a map

![Severe Weather Alert Dashboard](screenshots/TWC-SevereWeatherAlerts-dashboard.png?raw=true "Severe Weather Dashboard")
<p align="center">
  <strong>Get the Code: <a href="flows/SevereWeatherAlertMap.flow">Node-RED flow for Severe Weather Alerts</strong></a>
</p>

![Severe Weather Alert flow](screenshots/TWC-SevereWeatherAlerts-flow.png?raw=true "Severe Weather flow")
---

### Authors

- [John Walicki](https://github.com/johnwalicki)

___

Enjoy!  Give us [feedback](https://github.com/johnwalicki/Node-RED-Severe-Weather-Alert-Map/issues) if you have suggestions on how to improve this tutorial.

## License

This tutorial is licensed under the Apache Software License, Version 2.  Separate third party code objects invoked within this code pattern are licensed by their respective providers pursuant to their own separate licenses. Contributions are subject to the [Developer Certificate of Origin, Version 1.1 (DCO)](https://developercertificate.org/) and the [Apache Software License, Version 2](http://www.apache.org/licenses/LICENSE-2.0.txt).

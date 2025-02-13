# Introduction

This is an updated version of the great work done by Andrewcowley!

I have used Postman to do all the hard work, i will list below to steps i did to make this work. This is a quick guide for Dummies like myself!!


One of the services [WaterNSW](https://www.waternsw.com.au/) provides is the monitoring of rivers, dams and groundwater across the state of New South Wales, Australia. This data is made available [via their website](https://realtimedata.waternsw.com.au/), [mobile apps](https://www.waternsw.com.au/supply/regional-nsw/real-time-data#footer) as well as a web service.

The web service allows a user to request realtime and historical timeseries data for monitoring site via HTTP and have the data returned in JSON or CSV format.

This documetation aims to provide someone with some knowledge of requesting data via an HTTP API enough information to access the water monitoring data. 

## Dive in

The two main parts of the documentation are:

  - [Getting started](/getting-started.md):  make requests to the API and what can be expected in response.
  - [API reference](/api-reference.md): information on the possible API calls and examples of their use.

**Both sections are works in progress.**

## Credits

All data sourced from the NSW Water web service is subject to the [WaterNSW copyright notice](https://www.waternsw.com.au/copyright).

Most of the information for this document comes from the following sources:

  - Kisters [web service documentation](http://kisters.com.au/doco/hydllp.htm)
  - [This github repository](https://github.com/tonycaine/pages-for-appchallenge)
  
Thank you to:
  - [Kisters](http://kisters.com.au/) support for answering my questions around the Hydstra system.
  
## Contributing

If you wish to contribute, thank you! Please read [CONTRIBUTING.md](/CONTRIBUTING.md) making special note of the [Code of Conduct](/CONTRIBUTING.md#code-of-conduct).

## License

[MIT](/LICENSE)

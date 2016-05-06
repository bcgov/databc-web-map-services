# DataBC Web Map Services

DataBC offers data connection services that allow users to view thousands of data layers from the BC Geographic Warehouse (BCGW) in geospatial software or custom web-based applications. They are all available in the industry standard Web Map Service (WMS), and some also in Google Earth’s popular Keyhole Markup Language (KML), and ArcGIS Server REST services.

You can learn more about DataBC's WMS services [here](http://www.data.gov.bc.ca/dbc/geographic/connect/index.page?).

In this repository you will find opportunities to contribute to the improvement of our WMS.


## Usage and Requirements

The core requirements for contributing at this time revolves entirely around the GeoServer, an open source software server written in Java that allows users to share and edit geospatial data. Designed for interoperability, it publishes data from any major spatial data source using open standards.

DataBC uses GeoServer to provide map views of geographic data layers embedded in the metadata records in our [BC Data Catalogue](https://github.com/bcgov/ckanext-bcgov), which provides metadata and access to more than 3500 government datasets, web services (APIs) and online applications, including more than 1500 datasets licensed for commercial use under the Open Government License – British Columbia.  

To contribute to this project, you will need to fork the [GeoServer git repository](https://github.com/geoserver/geoserver/tree/2.8.2), which is licensed under the GPL 2.0.

## Why are we not posting this issue in the GeoServer Community?

The quick answer is we are. We posted an [issue](https://osgeo-org.atlassian.net/browse/GEOS-7369) in the GeoServer community.

But we really want to get this work done, so we are trying this new pay for pull experiment as a way to sponsor a developer to do the work. 

For a Pay for Pull we offer a thousand dollars as an incentive. In the GeoServer project, community members are responsible for reviewing the code submissions. But as government, we must do the code review as we are responsible to ensure the goods, in this case, the code is received and meets our acceptance criteria before we can make a payment. For that reason alone, we need to post the issue here in a repo where we have the power as admins to open and close issues, merge code contributions, etc.

Please see the [Wiki](https://github.com/BCDevExchange/rapid-adoption/wiki) for more information on how Pay for Pull works.

All that being said, we would like the code to go back to the GeoServer community. The intention is that the developer who sends us code to complete this issue also contributes their work back to the GeoServer code base. For more information, on how that can be done, please see GeoServer's [contributing guidelines](https://github.com/geoserver/geoserver/blob/master/CONTRIBUTING.md) 

## Project Status
Under active development.

## Goals/Roadmap
TBD

## Getting Help or Reporting an Issue
To report bugs/issues/feature requests, please file an [issue](https://github.com/bcgov/databc-web-map-services/issues).

## How to Contribute
Pull requests are welcome. If you would like to contribute a package, please see our [CONTRIBUTING guidelines](https://github.com/bcgov/databc-web-map-services/blob/master/CONTRIBUTING.md).

## License
The code in this repository may be licensed under different licenses.

- All new code in the /GeoServer code directory is licensed under the GNU General Public License (GPL), version 2. See [LICENSE.GPL.2.0](https://github.com/bcgov/databc-web-map-services/blob/master/geoserver-code/LICENSE.GPL.2.0) in the appropriate directories.




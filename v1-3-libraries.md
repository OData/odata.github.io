---
layout: default
title: "V1-3 Libraries"
---
The .NET libraries for OData V1-3 are the core libraries and the WCF Data Services series. They are:

**Libraries**

- Core libraries
	- **ODataLib for OData v1-3**, namespace `Microsoft.Data.OData`. It contains classes to serialize, deserialize and validate OData payloads. Enables construction of OData producers and consumers ([source code](https://github.com/OData/odata.net/tree/ODATAV3/ODataLib/OData) \| [binary](http://www.nuget.org/packages/Microsoft.Data.OData/)).
	- **EdmLib for OData v1-3**, namespace `Microsoft.Data.Edm`. It contains classes to represent, construct, parse, serialize and validate entity data models ([source code](https://github.com/OData/odata.net/tree/ODATAV3/ODataLib/EdmLib) \| [binary](http://www.nuget.org/packages/Microsoft.Data.Edm/)).
	- **System.Spatial for OData v1-3**, namespace `System.Spatial`. It contains classes and methods that facilitate geography and geometry spatial operations ([source code](https://github.com/OData/odata.net/tree/ODATAV3/ODataLib/Spatial) \| [binary](http://www.nuget.org/packages/System.Spatial/)).
    - **WCF Data Services Client for OData v1-3**, namespace `Microsoft.Data.Services.Client`. It contains LINQ-enabled client API for issuing OData queries and consuming OData payloads ([source code](https://github.com/OData/odata.net/tree/ODATAV3/WCFDataService/Client) \| [binary](http://www.nuget.org/packages/Microsoft.Data.Services.Client/)).
    - **WCF Data Services Server for OData v1-3**, namespace `Microsoft.Data.Services`. It contains fully-featured server API for responding to OData queries and consuming/producing OData payloads ([source code](https://github.com/OData/WebApi) \| [binary](http://www.nuget.org/packages/Microsoft.Data.Services/)).
- **ASP.NET Web API for OData v1-3**, namespace `System.Web.Http.OData`. It contains everything you need to create OData endpoints using ASP.NET Web API and to support OData query syntax for your web APIs ([source code](https://github.com/OData/WebApi) \| [binary](http://www.nuget.org/packages/Microsoft.AspNet.WebApi.OData/)).
- **WCF Data Services EntityFramework Provider**, namespace `Microsoft.OData.EntityFrameworkProvider`. It contains server API for responding to OData queries and consuming/producing OData payloads based on entity framework version 6.0 or higher ([source](https://github.com/OData/odata.net/tree/ODATAV3/WCFDataService/EntityFrameworkProvider) \| [binary](http://www.nuget.org/packages/Microsoft.OData.EntityFrameworkProvider/))

**Tooling**

- **Add Service Reference**. It enables the creation of client-side proxies in projects to access one or more OData v1-3 services. ([tutorial](http://www.asp.net/web-api/overview/odata-support-in-aspnet-web-api/odata-v3/calling-an-odata-service-from-a-net-client)).
---
layout: default
---

# Getting started

OData is an [OASIS standard](https://www.oasis-open.org/committees/tc_home.php?wg_abbrev=odata) for creating and consuming RESTful APIs. The OData .NET libraries implement the OData version 4.0.

To build an OData V4 **client application**, start by following:

- ["How to use OData Client Code Generator to generate client-side proxy class"](http://blogs.msdn.com/b/odatateam/archive/2014/03/12/how-to-use-odata-client-code-generator-to-generate-client-side-proxy-class.aspx)

To build an OData V4 **service**, start by following:

- ["Building an OData v4 Service within minutes using RESTier"](https://github.com/OData/RESTier/wiki/%5BSamples-1%5D-Getting-started---basic) for a turn-key experience.

- ["Create an OData v4 Endpoint Using ASP.NET Web API 2.2"](http://www.asp.net/web-api/overview/odata-support-in-aspnet-web-api/odata-v4/create-an-odata-v4-endpoint) for more advanced scenarios.

# Introduction

**Libraries**

- Core libraries
	- **ODataLib**, namespace `Microsoft.OData.Core`. It contains classes to serialize, deserialize and validate OData JSON payloads ([source code](https://github.com/OData/odata.net/tree/master/src/OData) \| [binary](http://www.nuget.org/packages/Microsoft.OData.Core/) \| [samples](http://odata.github.io/odata.net/)).
	- **EdmLib**, namespace `Microsoft.OData.Edm`. It contains classes to represent, construct, parse, serialize and validate entity data models ([source code](https://github.com/OData/odata.net/tree/master/src/Edm) \| [binary](http://www.nuget.org/packages/Microsoft.OData.Edm/) \| [samples](http://odata.github.io/odata.net/)).
	- **Microsoft.Spatial**, namespace `Microsoft.Spatial`. It contains classes and methods that facilitate geography and geometry spatial operations ([source code](https://github.com/OData/odata.net/tree/master/src/Spatial) \| [binary](http://www.nuget.org/packages/Microsoft.Spatial/) \| [samples](http://odata.github.io/odata.net/)).
    - **OData Client for .NET**, namespace `Microsoft.OData.Client`. It contains LINQ-enabled client APIs for issuing OData queries and consuming OData JSON payloads ([source code](https://github.com/OData/odata.net/tree/master/src/Client) \| [binary](http://www.nuget.org/packages/Microsoft.OData.Client/) \| [samples](http://odata.github.io/odata.net/)).
- **ASP.NET Web API OData**, namespace `System.Web.OData`. It contains everything you need to create OData v4.0 endpoints using ASP.NET Web API and to support OData query syntax for your web APIs ([source code](https://github.com/OData/WebApi) \| [binary](http://www.nuget.org/packages/Microsoft.AspNet.OData/) \| [samples](http://odata.github.io/WebApi/)).
- **RESTier**, namespace `Microsoft.Restier`. It's built upon ASP.NET Web API OData.  RESTier can help developers bootstrap an OData service quickly , add business logic conveniently and customize easily. It is currently a preview version ([source code](https://github.com/OData/RESTier) \| [binary](http://www.nuget.org/packages/Microsoft.Restier/) \| [samples](http://odata.github.io/RESTier/)).

**Tooling**

- **OData v4 Client Code Generator**. An item template that simplifies the process of accessing OData v4 services by generating C# and VB.Net client-side proxy classes ([download](https://visualstudiogallery.msdn.microsoft.com/9b786c0e-79d1-4a50-89a5-125e57475937) \| [tutorial](http://blogs.msdn.com/b/odatateam/archive/2014/03/11/how-to-use-odata-client-code-generator-to-generate-client-side-proxy-class.aspx)).

**Relationship**

![Client side]({{site.baseurl}}/assets/library-relationship.png)

# Support

- [OData Team's MSDN blog](http://blogs.msdn.com/b/odatateam/)
- [StackOverflow](http://stackoverflow.com/questions/tagged/odata)
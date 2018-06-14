---
layout: default
---

# Getting started

OData is an [OASIS standard](https://www.oasis-open.org/committees/tc_home.php?wg_abbrev=odata) for creating and consuming RESTful APIs. 
The OData .NET libraries help users to build and consume OData v4 services.

To build an OData V4 **service**, start by following:

- ["Build an OData v4 Service with RESTier Library"](http://odata.github.io/RESTier/#01-01-Introduction) for a turn-key experience, or if you are a data developer.

- ["Build an OData v4 Service with OData WebApi Library"](http://odata.github.io/WebApi/#01-02-getting-started) if you get used to MVC pattern, or you are a web developer.

To build an OData V4 **client application** to consume OData v4 Service, start by following:

- ["Using OData Client Code Generator to generate client-side proxy class"](http://blogs.msdn.com/b/odatateam/archive/2014/03/12/how-to-use-odata-client-code-generator-to-generate-client-side-proxy-class.aspx)

- ["Using OData Connected Service to generate client-side proxy class"](http://odata.github.io/odata.net/#OData-Client-Code-Generation-Tool)

- ["Basic CRUD Operations with OData .Net Client"](http://odata.github.io/odata.net/#04-01-basic-crud-operations)


# Introduction

**Libraries**

- **Core libraries**
	- **ODataLib**, namespace `Microsoft.OData.Core`. It contains classes to serialize, deserialize and validate OData JSON payloads ([source code](https://github.com/OData/odata.net/) \| [binary](http://www.nuget.org/packages/Microsoft.OData.Core/) \| [tutorial](http://odata.github.io/odata.net/)).
	- **EdmLib**, namespace `Microsoft.OData.Edm`. It contains classes to represent, construct, parse, serialize and validate entity data models ([source code](https://github.com/OData/odata.net/) \| [binary](http://www.nuget.org/packages/Microsoft.OData.Edm/) \| [tutorial](http://odata.github.io/odata.net/)).
	- **Microsoft.Spatial**, namespace `Microsoft.Spatial`. It contains classes and methods that facilitate geography and geometry spatial operations ([source code](https://github.com/OData/odata.net/) \| [binary](http://www.nuget.org/packages/Microsoft.Spatial/) \| [tutorial](http://odata.github.io/odata.net/)).

    
- **Web API OData**, namespace for <= 6.x `System.Web.OData`. Starting with 7.0, the library ships as two binaries, one for .NET Framework (namespace `Microsoft.AspNet.OData`) and one for .NET Core (namespace `Microsoft.AspNetCore.OData`). It contains everything you need to create OData v4.0 endpoints using ASP.NET Web API and to support OData query syntax for your web APIs ([source code](https://github.com/OData/WebApi) \| [.NET Framework binary](http://www.nuget.org/packages/Microsoft.AspNet.OData/) \| [.NET Core binary](http://www.nuget.org/packages/Microsoft.AspNetCore.OData/) \| [tutorial](http://odata.github.io/WebApi/)).

- **RESTier**, namespace `Microsoft.Restier`. RESTier is a RESTful API development framework for building standardized, OData V4 based RESTful services on .NET platform. It can be seen as a middle-ware on top of Web API OData. RESTier provides facilities to bootstrap an OData service like what WCF Data Services (which is sunset) does, beside this, it supports to add business logic in several simple steps, has flexibily and easy customization like what Web API OData do. It also supports to add additional publishers to support other protocols and additional providers to support other data sources. It is currently a preview version ([source code](https://github.com/OData/RESTier) \| [binary](http://www.nuget.org/packages/Microsoft.Restier/) \| [tutorial](http://odata.github.io/RESTier/)).

- **OData Client for .NET**, namespace `Microsoft.OData.Client`. It contains LINQ-enabled client APIs for issuing OData queries and consuming OData JSON payloads ([source code](https://github.com/OData/odata.net/) \| [binary](http://www.nuget.org/packages/Microsoft.OData.Client/) \| [tutorial](http://odata.github.io/odata.net/)).

**Tooling**

- **OData Client Code Generator**. An item template that simplifies the process of accessing OData v4 services by generating C# and VB.Net client-side proxy classes. It works with Visual Studio 2010, 2012, 2013 and 2015. ([download](https://visualstudiogallery.msdn.microsoft.com/9b786c0e-79d1-4a50-89a5-125e57475937) \| [tutorial](http://blogs.msdn.com/b/odatateam/archive/2014/03/11/how-to-use-odata-client-code-generator-to-generate-client-side-proxy-class.aspx)).

- **OData Connected Service**. An item template that simplifies the process of accessing OData v3 and v4 services by generating C# client-side proxy classes. It works with Visual Studio 2015 only. ([download](https://visualstudiogallery.msdn.microsoft.com/b343d0eb-6493-44c2-b558-13a0408d013f/file/163980/4/Microsoft.OData.ConnectedService.vsix) \| [tutorial](http://odata.github.io/odata.net/#OData-Client-Code-Generation-Tool)).

**Relationship**

![Client side](/assets/library-relationship.png)

# Support

- [StackOverflow](http://stackoverflow.com/questions/tagged/odata)
- [OData .Net Lib Issue Tracker](https://github.com/OData/odata.net/issues)
- [WebApi OData Issue Tracker](https://github.com/OData/WebApi/issues)
- [RESTier Issue Tracker](https://github.com/OData/RESTier/issues)

# Thank You!

We’re using NDepend to analyze and increase code quality.

[![NDepend](assets/ndependlogo.png)](http://www.ndepend.com)

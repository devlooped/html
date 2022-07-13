![Icon](https://raw.githubusercontent.com/devlooped/html/main/assets/icon-32.png) XLinq to Html
============

[![Version](https://img.shields.io/nuget/vpre/Devlooped.Html.svg?color=royalblue)](https://www.nuget.org/packages/Devlooped.Html)
[![Downloads](https://img.shields.io/nuget/dt/Devlooped.Html.svg?color=green)](https://www.nuget.org/packages/Devlooped.Html)
[![License](https://img.shields.io/github/license/devlooped/css.svg?color=blue)](https://github.com/devlooped/html/blob/main/license.txt)

Read HTML as XML using XLinq.

# Usage

```csharp
using System.Xml.Linq;
using Devlooped.Html;

XDocument page = HtmlDocument.Load("page.html")
```

Works great when combined with [CSS selectors](https://www.nuget.org/packages/Devlooped.Xml.Css) 
for XLinq.

Leverages [Microsoft SgmlReader](https://www.nuget.org/packages/Microsoft.Xml.SgmlReader) which 
converts (almost) all HTML to valid XML.


# Dogfooding

[![CI Version](https://img.shields.io/endpoint?url=https://shields.kzu.io/vpre/Devlooped.Html/main&label=nuget.ci&color=brightgreen)](https://pkg.kzu.io/index.json)
[![Build](https://github.com/devlooped/html/workflows/build/badge.svg?branch=main)](https://github.com/devlooped/html/actions)

We also produce CI packages from branches and pull requests so you can dogfood builds as quickly as they are produced. 

The CI feed is `https://pkg.kzu.io/index.json`. 

The versioning scheme for packages is:

- PR builds: *42.42.42-pr*`[NUMBER]`
- Branch builds: *42.42.42-*`[BRANCH]`.`[COMMITS]`



## Sponsors

[![sponsored](https://raw.githubusercontent.com/devlooped/oss/main/assets/images/sponsors.svg)](https://github.com/sponsors/devlooped) [![clarius](https://raw.githubusercontent.com/clarius/branding/main/logo/byclarius.svg)](https://github.com/clarius)[![clarius](https://raw.githubusercontent.com/clarius/branding/main/logo/logo.svg)](https://github.com/clarius)

*[get mentioned here too](https://github.com/sponsors/devlooped)!*

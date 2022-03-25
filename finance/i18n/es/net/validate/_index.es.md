---
title: Validar informes financieros a través de .NET
url: /es/net/validate/
description:  C# código para validar los informes financieros en XBRL y iXBRL archivos a través de .NET biblioteca.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Validar archivos de Financial Reporting a través de C#" h2="Validar formatos de informes financieros, incluidos XBRL y iXBRL dentro de .NET aplicaciones basadas." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) Es una característica rica, extensible y fácil de usar de procesamiento de informes financieros API. Los desarrolladores pueden cargar, validar, ver o crear fácilmente formatos XBRL y iXBRL para soluciones financieras y empresariales. API proporciona [XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Clase y  [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) Clase para cargar archivos XBRL y iXBRL.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Validar XBRL documento" %}}

Se necesita la validación de XBRL archivo para varios casos, como para comprobar que los datos están en la estructura y el formato adecuados. Para validar documentos XBLR, use en primer lugar la clase XbrlDocument para cargar el archivo XBRL. Para usar el [Validar ()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) Método de [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) Clase, en primer lugar, intializar el [Colección XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) Con XbrlDocument objeto XbrlInstances. Iterar a través de cada uno [XbrlInstance. ValidationErrores](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/properties/validationerrors) Para obtener el código de error correcto y actuar en consecuencia imprimiendo los mensajes de error personalizados en la consola o escribiendo dentro de un archivo.

{{% blocks/products/pf/feature-page-code h3="C# código para validar XBRL archivo" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-xbrl-file.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Validar iXBRL documento" %}}

Para la validación iXLRB, cargarlo mediante [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) Y use su método Validate(). En [ValidaciónErrorCode](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.validator/validationerrorcode) Enumeración, los códigos de error de validación se definen para cada regla de validación. Pocos de los códigos son ContextPeriodNoStartTime, ContextPeriodNoEndTime, ContextPeriodStartAfterEnd, ContextInstantNoTime, ContextScenarioXbrlNamespace, ContextarioXbrlSubstitutionGroup, etc. Los desarrolladores pueden depurar y mostrar códigos como usuarios finales o pueden mostrar la dirección para resolver el problema.

{{% blocks/products/pf/feature-page-code h3="C# código para validar iXBRL documento" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}
---
title: Validar informes financieros a través de .NET
url: /es/net/validate/
description:  Código C# para validar informes financieros en archivos XBRL y iXBRL a través de la biblioteca .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Validar archivos de informes financieros a través de C#" h2="Validación de formatos de informes financieros, incluidos XBRL y iXBRL dentro de aplicaciones basadas en .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) es un procesamiento de informes financieros rico en funciones, extensible y fácil de usar API. Los desarrolladores pueden cargar, validar, ver o crear fácilmente formatos XBRL y iXBRL para soluciones financieras y comerciales. API proporciona [XbrlDocumento](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) clase y  [InlineXbrlDocumentInlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) clase para cargar archivos XBRL y iXBRL.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Validar XBRL documento" %}}

La validación del archivo XBRL es necesaria para una serie de casos, como para verificar que los datos tengan la estructura y el formato correctos. Para validar documentos XBLR, primero use la clase XbrlDocument para cargar el archivo XBRL. Usar el [validar()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) método de [XbrlInstancia](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) clase, primero inicialice el [XbrlInstanceCollectionXbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) con el objeto XbrlDocument XbrlInstances. Iterar a través de cada [XbrlInstance.ValidationErrors](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/properties/validationerrors) para obtener el código de error correcto y actuar en consecuencia imprimiendo los mensajes de error personalizados en la consola o escribiendo dentro de un archivo.

{{% blocks/products/pf/feature-page-code h3="Código C# para validar el archivo XBRL" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-xbrl-file.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Validar iXBRL documento" %}}

Para la validación de iXLRB, cárguelo a través de [InlineXbrlDocumentInlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) class y use su método Validate(). En [Código de error de validación](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.validator/validationerrorcode) enumeración, se definen códigos de error de validación para cada regla de validación. Algunos de los códigos son ContextPeriodNoStartTime, ContextPeriodNoEndTime, ContextPeriodStartAfterEnd, ContextInstantNoTime, ContextScenarioXbrlNamespace, ContextScenarioXbrlSubstitutionGroup, etc. Los desarrolladores pueden depurar y mostrar códigos a partir de los usuarios finales o pueden mostrar la dirección para resolver el problema.

{{% blocks/products/pf/feature-page-code h3="C# Código para Validar iXBRL Documento" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}
{{< /blocks/products/pf/feature-page-wrap >}}
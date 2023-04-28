---
title: Validar informes financieros a través de Python
url: /es/python-net/validate/
description:  Código Python para validar informes financieros en archivos XBRL y iXBRL a través de la biblioteca Python.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Validar archivos de informes financieros a través de Python" h2="Validación de formatos de informes financieros, incluidos XBRL y iXBRL dentro de aplicaciones basadas en Python." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance para Python a través de .NET](https://products.aspose.com/finance/python-net/) es un procesamiento de informes financieros rico en funciones, extensible y fácil de usar API. Los desarrolladores pueden cargar, validar, ver o crear fácilmente formatos XBRL y iXBRL para soluciones financieras y empresariales. API proporciona la clase XbrlDocument y la clase InlineXbrlDocument para cargar archivos XBRL y iXBRL.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Validar XBRL documento" %}}

La validación del archivo XBRL es necesaria para una serie de casos, como para verificar que los datos tengan la estructura y el formato correctos. Para validar documentos XBLR, primero use la clase XbrlDocument para cargar el archivo XBRL. Para usar el método de validación de la clase XbrlInstance, primero inicialice XbrlInstanceCollection con el objeto XbrlDocument XbrlInstances. Repita cada XbrlInstance.ValidationErrors para obtener el código de error correcto y actúe en consecuencia imprimiendo los mensajes de error personalizados en la consola o escribiendo dentro de un archivo.

{{% blocks/products/pf/feature-page-code h3="Código Python para validar el archivo XBRL" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-xbrl-instance-file.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Validar iXBRL documento" %}}

Para la validación de iXLRB, cárguelo a través de la clase InlineXbrlDocument y use su método de validación(). En la enumeración ValidationErrorCode, los códigos de error de validación se definen para cada regla de validación. Algunos de los códigos son ContextPeriodNoStartTime, ContextPeriodNoEndTime, ContextPeriodStartAfterEnd, ContextInstantNoTime, ContextScenarioXbrlNamespace, ContextScenarioXbrlSubstitutionGroup, etc. Los desarrolladores pueden depurar y mostrar códigos a partir de los usuarios finales o pueden mostrar la dirección para resolver el problema.

{{% blocks/products/pf/feature-page-code h3="Python Código para Validar iXBRL Documento" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-ixbrl-file.py" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}
{{< /blocks/products/pf/feature-page-wrap >}}
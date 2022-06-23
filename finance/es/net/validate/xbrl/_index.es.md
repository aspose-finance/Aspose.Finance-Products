---
title: Validar XBRL archivo a través de C#
description: Código de muestra para la validación de archivos XBRL. Utilice el código de ejemplo API para validar los archivos por lotes XBRL dentro de las aplicaciones basadas en .NET. 
url: /es/net/validate/xbrl/
family: finance
platformtag: net
feature: validate
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Validar XBRL archivos a través de C#" h2="Validación de informes financieros en formato XBRL sin necesidad de tener instalado Microsoft Office ni ningún otro software." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Cómo validar XBRL archivos" %}}

Siga los pasos del fragmento de código o mejórelo según las necesidades de su aplicación para validar documentos XBRL en lenguaje extensible de informes comerciales. Asegúrese de tener requisitos de validación dentro de su aplicación.

1. Cargue el archivo XBRL usando [Clase XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Instancia.1. Para comprobar la validez del archivo cargado, de modo que debe coincidir con [especificación XBRL](http://www.xbrl.org/specification/inlinexbrl-part1/rec-2013-11-18/inlinexbrl-part1-rec-2013-11-18.html)1. Para comprobar la validez, utilice [Validar()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) método de [XbrlInstancia](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) clase.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisito de validación" %}}
Para proceder a la validación de XBRL documentos, .NET Finance API es el principal requisito que debe incluirse en la solicitud. 
- Instálelo a través de la línea de comandos como ```nuget install Aspose.Finance``` o a través de la consola del administrador de paquetes de Visual Studio con ```Install-Package Aspose.Finance```.
- Alternativamente, obtenga el instalador MSI fuera de línea o las DLL en un archivo ZIP de [descargas](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# código para validar XBRL archivos" offSpacer="" %}}

{{< gist "aspose-com-gists" "1272da1f804f8cef122600269db09fbb" "validate-xbrl-instance-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Otras opciones de validación" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/validate/ixbrl/" name="XBRL" description="Lenguaje de informes comerciales extensible en línea" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
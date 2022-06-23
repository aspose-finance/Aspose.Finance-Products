---
title: Ver XBRL archivo a través de C#
description: Código de ejemplo para la visualización de archivos XBRL. Utilice el código de ejemplo API para ver los archivos por lotes XBRL dentro de las aplicaciones basadas en .NET. 
url: /es/net/view/xbrl/
family: finance
platformtag: net
feature: view
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Ver XBRL archivos a través de C#" h2="Visualización de informes financieros en formato XBRL sin necesidad de tener instalado Microsoft Office ni ningún otro software." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Cómo ver XBRL archivos" %}}

Siga los pasos del fragmento de código o mejórelo según las necesidades de su aplicación para leer archivos extensibles de lenguaje de informes comerciales XBRL. Asegúrese de tener requisitos de lectura dentro de su aplicación.

1. Crear [Clase XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Instancia.2. Pase el nombre de un archivo XBRL válido como parámetro.
3. Para obtener el detalle interno del archivo, use las clases relevantes como [SchemaRefCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection), [Contexto](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context), [Unidad](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/unit) 
4. Mostrar esta información

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisito de lectura" %}}
Para continuar con la visualización de XBRL documentos, .NET Finance API es el requisito principal que debe incluirse en la solicitud. 
- Instálelo a través de la línea de comandos como ```nuget install Aspose.Finance``` o a través de la consola del administrador de paquetes de Visual Studio con ```Install-Package Aspose.Finance```.
- Alternativamente, obtenga el instalador MSI fuera de línea o las DLL en un archivo ZIP de [descargas](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# código para leer XBRL archivos" offSpacer="" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "read-xbrl-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Otras opciones de visualización" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/view/ixbrl/" name="iXBRL" description="Lenguaje de informes comerciales extensible en línea" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
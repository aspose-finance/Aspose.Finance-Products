---
title: Crear XBRL archivo a través de C#
description: Código de ejemplo para la creación de archivos XBRL. Utilice el código de ejemplo API para la generación de archivos por lotes XBRL dentro de las aplicaciones basadas en .NET. 
url: /es/net/create/xbrl/
family: finance
platformtag: net
feature: create
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Crear XBRL archivos a través de C#" h2="Creación de XBRL archivos sin necesidad de tener Microsoft Office instalado ni ningún otro software." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Cómo crear archivos XBRL" %}}

Siga los pasos del fragmento de código o mejórelo según las necesidades de su aplicación para generar archivos extensibles de lenguaje de informes empresariales XBRL. Asegúrese de tener requisitos de creación dentro de su aplicación.

1. Crear [Clase XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Ejemplo.1. Para crear un nuevo documento de instancia XBRL [XbrlInstanceCollectionXbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) y [XbrlInstancia](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance).1. Agregar referencia de esquema usando [SchemaRefCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection)1. Dependiendo de la naturaleza de la aplicación, agregue contexto, unidad, elemento, enlace de nota al pie y más.1. Llama a [Guardar método](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) proporcionando la ruta del archivo de destino.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisito de creación" %}}
Para proceder a la generación de XBRL documentos, .NET Finance API es el requisito principal que debe incluirse en la aplicación. 
- Instálelo a través de la línea de comandos como ```nuget install Aspose.Finance``` o a través de la consola del administrador de paquetes de Visual Studio con ```Install-Package Aspose.Finance```.
- Alternativamente, obtenga el instalador MSI fuera de línea o las DLL en un archivo ZIP de [descargas](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# código para la creación de XBRL archivos" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-schema-reference.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Otras opciones de creación" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX solicitud" description="Formato 1.03 o 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX Respuesta" description="Formato 1.03 o 2.2" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
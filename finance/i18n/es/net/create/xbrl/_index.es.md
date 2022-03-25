---
title: Crear XBRL archivo a través de C#
description: Código de muestra para XBRL creación de archivos. Use API código de ejemplo para la generación de XBRL archivos por lotes dentro de .NET aplicaciones basadas. 
url: /es/net/create/xbrl/
family: finance
platformtag: net
feature: create
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Crear XBRL archivos a través de C#" h2="XBRL creación de archivos sin necesidad de Microsoft Office instalado ni ningún otro software." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Cómo crear XBRL archivos" %}}

Siga los pasos del fragmento de código o mejore las necesidades de su aplicación para generar archivos de lenguaje de informes empresariales extensibles XBRL. Asegúrese de tener requisitos de creación dentro de su aplicación.

1. Crear [Clase XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Instancia.1. Para crear un nuevo documento de instancia de XBRL [Colección XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) Y [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance)...1. Agregar referencia de esquema usando [SchemaRefCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection)1. Dependiendo de la naturaleza de la aplicación agregue contexto, unidad, elemento, enlace de nota al pie y más.1. Llama al [Save (método)](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) Proporcionando la ruta del archivo de destino.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisito de creación" %}}
Para proceder a la generación de XBRL documentos, .NET Finance API es el principal requisito para ser incluido dentro de la solicitud. 
- Instálelo a través de la línea de comandos como ''nuget install Aspose.Finance'' o a través de la consola de Package Manager de Visual Studio con ''Install-Package Aspose.Finance'' '.
- Alternativamente, obtenga el instalador MSI sin conexión o DLL en un archivo ZIP desde [Descargas](https://downloads.aspose.com/finance/net)...{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# código para XBRL creación de archivos" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-schema-reference.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Otras opciones de creación" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX solicitud" description="Formato 1,03 o 2,2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX respuesta" description="Formato 1,03 o 2,2" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
---
title: Crear OFX archivo de respuesta a través de C#
description: Código de muestra para la creación de OFX archivos de respuesta. Use API código de ejemplo para la generación de archivos de respuesta por lotes en OFX aplicaciones basadas en .NET. 
url: /es/net/create/ofx-response/
family: finance
platformtag: net
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Crear OFX archivos de respuesta a través de C#" h2="OFX creación de archivos de respuesta sin necesidad de Microsoft Office instalado ni ningún otro software." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Cómo crear OFX archivos de respuesta" %}}

Siga los pasos en el fragmento de código o mejore según sus necesidades de aplicación después de tener los requisitos de creación dentro de su aplicación.

1. Crear [OfxResponseDocument clase](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) Objeto.1. Asigne las propiedades relevantes utilizando diferentes clases proporcionadas por API como [SignonResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [EstadosRespuesta de la transacción](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse), [Declaración Transacción](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction)1. Utilice la versión ofxVersion V2x o V1x para archivos xml y sgml respectivamente de [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) Como parámetro en el método Save.1. Llama al [Save (método)](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument/methods/save) Proporcionando el archivo de destino y ofxVersion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisito de creación" %}}
Para continuar con la creación de OFX archivos de respuesta, .NET Finance API es el principal requisito para ser incluido en la aplicación de generación de informes. 
- Instálelo a través de la línea de comandos como ''nuget install Aspose.Finance'' o a través de la consola de Package Manager de Visual Studio con ''Install-Package Aspose.Finance'' '.
- Alternativamente, obtenga el instalador MSI sin conexión o DLL en un archivo ZIP desde [Descargas](https://downloads.aspose.com/finance/net)...{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# código para OFX creación de archivos de respuesta" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Otras opciones de creación" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX Archivo de solicitud" description="Formato 1,03 o 2,2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL Archivo" description="Lenguaje extensible de informes empresariales" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
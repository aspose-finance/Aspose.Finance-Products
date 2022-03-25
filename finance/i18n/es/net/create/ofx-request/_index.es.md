---
title: Crear OFX archivo de solicitud a través de C#
description: Código de muestra para OFX creación de archivos de solicitud. Use API código de ejemplo para la generación de archivos de solicitud por lotes en OFX aplicaciones basadas en .NET. 
url: /es/net/create/ofx-request/
family: finance
platformtag: net
feature: create
informat: OFX Request
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Crear OFX Solicitar archivos a través de C#" h2="OFX solicitar la creación de archivos sin necesidad de Microsoft Office instalado ni ningún otro software." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Cómo crear OFX archivos de solicitud" %}}

Después de tener los OFX requisitos de creación de archivos de solicitud dentro de su aplicación, siga los pasos en el fragmento de código o mejore según sus necesidades.

1. Crear [OfxRequestDocument (clase)](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) Objeto.1. Asigne las propiedades relevantes utilizando diferentes clases proporcionadas por API como [Solicitud de señal](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [Institución financiera](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution), [Solicitud de transacción](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest)1. Utilice la versión ofxVersion V2x o V1x para archivos xml y sgml respectivamente de [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) Como parámetro en el método Save.1. Llama al [Save (método)](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument/methods/save) Proporcionando el archivo de destino y ofxVersion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisito de creación" %}}
Para proceder con OFX Solicitud de creación de archivos, .NET Finance API es el principal requisito para ser incluido en la aplicación de generación de informes. 
- Instálelo a través de la línea de comandos como ''nuget install Aspose.Finance'' o a través de la consola de Package Manager de Visual Studio con ''Install-Package Aspose.Finance'' '.
- Alternativamente, obtenga el instalador MSI sin conexión o DLL en un archivo ZIP desde [Descargas](https://downloads.aspose.com/finance/net)...{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# código para OFX creación de archivos de solicitud" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-request-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Otras opciones de creación" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX Archivo de respuesta" description="Formato 1,03 o 2,2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL Archivo" description="Lenguaje extensible de informes empresariales" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
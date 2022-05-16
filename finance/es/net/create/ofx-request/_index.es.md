---
title: Crear OFX archivo de solicitud a través de C#
description: Código de muestra para la creación del archivo de solicitud OFX. Utilice el código de ejemplo API para la generación de archivos de solicitud por lotes OFX dentro de las aplicaciones basadas en .NET. 
url: /es/net/create/ofx-request/
family: finance
platformtag: net
feature: create
informat: OFX Request
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Crear OFX archivos de solicitud a través de C#" h2="OFX solicitar la creación de archivos sin necesidad de tener instalado Microsoft Office ni ningún otro software." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Cómo crear OFX archivos de solicitud" %}}

Después de tener los OFX requisitos de creación de archivos de solicitud dentro de su aplicación, siga los pasos en el fragmento de código o mejórelo según sus requisitos.

1. Crear [Clase OfxRequestDocumentOfxRequestDocument class](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) objeto.1. Asigne las propiedades relevantes usando diferentes clases proporcionadas por API como [Solicitud de inicio de sesión](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [Institución financiera](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution), [DeclaraciónTransacciónSolicitud](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest)1. Use ofxVersion V2x o V1x para archivos xml y sgml respectivamente desde [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) como parámetro en el método Guardar.1. Llama a [Guardar método](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument/methods/save) proporcionando el archivo de destino y ofxVersion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisito de creación" %}}
Para continuar con la creación del archivo de solicitud OFX, .NET Finance API es el requisito principal que debe incluirse en la aplicación de generación de informes. 
- Instálelo a través de la línea de comandos como ```nuget install Aspose.Finance``` o a través de la Consola del administrador de paquetes de Visual Studio con ```Install-Package Aspose.Finance```.
- Alternativamente, obtenga el instalador MSI fuera de línea o las DLL en un archivo ZIP de [descargas](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# código para la creación de OFX archivos de solicitud" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-request-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Otras opciones de creación" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX archivo de respuesta" description="Formato 1.03 o 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL archivo" description="Lenguaje extensible de informes comerciales" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
---
title: Convertir informes financieros a través de .NET
url: /es/net/conversion/
description:  C# código para convertir los informes financieros en XBRL, iXBRL y OFX fomats de archivos a través de .NET biblioteca.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convertir archivos de informes financieros a través de C#" h2="La conversión de formatos de informes financieros incluye XBRL, iXBRL y OFX archivos de formato 1,03 a 2,2 dentro de las aplicaciones basadas en .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) Es una característica rica, extensible y fácil de usar API. Los desarrolladores pueden validar fácilmente XBRL instancias, bases de vínculos y esquemas de taxonomía mediante [Validar () método](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) Que debe cumplir con los requisitos de sintaxis impuestos en la especificación. Además, pueden leer XBRL, iXBRL formatos, así como crear XBRL instancias desde cero. Además, pueden ** convertir XBRL formato ** a iXBRL y archivos XLSX de Microsoft Excel. API también admite la creación de solicitud/respuesta de formato de intercambio financiero abierto (OFX) y convierte OFX solicitud/respuesta de archivo de formato 1,03 a 2,2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Convertir OFX archivos de respuesta y solicitud" %}}

API admite la creación de OFX archivos de solicitud y respuesta al proporcionar dos clases. [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) Para crear y cargar OFX archivos de solicitud en formato 1,03 y 2,2 y [OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) Para OFX archivos de respuesta en formato 1,03 y 2,2. Además, [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) Enumeración que tiene miembros V1x que es la versión 1.x, formato de archivo sgml y versión V2x 2.x, formato de archivo xml. Después de llamar al método Save de la clase OfxRequestDocument o OfxResponseDocument, los desarrolladores pueden convertir fácilmente de un archivo 1,03 sgml a un formato de 2,2 xml.


{{% blocks/products/pf/feature-page-code h3="C# código para convertir OFX archivos de respuesta" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-response-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# código para convertir OFX archivos de solicitud" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-request-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL Conversión de Informes Financieros" %}}

API admite la conversión de XBRL archivos a iXBRL y Microsoft®Excel XLSX formato El proceso de conversión es simple, primero carga el archivo a través [Clase XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument)... Usa el [Clase SaveOptions](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions) Para [Formato de ahorro](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions/properties/saveformat), Que se utilizará como parámetro en el método Save de XbrlDocument Class. Para guardar en archivo iXBLR, [SaveFormat! IXBRL](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveformat) Se utilizará y para exportar a formato XLSX, se utilizará SaveFormat.XLSX.

{{% blocks/products/pf/feature-page-code h3="C# código para exportar XBRL a iXBRL" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-ixbrl.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# código para la conversión de XBRL a XLSX" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-xlsx.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}
---
title: Convertir informes financieros a través de .NET
url: /es/net/conversion/
description:  Código C# para convertir informes financieros en formatos de archivo XBRL, iXBRL(inline xbrl) y OFX a través de la biblioteca .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convertir archivos de informes financieros a través de C#" h2="Conversión de formatos de informes financieros, incluidos los archivos XBRL, iXBRL y OFX del formato 1.03 al 2.2 dentro de las aplicaciones basadas en .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) es una característica rica, extensible y fácil de usar API. Los desarrolladores pueden validar fácilmente XBRL instancias, bases de enlaces y esquemas de taxonomía mediante [método validar()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) que debe cumplir con los requisitos de sintaxis impuestos en la especificación. Además, pueden leer formatos XBRL, iXBRL y crear instancias XBRL desde cero. Además, pueden **convertir el formato XBRL** a iXBRL y archivos XLSX de Microsoft Excel. API también admite la creación de solicitudes/respuestas en formato de intercambio financiero abierto (OFX) y convierte la solicitud/respuesta de archivos OFX del formato 1.03 al 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Convertir OFX archivos de respuesta y solicitud" %}}

API admite la creación de OFX archivos de solicitud y respuesta proporcionando dos clases. [OfxSolicitudDocumento](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) para crear y cargar OFX archivos de solicitud en formato 1.03 y 2.2 y [OfxRespuestaDocumento](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) para OFX archivos de respuesta en formato 1.03 y 2.2. Además, [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) Enumeración que tiene miembros V1x que es la versión 1.x, formato de archivo sgml y V2x versión 2.x, formato de archivo xml. Después de llamar al método Guardar de la clase OfxRequestDocument o la clase OfxResponseDocument, los desarrolladores pueden convertir fácilmente un archivo sgml 1.03 a un formato xml 2.2.


{{% blocks/products/pf/feature-page-code h3="C# código para convertir OFX archivos de respuesta" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-response-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Código para convertir OFX archivos de solicitud" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-request-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL Conversión de informes financieros" %}}

API admite la conversión de archivos XBRL a iXBRL y al formato Microsoft® Excel XLSX. El proceso de conversión es simple, primero cargue el archivo a través de [Clase XbrlDocumentXbrlDocument Class](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument). Utilizar el [clase GuardarOpciones](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions) por [Guardar formato](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions/properties/saveformat), para ser utilizado como parámetro en el método Guardar de la clase XbrlDocument. Para guardar en un archivo iXBLR, [GuardarFormato.IXBRL](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveformat) se utilizará y para exportar a formato XLSX, se utilizará SaveFormat.XLSX.

{{% blocks/products/pf/feature-page-code h3="C# Código para exportar XBRL a iXBRL" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-ixbrl.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Código para XBRL a XLSX Conversión" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-xlsx.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}
{{< /blocks/products/pf/feature-page-wrap >}}
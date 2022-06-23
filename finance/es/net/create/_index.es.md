---
title: Crear informes financieros a través de .NET
url: /es/net/create/
description:  Código C# para crear informes financieros en XBRL y OFX archivos de solicitud o respuesta a través de la biblioteca .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Crear archivos de informes financieros a través de C#" h2="Creación de formatos de informes financieros, incluido el archivo de solicitud o respuesta XBRL y OFX en formato 1.03 o 2.2 dentro de las aplicaciones basadas en .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) es una función rica en funciones, ampliable y fácil de usar para la creación y el procesamiento de informes financieros API. Los desarrolladores pueden crear fácilmente una instancia de XBRL desde cero, así como agregar una referencia de esquema, contexto, unidad, elemento, enlace de nota al pie, referencia de función y 
referencia de rol de arco. API proporciona una clase relevante para cada función, como el contexto, que los desarrolladores pueden usar [Período de contexto](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextperiod), [Entidad de contexto](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextentity) y [Contexto](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context). 
Además, API también admite la creación de solicitudes/respuestas en formato de intercambio financiero abierto (OFX) en formato 1.03 o 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Crear archivo XBRL agregando elemento" %}}

Para crear el archivo XBRL y agregar elementos al documento, el proceso es crear [Clase XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) instancia. Prepare la configuración relevante para el elemento mediante el uso de clases API adecuadas, como [Clase de referencia de esquema](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemaref)clases de contexto relevantes como se mencionó anteriormente y [clase de concepto](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/concept). Finalmente definir e inicializar [clase de artículo](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/item) propiedades, así como llamar a la [Guardar método](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) a [crear XBRL](https://products.aspose.com/finance/net/create/xbrl/) archivo en el disco.

{{% blocks/products/pf/feature-page-code h3="Código C# para crear un archivo XBRL agregando un elemento" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-item.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Crear OFX archivos de solicitud y respuesta" %}}


Para generar archivos OFX, API proporciona [OfxSolicitudDocumento](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) y [OfxRespuestaDocumento](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) las clases y los desarrolladores pueden fácilmente [crear OFX solicitud](https://products.aspose.com/finance/net/create/ofx-request/) y archivos de respuesta en formatos 1.03 y 2.2. Para inicializar las propiedades de OfxRequestDocument, API también proporciona otras clases como [Solicitud de inicio de sesión](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [Institución financiera](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution) y [DeclaraciónTransacciónSolicitud](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest) clases Del mismo modo, para inicializar las propiedades de OfxResponseDocument, API proporciona clases de apoyo como [Iniciar sesiónRespuesta](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [DeclaraciónTransacciónRespuesta](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse) y [DeclaraciónTransacción](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction). A continuación se encuentran los fragmentos de código para ambos casos con el uso de clases apropiadas relevantes.

{{% blocks/products/pf/feature-page-code h3="C# Código para generar OFX documentos de solicitud" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Código para generar OFX documentos de respuesta" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
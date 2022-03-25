---
title: Crear informes financieros a través de .NET
url: /es/net/create/
description:  C# código para crear Financial Reports en XBRL, y OFX archivos de solicitud o respuesta a través de .NET biblioteca.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Crear archivos de Financial Reporting a través de C#" h2="La creación de formatos de informes financieros incluye XBRL y OFX archivo de solicitud o respuesta en formato 1,03 o 2,2 dentro de .NET aplicaciones basadas." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) Es una característica rica, extensible y fácil de usar de creación y procesamiento de informes financieros API. Los desarrolladores pueden crear fácilmente XBRL instancia desde cero, así como agregar referencia de esquema, contexto, unidad, elemento, enlace de nota al pie, referencia de rol y 
Referencia de rol de arco. API proporciona una clase relevante para cada función, como para el contexto, los desarrolladores pueden usar [Período de contexto](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextperiod), [ContextoEntidad](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextentity) Y [Contexto](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context)... 
Además, API también admite la creación de solicitud/respuesta de formato de intercambio financiero abierto (OFX) en formato 1,03 o 2,2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Crear XBRL archivo mediante la adición de elemento" %}}

Para crear XBRL archivo y agregar elemento al documento, el proceso es, crear [Clase XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Instancia. Preparar la configuración relevante para el elemento utilizando API clases apropiadas como [Clase SchemaRef](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemaref), Clases de contexto relevantes como se mencionó anteriormente y [Clase concepto](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/concept)... Finalmente definir e intializar [Clase de artículo](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/item) Propiedades así como llamar a la [Save (método)](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) A [Crear XBRL](https://products.aspose.com/finance/net/create/xbrl/) Archivo en el disco.

{{% blocks/products/pf/feature-page-code h3="C# código para crear XBRL archivo agregando elemento" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-item.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Crear OFX archivos de solicitud y respuesta" %}}


Para generar OFX archivos, el API proporciona [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) Y [OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) Clases y desarrolladores pueden fácilmente [Crear OFX solicitud](https://products.aspose.com/finance/net/create/ofx-request/) Y archivos de respuesta en los formatos 1,03 y 2,2. Para inicializar las propiedades de OfxRequestDocument, API también proporciona otras clases como [Solicitud de señal](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [Institución financiera](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution) Y [Solicitud de transacción](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest) Clases. De manera similar, para intializar las propiedades de OfxResponseDocument, API proporciona clases de apoyo como [SignonResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [EstadosRespuesta de la transacción](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse) Y [Declaración Transacción](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction)... A continuación se muestran los fragmentos de código para ambos casos con el uso de clases apropiadas relevantes.

{{% blocks/products/pf/feature-page-code h3="C# código para generar OFX documentos de solicitud" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# código para generar OFX documentos de respuesta" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
---
title: Crear informes financieros a través de Python
url: /es/python-net/create/
description:  Código Python para crear informes financieros en XBRL y OFX archivos de solicitud o respuesta a través de la biblioteca Python.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Crear archivos de informes financieros a través de Python" h2="Creación de formatos de informes financieros, incluido el archivo de solicitud o respuesta XBRL y OFX en formato 1.03 o 2.2 dentro de las aplicaciones basadas en Python." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance para Python a través de .NET](https://products.aspose.com/finance/python-net/) es una función rica en funciones, ampliable y fácil de usar para la creación y el procesamiento de informes financieros API. Los desarrolladores pueden crear fácilmente una instancia de XBRL desde cero, así como agregar una referencia de esquema, contexto, unidad, elemento, enlace de nota al pie, referencia de función y 
referencia de rol de arco. API proporciona una clase relevante para cada función, como contexto, los desarrolladores pueden usar ContextPeriod, ContextEntity y Context. 
Además, API también admite la creación de solicitudes/respuestas en formato de intercambio financiero abierto (OFX) en formato 1.03 o 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Crear archivo XBRL agregando elemento" %}}

Para crear el archivo XBRL y agregar elementos al documento, el proceso es crear una instancia de clase XbrlDocument. Prepare la configuración relevante para el elemento mediante el uso de clases API apropiadas, como la clase SchemaRef, las clases de contexto relevantes como se mencionó anteriormente y la clase Concept. Finalmente, defina e inicialice las propiedades de la clase Item y llame al método save para crear el archivo XBRL en el disco.

{{% blocks/products/pf/feature-page-code h3="Código Python para crear un archivo XBRL agregando un elemento" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-xbrl-file-and-add-item.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Crear OFX archivos de solicitud y respuesta" %}}


Para generar archivos OFX, API proporciona clases OfxRequestDocument y OfxResponseDocument y los desarrolladores pueden fácilmente [crear OFX solicitud](https://products.aspose.com/finance/python-net/create/ofx-request/) y archivos de respuesta en formatos 1.03 y 2.2. Para inicializar las propiedades de OfxRequestDocument, API también proporciona otras clases, como las clases SignonRequest, FinancialInstitution y StatementTransactionRequest. De manera similar, para inicializar las propiedades de OfxResponseDocument, API proporciona clases de apoyo como SignonResponse, StatementTransactionResponse y StatementTransaction. A continuación se encuentran los fragmentos de código para ambos casos con el uso de clases apropiadas relevantes.

{{% blocks/products/pf/feature-page-code h3="Python Código para generar OFX documentos de solicitud" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Código para generar OFX documentos de respuesta" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< /blocks/products/pf/feature-page-wrap >}}
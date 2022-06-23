---
title: Convertir informes financieros a través de Python
url: /es/python-net/conversion/
description:  Código Python para convertir informes financieros en formatos de archivo XBRL, iXBRL(inline xbrl) y OFX a través de la biblioteca Python.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convertir archivos de informes financieros a través de Python" h2="Conversión de formatos de informes financieros, incluidos los archivos XBRL, iXBRL y OFX del formato 1.03 al 2.2 dentro de las aplicaciones basadas en Python." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance para Python a través de .NET](https://products.aspose.com/finance/python-net/) es una característica rica, extensible y fácil de usar API. Los desarrolladores pueden validar fácilmente XBRL instancias, bases de enlaces y esquemas de taxonomía mediante el método de validación () que debe cumplir con los requisitos de sintaxis impuestos en la especificación. Además, pueden leer formatos XBRL, iXBRL y crear instancias XBRL desde cero. Además, pueden **convertir el formato XBRL** a iXBRL y archivos XLSX de Microsoft Excel. API también admite la creación de solicitudes/respuestas en formato de intercambio financiero abierto (OFX) y convierte la solicitud/respuesta de archivos OFX del formato 1.03 al 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Convertir OFX archivos de respuesta y solicitud" %}}

API admite la creación de OFX archivos de solicitud y respuesta proporcionando dos clases. OfxRequestDocument para crear y cargar OFX archivos de solicitud en formato 1.03 y 2.2 y OfxResponseDocument para OFX archivos de respuesta en formato 1.03 y 2.2. Además, OfxVersionEnum Enumeration tiene miembros V1x que es la versión 1.x, formato de archivo sgml y V2x versión 2.x, formato de archivo xml. Después de llamar al método de guardado de la clase OfxRequestDocument o la clase OfxResponseDocument, los desarrolladores pueden convertir fácilmente un archivo sgml 1.03 a un formato xml 2.2.


{{% blocks/products/pf/feature-page-code h3="C# código para convertir OFX archivos de respuesta" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-ofx-response-from-1.03-to-2.2.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Código para convertir OFX archivos de solicitud" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-ofx-request-from-1.03-to-2.2.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL Conversión de informes financieros" %}}

API admite la conversión de archivos XBRL a iXBRL y al formato Microsoft® Excel XLSX. El proceso de conversión es simple, primero cargue el archivo a través de XbrlDocument Class. Utilice la clase SaveOptions para SaveFormat, que se utilizará como parámetro en el método de guardado de la clase XbrlDocument. Para guardar en un archivo iXBLR, se usará SaveFormat.IXBRL y para exportar a formato XLSX, se usará SaveFormat.XLSX.

{{% blocks/products/pf/feature-page-code h3="Python Código para exportar XBRL a iXBRL" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-xbrl-to-ixbrl.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Código para XBRL a XLSX Conversión" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-xbrl-to-xlsx.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}
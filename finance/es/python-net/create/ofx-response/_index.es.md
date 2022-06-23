---
title: Crear OFX archivo de respuesta a través de Python
description: Código de muestra para la creación del archivo de respuesta OFX. Utilice el código de ejemplo API para la generación de archivos de respuesta por lotes OFX dentro de las aplicaciones basadas en Python. 
url: /es/python-net/create/ofx-response/
family: finance
platformtag: python
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Crear OFX archivos de respuesta a través de Python" h2="OFX creación de archivos de respuesta sin necesidad de tener instalado Microsoft Office ni ningún otro software." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Cómo crear OFX archivos de respuesta" %}}

Siga los pasos en el fragmento de código o mejórelo según las necesidades de su aplicación después de tener los requisitos de creación dentro de su aplicación.

1. Crear objeto de clase OfxResponseDocument.1. Asigne las propiedades relevantes usando diferentes clases proporcionadas por API como SignonResponse, StatementTransactionResponse, StatementTransaction1. Utilice ofxVersion V2x o V1x para archivos xml y sgml respectivamente de OfxVersionEnum como parámetro en el método de guardado.1. Llame al método save proporcionando el archivo de destino y ofxVersion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisito de creación" %}}
Para continuar con la creación del archivo de respuesta OFX, asegúrese de cumplir con los siguientes requisitos previos. 
- Sistema operativo basado en Microsoft Windows o Linux.- Python 3.5 o posterior.- Aspose.Finance para Python a los que se hace referencia en su proyecto.{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python código para la creación de OFX archivos de respuesta" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Otras opciones de creación" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-request/" name="OFX Solicitar archivo" description="Formato 1.03 o 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/xbrl/" name="XBRL Archivo" description="Lenguaje extensible de informes comerciales" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
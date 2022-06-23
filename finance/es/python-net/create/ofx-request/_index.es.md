---
title: Crear OFX archivo de solicitud a través de Python
description: Código de muestra para la creación del archivo de solicitud OFX. Utilice el código de ejemplo API para la generación de archivos de solicitud por lotes OFX dentro de las aplicaciones basadas en Python. 
url: /es/python-net/create/ofx-request/
family: finance
platformtag: python
feature: create
informat: OFX Request
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Crear OFX archivos de solicitud a través de Python" h2="OFX solicitar la creación de archivos sin necesidad de tener instalado Microsoft Office ni ningún otro software." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Cómo crear OFX archivos de solicitud" %}}

Después de tener los OFX requisitos de creación de archivos de solicitud dentro de su aplicación, siga los pasos en el fragmento de código o mejórelo según sus requisitos.

1. Crear objeto de clase OfxRequestDocument.2. Asigne las propiedades relevantes usando diferentes clases proporcionadas por API como SignonRequest, FinancialInstitution], StatementTransactionRequest
3. Use ofxVersion V2x o V1x para archivos xml y sgml respectivamente de OfxVersionEnum como parámetro en el método Guardar.
4. Llame al método de guardar proporcionando el archivo de destino y ofxVersion.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisito de creación" %}}
Para continuar con la creación del archivo de solicitud OFX, asegúrese de cumplir con los siguientes requisitos previos. 
- Sistema operativo basado en Microsoft Windows o Linux.- Python 3.5 o posterior.- Aspose.Finance para Python a los que se hace referencia en su proyecto.{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python código para la creación de OFX archivos de solicitud" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-request-files.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Otras opciones de creación" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-response/" name="OFX archivo de respuesta" description="Formato 1.03 o 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/xbrl/" name="XBRL Archivo" description="Lenguaje extensible de informes comerciales" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
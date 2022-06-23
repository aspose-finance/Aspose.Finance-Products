---
title: Crear XBRL archivo a través de Python
description: Código de ejemplo para la creación de archivos XBRL. Utilice el código de ejemplo API para la generación de archivos por lotes XBRL dentro de las aplicaciones basadas en Python. 
url: /es/python-net/create/xbrl/
family: finance
platformtag: python
feature: create
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Crear XBRL archivos a través de Python" h2="Creación de XBRL archivos sin necesidad de tener Microsoft Office instalado ni ningún otro software." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Cómo crear archivos XBRL" %}}

Siga los pasos del fragmento de código o mejórelo según las necesidades de su aplicación para generar archivos extensibles de lenguaje de informes empresariales XBRL. Asegúrese de tener requisitos de creación dentro de su aplicación.

1. Crear instancia de clase XbrlDocument.1. Para crear un nuevo documento de instancia XBRL XbrlInstanceCollection y XbrlInstance.1. Agregar referencia de esquema usando SchemaRefCollection1. Dependiendo de la naturaleza de la aplicación, agregue contexto, unidad, elemento, enlace de nota al pie y más.1. Llame al método de guardado proporcionando la ruta del archivo de destino.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisito de creación" %}}
Para continuar con la generación de documentos XBRL, asegúrese de tener los siguientes requisitos previos. 
- Sistema operativo basado en Microsoft Windows o Linux.- Python 3.5 o posterior.- Aspose.Finance para Python a los que se hace referencia en su proyecto.{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python código para la creación de XBRL archivos" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-xbrl-file-and-add-schema-reference.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Otras opciones de creación" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-request/" name="OFX solicitud" description="Formato 1.03 o 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-response/" name="OFX Respuesta" description="Formato 1.03 o 2.2" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
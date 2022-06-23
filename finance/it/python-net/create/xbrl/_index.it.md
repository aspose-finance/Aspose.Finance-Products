---
title: Crea file XBRL tramite Python
description: Codice di esempio per la creazione di file XBRL. Utilizza API codice di esempio per la generazione di file batch XBRL all'interno di applicazioni basate su Python. 
url: /it/python-net/create/xbrl/
family: finance
platformtag: python
feature: create
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Crea XBRL file tramite Python" h2="XBRL creazione di file senza la necessità di installare Microsoft Office o qualsiasi altro software." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Come creare XBRL file" %}}

Segui i passaggi nello snippet di codice o miglioralo in base alle esigenze della tua applicazione per generare file XBRL estensibili del linguaggio di reporting aziendale. Assicurati di avere requisiti di creazione all'interno della tua applicazione.

1. Crea un'istanza di classe XbrlDocument.1. Per creare un nuovo documento di istanza XBRL XbrlInstanceCollection e XbrlInstance.1. Aggiungi un riferimento allo schema usando SchemaRefCollection1. A seconda della natura dell'applicazione, aggiungi contesto, unità, elemento, collegamento a piè di pagina e altro ancora.1. Chiama il metodo di salvataggio fornendo il percorso del file di destinazione.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisito di creazione" %}}
Per procedere con la XBRL generazione dei documenti, assicurati di disporre dei seguenti prerequisiti. 
- Sistema operativo basato su Microsoft Windows o Linux.- Python 3.5 o successivo.- Aspose.Finance per Python a cui si fa riferimento nel tuo progetto.{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python codice per XBRL creazione di file" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-xbrl-file-and-add-schema-reference.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Altre opzioni di creazione" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-request/" name="OFX Richiesta" description="Formato 1.03 o 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-response/" name="OFX Risposta" description="Formato 1.03 o 2.2" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
---
title: Crea XBRL File tramite C#
description: Codice di esempio per la creazione di file XBRL. Utilizza API codice di esempio per la generazione di file batch XBRL all'interno di applicazioni basate su .NET. 
url: /it/net/create/xbrl/
family: finance
platformtag: net
feature: create
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Crea XBRL file tramite C#" h2="XBRL creazione di file senza bisogno di Microsoft Office installato o di qualsiasi altro software." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Come creare XBRL file" %}}

Segui i passaggi nello snippet di codice o miglioralo secondo le esigenze della tua applicazione per generare file XBRL in linguaggio di reporting aziendale estensibile. Assicurati di avere i requisiti di creazione all'interno della tua applicazione.

1. Crea [Classe XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Istanza.1. Per creare un nuovo documento di istanza XBRL [Collezione XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) E [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance).1. Aggiungi riferimento allo schema usando [SchemaRefCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection)1. A seconda della natura dell'applicazione aggiungere contesto, unità, elemento, link note a piè di pagina e altro.1. Chiama il [Metodo di salvataggio](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) Fornendo il percorso del file di destinazione.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisito di creazione" %}}
Per procedere per la generazione di XBRL documenti, .NET Finance API è il requisito principale da includere nell'applicazione. 
- Installalo tramite riga di comando come '''nugget install Aspose.Finance''' o tramite Package Manager Console di Visual Studio con ''Installa-Package Aspose.Finance'''.
- In alternativa, ottenere il programma di installazione MSI offline o le DLL in un file ZIP da [Download](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# codice per la creazione di XBRL file" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-schema-reference.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Altre opzioni di creazione" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX Richiesta" description="Formato 1.03 o 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX Risposta" description="Formato 1.03 o 2.2" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
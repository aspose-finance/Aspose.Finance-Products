---
title: Crea file XBRL tramite C#
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
{{< blocks/products/pf/i18n/feature-page-header h1="Crea XBRL file tramite C#" h2="XBRL creazione di file senza la necessità di installare Microsoft Office o qualsiasi altro software." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Come creare XBRL file" %}}

Segui i passaggi nello snippet di codice o miglioralo in base alle esigenze della tua applicazione per generare file XBRL del linguaggio di reporting aziendale estensibile. Assicurati di avere requisiti di creazione all'interno della tua applicazione.

1. Creare [Classe XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Esempio.1. Per creare un nuovo documento di istanza XBRL [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) e [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance).1. Aggiungi riferimento allo schema utilizzando [SchemaRefCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection)1. A seconda della natura dell'applicazione, aggiungi contesto, unità, elemento, collegamento a piè di pagina e altro ancora.1. Chiama il [Salva metodo](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) fornendo il percorso del file di destinazione.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisito di creazione" %}}
Per procedere con la XBRL generazione dei documenti, .NET Finance API è il requisito principale da includere nell'applicazione. 
- Installalo tramite riga di comando come ```nuget install Aspose.Finance``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Finance```.
- In alternativa, ottenere il programma di installazione MSI offline o le DLL in un file ZIP da [download](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# codice per XBRL creazione di file" offSpacer="" %}}

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
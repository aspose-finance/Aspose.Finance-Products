---
title: Crea OFX file di risposta tramite C#
description: Codice di esempio per la creazione del file di risposta OFX. Utilizza API codice di esempio per la generazione di file di risposta in batch OFX all'interno di applicazioni basate su .NET. 
url: /it/net/create/ofx-response/
family: finance
platformtag: net
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Crea OFX file di risposta tramite C#" h2="OFX creazione di file di risposta senza la necessità di installare Microsoft Office o qualsiasi altro software." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Come creare OFX file di risposta" %}}

Segui i passaggi nello snippet di codice o miglioralo in base alle esigenze dell'applicazione dopo aver soddisfatto i requisiti di creazione all'interno dell'applicazione.

1. Creare [Classe OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) oggetto.1. Assegna le proprietà pertinenti utilizzando diverse classi fornite da API like [SignonResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [StatementTransactionResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse), [DichiarazioneTransazione](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction)1. Utilizzare ofxVersion V2x o V1x rispettivamente per i file xml e sgml da [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) come parametro nel metodo Save.1. Chiama il [Salva metodo](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument/methods/save) fornendo il file di destinazione e ofxVersion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisito di creazione" %}}
Per procedere con la OFXcreazione del file di risposta, .NET Finance API è il requisito principale da includere nell'applicazione di generazione dei rapporti. 
- Installalo tramite riga di comando come ```nuget install Aspose.Finance``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Finance```.
- In alternativa, ottenere il programma di installazione MSI offline o le DLL in un file ZIP da [download](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# codice per OFX creazione di file di risposta" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Altre opzioni di creazione" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX File di richiesta" description="Formato 1.03 o 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL File" description="Linguaggio di reporting aziendale estensibile" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
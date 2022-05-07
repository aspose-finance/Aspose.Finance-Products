---
title: Crea OFX file di richiesta tramite C#
description: Codice di esempio per OFX la creazione del file di richiesta. Utilizza API codice di esempio per la generazione di file di richiesta batch OFX all'interno di applicazioni basate su .NET. 
url: /it/net/create/ofx-request/
family: finance
platformtag: net
feature: create
informat: OFX Request
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Crea OFX file di richiesta tramite C#" h2="OFX richiedere la creazione di file senza che sia necessario installare Microsoft Office o qualsiasi altro software." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Come creare OFX file di richiesta" %}}

Dopo aver soddisfatto i OFXrequisiti per la creazione di file di richiesta all'interno della tua applicazione, segui i passaggi nello snippet di codice o miglioralo in base alle tue esigenze.

1. Creare [Classe OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) oggetto.1. Assegna le proprietà pertinenti utilizzando diverse classi fornite da API like [Richiesta di accesso](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [Istituzione finanziaria](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution), [DichiarazioneTransazioneRichiesta](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest)1. Utilizzare ofxVersion V2x o V1x rispettivamente per i file xml e sgml da [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) come parametro nel metodo Save.1. Chiama il [Salva metodo](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument/methods/save) fornendo il file di destinazione e ofxVersion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisito di creazione" %}}
Per procedere con la OFXcreazione del file di richiesta, .NET Finance API è il requisito principale da includere nell'applicazione di generazione dei rapporti. 
- Installalo tramite riga di comando come ```nuget install Aspose.Finance``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Finance```.
- In alternativa, ottenere il programma di installazione MSI offline o le DLL in un file ZIP da [download](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# codice per OFX creazione di file di richiesta" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-request-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Altre opzioni di creazione" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX File di risposta" description="Formato 1.03 o 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL File" description="Linguaggio di reporting aziendale estensibile" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
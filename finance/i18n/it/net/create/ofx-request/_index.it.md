---
title: Crea OFX file di richiesta tramite C#
description: Codice di esempio per la creazione di file di richiesta OFX. Utilizza API codice di esempio per la generazione di file di richiesta in batch OFX all'interno di applicazioni basate su .NET. 
url: /it/net/create/ofx-request/
family: finance
platformtag: net
feature: create
informat: OFX Request
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Crea OFX file di richiesta tramite C#" h2="OFX richiede la creazione di file senza bisogno di Microsoft Office installato o di qualsiasi altro software." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Come creare OFX file di richiesta" %}}

Dopo aver richiesto i OFX requisiti per la creazione di file nella tua applicazione, segui i passaggi nello snippet di codice o miglioralo a partire dalle tue esigenze.

1. Crea [Classe OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) Oggetto.1. Assegnare le proprietà pertinenti utilizzando classi diverse fornite da API come [Richiesta di firma](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [Istituzione finanziaria](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution), [StatementTransactionRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest)1. Utilizzare il ofxVersion V2x o V1x per i file xml e sgml rispettivamente da [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) Come parametro nel metodo Salva.1. Chiama il [Metodo di salvataggio](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument/methods/save) Fornendo il file di destinazione e ofxVersion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisito di creazione" %}}
Per procedere per la creazione di file di OFX richieste, .NET Finance API è il requisito principale da includere nell'applicazione di generazione di report. 
- Installalo tramite riga di comando come '''nugget install Aspose.Finance''' o tramite Package Manager Console di Visual Studio con ''Installa-Package Aspose.Finance'''.
- In alternativa, ottenere il programma di installazione MSI offline o le DLL in un file ZIP da [Download](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# codice per la creazione di OFX file di richiesta" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-request-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Altre opzioni di creazione" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX file di risposta" description="Formato 1.03 o 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="File XBRL" description="Linguaggio di segnalazione aziendale estensibile" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
---
title: Crea rapporti finanziari tramite .NET
url: /it/net/create/
description:  C# codice per creare rapporti finanziari in XBRL e OFX file di richiesta o risposta tramite la libreria .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Crea file di rendicontazione finanziaria tramite C#" h2="Creazione di formati di report finanziari inclusi XBRL e OFX file di richiesta o risposta in formato 1.03 o 2.2 all\'interno di applicazioni basate su .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) è una funzionalità ricca, estensibile e facile da usare per la creazione e l'elaborazione di report finanziari API. Gli sviluppatori possono creare facilmente XBRL istanza da zero, nonché aggiungere riferimenti a schemi, contesto, unità, elementi, collegamenti a piè di pagina, riferimenti a ruoli e 
riferimento al ruolo dell'arco. API fornisce una classe pertinente per ciascuna funzionalità, ad esempio per il contesto, che gli sviluppatori possono utilizzare [ContestoPeriodo](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextperiod), [ContestoEntità](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextentity) e [Contesto](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context). 
Inoltre, API supporta anche la creazione di richieste/risposte in formato Open Financial Exchange (OFX) nel formato 1.03 o 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Crea un file XBRL aggiungendo un elemento" %}}

Per creare un file XBRL e aggiungere un elemento al documento, il processo è creare [Classe XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) esempio. Prepara le impostazioni pertinenti per l'elemento utilizzando API classi appropriate come [Classe SchemaRef](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemaref)classi di contesto rilevanti come menzionato sopra e [Classe di concetto](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/concept). Infine definire e inizializzare [Classe dell'oggetto](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/item) proprietà così come chiamare il [Salva metodo](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) a [crea XBRL](https://products.aspose.com/finance/net/create/xbrl/) file su disco.

{{% blocks/products/pf/feature-page-code h3="C# Codice per creare XBRL file aggiungendo l\'elemento" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-item.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Crea OFX file di richiesta e risposta" %}}


Per la generazione di OFX file, API fornisce [Documento di richiesta Ofx](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) e [OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) classi e sviluppatori possono facilmente [crea OFX Richiesta](https://products.aspose.com/finance/net/create/ofx-request/) e File di risposta in entrambi i formati 1.03 e 2.2. Per inizializzare le proprietà OfxRequestDocument, API fornisce anche altre classi come [Richiesta di accesso](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [Istituzione finanziaria](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution) e [DichiarazioneTransazioneRichiesta](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest) classi. Allo stesso modo, per l'inizializzazione delle proprietà OfxResponseDocument, API fornisce classi di supporto come [SignonResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [StatementTransactionResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse) e [DichiarazioneTransazione](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction). Di seguito sono riportati i frammenti di codice per entrambi i casi con l'uso di classi appropriate pertinenti.

{{% blocks/products/pf/feature-page-code h3="C# Codice per generare OFX documenti di richiesta" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Codice per generare OFX documenti di risposta" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
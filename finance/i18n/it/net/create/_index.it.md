---
title: Crea rapporti finanziari tramite .NET
url: /it/net/create/
description:  C# codice per creare rapporti finanziari in XBRL e OFX file di richiesta o risposta tramite .NET libreria.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Creare file di reporting finanziario tramite C#" h2="Creazione di formati di report finanziari, inclusi XBRL e OFX file di richiesta o risposta in formato 1.03 o 2.2 all\'interno di applicazioni basate su .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) È una funzionalità ricca, estensibile e facile da usare creazione ed elaborazione di report finanziari API. Gli sviluppatori possono facilmente creare XBRL istanza da zero e aggiungere riferimento allo schema, contesto, unità, elemento, collegamento a piè di pagina, riferimento al ruolo e 
Riferimento al ruolo dell'arco. API fornisce una classe pertinente per ogni funzionalità, ad esempio per il contesto, che gli sviluppatori possono utilizzare [Periodo di contatto](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextperiod), [Contextità](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextentity) E [Contesto](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context). 
Inoltre, API supporta anche la creazione di richieste/risposte in formato open financial exchange (OFX) in formato 1.03 o 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Crea XBRL file aggiungendo un articolo" %}}

Per la creazione di XBRL file e l'aggiunta di elementi nel documento, il processo è, creare [Classe XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) L'istanza. Prepara le impostazioni pertinenti per l'articolo utilizzando API classi appropriate come [Classe SchemaRef](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemaref), Classi di contesto pertinenti come menzionato sopra e [Classe di concetto](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/concept). Infine definire e inzializzare [Classe articolo](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/item) Proprietà così come chiamare il [Metodo di salvataggio](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) A [Crea XBRL](https://products.aspose.com/finance/net/create/xbrl/) File nel disco.

{{% blocks/products/pf/feature-page-code h3="C# codice per creare XBRL file aggiungendo un articolo" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-item.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Crea OFX file di richiesta e risposta" %}}


Per la generazione di OFX file, il API fornisce [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) E [OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) Classi e sviluppatori possono facilmente [Crea OFX Richiesta](https://products.aspose.com/finance/net/create/ofx-request/) E file di risposta in entrambi i formati 1.03 e 2.2. Per inizializzare le proprietà OfxRequestDocument, API fornisce anche altre classi come [Richiesta di firma](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [Istituzione finanziaria](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution) E [StatementTransactionRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest) Lezioni. Allo stesso modo, per l'intializzazione delle proprietà OfxResponseDocument, API fornisce classi di supporto come [Segnaletica](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [Dichiarazione TransactionResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse) E [Dichiarazione di transazione](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction). Di seguito sono riportati gli snippet di codice per entrambi i casi con l'uso di classi appropriate pertinenti.

{{% blocks/products/pf/feature-page-code h3="C# codice per generare OFX documenti di richiesta" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# codice per generare OFX documenti di risposta" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
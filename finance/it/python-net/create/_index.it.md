---
title: Crea rapporti finanziari tramite Python
url: /it/python-net/create/
description:  Python codice per creare rapporti finanziari in XBRL e OFX file di richiesta o risposta tramite la libreria Python.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Crea file di rendicontazione finanziaria tramite Python" h2="Creazione di formati di report finanziari inclusi XBRL e OFX file di richiesta o risposta in formato 1.03 o 2.2 all\'interno di applicazioni basate su Python." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance per Python tramite .NET](https://products.aspose.com/finance/python-net/) è una funzionalità ricca, estensibile e facile da usare per la creazione e l'elaborazione di report finanziari API. Gli sviluppatori possono creare facilmente XBRL istanza da zero, nonché aggiungere riferimenti a schemi, contesto, unità, elementi, collegamenti a piè di pagina, riferimenti a ruoli e 
riferimento al ruolo dell'arco. API fornisce una classe pertinente per ciascuna funzionalità, ad esempio per il contesto, gli sviluppatori possono utilizzare ContextPeriod, ContextEntity e Context. 
Inoltre, API supporta anche la creazione di richieste/risposte in formato Open Financial Exchange (OFX) nel formato 1.03 o 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Crea un file XBRL aggiungendo un elemento" %}}

Per creare un file XBRL e aggiungere elementi al documento, il processo consiste nel creare un'istanza di classe XbrlDocument. Prepara le impostazioni pertinenti per l'elemento utilizzando le classi API appropriate come la classe SchemaRef, le classi di contesto pertinenti come menzionato sopra e la classe Concept. Infine definisci e inizializza le proprietà della classe Item e chiama il metodo save per creare il file XBRL su disco.

{{% blocks/products/pf/feature-page-code h3="Python Codice per creare XBRL file aggiungendo l\'elemento" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-xbrl-file-and-add-item.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Crea OFX file di richiesta e risposta" %}}


Per generare OFX file, API fornisce OfxRequestDocument e OfxResponseDocument e gli sviluppatori possono facilmente [crea OFX Richiesta](https://products.aspose.com/finance/python-net/create/ofx-request/) e File di risposta in entrambi i formati 1.03 e 2.2. Per inizializzare le proprietà OfxRequestDocument, API fornisce anche altre classi come SignonRequest, FinancialInstitution e StatementTransactionRequest. Allo stesso modo, per l'inizializzazione delle proprietà OfxResponseDocument, API fornisce classi di supporto come SignonResponse, StatementTransactionResponse e StatementTransaction. Di seguito sono riportati i frammenti di codice per entrambi i casi con l'uso di classi appropriate pertinenti.

{{% blocks/products/pf/feature-page-code h3="Python Codice per generare OFX documenti di richiesta" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Codice per generare OFX documenti di risposta" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}